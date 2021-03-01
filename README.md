# Timetable-import

NOTICE: The program runs in python 2.7, actually you can modify it in order to run in python 3.x. It is not difficult.

---
## How to use it
1. Enter your information of the classes into the file "classinfo.xlsx"
2. Modify the json file called "conf_classTime.json"
3. Run the file "excelReader.py", and the program will generate a json file called "conf_classInfo.json" if it runs successfully.
4. Run the file "main.py". The question "input 0 1 2 3 4 to set reminder method" is as follow:

>【0】不提醒
>
>【1】上课前 10 分钟提醒
>
>【2】上课前 30 分钟提醒
>
>【3】上课前 1 小时提醒
>
>【4】上课前 2 小时提醒
>
>【5】上课前 1 天

5. If "main.py" runs successfully, it will generate an ics file. You can use any method import it in your mobile phone/APP.

## How to import .ics into Outlook
https://support.microsoft.com/zh-cn/office/%E5%9C%A8-outlook-%E7%BD%91%E9%A1%B5%E7%89%88%E4%B8%AD%E5%AF%BC%E5%85%A5%E6%88%96%E8%AE%A2%E9%98%85%E6%97%A5%E5%8E%86-503ffaf6-7b86-44fe-8dd6-8099d95f38df

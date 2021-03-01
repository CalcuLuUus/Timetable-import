# Timetable-import

NOTICE: python 2.7

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

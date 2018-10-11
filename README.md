# Mysql_creat_table

根据当时时间，定时执行sql.py脚本，每月一号凌晨三点执行一次脚本，

crontab -e

0 3 1 * * /home/user/py35env/bin/python3 /home/user/桌面/sort/Functions/Common/sql.py

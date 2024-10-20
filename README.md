Mikrotik chr auto install Ubuntu vps -- version 18 or 20.4
نصب اتوماتیک میکروتیک کلاد روتر روی سرور مجازی 
دقت کنید فقط روی اوبونتو ۱۸ و ۲۰ کار میکنه این اسکریپت و روی اوبونتو خام با درایو بدون Swap قابل نصبه . 
بعد از اجرا اسکریپت ماشین مجازی خود را خاموش و روشن کنید فقط حواستون باشه یوزر ادمین و بدون رمز میباشد .

curl -fsSL https://github.com/asghar61/Mikrotik-chr-
install-script-/blob/main/install.sh | 

sudo bash install.sh 




shutdown manually from vps ui, then turn on it



Caution !!!
I already test anything to set password on boot, but it can't. so after vps turn on, you must be change the password and user. otherwise you know what will happen :)

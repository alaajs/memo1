
[كـيـفـيـه تـنـصـيـب سـورس ]) 
 
```sh

افتـح ترمنـــأل وخلي   

sudo apt-get update 
➖🔹➖🔹➖🔹➖🔹➖🔹
ورهأَ خلي  

redis-server
➖🔹➖🔹➖🔹➖🔹➖🔹
تركه مفتوح    
➖🔹➖🔹➖🔹➖🔹➖🔹
وفتح ترمنال ثاني وخلي    
➖🔹➖🔹➖🔹➖🔹➖🔹
ورهأ خلي    

sudo apt-get install libreadline-dev libconfig-dev libssl-dev lua5.2 liblua5.2-dev libevent-dev libjansson* libpython-dev make unzip git redis-server g++ -y --force-yes
➖🔹➖🔹➖🔹➖🔹➖🔹
ورأهأَ خلي  

git clone https://github.com/alaajs/memo1.git
➖🔹➖🔹➖🔹➖🔹➖🔹
ورهأ خلي    

cd BOSS
➖🔹➖🔹➖🔹➖🔹➖🔹
ورهأَ خلي 
➖🔹➖🔹➖🔹➖🔹➖🔹
chmod +x TH3BOSS.sh
➖🔹➖🔹➖🔹➖🔹➖🔹
ورهأَ خلي 

./TH3BOSS.sh install
➖🔹➖🔹➖🔹➖🔹➖🔹
ورهأَ خلي  

./TH3BOSS.sh 
➖🔹➖🔹➖🔹➖🔹➖🔹
*ملاحظه اذا يطلعلك حرف او  
يوكف بالتنصيب تطي امر y وانتر 
 ➖🔹➖🔹➖🔹➖🔹➖🔹
يطلب رقم خلي رقم البوت 
مبروك عليك افضل بوت عل تلي 

عندك استفسار او اي شي راسلني
@jgjgjgjgj
واذا محظور تعال على بوت التواصل
@jgjgjgjgjbot
قـنـاة الـسـورس
@memojs

 Enter a phone number & confirmation code.
Congratulations, you better bot
```
 One command
To install everything in one command (useful for VPS deployment) on Debian-based distros, use:

لتنصيب البوـب بكوَدَ واحد فقط َ   

فتح ترمنال وخلي   
➖🔹➖🔹➖🔹➖🔹➖🔹

sudo apt-get update 

➖🔹➖🔹➖🔹➖🔹➖🔹
ورهأَ خلي  

redis-server

➖🔹➖🔹➖🔹➖🔹➖🔹

تركه مفتوح   

وفتح ترمنال ثاني وخلي  


sudo apt-get install libreadline-dev libconfig-dev libssl-dev lua5.2 liblua5.2-dev libevent-dev libjansson* libpython-dev make unzip git redis-server g++ -y --force-yes && git clone https://github.com/alaajs/memo1.git && cd TH3BOSS && chmod +x TH3BOSS.sh && ./TH3BOSS.sh install && ./TH3BOSS.sh
```

➖🔹➖🔹➖🔹➖🔹➖🔹
يطلب رقم خلي رقم البوت 
مبروك عليك افضل بوت عل تلي 

 Enter a phone number & confirmation code.
Congratulations, you better bot

 Realm configuration

After you run the bot for first time, send it `!id`. Get your ID and stop the bot.

Open ./data/config.lua and add your ID to the "sudo_users" section in the following format:
 لتصبح مطور بوتك غير الايدي خاص كونفج بايديك 
```
  sudo_users = {
    266714448,
    0,
    YourID
  }
```

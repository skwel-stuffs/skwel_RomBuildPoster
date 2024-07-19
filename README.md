# skwel ROM Build Poster #


I created this script to automate tasks for building a custom ROM because I'm lazy. Essentially, it performs the following steps: **Build**, **Upload**, and **Notify Telegram**.



**Requirements:**


sudo apt-get install jq  # On Debian-based systems

sudo yum install jq      # On Red Hat-based systems


git clone https://github.com/skwel-stuffs/skwel_RomBuildBot.git . && chmod +x skwel_upload





Edit Config file: _config.json_ as follow:




**TOKEN:** <E.g asxxcasDASa100^& > // Use @BotFather to create a new Bot, name it whatever you want, and make sure to add the bot in your Group as admin. 

**CHAT_ID:** <E.g -123456789 > // Execute this command and retrieve the Chat Id: 

curl -s https://api.telegram.org/bot<TOKEN_ID>/getupdates



**MAINTAINER:** <E.g skwel> 

**ROM:** < E.g EverestOS >

**TARGET:** < E.g everest_topaz-userdebug >

**FILE_PATH:** < E.g out/target/product/topaz >

**BUILD_TYPE:** < E.g OFFICIAL/UNOFFICIAL>





**Usage:**

./skwel_upload

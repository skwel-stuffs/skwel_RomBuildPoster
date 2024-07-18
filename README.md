#####################################
# skwel ROM Build Poster #
#####################################

I created this script to automate tasks for building a custom ROM because I'm lazy. Essentially, it performs the following steps: **Build**, **Upload**, and **Notify Telegram**.



**Requirements:**


sudo apt-get install jq  # On Debian-based systems

sudo yum install jq      # On Red Hat-based systems


git clone https://github.com/skwel-stuffs/skwel_RomBuildBot.git . && chmod +x skwel_upload





Edit Config file: _config.json_ as follow:




**TOKEN:** <E.g asxxcasDASa100^& >

**CHAT_ID:** <E.g -123456789 >

**MAINTAINER:** <E.g skwel>

**ROM:** < E.g EverestOS >

**TARGET:** < E.g everest_topaz-userdebug >

**FILE_PATH:** < E.g out/target/product/topaz >

**BUILD_TYPE:** < E.g OFFICIAL/UNOFFICIAL>






**Usage:**

./skwel_upload

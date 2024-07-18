#####################################
# skwel ROM Build Poster #
#####################################

I created this script to automate tasks for building a custom ROM because I'm lazy. 

Requirements:

sudo apt-get install jq  # On Debian-based systems
sudo yum install jq      # On Red Hat-based systems

git clone https://github.com/skwel-stuffs/skwel_RomBuildBot.git . && chmod +x skwel_upload


Edit Comfig file: config.json as follow:


TOKEN: <E.g asxxcasDASa100^&>

CHAT_ID: >

MAINTAINER: <E.g skwel>

ROM: <E.g EverestOS>

TARGET: <E.g everest_topaz-userdebug>

FILE_PATH: <E.g out/target/product/topaz>

BUILD_TYPE: <E.g OFFICIAL/UNOFFICIAL>


Usage:

./skwel_upload

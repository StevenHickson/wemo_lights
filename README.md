This is a simple shell script for controlling Belkin WeMo light swtiches. This should work on any linux but was tested on Raspbian OS on the Raspberry Pi,
simply pull the github repository with:
git clone https://github.com/StevenHickson/wemo_lights.git

Then make it executable
chmod +x wemo
Then install it
sudo cp wemo /usr/local/bin/

Now you can control your lights with wemo commands. wemo LISTNAMES lists each device IP, port, and name.

# network.sh
only works on macOS
this is very basic, equivalent to turning wifi button on or off in network preferences. but this run this script just in case that doesn't work

use brew to install git if not already installed
command = brew install git

if you dont have brew, got to their website (full name is homebrew) - https://brew.sh and follow their instructions or search how to install it on youtube
after setting up all that, open your default terminal and write or copy paste the following commands- 
git clone https://github.com/shadows1003929/network.sh.git

I would recommend you to move the network_work.sh file to your user folder. Especially if you are gonna run it from terminal (best opton is to run from terminal, never tested the user interface method)

open finder and go to the network.sh folder
u can take the file named network_work.sh and move it back to your user directory (home directory) if u want to

OR,u can open a new terminal and copy paste these commands like this (do it line by line, one by one)-
cd network.sh 
sudo mv network_work.sh ~
<enter your login password>
cd ~
  
You can delete the folder named network.sh if you want to clear space
Terminal way -
sudo rm -rf network.sh
<Enter pasword>
  
 
And, your done
to test this out, open terminal again and type-
sh network.sh 

or just double click on your file in finder (not sure if this will work cause never tried it)

it will restart your network service and you will be disconnected and a few seconds later, you will reconnect to the internet.

If this doesn't work, check if your router is actually working and anyother device has internet connection
  
If this doesnt work, try restarting your macbook
  
  
Generally these issues fix themselves after a reboot.
  
Sometimes none of this might not work at all. I have had this happen to me twice. This automatic disconnection problem generally fixed itself in a few days or a week. 

This video has a more comprehensive troubleshooting measure. Make sure do the basic stuff first (restarting macbook or running my script) and then do higher level troubleshooting like this - 
https://www.youtube.com/watch?v=42oGuoGI9U4

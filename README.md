# i3

* apt-get install i3
* apt-get install xfce4-panel
* apt-get install rxvt-unicode
* apt-get install lxappearance
* apt install nm-applet
* apt install pnmixer
* apt install git
* apt-get update -y && apt-get upgrade -y && apt-get dist-upgrade -y
* reboot
* xfce4-pane
* add the config file to .config/i3/config
* mv config .config/i3/config
* xrdb .rxvt-unicode
* mv .Xdefault /userfolder/.Xdefault
* xrdb .Xdefaults
* xrdb .rxvt-unicode
* rxvt-unicode
* reboot
* xrdb .rxvt-unicode


*geckodirvers for selenium
*https://github.com/mozilla/geckodriver/releases
*export PATH=$PATH:/root/Downloads/geckodriver-v0.23.0-linux64



# xfce4-panel

xfce4-panel

### right click and add the application menu in the preferences.
### change the apperance of the xfce4-panel

vim .config/i3/config

### border size:

#no windows border:
new_window pixel 3

### change the following at the line: 
#start a terminal
uncommend the current terminal and add the one we want to use:

bindsym $mod+Return exec rxvt-unicode

### add the following:
#statup panel
exec --no-startup-id xfce4-panel --disable-wm-check

# Setting the bar at the top
# add following at the end (in between the bar brackets)
# under status command
		postion top
 
# close and save the file
### restart your terminal.
if it doesn't show the new terminal run the following
xrdb .rxvt-unicode

# to change the colors of the terminal
cd /home/
nano .Xdefaults

### fill in the xdefault file
xrdb .Xdefaults
if colors aren't picked up with a new terminal

notes:

windowstoets + shift + e
logout pop up.

windowstoests + pijltje switch naar andere pannel

windowstoests + h voor horizontaal uitlijning

windowstoets + enter voor nieuwe terminal

windowstoets + v voor verticale uitlijning

windowstoets + shift + pijltje swappen van pannels naar richting van de pijl.

windowstoets + shift + nummer voor switchen van item naar andere workspace

windwostoets + nummer voor switchen naar andere workspace.




# background
apt-get install feh

# open an image with feh
feh imagename.jpg

# set it as your background

cat .fehbg

nano .xinitrc

#add this in the file:
~/.fehbg

close and save.
on reboot your background will now be taken from the .fehbg file.

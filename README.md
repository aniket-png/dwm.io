# myfiles <br> <br>
This are my dwm files<br><br>
You could see all the pathches in the patch directory 
<br>
<br>

there are some steps for creating .dwm file and all that i hope u have done that <br> 
<br> & you are only here for some files
<br> <br> 
to install it <br> <br> 
git clone https://github.com/aniket-png/myfiles.git
<br> <br> then
<br> 
cd dmenu
<br> <br> sudo make install 
<br> <br> cd ..<br> 
cd dwm <br> <br> 
<br> <br> sudo make install
cd ..<br> <br> 
<br> <br> cd st
<br> <br> sudo make install
<br> <br> 
&You are done

for dwm blocks paste the scripts in local/bin
and give the path
export PATH=$HOME/bin:/usr/local/bin:$PATH
or wherever your local/bin scripts are
cd dwmblocks
sudo make install
then to give it a start
if you use a xintrc
or .dwm file or wherever your autostart file is there paste it
dwmblocks &

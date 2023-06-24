# myfiles <br> 
This are my dwm files<br>
You could see all the pathches in the patch directory 
<br>
there are some steps for creating .dwm file and all that i hope u have done that <br> 
<br> & you are only here for some file <br> 
to install it <br> 
git clone https://github.com/aniket-png/myfiles.git
<br>  then
<br> 
cd dmenu
<br> sudo make install 
<br>  cd ..<br> 
cd dwm  <br> 
<br>  sudo make install
cd ..<br>  
<br>  cd st
<br>  sudo make install
<br> 
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

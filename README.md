# myfiles
This are my dwm files
You could see all the pathches in the patch directory 

there are some steps for creating .dwm file and all that i hope u have done that 
& you are only here for some files

to install it 
git clone https://github.com/aniket-png/myfiles.git
then

cd dmenu
sudo make install 
cd ..
cd dwm
sudo make install
cd ..
cd st
sudo make install

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

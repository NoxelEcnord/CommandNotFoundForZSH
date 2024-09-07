# CommandNotFoundForZSH
add bash-like "command not found" fork for zsh
ASSUMPTIONS i mad and I assume the user meets the assumptions
*1. you have zsh installed and working(plus its your default login shell)
*2. you posses basic file handling skills 
*3. you have some basic conceots of a linux/unix/(any shell scripting language) . musnt be a pro. just  basic commands  to manouver around in a CLI environment
clone this repo "git clone https://github.com/NoxelEcnord/CommandNotFoundForZSH" 
find your home directory( by default when you open a terminal you are always in your default home shell.
 how to get home directory
   if youre using zsh the just do "echo $HOME" and the output should be something like "/home/your_usernamme_/" where your_username is the username of the active user that is if you have multiple user accounts 
   for windows it should be something like "C:\users\your_username" (not sure though it may vary )
get inside the home directory by "cd $HOME"
in home directory/folder theres a zsh configuration file caled .zshrc. it gets executed each time zsh is started. in that file we will add a few lines of instuctions telling zsh hoew to handle commands that are not in path($PATH).
to do that we will need a  text editor (i prefer vim,vi,neovim or nano) but any would do just good whichever youll choose. for windows notepad is just enough.
launch your editor .

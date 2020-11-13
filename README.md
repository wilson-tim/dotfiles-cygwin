My dot files for Cygwin + zsh on Windows.  
  
Installation per the following, many thanks:  
https://dev.to/zinox9/installing-zsh-on-windows-37em  
https://gist.github.com/dfontana/3e27ec5ea3a6f935b7322b580d3df318  
https://jimfrenette.com/2017/02/cygwin-oh-my-zsh-recipe  
  
Installed packages: zsh git gdb dos2unix openssh vim  
  
Updating:  
**cygwin packages** $ run the cygwin-setup-x86_64.exe file and check for updated packages  
**oh-my-zsh** $ omz update  
**powerlevel10k** $ git -C ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k pull  


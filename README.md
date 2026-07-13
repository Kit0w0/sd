sd is a simple tool to swap between saved directories on Linux systems.

## Installation
Download the bash script, sh. Place it in your PATH, and add the following alias to your .bashrc (or whatever equivilant there is for other shells):  
alias sd=". sd.sh"  

Note: this tool assumes that ~/.local/bin exists

## Usage
'sd .' will automatically save the current directory.  
'sd [dir]' will manually saved a specified directory, [dir]  
'sd' will go to the saved directory. If your current directory is the saved directory, instead go back to previous directory.  
'sd -b' will go to the previous directory regardless of current directory.  

## Options
-b, --back        go to previous directory  
-p, --print       print saved directory  
-h, --help        print this message  

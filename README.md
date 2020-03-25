# shortcut of gfortran compiler
gcom is bash script to compile fortran program in single time through the terminal. It works in Linux OS and Mac OS.
# How To Use?
Open your terminal and go to the directory where the fortran program saved and type:
```
gcom --input fortran_file
```
for example:
```
gcom --input helloworld.f95
```
gcom direct to execute the hellowrold.f95 through helloworld executable file
# How To Install gcom
1. Save the gcom's folder in folder that do you want (example: in packages's folder, /home/packages/gcom)
2. Open your .bashrc through terminal and type PATH=/home/packages/gcom:$PATH in the last line. 
3. Save your .bashrc and close the editor.
4. Type source .bashrc in terminal and press enter
5. To check gcom, type:
```
gcom --help or gcom -h
```
It will show:
# How To Use This?
```
gcom --input fortran_file
HELP: gcom --help or -h

To run this script, you have to install gfortran compiler.

The script is created by Aulia Khalqillah, S.Si (2019)
email : auliakhalqillah.mail@gmail.com
```
# NOTE
Before you install gcom, yo have to install gfortran compiler first. If you use Linux (Ubuntu), type:
```
sudo apt-get install gfortran
```
through terminal. If you use Mac Os, type:
```
brew install gfortran
```
through terminal

#Sublime Shlisp

This package adds Syntax Highlighting for the Shbobo Shnth's Shlisp language. For more information on Shlisp and Shnth, go to http://www.shbobo.net/

The syntax file includes a ready-to-use Sublime bundle, along with an AAAPackageDev YAML file for easy customization.

"Shlisp Syntax" is now up on Sublime Package Control. If you are new to Sublime Text, here are some instructions to get you started: 

##To install Shlisp the easy way
- 1) Install Package Control (https://sublime.wbond.net/) 
- 2) Hit ctrl+shift+p (on windows; use cmd+shift+p on OS X) to bring up the command palette on Sublime Text. 
- 3) Look for "Package Control: Install Package" 
- 4) Type in "Shlisp Syntax". Hit enter when you find it. It should install. 

##To use 
- 1) Open a file. Start with an existing sketch to make sure that it works. 
- 2) Bring up the command palette and type "Shlisp". It should bring up the option to change the current syntax to Shlisp. 

##Windows Build System

If you are on Windows or Linux, you can send sketches directly to your Shnth without needing to exit Sublime. 

- 1) Shlisp must be on your operating system's path. Google how to do this, as it's different on each platform. 
- 2) Open a file and make sure that the active syntax is Shlisp. 
- 3) In Sublime Text, select Tools from the file bar, then Build System. Set it to automatic. This will select an appropriate build system to each language that you use. 
- 4) Hit Ctrl+B to send the current file to your Shnth. 

I have an OS X computer, but haven't tested the build system on it yet. On Linux and Windows, the runtime is "shlisp," while on OS X, it's "shlisp.app". If you're on OS X, you'll probably need to remove the Linux "shlisp" from the path so that it doesn't execute that one on accident.

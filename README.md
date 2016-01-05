# GitConfigureOnWindows
Set up git workspace on Windows.


##Downloading necessary files


* Save *git-completion.bash* in your home directory with the name **git-completion.bash**.
* Save *git-prompt.sh* in your home directory with the name **git-prompt.sh**.
* Download **.bash_profile** .

If you already have a file in your home directory named *.bash_profile*, copy the content from downloaded *.bash_profile* and paste it at the bottom of *.bash_profile* **in your home directory**. Otherwise, move *.bash_profile* to your home directory and rename it to *.bash_profile*. 
##Making Git configurations

Run the following Git configuration commands. The first one will need to be modified if you are using a text editor other than Sublime, or if Sublime is installed in another location for you. See this page for the correct command for a couple of other popular text editors. For any other editor, you'll need to enter the command you use to launch that editor from Git Bash.

* _git config --global core.editor "'C:/Program Files/Sublime Text 2/sublime_text.exe' -n -w"_
* _git config --global push.default upstream_
* _git config --global merge.conflictstyle diff3_
* __Make sure you can start your editor from Git Bash.__

If you use Sublime 2, you can do this by adding the following line to your .bash_profile:

* _alias subl="C:/Program\ Files/Sublime\ Text\ 2/sublime_text.exe"_
##Restart Git Bash

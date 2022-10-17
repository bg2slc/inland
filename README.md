Inland - Helper Script for creating Makefiles

Bash script to facilitate creating simple makefiles and running projects in C++ and C#. Intended to be usable from the command prompt in vim/neovim.

Is there a better way to do this sort of thing? Probably. But this is my way.

INSTALL METHOD:
Recommended install method is to copy and paste the `inland` script file to either /usr/local/bin or $HOME/.bin. Ensure that it is executable, and then make sure that location is in your $PATH. You can do this by simply running the following commands:

mkdir $HOME/.bin
cp inland $HOME/.bin
cd $HOME/.bin
chmod +x inland

and then make sure "export $PATH=$PATH:$HOME/.bin" is added to your .bashrc file. This is intended to be a dumb script, and the only additional files that will be created are the Makefiles that it is used to create.

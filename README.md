
My Sublime Text configuration.

As a note to self, my routine for setting up a new install of Sublime 3:

On Linux:

    cd ~/.config/sublime-text-3/Packages

On Windows (Git bash):

    cd ~/AppData/Roaming/Sublime\ Text\ 3/Packages/

Then:

    rm -rf User
    git clone git@github.com:mtti/sublime.git User

Install [Package Control](https://packagecontrol.io/installation).

Using Package Control, install:

* Monokai Extended
* WordCount

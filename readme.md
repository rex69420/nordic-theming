This is a guide for setting up a linux environment, with nordic dark theming, nordic icons, dash to dock, nord-gnome-terminal, neofetch.

Let's get started!

First: - Get Gnome-tweak-tool by doing : -

sudo apt-get install gnome-tweak-tool

Then clone this repo by doing -
git clone

While that is happening, open up gnome extensions on a browser. Then install the browser extension by clicking on the pop up that comes up.

Then search up 2 extensions, Dash to Dock and User Themes to load shell themes from the user directory.

When that is done, go to your file manager and go to your home directory. Then do ctrl+h to see the hidden files. If you don't see .themes and .icons folders, then create them. Then copy the Nordic-darker-standard-buttons folder to .themes and then copy the Nordic-Darker and Nordic folder to .icons. After that is done open Tweaks, go to appearance and select the nordic-darker-standard-buttons in themes and nordic-icons in icons, and nordic in shell as well. While you're in there you can even configure your dash to dock.

Then, cd into the nord-gnome-terminal/src folder, and do ./nord.sh.

Then go to your settings and select the newly created nordic theme. Before restarting your terminal, do -

sudo apt install neofetch

then do -

sudo nano ~/.bashrc

scroll all the way down and then at the bottom of the file press enter and then add neofetch. Then do Ctrl+x, y and enter.

After that is done, do a quick restart and everything shold be the way you want it to be.

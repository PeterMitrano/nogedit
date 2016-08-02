# Do This

    git clone https://github.com/PeterMitrano/nogedit.git && cd nogedit && source install.sh

# What it does

Replaced gedit with gvim. Make sure you source ~/.bashrc in all their currently open shells for it to have the full effect. Fucks the unity desktop file and alias's the gedit command. Doesn't mess with the actual /usr/bin/gedit.

# Undoing it

Do you feel bad? Fine...

    sudo apt-get install --reinstall gedit
    #then remove the `alias gedit=gvim` from their ~/.bashrc

Weak.


# kde-ssh-agent

# check and load ssh-agent
To load the ssh agent when opening konsole put .bash_profile in your home folder. ~/.bash_profile

# load your key

put add-ssh.ssh in ~/.config/autostart-script/add-ssh.sh. This will save your password in the kde wallet and will unlock your ssh key on login. Don't forget to make it executable:
chmod a+x ~/.config/autostart-script/add-ssh.sh


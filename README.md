# DOCUMENTATION FOR STRESSFUL ERRORS I FIND WORTHY THAT THEIR FIXES SHOULD BE HERE
Important error fixes.


#### SSH CLONE ERROR:
##### Permission denied (publickey)
Generated and added an ssh key to the user/settings from my mac terminal.  pbcopy < ~/.ssh/id_rsa.pub copies the ssh key (Resources)[https://medium.com/modulr/clone-giltlab-repository-with-ssh-in-mac-os-5bc6a93bc43b]
        - -- Fix: used direct repository link instead of the given clone urls. i.e git clone ssh://git@[[main link on the url]].git

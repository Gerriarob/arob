# arob
Android rooting on Brunch Framework

arob doesnt work in Downloads anymore, as a workaround, create a folder in /usr/local and copy content from arob.zip in the new created folder. run the scripts from the /usr/local/new_created_folder.

arob v0.10 Beta state (android rooting on brunch)

Rooting scripts for Android on a Chrome OS installation with Brunch framework.

just make sure you have the developement options on your regular installation and enabled adb debuging.

be aware, rooting can destroy your Android Container and it could be you loss your complete data, to be secure, make a backup of all your data.

in case of an Chrome OS update or a powerwash, you have to reroot your Android container.


this Version is only tested on Intel CPU with Crome OS v80+ installed with Brunch framework. It could work on v76+ i dont know, if you rooted with this scripts Android v76+, let me know.

many thanks go to nolirium for the base of the scripts and the knowlege.
the scripts developement stoped in 2018 and the scripts where broken for the new Chrome OS installations, so i decide to figure it out and correct and rewrite the scripts. If nolirium have a problem with this, please contact me in telegram. (i have tried to contact you, but no answer replied from you).




First:

extract the arob-v0.10.zip in your Download folder, there are 2 folders, 2 scripts and 1 apk inside the zip file.

you must have in your Downloads folder:

x86
common
root.sh
selinux.sh
SuperSU-v2.82.apk
readme.md


Second:

a) open a terminal with 'ctrl + alt + t'
b) type in crosh 'shell'
c) type in the shell 'cd ~/Downloads'
d) get root with 'sudo su'
e) check script permission with 'ls -l' the scripts should be executeable, do this with 'chmod +x root.sh' and 'chmod +x selinux.sh


Third:

run the script root.sh with following command 'sh root.sh'

if no error occurs, reboot the machine.
if an error occurs, you can rerun the script.


Fourth:
a) open a terminal with 'ctrl + alt + t'
b) type in crosh 'shell'
c) type in the shell 'cd ~/Downloads'
d) get root with 'sudo su'
e) run the script selinux.sh with following command and watch the output, its interactive 'sh selinux.sh'


Fifth:

install SuperSU-v2.8.2.apk just by doubleklick it.





changelog:
v0.10
initial release

by Gerri

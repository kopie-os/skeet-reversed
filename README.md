# Information
- This is an older version that got reversed, not the latest. This is for CS:GO.
- Building it isn't easy.
- You require external libraries.

### Needed stuff
- You need to install ```wsn```.
- You need to install ```python```.
- You need to install ```wine```.
- You need to install a ```SQL viewer```
- ```DBVisualizer``` is needed.
- ```Kali Linux``` or ```Ubuntu``` is recommended.

### How to build the skeet loader
- Install ```wine``` binary or shell (x64 recommended)
- Open ```terminal``` and enter ```wine skeet.exe -d SQL -f```
- Wait until it builds
- CD into ```binary_skeet``` like this: ```cd binary_skeet```
- ```sudo apt get install WSSN2``` for cloud server you need a VPS.
- ```WSSN2 192.168.1.1 -f skeet.exe -d SQL -r``` set 192.168.1.1 to your server's API ip address. In this case I'm using localhost.
- ```WSSN2 build skeet.exe -d SQL -r``` build it and once its built use the API address like this: ```WSSN2 api -l -r skeet.exe```
- Once everything is done, you now have the loader, now create a PHPMyAdmin workspace and put ```test.sql``` inside of the workspace.
- Once loaded, create a user called ```admin``` ```admin123``` admin is the username, admin123 is the password. (change it later)
- ```wine binary -r skeet.exe -d 192.168.1.1``` and log in with your credentials.
- You will see a option to inject the CS:GO version and now it's possible, transfer with USB (i use KDNMF2 for transfering it)

### Time
It took me ```an hour``` to build everything and set it up, it can take less.
Make sure your IP is on a real host and transfer it after because localhost isn't reliable.

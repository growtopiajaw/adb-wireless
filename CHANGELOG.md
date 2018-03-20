adb-wireless v1.0 Copyright © 2018 Microsoft10 4-3-2018

1. Initial commit

adb-wireless v2.0 Copyright © 2018 Microsoft10 6-3-2018

1. Added adb not found
2. Removed TCP PORT as inputable mode. As adb only accepts PORT 5555. When testing, adb refuses to connect to any PORT other than PORT 5555. So, I decided to remove TCP PORT as inputable mode.
3. Also, I don't know if this is a bug with adb. When I remove adb tcpip and just skip to adb connect 192.168.xx.xx, adb refuses to connect. Again, when I added back the command adb tcpip, it accepts to connect again. Very strange. So, I just leave the command there until someone finds out about this explanation.
4. Changed IP ADDRESS to inputable mode
5. Made script mode user-friendly with more interactive prompt + informations

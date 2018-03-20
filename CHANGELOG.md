adb-wireless v1.0 Copyright © 2018 Microsoft10 4-3-2018

1. Initial commit

adb-wireless v2.0 Copyright © 2018 Microsoft10 6-3-2018

1. Added adb not found in current directory
2. Removed TCP PORT as inputable mode. As adb only accepts PORT 5555. When testing, adb refuses to connect to any PORT other than PORT 5555. So, I decided to remove TCP PORT as inputable mode.
3. Also, I don't know if this is a bug with adb. When I remove adb tcpip and just skip to adb connect 192.168.xx.xx, adb refuses to connect. Again, when I added back the command adb tcpip, it accepts to connect again. Very strange. So, I just leave the command there until someone finds out about this explanation.
4. Changed IP ADDRESS to inputable mode
5. Made script mode user-friendly with more interactive prompt + informations

adb-wireless v2.1-debug Copyright © 2018 Microsoft10 9-3-2018

1. 1st update and debug version released
2. Made script output more verbose to debug errors easily
3. Edited some lines of prompt

adb-wireless v2.1 Copyright © 2018 Microsoft10 9-3-2018

1. 1st update version released
2. Edited some lines of prompt

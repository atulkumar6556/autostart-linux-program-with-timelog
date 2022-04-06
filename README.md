# autostart-linux-program-with-timelog
AUTO START LINUX PROGRAM 
### autorun and create log with timestamp

## PASTE IT IN rc.local to start autorun on startup 

        #!/bin/bash

        echo `date +%F" "%T` "Starting Programs"  >> /root/yourlogname.log

        sudo /usr/bin/python3 /home/admin1/atul.py  &
        sudo /usr/bin/python3 /home/admin1/Videos/atul2.py &


        echo `date +%F" "%T` "Programs Started"  >> /root/yourlogname.log


        exit 0

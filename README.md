# Eleduino Fan Controller for Raspberry Pi 3

Download the script

> git clone https://github.com/viktor6/Raspberry-Fan-Controll.git

Open your crontab -e

> sudo crontab -e

Add this line 

> 5 * * * * sudo python /home/pi/fanControll.py

Reboot and the fan will now turn on if the temperature gets above 45C. To change the temperature open the script in leafpad, and change maxTemp to the temperature you want the fan to turn on at in Celsius.


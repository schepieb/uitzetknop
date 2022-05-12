# uitzetknop
drukknop om raspberry pi uit te zetten
## Beschrijving
Met een drukknop aangesloten op pin 5 en 6 kan je de raspberry uitzetten
## Bron
https://raspberrytips.nl/raspberry-pi-afsluiten-met-een-shutdown-drukknop/
## Software
plaats shutdown in home/pi
in terminal :
crontab -e
onderaan toevoegen : @reboot sudo python /home/pi/shutdown.py
herstarten

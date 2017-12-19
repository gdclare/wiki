# dash
Dash setup wiki

1. Login to MediaPi

2. Dasher must be started - Start up
cd ~/dasher/config
sudo npm start

3. Sonos http must be started
cd ~/node-sonos-http-api
sudo npm start

## To add a new button
cd ~/dasher
script/find_button - press your button and copy the mac address

cd ~/dasher/config
sudo nano config.json -- Copy the example from the previous buttons
--if you want to see some more examples run the 'dir' command. and open config.example.json by running the command. sudo nano config.example.json 

## Links
https://www.hackster.io/ravi-sawhney/play-your-favourite-sonos-playlist-with-an-amazon-dash-cd554b  
https://github.com/maddox/dasher  
https://github.com/jishi/node-sonos-http-api  

## Futher uses
Switch input, could use to pause all
https://jonasrosland.com/control-sonos-with-amazon-dash-button/

Reboot a Pi
https://howchoo.com/g/ymy4nza0nzb/reboot-your-raspberry-pi-using-an-amazon-dash-button

## Register as a service
https://github.com/maddox/dasher/wiki/Running-Dasher-on-a-Raspberry-Pi-at-startup, repeat the process for node-sonos-http-api

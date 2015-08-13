### SynthInit
is a init.d script to
start and stop
pyDispSys.py
synthOS.pd

### Setup autostart
Place synthInit in /etc/init.d

#### Adding the serice to auto start
then call update-rc.d synthOSInit defaults

#### Removing auto start
remove the file from /etc/rc*/*synthOSInit

#### Starting and Stoping
service synthOSInit start
service synthOSInit stop

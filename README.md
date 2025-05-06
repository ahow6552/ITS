# HW1
TDX training: 236羅斯福路 api test

# HW2
sumo and veins connection
-------------------------
```
cd /home/ahow/School/ITS/hw2/env/veins-veins-5.2/examples/veins
~/School/ITS/hw2/env/sumo-1.11.0/bin/sumo -c erlangen.sumo.cfg
/home/ahow/School/ITS/hw2/env/veins-veins-5.2/sumo-launchd.py -vv -c ~/School/ITS/hw2/env/sumo-1.11.0/bin/sumo
```


build omnetpp
-------------
```
cd ~/School/ITS/hw2/env/omnetpp-5.6
. setenv
./configure 
make clean
make -j$(nproc)
omnetpp
```

features
--------
veins-5.2
omnetpp-5.6.1
inet4
sumo-1.11.0
openjdk 17.0.14 

# HW3
draw 530 bus trial on OSM

# HW4
use sumo to design maps
```
./netgenerate -g --grid.number 3
```
vehicle trips
```
python ~/School/ITS/hw2/env/sumo-1.11.0/tools/randomTrips.py -n net.net.xml -r net.rou.xml
```
then use sumo-gui to simulate
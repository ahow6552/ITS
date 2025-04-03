# HW1
TDX training: 236羅斯福路 api test

# HW2
sumo and veins connection
-------------------------
```
~/School/IoT/hw2/env/sumo-1.11.0/bin/sumo -c erlangen.sumo.cfg
python3 ~/School/IoT/hw2/env/veins-veins-5.2/sumo-launchd.py -vv -c ~/School/IoT/hw2/env/sumo-1.11.0/bin/sumo
```


build omnetpp
-------------
```
cd /home/ahow/School/IoT/hw2/env/omnetpp-5.6
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
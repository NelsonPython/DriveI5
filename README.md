# Drive I-5

This is the repository for the [Drive I-5 tutorial](http://i18nelson.com/Tutorial-DriveI5/EVehicles.htm) that runs in the [AI Lab](https://github.com/NelsonPython/AI_Lab).  To build your own AI Lab, follow these [instructions](https://github.com/NelsonPython/AI_Lab).  To conduct Drive I-5 experiments, click on these links to configure each device:</h2>

[AstroPiQuake](AstroPiQuake/README.md)

[Enviro](Enviro/README.md)

[Air MacClean](AirMacClean/README.md)

[Bumblebee AV](BumblebeeAV/README.md)

[Public Radio](PublicRadio/README.md)

[MOBI Data Mart](DataMart/README.md)

After your devices are configured, follow these steps to conduct experiments:

1. Power on all your devices

2. If you don't have a static IP address for Public Radio, get the current IP address

```
ip addr
```



3. If you don't have static IP addresses for each device, lookup the username and password for each device using their MAC address

```
python3 nmap2mac.py
```

4. Open the AstroPiQuake emoji listener so you can view emojis on the LED panel

```
python3 emoji.py
```

5. Open the BumbleBee AV listener so it can respond to messages such as an earthquake alert

```
python3 listener.py
```

6. Go to the MOBI Data Mart website, click on Roadtrip, and choose your route

7. To simulate an earthquake, go to Public Radio and run ./quake.sh

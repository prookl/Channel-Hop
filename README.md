This channel hop bash script will help in looking for wifi channels when using an external antenna. Some computers have an issue with the Alfa AWUS036ACH antenna when using `airodump-ng`. Channels will all stay as 1 (not-1) unless manually set with `iwconfig`. 

Usage:

```
IFACE=<antenna_interface> ./channel-hop.sh 
```
Output is saved as channels.txt

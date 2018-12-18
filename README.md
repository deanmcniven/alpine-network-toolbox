# alpine-network-toolbox
This is a minimal docker image based on alpine that contains a number of useful network tools:
* dig
* nslookup
* telnet
* tcpdump
* netcat

# Usage
```docker run -it --rm deanmcniven/alpine-network-toolbox:latest```
Note: The image assumes a `Australia/Sydney` timezone. If you would like another timezone simply set the TZ environment variable.

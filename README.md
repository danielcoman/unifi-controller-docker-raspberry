# unifi-controller-docker

Run ubiquiti unifi controller in docker on raspberry pi arm32 or x86-64

Image Build:
```bash
sudo docker-compose -f  build-rpi.yaml build
sudo docker-compose -f  build.yaml build
```

Run:
```bash
sudo docker-compose -f unifi-rpi.yaml up -d
sudo docker-compose -f unifi.yaml up -d
```

# Ports
https://help.ubnt.com/hc/en-us/articles/218506997-UniFi-Ports-Used

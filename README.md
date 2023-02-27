# How to use

sh````
docker run -it --name=wa -p 8:8888 -p 2222:22 -p 3389:3389 ghcr.io/der2beers/webaudio:testing
````
Connect via RDP or ssh with
User: root
Password :root

SSH uses port 2222 therfore go with
sh````
ssh root@localhost -p 2222
````

# yi-hack-MStar-rsync

This is rsync 3.2.4 compiled for use with https://github.com/roleoroleo/yi-hack-MStar

# Installation
```
mkdir -p /tmp/sd/yi-hack/bin
cd /tmp/sd/yi-hack/bin
wget https://github.com/cheese1/yi-hack-MStar-rsync/releases/download/3.2.3/rsync
chmod 0755 rsync
```
# Example Usage
to move videos to a server at 192.168.1.4 with user yihack and target directory /home/cam:
```
rsync --delete-source-files -avp --progress /tmp/sd/record/2020Y12M25D* yihack@192.168.1.4:/home/cam/
```
works great as cronjob on the camera.

I will keep updating this as soon as new versions become available.

rsync is licensed under GPL version 3 



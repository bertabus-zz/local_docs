local_docs
==========

A collection of nginx/systemd scripts to have local documentation when offline.

Install nginx, pacin/apt-get/yum, whatever.

Install the godoc startup script-
```sh
sudo cp godoc.service /usr/lib/systemd/system/
sudo systemctl enable godoc.service
sudo systemctl start godoc.service
```

Replace/modify your nginx.conf file and hosts file with those provided.
Lastly download each of the source doc's, notes of where I found them
at the time of writing are in the hosts file.

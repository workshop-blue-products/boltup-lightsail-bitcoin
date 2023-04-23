# Bitcoin running on Lightsail for Boltup

# Setup a lightsail Bitcoin node
Add the following code as the launch script for the lightsail node 
``` 
curl -s https://raw.githubusercontent.com/workshop-blue-products/boltup-lightsail-bitcoin/main/lightsail-launch-script | bash
```

 - Add a disk (at least 650GB to Lightsail and connect it to the machine as /dev/xvdf
 - Run `sudo /home/ubuntu/boltup-lightsail-bitcoin/lightsail-setup-storage`
 - Reboot the node to start bitcoind on the mounted storage

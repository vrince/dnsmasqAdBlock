
```bash
ssh username@usg-ip

# on the usg
sudo -i
cd /config/scripts
curl https://raw.githubusercontent.com/vrince/dnsmasqAdBlock/master/getBlacklistHosts.sh > getBlacklistHosts.sh

# run once to setup the thing
./getBlacklistHosts.sh

# runa second time to actually fetch host to black list and update dnsmask config
./getBlacklistHosts.sh
```

# References

https://www.suffix.be/blog/network-wide-ad-blocking-unifi/
https://github.com/unifiMynet/dnsmasqAdBlock/
https://community.ui.com/questions/HowTo-Ad-blocking-using-dnsmasq-d-instead-of-etc-hosts/1598a96d-28af-4f3f-ab96-97bccdb897b3#M66463
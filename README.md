# Allow only single IP on linux via iptables configuration

I created this configuration researching and testing multiple examples from many authors.  
I'm not an expert of iptables so can't guarantee it's 100% correct but I use this setup [and hoping won't get hacked :)]

In this configuration on SSL port 443 is allowed, you must make additional adjustments to allow different ports if desired

see **iptables.txt**

# References

**Clear from**  
[https://serverfault.com/questions/200635/best-way-to-clear-all-iptables-rules](https://serverfault.com/questions/200635/best-way-to-clear-all-iptables-rules)

[https://medium.com/@gokhanefendi/how-to-reset-iptables-to-default-d60ca88f6e5e ](https://medium.com/@gokhanefendi/how-to-reset-iptables-to-default-d60ca88f6e5e ) 

**Base firewall from**  
[https://github.com/amarildojr/Firewall/blob/master/rules2](https://github.com/amarildojr/Firewall/blob/master/rules2)

**iptables info**  
[https://www.howtogeek.com/177621/the-beginners-guide-to-iptables-the-linux-firewall](https://www.howtogeek.com/177621/the-beginners-guide-to-iptables-the-linux-firewall)  
[https://serverfault.com/questions/183461/how-do-i-allow-outgoing-connections-via-iptables](https://serverfault.com/questions/183461/how-do-i-allow-outgoing-connections-via-iptables)


### Make IP tables permanent

https://unix.stackexchange.com/questions/111338/saving-an-iptables-configuration-permanently
  
https://www.digitalocean.com/community/tutorials/how-to-implement-a-basic-firewall-template-with-iptables-on-ubuntu-14-04

*using rc.local*  
https://askubuntu.com/questions/84781/iptables-resets-when-server-reboots

https://zertrin.org/projects/iptables-persistent/


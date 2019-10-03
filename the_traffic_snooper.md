# The Traffic Snooper

Unfortunately, DNS Corporation still uses a number of very old routers throughout there network. On the bright side though, even though these devices don't automatically use SSL for their management portals, your admins know to make sure to always use https. As part of your pentest, you managed to capture some traffic during when an admin changed the wifi password. Since it's SSL encrypted, you shouldn't be able to decrypt it, right? It's not like you'd be able to find the private key for someone's router on the internet. RIGHT? Download [snoop.pcap](https://problems.metactf.com/rvasec2019/snoop.pcap), and let's find out. Your flag is the new Wifi password.

Tip: For this one, see if you can find a repository that stores hardcoded SSL keys / is a tool that can detect that from a pcap. Take a very close look at the hint

__Hint:__ I hid your key in a little black box :)
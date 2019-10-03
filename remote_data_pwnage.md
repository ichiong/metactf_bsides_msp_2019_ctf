# Remote Data Pwnage 2: The Cached Edition

If you've competed in some past MetaCTF events, you may remember Remote Data Pwnage where you reconstructed an RDP session from a pcap like a true packet ninja. This time, though, our network team was (unfortunately) unable to pull the network pcap due to visibility & retention constraints. Do not despair! Our IR team did indeed manage to recover a partial file system dump? Take a look at [Users.zip](https://problems.metactf.com/rvasec2019/Users.zip) and see if you can reconstruct anything useful.

Note: If you did this in real life, you'd probably get a memory dump, but we've just extracted the Users folder to save several GBs in the download.

Tip: Have you found where the cache file is stored? Once you find where the cache file is stored, you can use a tool to extract some images

__Hint:__ Don't you just love having a lot of cache? :)
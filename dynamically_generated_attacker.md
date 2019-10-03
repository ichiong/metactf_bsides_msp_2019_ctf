# Dynamically Generated Attacker

Your colleagues on the network team have recently identified a piece of malware reaching out to a different C2 server hosted at a unique domain every request. Until you have a chance to remove all the malware across your environment, we need you to reverse engineer the domain generation algorithm (DGA) based on the malicious domains we already identified. Once we have this info, we can extend your script and block all future requests.

Using this [list of domains](https://problems.metactf.com/content/domains.txt) and [this starter python script](https://problems.metactf.com/content/generate_blocklist.py), complete the generate_next_domain function. Your flag is the domain the malware would reach out to at 07/11/2019 19:38.

__Hint:__ What information changes between each entry in domains.txt?




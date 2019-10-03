# Attack of the Cryptographic Certificate

On the surface, a file might look like something else, but really it's just a disguise for the attacker's true payload, embedded inside the smokescreen. Our blue team recently came across this suspicious looking certificate when we noticed it was much larger than normal certificate files. Can you take a look and see if you can figure out more? Here's the file: [sus.crt](https://problems.metactf.com/rvasec2019/sus.crt).

Note: This problem is based off real malware, but has been neutered for the purposes of this problem, so it will not cause any harm. That said, your AV may still flag it, and we always recommend conducting malware analysis inside a clean VM.

Tip: After getting to the point where you have an actual file, take a look at the file's metadata

__Hint:__ When you get to that point, seek out and analyze where the rest of the executed payload is stored within the file.
# Collision Course

Internet scale data collection presents some interesting opportunities and hard problems to solve. Here's one for you. We've collected 5,000,000 RSA public keys and encrypted the flag 5,000,000 times, once with each of the public keys. Your challenge? Recover the original flag by applying a clever approach that takes advantage of having so many public keys. Download this [file](https://drive.google.com/file/d/1VtvWbTerAtUdrBKT-HALZJ_RmxAibCW-/view) to get started.

Note: `e = 65537` and the file is formatted `C\tN`. Also, the flag is encoded base 36, so you'll need to convert the decrypted ciphertext to the plaintext flag using an online tool like CyberChef or something similar to `python -c 'import numpy as np; print(np.base_repr(plaintext_number,36))'`

__Hint:__ Now that you've collected so many public keys, how might we use that to our advantage?


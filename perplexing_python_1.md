# Perplexing Python # 1

You found this authentication module to a piece of malware with a hard-coded password. Can you find the password?

__Hint:__ Can you split it into parts and figure out what each of them does?

```python
import random
a = input("Enter password: "); a += chr(random.randint(97,122))*(len(a)%2)
b = lambda a: "".join([a[b+1]+a[b] for b in range(0,len(a),2)])[::-1]
c = lambda b: "".join([chr(ord(b[c])+(-1)**(c+1)) for c in range(len(b))])[::-1]
print("Correct! Your flag is %s." % a if c(b(a))=="nhpouqb^umhhbqjuzs" else "Wrong... Try again.")
```
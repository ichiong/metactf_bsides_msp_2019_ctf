# Assembly 101

We found a program written in an interesting programming language. One of the functions is called something(). Here is the code below:

```
something:
push  rbp
mov  rbp, rsp
mov  DWORD PTR [rbp-0x14], edi
mov  DWORD PTR [rbp-0x4], 0x0
mov  DWORD PTR [rbp-0x8], 0x0
jmp  label_2


label_1:
mov  eax, DWORD PTR [rbp-0x8]
add  DWORD PTR [rbp-0x4], eax
add  DWORD PTR [rbp-0x8], 0x1


label_2:
mov  eax, DWORD PTR [rbp-0x8]
cmp  eax, DWORD PTR [rbp-0x14]
jl label_1
mov  eax, DWORD PTR [rbp-0x4]
pop  rbp
ret
```

What is the value returned from something(10)? (where 10 is in decimal format) Express your answer as a base 10 decimal.
Note: You only have 5 attempts for this one, so double check your work!

UPDATE: This may be useful: https://www.tutorialspoint.com/assembly_programming/assembly_introduction.htm
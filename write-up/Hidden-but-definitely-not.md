
- solved by @lawence3713
- 하단 코드를 통해 플래그를 획득할 수 있다.

**solve.py**
```
enc = "ehuhDSA|NXO?XJG0ni`XTsU6i`2XdOfktz"

for i in range(len(enc)):
    dec = (ord(enc[i]) ^ 0x7) & 0xff
    print(chr(dec), end='')
```

- Flag: boroCTF{I_H8_M@7ing_StR1ng5_cHals}

# One Time Pad

Example:
```
python otp_decrypt.py orig/1 ciphers/ | xxd -r -p > wut
```

This example is for volga ctf cry200. Rotate the caesar cipher with:

<http://www.xarg.org/tools/caesar-cipher/>

Also this explains everything about OTP: <http://crypto.stackexchange.com/a/6095>.
Another good explanation: <http://travisdazell.blogspot.de/2012/11/many-time-pad-attack-crib-drag.html>

We use probability here, though.

Keystream (correctkey) is from [here](https://ctftime.org/writeup/1024).

Also I've seen this <http://blogs.gnome.org/muelli/2012/05/breaking-multiple-time-pad/> and maybe it's cool?
This also looks promising: <http://cryptosmith.org/archives/70>

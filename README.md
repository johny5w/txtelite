This is a cleaned up version of the
[Text Mode Elite](http://www.iancgbell.clara.net/elite/text/) source code
published by Ian Bell on his website. I found that the source code would
neither compile or work properly on modern systems and was not proper
ANSI C. All credit belongs to Ian.



NB for ubuntu change line 52 to  
```c
typedef unsigned int uint;
```
compile with -lm flag
```bash
gcc txtelite.c -lm -o txtelite
```

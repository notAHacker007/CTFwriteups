```
Sean Sears, the international Rock, Paper, Scissors champion, gives his adoring fans a thumbs-up after every bout. 
His grueling daily training routine starts with unary exercises, then progresses to binary, and then...
```

Decoding the image given as paper=0, rock=1, scissors=2 and thumbs up is a delimiter we get

01201 00111 01020 01200 00021 00112 0200 01211 0221 01002 01110 2222 01112 01002 00120 01222 0200 00111 00111 00002 00022 

and since the flag starts with f, which is 10210 in trinary we see that 1 and 0 should be swapped, and decoding gives the flag as flag{n1c3_RPS_sk1llz}

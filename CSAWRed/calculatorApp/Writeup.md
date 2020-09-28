```
I just made my first website! Its just a simple calculator. I dont really know what I'm doing, can you help me test it?

The flag is at /flag.txt.

http://web.red.csaw.io:5005

```

Taking a look at the source code they gave us, we see that they pass the expression into an eval statment in order to get the result. As such, we can inject into the equation field using the built-in file system (https://nodejs.org/api/fs.html). We can pass it `fs.readFileSync('/flag.txt')`to get the flag which is flag{rce_is_a_fun_thing}

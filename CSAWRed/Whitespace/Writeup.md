```
I think I handled the authentication correctly here... (this challenge resets its database every 60 seconds)

http://web.red.csaw.io:5002

```

Taking a look at the source code, we see that it authenticates and registers normally, but when it checks if you are admin, it removes all white space. We can register as 
"admin " and login with that same username and password, and if we log in, we are greeted with the flag.

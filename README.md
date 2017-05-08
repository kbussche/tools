
# Random Tools

## IPCcount
**Not mine**,  **Not mine**, **Not mine**  no idea who wrote this but it found its way onto some of my favorite systems.  Great for diagnosing who is DDOS'ing you or eating up all your apache/mysq/nginx resources.
There are many other ways to use this, this is what I do.

```
Install: 
    wget https://raw.githubusercontent.com/kbussche/tools/master/ipcount; chmod +x ipcount

Usage:
  netstat -vatn | ./ipcount | more

```


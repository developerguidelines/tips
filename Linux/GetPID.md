# How to get the process PID from name

I always do that using

```
ps aux | grep NAME
```

But exists a better way

```
pgrep NAME
```

One useful options for pgrep is `-l` to list the process name as well as the process ID.

More information about pgrep can be found on your man page.


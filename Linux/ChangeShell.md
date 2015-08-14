# How to change the default shell for a user
There is two tools that I know to do the job:
- usermod
- chsh

To use the first one root access is necessary.

To use the second one, root access is optional.

The syntax to `usermod` is:

```
# usermod -s /path/to/shell user-login
```

And the syntax to `chsh` is:

```shell
$ chsh -s /path/to/shell [user-login]
```

where `[user-login]` is optional.

If you don't pass the `user-login` then the actual user will be used.

The `chsh` is a good option because it allows to a user change your own shell, without root access.

## Aditional tip
One possible way to kwnow what is the actual shell for a user is using the `getent` command:

```
$ getent passwd user-login
```

which will return the line associated to the `user-login` from `/etc/passwd` file where the last information is the user's shell.

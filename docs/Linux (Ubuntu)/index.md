# User Management

```bash
sudo useradd -m username
```

The `-m` option gives the user a home directory `\home\username`

set the password for the user
```bash
sudo passwd username
```


set the shell for the user
```bash
sudo usermod -s \bin\bash username
```

delete the user
```bash
sudo userdelete username
```

## still required
* add a user to a group
* add the user to sudoers
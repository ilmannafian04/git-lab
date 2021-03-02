# lol

## Git

### GPG config

Need to specify direct path to gpg program

```.gitconfig
[gpg]
	program = /Program Files (x86)/GnuPG/bin/gpg.exe
```

## GitHub

### Action

- ssh is available on default ubuntu image
- .ssh folder is not configured, use action from marketplace to configure
- Ansible is availbale in ubuntu base image
- Careful with artifact pathing

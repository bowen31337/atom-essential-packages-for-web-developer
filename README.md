# Atom essential packages for web developer

all essential packages for web developer when using Atom as the editor

- Download atom-package-list.txt 
- Install packages from this downloaded file
```shell
apm install --packages-file atom-package-list.txt
```
- Then you are good to go

The folowing command is used to backup the installed packages to a file.
```shell
apm list -i -b | grep '^[^@]\+' -o > atom-package-list.txt
```

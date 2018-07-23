# debian-ubuntu-repos
Repos for Ubuntu and Debian

* These are for Debian Stable and Testing and Ubuntu current and last LTS only.
* We will keep these updated as new releases are made and old ones are no longer supported.

### Before you make changes
Install these packages:

```
apt install curl wget apt-transport-https dirmngr
```

### Making the Changes
* Open a terminal
* Backup your original sources file:

```
mv /etc/apt/sources.list /etc/apt/sources.list.orig
```
* Create a new sources file:
```
vi /etc/apt/sources.list
```
* Paste in the sources info you will be using

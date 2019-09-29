# Debian Apt Sources

Debian only has three release cycles `stable`, `testing`, and `unstable`.

## Stable

The "stable" distribution contains the latest officially released distribution of Debian.

```
#------------------------------------------------------------------------------#
#                   OFFICIAL DEBIAN REPOS                    
#------------------------------------------------------------------------------#

###### Debian Main Repos
deb http://deb.debian.org/debian/ stable main contrib non-free
deb-src http://deb.debian.org/debian/ stable main contrib non-free

deb http://deb.debian.org/debian/ stable-updates main contrib non-free
deb-src http://deb.debian.org/debian/ stable-updates main contrib non-free

deb http://deb.debian.org/debian-security stable/updates main
deb-src http://deb.debian.org/debian-security stable/updates main

deb http://ftp.debian.org/debian buster-backports main
deb-src http://ftp.debian.org/debian buster-backports main
```

## Testing

The "testing" distribution contains packages that haven't been accepted into a "stable" release yet, but they are in the queue for that.

```
#------------------------------------------------------------------------------#
#                   OFFICIAL DEBIAN REPOS                    
#------------------------------------------------------------------------------#

###### Debian Main Repos
deb http://deb.debian.org/debian/ testing main contrib non-free
deb-src http://deb.debian.org/debian/ testing main contrib non-free

deb http://deb.debian.org/debian/ testing-updates main contrib non-free
deb-src http://deb.debian.org/debian/ testing-updates main contrib non-free

deb http://deb.debian.org/debian-security testing-security main
deb-src http://deb.debian.org/debian-security testing-security main
```

## Unstable

The "unstable" distribution is where active development of Debian occurs.

```
#------------------------------------------------------------------------------#
#                   OFFICIAL DEBIAN REPOS                    
#------------------------------------------------------------------------------#

###### Debian Main Repos
deb http://deb.debian.org/debian/ unstable main contrib non-free
deb-src http://deb.debian.org/debian/ unstable main contrib non-free
```

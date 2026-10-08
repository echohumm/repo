arch repo with some packages of mine (currently zen-browser repackage because the aur one sucks, and starship because i forked it)

to use put this at the top of your `/etc/pacman.conf`:
```
[echohumm]
# maybe don't make this Optional TrustAll, though. unless you trust me and github(???) that much
SigLevel = Optional TrustAll
Server = https://github.com/echohumm/repo/releases/download/x86_64
```

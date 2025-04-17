# Why this project ? 

Everybody hates documention, and even more having to do manual menial tasks. 
While the footprint of Alpine is super low (200mb), it is a bit of work to configure. 
It is also versatile, efficient and secure. 

I wanted to see how how much a single setup script can do. 

The only prereq is git to access the script.

So `apk add git`
Then `chmod +x` and `./setup.sh` 


## What exactly: 

### From Alpine Docs

Create /etc/profile.d/profile.sh with
```
if [ -f "$HOME/.config/ash/profile" ]; then
    . "$HOME/.config/ash/profile"
fi
```
Create ~/.config/ash/profile with:
```
export ENV="$HOME/.config/ash/ashrc"
```

^^ Same for zsh and BOTH to /.config/aliases

This modular approach makes it so that if you create several users down the line they can all have their own configs. 

### Basic system conf 

### Auto-add main/community repos

### Emoji / UTF8 support

### Added more helpful motd

### Cool splash screen
----






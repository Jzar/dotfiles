# Malikoth's Dotfiles

## Prerequisites
* bash
* curl
* git

### OSX
```bash
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
brew install bash curl git
```

### Debian
```bash
apt-get update && apt-get install -y bash curl git
```

### Alpine
```bash
apk add --no-cache bash curl git
``` 

## Installation

* Bootstrap this repo via YADM

```bash
curl -fsSL 'https://github.com/TheLocehiliosan/yadm/raw/master/yadm' | bash -s -- clone --bootstrap http://git.klr.blue/kyle/dotfiles.git
```

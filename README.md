# Console keyboard layout switcher for Mac OS X

## Install

```bash
git clone git@github.com:fullpipe/xkbswitch.git
cd xkbswitch
make && sudo mv xkbswitch /usr/local/bin
```

## Usage

```bash
xkbswitch # prints com.apple.keylayout.ABC
xkbswitch com.apple.keylayout.ABC # sets up keyboard layout to com.apple.keylayout.ABC
```


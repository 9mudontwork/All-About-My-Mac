# Golang

If you installed on Mac OS not with home-brew but with the macOS package installer, your _GOBIN_ be in [/usr/local/go](https://golang.org/doc/install) and _GOPATH_ in [$HOME/go](https://github.com/golang/go/wiki/SettingGOPATH), finally in `~/.zshrc`:

```text
export GOPATH=$HOME/go
export GOROOT=/usr/local/go
export GOBIN=$GOPATH/bin
export PATH=$PATH:$GOPATH
export PATH=$PATH:$GOROOT/bin
```


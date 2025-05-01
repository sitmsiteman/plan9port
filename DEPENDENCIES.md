## Linux
### Arch Linux
#### Runtime Dependencies
* fuse (fuse2)
* libxext
* libxt
* xorg-server
#### Build Dependencies
* gendesk

### Debian
* libfontconfig1-dev
* libx11-dev
* libxext-dev
* libxt-dev

### Ubuntu
* xorg-dev

### Fedora
* libX11-devel
* libXt-devel
* fontconfig-devel
* libXext-devel

### Alpine
* libx11
* libxext
* musl
* fontconfig-dev
* freetype-dev
* linux-headers
* libucontext: need to add '-lucontext' linker flag in bin/9l

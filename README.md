Image Maker
=============

Packer repo to build stanard images

Requirements
=============

Install [VirtualBox](https://www.virtualbox.org/wiki/Downloads)

Install [Packer](https://www.packer.io/downloads.html)

Example Usage
=============

Build Debian 7 Vagrant Box (default)
```packer build debian7-packer.json
```

Resulting image will be at
```builds/mm-debian7-packer.box
```

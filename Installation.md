## Installation
```
  # pkg update
  # pkg install bvm
```
### -- or --
```
  # portsnap fetch update
  # cd /usr/ports/sysutils/bvm/
  # make install clean
```
### -- or --
```
  // Compile source code
  # cd src
  # make
  # cp bvm bvmb /usr/local/bin/
  # mkdir /usr/local/etc/bvm/
  # cd ..
  # cp conf/*.conf /usr/local/etc/bvm/
  # cp conf/bvmd /usr/local/etc/rc.d/

  // Generate the installation package
  # cd pkg
  # ./create

  // Installation
  // bvm.txz is replaced with the installation package you generated
  # pkg add bvm.txz
```


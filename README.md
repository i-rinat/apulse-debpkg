Debian packaging scripts for apulse
===================================

To start, clone repository into `debian/` subdirectory of `apulse` sources:
```
git clone https://github.com/i-rinat/apulse-debpkg debian
```

Then, use `dpkg-buildpackage -b -us -uc` to build the package.

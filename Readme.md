ICU4C
=====

http://icu-project.org/apiref/icu4c/index.html

### Version 51.2 (linux/i386, linux/amd64)

Configuration:

```bash
CXXFLAGS="-fPIC" CFLAGS="-fPIC" ./runConfigureICU Linux/gcc --enable-static --prefix=/opt/icu
```

Built with GCC 4.1.2 on Debian/Etch.

### Version 52.1 (darwin/universal)

Configuration:

```bash
CXXFLAGS="-fPIC -arch i386 -arch x86_64 -mmacosx-version-min=10.6" CFLAGS="-fPIC -arch i386 -arch x86_64 -mmacosx-version-min=10.6" ./runConfigureICU MacOSX --enable-static --prefix=/usr/local/icu/52.1
```

Built with XCode 5.0.2 on OS X Mavericks.

---
[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/cpp-libs/icu/trend.png)](https://bitdeli.com/free "Bitdeli Badge")

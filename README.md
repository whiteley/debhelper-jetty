debhelper-jetty
===============

Debhelper packaging files for binary Jetty distribution.

* Download and rename [jetty-distribution](http://download.eclipse.org/jetty/stable-9/dist/) tarball

```
jetty-distribution-9.0.5.v20130815.tar.gz jetty_9.0.5.v20130815.orig.tar.gz
```

* Extract tarball and clone this repo

```
tar zxf jetty_9.0.5.v20130815.orig.tar.gz
git clone https://github.com/whiteley/debhelper-jetty.git jetty-distribution-9.0.5.v20130815/debian
```

* Build the package

```
cd jetty-distribution-9.0.5.v20130815
dpkg-buildpackage -rfakeroot -uc -us
```

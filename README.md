# qt-builder-env

Simple config file to create deb metapackage. The package depends from packages
required to build Qt from source.

# How to

```
sudo apt-get install equivs
equivs-build qt-builder-env.cfg
sudo apt-get install ./qt-builder-env_2.0_all.deb
```

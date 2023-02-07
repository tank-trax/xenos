 ### Linux ###

```
git clone https://github.com/tank-trax/xenos.git
cd xenos
git checkout linux
git submodule update --init --recursive
```

* Open Xenos-Linux.jucer in Projucer
* Save

```
cd Builds/LinuxMakefile/
make CONFIG=Release
```

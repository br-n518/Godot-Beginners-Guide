
### GDNative C++ Install on Ubuntu

[Source](https://github.com/GodotNativeTools/godot-cpp/blob/master/README.md)

```
sudo apt-get install scons gcc-multilib g++-multilib
mkdir bin
mkdir src
# remove '-b 3.0' for 3.1-beta1 version
git clone --recursive https://github.com/GodotNativeTools/godot-cpp -b "3.0"
cd godot-cpp
scons platform=linux generate_bindings=yes
# TAKES FOREVER

# Windows compile
sudo apt-get install g++-mingw-w64
scons platform=windows bits=64 generate_bindings=yes
```

* `platform=( linux osx windows )`
* `bits=32`

* use_llvm :bool
* use_mingw :bool


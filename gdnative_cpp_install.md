
### GDNative C++ Install on Ubuntu

[Source](https://github.com/GodotNativeTools/godot-cpp/blob/master/README.md)

```
sudo apt-get install scons gcc-multilib g++-multilib
# remove '-b 3.0' for 3.1-beta1 version
git clone --recursive https://github.com/GodotNativeTools/godot-cpp -b "3.0"
cd godot-cpp
scons platform=linux bits=64 generate_bindings=yes
```



# TIFF

## Windows上使用mingw64编译

```bash
> mkdir build & cd build
> cmake .. -G Ninja -DCMAKE_BUILD_TYPE=Release -DCMAKE_INSTALL_PREFIX=D:\devtools\TIFF.4.6.0
> ninja install
```
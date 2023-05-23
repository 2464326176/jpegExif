# jpegExif

```makefile
sudo apt-get update
sudo apt-get upgread
apt-get install build-essential gdb

cd {build_directory}
cmake -G"Unix Makefiles" [additional CMake flags] {source_directory}
./configure --prefix=

在运行之前，使用 export/setenv 设置以下环境变量 招商：
export  CFLAGS=-m32 LDFLAGS=-m32 CC="gcc -m32" CXX="g++ -m32"
cmake -G"Unix Makefiles" --install-prefix=/home/sourceCode/exifJpeg/libjpeg-turbo/build32/build   ..
make install

export  CFLAGS=-m64 LDFLAGS=-m64 CC="gcc -m64" CXX="g++ -m64"
cmake -G"Unix Makefiles" --install-prefix=/home/sourceCode/exifJpeg/libjpeg-turbo/build64/build   ..
make install
```


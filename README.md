# Android-Toolchain-NDK-build
easy to build android project via ndk

# How to use it
## step1 
To find your ndk installation directory and your arch, e.g arm64-v8a. go to directory which CMakeLists.txt file locate at.
example:
python3 tools/android_cmake_build.py -n C:\Users\mg\AppData\Local\Android\Sdk\ndk\26.1.10909125 -a arm64-v8a -i ./ -o build/arm64-v8a

it will create directory build/arm64-v8a and generate makefile according to CMakeLists.txt

## step2
go into directory build/arm64-v8a, execute below command:


$cmake --build ./

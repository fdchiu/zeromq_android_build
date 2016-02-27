# zeromq_android_build
this repo has the reference build scripts for building libzmq for android platform.
#What does it do
It compiles libzmq.a and libzmq.so for android target
#How to use it
1) Copy the scripts to libzmq's dir tree: builds/android
2) Edit the path and target info in android_build_helper.sh
3) Make sure you have created an android NDK standalone toolchain to compile libzmq
4) Run: ./build.sh
5) lib & header will be created at: builds/android/prefix/arm-linux-androideabi-4.8
#Note:
Following this instuction on how to create standalone android toolchain:
http://developer.android.com/intl/ru/ndk/guides/standalone_toolchain.html
If you don't know what is libzmq, read more at the following link:
http://zeromq.org


# python_fun

# Dependencies

* Clang-format
* Clang 3.6 or GCC 4.9.2
* jemalloc
* SBT 0.13.8
* Intel TBB
* C++11
* AVX

It may work with different versions of these but this is what the system is currently tested on.

**Need Clang-format**

Linux:
```
sudo apt-get install clang-format
```
Mac:
```
brew install clang-format
```

**Need GCC?**

Linux:
```
sudo add-apt-repository -y ppa:ubuntu-toolchain-r/test  
sudo apt-get update
sudo apt-get install g++-4.9
```

**Need jemalloc?**
```
sudo apt-get install libjemalloc-dev
```
**Need SBT?**

http://www.scala-sbt.org/download.html

**Need TBB?**

Linux: `sudo apt-get install libtbb-dev`
Mac: `brew install tbb`

For more information....

https://www.threadingbuildingblocks.org/

**Need AVX?**

Buy a new machine.

# Configuration

Run `source setupEnv.sh`
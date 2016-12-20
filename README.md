# wlc example in java

Wlc stands for Wayland compositor library. It is available on their github repository:

https://github.com/Cloudef/wlc

Their aim is to enable the creation of compositor easily. In this repository, we prepose a less than minimal example (only mouse movement is implemented). 


## Java bindings for WLC using JavaCPP

The first working version is available here: 

https://github.com/poqudrof/javacpp-presets/tree/wlc

### Download and compile JavaCPP-presets for wlc

``` bash
git clone https://github.com/poqudrof/javacpp-presets.git
cd javacpp-presets
git checkout wlc
sh cppbuild.sh install wlc
maven install --projects .,wlc
```

### Download and compile this minimal example

``` bash
git clone https://github.com/poqudrof/wlc-java.git
cd wlc-java
mvn install 
java -jar target/wlc-java-1.3.jar
``` 

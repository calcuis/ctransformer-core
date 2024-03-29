### ctransformer-core

[<img src="https://raw.githubusercontent.com/calcuis/ctransformer-core/master/milk.gif" width="128" height="128">](https://github.com/calcuis/ctransformer-core)
[![Static Badge](https://img.shields.io/badge/core-0.2.28-yellow?logo=github)](https://github.com/calcuis/ctransformer-core/releases)

Follow up the stopping updated project ctransformers; continue working on it.

#### install it by (pip/pip3):
```
pip install ctransformers-0.2.28.tar.gz
```
#### run it by (python/python3):
```
python -m ctransformers
```
[<img src="https://raw.githubusercontent.com/calcuis/llama-core/master/demo.png" width="235" height="95">](https://github.com/calcuis/llama-core/blob/main/demo.png)

User interfaces are available to choose (eithr CLI or GUI); while chosen, GGUF file(s) in the current directory will be searched and detected.

[<img src="https://raw.githubusercontent.com/calcuis/chatgpt-model-selector/master/demo.gif" width="350" height="280">](https://github.com/calcuis/chatgpt-model-selector/blob/main/demo.gif)

This is another solo connector core; same as llama-core; being able to work independently as well.

#### reference
[ctransformers](https://github.com/marella/ctransformers)

All other functions are same as ctransformers; please see the reference above.

#### build from ctransformers-0.2.28.tar.gz (examples below are for CPU)
According to the latest note inside vs code, msys64 is recommended by Microsoft; or you can opt w64devkit or etc. as source of your gcc and g++ compilers.
#### for windows user(s):
```
$env:CMAKE_GENERATOR = "MinGW Makefiles"
$env:CMAKE_ARGS = "-DCMAKE_C_COMPILER=C:/msys64/mingw64/bin/gcc.exe -DCMAKE_CXX_COMPILER=C:/msys64/mingw64/bin/g++.exe"
pip install ctransformers-0.2.28.tar.gz
```
In mac, xcode command line tools are recommended by Apple for dealing all coding related issue(s); or you can bypass it for your own good/preference.
#### for mac user(s):
```
pip3 install ctransformers-0.2.28.tar.gz
```
Make sure your gcc and g++ are >=11; you can check it by: gcc --version and g++ --version if you opt to build the wheel from source code.

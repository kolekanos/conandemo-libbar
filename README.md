# conandemo-libbar
Simple C library

## Build steps

```bash
$ mkdir build && cd build
$ cmake .. -G "MSYS Makefiles" -DCMAKE_INSTALL_PREFIX=$PWD/../install
-- The C compiler identification is GNU 10.3.0
-- Detecting C compiler ABI info
-- Detecting C compiler ABI info - done
-- Check for working C compiler: C:/msys64/mingw64/bin/gcc.exe - skipped
-- Detecting C compile features
-- Detecting C compile features - done
-- Configuring done
-- Generating done
-- Build files have been written to: C:/msys64/home/kolekanos/conandemo-libbar/build
$ cmake --build .
[ 50%] Building C object source/CMakeFiles/Bar.dir/bar.c.obj
[100%] Linking C static library libBar.a
[100%] Built target Bar
$ cmake --install .
-- Install configuration: ""
-- Installing: C:/msys64/home/kolekanos/conandemo-libbar/install/lib/libBar.a
-- Installing: C:/msys64/home/kolekanos/conandemo-libbar/install/share/Bar/cmake/BarTargets.cmake
-- Installing: C:/msys64/home/kolekanos/conandemo-libbar/install/share/Bar/cmake/BarTargets-noconfig.cmake
-- Installing: C:/msys64/home/kolekanos/conandemo-libbar/install/share/Bar/cmake/BarConfig.cmake
-- Installing: C:/msys64/home/kolekanos/conandemo-libbar/install/share/Bar/cmake/BarConfigVersion.cmake
-- Installing: C:/msys64/home/kolekanos/conandemo-libbar/install/include
-- Installing: C:/msys64/home/kolekanos/conandemo-libbar/install/include/bar
-- Installing: C:/msys64/home/kolekanos/conandemo-libbar/install/include/bar/bar.h
```


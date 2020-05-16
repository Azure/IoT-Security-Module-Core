# IoT-Security-Module-Core
---

## Overview
Shared code base for IoT Security Modules

## Tests
### Requirements
- `cmake` > 3.15.0
- `cmocka` > 1.1.5

### Linux Environment
- Install `cmake` on Linux:
```
wget https://cmake.org/files/v3.15/cmake-3.15.0-Linux-x86_64.sh && \
    chmod +x cmake-3.15.0-Linux-x86_64.sh && \
    ./cmake-3.15.0-Linux-x86_64.sh --skip-license --prefix=/usr/local --exclude-subdir && \
    rm cmake-3.15.0-Linux-x86_64.sh
```

- Install `cmocka`:
```
wget https://cmocka.org/files/1.1/cmocka-1.1.5.tar.xz && \
    tar xf cmocka-1.1.5.tar.xz && \
    cd cmocka-1.1.5 && \
    mkdir bin && \
    cd bin && \
    cmake -DCMAKE_INSTALL_PREFIX=/usr -DCMAKE_BUILD_TYPE=Debug .. && \
    sudo make install
```
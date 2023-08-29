# ECG Monitor App

[![GNU/Linux CI badge](https://github.com/mbedded-mike/ECGMonitorApp/actions/workflows/ci_linux.yml/badge.svg)](https://github.com/mbedded-mike/ECGMonitorApp/actions/workflows/ci_linux.yml)

desktop app for my ECGMonitor hardware

![Rough, layered architecture depiction of the app](media/layers.png)

# Building

## Dependencies

- GNU/Linux machine

- compiler with C++20 support (gcc/clang)

- CMake 3.20

- GNU Make or Ninja

- SDL2

## Steps

1.
```
mkdir build && cd build
```

2.
```
cmake ..
```

3.
```
make -j`nproc`
```

4.
```
./ecgm_app
```

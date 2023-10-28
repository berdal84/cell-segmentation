# cell-segmentation
Cell segmentation using OpenCV

# How to build?

## Prerequisites:
- Required OS: GNU/Linux* Ubuntu 22

*can compile on Windows and Mac, but it is out of scope

## Download and build OpenCV:

From an empty directory

```
# Install minimal prerequisites (Ubuntu 18.04 as reference)
sudo apt update && sudo apt install -y cmake g++ wget unzip

# Download and unpack sources
wget -O opencv.zip https://github.com/opencv/opencv/archive/4.x.zip
unzip opencv.zip

# Create build directory
mkdir -p build && cd build

# Configure
cmake ../opencv-4.x

# Build
cmake --build .
```

## Build

From this folder

```
# Create build directory
mkdir -p build && cd build

# Configure
cmake ../

# Build
cmake --build .
```

## Run

From `./build` folder, run `./cell-segmentation path/to/your/image.png` 


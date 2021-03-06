# Custom Low-Cost Stereo Camera Using OpenCV

Create a custom low-cost stereo camera and capture 3D videos with it using OpenCV.

## Using the C++ code
### Compilation
To compile the `calibrate.cpp`, `capture_images.cpp` and `movie3d.cpp` code files, use the following:
```shell
mkdir build
cd build
cmake ..
cmake --build . --config Release
```
## Usage
Refer to the following to use the compiled files:

```shell
./build/capture_images
./build/calibrate
./build/movie3d
```

### Using the python code

Refer to the following to use the `calibrate.py`, `capture_images.py` and `movie3d.py` files respectively:

```shell
python3 calibrate.py
python3 capture_images.py
python3 movie3d.py
```

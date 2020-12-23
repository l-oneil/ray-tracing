# Ray Tracing
Repository containing some basic Ray Tracing implementations. These are entirely based on the ["Ray-Tracing in 1 Weekend series"](https://raytracing.github.io/).

The code here has been tested on the M1 Arm-based Macbook Air, but nothing else.

## Building 
Compile with:
```sh
 $ mkdir build && cd build 
 $ cmake -GNinja ..
 $ ninja
```

## Running 
The rendering is going to write PFM files to the `std::cout`, so run like so:
```sh
 $ ./RayTracer > image.ppm
```

## Example Output 
![Ray Traced Marbles](https://github.com/l-oneil/ray-tracing/blob/master/examples/in-one-weekend-final.jpg")


## Acknowledgements
* This repo is based wholly on the course [_Ray Tracing in One Weekend_](https://raytracing.github.io/), very little code is my own, please check this out!


## Useful Add-ons
* [VS Code PPM Viewer](https://marketplace.visualstudio.com/items?itemName=AYH.ppmviewer)

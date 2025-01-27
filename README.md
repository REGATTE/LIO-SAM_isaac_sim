# LIO-SAM

This branch of LIO_SAM is aimed for distributed slam, with LIO_SAM acting as the front end for a single robot. The package will not have **loop closure detection**, and also will publish **Keyframes** every `1m move` or `0.2radian` change.

## Files changed

 - **utility.hpp** : Added robot info handler for namespace
 - **imageProject.cpp** : Logic to remove Nan values in pointcloud
 - **imuPreintegration.cpp** : prefixed namespace to all frames necessary
 - **mapOptimaization.cpp**  :
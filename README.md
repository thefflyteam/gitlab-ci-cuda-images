# gitlab-ci-cuda-images
Cuda images for gitlab-CI.

## Cuda installation process  
- Go to nvidia download page - https://developer.nvidia.com/cuda-downloads - for cuda 12.3, and https://developer.nvidia.com/cuda-11-8-0-download-archive for cuda 11.8
 
- Choose Linux, x84_64, ubuntu, 20.04, deb (local)

- Copy the script and put it into the Dockerfile

Note: it take a long time to download all cuda's dependencies so be patient and make sure you have a good internet.
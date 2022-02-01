# drm-tools

Dockerised binaries helpful when testing DRM/KMS services.

Image is published at [rahulthakoor/drm-tools](https://hub.docker.com/repository/docker/rahulthakoor/drm-tools)

## Tools included

- drmdevice 
- kmscube 
- kms-steal-crtc 
- kms-universal-planes 
- modeprint 
- modetest 
- proptest 
- texturator 
- vbltest 

## How to use

1. Run a binary directly 

`docker run --rm -it --privileged rahulthakoor/drm-tools modetest`

2. Use as a base image

`FROM rahulthakoor/drm-tools`
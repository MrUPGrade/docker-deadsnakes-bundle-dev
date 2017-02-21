# Ubuntu dead snakes dev bundle

Dockerfile based on ubuntu with added python builds from the dead snakes PPA repository
(https://launchpad.net/~fkrull/+archive/ubuntu/deadsnakes).

This is a bundle version of the https://github.com/MrUPGrade/docker-deadsnakes-dev image with all python 
versions in one image. 

Images include additional packages needed often for building various python dependencies:

 - `libffi-dev`
 - `libssl-dev`
 - `build-essential`
 - `sudo`
 
To run selected python version (in example python 2.6) inside image execute command:

```bash
docker run --rm -it mrupgrade/deadsnakes-bundle-dev python2.6
```


# docker-packer
docker image to build the latest packer: https://github.com/mitchellh/packer

```
# mkdir -p ${PWD}/dist
# docker run --privileged -v ${PWD}/dist:/dist  henrysher/build-packer
```
```
# ls ${PWD}/dist
packer-latest-20150603063457.zip
```

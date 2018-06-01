## Docker
### usage
```
$nvidia-docker run -ti -v /home/share:/home/share bvlc/caffe:gpu
```
### check images
```
$docker images
```

### check container
```
$docker ps {-l}
```
### update
```
$docker commit -a "Foo Bar <foo@bar.com>" -m "add hello.txt" {container} {new image name}
```

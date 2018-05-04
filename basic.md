## SSH

### 포트열기
```
$sudo vi /etc/ssh/sshd_config
```
port 22 주석제거

### SSH 서버설치 및 서비스 가동
```
$sudo apt install openssh-server
$service ssh restart
```

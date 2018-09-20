<script type="text/javascript" src="http://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML"></script>

$ x = {-b \pm \sqrt{b^2-4ac} \over 2a} $

## SAMBA 설정
### SAMBA server install
```
$sudo apt install samba
```
### SAMBA config
```
sudo vi /etc/samba/smb.conf
```
### SAMBA restart
```
sudo service smbd restart
```

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

## MOUNT
### Path 연결
```
$sudo apt install cifs-utils
$mkdir {~/data(path-to-mount)}
$sudo mount -t cifs {target-path} {path-to-mount} -o username={username},domain={domain}, password={password}
```

## TMUX
### 새 세션 생성
```
$tmux new -s <session-name>
```
### 세션 이름 수정
ctrl+b, $
### 세션 종료
```
$exit
```
### 세션 중단하기 (detached)
ctrl+b,d
### 세션 목록 보기 (list-session)
```
$ tmux ls
```
### 세션 다시 시작
```
$ tmux attach -t <session-number or session-name>
```

## RSYNC
```
$sudo rsync -avz <src_path> <dst_path>
```
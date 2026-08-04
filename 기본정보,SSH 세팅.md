

## 1. 기본정보 파악
whoami → 사용자명 (enitt)
hostname → 호스트명 (ras)
hostname -I → IP주소 (192.168.10.16)

## 2. SSH 켜져있는지 확인
systemctl is-active ssh
- `active` : 켜져있음
- `inactive` or `not-found` : 꺼져있음

sudo systemctl enable --now ssh

PC에서 접속
ssh 사용자명@IP주소
ssh enitt@192.168.10.16



# Git Bash 명령어

pull, push 작업 전에 꼭 commit 을 하고 local repository 최신화 시켜주
기

개발완료 후commit->push 할때 팀원들에게 알려주기

git bash 실행 후 git할 경로 설정 해주기(cd)

코드 공유 명령----------------------------
1. git init
=> 현재 경로(폴더) 로컬레퍼지토리화 시키겠습니다

2. git config --global user.name "사용자이름"
3. git config --global user.email "사용자이메일"
=> 사용자 정보 입력


4. git remote add origin 원격저장소 주소
=> 원격 저장소 등록

-------커밋 과정-------

5. git add 프로젝트명
=> 커밋 활성화

6. git commit -m "커밋메시지"
=> 커밋 실행
-------------------------

7. git push origin master
=> 푸시 명령

8. git pull origin master
=> 풀 명령

------------------------ 코드 공유 명령

9. git remote -v
=> 등록된 원격 저장소 확인

10. git remote rm origin 

11. rm -rf .git
=> 로컬 레퍼지토리 취소

12. git config --global --list
=> 리스트 확인

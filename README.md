### Git과 GitHub 익히기
* Local 저장소 생성하기 git init
* Staging Area에 추가하기 git add
* log창에서 안나와질 때, ESC + Q
* 특정 버전을 생성하기 git commit
* 원격 저장소의 master 브랜치에 올리기 git push origin master

#### SourceTree 사용하기
* sourceTree에서 add 및 Push 하기

#### Branch 종류
* 1. master - 기본 배포용
* 2. Develop - 개발 영역
* 3. Release - 최종 출시 버전
* 4. Feature - 임시로 로컬에서 개발영역을 나워어서 작업 후 다시 Develop에서 merge
* 5. Hotfix - 출시 버전에서 급하게 버그가 생겼을 때 수정

#### Branch 이름
숫자 및 내용을 길게 안쓰고 작성자_타입_내용 ex) jwhan_feature_VR System Develop

#### Branch 명령어
* git branch -a -모든 브랜치 보기, 초록생은 현재 브랜치
* git checkout 브랜치명 -해당 브랜치로 이동
* git checkout -b 브랜치명 -해당 브랜치를 생성하고 현재 브랜치를 복사 후 이동
* git merge 브랜치명 -해당 브렌치의 내용을 현재 브랜치에 병합
* git push origin 브랜치명 -해당 브랜치를 원격에 Push
* git branch -d 브랜치명 -해당 브랜치를 로컬에서 삭제
* git push origin --delete 브랜치명 -해당 브랜치를 원격에서 삭제 (주의요망)


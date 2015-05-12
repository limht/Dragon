# Dragon
태홍이의 Git 사용법


** 변경된 사항 커밋하기

변경된 모든 파일 추가 (커밋 전에 필수 실행)
git add . 

아래의 명령어를 입력후 엔터 치고 변경목록이 보이면 Ctrl+o 그리고 엔터 그리고 Ctrl+x 종료한다.
git commit

커밋 메세지를 입력 (하지 않으면 안됨)
git commit -m '메세지입력'

저장소에 올리기 (계정과 암호 물어보면 입력)
git push


저장소 업데이트 (내려받기)
git pull

상태 확인
git status


** 파일무시하기
저장소 폴더에 .gitignore 파일을 생성한다.
내용에 무시하고 싶은 폴더나 파일명을 입력하고 저장한다.

data 폴더 제외
data/*

저장 후 커밋...



# Sample
git clone ghttps://github.com/limht/Dragon.git
cd Dragon
vi index.html
git add . or git add index.html
git commit -a -m'first commit'
git remote add origin ghttps://github.com/limht/Dragon.git or git remote add origin master
이제는 github를 확인~


덧, 위 명령어가 실행이 안되면
cd .git
vi config
	url = git://github.com ~~~~~~
	url = https://github.com ~~~~~ 로 바꿔주면 됨.
git push origin master


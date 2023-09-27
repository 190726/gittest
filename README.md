# gittest

git config --global user.name "190726" //user name 설정
git config --global user.name // user name 확인


git config --global user.email "xxx@naver.com" //user email 설정
git config --global user.email // user email 확인

git commit -m "first commit" //[-m] 은 message 의 약자

git checkout ab01er3 //커밋아이디 앞 7자리

git push origin main // 원격저장소(origin) 의 main이라는 방에 내 커밋들을 올려라라는 의미

git pull origin main // 원격저장소에 새로운 커밋이 있으면 내 로컬에 받아와라 라는 의미

git clone https://github.com...sixstar6.git . //끝에 마침표를 하지 않으면 새폴더가 하나 더 생기고 거기에 자원이 받아진다.

git reset file1.txt //언스테이징

git log --oneline --graph --all --decorate -n4 //n4-최근 4번째 커밋까지

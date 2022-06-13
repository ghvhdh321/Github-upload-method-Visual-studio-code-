###### Github-upload-method-Visual-studio-code-

ㅇ 처음 코딩 업로딩하기
1. 초기화
    git init

2. 추가할 파일 더하기
    git add .
    ex) git add index.html

3. 상태 확인
    git status

4. 히스토리 만들기
   git commit -m "first commit"

5. 연결됐는지 확인
   git remote -v

6. github로 올리기
   git push origin master


ㅇ 업데이트 하는 법
1. 추가할 파일 더하기
   git add .

2. 히스토리 만들기
   git commit -m "first commit"

3. github로 올리기
   git push origin master

ㅇ 팀프로젝트 하는 법
1. github에서 소스코드 다운로드 
   git clone 주소 폴더이름
   (주소는 깃허브에서 들고와야 함
    폴더이름은 선택사항이다. (즉 없어도됨) 폴더이름을 줄 경우에는
    그 폴더가 새로 생성이 되면서 그 안에 코드들이 다운로드가 되고,
    폴더이름을 안줄 경우에는 깃허브 프로젝트 이름으로 폴더가
    자동으로 생기고 그 안에 코드들이 다운로드 된다.)

2. github에서 내 branch(브렌치) 만들기
   git checkout -b 브렌치이름

3. 내 브렌치에서 소스코드 업데이트하기
   git add .
   git commit -m "first commit"
   git push origin 브렌치이름

4. 마스터 브렌치에 소스가져오기
   git pull origin master
   pull하기 전에 기존에 소스코드들을 commit을 먼저 해놔야 한다.

5. 브렌치끼리 이동하는 법
   git checkout 브렌치이름



깃 처음 들어와서 git bash 킨 다음 1. cd desktop -> cd 자기가만든 파일   (cd 명령어는 파일에 들어가는 것을 의미)
                                2. git clone --single-branch -b dev 주소
                                
                                
 다른사람 파일 건드릴땐 커밋 메세지에 입력
 


 개발을 시작하거나 작업을 끝마쳤을경우에 git pull origin dev를 한후에 개발 진행
 개발을 마쳤다면  다음 순서대로 입력
 
git add .
git commit -m "수정한 파일이나 패키지install한 메세지"
git push origin dev

# Github에 처음 올리기

1. 초기화
```
git init
```
2. 추가할 파일 더하기
```
git add .
```
3. 상태 확인
```
git status
```
4. 히스토리 만들기
```
git commit -m "first commit"
```
5. 메인 브랜치 지정
```
git branch -M main
```
6. Github repository랑 내 로컬 프로젝트 연결
```
git remote add origin https://github.com/~~~~.git
```
   Github repository가 private인 경우
```
git remote add origin git@github.com:username/reponame.git
```
7. 연결 확인
```
git remote -v
```
8. Github로 올리기
```
git push -u origin main
```
<br/><br/>

# Github에 강제로 올리기 (에러 발생할 때)
```
git push -u origin main --force
```
<br/><br/>

# Github에 계속 업데이트 하는 방법
1. 추가할 파일 더하기
```
git add .
```
2. 히스토리 만들기
```
git commit - m "second commit"
```
3. Github로 올리기
```
git push origin main
```
<br/><br/>

# Github repository가 private인 경우
Private 저장소의 경우 Ssh key를 사용하여 업로드하여야 합니다.
https://github.com/settings/keys 로 접속하면 ssh키를 등록할 수 있습니다.
비공개 저장소인 경우 아래와 같이 노출됩니다. ssh 키 암호를 입력합니다.
> Enter passphrase for key '/Users/.ssh/id_rsa':

암호는 입력해도 입력하는 과정이 보이지 않습니다.
정확히 암호를 입력한 뒤 enter를 눌러주세요. git push가 완료됩니다.

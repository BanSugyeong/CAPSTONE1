# CAPSTONE Design 1
## 깃허브 사용 규칙
- 그 날의 진행사항 날짜를 포함하여 올림 (ex. 2024-03-05)
- 필요한 참고코드는 code에 올려둘테니 참고
- 전달하고 싶은 코드는 압축하여 카톡 혹은 이슈에 올림
- 프로젝트에 도움이 될만한 내용이 있으면 새로운 이슈를 생성해서 올려도 됨

## 데이터
- 각자 수집한 데이터는 이슈의 <데이터 수집>에 올려서 공유
- 데이터는 csv 파일 형태로 수집
- 조금이라도 전처리가 진행된 데이터 파일의 경우 <데이터 전처리>에 올림

# CAPSTONE Design 2
## 추가 및 보완
### 1. 모델 성능 보완
### 2. 웹 페이지 UI 및 구성 추가
- 사이드바 그래프 수정
- 모달창 : 5대 범죄 수치 표시 잘 보이지 않는 것 수정
  - 원그래프로 나타낼 예정
- 전체적인 UI 수정

### 3. 서버 구축
- node.js 말고 다른 서버 제대로 구축하기

## git 사용법
### 초기설정
- git config --global user.email "이메일 주소"
- git config --global user.name "깃허브 이름"
- git remote add origin https://github.com/깃허브 이름/연결할 레파지토리 주소.git
  - ex) git remote add origin https://github.com/BanSugyeong/xxx.git

### pull & push
- git pull origin master
- git add .
- git commit -m "2024-03-10/내용"
- git push origin master

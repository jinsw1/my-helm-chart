
## 나만의 helm chart 를 만들고 github pages 로 배포 해보자 

<img src="./assets/image01.png">

### templates yaml 파일 작성법

<img src="./assets/image02.png">

### 작성한 chart 가 잘 실행되는지 확인해 보자

<img src="./assets/image03.png">

helm repo index docs/ --url https://<나의 github아이디>.github.io/<저장소의 이름>
helm repo index docs/ --url https://jinsw1.github.io/git_my-helm-chart


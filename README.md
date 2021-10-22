# git-flow
git-flow 전략 연습
<br>

### git flow branch

- master : 정식 배포해도 될만큼의 안정적이고 완성 된 코드들을 관리함.
- develop : 새로운 기능의 코드 , 버그 수정을 위한 코드 등. 검증된 개발 코드들을 관리함.
- feature : 새로운 기능 개발 , 버그 수정 코드들을 관리함. feature에서 개발 코드들을 검증하는 과정을 거치고, 완료되면
git flow feature finish 를 통해 develop 브랜치와 병합을 하게 됨.
(develop 브랜치와 병합을 하게되면 feature 브랜치는 삭제)
- release : 배포를 위한 브랜치로, 개선이나 추가 & 수정사항을 반영함. 릴리즈 테스트 후 안정적이다 라고 판단이되면
master 브랜치와 병합 됨. 
- hotfix : 버그 픽스를 최대한 빨리 해야하는 경우에 사용하는 브랜치.

참고링크 : https://hbase.tistory.com/60

### git flow 세팅
- git flow init

<br>

### feature 생성 / 삭제

- git flow feature start <feature 브랜치 이름>
- git flow feature finish <feature 브랜치 이름>
- (feature -> delvelop 병합 후 삭제)

참고링크 : https://inma.tistory.com/112

<br>

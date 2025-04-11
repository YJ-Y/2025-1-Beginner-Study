* 3주차 *
head: 현재 작업 중인 위치 
commit --amend : 마지막 commit의 내용에 변경이 있을 때 사용

* 4주차 *
브랜치 관리의 필요성
- 서로의 작업에 영향을 주지 않기 위함
- main 브랜치의 안전한 관리 필요 

브랜치 전략 
 1. git flow 
 - 브랜치 종류 
  1) main branches
    - main(master): 프로젝트 생성 시 기본으로 생성, 영원히 존재하는 첫 번째 브랜치 
    - develop
    

  2) supporting branches
    - feature: develop 브랜치에서 분기하여 작업
    - release : 배포 준비를 위한 브랜치, 버그 수정 QA 작업 
    - hotfix : 즉각적인 수정이 필요할 경우 


2. github flow
: 수시로 배포되는 상황이 git flow와 어울리지 않는 것을 개선하기 위해 고안
- 브랜치 종류 
  1) main
    - 항상 배포 가능한 상태로 유지 
   
  2) feature
    - 브랜치들을 구분하지 않음 
    - main에서 분기하여 작업 후 다시 main으로 병합 



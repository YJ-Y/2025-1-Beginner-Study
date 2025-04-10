git log 
: commit 기록을 최신 순으로 확인 
--oneline: 각 커밋을 한 줄에 요약 

head 
: 현재 작업 중인 위치 

commit --amend
: 마지막 commit의 내용에 변경이 있을 때 사용 
$ git commit --amend -m "커밋 메시지"
                     --no-edit 
reset
: commit을 제거하는 데 사용 

reset --soft
: 커밋만 취소, 변경사항이 Staging Area로 돌아감 

reset은 commit을 삭제하므로 위험
commit을 공유하는 다른 브랜치에도 영향을 줄 수 있음
commit을 삭제하기보다 생성하여 되돌리는 revert가 안전 

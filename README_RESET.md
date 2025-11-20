# RESET
git reset 명령어는 commit을 취소하는 명령어이다.
revert와는 다르게 취소한 기록을 남기지 않는다.
- 사용법
`git reset --(SOFT/MIXED/HARD) [commit]`
soft: 커밋 취소, staging 상태 유지
mixed: 커밋 취소, staging 취소, local은 변경 상태로 유지
hard: 커밋 취소, staging 취소, local 변경 상태 취소

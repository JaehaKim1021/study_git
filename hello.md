#hello git

## git 명령어 요약

- clone : 원격 저장소 복사
- add : 스테이지 영역에 작업 파일 추가
- commit : 세이브, 스테이지 영역의 파일들을 가지고 커밋(=세이브)을 만들 수 있음
- push : 원격 저장소에 커밋을 업로드


# branch 변경하기

- branch : 기존 내용을 유지한 채 새로운 내용을 추가하고 싶을 때 사용
- checkout : 특정 브랜치(혹은 커밋)으로 돌아가고 싶을 때 사용
- 소스트리의 checkout : 브랜치 이름을 더블클릭하는 것만으로 checkout 가능


# merge test 1
- head branch에 변경사항이 없고
- 병합 대상 branch가 head로부터 시작된 경우
- 바로 병합 가능 = Fast-forward



### 충돌 해결하기
- git 충돌 testing

### branch 만들어서 되돌리기

- reset과 달리 내용이 사라지지 않는다.
- 장점 : 쉽다.
- 단점 : 트리가 지저분해진다.

###revert

- 커밋은 없어지지 않는다.
- 장점: 가장 정석적
- 단점 : 충돌이 발생할 수 있음

## 리버트 되돌리기용

-trash line

# 숫자 야구 게임
## 진행 방법
* 숫자 야구 게임 요구사항을 파악한다.
* 요구사항에 대한 구현을 완료한 후 자신의 github 아이디에 해당하는 브랜치에 Pull Request(이하 PR)를 통해 과제를 제출한다.

## 과제 제출 과정
* [과제 제출 방법](https://github.com/next-step/nextstep-docs/tree/master/precourse)

----

## 기능 목록

0. 게임을 실행한다.
0. 랜덤 정답을 생성한다.
    - 생성 유효성을 검증한다.
        - 양의 정수 여부 ( 1 ~ 9 )
        - 정답 size 정상 여부
0. 정답을 입력한다.
    - 정답 유효성 검사를 한다.
        - 양의 정수 입력 여부
        - 정답 size 일치 여부
0. 볼 카운트를 한다.
    - 스트라이크 카운트 : 숫자 일치 + 위치 일치
    - 볼 카운트 : 숫자 일치 + 위치 불일치
    - 낫싱 카운트 : 숫자 전체 불일치
0. 정답 여부를 체크한다.
    - 스트라이크 카운트 == 정답 size
0. 게임 종료 여부를 입력한다.
    - 0 입력 시 게임 재시작
    - 1 입력 시 게임 종료

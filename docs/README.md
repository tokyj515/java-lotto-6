# 3주차 미션 - 로또 게임

## 로또 번호
- 숫자 범위는 1~45
- 당첨 번호 6개는 사용자에게 입력 받음(,으로 split)
- 범위에서 벗어나면 예외 처리
- 6개가 아니면 예외 처리
- 당첨 번호는 중복되면 안 됨 -> 중복 시 예외 처리
- 보너스 번호 1개는 사용자에게 입력 받음
- 보너스 번호는 입력 받은 당첨 번호와 중복되면 안 됨 -> 중복 시 예외 처리


## 로또 구매
- 1000원 단위
- 1000으로 나눠지지 않을 시 예외 처리
- 로또 1장 당 1000원 -> 횟수 체크하기


## 결과 출력
- 몇 개 일치했는지 개수 체크
- 수익률 체크하기(구매 금액/총 당첨 금액 * 100)
- 수익률은 소수점 첫번째 자리까지 표현하기


## 예외 처리
- [ERROR] 문구로 시작하기
- `IllegalArgumentException`, `IllegalStateException`
## 구현 기능 목록

- [x] 경주할 자동차 이름들을 입력하는 기능
  - [x] 입력 이름 중 5자를 초과하는 이름이 입력된 경우 예외처리
  - [x] 입력 이름 중 문자의 길이가 0인 경우 (`hudi,,donghyun` 또는 `,hudi,donghyun`  등의 경우)
  - [x] `hudi,   ,donghyun` 과 같이 공백만으로 이뤄진 이름을 입력한 경우 예외처리
  - [x] `,` 만 입력하였을 경우의 예외처리
  - [x] 같은 이름이 2개 이상 들어온 경우 예외처리
  - [x] 입력된 자동차 수가 2대보다 작을 경우 (0 ~ 1대) 예외처리
  - [x] 예외가 발생한 경우 에러를 출력하고, 입력을 다시 받는 기능
- [x] 시도할 회수를 입력하는 기능
  - [x] 숫자가 아닌 문자를 입력받을 경우 예외처리 (공백 포함)
  - [x] 양의 정수가 아닌 숫자 (0과 음수) 를 입력 받을 경우 예외처리
  - [x] 예외가 발생한 경우 에러를 출력하고, 입력을 다시 받는 기능
- [x] 개별 자동차 1회 전진 기능
  - [x] 0 ~ 9 사이의 무작위 값을 구하고, 4 이상일 경우에만 전진한다.
- [x] 개별 자동차의 진행도를 출력하는 기능
- [x] 모든 자동차를 사용자가 입력한 횟수만큼 전진하는 기능
- [x] 모든 자동차의 진행도를 출력하는 기능
- [x] 경주가 마무리되면, 우승자를 출력하는 기능
  - [x] 단독 우승자는 단일 이름만 출력되어야 함
  - [x] 공동 우승자는 `,` 로 구분되어 함께 출력되어야 함
  - [ ] 모든 자동차의 전진 거리가 `0` 인 경우 예외처리


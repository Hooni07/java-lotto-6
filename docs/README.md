# 프리코스 미션3 - 자동차 경주

## 기능 요구 사항 & 과제 진행 요구 사항

- start: [java-lotto-6](https://github.com/woowacourse-precourse/java-lotto-6) 저장소를 Fork & Clone해 시작한다.

### 입출력

#### 입력

- 로또 구입금액 입력
    - 1000원 단위로 입력
    - 해당 조건 무시하고 입력할 경우, error 출력
- 당첨 번호 입력
    - 2주차 프리코스 입력방식 참고!
- 보너스 입력 번호 입력

```java

```

#### 출력

- 발행한 로또 수량 및 번호를 출력
    - 오름차순 정렬 필요
    - 입력받은 구입금액을 바탕으로 발행한 로또 수량 설정

```java

```

### 구현할 기능 및 구현 내용

* 구현 조건
    * camp.nextstep.edu.missionutils에서 제공하는 Randoms 및 Console API를 사용하여 구현한다.
        * Random 값 추출: camp.nextstep.edu.missionutils.Randoms의 pickUniqueNumbersInRange()를 활용
        * 사용자가 입력하는 값은 camp.nextstep.edu.missionutils.Console의 readLine()을 활용

#### Lotto class 구현
- 

#### LottoTest 구현

1. 로또 번호에 중복된 숫자가 있으면 예외가 정상적으로 발생하는 test case 구현

```java

```

2. Lotto에 각 상황에 맞는 test code 구현

```java

```

---

## test 결과

1.

2. Test 확인


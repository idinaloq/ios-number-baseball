## iOS 커리어 스타터 캠프

### 숫자야구 프로젝트

### 소개
- 중복되지 않은 랜덤숫자 3개를 생성하고 사용자가 입력한 숫자 3개를 비교해서 순서와 번호를 맞추면 사용자가 승리하는 게임


### 팀원
<<<<<<< HEAD
|idinaloq|
|------|
|![스크린샷 2023-04-24 오후 4 47 09](https://user-images.githubusercontent.com/124647187/235142373-a36360bb-88cd-4bb1-a287-b23b658e5700.png)|

|Erick|
|-----|
|![IMG_6844](https://user-images.githubusercontent.com/109963294/235143560-d5f501e5-872d-4ebf-a748-738b2f68e79b.jpg)|

<br>

## 타임라인

### 4월 24일(월)
- git repository fork 생성
- git clone 및 step0 브랜치 생성
- Flow Chart 생성

### 4월 25일(화)
- Flow Chart를 README에 추가
- Step1 코드 구현
- Step0 + Step1 Pull Request 생성

### 4월 26일(수)
- PR comment에 Reply 추가
- PR 요구사항에 맞게 코드 수정
- Step2 코드 간단하게 구현( SelectMenu함수 추가 및 inputData함수 추가 )

### 4월 27일(목)
- Step2 코드 구현 마무리
- Step2 Pull Request 생성

### 4월 28일(금)
- PR comment에 Reply 추가
- PR 요구사항에 맞게 코드 수정
- README 작성


<br>
=======
- Erick
- idinaloq
>>>>>>> origin/main

## Flow Chart

![제목 없는 다이어그램 drawio-2-2](https://user-images.githubusercontent.com/109963294/235088769-cd1a8df9-7bb5-4832-a9a6-91f217df226d.png)

<br>

## 실행화면

### 메뉴선택

<img width="387" alt="스크린샷 2023-04-28 오후 5 20 41" src="https://user-images.githubusercontent.com/109963294/235095123-7dabef4b-4472-42ed-99e2-63bdffdfdbcc.png">

<<<<<<< HEAD
- 처음 실행을 하면 메뉴가 출력됩니다.
- 1을 입력하면 게임을 시작하고, 2를 입력하면 게임을 종료합니다.

=======
>>>>>>> origin/main
### 사용자의 승리

<img width="387" alt="스크린샷 2023-04-28 오후 5 21 52" src="https://user-images.githubusercontent.com/109963294/235095443-54122a82-a877-491c-99d1-796da5ece470.png">

<<<<<<< HEAD
- 조건에 맞게 숫자를 입력하고, 시도 횟수가 다 끝나기 전에 입력한 숫자와 랜덤숫자가 일치하는 경우 사용자가 승리합니다.

=======
>>>>>>> origin/main
### 컴퓨터의 승리

<img width="387" alt="스크린샷 2023-04-28 오후 5 23 35" src="https://user-images.githubusercontent.com/109963294/235095590-f3deebfb-88cf-4202-aabb-58848d519303.png">

<<<<<<< HEAD
- 조건에 맞게 숫자를 입력하고, 시도 횟수가 다 끝날 때까지 사용자가 승리하지 못한다면 컴퓨터가 승리합니다.

<br>

## 트러블슈팅
### 사용자 입력값이 올바른지 확인
***components***

- String으로 입력받은 값을 split 메서드를 이용해서 공백 1칸 기준으로 나누었으나, 공백이 두 칸 이상 있는 경우에 예외 처리가 되지 않는 문제가 있었습니다.
- 코드를 추가로 작성해서 예외처리를 하는 방법도 있었지만, components 메서드를 사용하여 별도의 코드 작성 없이 정상적으로 예외 처리를 할 수 있었습니다.

***String to Int***
- components로 나눈 입력값을 [String] -> [Int]로 타입 변환을 하려고 했지만 값이 적용되지 않는 오류가 있었습니다.
- for문을 이용해 요소 하나하나에 접근하여 guard문을 이용하여 String to Int로 변환하였습니다.

<br>

### 전달인자 레이블
***전치사 활용***

- 기존에 함수를 만들고, 전달인자 레이블을 생성할 때 ```_```를 이용해서 생략하기만 했습니다. 간단한 함수 같은 경우 전달인자 레이블이 생략되어도 상관 없으나, 함수가 복잡해지면 가독성이 나빠지는 문제가 있었습니다.
- 전치사를 활용하여 전달인자 레이블에 추가하면, 함수명과 문장처럼 이어져 가독성을 높일 수 있어 전달인자 레이블에 전치사를 추가했습니다.

<br>

### 네이밍
***함수, 변수 네이밍***
- bool타입 변수 ```resultCheck```에 접두사로 ```is```를 사용하지 않았던 부분이 있었고, 남은 시도 횟수 같은 경우는 변수명을 ```tryCount```로 선언하여 더 정확한 네이밍이 부족했습니다.
- 네이밍 규칙에 대해 다시 한 번 공부하고 ```resultCheck```는 ```isResultCheck```로, ```tryCount```는 ```remainTryCount```로 수정하였습니다.

<br>

## 팀 프로젝트 회고
=======
<br>

# 팀 프로젝트 회고
>>>>>>> origin/main

## 참여자
- Erick
- idinaloq

<br>

## 배운점
- Erick: git 명령어에 대해 생소했는데, 많이 이해하고 사용해볼 수 있었던 시간이었습니다. 반복되는 작업을 재귀함수가 아닌 while로 처리하는 등 생각하지 못 했던 방법을 배우게 되었습니다.
- idinaloq: 과거 1인 개발자로 일하고 있을 때 해볼 수 없었던 협업을 처음으로 해보았고, 거기에 더 나아가 프로젝트 관리까지 같이 할 수 있었습니다.
<br>

## 좋았던 점
- Erick: 협업이라는 것을 처음 접하여 팀원에 코드를 보며 더 깊게 생각하고 이해하고 기능을 구현하는 것이 아닌 어떤 코드가 더 괜찮은 코드인지 보기 좋은 코드인지 생각할 수 있어서 좋았습니다. 그리고 이디나로크가 초반에 git에 관한 도움을 많이 줘서 고마웠습니다.
- idinaloq: 짝 프로그래밍을 해야되서 오래 걸릴 줄 알았는데, 막히는 부분에서 서로 보완이 되어서 결과적으로 혼자 할 보다 시간이 오래걸리거나 하지 않았다고 생각하고, 다른 사람이 실시간으로 작성하는 코드와 왜 그렇게 작성했는지 알게된 점이 좋았습니다.

<br>

## 아쉬웠던 점
- Erick: 기능을 구현하는 방법과 방향이 달라서 생기는 의견차이(?) 때문에 시간이 조금은 더 걸렸던 것 같습니다.
- idinaloq: 월,화,목,금 중간에 협동수업이 있어서 이 부분때문에 약간 흐름이 끊기는 감이 있었다고 생각해서 조금 아쉬웠지만, 다음 주 부터는 주 2회 수업이기 때문에 미리 조율하면 괜찮을 것 같다고 생각합니다.
- idinaloq: 코드 작성할 때 스타일이 많이 달라서 어느정도까지 내가 원하는 대로 해도 되는지, 서로 어떻게 정할지에 대해 미리 협의하고 시작하지 않았던 점이 조금 아쉬워서 다음 프로젝트부터는 변수 이름, 코드 개행 등 전체적으로 정하고 가는 편이 좋다고 생각합니다.

<br>

## 참고자료

- https://velog.io/@folw159/Swift-components와-split의-차이
- https://developer.apple.com/documentation/swift/set
<<<<<<< HEAD
- https://velog.io/@lhj26/Swift-if-vs-if-let-vs-guard-let
=======
- https://velog.io/@lhj26/Swift-if-vs-if-let-vs-guard-let
>>>>>>> origin/main

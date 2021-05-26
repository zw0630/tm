 Teachable Machine Image Project
===
## 😷 마스크 착용 여부 파악 프로그램 😷
### 주제 선정이유
```
최근 코로나19로 집 바깥을 외출할 때 마스크를 꼭 착용해야 하고 착용하지 않을 시 시설 출입이 금지당하거나
과태료가 부과되는 등 마스크 착용의 중요성이 높아지고 있다.
티쳐블 머신을 이용하여 마스크 착용 여부를 판단하는 프로그램을 만들어 보고 이를 개선한다면
실제 생활에서도 사용될 수 있을 것이라고 생각하여 주제를 선정하게 되었다.
```
### 작성소감
~~~
지난 시간에 한 번 해 보아서 그런지 조금 더 쉽고 빠르게 할 수 있어서 뿌듯했다.
만들어낸 프로그램이 잘못된 마스크 착용 사례를 걸러내지 못하는 등의 한계가 있었지만
생각보다 정확하고 유용하게 만들어진 것 같아 신기하다.
~~~

### 1. 이미지 모으기

+ 학습에 필요한 이미지를 모음
+ 크롬 확장 프로그램 Download All Image 활용
+ 학습과 관련없는 사진, 일러스트 등 삭제

|착용여부|이미지 개수|
|----|----|
|착용|181|
|미착용|182|

### 2. 이미지 프로젝트

+ 분류될 laber에 해당하는 class명을 각각 마스크 착용, 마스크 미착용으로 변경
+ class별로 마스크를 착용하고 있는 사람의 이미지, 착용하지 않은 사람의 이미지 업로드

![마스크 착용](https://www.google.com/imgres?imgurl=https%3A%2F%2Fwww.healthychildren.org%2FSiteCollectionImagesArticleImages%2Fyoung-girl-with-hand-made-face-mask.jpg%3FRenditionID%3D6&imgrefurl=https%3A%2F%2Fwww.healthychildren.org%2FEnglish%2Fhealth-issues%2Fconditions%2FCOVID-19%2FPages%2FMask-Mythbusters.aspx&tbnid=XIHmBFAWxQoumM&vet=12ahUKEwiy1IDPqOfwAhUEc5QKHbowA-gQMygVegUIARCgAg..i&docid=I_3EP064b6zH1M&w=1200&h=1200&q=mask&ved=2ahUKEwiy1IDPqOfwAhUEc5QKHbowA-gQMygVegUIARCgAg)
![마스크 미착용](https://www.google.com/imgres?imgurl=https%3A%2F%2Fimg1.daumcdn.net%2Fthumb%2FR720x0.q80%2F%3Fscode%3Dmtistory2%26fname%3Dhttp%253A%252F%252Fcfile21.uf.tistory.com%252Fimage%252F99F5E2375E099993185C19&imgrefurl=https%3A%2F%2Fbioinformaticsandme.tistory.com%2F272&tbnid=AtpzDAjBX7YnoM&vet=12ahUKEwjl7rH5qOfwAhXTAqYKHc2yCRQQMygnegUIARCMAg..i&docid=_goHGSmc0SUAqM&w=720&h=721&q=%E3%85%94%E3%84%B7%E3%84%B1%EB%82%B4%E3%85%9C&ved=2ahUKEwjl7rH5qOfwAhXTAqYKHc2yCRQQMygnegUIARCMAg)

### 3. 학습 후 테스트

|실제 착용 여부|OUTPUT| |
|----|----|----|
|착용|착용|✔️|
|미착용|미착용|✔️|
|올바르지 못한 착용|착용|❌|

### 4. 모델 내보내기

+ 티쳐블머신에서 링크 생성하여 확인

[Teachable Machine](https://teachablemachine.withgoogle.com/models/3ZMhnIea8/)

### 5. Github에서 서비스하기

[Github](https://zw0630.github.io/tm/)

---

5월 20일
===
## 배운 점
티처블머신을 이용하여 BTS 멤버들 중 세 명의 사진을 학습시키고,

입력한 사진이 멤버 중 누구와 가장 유사한지 알아보는 인공지능 프로그램을 만들었다.

깃허브 주소를 만들어 자신이 만든 프로그램을 어떻게 서비스할 수 있는지 알아보고

마크다운을 작성할 때 사용되는 문법에 대해 배우고 사용해보았다.

---
## 느낀 점
인공지능 프로그램을 만들고 이용하는 것이 어려울 것이라고만 생각하였는데

생각보다 쉽고 간단하게 만들 수 있어서 놀랍다.

티처블머신과 깃허브, 마크다운을 이용하여

무엇을 배우고 어떤 프로그램을 만들 수 있을지 궁금하다.

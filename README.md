# DGSWMarble
1학년 c언어 수행평가로 만든 대소고를 배경으로 만든 부루마블

0. 정문
1. 운동장
2. 체육관
3. 사회전용실
4. 포춘카드
5. 수학전용실
6. 시청각실
7. 무인택배함
8. 기숙사
9. 방송실
10. 창의공작실
11. 모바일프로그래밍실
12. 포춘카드
13. 윈도우프로그래밍실
14. 오케스트라실
15. 도서관
16. 급식실
17. 언턴드
18. 스타봇
19. 세븐랩스
20. 포춘카드
21. CnS
22. ducami
23. b1nd
24. 귀가 버스
25. 사감실
26. 교장실
27. 재덕정
28. 포춘카드
29. 대니산
30. 1학년1반
31. 박병관

<br>

## 실행
유저 수를 입력받고 랜덤으로 순서를 부여해준다

![실행1](https://user-images.githubusercontent.com/85085375/170060756-050ae24e-9572-44d5-b123-dd151d6b81fb.gif)

## 진행
주사위 세기를 1~5 중 입력해서 정한다
주사위 세기는 아래의 코드처럼 `power(1~5중 입력한 수) + rand함수` 로 주사위 세기에 따른 주사위 생성을 했다

![주사위 세기](https://user-images.githubusercontent.com/85085375/170153379-d6ac6805-2d51-4ead-b043-7d0e3c74ecaa.png)

![기본 진행](https://user-images.githubusercontent.com/85085375/170061154-2ee6591d-d405-44d1-b19d-d7c89a296bbf.gif)

### 월급
0(정문)을 지날 때 마다 월급을 받고, 정문에 딱 도착했을 때 선택한 땅을 건설할 수 있다

![정문](https://user-images.githubusercontent.com/85085375/170148411-e682a0e9-dc83-4952-aa61-2c734e0e4fa3.gif)

### 무인도
8(기숙사)에 가면 한 턴이 넘어가게 된다

![무인도](https://user-images.githubusercontent.com/85085375/170148343-217afd49-bd45-4fbf-bc39-d5da4b3e225b.gif)

### 올림픽
16(급식소)에서 선택한 땅의 가격을 2배로 할 수 있다

![올림픽](https://user-images.githubusercontent.com/85085375/170179759-a87e44da-ceaf-4d4a-8055-56a6df9f767f.gif)


### 세계여행
24(귀가버스)에 가면 다음턴에 선택한 땅으로 이동할 수 있다

![세계여행](https://user-images.githubusercontent.com/85085375/170171886-b45ae470-5eec-4633-b7b5-4c6a8951ef58.gif)

### 포춘카드
10가지 포춘카드(한 번 더, 건물 파괴, 무인도 이동, 건물 변경, 세계 여행, 출발점, 기숙사, 체육관, 다른 플레이어의 돈 받기, 모든 플레이어 운동장으로 모이기)

건물파괴와 땅변경은 아래와 같다
![건물파괴](https://user-images.githubusercontent.com/85085375/170173286-409910ea-8216-44ad-bcdc-5f3240b114fa.gif)
![땅변경](https://user-images.githubusercontent.com/85085375/170173311-35edc11f-4181-4bc5-8632-8e1656e6eed0.png)

### 파산
0원 이하가 되면 파산, 1명을 제외하고 다 파산이 된다면 끝이 난다

![파산](https://user-images.githubusercontent.com/85085375/170180345-d6436c9e-51ba-4381-917a-c288d1961e5f.gif)

## 예외처리
기본적인 수 관련 예외처리는 되어있고 포춘카드 관련은 되어있지 않다

![예외처리](https://user-images.githubusercontent.com/85085375/170148390-e9619a41-8b1d-4050-94cc-f2e88867991f.gif)

아직 안 된건 포춘카드의 건물변경 다음 실행이 안 되고, 파괴할 땅이 없을 때 실행이 안 된다


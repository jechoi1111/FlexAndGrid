## 부모 = container
## 자식 = item

`````
<div class="container">
	<div class="item">helloflex</div>
	<div class="item">abc</div>
	<div class="item">helloflex</div>
</div>
`````

- 메인축 : flex item 이 배치 된 방향
- 교차축 : 메인축과 수직에 위치

---

## flex-direction
아이템들이 배치되는 축의 방향을 결정

ex) row(기본), column, row-reverse, column-reverse

1. ### row
    아이템들이 행(가로) 방향 배치
2. ### row-reverse
    아이템들이 역순으로 가로 배치
3. ### column
    아이템들이 열(세로) 방행 배치
4. ### column-reverse
    아이템들이 역순으로 세로 배치

---

## flex-wrap
컨테이너가 더 이상 아이템들을 한 줄에 담을 여유 공간이 없을 때,
아이템 줄바꿈을 어떻게 할지 결정하는 속성

ex) nowrap(기본), wrap, wrap-reverse

1. ### nowrap
   줄바꿈 X
2. ### wrap
   줄바꿈 O
3. ### wrap-reverse
   줄바꿈을 하지만 아이템을 역순 배치

---


## flex-flow
flex-direction과 flex-wrap을 한꺼번에 지정할 수 있는 단축 속성

순서는 flex-direction, flex-wrap 순이다.

---


## justify-content
메인축 위에서 item 정렬

ex) flex-start(기본), flex-end, center, space-between, space-around, space-evenly

1. ### flex-start
   아이템을 시작점으로 정렬
2. ### flex-end
   아이템을 끝점으로 정렬
3. ### center
   아이템을 가운데로 정렬
4. ### space-between
   아이템들 사이에 균일한 간격 추가
5. ### space-around
   아이템들 둘레에 균일한 간격 추가
6. ### space-evenly
    아이템들 사이와 양 끝에 균일한 간격 추가
   (_IE와 Edge에서는 지원 X_)

---

## align
수직축 위에서 item 정렬

ex) stretch(기본), flex-start, flex-end, center, baseline

1. ### stretch
   아이템이 수직 방향으로 끝까지 늘어남
2. ### flex-start
   아이템들을 시작점으로 정렬
3. ### flex-end
   아이템들을 끝으로 정렬
4. ### center
   아이템들을 가운데로 정렬
5. ### baseline
   아이템들을 텍스트 베이스라인 기준으로 정렬

---

## align-content
flex-wrap: wrap;이 설정된 상태에서, 아이템들의 행이 2줄 이상
되었을 때의 수직 축 방향 정렬을 결정하는 속성

ex) stretch(기본), flex-start, flex-end, center, space-between, space-around, space-evenly

1. ### stretch
   아이템이 수직 방향으로 끝까지 늘어남
2. ### flex-start
   아이템들을 시작점으로 정렬
3. ### flex-end
   아이템들을 끝으로 정렬
4. ### center
   아이템들을 가운데로 정렬
5. ### space-between
   아이템들 사이에 균일한 간격 추가
6. ### space-around
   아이템들 둘레에 균일한 간격 추가
7. ### space-evenly
   아이템들 사이와 양 끝에 균일한 간격 추가
   (_IE와 Edge에서는 지원 X_)


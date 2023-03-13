# 버블 정렬 (Bubble Sort)
<br></br>
## :point_up: 정의
* 이웃한 두 요소의 대소 관계를 비교하고 필요에 따라 교환을 반복하는 
알고리즘으로 단순 교환 정렬(straight exchange sort)이라고도 함

<br></br>
<img src = "https://user-images.githubusercontent.com/101400945/224753301-07498961-4aa1-4113-b789-4d8b46c9ac21.jpg" width="90%" height="90%">


1. 총 3번의 Pass를 통해 [1, 3, 4, 6, 7]로 오름차순 정렬을 만들 수 있음
2. 사진에서는 모든 비교과정을 표시하였지만, 이미 정렬된 수와의 비교는 굳이 진행하지 않아도 됨

<br></br>


## :v: 장점
* 구현이 매우 간단하고, 소스코드가 직관적
* 정렬하고자 하는 배열 안에서 교환하는 방식이므로, 다른 메모리 공간을 필요로 하지 않음
=> 제자리 정렬(in-place sorting)
* 안정 정렬(Stable Sort)

<br></br>
## :ok_hand: 단점
* 시간복잡도가 최악, 최선, 평균 모두 O(n^2)으로, 굉장히 비효율적
* 정렬 되어있지 않은 원소가 정렬 되었을 때 자리로 가기 위해, 교환 연산(swap)이 많이 일어남

<br></br>

## :metal: 관련 문제 && 관련 자료
<a href="https://wodlszz.tistory.com/13">jaein's tistory</a></p>


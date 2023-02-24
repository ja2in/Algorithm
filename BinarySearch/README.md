# 이진검색 (Binary Search)
<br></br>
## :point_up: 정의
* 이진검색은 요소가 오름차순으로 정렬된 배열인 상태에서 검색하는 알고리즘
* 오름차순으로 정렬된 정수의 리스트를 같은 크기의 두 부분 리스트로 나누고 필요한 부분에서만 탐색
* 리스트의 중간 부분에 찾는 원소가 있는지 확인, 없으면 위쪽에 있는지 아래쪽에 있는지 판단하여 맨 앞부터 검색하거나 중간부터 검색
<br></br>
<img src = "https://user-images.githubusercontent.com/101400945/221161087-46c4b124-6c17-4e60-b9d5-291fca85ff32.jpg" width="70%" height="70%">

1. index 0과 10을 기준으로 2로 나눈 값 index 5를 살펴본다.
2. index 5의 값이 찾으려는 39보다 작으므로 index 5 이하는 더 이상 살피지 않는다.
3. index 6과 10을 기준으로 2로 나눈 값 index 8을 살펴본다.
4. index 8의 값이 찾으려는 39보다 크므로 index 8 이상은 더 이상 살피지 않는다.
5. index 6과 7을 살펴 원하는 값 39를 찾는다.

<br></br>


## :v: Arrays.binarySearch
* 자바에서 제공하는 이진 검색 표준 라이브러리
* 이진 검색 메서드를 직접 작성할 필요가 없음
* 배열 요소의 자료형과 관계없이 검색할 수 있음
* 검색에 실패한 경우, 삽입 포인트를 x라고 할 때 반환값은 -x -1이 됨

<br></br>
## :ok_hand: Method
```java
1. static int binarySearch(byte[] a, byte key)
2. static int binarySearch(char[] a, char key)
3. static int binarySearch(double[] a, double key)
4. static int binarySearch(float[] a, float key)
5. static int binarySearch(int[] a, int key)
6. static int binarySearch(long[] a, long key)
7. static int binarySearch(short[] a, short key)
8. static int binarySearch(Object[] a, Object key)
9. static <T> int binarySearch(T[] a, T key, Comparator <? super T> c)
```

<br></br>

## :metal: 관련 문제 && 관련 자료
<a href="https://www.acmicpc.net/problem/1920" rel="nofollow">BOJ [NO.1920]</a></p>
<a href="https://wodlszz.tistory.com/10">jaein's tistory</a></p>

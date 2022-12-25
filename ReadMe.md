# Level 2

### ⛳️ GOAL
좀 더 어려운 `그리디`, `다이나믹 프로그래밍`, `구현`과 `그래프`와 관련된 알고리즘, `완전 탐색`, `백트랙킹`, `이분 탐색` 을 이용하여 `최적해 문제`를 `판정 문제`로 바꾸어 푸는 법을 공부해봅시다. 대부분의 코딩 테스트는 해당 레벨 정도의 난이도로 출제됩니다. 

### ❔판정 문제와 최적해 문제
최적해 문제는 주어진 조건에 맞는 최적의 해를 찾는 문제입니다. 예를 들면 배열에 존재하는 최댓값, 1000원으로 가장 많은 살 수 있는 물건의 개수 같은 문제들이 있습니다.

판정 문제는 단순하게 보자면 참이냐 거짓이냐로 볼 수 있습니다. 즉, 예-아니오로 대답을 할 수 있는 문제들을 말합니다. 예를 들면 `10은 4로 나누어 떨어지는가?` 와 같은 문제들이 있습니다.

최적해 문제를 판정 문제로 바꾸어 푸는 예로는 `정수만 존재하는 배열 A에 존재하는 최댓값을 구하는 문제` 를 `배열 A에 x보다 큰 숫자가 존재하는가?` 라는 판정 문제 `Q(x)`로 바꾼다면 `Q(x-1)` 이 참이고 `Q(x)` 는 거짓인 `x` 를 찾으면 됩니다.

이러한 판정 문제를 이분 탐색으로 풀기 위해선 어떻게 해야 할까요?? 이분 탐색을 사용하기 위해선 어떤 상황이여야 하는지 생각해봅시다!🔔

## :school_satchel: 문제 리스트

### 💰그리디 
1. [BOJ 행렬](https://www.acmicpc.net/problem/1080)
2. [BOJ 소트](https://www.acmicpc.net/problem/1083)
3. [BOJ 팔](https://www.acmicpc.net/problem/1105)
4. [BOJ 단어수학](https://www.acmicpc.net/problem/1339)
5. [BOJ 카드 정렬하기](https://www.acmicpc.net/problem/1715)
6. [BOJ 회의실](https://www.acmicpc.net/problem/1374)
7. [BOJ 수 분해](https://www.acmicpc.net/problem/1437)
8. [BOJ 도서관](https://www.acmicpc.net/problem/1461)
9. [BOJ 연료 채우기](https://www.acmicpc.net/problem/1826)

### ✏️다이나믹 프로그래밍
1. [BOJ 호텔](https://www.acmicpc.net/problem/1106)
2. [BOJ RGB거리](https://www.acmicpc.net/problem/1149)
3. [BOJ 동물원](https://www.acmicpc.net/problem/1309)
4. [BOJ 축구](https://www.acmicpc.net/problem/1344)
5. [BOJ 수확](https://www.acmicpc.net/problem/1823)
6. [BOJ ACM Craft](https://www.acmicpc.net/problem/1005)
7. [BOJ 뉴스 전하기](https://www.acmicpc.net/problem/1135)
8. [BOJ 내리막 길](https://www.acmicpc.net/problem/1520)
9. [BOJ 안녕](https://www.acmicpc.net/problem/1535)

### ▶️ 구현
1. [BOJ 소용돌이 예쁘게 출력하기](https://www.acmicpc.net/problem/1022)
2. [BOJ 한 줄로 서기](https://www.acmicpc.net/problem/1138)
3. [BOJ 스타트링크 타워](https://www.acmicpc.net/problem/1089)
4. [BOJ 피자 굽기](https://www.acmicpc.net/problem/1756)
5. [BOJ 타일 위의 원](https://www.acmicpc.net/problem/1709)
6. [BOJ 소코반](https://www.acmicpc.net/problem/4577)
7. [BOJ 톱니바퀴](https://www.acmicpc.net/problem/14891)
8. [BOJ 내리막길](https://www.acmicpc.net/problem/14890)
9. [BOJ 드래곤 커브](https://www.acmicpc.net/problem/15685)
10. [BOJ 아기 상어](https://www.acmicpc.net/problem/16236)

### ♻️ 그래프
1. [BOJ DFS와 BFS](https://www.acmicpc.net/problem/1260)
2. [BOJ 최소 스패닝 트리](https://www.acmicpc.net/problem/1197)
3. [BOJ 트리](https://www.acmicpc.net/problem/1068)
4. [BOJ 게임](https://www.acmicpc.net/problem/1103)
5. [BOJ 특정한 최단 경로](https://www.acmicpc.net/problem/1504)
6. [BOJ 이분 그래프](https://www.acmicpc.net/problem/1707)
7. [BOJ 숨바꼭질](https://www.acmicpc.net/problem/1697)
8. [BOJ 벽 부수고 이동하기](https://www.acmicpc.net/problem/2206)
9. [BOJ 네트워크 복구](https://www.acmicpc.net/problem/2211)
10. [BOJ 키 순서](https://www.acmicpc.net/problem/2458)
11. [BOJ 저울](https://www.acmicpc.net/problem/10159)
12. [BOJ 가운데서 만나기](https://www.acmicpc.net/problem/21940)
13. [BOJ 백도어](https://www.acmicpc.net/problem/17396)
14. [BOJ 타임머신](https://www.acmicpc.net/problem/11657)
15. [BOJ 골목길](https://www.acmicpc.net/problem/1738)
16. [BOJ 집합의 표현](https://www.acmicpc.net/problem/1717)
17. [BOJ 피리 부는 사나이](https://www.acmicpc.net/problem/16724)
18. [BOJ 유니온 파인드 복원](https://www.acmicpc.net/problem/22996)
19. [BOJ 트리의 순회](https://www.acmicpc.net/problem/2263)
20. [BOJ 전화번호 목록](https://www.acmicpc.net/problem/5052)
21. [BOJ 회사 문화1](https://www.acmicpc.net/problem/14267)
22. [BOJ 트리 색칠하기](https://www.acmicpc.net/problem/24230)

### ➿ 완전 탐색과 백트랙킹
1. [BOJ 감시](https://www.acmicpc.net/problem/15683)
2. [BOJ 가르침](https://www.acmicpc.net/problem/1062)
3. [BOJ 게리멘더링](https://www.acmicpc.net/problem/17471)
4. [BOJ 연산자 끼워넣기(2)](https://www.acmicpc.net/problem/15658)
5. [BOJ 0 만들기](https://www.acmicpc.net/problem/7490)
6. [BOJ 제곱수 찾기](https://www.acmicpc.net/problem/1025)
7. [BOJ 산업 스파이의 편지](https://www.acmicpc.net/problem/3671)
8. [BOJ 폰 호석만](https://www.acmicpc.net/problem/21275)
9. [BOJ 도도의 음식 준비](https://www.acmicpc.net/problem/22953)
10. [BOJ 숌 사이 수열](https://www.acmicpc.net/problem/1469)
11. [BOJ 등비수열의 합](https://www.acmicpc.net/problem/23848)
12. [BOJ 소-난다!](https://www.acmicpc.net/problem/19699)

### 🧭 이분 탐색
1. [BOJ 나무 자르기](https://www.acmicpc.net/problem/2805)
2. [BOJ 두 배열의 합](https://www.acmicpc.net/problem/2143)
3. [BOJ 개똥벌레](https://www.acmicpc.net/problem/3020)
4. [BOJ 구간 나누기 2](https://www.acmicpc.net/problem/13397)
5. [BOJ 공정 컨설턴트 호석](https://www.acmicpc.net/problem/22254)
6. [BOJ 연료가 부족해](https://www.acmicpc.net/problem/20293)
7. [BOJ 누적거리](https://www.acmicpc.net/problem/22345)
8. [BOJ 두 수의 합](https://www.acmicpc.net/problem/9024)
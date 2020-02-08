# PS 향유회

![PS/KakaoTalk_Image_2019-12-09-09-30-29_002.jpeg](PS/KakaoTalk_Image_2019-12-09-09-30-29_002.jpeg)
# 채팅방 링크

[https://open.kakao.com/o/g3antjMb](https://open.kakao.com/o/g3antjMb)

# 노션 링크

[https://www.notion.so/PS-da8977089c2344dba9bdbc3d0188d286](https://www.notion.so/PS-da8977089c2344dba9bdbc3d0188d286)

# 깃허브 링크

[https://github.com/sesang06/problem-solving-teatime](https://github.com/sesang06/problem-solving-teatime)

- 노션의 미러버전으로, 일이주에 한번 정도만 커밋됩니다.

# 규칙

- 하루에 한문제씩 향유합니다.
- 무슨 문제를 향유할지는 의견이 없으면 제가 제시합니다.
- 의견 제안은 제가 아침에 새로운 향유문제를 올리기 전까지입니다.
- 낮에는 (2시 ~8시) 풀고 인증합니다.
- 어려운 문제가 나왔을 때는, 4시부터 서로 힌트를 주고받습니다.
- 밤 8시 부터 푼 문제의 코드를 공개합니다.

# 항유회를 즐기는 방법

- 점심 시간에 중상급 한 문제를 풀기
- 점심 시간에 중하급 두 문제를 풀기
- 특이한 언어로 중하급 두 문제를 풀기
- 주중에 나온 문제를 주말에 몰아 풀고 올리기

# 뉴비 입문

## 서적

- 종만북
    - [https://book.algospot.com/](https://book.algospot.com/)
- 탑코더 알고리즘 트레이닝
    - [http://m.hanbit.co.kr/store/books/book_view.html?p_code=B9653641350](http://m.hanbit.co.kr/store/books/book_view.html?p_code=B9653641350)

## 사이트

- 그릭포그릭
    - [https://www.geeksforgeeks.org/](https://www.geeksforgeeks.org/)

- 문제집
    - [https://solved.ac/problems/](https://solved.ac/problems/)

# 플랫폼

- 중상급 한 문제 : 백준
    - [https://www.acmicpc.net/](https://www.acmicpc.net/)
- 중하급 두 문제 : 릿코드
    - [https://leetcode.com/](https://leetcode.com/)

# 향유문제

# 구글 코드 잼 :)

구글 코드잼의 등록이 2020년 3월 3일부터 열립니다 :) 예선은 통과하도록 화이팅해 봅시다.

[https://codingcompetitions.withgoogle.com/codejam/schedule](https://codingcompetitions.withgoogle.com/codejam/schedule)

### 2020년 2월 7일, 8일

- 중하급
    - [https://programmers.co.kr/learn/courses/30/lessons/42576](https://programmers.co.kr/learn/courses/30/lessons/42576)
        - 풀이
            - [https://sas-study.tistory.com/2](https://sas-study.tistory.com/2)
    - [https://programmers.co.kr/learn/courses/30/lessons/42584](https://programmers.co.kr/learn/courses/30/lessons/42584)
        - 풀이
            - [https://sas-study.tistory.com/256](https://sas-study.tistory.com/256)
- 중상급
    - [https://www.acmicpc.net/problem/12169](https://www.acmicpc.net/problem/12169)
    - 풀이
        - 해당 코드잼에서 가장 어려웠던 문제 :(
        - [https://code.google.com/codejam/contest/6224486/dashboard#s=a&a=1](https://code.google.com/codejam/contest/6224486/dashboard#s=a&a=1)

### 2020년 2월 6일

- 중하급
    - [https://www.acmicpc.net/problem/11047](https://www.acmicpc.net/problem/11047)
    - [https://leetcode.com/problems/two-city-scheduling/](https://leetcode.com/problems/two-city-scheduling/)
- 중상급
    - [https://www.acmicpc.net/problem/15422](https://www.acmicpc.net/problem/15422)
    - 풀이
        - 다익스트라 문제, 일반적인 다익스트라는 {거리, 인덱스} 를 큐에 집어넣는다면, 이 문제는 {거리, 인덱스, 비행기 이용 여부} 를 큐에 집어 넣는다.
        - 다음 최단 거리를 통할 때, 비행기를 향해 간다면,
            - 비행기를 이미 이용했을 경우 갱신하지 않는다.
            - 비행기를 이용하지 않았을 경우 {거리, 인덱스, true} 를 큐에 넣는다.
        - [http://boj.kr/8e70ff08c58d4599b0f33b62267b3d11](http://boj.kr/8e70ff08c58d4599b0f33b62267b3d11)

### 2020년 2월 5일

구글 코드잼 예선 :)

- 중하급
    - [https://www.acmicpc.net/problem/14788](https://www.acmicpc.net/problem/14788)
- 중상급
    - [https://www.acmicpc.net/problem/14793](https://www.acmicpc.net/problem/14793)
    - 풀이
        - [https://www.youtube.com/watch?v=Y7GGwEKFboA](https://www.youtube.com/watch?v=Y7GGwEKFboA)
        - 화장실을 하나의 구간으로 보고, 이용한 화장실을 기준으로 구간을 계속 잘라간다고 생각한다.
        - 우선순위 큐에 현재 비어 있는 연속된 화장실의 구간을 집어 넣는다. 예를 들어, 처음에는 {0, n} 을 집어 넣는다.
        - 큐에서 꺼내서, 정중앙을 뺀 나머지 두 구간으로 만든 뒤 다시 큐에 넣는 작업을 반복한다. 예를 들어, {0, n} 을 빼서 {0, n/2}, {n/2 + 1, 0} 을 집어 넣는다.

### 2020년 2월 4일

- 중하급
    - [https://www.acmicpc.net/problem/2798](https://www.acmicpc.net/problem/2798)
    - [https://www.acmicpc.net/problem/2231](https://www.acmicpc.net/problem/2231)
- 중상급
    - [https://www.acmicpc.net/problem/3015](https://www.acmicpc.net/problem/3015)
    - 풀이
        - [https://sesang06.tistory.com/169](https://sesang06.tistory.com/169)

### 2020년 2월 2, 3일

- 중하급
    - [https://www.acmicpc.net/problem/2562](https://www.acmicpc.net/problem/2562)
    - [https://www.acmicpc.net/problem/1931](https://www.acmicpc.net/problem/1931)
- 중상급
    - [https://www.acmicpc.net/problem/15457](https://www.acmicpc.net/problem/15457)

### 2020년 2월 1일

- 중하급
    - [https://leetcode.com/problems/4sum-ii/](https://leetcode.com/problems/4sum-ii/)
- 중상급
    - [https://www.acmicpc.net/problem/17495](https://www.acmicpc.net/problem/17495)

### 2020년 1월 31일

- 중하급
    - [https://leetcode.com/problems/two-sum/](https://leetcode.com/problems/two-sum/)
- 중상급
    - [https://www.acmicpc.net/problem/15459](https://www.acmicpc.net/problem/15459)

### 2020년 1월 30일

- 중하급
    - [https://leetcode.com/problems/sort-array-by-parity-ii/](https://leetcode.com/problems/sort-array-by-parity-ii/)
- 중상급
    - [https://www.acmicpc.net/problem/15758](https://www.acmicpc.net/problem/15758)

### 2020년 1월 29일

- 중하급
    - [https://www.acmicpc.net/problem/17626](https://www.acmicpc.net/problem/17626)
- 중상급
    - [https://www.acmicpc.net/problem/12013](https://www.acmicpc.net/problem/12013)

### 2020년 1월 28일

- 중하급
    - [https://leetcode.com/problems/range-sum-of-bst/](https://leetcode.com/problems/range-sum-of-bst/)
    - [https://www.acmicpc.net/problem/2739](https://www.acmicpc.net/problem/2739)
- 중상급
    - [https://www.acmicpc.net/problem/1081](https://www.acmicpc.net/problem/1081)

### 2020년 1월 26일

- 중하급
    - [https://www.acmicpc.net/problem/10816](https://www.acmicpc.net/problem/10816)
- 중상급
    - [https://www.acmicpc.net/problem/14637](https://www.acmicpc.net/problem/14637)

    ![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/8be540e2-f43e-4a47-ae4a-ce69b8806563/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/8be540e2-f43e-4a47-ae4a-ce69b8806563/Untitled.png)

### 2020년 1월 24일

- 중하급
    - [https://leetcode.com/problems/maximum-69-number/](https://leetcode.com/problems/maximum-69-number/)
- 중상급
    - [https://www.acmicpc.net/problem/1604](https://www.acmicpc.net/problem/1604)

### 2020년 1월 23일

- 중하급
    - [https://leetcode.com/problems/maximum-69-number/](https://leetcode.com/problems/maximum-69-number/)
- 중상급
    - [https://www.acmicpc.net/problem/2637](https://www.acmicpc.net/problem/2637)

### 2020년 1월 22일

- 중하급
    - [https://leetcode.com/problems/combination-sum-ii/](https://leetcode.com/problems/combination-sum-ii/)
- 중상급
    - [https://www.acmicpc.net/problem/17192](https://www.acmicpc.net/problem/17192)

### 2020년 1월 21일

- 중하급
    - [https://leetcode.com/problems/binary-number-with-alternating-bits/](https://leetcode.com/problems/binary-number-with-alternating-bits/)
- 중상급
    - [https://www.acmicpc.net/problem/17612](https://www.acmicpc.net/problem/17612)

### 2020년 1월 20일

- 중하급
    - [https://leetcode.com/problems/target-sum/](https://leetcode.com/problems/target-sum/)
- 중상급
    - [https://www.acmicpc.net/problem/2272](https://www.acmicpc.net/problem/2272)

### 2020년 1월 19일

- 중하급
    - [https://leetcode.com/problems/implement-strstr/](https://leetcode.com/problems/implement-strstr/)
- 중상급
    - [https://www.acmicpc.net/problem/1797](https://www.acmicpc.net/problem/1797)

### 2020년 1월 18일

- 중하급
    - [https://leetcode.com/problems/top-k-frequent-elements/](https://leetcode.com/problems/top-k-frequent-elements/)
- 중상급
    - [https://www.acmicpc.net/problem/2086](https://www.acmicpc.net/problem/2086)

### 2020년 1월 17일

- 중하급
    - [https://leetcode.com/problems/fizz-buzz/](https://leetcode.com/problems/fizz-buzz/)
- 중상급
    - [https://www.acmicpc.net/problem/14743](https://www.acmicpc.net/problem/14743)

### 2020년 1월 15일, 16일

- 중하급
    - [https://leetcode.com/problems/perfect-squares/](https://leetcode.com/problems/perfect-squares/)
- 중상급
    - [https://www.acmicpc.net/problem/17511](https://www.acmicpc.net/problem/17511)

### 2020년 1월 14일

- 중하급
    - [https://www.acmicpc.net/problem/14465](https://www.acmicpc.net/problem/14465)
- 중상급
    - [https://www.acmicpc.net/problem/14462](https://www.acmicpc.net/problem/14462)

### 2020년 1월 13일

- 중하급
    - [https://leetcode.com/problems/is-graph-bipartite/](https://leetcode.com/problems/is-graph-bipartite/)
    - 이분 매칭 (Bipartite Graph) 으로 검색해 주세요.
- 중상급
    - [https://www.acmicpc.net/problem/17834](https://www.acmicpc.net/problem/17834)

### 2020년 1월 12일

- 중하급
    - [https://leetcode.com/problems/permutations/](https://leetcode.com/problems/permutations/)
- 중상급
    - [https://www.acmicpc.net/problem/17505](https://www.acmicpc.net/problem/17505)

### 2020년 1월 11일

휴무 :)

### 2020년 1월 10일

- 중하급
    - [https://leetcode.com/problems/product-of-array-except-self/](https://leetcode.com/problems/product-of-array-except-self/)
- 중상급
    - [https://www.acmicpc.net/problem/17023](https://www.acmicpc.net/problem/17023)

### 2020년 1월 9일

- 중하급
    - [https://leetcode.com/problems/merge-two-sorted-lists/](https://leetcode.com/problems/merge-two-sorted-lists/)
    - [https://leetcode.com/problems/network-delay-time/](https://leetcode.com/problems/network-delay-time/)
- 중상급
    - [https://www.acmicpc.net/problem/1595](https://www.acmicpc.net/problem/1595)

### 2020년 1월 8일

- 중하급
    - [https://leetcode.com/problems/valid-anagram/](https://leetcode.com/problems/valid-anagram/)
- 중상급
    - [https://www.acmicpc.net/problem/17840](https://www.acmicpc.net/problem/17840)

### 2020년 1월 7일

- 중하급
    - [https://leetcode.com/problems/contains-duplicate/](https://leetcode.com/problems/contains-duplicate/)
- 중상급
    - [https://www.acmicpc.net/problem/17240](https://www.acmicpc.net/problem/17240)

### 2020년 1월 6일

- 중하급
    - [https://leetcode.com/problems/n-repeated-element-in-size-2n-array/](https://leetcode.com/problems/n-repeated-element-in-size-2n-array/)
    - [https://leetcode.com/problems/daily-temperatures/](https://leetcode.com/problems/daily-temperatures/)
- 중상급
    - [https://www.acmicpc.net/problem/15877](https://www.acmicpc.net/problem/15877)

### 2020년 1월 5일

- 중하급
    - [https://leetcode.com/problems/maximum-difference-between-node-and-ancestor/](https://leetcode.com/problems/maximum-difference-between-node-and-ancestor/)
- 중상급
    - [https://www.acmicpc.net/problem/14267](https://www.acmicpc.net/problem/14267)

### 2020년 1월 4일

- 중하급
    - [https://leetcode.com/problems/beautiful-array/](https://leetcode.com/problems/beautiful-array/)
- 중상급
    - [https://www.acmicpc.net/problem/14502](https://www.acmicpc.net/problem/14502)

### 2020년 1월 3일

- 중하급
    - [https://leetcode.com/problems/move-zeroes/](https://leetcode.com/problems/move-zeroes/)
- 중상급
    - [https://www.acmicpc.net/problem/13459](https://www.acmicpc.net/problem/13459)

### 2020년 1월 2일

- 중하급
    - [https://leetcode.com/problems/subsets/](https://leetcode.com/problems/subsets/)
- 중상급
    - [https://www.acmicpc.net/problem/1756](https://www.acmicpc.net/problem/1756)

### 2020년 1월 1일

- 중하급
    - [https://leetcode.com/problems/combination-sum/](https://leetcode.com/problems/combination-sum/)
- 중상급
    - [https://www.acmicpc.net/problem/13460](https://www.acmicpc.net/problem/13460)

### 2019년 12월 31일

- 중하급
    - [https://leetcode.com/problems/min-stack/](https://leetcode.com/problems/min-stack/)
- 중상급
    - [https://www.acmicpc.net/problem/18225](https://www.acmicpc.net/problem/18225)

### 2019년 12월 30일

- 중하급
    - [https://leetcode.com/problems/cousins-in-binary-tree/](https://leetcode.com/problems/cousins-in-binary-tree/)
    - [https://leetcode.com/problems/maximum-depth-of-n-ary-tree/](https://leetcode.com/problems/maximum-depth-of-n-ary-tree/)
- 중상급
    - [https://www.acmicpc.net/problem/15999](https://www.acmicpc.net/problem/15999)

### 2019년 12월 29일

- 중하급
    - [https://leetcode.com/problems/best-time-to-buy-and-sell-stock/](https://leetcode.com/problems/best-time-to-buy-and-sell-stock/)
    - [https://leetcode.com/problems/palindromic-substrings/](https://leetcode.com/problems/palindromic-substrings/)
- 중상급
    - [https://www.acmicpc.net/problem/17953](https://www.acmicpc.net/problem/17953)

### 2019년 12월 28일

- 중하급
    - [https://leetcode.com/problems/reverse-linked-list/](https://leetcode.com/problems/reverse-linked-list/)
    - [https://leetcode.com/problems/delete-node-in-a-linked-list/](https://leetcode.com/problems/delete-node-in-a-linked-list/)
- 중상급
    - [https://www.acmicpc.net/problem/17209](https://www.acmicpc.net/problem/17209)

### 2019년 12월 27일

- 중하급
    - [https://leetcode.com/problems/di-string-match/](https://leetcode.com/problems/di-string-match/)
    - [https://leetcode.com/problems/single-number/](https://leetcode.com/problems/single-number/)
- 중상급
    - [https://www.acmicpc.net/problem/17265](https://www.acmicpc.net/problem/17265)

### 2019년 12월 25일, 26일

- 중하급
    - [https://leetcode.com/problems/house-robber/](https://leetcode.com/problems/house-robber/)
    - [https://leetcode.com/problems/fair-candy-swap/](https://leetcode.com/problems/fair-candy-swap/)
- 중상급
    - [https://www.acmicpc.net/problem/17084](https://www.acmicpc.net/problem/17084)

### 2019년 12월 24일

- 중하급
    - [https://leetcode.com/problems/pascals-triangle/](https://leetcode.com/problems/pascals-triangle/)
    - [https://leetcode.com/problems/stone-game/](https://leetcode.com/problems/stone-game/) (미니맥스 알고리즘)
- 중상급
    - [https://www.acmicpc.net/problem/17075](https://www.acmicpc.net/problem/17075)

### 2019년 12월 23일

- 중하급
    - [https://leetcode.com/problems/reverse-string/](https://leetcode.com/problems/reverse-string/)
    - [https://leetcode.com/problems/interval-list-intersections/](https://leetcode.com/problems/interval-list-intersections/)
- 중상급
    - [https://www.acmicpc.net/problem/15678](https://www.acmicpc.net/problem/15678)

### 2019년 12월 22일

- 중하급
    - [https://leetcode.com/problems/evaluate-division/](https://leetcode.com/problems/evaluate-division/)
    - [https://leetcode.com/problems/path-with-maximum-gold/](https://leetcode.com/problems/path-with-maximum-gold/)
- 중상급
    - [https://www.acmicpc.net/problem/17305](https://www.acmicpc.net/problem/17305)

### 2019년 12월 21일

- 중하급
    - [https://leetcode.com/problems/evaluate-division/](https://leetcode.com/problems/evaluate-division/)
    - [https://leetcode.com/problems/path-with-maximum-gold/](https://leetcode.com/problems/path-with-maximum-gold/)
- 중상급
    - [https://www.acmicpc.net/problem/5615](https://www.acmicpc.net/problem/5615)

### 2019년 12월 20일

- 중하급
    - [https://leetcode.com/problems/rotting-oranges/](https://leetcode.com/problems/rotting-oranges/)
    - [https://leetcode.com/problems/max-area-of-island/](https://leetcode.com/problems/max-area-of-island/)
- 중상급
    - [https://www.acmicpc.net/problem/17267](https://www.acmicpc.net/problem/17267)

### 2019년 12월 19일

- 중하급
    - [https://leetcode.com/problems/maximum-subarray/](https://leetcode.com/problems/maximum-subarray/)
    - [https://leetcode.com/problems/k-closest-points-to-origin/](https://leetcode.com/problems/k-closest-points-to-origin/)
- 중상급
    - [https://www.acmicpc.net/problem/16740](https://www.acmicpc.net/problem/16740)

### 2019년 12월 18일

- 중하급
    - [https://leetcode.com/problems/split-a-string-in-balanced-strings/](https://leetcode.com/problems/split-a-string-in-balanced-strings/)
    - [https://leetcode.com/problems/minimum-add-to-make-parentheses-valid/](https://leetcode.com/problems/minimum-add-to-make-parentheses-valid/)
- 중상급
    - [https://www.acmicpc.net/problem/17268](https://www.acmicpc.net/problem/17268)

### 2019년 12월 17일

- 중하급
    - [https://leetcode.com/problems/count-square-submatrices-with-all-ones/](https://leetcode.com/problems/count-square-submatrices-with-all-ones/)
    - [https://leetcode.com/problems/minimum-cost-for-tickets/](https://leetcode.com/problems/minimum-cost-for-tickets/)
- 중상급
    - [https://www.acmicpc.net/problem/15113](https://www.acmicpc.net/problem/15113)

### 2019년 12월 16일

- 중하급
    - [https://www.acmicpc.net/problem/2529](https://www.acmicpc.net/problem/2529)
    - [https://leetcode.com/problems/course-schedule/](https://leetcode.com/problems/course-schedule/)
- 중상급
    - [https://www.acmicpc.net/problem/17492](https://www.acmicpc.net/problem/17492)

### 2019년 12월 15일

- 중하급
    - [https://leetcode.com/problems/find-the-town-judge/](https://leetcode.com/problems/find-the-town-judge/)
    - [https://leetcode.com/problems/is-graph-bipartite/](https://leetcode.com/problems/is-graph-bipartite/)
- 중상급
    - [https://www.acmicpc.net/problem/15791](https://www.acmicpc.net/problem/15791)

### 2019년 12월 14일

- 중하급
    - [https://leetcode.com/problems/flood-fill/](https://leetcode.com/problems/flood-fill/)
    - [https://leetcode.com/problems/pacific-atlantic-water-flow/](https://leetcode.com/problems/pacific-atlantic-water-flow/)
- 중상급
    - [https://www.acmicpc.net/problem/16000](https://www.acmicpc.net/problem/16000)

### 2019년 12월 13일

- 중하급
    - [https://leetcode.com/problems/is-subsequence/](https://leetcode.com/problems/is-subsequence/)
    - [https://leetcode.com/problems/longest-common-subsequence/](https://leetcode.com/problems/longest-common-subsequence/)
- 중상급
    - [https://www.acmicpc.net/problem/14517](https://www.acmicpc.net/problem/14517)

### 2019년 12월 12일

- 중하급
    - [https://leetcode.com/problems/island-perimeter/](https://leetcode.com/problems/island-perimeter/)
    - [https://leetcode.com/problems/fraction-addition-and-subtraction/](https://leetcode.com/problems/fraction-addition-and-subtraction/)
- 중상급
    - [https://www.acmicpc.net/problem/1341](https://www.acmicpc.net/problem/1341)

### 2019년 12월 11일

- 중하급
    - [https://leetcode.com/problems/count-primes/](https://leetcode.com/problems/count-primes/)
    - [https://leetcode.com/problems/fibonacci-number/](https://leetcode.com/problems/fibonacci-number/)
- 중상급
    - [https://www.acmicpc.net/problem/15897](https://www.acmicpc.net/problem/15897)

### 2019년 12월 10일

- 중하급
    - [https://leetcode.com/problems/balanced-binary-tree/](https://leetcode.com/problems/balanced-binary-tree/)
    - [https://leetcode.com/problems/distribute-coins-in-binary-tree/](https://leetcode.com/problems/distribute-coins-in-binary-tree/)
- 중상급
    - [https://www.acmicpc.net/problem/17073](https://www.acmicpc.net/problem/17073)

### 2019년 12월 9일

- 중하급
    - [https://leetcode.com/problems/battleships-in-a-board/](https://leetcode.com/problems/battleships-in-a-board/)
    - [https://leetcode.com/problems/queens-that-can-attack-the-king/](https://leetcode.com/problems/queens-that-can-attack-the-king/)
- 중상급
    - [https://www.acmicpc.net/problem/17455](https://www.acmicpc.net/problem/17455)

### 2019년 12월 8일

- 중하급
    - [https://leetcode.com/problems/regions-cut-by-slashes/](https://leetcode.com/problems/regions-cut-by-slashes/)
    - [https://leetcode.com/problems/partition-labels/](https://leetcode.com/problems/partition-labels/)
- 중상급
    - [https://www.acmicpc.net/problem/17951](https://www.acmicpc.net/problem/17951)

### 2019년 12월 7일

- 중하급
    - [https://leetcode.com/problems/keys-and-rooms/](https://leetcode.com/problems/keys-and-rooms/)
    - [https://leetcode.com/problems/stone-game-ii/](https://leetcode.com/problems/stone-game-ii/)
- 중상급
    - [https://www.acmicpc.net/problem/13261](https://www.acmicpc.net/problem/13261)
    - 지뢰문제

### 2019년 12월 6일

- 중하급
    - [https://leetcode.com/problems/is-subsequence/](https://leetcode.com/problems/is-subsequence/)
    - [https://leetcode.com/problems/minesweeper/](https://leetcode.com/problems/minesweeper/)
- 중상급
    - [https://www.acmicpc.net/problem/11583](https://www.acmicpc.net/problem/11583)

### 2019년 12월 5일

- 중하급
    - [https://leetcode.com/problems/delete-nodes-and-return-forest/](https://leetcode.com/problems/delete-nodes-and-return-forest/)
    - [https://leetcode.com/problems/search-insert-position/](https://leetcode.com/problems/search-insert-position/)
- 중상급
    - [https://www.acmicpc.net/problem/17235](https://www.acmicpc.net/problem/17235)

### 2019년 12월 4일

- 중하급
    - [https://leetcode.com/problems/min-cost-climbing-stairs/](https://leetcode.com/problems/min-cost-climbing-stairs/)
    - [https://leetcode.com/problems/minimum-falling-path-sum/](https://leetcode.com/problems/minimum-falling-path-sum/)
- 중상급
    - [https://www.acmicpc.net/problem/17234](https://www.acmicpc.net/problem/17234)

### 2019년 12월 3일

- 중하급
    - [https://leetcode.com/problems/number-of-closed-islands/](https://leetcode.com/problems/number-of-closed-islands/)
    - [https://leetcode.com/problems/happy-number/](https://leetcode.com/problems/happy-number/)
- 중상급
    - [https://www.acmicpc.net/problem/17453](https://www.acmicpc.net/problem/17453)

### 2019년 12월 2일

- 중하급
    - [https://leetcode.com/problems/letter-tile-possibilities/](https://leetcode.com/problems/letter-tile-possibilities/)
    - [https://leetcode.com/problems/greatest-common-divisor-of-strings/](https://leetcode.com/problems/greatest-common-divisor-of-strings/)
- 중상급
    - [https://www.acmicpc.net/problem/17370](https://www.acmicpc.net/problem/17370)

### 2019년 12월 1일

- 중하급
    - [https://leetcode.com/problems/climbing-stairs/](https://leetcode.com/problems/climbing-stairs/)
    - [https://leetcode.com/problems/majority-element/](https://leetcode.com/problems/majority-element/)
- 중상급
    - [https://www.acmicpc.net/problem/16681](https://www.acmicpc.net/problem/16681)

### 2019년 11월 30일

- 중하급
    - [https://leetcode.com/problems/middle-of-the-linked-list/](https://leetcode.com/problems/middle-of-the-linked-list/)
    - [https://leetcode.com/problems/minimum-absolute-difference/](https://leetcode.com/problems/minimum-absolute-difference/)
- 중상급
    - [https://www.acmicpc.net/problem/16674](https://www.acmicpc.net/problem/16674)

### 2019년 11월 29일

- 중하급
    - [https://leetcode.com/problems/n-ary-tree-preorder-traversal/](https://leetcode.com/problems/n-ary-tree-preorder-traversal/)
    - [https://leetcode.com/problems/find-common-characters/](https://leetcode.com/problems/find-common-characters/)
- 중상급
    - [https://www.acmicpc.net/problem/16682](https://www.acmicpc.net/problem/16682)

### 2019년 11월 28일

- 중하급
    - [https://leetcode.com/problems/merge-two-binary-trees/](https://leetcode.com/problems/merge-two-binary-trees/)
    - [https://leetcode.com/problems/number-of-recent-calls/](https://leetcode.com/problems/number-of-recent-calls/)
- 중상급
    - [https://www.acmicpc.net/problem/16678](https://www.acmicpc.net/problem/16678)

### 2019년 11월 27일

- 중하급
    - [https://leetcode.com/problems/array-partition-i/](https://leetcode.com/problems/array-partition-i/)
    - [https://leetcode.com/problems/hamming-distance/](https://leetcode.com/problems/hamming-distance/)
- 중상급
    - [https://www.acmicpc.net/problem/16677](https://www.acmicpc.net/problem/16677)

### 2019년 11월 26일

- 중하급
    - [https://leetcode.com/problems/unique-morse-code-words/](https://leetcode.com/problems/unique-morse-code-words/)
    - [https://leetcode.com/problems/self-dividing-numbers/](https://leetcode.com/problems/self-dividing-numbers/)
- 중상급
    - [https://www.acmicpc.net/problem/12846](https://www.acmicpc.net/problem/12846)

### 2019년 11월 25일

- 중하급
    - [https://leetcode.com/problems/remove-outermost-parentheses/](https://leetcode.com/problems/remove-outermost-parentheses/)
    - [https://leetcode.com/problems/robot-return-to-origin/](https://leetcode.com/problems/robot-return-to-origin/)
- 중상급
    - [https://www.acmicpc.net/problem/14618](https://www.acmicpc.net/problem/14618)

### 2019년 11월 24일

- 중하급
    - [https://leetcode.com/problems/to-lower-case/](https://leetcode.com/problems/to-lower-case/)
    - [https://leetcode.com/problems/cells-with-odd-values-in-a-matrix/](https://leetcode.com/problems/cells-with-odd-values-in-a-matrix/)
- 중상급
    - [https://www.acmicpc.net/problem/14619](https://www.acmicpc.net/problem/14619)

### 2019년 11월 23일

- [https://www.acmicpc.net/problem/14620](https://www.acmicpc.net/problem/14620)
    - 중급
    - #백트래킹 #브루트 포스 #DFS #BFS

### 2019년 11월 22일

- [https://www.acmicpc.net/problem/14612](https://www.acmicpc.net/problem/14612)
    - 중상급
    - #그래프 #연결 리스트 #다익스트라 #DFS

### 2019년 11월 21일

- [https://www.acmicpc.net/problem/14612](https://www.acmicpc.net/problem/14612)
    - 중급
    - #배열 #정렬 #우선순위 큐 #자료구조
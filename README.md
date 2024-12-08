### Algorithm Study

**1. Hash Table**

**2. BFS(Bread-First Search)**

**3. DFS (Depth-First-Search)**

**4. 선형 탐색**
(pg.103~~ )

**5. 이진 탐색**
(pg.107 ~~ )

**6. 정렬 알고리즘**

**7. 경로 탐색 알고리즘**

**8. 군집화 알고리즘**

**9. 분할 정복 알고리즘 (=Divide and Conquer Algorithm)**

-> 큰 문제를 여러개의 작은문제로 나눠 해결하고 결과를 결합해 하나의 해결방법을 얻는 알고리즘 

**10. 탐욕 알고리즘 (=Greedy Algorithm)**

-> 실행되는 순간마다 최상의 결정을 내리는 알고리즘

**11. 동적 알고리즘 (=Dynamic Programming)**

-> 탐욕 알고리즘과 정반대; 과거에 내린 결정이 앞으로의 결정에 영향을 주는 알고리즘 

효율성 분석 -> 시간 복잡도, 공간 복잡도 

**<ins><시간 복잡도 (= Time Complexity)></ins>**

-> 주어진 입력에 따라 알고리즘이 문제를 해결할 때 걸리는 시간

**<ins><공간 복잡도 (= Space Complexity)></ins>**

-> 알고리즘이 문제를 해결할때 쓰이는 컴퓨터의 메모리 공간 (자원이 제한된 시스템에서 주로 쓰임)

### 데이터 구조
-> 알고리즘이 결과를 산출하는 과정에서 처리하는 데이터를 저장하고 구성하는 구조

**<자료형>**
처리할 데이터의 속성이 무엇인지, 데이터로 수행하려는 작업이 무엇인지 컴퓨터에 알려주려고 만든 것 
1. Boolean
- 논리 자료형-> 0/1 또는 참/거짓으로 나뉘는 상태 
  
2. Character (=문자)

3. Integer (=정수)

4. Floating-point number (=부동 소수점 수)
- ex. 6.5 / 7.1

**<함수>**
input: 매개변수 (parameter) / 인수 (argument)
C 기반의 프로그래밍 언어; void 함수

**<객체 지향 프로그래밍 언어 (=OOP)>**

<ins>클래스</ins>; 
<ins>메소드</ins> = 클래스 내부에 있는 함수

<ins>재귀 함수</ins> = 특정 조건을 충족할 때까지 끊임없이 동작함.

최대재귀깊이 (maximum recursion depth) -> 초과하면 에러남.

* RAM에 적재된 데이터는 CPU 칩에 내장된 **<ins>캐시</ins>** 라는 메모리 유형에 적재된 후, CPU가 처리 중인 데이터를 저장하는 **<ins>레지스터</ins>**에 적재됨.

**메모리 주소** = 메모리 공간을 식별하기 위해 사용 됨.

**가상 메모리** = 물리적인 주소에 매핑되어 메모리 역할을 하는 영역. 

**페이징** = 가상 메모리를 일정한 크기의 페이지로 나눠서 사용됨.

**페이지 테이블** = 페이지에 매핑된 주소를 물리적인 주소로 변환함.

### 빅 오 표기법

**<ins>성능 좋은 순서; O(1), O(log n), O(n), O(nlogn), O(n^2), O(2^n), O(n!)</ins>**


**1. List**

-> 데이터 요소가 포인터(=참조)의 쌍으로 구성됨. 

**포인터** = 리스트 내의 바로 다음 요소가 저장된 메모리 위치를 가리킴 

**노드** = 연결 리스트에서 데이터 요소와 다음 요소를 가리키는 포인터의 쌍

**헤드** = 리스트에 진입하는 지점

**<ins>단방향 리스트</ins>** = 노드 하나가 다른 노드를 가리키는 포인터 하나를 갖는 유형의 연결 리스트. 마지막 노드는 다른 노드를 가리키지 않으므로 NULL 상태.

**<ins>양방향 연결 리스트</ins>** = 각 노드가 다음 노드를 가리키는 포인터와 이전 노드를 가리키는 포인터를 함께 갖는 연결 리스트 구조 (*데이터를 삭제할 때나 리스트를 양방향으로 순회할 때 더 효율적인 연결 리스트)

**<ins>순환 연결 리스트</ins>** = 마지막 노드는 첫 번째 노드와 연결 됨 

**2. Stack**

-> 추가된 요소를 메모리의 가장 앞 주소에 배치하는 선형 데이터 구조

 - 푸시 = 스택에 요소를 추가하는 동작
 - 팝 = 삭제할 때는 마지막으로 추가된 요소를 삭제함.
 - LIFO (후입선출) = 스택에 마지막으로 추가된 요소를 먼저 삭제하는 스택 구조
 - **정적 스택** = 데이터 구조나 규모가 고정됨.
 - **동적 스택** = 실행중에 크기를 늘릴 수 있음.
   
**3. queue**
 -> 각 요소에 우선순위를 부여하는 데이터 구조 
 - enqueue; 큐에 요소를 추가
 - dequeue;  큐에서 요소를 삭제하는것. (가장 오래된 요소가 우선 삭제.)
 - **<ins>FIFO</ins>** = 선입선출 = 먼저 추가된 요소가 우선적으로 삭제됨.
**4.Tree**
![image](https://github.com/user-attachments/assets/fce62887-92e3-47cb-91ef-b0dd3d3e57a8)

**5. Heap**

**6. Hash**

## Disjoint-set Algorithm: 서로소 집합
### 개요
* 수학에서 서로소 집합은 공통 원소가 없는 두 집합이다.
* 서로소 집합 자료구조란 서로소 부분 집합들로 이루어진 원소 데이터를 처리하고자 한다.

### 자료구조
* 크게 두 가지의 연산을 갖는다.
    * ```union()``` : 2개의 원소가 포함된 집합을 하나의 집합으로 합치는 연산이다. X번 노드의 최고 조상인 루트를 찾는다.
    * ```find()```: 특정한 원소가 속한 집합이 어떤 집합인지 알려주는 연산이다.

* 가. union(합집합) 연산을 확인하여, 서로 연결된 두 노드 A, B를 확인한다.
    * I. A와 B의 루트 노드인 A', B'을 찾는다.
    * II. A'를 B'의 부모 노드로 설정하여, B'가 A'를 가리키도록 한다.
* 나. 모든 union 연산을 처리할 때까지 1번 과정을 반복한다.

### 예시
* 내일 아침 추가 예정...

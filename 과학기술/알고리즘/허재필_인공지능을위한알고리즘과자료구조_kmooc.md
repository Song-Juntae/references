# 인공지능을 위한 알고리즘과 자료구조

## 목차

* 자료구조/알고리즘의 정의

* 선형 자료구조

* 비선형 자료구조

* 그래프 탐색 알고리즘

* 함수의 점근적 분석

* 알고리즘 복잡도 분석

* 삽입 정렬과 합병 정렬 및 재귀적 알고리즘의 복잡도

* 힙 자료구조

* 힙 정렬과 퀵 정렬

* 최소 신장 트리 알고리즘

* 서로소 집합 자료구조를 통한 크루스칼 알고리즘의 개선

* 최단경로 알고리즘

* 위상정렬

* 동적계획법

### 자료구조/알고리즘의 정의

컴퓨터 과학에서의 인공지능을 공부하기 위해서 수학, 알고리즘, 자료구조와 같은 컴퓨터 과학 배경 지식들이 필요하다.

Data Structures : (자료구조) 자료구조는 자료의 값과 자료 간의 관계 그리고 자료에 행할 수 있는 작업도 포함한다. {Data values, Relationships, Operations}

    Abstraction : (추상화) 목적에 맞게 필요한 정보만 남기고, 불필요한 것은 지우는 것

    Topologically correct : (위상적으로 동일하다) 목적에 부합하는 추상화된 정보들이 같다

Algorithm : (알고리즘) Input --Operations--> Output

    모든 input instance에 대해서 알맞은 out을 내놓아야 한다.
    알고리즘은 종료되어야 한다

Computational thinking
    abstraction
    automation
    analysis

* Fundamental Data Structures
    * Data Structures
        * Primitive
            * Integer
            * Float
            * Character
        * Non-Primitive
            * Linear
                * Arrays
                * Lists
                    * Stacks
                        * 팬케이크
                    * Queues
                        * 예약줄
            * Non-Linear
                * Trees
                    * 가계도
                * Graphs
                    * 지도
            * Files

* Algorithm analysis
    * Asymptotic notations and analysis
    * Time and space comlexities

* Fundmental Algorithms
    * Sorting
    * Shortest path
    * Minimum spanning tree
        * 가장 효율적으로 그래프를 트리로 변환하는 문제
    * Topological sort
        * 선행과목 구조도, 옷을 입는 순서도 정렬
    * Dynamic programming
        * Interval scheduling
        * Edit distance
        * Matrix chain multiplication

### 선형 자료구조

Call by value : 값 변경이 불가능

Call by reference : 값 변경이 가능

Linked list : (연결리스트) 값과 주소를 가지는 선형자료구조

Stack : (스택) Last-in-first-out인 선형자료 구조

Queue : (큐) First-in-first-out인 선형자료 구조

### 비선형 자료구조

Tree : (트리) 계층적 관계 정보를 갖는 노드(root, internal, leaf)로 이루어진 자료구조, 어떤 노드의 자녀의 수를 degree라고 하며, 자녀들의 순서 유무에 따라 ordered/unordered 트리로 분류

Graph : (그래프) 데이터 간의 정보를 갖는 자료구조, Edge의 방향성 유무에 따라 directed/undirected 그래프로 분류한다. 그래프를 표현하는 방법에는 binary-relation list, adjacency matrix, adjacency list가 있는데, 주로 adjacency list가 사용된다.

### 그래프 탐색 알고리즘

Breadth-first search : (너비우선 탐색) 시작 노드로부터 가까운 depth, 깊이 노드 부터 검색, 일반적으로 Queue로 구현

Depth-first search : (깊이우선 탐색) 한번에 depth 끝까지 검색하고, 없으면 부모 노드로 올라와서 다른 자녀의 끝까지 검색, 일반적으로 Stack으로 구현

BFS, DFS로 검색하였으나 결과가 없다면 연결된 그래프가 아니다.

### 함수의 점근적 분석

Asymptotic analysis : (점근적 분석) 알고리즘의 효율성 검사

Weak ordering : 알고리즘 차수가 같으면, 대소관계를 구별안한다

theta, big-o, big-omega, little notation : 알고리즘 복잡도를 표현하는 방법들

### 알고리즘 복잡도 분석

### 삽입 정렬과 합병 정멸 및 재귀적 알고리즘의 복잡도

### 힙 자료구조

### 힙 정렬과 퀵 정렬

...
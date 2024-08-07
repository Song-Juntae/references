# 면접을 위한 CS 전공지식 노트

## 목차

* 디자인 패턴과 프로그래밍 패러다임
    * 디자인 패턴
    * 프로그래밍 패러다임
* 네트워크
    * 네트워크의 기초
    * TCP/IP 4계층 모델
    * 네트워크 기기
    * IP 주소
    * HTTP
* 운영체제
    * 운영체제와 컴퓨터
    * 메모리
    * 프로세스와 스레드
    * CPU 스케줄링 알고리즘
* 데이터베이스
    * 데이터베이스의 기본
    * ERD와 정규화 과정
    * 트랜잭션과 무결성
    * 데이터베이스의 종류
    * 인덱스
    * 조인의 종류
    * 조인의 원리
* 자료구조
    * 복잡도
    * 선형 자료 구조
    * 비선형 자료 구조
* 포트폴리오와 면접
    * 포트폴리오
    * 면접



디자인 패턴과 프로그래밍 패러다임
    디자인 패턴
        싱글톤 패턴
        팩토리 패턴
        전략 패턴
        옵저버 패턴
        프록시 패턴과 프록시 서버
        이터레이터 패턴
        노출모듈 패턴
        MVC 패턴
        MVP 패턴
        MVVM 패턴
    프로그래밍 패러다임
        선언형과 함수형 프로그래밍
        객체지향 프로그래밍
        절차형 프로그래밍
        패러다임의 혼합
네트워크
    네트워크의 기초
        처리량과 지연 시간
        네트워크 토폴로지와 병목 현상
        네트워크 분류
        네트워크 성능 분석 명령어
        네트워크 프로토콜 표준화
    TCP/IP 4계층 모델
        계층 구조
        PDU
    네트워크 기기
        네트워크 기기의 처리 범위
        애플리케이션 계층을 처리하는 기기
        인터넷 계층을 처리하는 기기
        데이터 링크 계층을 처리하는 기기
        물리 계층을 처리하는 기기
    IP 주소
        ARP
        홉바이홉 통신
        IP 주소 체계
        IP 주소를 이용한 위치 정보
    HTTP
        HTTP/1.0
        HTTP/1.1
        HTTP/2
        HTTPS
        HTTP/3
운영체제
    운영체제와 컴퓨터
        운영체제의 역할과 구조
        컴퓨터의 요소
    메모리
        메모리 계층
        메모리 관리
    프로세스와 스레드
        프로세스와 컴파일 과정
        프로세스의 상태
        프로세스의 메모리 구조
        PCB
        멀티프로세싱
        스레드와 멀티스레딩
        공유 자원과 임계 영역
        교착 상태
    CPU 스케줄링 알고리즘
        비선점형 방식
        선정형 방식
데이터베이스
    데이터베이스의 기본
        엔터티
        릴레이션
        속성
        도메인
        필드와 레코드
        관계
        키
    ERD와 정규화 과정
        ERD의 중요성
        예제로 배우는 ERD
        정규화 과정
    트랜잭션과 무결성
        트랜잭션
        무결성
    데이터베이스의 종류
        관계형 데이터베이스
        NoSQL 데이터베이스
    인덱스
        인덱스의 필요성
        B-트리
        인덱스 만드는 방법
        인덱스 최적화 기법
    조인의 종류
        내부 조인
        왼쪽 조인
        오른쪽 조인
        합집합 조인
    조인의 원리
        중첩 루프 조인
        정렬 병합 조합
        해시 조인
자료구조
    복잡도
        시간 복잡도
        공간 복잡도
        자료 구조에서의 시간 복잡도
    선형 자료 구조
        연결 리스트
        배열
        벡터
        스택
        큐
    비선형 자료 구조
        그래프
        트리
        힙
        우선순위 큐
        맵
        셋
        해시 테이블
포트폴리오와 면접
    포트폴리오
    면접

### 디자인 패턴

디자인 패턴이란 하나의 '규약'

* singleton pattern : (싱글톤 패턴) 하나의 클래스에 오직 하나의 인스턴스만 가지는 패턴

* factory pattern : (팩토리 패턴) 객체를 사용하는 코드에서 객체 생성 부분을 떼어내 추상화한 패턴

* strategy pattern : (전략 패턴, policy pattern, 정책 패턴) 어떤 컨텍스트 안에서 여러 전략(선택지, 캡슐화한 알고리즘)을 사용할 수 있도록 하는 패턴

proxy : (프록시) 프록시 개체는 어떤 대상의 기본적인 동작의 작업을 가로챌 수 있는 객체, 옵저버, 프록시 패턴에 쓰임

* observer pattern : (옵저버 패턴) 객체의 변화를 옵저버들에게 알려주는 패턴

* proxy pattern : (프록시 패턴) 객체의 인터페이스 역할을 만들어주는 패턴

* iterator pattern : (이터레이터 패턴) 데이터 구조와 상관없이 순회하는 이터레이터를 사용하는 패턴

* revealing module pattern : (노출모듈 패턴) 즉시 실행 함수를 통해 접근 제어자(private, public)를 만드는 패턴

* MVC pattern : Model(데이터), View(사용자 인터페이스), Controller(모델과 뷰를 컨트롤)을 사용하는 패턴

* MVP pattern : MVC 에서 Controller를 Presenter로 바꾼 패턴

* MVVM pattern : MVC 에서 Controller를 View model로 바꾼 패턴

### 프로그래밍 패러다임

Programming paradigm이란 개발 방법론

* 선언형 : HTML
    * 함수형 : 순수 함수, 고차 함수
* 명령형 : 순차적인 명령 수행
    * 객체지향형 : 추상화, 캡슐화, 상속성, 다형성, 오버로딩, 오버라이딩
    * 절차지향형 : 루틴, 서브루틴 같은 프로시저

객체지향 프로그래밍 SOLID 원칙
    Single Responsibility Principle : (단일 책임 원칙)
    Open Closed Principle : (개방-폐쇄 원칙)
    Liskov Substituion Principle : (리스코프 치환 원칙)
    Interface Segregation Principle : (인터페이스 분리 원칙)
    Dependency Inversion Principle : (의존 역전 원칙)

패러다임 간의 장점만 취한다

### 네트워크의 기초

Network = node + link

Throughput : (처리량) 단위 시간당 데이터양, 단위로는 bps(bits per second)를 쓴다

대역폭 : 최대 비트 수

Latency : (지연 시간) 요청이 처리되는 시간, 서버와 클라이언트 왕복시간

* Network topology : 노드와 링크 배치
    * Tree
    * Bus : 스푸핑, 악의적인 노드의 위험
    * Star
    * Ring
    * Mesh

* 네트워크 규모별 분류
    * Local Area Network : (LAN) 속도 빠르고 혼잡하지 않음
    * Metropolitan Area Network : (MAN)
    * Wide Area Network : (WAN) 

Bottleneck : (병목현상) 네트워크 병목현상은 하나의 구성요소 때문에 전체의 성능이 제한되는 상황
    네트워크 대역폭
    네트워크 토폴로지
    서버 CPU, 메모리 사용량
    비효율적인 네트워크 구성

ping : (Packet INternet Groper) 네트워크 상태 확인을 위한 패킷 전송 명령어

netstat : 네트워크 접속, 라우팅 테이블, 프로토콜 등의 리스트를 보여준다

nslookup : DNA 관련 내용 확인 명령어

traceroute : 목적지 노드까지 네트워크 경로를 확인

네트워크 프로토콜 : IEEE, IETF 표준화 단체가 정함, 예를 들어 HTTP

Internet protocol suite : 프로토콜 집합
    Transmission Control Protocol/Internet Protocol : (TCP/IP 4 계층)
        Application layer
        Transport layer
        Internet layer
        Link layer
    Open Systems Interconnection model : (OSI model)
        Application layer
        Presentation layer
        Session layer
        Transport layer
        Network layer
        Data link layer
        Physical layer

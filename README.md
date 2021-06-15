# 📚💻 Today I learned
## I-Am-Studying :smile:  - ing :relaxed: - ing 🌼:blush:

--- 

<br>

## Computer Software Engineering 2021-1

### I will be briefly recording and steadily updating what I learn everyday 🌼 🧑‍🎓 📝
<br>

|**Contents of Majors**|
|--|
|자료구조1/실습|
|Cpp|
|이산수학/연습|
|컴퓨터아키텍쳐|

---

<br>

*2021.03.25 THURS*


### 1.1 자료구조와 알고리즘 <br>
- 자료구조의 개념
- 종류: 스택, 큐, 리스트, 사전, 그래프, 트리
- 알고리즘의 개념
- 자연어, 흐름도, 의사 코드, 프로그래밍 언어

<br>

### 1.2 추상 데이터 타입 <br>
- 기초자료형, 파생 자료형, 사용자 정의 자료형
- ADT: Abstract Data Type 의 객체와 함수

<br>

### 1.3 알고리즘의 성능 분석 <br>
- 알고리즘의 복잡도 분석
- 시간 복잡도 함수와 빅오 표기법
- <time.h> 헤더파일의 clock() 함수 사용
- 사칙 연산의 실행 시간, 알고리즘의 실행 시간 비교
- 최선, 평균, 최악의 경우

<br>


### 객체 지향
- 클래스 생성
- 생성자 개념과 사용법
- 위임 생성자 문법
- get, set 멤버 함수 사용
- this->
- 문자열 처리 헤더 파일 추가
- string VS char[] 

### 자료구조
- 순환 함수의 내부적 구현 : 순환 구조와 스택에 저장되어 있는 호출된 함수의 주소
- 반복(iteration) VS 순환(recursion)
- 거듭제곱의 순환 구조
- 순환 알고리즘의 성능 분석
- 피보나치 수열 알고리즘 성능 분석 (반복/순환 - 시간 복잡도 계산)

<hr>

|**목록**|**O/X**|**Today's**|**한줄평**|
|--|--|--|--|
|세미나|[ x ]|2장 공부|due MON|


<br>

*2021.03.26 FRI*


### 자료구조 02 순환
- 2.1 순환 
> 순환 호출의 내부적 구현 <br>
> 순환 알고리즘의 구조 <br>
> 순환과 반복 <br>
> 순환의 원리 <br>
- 2.2 거듭제곱값 계산
- 2.3 피보나치 수열 계산
- 2.4 하노이탑 문제

<hr>

|**목록**|**O/X**|**Today's**|**한줄평**|
|--|--|--|--|
|세미나|[ △ ]|2장 실습/예제 추가|Seminar Tmrw|

<br>

*2021.03.28 SUN*

### 1. 자료구조와 알고리즘
- 삽입 정렬
- 버블 정렬
- Big(O) Graphh - 상수형/로그형/선형/k차형/지수형

### 2. 순환
- 꼬리재귀
- 예제 : power, getLen, printStr, printReverseStr, search, digitSum

<hr>

|**목록**|**O/X**|**Today's**|**한줄평**|
|--|--|--|--|
|세미나|[x]|1,2장|Seminar Complete|

<br>

*2021.03.29 MON*

### 2. 순환 
- 순환 거듭제곱 알고리즘 실행 시간
- 하노이탑 시각화

<hr>

|**목록**|**O/X**|**Today's**|**한줄평**|
|--|--|--|--|
|자료구조|X|3장 이론/실습||
|Cpp|X|클래스, 객체 배열||
|이산수학|X|행렬||
|Seminar|O|MON - CH 3|마무리잇|
<br>

*2021.04.02 FRI ~ 2021.04.06 TUES TODO CHECKLIST*

### 자료구조

3. 배열 구조체 포인터
- [x] 3.1 배열
- [x] 3.2 구조체
- [x] 3.3 배열의 응용: 다항식
- [x] 3.4 배열의 응용: 희소행렬
- [x] 3.5 포인터
- [x] 3.6 동적 메모리 할당
- [x] 연결 리스트 복습

### Cpp

3. 클래스와 객체
- [x] 3.1 객체에 대한 이해
- [x] 3.2 C++ 클래스 생성 <br>
        - 클래스 선언부, 구현부 <br>
        - 멤버 변수, 멤버 함수 <br>
        - 캡슐화 <br>
- [x] 3.3 객체 생성/활용 <br>
        - 클래스 이름 + 객체 이름 <br>
        - 멤버 접근 연산자 . <br>
- [x] 3.4 생성자 <br>
        - 기본 디폴트 생성자 자동 삽입 <br>
        - 생성자의 중복 <br>
        - 위임, 타겟 생성자 <br>
        - 생성자에서 멤버 변수의 초기화 <br>
- [x] 3.5 소멸자 <br>
- [x] 3.6 접근 지정 <br>
        - 멤버 접근 지정자(private: 디폴트, public, protected) - 캡슐화 구현 <br>
- [x] 3.7 인라인 함수 <br>
        - 클래스 멤버 함수의 자동 인라인 함수 선언 <br>
        - 제약 사항: 재귀, static, 반복문, switch문을 가진 함수는 허용 X <br>
- [x] 3.8 C++ 구조체 <br>
        - 디폴트가 public <br>
- [x] 3.9 헤더파일과 CPP 파일 분리 <br>
        - " .h" : 클래스 선언부 - 정복 방지를 위한 조건 컴파일문 사용(#ifndef, #define, endif) <br>
        - .cpp : 클래스 구현부 - 헤더 파일 추가 <br>
        - main.cpp : main함수와 전역 변수 - 헤더 파일 추가 <br>

### 4. 객체 포인터와 객체 배열, 객체의 동적 생성
- [x] 4.1 객체 포인터
- [x] 4.2 객체 배열 <br>
    - 배열 초기화 <br>
    - 다차원 객체 배열 <br>
- [x] 4.3 동적 메모리 사용 <br>
    - 동적 할당과 반환(변수/배열/객체/객체배열) <br>
        - Circle *circle=new Circle[n]; <br>
        - elete []circle; <br>
    - 동적 메모리 초기화 <br>
- [x] 4.4 객체 배열 동적 메모리 사용
- [x] 4.5 this pointer

✅ 4.6 string class 를 이용한 문자열 활용 <br>
    - string 객체의 동적 생성 <br>
    - getline(cin, s, '/n') 전역 함수 <br>

### <string 클래스 주요 멤버 함수>
<br>


|멤버 함수 원형 |설명	|
|--|-----|
|string& append(const string& char);	|문자열 연결<br>문자열 뒤에 str 추가|
|stinrig& append(const string &str, int pos, int n);	|str 문자열 내  pos 위치에서 문자 n개를 현재 문자열 뒤에 추가	|
|string& insert(int pos, const string& str);|문자열 삽입<br>문자열의 pos위치에 str삽입|
|string& replace(int pos, int n, const string& str);|문자열의 pos 위치부터 n개 문자를 str로 대치|
|int size();<br>int length();	|문자열 반환<br>(영어 문자 바이트 - 한글: 한 문자 2바이트)	|
|int capacity();	|할당된 메모리 크기 리턴	|
|string& erase(int pos, int n);	|문자열 삭제|pos 위치부터 n개 문자 삭제|
|void clear();	|문자열 모두 삭제. 크기를 0으로 만듬	|
|bool empty();	|문자열 크기가 0이면 true, 아니면 false 반환|
|char& at(int pos);|	pos 위치의 문자 반환|
|int find(const string& str);|	문자열의 처음부터 str을 검색하여 발견한 처음 인덱스 반환, 없으면 -1 반환|	
|int find(const string& str, int pos);	|문자열 검색<br>문자열의 pos 위치부터 str을 검색하여 발견한 처음 인덱스 반환, 없으면 -1 반환|
|int rfind(const strng& str, int pos);	|문자열의 pos 위치부터 str을 검색하여 발견한 마지막 인덱스 반환, 없으면 -1 반환	|
|int compare(const string& str);|	문자열 비교|문자열과 str을 비교하여 같으면 0, 사전 순으로 앞에 오면 음수, 뒤에 오면 양수 반환|
|string substr(int pos);<br>string substr(int pos, int n);	|문자열 서브스트링<br>pos 위치부터 n개 문자를 새로운 서브스트링으로 생성하여 반환|

<br>

### <string 클래스 주요 연산자>
<br>

|연산자|설명|예시|결과|
|---|---|---|---|
|s1=s2|문자열 치환<br>|s2를 s1에 치환| s1=s2 |s1="Java"|
s []|s의 [] 인덱스에 있는 문자 반환 | char c=s[1]	| c='+'|
|s1+s2|문자열 연결<br>s1과 s2를 연결한 새로운 문자열|	s1+s2	|"CJava"|
|s1+=s2	|s1에 s2 연결|	s1+=s2	|s1="CJava"|
|s1==s2	|문자열 비교<br>s1과 s2가 같은 문자열이면 true|	s1==s2	|false|
|s1!=s2|	s1과 s2가 다른 문자열이면 true|	s1!=s2|	true|
|s1<s2|	s1이 사전 순으로 s2보다 앞에 오면 true	|s1<s2|	true|
|s1>s2|||false|
|s1<=s2	|||true|
|s1>=s2	|||false|



<hr>

*2021.04.07 WED*
|**목록**|**O/X**|**Today's**|**한줄평**|
|--|--|--|--|
|자료구조|△|3장 이론|희소행렬 공부|
|자료구조실습|X|3장 실습||
|Cpp|O|4장 클래스/객체 배열|예제 실습|
|이산수학|X|행렬||
|컴퓨터아키텍쳐|X|CPU구조||
|Seminar|X|MON - CH4 스택|공부하기|

<br>

*2021.04.07 WED ~ 2021.04.11 SUN TODO CHECKLIST*

### Cpp

#### CH5
- [x] 5.1 함수의 인자 전달방식 <br>
    - 값에 의한 호출(call by value) <br>
    - 주소에 의한 호출(call by address) <br>
    - 참조에 의한 호출(call by reference) <br>
- [x] 5.2 함수 호출시 객체 전달 <br>
    - 복사 생성자와 소멸자 <br>
- [x] 5.3 객체 치환 및 객체 리턴 
- [x] 5.4 참조와 함수 <br>
    - 참조 변수(매개변수, 리턴) <br>
    - 참조에 의한 호출 <br>
- [x] 5.5 복사 생성자
    - 얕은 복사(디폴트 복사 생성자) <br>
    - 깊은 복사(사용자 복사 생성자 생성) <br>
    - 묵시적 복사 생성의 경우 <br>
        1) 객체를 초기화하여 생성할 때 <br>
        2) 값에 의한 호출로 객체가 전달 돌 때 <br>
        3) 함수가 객체를 리턴할 때 <br>

*2021.04.08 THURS*

|**목록**|**O/X**|**Today's**|**한줄평**|
|--|--|--|--|
|자료구조|△|3장 이론|희소행렬 공부|
|자료구조실습|△|3장 행렬 전치 실습||
|Cpp|O|5장 함수/참조|이론 공부, 실습||
|이산수학|X|행렬||
|컴퓨터아키텍쳐|△|CPU구조||
|Seminar|X|MON - CH4 스택|공부하기|

<br>

<hr>

<br>

*2021.04.12 MON*
|**목록**|**O/X**|**Today's**|**한줄평**|
|--|--|--|--|
|자료구조|O|3장 이론/실습|희소행렬, 행렬 전치 이해|
|자료구조실습|X|이중 연결 리스트|연결리스트 복습|
|Cpp|X|6장 함수중복, static 멤버|이론 예습|
|이산수학|X|행렬||
|컴퓨터아키텍쳐|△|CPU구조||
|Seminar|X|4/28 월||

*2021.04.12 MON ~ 2021.04.13 WED TODO CHECKLIST*

### Cpp

#### CH6 함수 중복과 static 멤버 
- [x] 6.1 함수 중복 <br>
    - 함수 중복의 조건 <br>
    - 생성자 함수 중복 <br>
- [x] 6.2 디폴트 매개 변수
- [x] 6.3 함수 중복의 모호성 <br>
    - 형변환, 참조 매개 변수, 디폴트 매개 변수 <br>
- [x] 6.4 static 멤버 <br>
    - static 멤버 접근: 객체, 클래스명 <br>
  

<br>

### 자료구조

#### CH3
- [x] 3.4 희소행렬
- [x] 행렬의 연산(덧셈, 뺄셈, 곱셈)

<br>

<hr>

<br>

*2021.04.15 THRUS*

|**목록**|**O/X**|**Today's**|**한줄평**|
|--|--|--|--|
|자료구조|△|3장 희소행렬 부분|희소행렬, 행렬 전치 이해|
|자료구조실습|X|이중 연결 리스트|연결리스트 복습|
|Cpp|O|6장 함수중복, static 멤버|이론 예습||
|컴퓨터아키텍쳐|△|CPU구조||

<br>

### *2021.04.16 FRI - 2021. 04. 23 MID TERM EXAMS*

|**목록**|**O/X**|**Today's**|**한줄평**|
|--|--|--|--|
|자료구조|X|3장 희소행렬 부분|희소행렬, 행렬 전치 이해|
|자료구조실습|△|이중 연결 리스트|연결리스트 복습|
|이산수학|X|1장 이산수학 기본개념-행렬|||
|컴퓨터아키텍쳐|△|CPU구조||

<br>

### 이산수학

#### CH1
- [x] 1.1 이산수학 개념
- [x] 1.2 이산수학 마술카드 문제
- [x] 1.3 자연수와 정수
- [x] 1.4 행렬 <br>
    - 행렬 연산(행렬의 합, 차, 스칼라 곱, 곱) <br>
    - 특수 행렬 - 정방/대각/단위/전치/대칭/삼각/띠/특이/정칙/역/직교 행렬 <br>
    - 역행렬, 행렬식(소행렬식/여인수) <br>
    - 첨가/증가행렬, 가우스 조르단 소거법 <br>
    - 부울 행렬(접합 / 교합 / 부울곱) <br>
    - 고유값, 고유벡터 구하기 <br>

<br>

#### CH2 수학적 모델과 논리
- [x] 2.1 수학적 모델
- [x] 2.2 논리적 추론 <br>
    - 명제, 공리 <br>
    - 논리 연산 <br>
        - 논리곱 OR, 합 AND, 부정 NOT, 배타적 논리합 XOR <br>
        - 논리함축 -> <br>
        - 논리적 동치 <br>
    - 진리표 <br>  
    - 항진 명제 , 모순 명제 , 사건 명제 <br>
    - 역 / 이 / 대우  <br>
    - 항등 <br>
    -  명제의 표현: 술어, 한정자(전체 한정자∀, 존재 한정자∃, 유일 한정자∃!) <br>
    -  논리적 추론(가정, 전제 -> 결론) - 항진 이용 <br>
- [x] 2.3 증명 기술과 프로그램 검증 <br> 
    - 증명: 진위 추론, 허위 추론 <br>
    - vacuous 증명 방법 <br>
    - trivial 증명 방법 <br>
    - 직접 증명 방법 <br>
    - 간접 증명 방법 <br>
        - 대우 <br>
        -  배리법(반증법) <br>
        -  존재 증명 <br>
    - 명제의 거짓을 밝히는 반증 이용 방법 <br>
        - 반례 <br>
        - 모순 <br>
    - 수학적 귀납법 <br>
- [ ] 2.4 지식 베이스 시스템

<br>

#### CH4 관계
- [x] 4.1 곱집합
    - 순서쌍
    - 곱집합
        - 곱집합 크기
- [x] 4.2 관계와 관계 표현
    - 이항 관계
    - 정의역/치역/공변역
    - 항등관계
    - 관계 표현
        - 화살표 그림
        - 관계 행렬
        - 유향 그래프
- [x] 4.3 경로
    - 경로 π, 순환, x R^n y, 연결 관계
    - 관계 행렬 M (R^n) 부울곱 n 번
    - 경로의 합성
    - 역경로        
- [x] 4.4 관계의 성질
    - 반사/비반사 - 집합 A의 모든 요소 a에 대하여 aRa
    - 대칭/비대칭 - 집합 A의 어떤 요소 a와 b에 대하여 aRb이면 bRa
    - 반대칭 - 집합 A의 어떤 요소 a와 b에 대하여 aRb이고 bRa이면 a=b
    - 추이 - 집합 A의 어떤 a,b,c, 에 대하여 aRb 이고 bRc이면 aRc
    - 동치 - 반사/대칭/추이를 모두 만족
- [ ] 4.5 역관계와 합성 관계
- [ ] 4.6 연결 관계와 와샬 알고리즘


<br>

### 컴퓨터 아키텍쳐

#### CH1 컴퓨터 시스템 개요
- [ ] 1.1 컴퓨터의 기본 구조
- [ ] 1.2 정보의 표현과 저장
- [ ] 1.3 시스템의 구성
    - [ ] 1.3.1 CPU와 기억장치의 접속
    - [ ] 1.3.2 CPU와 I/O 장치의 접속
    - [ ] 1.3.3 전체 시스템 구성
- [ ] 1.4 컴퓨터 구조의 발전 과정
    - [ ] 1.4.1 초기 컴퓨터들의 구조
    - [ ] 1.4.2 주요 컴퓨터 부품들의 발전 경위
    - [ ] 1.4.3 컴퓨터시스템의 분류와 발전 동향

#### CH1 논리 회로
- [x] 이진수-디지털 신호와 아날로그 신호 비교
- [x] 논리 연산 <br>
    - AND, OR, NOT, Buffer <br>
    - NAND, NOR, XOR, XNOR <br>
- [x] 논리식과 논리 게이트
- [x] 조합 논리 회로 <br>
    - 반가산기, 전 가산기 <br>
    - 디코더, 인코더 <br>
    - (디)멀티플렉서 <br>
    - 플립플롭 <br>



<br>

#### CH2 CPU의 구조와 기능
- [x] 2.1 CPU의 기본 구조 <br>
    - ALU <br>
    - Register <br>
    - Control Unit <br>
    - CPU internal bus <br>
- [x] 2.2 명령어 실행 <br>
            - CPU register : PC, AC, IR, MAR, MBR <br>
    -  [x] 2.2.1 인출 사이클(fetch cycle)
    -  [x] 2.2.2 실행 사이클(execution cycle)
    -  [x] 2.2.3 인터럽트 사이클(interrupt cycle) <br>
            - Interrupt service routine <br>
            - multiple interrupt <br>
    -  [x] 2.2.4 간접 사이클(indirect cycle) <br>
            - indirect addressing mode <br>
- [x] 2.3 명령어 파이프라이닝 <br>
    -  [x] 2.3.1 2-단계 명령어 파이프라인(Two-Stage Instruction Pipeline) <br>
            - 인출(fetch) / 실행(execute) stage <br> 
    -  [x] 2.3.2 4-단계 명령어 파이프라인  <br>
               - 명령어 인출 / 명령어 해독 / 오퍼랜드 인출 / 실행 단계 <br>
               - 파이프라인에 의한 전체 명령어 실행 시간 T(k) = k + (N-1) <br>
        - 파이프 라인 효율 저하 요인들 <br>
        - 분기 발생에 이ㅡ한 성능 저하의 최소화 방법 <br>
    -  [x] 2.3.3 슈퍼스칼라
    -  [x] 2.3.4 듀얼-코어 및 멀티-코어
- [x] 2.4 명령어 세트
    -  [x] 2.4.1 연산 종류 <br>
            - 데이터 전송, 산술논리 연산, 입출력, 프로그램 제어 <br>
    -  [x] 2.4.2 명령어 형식  <br>
            - 연산 코드 / 오퍼랜드 <br>
            - 다음 명령어 주소 <br>
            - 명령어 형식 <br>
            - 필드 <br>
            - 명령어 길이 <br>
    -  [x] 2.4.3 주소지정 방식 <br>
               1) 직접 주소 지정 방식 <br>
               2) 간접 주소 지정 방식 <br> 
               3) 묵시적 주소 지정 방식 <br>
               4) 즉시 주소 지정 방식 <br>
               5) 레지스터 주소 지정 방식 <br>
               6) 레지스터 간접 주소 지정 방식 <br>
               7) 변위 주소 지정 방식 <br>
               8) 상대 주소 지정 방식 <br>
               9) 인덱스 주소 지정 방식 <br>
               10) 베이스-레지스터 주소  <br>
    -  [x] 2.4.4 실제 상용 프로세서들의 명령어 형식 <br>


<br>

#### CH3 컴퓨터 산술과 논리 연산
- [x] 3.1 ALU의 구성 요소
- [x] 3.2 정수의 표현
    - [x] 3.2.1 부호화-크기 표현
    - [x] 3.2.2 보수 표현
    - [x] 3.2.3 부호-비트 확장
- [x] 3.3 논리 연산
- [x] 3.4 시프트 연산
- [x] 3.5 정수의 산술 연산
    - 덧셈 뺼셈 곱셈 나눗셈
- [ ] 3.6 부동소수점 수의 표현
- [ ] 3.7 부동소수점 산술 연산
    - [ ] 3.7.1 덧셈과 뺄셈
    - [ ] 3.7.2 곱셈과 나눗셈


<br>

### 자료구조

#### CH6 연결 리스트 1
- [x] 6.1 리스트 추상 데이터 타입
- [x] 6.2 배열로 구현된 리스트
- [x] 6.3 연결 리스트
- [x] 6.4 단순 연결 리스트
- [x] 6.5 단순 연결 리스트의 구현
        - 리스트 생성, 초기화
        - 노드 생성, 추가, 삽입
        - 정렬과 출력
        - 노드 데이터 탐색
        - 역순 연산
- [x] 6.6 연결 리스트의 응용: 다항식

<br>


---

### 04.23 - 04.26 

|**목록**|**O/X**|**Today's**|**한줄평**|
|--|--|--|--|
|Seminar||04.26 Stack, sParseMatrix, transpose|stack study, PPT|
|DataStructure Practice||원형/이중 연결 리스트 구현실습|book reference|
|DataStructure||다항식배열|복습|
|CPP||프렌드/연산자중복|예습|

### 자료구조

#### CH4 스택
- [x] 4.1 스택의 개념
- [x] 4.2 스택의 구현
- [x] 4.3 동적 배열 스택
- [x] 4.4 스택 응용: 괄호 검사 문제
- [x] 4.5 스택 응용: 후위 표기 수식 계산
- [x] 4.6 스택 응용: 미로 문제

#### CH7 연결 리스트 2
- [x] 7.1 원형 연결 리스트
- [x] 7.2 원형 연결리스트의 사용
- [x] 7.3 이중 연결 리스트
- [ ] 7.4 예제: mp3 프로그램
<br>

### CPP

#### CH7 프렌드와 연산자 중복

- [x] 7.1 C++ 프렌드 개념 <br>
    - 프렌드 함수, friend 키워드
    - 전방 참조, 전방 선언
- [x] 7.2 연산자 중복 (Operatior Overloading)
    - 연산자 함수 (Operator Function)
    - operator 키워드
- [x] 7.3 이항 연산자 중복
    - +, - ==, +=, -=
    - 참조 리턴, *this 리턴
- [x] 7.4 단항 연산자 중복
    - ++, -- ! 
    - 전위/후위 연산자
- [x] 7.5 프렌드를 이용한 연산자 중복
- [x] 7.6 참조를 리턴하는 << 연산자 실습



### LikeLion 9th Class 

#### Web Basic
- [x] Web & Web Service
- [x] 웹 서버를 만드는 방법
- [x] HTML [1]
- [x] HTML [2]
- [x] HTML [3]
- [x] Bootstrap
- [x] Github 배포

#### HTML & CSS
- [x] HTML 기초
- [x] 텍스트와 관련된 태그
- [x] 링크 태그
- [ ] 멀티미디어와 관련된 태그
- [x] 테이블과 리스트
- [x] 폼 태그
- [x] CSS 기초
- [x] 선택자
- [x] 값과 단위
- [x] 텍스트와 관련된 프로퍼티
- [x] 박스 모델
- [x] 위치와 관련된 프로퍼티 [1]
- [x] 위치와 관련된 프로퍼티 [2]
- [x] 상속과 우선순위
- [ ] Bootstrap

<br>

---

### 05.07 - 05.10

|**목록**|**O/X**|**Today's**|**한줄평**|
|--|--|--|--|
|Seminar-DS|O|05.10 스택-개념.구현.후위연산표기.계산/희소행렬/행렬전치|stack study, PPT|
|CPP|△|프렌드/연산자중복 정리|복습|
|CPP|△|상속|복습,정리|
|멋사|O|HTML/CSS강의|복습다시...|

<br>

### 컴퓨터 아키텍처

#### CH4. 제어 유니트 (Control Unit)

- [x] 4.1 제어 유니트 기능 <br>
- [x] 4.2 제어 유니트 구조 <br>
    - 명령어 해독기(Instruction Decoder) <br>
        - 사상 (mapping) 방식 <br>
            - 제어 주소 레지스터(CAR: Control Address Register) <br>
            - 제어 기억장치(Control Memory) <br>
            - 제어 버퍼 레지스터(CBR: Control Buffer Register) <br>
            - 서브루틴 레지스터(SBR: Subroutine Register) <br>
            - 순서 제어 모듈(Sequencing Module) <br>
- [x] 4.3 마이크로 명령어 형식 <br>
    - 연산 필드 1, 2 / 조건(CD) 필드 / 분기(BR) 필드 / 주소(AD) 필드 <br> 
- [x] 4.4 마이크로프로그래밍 <br>
    - 인출 사이클 루틴 <br>
    - 간접 사이클 루틴 <br>
    - 실행 사이클 루틴 <br>
    - 사상 방식 이용 <br>
- [x] 마이크로프로그램의 순서제어 <br>
    - 순서 제어(Sequencing)  / MUX1, MUX2 <br>
    - 주소 선택 회로 <br>
    - 제어 신호의 생성 <br>
        - 수직적 마이크로프로그래밍 (Vertical MicroProgramming) <br>
        - 수평적 마이크로프로그래밍 (Horizontal MicroProgramming) <br>



#### CH5. 기억장치
- [x] 5.1 기억장치 분류와 특성 <br>
    - 기억 장치 액세스 <br>
        - 1. 순차적 액세스(sequential access) <br>
        - 2. 직접 액세스(direct access) <br>
        - 3. 임의 액세스(random access) <br>
            - 4. 연관 액세스(associative access) <br>
    - 기억장치 설계 <br>
       - 용량/속도 <br>
        - 전송 단위(unit of transfer) <br>
        - 주소지정 단위(addressable unit) <br>
    - 액세스 속도 파라미터 <br>
        - 액세스 시간(access time) <br>
        - 기억 장치 사이클 시간(memory cycle time) <br>
        - 데이터 전송률(data transfer rate) <br>
    - 기억 장치 제조 재료에 따른 유형 <br>
        - 반도체 기억장치(semiconductor memory) <br>
        - 자기-표면 기억장치(magnetic-surface memory) <br>
    - 데이터를 저장하는 성질에 따른 유형 <br>
        - 휘발성(volatile) / 비휘발성(nonvolatile) 메모리 <br>
- [x] 5.2 계층적 기억장치시스템 <br>
    - 내부 기억 장치 / 외부 기억 장치 <br>
    - 캐시 메모리 / 디스크 캐시 <br>
- [x] 5.3 반도체 기억장치 <br>
    - RAM(Random Access Memory) - DRAM, SDRAM <br>
    - ROM(Read Only Memory) - PROM< EPROM< EEPROM, flash memory <br>
- [x] 5.4 기억장치 모듈 설계 <br>
    - 병렬 접속 <br>
    - 직렬 접속 <br>
    - 기억장치 모듈의 설계 순서 <br>
        - 기억 장치 주소 표(memory address map) <br>
- [x] 5.5 캐시 메모리 <br>
    - [x] 5.5.1 캐시 용량 <br>
    - [x] 5.5.2 인출 방식 <br>
        - 요구 인출(demand fetch) 방식 <br>
        - 선인출(prefetch) 방식 <br>
    - [x] 5.5.3 사상 방식 <br>
        - 1. 직접 사상(Direct Mapping)
        - 2. 완전-연관 사상(Fully-Associative Mapping)
        - 3. 세트-연관 사상(Set-Associative Maaping)
    - [ ] 5.5.4 교체 알고리즘
    - [x] 5.5.5 쓰기 정책
        - 1. Write-Trhough
        - 2. Write-Back
    - [x] 5.5.6 다중 캐시
        - 온-칩 캐시(On-Chip Cahce)
        - 1. 계층척 캐시(Hierarchial Cache)
        - 2. 분리 캐시(Split Cache)
- [x] 5.6 DDR SDRAM
    - [x] 5.6.1 SDRAM
    - [x] 5.6.2 DDR SDRAM
    - [ ] 5.6.3 기억장치 랭크
- [x] 5.7 차세대 비휘발성 기억장치
    - [x] 5.7.1 PRAM
    - [x] 5.7.2 FRAM
    - [x] 5.7.3 MRAM


<br>

### 자료구조
#### CH5. 큐
- [x] 5.1 큐 추상 데이터 타입
- [x] 5.2 선형큐
- [x] 5.3 원형큐
- [x] 5.4 큐의 응용: 버퍼
- [x] 5.5 덱
- [x] 5.6 큐 응용 : 시뮬레이션


<br>

---

### 05.11 - 05.14

|**목록**|**O/X**|**Today's**|**한줄평**|
|--|--|--|--|
|Seminar-DS|X|05.17 CH5.큐 / 스택-중위->후위표기,계산 / 희소행렬,행렬전치|queue study, PPT|
|CPP|O|가상함수, 추상클래스|ch7.8복습|
|멋사|O|Python basic|python codeup 기초 100제 50문제 풀기|
|자료구조|X|CH4복습/레포트|개요|
|DL||05.14 - MNIST, 자료||

### CPP

#### CH8. 상속 (Inheritance)

- [x] 8.1 상속의 개념
    - 상속 / 기본 클래스 (base class) - 파생 클래스 (derived class)
- [x] 8.2 클래스 상속과 객체
    - 상속 접근 지정
    - 파생 클래스 객체
- [x] 8.3 상속과 객체 포인터
    - 업캐스팅(up-casting) / 다운캐스팅(down-casting)과 명시적 형변환
- [x] 8.4 protected 접근 지정
- [x] 8.5 상속과 생성자, 소멸자
    -  묵시적인 기본 생성자선택, 명시적 생성자 선택, 
- [x] 8.6 상속의 종류 : public, protected, private 상속
- [x] 8.7 다중 상속 (Multiple Inhertiance)
- [x] 8.8 가상 상속 (Virtual Inheritance)
    - 가상 기본 클래스 (virtual base class)

<br>

#### CH9. 가상 함수와 추상 클래스 (Virtual Function / Abstract Class)

- [x] 9.1 상속 관계에서의 함수 재정의 (Function Redefine)
- [x] 9.2 가상 함수와 오버라이딩 (Virtual Function Overriding)
    - 함수 오버라이딩 - 실행 시간 다형성(run time polymorphism)
    - 가상 함수 (virtual function) 
    - 동적 바인딩(Dynamic Binding)
    - override, final 지시어
    - 범위 지정 연산자(::)
    - 가상 소멸자
- [x] 9.3 가상 함수와 오버라이딩의 활용 사례
- [x] 9.4 추상 클래스 (abstract class)
    - 순수 가상 함수 (pure virtual function)
    
<br>


<br>

---

### 05.15 - 06.10
### Final Exam

|**목록**|**O/X**|**Today's**|**한줄평**|
|--|--|--|--|
|Seminar-DS|X|05.17 CH5.큐 / 스택-중위->후위표기,계산 / 희소행렬,행렬전치|queue study, PPT|
|CPP|O|ch 10 STL |ch7,8,9 복습|
|CPP|X|ch11|ch7~11복습|
|멋사|O|Python basic|python codeup 기초 100제 끝내기|
|멋사스터디|O|openAPI|python openAPI 공공데이터 활용 프로젝트|
|자료구조|O|CH4복습/레포트|개요|
|자료구조실습|X|CH5|얼른..|

### CPP

#### CH10. 템플릿과 표준 템플릿 라이브러리(STL)

- [x] 10.1 일반화와 템플릿 (Template)
    - 템플릿 함수 (template function) , 제네릭 함수 (generic function)
    - 제네릭 타입
    - 템플릿으로부터의 구체화(specialization)
- [x] 10.2 다양한 제네릭 함수 만들기
- [x] 10.3 제네릭 클래스 만들기 (Generic Class)
    - 제네릭 클래스 객체 <specialized type>
- [x] 10.4 C++ 표준 템플릿 라이브러리(STL)와 활용 (Standard Template Library)
    - STL 컨테이너 - 템플릿 클래스 
        - 1. 순차 컨테이너 - vector, dequeue, list
        - 2. 컨테이너 어댑터 - stack, queue
        - 3. 연관 컨테이너 - set, map
    - STL iterator 포인터 
    - STL 알고리즘 함수
- [x] 10.5 auto와 람다식
        
<br>

#### CH11. C++ 입출력 시스템
        
- [x] 11.1 C++ 입출력 기초
    - 스트림(stream) - 표준 입력/출력/오류 출력 스트림 객체
    - 버퍼(buffer) - 입력/스트림 버퍼
    - C++ 입출력 라이브러리 - 템플릿을 통한 일반화
- [x] 11.2 ostream의 멤버 함수 이용 문자 출력
    - << 연산자, cout 스트림 객체
    - put, write, flush
- [x] 11.3 istream 멤버 함수 이용 문자 입력
    - >> 연산자, cin 입력 스트림 객체
    - get, getline, ignore, gcount
- [x] 11.4 포맷 입출력
    - 포맷 플래그 (format flag)
        - ios::left, ios::right / ios::dec, oct, hex  ios::boolalpha
        - setf(), unsetf()
    - 포맷 함수(format function)
        - width, fill, precision
    - 조작자(manipulator)
        - endl, oct,dec,hex, left, right, skipws, noskipws, boolalpha
        - setfill, setprecision, setw
- [x] 11.5 삽입 연산자<< 추출 연산자>>
- [x] 11.6 사용자 조작자 만들기
        
<br>

#### CH12. C++ 파일 입출력
        
- [x] 12.1 텍스트 파일, 바이너리 파일
    - 텍스트 파일  문자: 아스키/유니코드 - '\r'. '\n'
- [x] 12.2 파일 입출력 개요
    - ifstream, ofstream, fstream
    - 파일 입출력 모드
- [x] 12.3 <<, >> 연산자를 이용한 텍스트 파일 입출력
    - 파일 입출력 스트림 객체, 열기/검사 객체.open() (!객체), 입출력, 닫기 객체.open()
- [x] 12.4 파일 모드 (file mode)
    - ios::in, out, ate, app, binary
    - | 연산
- [x] 12.5 멤버 함수 이용한 텍스트 IO
    - get()과 EOF
    - put()
    - getline()
- [x] 12.6 바이너리 IO
    - read(), write() 블록 단위, gcount()
- [x] 12.7 스트림 상태 검사 (stream state check
    - eofbit, failbit, badbit
    - eof(), fail(), bad(), good(), clear()
- [x] 12.8 임의 접근 (random file access)
    - 파일 포인터 (file pointer)
    - seekg, seekp, tellg, tellp
    - ios::beg, cur, end
<br>

#### CH13. 예외 처리와 C 언어와의 링크 지정
- [ ] 13.1 실행 오류, 오류 처리
- [ ] 13.2 예외, 예외 처리
- [ ] 13.3 예외 처리란
- [ ] 13.4 예외 클래스
- [ ] 13.5 C++코드, C코드 링킹

<br><br>





### 컴퓨터 아키텍쳐

#### CHAPTER 06 보조저장장치
- [x] 6.1 하드 디스크
   - [x] 6.1.1 디스크의 구조 <br>
       - 구성 요소 : 원형 평판 / 헤드 / 디스크 팔 / 구동장치
       - 단일-헤드 / 다중-헤드
       - 이동-헤드 / 고정-헤드
       - 구조 : 섹터 / 섹터간갭  트랙간갭
       - 등각 속도 방식(CAV: Constant Angular Velocity) / 다중 영영 기록 방식(MZR: Multiple Zone Recording)
       - 디스크 형식화 작업(Disk Formatting)
       - 디스크 드라이브(Disk Drive)
           - 양면 / 단면 디스크
           - 실린더(Cylinder)
           - 단일-평판 / 다중-평판 디스크 드라이브
   - [x] 6.1.2 디스크 액세스 시간
       - 탐색 시간(Seek Time) / 회전 지연 시간(Rotational Latency Time) / 데이터 전송 시간(Data Transfer Time)
- [x] 6.2 RAID
     - [x] 6.2.1 RAID 출현의 배경
     - [x] 6.2.2 RAID의 종류
         - 기본 기술 : 디스크 인터리빙 (Disk-Interleaving) / 라운드-로빈 방식(Round-Robin)
         - RAID-1 : 디스크 미러링(Disk Mirroring) 방식
         - RAID-2 : 비트-단위 인터리빙 방식 / 해밍 코드(Hamming Code)
         - RAID-3 : 패리티 방식 / 팰티 비트
         - RAID-4 : 블록-단위 인터리빙 방식
         - RAID-5 : 패리티 블록의 라운드-로빈 방식으로의 분산 저장 방식
- [x] 6.3 플래시 메모리와 SSD
     - [x] 6.3.1 플래시 메모리
     - [x] 6.3.2 SSD
         - 마모 평준화(Wear Leaving)
         - 쓰레기 수집(Garbage Collection)
         - 초과 대비 공간(over-Provisioning)
     - 광 저장 장치 - CD-ROM : 등선 속도(CLV: Constant Linear Velocity)
<br>

#### CH 07 시스템 버스, I/O 밑 인터럽트
- [x] 7.1 시스템 버스
   - [x] 7.1.1 시스템 버스 조직
   - [x] 7.1.2 시스템 버스 기본 동작
- [x] 7.2 버스 중재
   - [x] 7.2.1 병렬 중재 방식
   - [x] 7.2.2 직렬 중재 방식
   - [x] 7.2.3 폴링 방식
- [x] 7.3 IO 장치 접속
   - [x] 7.3.1 IO 제어
   - [x] 7.3.2 IO 주소 지정
- [x] 7.4 인터럽트 이용 IO
   - [x] 7.4.1 다중 인터럽트 방식
   - [x] 7.4.2 데이지-체인 방식
   - [x] 7.4.3 소프트웨어 폴링 방식
- [x] 7.5 DMA 이용 IO 

<br>



### 이산 수학

#### CH4 관계
- [x] 4.1 곱집합
- [x] 4.2 관계와 관계 표현
- [x] 4.3 경로
- [x] 4.4 관계의 성질
    - 동치 관계(equivalence relation)
- [x] 4.5 역관계와 합성 관계
    - 역관계(inverse relation) 
    - 여 관계 (complementary relation)
    - 관계 행렬을 이용한 여러 관계의 성질(AND연산, OR연산, 전치-여관계, 여행렬)
    - 합성 관계(composite relation) - 교환법칙 성립x, 결합법칙 성립 o
    - 합성 관계의 부울곱 표현(결합)
    - 합성 관계의 결합 법칙
    - 합성 관계에 대한 역 관계
- [x] 4.6 연결 관계와 와샬 알고리즘
    - 닫힘 (closure) : 반사/대칭/추이 닫힘
    - 연결 관계 -> 추이 닫힘 ( 1) 유항 그래프   2) 관계 행렬)
    - 와샬 알고리즘(warshlall algorithm)
    - 가장 작은 동치 관계
<br>

#### CH6 부분 순서 관계와 부울 대수
- [x] 6.1 부분 순서 관계
    - 부분 순서 관계(partially ordered relation) - 반사, 반대칭, 추이 관계 
    - 전순서 관계(tortally ordered relation) - 모든 원소의 비교 가능(totally comparable)
    - 곱 부분 순서 관계(product partial ordered relation)
    - 사전식 순서(lexicographic order)
    - 위상 정렬(topological sorting) 
- [x] 6.2 부분 순서 집합의 상한과 하한
    - 극대/극소 원소(maximal/minimal element), 최대/최소 원소(greatest/least element)
    - 최대원소 I(단위원), 최소원소 0(영원)
    - 상계/하계(upper/lower bound)
    - 상한/하한(LUB-least upper bound:supremum / GLB-greatest lower bound:infimum)
- [x] 6.3 격자
    - 격자(lattice)
    - 격자의 성질
        - 멱등법칙(dempotenet law), 교환법칙(commutative), 결합(associative), 흡수(absortion) 법칙
- [x] 6.4 특별한 형태의 격자
    - 부분 격자 - 동형 사상(isomorphism)
    - 완비 격자(complete lattice)
    - 유계 격자(bounded lattice)
    - 분배 격자(distributive lattice), 비분배 격자
    - 여격자(complemented lattice), 여원(complement element)
- [x] 6.5 부울 대수
    - 부울 대수(boolean algebra) : 여격자, 분배 격자
- [x] 6.6 응용 : 2-비트 가산기의 설계
    - 반가산기(half adder)
        - 올림수(carry): AND연산
        - 더하기: XOR 연산
<br>


<hr>

### 이산수학

#### CH7 그래프
- [ ] 7.1 그래프 개념
- [ ] 7.2 여러가지 그래프
- [ ] 7.3 평면 그래프
- [ ] 7.4 정점의 착색

### CH8 트리
- [ ] 8.1 트리 개념
- [ ] 8.2 레이블을 갖는 트리, 최소 스패닝 트리
- [ ] 8.3 트리 탐방 알고리즘





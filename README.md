# python-basic
고등학교 입학 전 파이썬 기초 문법을 정리하며 학습한 내용입니다.  
변수, 조건문, 반복문, 함수 등 기본적인 개념을 이해하는 것을 목표로 합니다.
# 조건문과 반복문 연습
# 1부터 10까지의 숫자 중 짝수만 출력하기

for i in range(1, 11):
    if i % 2 == 0:
        print(i)
# Algorithm Basic

간단한 알고리즘 문제를 풀며  
문제를 분석하고 해결하는 사고 과정을 연습한 기록입니다.
# 문제: 1부터 n까지의 합을 구하시오.
# 풀이:
# 반복문을 사용하여 누적 합을 계산한다.

n = int(input())
total = 0

for i in range(1, n + 1):
    total += i

print(total)
mini-projects
 └─ robot-distance-checker
     ├─ distance_checker.py
     └─ README.md
# 로봇 거리 판단 프로그램
# 센서로부터 거리 값을 입력받아
# 로봇이 앞으로 갈지 멈출지를 판단한다

distance = int(input("장애물까지의 거리(cm)를 입력하세요: "))

if distance < 20:
    print("정지")
else:
    print("전진")
# 로봇 거리 판단 프로그램

## 프로젝트 개요
로봇이 장애물과의 거리를 판단하여  
앞으로 이동할지 멈출지를 결정하는 간단한 제어 프로그램입니다.

## 사용 기술
- Python

## 구현 기능
- 거리 값 입력
- 조건에 따른 로봇 행동 판단

## 배운 점
조건문을 활용해 로봇의 행동을 제어하는 기본 개념을 이해했습니다.

## 향후 개선
실제 거리 센서와 연동해 보고 싶습니다.





# python-basic

고등학교 입학 전, **파이썬 기초 문법을 정리하며 학습한 내용**을 기록한 포트폴리오입니다.
변수, 조건문, 반복문, 함수 등 **기본 개념을 이해하는 것**을 목표로 학습했습니다.

---

## 1. Python Basic Grammar

### 학습 목표

* 변수와 자료형 이해
* 조건문(if)과 반복문(for, while) 활용
* 간단한 문제를 코드로 해결하는 사고력 기르기

---

## 2. 조건문과 반복문 연습

### 문제 1 : 1부터 10까지의 숫자 중 짝수만 출력하기

```python
for i in range(1, 11):
    if i % 2 == 0:
        print(i)
```

#### 학습 내용

* `for` 반복문을 이용한 숫자 순회
* 나머지 연산자 `%`를 활용한 짝수 판별
* 조건문과 반복문의 결합 사용

---

## 3. Algorithm Basic

간단한 알고리즘 문제를 풀며 **문제를 분석하고 해결하는 사고 과정**을 연습했습니다.

### 문제 : 1부터 n까지의 합을 구하시오

#### 풀이 방법

* 반복문을 사용하여 값을 하나씩 더하며 누적 합을 계산

```python
n = int(input())
total = 0

for i in range(1, n + 1):
    total += i

print(total)
```

#### 학습 내용

* 사용자 입력 처리 (`input`, `int`)
* 누적 변수 개념 이해
* 반복문을 활용한 계산 로직 구현

---

## 4. Mini Project

### 📁 robot-distance-checker

```
mini-projects
└─ robot-distance-checker
   ├─ distance_checker.py
   └─ README.md
```

---

## 5. 로봇 거리 판단 프로그램

### 프로젝트 개요

센서로부터 거리 값을 입력받아,
로봇이 **앞으로 이동할지 또는 멈출지를 판단**하는 간단한 제어 프로그램입니다.

---

### 구현 코드

```python
distance = int(input("장애물까지의 거리(cm)를 입력하세요: "))

if distance < 20:
    print("정지")
else:
    print("전진")
```

---

### 사용 기술

* Python

---

### 구현 기능

* 거리 값 입력 받기
* 조건문을 이용한 로봇 행동 판단

---

### 배운 점

* 조건문을 활용해 프로그램의 흐름을 제어하는 방법을 이해함
* 로봇 제어의 기초적인 논리를 코드로 구현해봄

---

### 향후 개선 방향

* 실제 초음파 센서 또는 거리 센서와 연동
* Arduino 또는 Raspberry Pi와 결합한 로봇 제어 프로젝트로 확장

---

## 마무리

이 포트폴리오는 **프로그래밍 기초 역량을 쌓아가는 과정**을 기록한 자료입니다.
앞으로 로봇 제어, 알고리즘, 임베디드 프로그래밍까지 확장해 나갈 계획입니다.


python-basic
Python 기초 문법 학습 포트폴리오 (Pre-High School)

고등학교 입학 전, 파이썬의 기초 문법과 프로그래밍 사고력을 기르기 위해 학습한 내용을 정리한 포트폴리오입니다.
반복문, 조건문, 자료구조, 함수 등을 중심으로 문법 이해 → 문제 해결 → 응용의 흐름으로 학습했습니다.

📌 학습 목표

Python 기본 문법 이해

반복문과 조건문을 활용한 흐름 제어

자료구조(List, Tuple, Dictionary) 활용

문자열 처리 및 슬라이싱 이해

간단한 알고리즘 문제 해결 능력 향상

로봇·임베디드 프로그래밍의 기초 논리 학습

1️⃣ Python Basic Grammar
주요 학습 내용

출력 제어 (print, sep, end)

산술 연산자 및 축약 연산자

입력 처리 (input, int, float, map)

문자열 처리 및 슬라이싱

a = 10
b = 20
c = a + b

print(a, b, c, sep="+", end="***")
print("cat tower")

2️⃣ 반복문 (for / while)
예제 1: 숫자와 제곱 출력
for x in range(3):
    print(x, end=" ")
    print(x * x, end=":\n")


학습 포인트

range() 함수 구조 이해

반복문 내부 연산 처리

출력 형식 제어

예제 2: 특정 범위 출력
for x in range(6, 100, 2):
    print(x, end=" ")


range(start, end, step) 활용

규칙적인 수열 출력

while 문 활용 예제
n = 1
total = 0

while True:
    total += n
    if total > 50:
        break
    n += 1


무한 반복과 break 제어

조건 만족 시 반복 종료

3️⃣ 조건문 (if / else)
로봇 거리 판단 프로그램
distance = int(input("장애물까지의 거리(cm)를 입력하세요: "))

if distance < 20:
    print("정지")
else:
    print("전진")


학습 포인트

사용자 입력 처리

조건에 따른 분기

로봇 제어 로직의 기초 이해

4️⃣ 자료구조
리스트(List)
vegetable = ['고구마','감자','호박','상추','깻잎','오이']
nums = [23,45,98,74,46,36]


인덱싱 / 슬라이싱

append, insert, sort, max

반복문과 함께 사용

튜플(Tuple)
point = (10.5, 20.2)


불변 자료형 이해

좌표 데이터 표현

딕셔너리(Dictionary)
parts = {"엔진":0, "볼트":0, "너트":0}

parts["볼트"] += 100


키-값 구조 이해

재고 관리 형태의 응용

5️⃣ 문자열 처리 & 슬라이싱
word = "robot"
print(word[::-1])


문자열은 이터러블

슬라이싱 [start:end:step]

문자열 뒤집기 및 분리

6️⃣ 함수(Function)
조사 판별 함수
def auxWord(word):
    last = word[-1]
    if (ord(last) - ord('가')) % 28 == 0:
        return '는'
    else:
        return '은'


함수 정의 및 호출

문자열 처리 로직 구현

한글 유니코드 이해

7️⃣ 알고리즘 기초
문제: 1부터 n까지의 합
n = int(input())
total = 0

for i in range(1, n + 1):
    total += i

print(total)


누적 변수 개념

반복문을 이용한 계산

문제 분석 → 코드 구현

8️⃣ Mini Project
📁 robot-distance-checker
mini-projects
└─ robot-distance-checker
   ├─ distance_checker.py
   └─ README.md


프로젝트 개요

거리 값을 입력받아 로봇의 행동(정지/전진)을 판단하는 프로그램

배운 점

조건문을 활용한 로직 설계

로봇 제어의 기본 구조 이해

향후 확장

초음파 센서 연동

Arduino / Raspberry Pi와 결합

실제 로봇 제어 프로젝트로 발전

🧭 마무리

이 저장소는 프로그래밍 기초 역량을 쌓아가는 과정을 기록한 포트폴리오입니다.
앞으로 로봇 제어, 알고리즘, 임베디드 프로그래밍까지 확장해 나갈 계획입니다.

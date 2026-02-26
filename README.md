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


# 📘 Python Algorithm & Mini Projects Portfolio

고등학교 입학 전, 파이썬 기초 문법과 알고리즘 사고력을 기르기 위해 학습한 내용을 정리한 포트폴리오입니다.
기본 문법 이해부터 간단한 로봇 제어 로직까지 단계적으로 연습했습니다.

---

## 🧠 Algorithm Basic

### 📌 목적

간단한 알고리즘 문제 풀이를 통해 **문제를 분석하고 해결하는 사고력**을 기르는 것을 목표로 합니다.
각 문제는 풀이 과정을 단계적으로 정리하고, 코드에는 주석을 통해 사고 과정을 설명했습니다.

---

### 문제 1. 두 개의 정수를 입력받아 더 큰 수를 출력하시오

#### 풀이 과정

1. 두 개의 정수를 입력받는다.
2. `if` 문을 사용하여 두 수를 비교한다.
3. 더 큰 값을 출력한다.

```python
a, b = map(int, input().split())

if a > b:
    print(a)
else:
    print(b)
```

#### 학습 포인트

* 다중 입력 처리 (`map`, `split`)
* 조건문을 활용한 값 비교

---

### 문제 2. 1부터 n까지의 수 중 짝수의 합을 구하시오

#### 풀이 과정

1. 반복문으로 1부터 n까지의 수를 확인한다.
2. 짝수일 경우에만 누적 합을 계산한다.

```python
n = int(input())
total = 0

for i in range(1, n + 1):
    if i % 2 == 0:
        total += i

print(total)
```

#### 학습 포인트

* 반복문과 조건문의 결합
* 누적 합 알고리즘 이해

---

## 🤖 Mini Projects

### 📁 robot-action-decider

```
mini-projects
└─ robot-action-decider
   ├─ action_decider.py
   └─ README.md
```

---

### 로봇 행동 결정 프로그램

#### 프로젝트 개요

로봇이 **장애물과의 거리**와 **배터리 잔량**을 입력받아,
현재 상황에 따라 적절한 행동을 결정하도록 만든 간단한 제어 프로그램입니다.

---

#### 구현 코드

```python
distance = int(input("장애물과의 거리(cm): "))
battery = int(input("배터리 잔량(%): "))

if distance < 20:
    print("정지")
elif battery < 30:
    print("충전 필요")
else:
    print("전진")
```

---

#### 사용 기술

* Python

---

#### 구현 기능

* 거리 값 입력
* 배터리 상태 확인
* 조건에 따른 로봇 행동 판단

---

#### 배운 점

* 여러 조건을 고려하는 조건문 로직을 설계할 수 있게 됨
* 로봇 제어의 기본적인 판단 구조를 이해함

---

#### 향후 개선

* 실제 거리 센서와 배터리 센서 입력과 연동
* Arduino 기반 로봇 제어 프로그램으로 확장

---

## ✨ 마무리

이 저장소는 **파이썬 기초 문법, 알고리즘 사고력, 로봇 제어 논리**를 함께 성장시킨 학습 기록입니다.
앞으로 더 복잡한 알고리즘 문제와 실제 하드웨어 제어 프로젝트로 확장할 계획입니다.


# 📘 Python Basic Grammar & Algorithm Portfolio

고등학교 입학 전, 파이썬의 **기초 문법과 알고리즘 사고력**을 기르기 위해 학습한 내용을 정리한 포트폴리오입니다.
조건문, 반복문, 팩토리얼, 문자열 포맷 등 프로그래밍의 핵심 개념을 예제 중심으로 학습했습니다.

---

## 1️⃣ 조건식 (Condition)

조건식이란 **True 또는 False로 판단할 수 있는 식**을 의미합니다.

```python
a = 10
b = 20

print(a > b)   # False
print(a == b)  # False
print(a < b)   # True
```

✔ 결과가 `True / False`로 나오면 모두 조건식입니다.

---

## 2️⃣ 선택문 (if Statement)

### 2.1 단일 선택문

```python
age = 15

if age >= 14:
    print("중학생 이상입니다.")
```

---

### 2.2 다중 선택문 (if - elif - else)

여러 조건 중 **하나만 실행**됩니다.

```python
score = 85

if score >= 90:
    print("A")
elif score >= 80:
    print("B")
elif score >= 70:
    print("C")
else:
    print("F")
```

---

### 2.3 양자 택일 선택문 (if - else)

두 가지 경우 중 하나를 선택합니다.

```python
num = 10

if num % 2 == 0:
    print("짝수")
else:
    print("홀수")
```

---

### 2.4 조건 표현식 (삼항 연산자)

```python
num = 10
result = "짝수" if num % 2 == 0 else "홀수"
print(result)
```

---

## 3️⃣ 반복문 (Loop)

### 반복문의 종류

* `for` 문
* `while` 문

---

## 4️⃣ for 반복문

시퀀스(iterable)의 요소를 하나씩 꺼내 반복합니다.

```python
for 변수 in 시퀀스:
    실행할 문장
```

### 예제 1 : 리스트 반복

```python
for animal in ["dog", "cat", "mouse"]:
    print(f"{animal} is a mammal.")
```

출력 결과

```
dog is a mammal.
cat is a mammal.
mouse is a mammal.
```

---

### 예제 2 : range 사용

```python
for i in range(4):
    print(i, end=" ")
```

출력 결과

```
0 1 2 3
```

---

## 5️⃣ 들여쓰기 (Indentation)

✔ 파이썬에서 들여쓰기는 **문법의 일부**입니다.

* 코드 블록을 구분하는 역할
* 보통 공백 4칸 사용
* 들여쓰기가 다르면 오류 발생

```python
if True:
    print("정상")
  print("에러")  # ❌ Indentation Error
```

---

## 6️⃣ 반복문 실습 예제

### 6.1 구구단 출력

```python
n = int(input())

for i in range(1, 10):
    print(f"{n} * {i} = {n * i}")
```

---

### 6.2 삼각형 출력

```python
n = int(input())

for i in range(1, n + 1):
    print("*" * i)
```

---

### 6.3 피보나치 수열 (앞의 20개)

```python
a, b = 0, 1

for _ in range(20):
    print(a, end=" ")
    a, b = b, a + b
```

---

### 6.4 숫자 맞추기 게임

```python
import random

secret = random.randint(1, 100)
count = 0

while True:
    guess = int(input("숫자 입력: "))
    count += 1

    if guess > secret:
        print("더 작은 수입니다!")
    elif guess < secret:
        print("더 큰 수입니다!")
    else:
        print(f"{count}번 만에 맞추셨습니다!")
        break
```

---

## 7️⃣ 팩토리얼 (Factorial)

### 정의

```
n! = n × (n-1) × (n-2) × ... × 1
```

### 반복문으로 구현

```python
n = int(input())
result = 1

for i in range(1, n + 1):
    result *= i

print(result)
```

---

## 8️⃣ f-string (문자열 포맷)

```python
name = "Python"
age = 10

print(f"{name} is {age} years old.")
```

---

### 📌 f-string 포맷 지정자 요약표

| 포맷        | 의미      | 예시           | 결과        |
| --------- | ------- | ------------ | --------- |
| `{x}`     | 기본 출력   | `f"{x}"`     | 10        |
| `{x:d}`   | 정수      | `f"{x:d}"`   | 10        |
| `{x:f}`   | 실수      | `f"{x:f}"`   | 10.000000 |
| `{x:.2f}` | 소수 2자리  | `f"{x:.2f}"` | 10.00     |
| `{x:,}`   | 천 단위 구분 | `f"{x:,}"`   | 1,000     |
| `{x:05d}` | 0 채우기   | `f"{x:05d}"` | 00010     |
| `{x:<5}`  | 왼쪽 정렬   | `f"{x:<5}"`  | 10        |
| `{x:^5}`  | 가운데 정렬  | `f"{x:^5}"`  | 10        |

---

## ✨ 마무리

이 저장소는 **파이썬 기초 문법, 반복문·조건문 활용, 알고리즘 사고력**을 체계적으로 정리한 학습 기록입니다.
향후 로봇 제어 및 실제 센서 연동 프로젝트로 확장할 계획입니다.

# python-basic

## 목적

생각하는 힘과 문제 해결력을 기르기 위해 Python 기본 문법을 정리하고,
각 개념을 예제와 함께 정리한 학습 기록입니다.

튜플(tuple)과 사전(dictionary)을 중심으로,
자료구조의 특징과 활용 방법을 이해하는 것을 목표로 했습니다.

---

## 튜플 (Tuple)

### 개념

* 여러 값을 하나로 묶어 저장하는 자료형
* **순서가 있으며 (ordered)**
* **한 번 생성되면 값 변경 불가 (immutable)**

### 특징

* 입력한 순서 유지
* 중복 허용
* 인덱싱 / 슬라이싱 가능
* 값 변경 불가로 안전함

### 튜플 생성 예시

```python
# 기본 튜플
t1 = (1, 2, 3)

# 괄호 없이도 가능
t2 = 4, 5, 6

# 요소가 하나일 때는 콤마 필수
t3 = (7,)   # 튜플
t4 = (7)    # 정수
```

### 튜플 사용 예시 1

```python
# 인덱싱
print(t1[0])      # 1

# 슬라이싱
print(t1[1:])     # (2, 3)

# 튜플은 불변
# t1[0] = 10  → 오류 발생
```

### 튜플 사용 예시 2

```python
tup = (1, 2, 3)
print(tup[0])     # 1

# tup[0] = 3  → TypeError 발생
```

### 튜플 사용 예시 3

```python
print(type((1)))    # int
print(type((1,)))   # tuple
print(type(()))     # tuple
```

### 튜플 사용 예시 4

```python
len(tup)            # 3
tup + (4, 5, 6)     # (1, 2, 3, 4, 5, 6)
tup[:2]             # (1, 2)
2 in tup             # True
```

---

## 튜플 언패킹 (Unpacking)

```python
x, y, z = (12.3, 28.3, 9.87)
```

### 확장 언패킹

```python
a, *b, c = (1, 2, 3, 4)
# a = 1, b = [2, 3], c = 4
```

### 변수 값 교환

```python
a, b = 10, 20
a, b = b, a
print(a, b)   # 20 10
```

---

## 두 점 사이의 거리 계산 (문제 2.2.9)

```python
import math

p1 = (x1, y1)
p2 = (x2, y2)

d = math.sqrt((x2 - x1)**2 + (y2 - y1)**2)
```

---

## 사전 (Dictionary)

### 개념

* 데이터를 **키(key) : 값(value)** 형태로 저장
* 키를 이용해 빠르게 값에 접근 가능

```python
student = {
    "name": "John Doe",
    "age": 21,
    "cell": "010-2222-3333"
}
```

### 기본 특징

* 키는 중복 불가
* 키는 변경 불가능한 자료형만 가능
* 값은 어떤 자료형이든 가능
* Python 3.7+부터 입력 순서 유지

### 사전 접근

```python
print(student["age"])   # 21
```

---

## 해시 (Hash)

* 데이터를 고정된 길이의 값으로 변환하는 과정
* 사전은 해시 기반으로 빠른 탐색 가능

```python
invalid_dict = {[1, 2, 3]: "123"}  # 오류
valid_dict = {(1, 2, 3): "ok"}
```

---

## 사전 키 확인

```python
filled_dict = {"one": 1, "two": 2, "three": 3}
list(filled_dict.keys())
```

---

## Iterable

* 반복 가능한 객체
* for문에서 사용 가능

### 대표 예시

* 문자열: "hello"
* 리스트: [1, 2, 3]
* 튜플: (1, 2, 3)

---

## ✨ 마무리

이번 정리를 통해 Python의 기본 자료구조인 튜플과 사전을 이해하고,
불변성과 해시 구조의 개념을 익힐 수 있었습니다.

앞으로는 실제 문제 풀이와 프로젝트에 적극 활용할 예정입니다.


## python-basic

### 📌 목적

간단한 알고리즘 문제 풀이를 통해 **문제를 분석하고 해결하는 사고력**을 기르는 것을 목표로 합니다.
특히 이 문서에서는 **연산자(산술 연산문)** 를 중심으로 문제를 구성하여,
파이썬 기본 문법이 실제 계산 로직에 어떻게 사용되는지를 이해하는 데 중점을 둡니다.

각 문제는 풀이 과정을 단계적으로 정리하고,
코드에는 주석을 통해 사고 과정을 설명했습니다.

---

### 문제 1. 두 개의 정수를 입력받아 사칙연산 결과를 출력하시오

#### 풀이 과정

1. 두 개의 정수를 입력받는다.
2. 덧셈, 뺄셈, 곱셈, 나눗셈을 각각 계산한다.
3. 계산 결과를 순서대로 출력한다.

```python
a, b = map(int, input().split())

print(a + b)   # 덧셈
print(a - b)   # 뺄셈
print(a * b)   # 곱셈
print(a // b)  # 나눗셈(몫)
```

#### 학습 포인트

* 산술 연산자 (`+`, `-`, `*`, `//`) 이해
* 다중 입력 처리 (`map`, `split`)
* 연산 결과 출력 흐름 파악

---

### 문제 2. 세 개의 정수의 평균을 구하시오

#### 풀이 과정

1. 세 개의 정수를 입력받는다.
2. 세 수의 합을 계산한다.
3. 합을 3으로 나누어 평균을 구한다.

```python
a, b, c = map(int, input().split())

average = (a + b + c) / 3
print(average)
```

#### 학습 포인트

* 덧셈과 나눗셈 연산 결합
* 실수 결과 처리
* 계산식 변수 저장

---

### 문제 3. 정수 하나를 입력받아 제곱 값을 출력하시오

#### 풀이 과정

1. 정수를 하나 입력받는다.
2. 자기 자신과 곱하여 제곱 값을 계산한다.
3. 결과를 출력한다.

```python
n = int(input())

print(n * n)
```

#### 학습 포인트

* 곱셈 연산 활용
* 간단한 수학 연산의 알고리즘화

---

## 🤖 Mini Projects

### 📁 robot-action-decider

```
mini-projects
└─ robot-action-decider
   ├─ action_decider.py
   └─ README.md
```

---

### 로봇 행동 결정 프로그램

#### 프로젝트 개요

로봇이 **장애물과의 거리**와 **배터리 잔량**을 입력받아,
현재 상황에 따라 적절한 행동을 결정하도록 만든 간단한 제어 프로그램입니다.

---

#### 구현 코드

```python
distance = int(input("장애물과의 거리(cm): "))
battery = int(input("배터리 잔량(%): "))

if distance < 20:
    print("정지")
elif battery < 30:
    print("충전 필요")
else:
    print("전진")
```

---

#### 사용 기술

* Python

---

#### 구현 기능

* 거리 값 입력
* 배터리 상태 확인
* 조건에 따른 로봇 행동 판단

---

#### 배운 점

* 연산 결과를 조건 판단에 활용하는 방법을 이해함
* 여러 조건을 고려한 로직 설계 경험
* 로봇 제어의 기본적인 판단 구조 습득

---

#### 향후 개선

* 실제 거리 센서 및 배터리 센서 값과 연동
* Arduino 기반 로봇 제어 프로그램으로 확장

---

## ✨ 마무리

이 저장소는 **연산문 중심의 파이썬 기초 문법**,
**알고리즘 사고력**, **로봇 제어 논리**를 함께 성장시킨 학습 기록입니다.

앞으로 조건문·반복문과 결합된 더 복잡한 계산 문제와
실제 하드웨어 제어 프로젝트로 확장할 계획입니다.


# python-basic

## 목적

프로그램 실행 중 발생할 수 있는 오류 상황을 이해하고,
Python의 예외 처리와 파일/JSON 처리 방법을 학습하기 위해
기본 개념과 예제를 정리한 학습 기록입니다.

예외(Exception)를 통해 프로그램이 중단되지 않도록 처리하고,
with 문을 사용해 자원을 안전하게 관리하는 것을 목표로 했습니다.

---

# ✅ Chapter 3. 기본 문법

## 3. 제어 흐름 (Control Flow and Iterables)

# 🧠 3.7. 예외(Exception) 처리

프로그램을 개발하다 보면 문법적으로는 완벽하지만,
실행 중 **예상치 못한 상황**(잘못된 입력, 네트워크 오류, 파일 부재 등)으로 인해
프로그램이 중단되는 경우가 발생합니다.

이러한 상황을 **예외(Exception)** 라고 하며,
이를 안전하게 처리하는 작업을 **예외 처리(Exception Handling)** 라고 합니다.

---

## ✅ 1/7 예외 처리 기본 개념

예를 들어 로그인 과정에서 서버 응답이 없다면 다음과 같은 고민이 필요합니다.

* 얼마나 기다려야 하는가?
* 사용자에게 무엇을 안내해야 하는가?
* 프로그램을 종료할 것인가, 다시 시도할 것인가?

이처럼 **비정상 상황에 대비하는 로직**이 바로 예외 처리입니다.

---

## 3.7.1 예외(Exception)란?

예외란 프로그램 실행 중 정상적인 흐름을 방해하는 사건입니다.

* 예외 처리를 하지 않으면 → 프로그램 즉시 종료 (Crash)
* 예외 처리를 하면 → 오류를 우아하게 처리하거나 복구 가능

---

## 3.7.2 Python 예외 처리 기본 문법

```python
try:
    # 실행하고 싶은 코드 (에러 가능 구간)
except 예외종류:
    # 예외 발생 시 실행 코드
else:
    # 예외가 발생하지 않았을 때 실행 (선택)
finally:
    # 예외 발생 여부와 관계없이 항상 실행 (선택)
```

---

## ✅ 2/7 예외 처리 예제 + raise

```python
try:
    raise IndexError("this is an index error")
except IndexError as e:
    pass
except (TypeError, NameError):
    pass
else:
    print("All good!")
finally:
    print("We can clean up resources here")
```

### 🔹 raise

* 의도적으로 예외를 발생시킬 때 사용

### 🔹 as e 의미

* 발생한 예외 객체를 변수(e)에 저장
* e 대신 err, error 등 다른 이름 사용 가능

---

## ✅ 3/7 IndexError 예시 + 예외 카테고리

```python
lockers = ["노트북", "책", "우산"]

try:
    item = lockers[5]
except IndexError as e:
    print("⚠️ 문제가 발생했습니다!")
    print(f"에러 메시지 내용: {e}")
```

출력 결과:

```
⚠️ 문제가 발생했습니다!
에러 메시지 내용: list index out of range
```

> `as e`를 사용하지 않으면 상세 에러 메시지를 확인할 수 없음

---

### 📌 주요 예외 카테고리

| 카테고리 | 예외 이름             | 발생 상황          |
| ---- | ----------------- | -------------- |
| 값/타입 | TypeError         | 잘못된 타입 연산      |
| 값/타입 | ValueError        | 타입은 맞으나 값이 부적절 |
| 참조   | NameError         | 변수 이름 없음       |
| 참조   | AttributeError    | 객체에 없는 속성 호출   |
| 인덱스  | IndexError        | 범위 초과 접근       |
| 인덱스  | KeyError          | 딕셔너리 키 없음      |
| 입출력  | FileNotFoundError | 파일 없음          |
| 입출력  | PermissionError   | 파일 권한 없음       |

---

## ✅ 4/7 파일 처리 기본 방식 vs with

### 일반적인 파일 처리 방식

```python
f = open("data.txt")
try:
    content = f.read()
finally:
    f.close()
```

⚠️ close()를 깜빡하기 쉬움

---

### with 사용 (권장)

```python
with open("myfile.txt") as f:
    for line in f:
        print(line)
```

#### 특징

* 블록 종료 시 자동 close()
* 오류 발생해도 안전하게 종료

---

## ✅ 5/7 추가 예외 + 0으로 나누기

### 주요 예외 추가

| 카테고리 | 예외 이름               | 발생 상황     |
| ---- | ------------------- | --------- |
| 수학   | ZeroDivisionError   | 0으로 나누기   |
| 수학   | OverflowError       | 너무 큰 수    |
| 모듈   | ImportError         | import 실패 |
| 모듈   | ModuleNotFoundError | 모듈 없음     |

### Practice: 0으로 나누기 처리

```python
try:
    m, n = map(int, input().split())
    print(f"{m} / {n} = {m / n}")
except ZeroDivisionError:
    print("0으로 나눌 수 없습니다.")
```

---

## 3.7.3 with 문장과 자원 관리

자원(Resource)이란 운영체제가 관리하는 데이터입니다.

* 파일
* 데이터베이스
* 네트워크

`with` 문은 자원을 **자동으로 정리(cleanup)** 해줍니다.

---

## ✅ 6/7 JSON 타입과 파일 읽기

### JSON ↔ Python 타입

| JSON         | Python       |
| ------------ | ------------ |
| string       | str          |
| number       | int / float  |
| true / false | True / False |
| null         | None         |

```python
with open("myfile2.txt", "r") as file:
    contents = json.load(file)
    print(contents)
```

---

## ✅ 7/7 with로 파일 쓰기 + JSON

```python
contents = {"aa": 12, "bb": 21}

with open("myfile1.txt", "w") as file:
    file.write(str(contents))

import json
with open("myfile2.txt", "w") as file:
    file.write(json.dumps(contents))
```

### 💡 JSON이란?

JSON(JavaScript Object Notation)은
사람과 컴퓨터 모두 읽기 쉬운 데이터 표현 형식입니다.

```json
{
  "name": "Sungyong",
  "age": 15,
  "likes": ["game", "coding"]
}
```

### JSON → Python 변환 규칙

| JSON      | Python |
| --------- | ------ |
| object {} | dict   |
| array []  | list   |

---

## ✨ 마무리

이 문서는 **파이썬 예외 처리의 핵심 개념부터 파일·JSON 처리까지**를 정리한 학습 기록입니다.

안정적인 프로그램을 만들기 위한 기반 문법으로,
향후 로봇 제어, 서버 통신, 데이터 처리 프로젝트로 확장할 수 있습니다.



# 4. 함수 (Functions)

함수는 **특정 작업을 수행하는 코드 묶음**입니다.
필요할 때마다 호출해서 사용할 수 있으며, 입력값을 받아 **결과를 반환**할 수도 있습니다.

함수를 사용하면 코드의 재사용성과 가독성이 높아지고, 유지보수가 쉬워집니다.

---

## 4.1 함수의 기본 구조

```python
def 함수이름(매개변수):
    실행할 코드
    return 결과
```

### 구성 요소 설명

* **def** : 함수를 정의하는 키워드
* **함수이름** : 함수의 역할을 나타내는 이름

  * 예: `calculate_area`, `say_hello`
* **매개변수(parameter)** : 함수에 전달되는 입력값 (없을 수도 있음)
* **return** : 함수 실행 결과를 반환 (생략 가능)

---

## 4.2 함수의 핵심 요소

### 1️⃣ 입력값이 있는 함수

외부에서 값을 받아 처리하는 가장 일반적인 형태

```python
def add(a, b):
    return a + b

result = add(3, 5)   # 8
```

---

### 2️⃣ 결과값이 없는 함수 (return 생략)

작업만 수행하고 값을 반환하지 않는 함수

```python
def greet(name):
    print(f"안녕하세요, {name}님!")

greet("지민")
# 반환값은 None
```

---

### 3️⃣ 기본 매개변수 (Default Parameters)

매개변수가 전달되지 않았을 때 사용할 기본값 지정

```python
def power(n, p=2):
    return n ** p

print(power(5))      # 25
print(power(5, 3))   # 125
```

---

## 4.3 함수를 사용하는 이유 (장점)

* **재사용성** : 한 번 만든 함수를 여러 번 호출 가능
* **가독성** : 기능별 분리로 코드가 깔끔해짐
* **유지보수** : 문제 발생 시 해당 함수만 수정

---

## 4.4 람다(Lambda) 함수

람다 함수는 **이름 없이 한 줄로 정의하는 간단한 함수(익명 함수)** 입니다.

```python
# 일반 함수
def add(a, b):
    return a + b

# 람다 함수
add_lambda = lambda a, b: a + b

print(add_lambda(10, 20))   # 30
```

---

## 4.5 가변 매개변수 (*args)

### 1️⃣ 여러 개의 인수를 받는 함수

```python
def varargs(*args):
    return args

varargs(1, 2, 3)   # (1, 2, 3)
```

* `*args`는 전달된 값을 **튜플(tuple)** 로 저장
* 위치 인자만 받음
* 관례적으로 이름을 `args`로 사용

```python
def total(*args):
    return sum(args)

print(total(1, 2, 3, 4))   # 10
```

---

## 4.6 지역 변수와 전역 변수

### 지역 변수 (Local Variable)

* 함수 내부에서 선언
* 함수 종료 시 소멸

### 전역 변수 (Global Variable)

* 함수 외부에서 선언
* 프로그램 전체에서 사용 가능

```python
x = 5   # 전역 변수

def set_x(num):
    x = num      # 지역 변수
    print(x)

def set_global_x(num):
    global x
    print(x)
    x = num
    print(x)

set_x(43)
set_global_x(6)
```

출력 결과:

```
43
5
6
```

---

## 4.7 위치 매개변수와 키워드 매개변수

### 위치 매개변수

```python
add(5, 6)
```

### 키워드 매개변수

```python
add(y=6, x=5)
```

---

## 4.8 키워드 가변 인수 (**kwargs)

```python
def func(*args, **kwargs):
    print(args)
    print(kwargs)

func(1, 2, name="John", age=30)
```

출력:

```
(1, 2)
{'name': 'John', 'age': 30}
```

```python
def keyword_args(**kwargs):
    return kwargs

keyword_args(big="foot", loch="ness")
```

---

## 4.9 Practice

### Practice 4.1 두 점 사이의 거리

```python
import math

def distance(x1, y1, x2, y2):
    return round(math.sqrt((x2 - x1)**2 + (y2 - y1)**2), 2)
```

---

### Practice 4.2 제곱의 합

```python
def s(m, n):
    return sum(i**2 for i in range(m, n + 1))
```

---

### Practice 4.3 평균 계산 함수

```python
def avg(*args):
    return sum(args) / len(args)
```

---

### Practice 4.4 중복 제거 함수

```python
def deduplicate(*args):
    return sorted(set(args))
```

예시:

```python
deduplicate('a','b','c','d','a','e','b')
# ['a', 'b', 'c', 'd', 'e']

deduplicate(10,21,32,44,11,21,43,21)
# [10, 11, 21, 32, 43, 44]
```

---

## ✨ 마무리

이 문서는 **파이썬 함수의 개념부터 실전 활용까지** 정리한 학습 기록입니다.

기초 문법을 바탕으로 알고리즘 문제 해결과
로봇 제어, 데이터 처리 프로그램으로 확장할 수 있는 핵심 개념을 담고 있습니다.


# 🐍 Python Functional Programming & Scope Portfolio

> **주제**: 클로저 · 람다 함수 · 고차 함수 · 일급 함수 · 가변 인자
>
> Python 함수형 프로그래밍 핵심 개념을 **이론 + 예제 + 실습** 형태로 정리한 깃허브 포트폴리오 문서입니다.

---

## ① 클로저 (Closure)

### 💡 Tip | 클로저란?

**클로저(Closure)**란

> *함수가 자신이 생성될 당시의 외부 스코프 변수 값을 기억하고 유지하는 기능*

즉,

> **함수 + 그 함수가 참조하는 외부 변수 환경**의 조합이다.

### ✅ 클로저 성립 조건 (3가지)

1. 함수가 **다른 함수 내부(nested function)** 에서 정의되어야 함
2. 내부 함수가 **외부 함수의 변수**를 사용해야 함
3. 외부 함수가 **내부 함수를 반환**해야 함

➡ 클로저를 사용하면 **상태를 기억하는 함수**를 만들 수 있다.

---

## ② 람다 함수 (Lambda Function)

### 📌 개념

람다 함수는 `lambda` 키워드를 사용하는 **익명 함수**이다.

```python
(lambda x: x > 2)(3)                # True
(lambda x, y: x**2 + y**2)(2, 1)    # 5
```

```python
square = lambda x: x * x
```

### ⭐ 람다 함수의 장점

1. 코드가 매우 간결해짐
2. **일회성 함수**에 적합
3. 함수를 인자로 전달할 때 편리
4. 불필요한 `def` 제거 → 가독성 향상
5. 클로저와 결합 가능

```python
sorted(data, key=lambda x: x.age)
list(map(lambda x: x + 1, [1, 2, 3]))
```

---

## ③ 내장 고차 함수 (Built-in Higher Order Functions)

### 📌 고차 함수란?

* 함수를 **매개변수로 받거나**
* 함수를 **반환하는 함수**

---
### 1️⃣ map(function, iterable)

```python
numbers = [1, 2, 3]
result = list(map(lambda x: x * 2, numbers))
# [2, 4, 6]
```

```python
list(map(add_10, [1, 2, 3]))
list(map(max, [1, 2, 3], [4, 2, 1]))
```

---

## ④ 일급 함수 (First-Class Function)

### 📌 정의

함수를 **값(value)** 처럼 다룰 수 있는 특성

### ✅ 특징 4가지

#### 1. 변수에 저장 가능

```python
def add(a, b):
    return a + b

f = add
f(3, 4)
```

#### 2. 함수의 인자로 전달 가능

```python
def apply(func, x, y):
    return func(x, y)
```

#### 3. 함수 반환 가능

```python
def make_adder(n):
    def adder(x):
        return x + n
    return adder
```

#### 4. 자료구조에 저장 가능

```python
funcs = [add, lambda x, y: x * y]
```

---

## ⑤ 부분 평가된 함수 (Partial Evaluation)

```python
def create_adder(x):
    def adder(y):
        return x + y
    return adder

add_10 = create_adder(10)
add_10(3)  # 13
```

➡ `add_10` 은 이미 `x=10` 이 평가된 함수

---

## ⑥ nonlocal 을 활용한 클로저

```python
def create_avg():
    total = 0
    count = 0

    def avg(n):
        nonlocal total, count
        total += n
        count += 1
        return total / count

    return avg
```

---

## ⑦ 다중 값 반환 (Tuple Packing)

```python
def swap(x, y):
    return y, x

x, y = swap(1, 2)
```

---

## ⑧ 전역 영역 (Global Scope)

```python
x = 5

def set_x(num):
    x = num
    print(x)

def set_global_x(num):
    global x
    print(x)
    x = num
    print(x)
```

---

## ⑨ **kwargs (키워드 인자)

```python
def func(*args, **kwargs):
    print(args)
    print(kwargs)
```

```python
func(1, 2, name="John", age=30)
```

---

## ⑩ Practice 4.3 | 평균 계산 함수

```python
def avg(*args):
    return sum(args) / len(args)
```

---

## ⑪ Practice 4.4 | 중복 제거 함수

```python
def deduplicate(*args):
    return sorted(set(args))
```

---

## ⑫ 가변 매개변수 (*args)

```python
def total(*args):
    return sum(args)
```

---

---

### ✨ 마무리

이 문서는 파이썬 함수의 개념부터 실전 활용까지를 정리한 학습 기록입니다.

기초 문법을 바탕으로  
클로저, 람다 함수, 고차 함수, 가변 인자 등 **파이썬의 핵심 함수 개념**을 이해하고  
이를 알고리즘 문제 해결, 로봇 제어 로직, 데이터 처리 프로그램으로  
확장할 수 있도록 정리하는 것을 목표로 했습니다.

앞으로는 이 개념들을 실제 프로젝트와 문제 풀이에 적용하며  
더 효율적이고 구조적인 코드를 작성해 나갈 예정입니다.



# python-basic

## 목적

파이썬에서 **함수를 값처럼 다루는 방식**을 이해하고,  
내장 고차 함수(map, filter, reduce, sorted 등)를 활용하여  
반복문을 줄이고 **가독성과 효율성이 높은 코드**를 작성하는 것을 목표로 합니다.

함수를 매개변수로 전달하거나 반환하는 개념을 익혀  
함수형 프로그래밍 스타일의 기초를 다집니다.


## 🔁 내장 고차 함수 (Built-in Higher Order Functions)

### 📌 고차 함수란?

고차 함수(Higher-Order Function)란  
**함수를 매개변수로 받거나, 함수를 반환하는 함수**를 의미합니다.

파이썬에서는 `map`, `filter`, `reduce`, `sorted` 등이  
대표적인 내장 고차 함수입니다.

---

## ✅ 1/5 고차 함수(Higher-Order Function)란?

고차 함수(Higher-Order Function)란  
**함수를 매개변수로 받거나, 함수를 반환하는 함수**를 의미합니다.

파이썬에서는 다음과 같은 함수들이  
대표적인 내장 고차 함수입니다.

- `map`
- `filter`
- `reduce`
- `sorted`
- `max`
- `min`

---

---

## ✅ 2/5 map(function, iterable)

`map()` 함수는  
iterable의 각 요소에 함수를 적용하여  
**새로운 값을 생성하는 함수**입니다.

#### 여러 예제

```python
list(map(add_10, [1, 2, 3]))
# [11, 12, 13]

list(map(max, [1, 2, 3], [4, 2, 1]))
# [4, 2, 3]

---

## ✅ 3/5 filter(function, iterable) ― 수정본

```markdown
## ✅ 3/5 filter(function, iterable)

`filter()` 함수는  
조건을 만족하는 요소만 추출하는 함수입니다.

함수의 반환값이 `True`인 요소만 남고,  
`False`인 요소는 제거됩니다.

#### 예제

```python
numbers = [1, 2, 3, 4]
evens = list(filter(lambda x: x % 2 == 0, numbers))
# [2, 4]

---

## ✅ 4/5 reduce(function, iterable) ― 수정본

```markdown
## ✅ 4/5 reduce(function, iterable)

`reduce()` 함수는  
여러 값을 **누적 계산하여 하나의 값으로 축약**하는 함수입니다.

`functools` 모듈에서 제공됩니다.

#### 예제

```python
from functools import reduce

numbers = [1, 2, 3, 4]
total = reduce(lambda x, y: x + y, numbers)
# 10
동작 방식
처음에는 1과 2가 x, y로 전달됨

이후에는 이전 계산 결과와 다음 값이 반복적으로 전달됨


---

## ✅ 5/5 sorted / max / min (key 함수 활용) ― 수정본

```markdown
## ✅ 5/5 sorted / max / min (key 함수 활용)

#### sorted(iterable, key=func)

정렬 기준을 함수로 지정할 수 있는 정렬 함수입니다.

```python
words = ["apple", "kiwi", "banana"]
sorted(words, key=len)
# ['kiwi', 'apple', 'banana']
문자열의 길이가 짧은 것부터 정렬됩니다.

max(iterable, key=func) / min(iterable, key=func)
함수를 기준으로 최댓값 또는 최솟값을 찾는 함수입니다.

words = ["apple", "kiwi", "banana"]
max(words, key=len)
# 'banana'

```

---

---

### ✨ 마무리 | 내장 고차 함수

내장 고차 함수는 파이썬에서 함수를 값처럼 다루는 사고 방식을 가장 잘 보여주는 기능입니다.
map, filter, reduce, sorted, max, min 함수는
반복문을 줄이고 코드의 의도를 명확하게 표현할 수 있도록 도와줍니다.

이 개념을 이해함으로써
데이터를 한 단계씩 가공하는 함수형 프로그래밍 스타일을 익힐 수 있으며,
알고리즘 문제 풀이, 데이터 처리, 로봇 제어 로직과 같은 실제 문제에서도
더 간결하고 효율적인 코드를 작성할 수 있습니다.

앞으로는 상황에 맞는 고차 함수를 선택하여
가독성과 유지보수성이 높은 파이썬 코드를 작성하는 것을 목표로 합니다.

---

# 🐍 python-basic

> Python 기초 문법 정리 프로젝트  
> Seoul Robot High School - Grade 1  

---

## 📌 프로젝트 목적

파이썬의 **기본 문법(입출력, 형변환, 연산자, 조건문, 반복문)**을 이해하고  
기초적인 문제 해결 능력을 기르는 것을 목표로 합니다.

정수, 실수, 문자열 입력 처리와  
논리 연산 및 조건 판단을 연습하여  
프로그래밍의 핵심 사고력을 기릅니다.

---

# 📘 BASIC Syntax Review

---

## ✅ Question 01. 시분초 입력받아 분만 출력하기

### 📌 문제 설명
시, 분, 초가 `"HH:MM:SS"` 형식으로 입력된다.  
입력값에서 **분(MM)**만 추출하여 출력하시오.

### 💻 해결 코드
```python
time = input()
print(time.split(":")[1])

---

## ✅ Question 02. 정수 1개 입력받아 부호 바꾸기

### 📌 문제 설명
정수 1개를 입력받아  
그 수의 **부호를 반대로 바꾸어 출력**하시오.

예를 들어:
- 입력이 `5`이면 → 출력은 `-5`
- 입력이 `-3`이면 → 출력은 `3`

### 💻 해결 코드
```python
n = int(input())
print(-n)

---

## ✅ Question 03. 문자 1개 입력받아 다음 문자 출력하기

### 📌 문제 설명
문자 1개를 입력받아  
**아스키(ASCII) 코드 기준으로 다음 문자**를 출력하시오.

예를 들어:
- 입력이 `A`이면 → 출력은 `B`
- 입력이 `a`이면 → 출력은 `b`
- 입력이 `0`이면 → 출력은 `1`

---

### 💻 해결 코드
```python
ch = input()
print(chr(ord(ch) + 1))

---

## ✅ Question 04. 단어 여러 번 출력하기

### 📌 문제 설명
단어 1개와 정수 1개를 입력받아  
해당 단어를 **입력받은 횟수만큼 반복 출력**하시오.

예를 들어:
- 입력 → `hello 3`  
- 출력 → `hellohellohello`

---

### 💻 해결 코드
```python
word, n = input().split()
print(word * int(n))

---

## ✅ Question 05. 실수 2개 입력받아 거듭제곱 계산하기

### 📌 문제 설명
실수 2개를 입력받아  
첫 번째 수를 두 번째 수만큼 **거듭제곱하여 출력**하시오.

예를 들어:
- 입력 → `2.0 3.0`  
- 출력 → `8.0`

- 입력 → `4.0 0.5`  
- 출력 → `2.0`

---

### 💻 해결 코드
```python
f1, f2 = map(float, input().split())
print(f1 ** f2)

---

## ✅ Question 06. 실수 1개 입력받아 소수점 이하 자리 변환하기

### 📌 문제 설명
실수 1개를 입력받아  
소수점 이하 **둘째 자리까지 출력**하시오.

예를 들어:
- 입력 → `3.14159`  
- 출력 → `3.14`

- 입력 → `2`  
- 출력 → `2.00`

---

### 💻 해결 코드
```python
f = float(input())
print(f"{f:.2f}")

---

## ✅ Question 07. 2의 거듭제곱 배로 곱해 출력하기

### 📌 문제 설명
정수 a와 b를 입력받아  
a에 **2의 b제곱을 곱한 값**을 출력하시오.

즉, 다음 식을 계산하시오:

a × (2^b)

예를 들어:
- 입력 → `3 2`  
- 출력 → `12`  
  (3 × 2² = 3 × 4 = 12)

- 입력 → `5 3`  
- 출력 → `40`  
  (5 × 2³ = 5 × 8 = 40)

---

### 💻 해결 코드
```python
a, b = map(int, input().split())
print(a * (2 ** b))

---

## ✅ Question 08. 정수 입력받아 참 거짓 평가하기

### 📌 문제 설명
정수 1개를 입력받아  
해당 값이 **True 또는 False**인지 출력하시오.

- `0`은 → `False`
- `0이 아닌 값`은 → `True`

예를 들어:
- 입력 → `0`  
- 출력 → `False`

- 입력 → `5`  
- 출력 → `True`

- 입력 → `-3`  
- 출력 → `True`

---

### 💻 해결 코드
```python
n = int(input())
print(bool(n))

---

## ✅ Question 09. 참 거짓 바꾸기

### 📌 문제 설명
정수 1개를 입력받아  
그 값의 **논리값을 반대로 출력**하시오.

- 입력값이 0이면 → False → True 출력  
- 입력값이 0이 아니면 → True → False 출력  

예를 들어:
- 입력 → `0`  
- 출력 → `True`

- 입력 → `5`  
- 출력 → `False`

- 입력 → `-10`  
- 출력 → `False`

---

### 💻 해결 코드
```python
n = int(input())
print(not bool(n))

---

## ✅ Question 10. 둘 다 참일 경우만 참 출력하기

### 📌 문제 설명
정수 2개를 입력받아  
두 값이 모두 **참(True)**일 경우에만 True를 출력하시오.

- 두 값이 모두 0이 아닐 때 → True  
- 하나라도 0이면 → False  

예를 들어:
- 입력 → `3 5`  
- 출력 → `True`

- 입력 → `0 5`  
- 출력 → `False`

- 입력 → `0 0`  
- 출력 → `False`

---

### 💻 해결 코드
```python
a, b = map(int, input().split())
print(bool(a) and bool(b))

---

## ✅ Question 11. 하나라도 참이면 참 출력하기

### 📌 문제 설명
정수 2개를 입력받아  
둘 중 하나라도 **참(True)**이면 True를 출력하시오.

- 둘 중 하나라도 0이 아니면 → True  
- 둘 다 0일 때만 → False  

예를 들어:
- 입력 → `3 0`  
- 출력 → `True`

- 입력 → `0 5`  
- 출력 → `True`

- 입력 → `0 0`  
- 출력 → `False`

---

### 💻 해결 코드
```python
a, b = map(int, input().split())
print(bool(a) or bool(b))

---

## ✅ Question 12. 서로 다를 때만 참 출력하기 (XOR)

### 📌 문제 설명
정수 2개를 입력받아  
두 값의 참/거짓이 **서로 다를 때만 True**를 출력하시오.

- 하나는 0이 아니고, 하나는 0일 때 → True  
- 둘 다 0이거나, 둘 다 0이 아닐 때 → False  

예를 들어:
- 입력 → `3 0`  
- 출력 → `True`

- 입력 → `0 5`  
- 출력 → `True`

- 입력 → `3 5`  
- 출력 → `False`

- 입력 → `0 0`  
- 출력 → `False`

---

### 💻 해결 코드
```python
a, b = map(int, input().split())
print(bool(a) != bool(b))

---

## ✅ Question 13. 서로 같을 때만 참 출력하기

### 📌 문제 설명
정수 2개를 입력받아  
두 값의 참/거짓이 **서로 같을 때만 True**를 출력하시오.

- 둘 다 0일 때 → True  
- 둘 다 0이 아닐 때 → True  
- 하나만 0일 때 → False  

예를 들어:
- 입력 → `3 5`  
- 출력 → `True`

- 입력 → `0 0`  
- 출력 → `True`

- 입력 → `3 0`  
- 출력 → `False`

- 입력 → `0 7`  
- 출력 → `False`

---

### 💻 해결 코드
```python
a, b = map(int, input().split())
print(bool(a) == bool(b))

---

## ✅ Question 14. 둘 다 거짓일 경우만 참 출력하기

### 📌 문제 설명
정수 2개를 입력받아  
두 값이 모두 **False일 경우에만 True**를 출력하시오.

- 두 값이 모두 0일 때 → True  
- 하나라도 0이 아니면 → False  

예를 들어:
- 입력 → `0 0`  
- 출력 → `True`

- 입력 → `3 0`  
- 출력 → `False`

- 입력 → `0 5`  
- 출력 → `False`

- 입력 → `4 7`  
- 출력 → `False`

---

### 💻 해결 코드
```python
a, b = map(int, input().split())
print(not bool(a) and not bool(b))

---

## ✅ Question 15. n개의 정수를 입력받아 짝수만 출력하기

### 📌 문제 설명
여러 개의 정수를 입력받아  
그 중 **짝수만 출력**하시오.

예를 들어:
- 입력 → `1 2 3 4 5 6`  
- 출력 →  

2
4
6


---

### 💻 해결 코드
```python
numbers = list(map(int, input().split()))

for n in numbers:
    if n % 2 == 0:
        print(n)

---

## ✅ Question 16. 정수 3개 입력받아 짝/홀 출력하기

### 📌 문제 설명
정수 3개를 입력받아  
각 숫자가 **짝수이면 `"even"`**,  
**홀수이면 `"odd"`**를 출력하시오.

예를 들어:

- 입력 → `1 2 3`  
- 출력 →


odd
even
odd


- 입력 → `4 6 8`  
- 출력 →


even
even
even


---

### 💻 해결 코드
```python
numbers = list(map(int, input().split()))

for n in numbers:
    if n % 2 == 0:
        print("even")
    else:
        print("odd")

---

# ✨ 마무리 | Python BASIC 문법 정리

이번 16문항은 파이썬 기초 문법의 핵심 요소를 단계적으로 학습하기 위한 문제들이다.  
단순한 코드 작성이 아니라, **프로그래밍 사고력의 기초를 다지는 과정**이다.

---

## 📚 이번 프로젝트에서 다룬 핵심 개념

### 1️⃣ 입력과 출력 (Input & Output)

프로그램에서 사용자와 상호작용하기 위한 가장 기본적인 기능이다.

---

#### 📌 `input()`

- 사용자로부터 값을 입력받는 함수
- 기본적으로 문자열(str) 형태로 저장된다.

```python
name = input()
print(name)

입력 →

Python

출력 →

Python

💡 숫자를 입력받아 계산하려면 반드시 형변환이 필요하다.

num = int(input())
print(num + 10)

입력 →

5

출력 →

15

---

### 2️⃣ 형변환 (Type Casting)

형변환은 데이터의 자료형(Type)을 다른 형태로 바꾸는 과정이다.  
Python에서는 입력값이 기본적으로 문자열(str)이기 때문에  
계산을 위해서는 형변환이 필수이다.

---

#### 📌 `int()`

- 문자열 또는 실수를 정수형(int)으로 변환한다.

```python
num = int("10")
print(num + 5)

출력 →

15

---

### 3️⃣ 문자열 처리 (String Handling)

문자열은 Python에서 매우 자주 사용되는 자료형이다.  
입력 처리, 데이터 가공, 출력 formatting 등 거의 모든 영역에서 사용된다.

---

## 📌 `split()`

- 문자열을 특정 기준(기본값: 공백)으로 나누는 함수
- 결과는 리스트(List)로 반환된다.

```python
text = "apple banana orange"
words = text.split()
print(words)

출력 →

['apple', 'banana', 'orange']

---

### 4️⃣ 산술 연산 (Arithmetic Operators)

산술 연산은 숫자 데이터를 계산할 때 사용하는 기본 연산이다.  
프로그램에서 가장 많이 사용되는 핵심 연산 기능이다.

---

## 📌 기본 연산자

| 연산자 | 의미 | 예시 |
|--------|------|------|
| `+` | 덧셈 | 3 + 2 → 5 |
| `-` | 뺄셈 | 5 - 2 → 3 |
| `*` | 곱셈 | 4 * 3 → 12 |
| `/` | 나눗셈 | 5 / 2 → 2.5 |

### 🔹 예시 코드

```python
a = 5
b = 2

print(a + b)
print(a - b)
print(a * b)
print(a / b)

출력 →

7
3
10
2.5

---

### 5️⃣ 논리 연산 (Logical Operators)

논리 연산은 조건을 판단할 때 사용하는 연산이다.  
주로 `if`문과 함께 사용되며, 프로그램의 흐름을 제어하는 핵심 요소이다.

---

## 📌 `and` (논리 AND)

- 두 조건이 **모두 참(True)**일 때만 True

```python
print(True and True)
print(True and False)

출력 →

True
False

💡 두 조건이 모두 만족해야 실행되는 경우에 사용한다.

📌 or (논리 OR)

두 조건 중 **하나라도 참(True)**이면 True

print(True or False)
print(False or False)

출력 →

True
False

💡 여러 조건 중 하나만 만족해도 되는 경우에 사용한다.

📌 not (논리 NOT)

논리값을 반대로 뒤집는다.

print(not True)
print(not False)

출력 →

False
True

💡 조건을 반전시킬 때 사용한다.

📌 XOR 개념 (!= 활용)

두 값이 서로 다를 때만 True

Python에는 전용 XOR 키워드는 없지만,
!= 비교 연산을 이용해 구현할 수 있다.

print(True != False)
print(True != True)

출력 →

True
False
📌 논리값 비교 (==)

두 값이 같으면 True, 다르면 False

print(True == True)
print(True == False)

출력 →

True
False

---

### 6️⃣ 조건문 (Conditional Statement)

조건문은 특정 조건이 참(True)인지 거짓(False)인지에 따라  
실행 흐름을 나누는 구조이다.

---

## 📌 기본 문법

```python
if 조건:
    실행문
else:
    실행문

if → 조건이 참일 때 실행

else → 조건이 거짓일 때 실행

: → 코드 블록 시작

들여쓰기 → 실행 범위 구분 (매우 중요)

📌 예시 1: 짝수 / 홀수 판별
num = int(input())

if num % 2 == 0:
    print("even")
else:
    print("odd")

입력 →

4

출력 →

even
📌 elif 사용하기 (여러 조건 처리)
score = int(input())

if score >= 90:
    print("A")
elif score >= 80:
    print("B")
else:
    print("C")

elif → 여러 조건을 순차적으로 검사할 때 사용

---

### 7️⃣ 반복문 (for)

반복문은 여러 데이터를 순차적으로 처리할 때 사용하는 구조이다.  
같은 동작을 여러 번 실행해야 할 때 사용된다.

---

## 📌 기본 문법

```python
for 변수 in 리스트:
    실행문

for → 반복 시작

변수 → 리스트에서 하나씩 꺼내 저장하는 공간

in → 반복 대상 지정

리스트 → 반복할 데이터 묶음

: → 코드 블록 시작

들여쓰기 → 반복 실행 영역

📌 예시 1: 리스트 출력하기
numbers = [1, 2, 3]

for n in numbers:
    print(n)

출력 →

1
2
3
📌 예시 2: 문자열 반복 처리
for ch in "robot":
    print(ch)

출력 →

r
o
b
o
t
📌 예시 3: 조건문과 함께 사용하기
numbers = [1, 2, 3, 4]

for n in numbers:
    if n % 2 == 0:
        print("even")

출력 →

even
even

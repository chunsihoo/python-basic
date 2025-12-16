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

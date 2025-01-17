---
layout: single
title:  "Jump to Python 01"
typora-root-url: ../
---

이지스 퍼블리싱의 Do it! 점프 투 파이썬 정리

# 01. 파이썬이란 무엇인가?

## 01-1 파이썬이란?

1990년 귀도 반 로섬이 개발한 인터프리터 언어

## 01-2 파이썬의 특징

1. 인간다운 언어이다.
2. 문법이 쉽다.
3. 무료이지만 강력하다.
4. 간결하다.
5. 프로그래밍을 즐기게 해준다.
6. 개발속도가 빠르다. 

> “Life is too short, You need python”
> 

## 01-3 파이썬으로 무엇을 할 수 있을까?

### 파이썬으로 할 수 있는일

1. 웹프로그래밍
2. 인공지능과 머신러닝 -사이킷런, 텐서플로, 파이토치, 케라스
3. 수치 연산 프로그래밍 -넘파이
4. 데이터 분석 -넘파이, 판다스, 맷플롯립
5. 데이터베이스 프로그래밍 -사이베이스, 인포믹스, 오라클, 마이에스큐엘, 포스트그레스큐엘, 피클
6. 시스템 유틸리티 제작
7. GUI 프로그래밍 -티케이인터
8. C/C++와 결합하기
9. 사물 인터넷 -라즈베리파이

### 파이썬으로 할 수 없는 일

1. 시스템과 밀접한 프로그래밍 영역
2. 모바일 프로그래밍

## 01-4 파이썬 설치하기

## 01-5 파이썬 둘러보기

![img1](/images/2023-12-04-Jump-to-Python01/img1.png)[파이썬 대화형 인터프리터] 사용자가 입력한 소스코드를 실행하는 환경

종료 Ctrl + z, quit(), exit() or sys모듈을 사용할 수 있다.

### 파이썬 기초 문법 따라 해보기 (사칙연산)

```python
>>> 1 + 2
3
```

### 변수에 숫자 대입하고 계산하기

```python
>>> a = 1
>>> b = 2
>>> a + b
3
```

### 변수에 문자 대입하고 출력하기

```python
>>> a = “Python”
>>> print(a)
Python
```

### 조건문 if

```python
>>> a = 3
>>> if a > 1;
>>>    print("a는 1보다 큽니다.")
a는 1보다 큽니다.
```

### 반복문 for

```python
>>> for a in [1, 2, 3]:
>>>    print(a)
1
2
3
```

### 반복문 while

```python
>>> i = 0
>>> while i < 3:
>>>     i = i + 1
>>>     print(i)
1
2
3
```

### 함수

```python
>>> def add(a, b):
>>>     return a + b

>>> add (3, 4)
7
```

### 01-6 파이썬과 에디터

파이썬에서 #으로 시작하는 문장은 주석이다.

여러줄의 주석은 “”” (큰따옴표 세개)로 사용한다. ‘’’도 가능

에디터로는 vs code or pycharm 추천

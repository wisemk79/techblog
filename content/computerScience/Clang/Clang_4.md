---
title: "C언어 - 4강"
metaTitle: "C언어 - 4강"
metaDescription: "This is the meta description for this page"
---

## 연산자
- 임의의 자료에 대해 각종 연산을 수행하도록하는 기호

### 연산자의 종류

#### 산술연산자
- 피 연산자에 대해 사칙연산을 포함한 각종 산술연산을 수행하는 연산자

- 이항 연산자
   - +, -, *, / : 가/감/승/제를 계산
   - % : 나눗셈의 나머지를 계산
- 단항 연산자
   - - : 부호의 반전
   - ++: 1증가
   - --: 1감소

### 관계 연산자
- 피 연산자에 대한 대,소 관계를 비교하는 연산자

#### 종류
- ==: 같은가의 여부를 비교
- !=: 다른가의 여부를 비교
- > >= < <= : 대, 소 관계를 비교


### 논리 연산자
- 피연산자에 대해 논리 연산을 수행하는 연산자

#### 종류
- &&: 논리곱(AND): 양쪽 모두 참일때만 참
- ||: 논리합(OR): 양쪽 중 하나라도 참이면 참
- !: 논리부정(NOT): 오른쪽이면 참이면 거짓, 거짓이면 참

### 대입연산자
- 연산자의 오른쪽을 왼쪽에 대입하는데 사용

#### 종류
- = : 대입연산자
- += : a += 5 는 a = a + 5랑 같음
- -= : a -= 5 는 a = a - 5랑 같음
- *= : a *= 5 는 a = a * 5랑 같음
- /= : a /= 5 는 a = a / 5랑 같음
- %= : a %= 5 는 a = a % 5랑 같음
- |=
- ^=
- <<=
- >>=

### 조건연산자
- 주어진 조건의 만족 여부에 따라 지정된 수식을 수행하는 연산자
- 형식: (조건)? 수식1: 수식2

### 비트연산자
- 수치에 대해 bit 단위의 연산을 수행하는 연산자
- &
- |
- ^
- ~
- <<
- >>

### 기타 연산자
- sizeof():지정한 자료형, 수식, 변수가 차지하는 기억공간의 크기를 구함
- case(형변환): 지정한 자료형을 다른 자료형으로 강제적으로바꿈
- &: 주소 연산자로서 피연산자의 주소를 나타냄
- *: 내용 연산자로서 피연산자의 내용을 가져옴

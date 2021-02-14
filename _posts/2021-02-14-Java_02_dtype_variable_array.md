---
title: Java LiveStudy(2) - 자바 데이터 타입, 변수 그리고 배열
author: RGunny
date: 2021-02-14 18:00:00 +0900
updated: 2021-02-14 18:00:00 +0900
categories: [Java, liveStudy]
tags: [Java, liveStudy]
toc: false
---

# Java LiveStudy(2) - 자바 데이터 타입, 변수 그리고 배열

## Goal

> 자바의 프리미티브 타입, 변수 그리고 배열을 사용하는 방법을 익힙니다.

# 2.1 프리미티브 타입 종류와 값의 범위 그리고 기본 값

# 2.2 프리미티브 타입과 레퍼런스 타입

# 2.2.1 기본형(Primitive) Type이란?

- 8가지의 기본형 타입을 미리 제공하여 제공합니다.
  - boolean, byte, short, int, long, float, double, char
- 기본값이 있기 때문에 `Null이 존재하지 않습니다`.
- `실제 값`을 저장하는 공간으로 JVM의 Runtime Data Area 영역 중 `스택(Stack)` 메모리 영역에 저장됩니다.
- 컴파일 시점에 해당 메모리 크기를 초과하면 `out of range` 에러가 발생합니다.

# 2.2.2 참조형(Reference) Type이란?

- 기본형 타입을 제외한 타입들입니다.
- `객체`이기 때문에, 빈 객체를 의미하는 `Null이 존재`합니다.
- 값(객체)이 저장되어 있는 곳의 `주소 값`을 저장하는 공간으로 JVM의 Runtime Data Area 영역 중`힙(Heap)` 메모리 영역에 저장됩니다.

# 2.3 리터럴

# 2.4 변수 선언 및 초기화하는 방법

# 2.5 변수의 스코프와 라이프타임

# 2.6 타입 변환, 캐스팅 그리고 타입 프로모션

# 2.7 1차 및 2차 배열 선언하기

# 2.8 타입 추론, var

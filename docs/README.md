---
title: ReadMe
author: 이우택 (wootaik@changwon.ac.kr)  
date: 2020 04 01
---

## Architecture 설계와 Module 개발 방법 



## Prerequisite





## Example Project

* [EST_Module_Exercise.zip](https://drive.google.com/open?id=1lqG-vVjvRZo1ia-wUIrsnUuGds661ot6)





## ToC



**Part I** 모듈화 설계 및 구현 방법



* [객체지향 프로그래밍: 모듈화 프로그래밍이란?](./ModularProgramming.md)

    **[강의 영상]**

    * [객체지향 프로그래밍이란?](https://drive.google.com/file/d/1WJAGiKlqxzWe2TsnW8NSQY8y_lNfE7ik/preview)

    * [모듈화 설계 방법](https://drive.google.com/file/d/1OR9xyQEB8eNbtNHmGtTy9i8KALeAXLLf/preview)



* [모듈화를 위한 코드 템플릿](./ModuleCodeTemplate.md)

    **[강의 영상]**

    * [모듈화 구현 방법과 코드 템플릿](https://drive.google.com/file/d/11rVY1j5vhZt9zHR8E1VLFXA4SAGprZQY/preview)
    * [모듈 만들기 Exercise 설명](https://drive.google.com/file/d/1QYOnF08XWJvdkABWVE9Sf0g4pirsXp8O/preview)

    **[강의 실습 영상]**

    * [Integer 연산 관련 예제 설명](https://drive.google.com/file/d/1e6H5nBCv2Hr_9nlxSbGhaSilG7oD3L3M/preview)
    * [Integer 연산 라이브러리 모듈 만들기](https://drive.google.com/file/d/1Gdlr70y65__ydx5UpZb2CCx_o_fc99rI/preview)

    

* [헤더파일의 인클루드 구조](./Includes.md)

    

* [C 변수와 함수의 scope 와 life-time](ScopeLifeTime.md)

    **[강의 영상]**

    * [변수와 함수의 Scope와 Life-time]()
    * [변수와 관련된 좀 더 깊이있는 이야기]()

    **[강의 실습 영상]**

    * [Unity 간략 설명](https://drive.google.com/file/d/11w7y53zlyKFL466XA88T4Xuesxvpwp14/preview) 
    * [Hystersis 함수 설명과 모듈화 하기](https://drive.google.com/file/d/1nBxdQqpYLkiaClMd5ebEZ0ipYS9XPibe/preview)
    * [Ramp 함수 설명과 모듈화 하기](https://drive.google.com/file/d/1BAkADshPkg4o5BVYhVW0te5E7m1qa3Pk/preview)

    


* [라이브러리 예제](LibExample.md)

    * IntMath lib: C 라이브러리 예제 

        * 모듈화를 위한 코드 템플릿에서 설명)
    * `i16Abs()`, `i16Add()`,`i16AbsSat()`,  `i16AddSat()`
    
* UserLib : 기능 라이브러리 예제 
    
        * C 변수와 함수의 Scope 와 Life-time 에서 설명
    * `Hyst()`, `Ramp()`
    
* FltCtrl Lib
    
        * Demo: `fltIirFilter1()`,  `fltPiCtrlP()`,  `fltLut1D()`
    * Exercise: `fltMaFilter()`,  `fltPiCtrlR()`
    
    
    
    



[architecture]

* 소프트웨어 구조와 프래임워크

    * 1

* 마이크로컨트롤러용 소프트웨어의 구조적 특징
  
    * 2
    * Interrupt
    * Multi-thread
    * HAL
    
* 자료흐름 중심의 설계 방법

    * 3.3

* 함수, 프로시져, 그리고 태스크

    * 프로시져 설명 추가
    * 태스크 설명 추가

* 인터페이스와 트리거링

    * 4.4, 4.5

* 운영체계와 스케쥴링

    * [xmc multi-rate scheduler](https://xmctutorial.readthedocs.io/ko/latest/ProgSystemTimerScheduler/index.html)
* [aurix multiple infinite loops](https://aurixtutorial.readthedocs.io/ko/latest/MultipleInfiniteLoops/index.html)
    * 4.6

* **[example]** MoBeE
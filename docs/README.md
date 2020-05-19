---
title: ReadMe
author: 이우택 (wootaik@changwon.ac.kr)  
date: 2020 04 01
---

## Architecture 설계와 Module 개발 방법 



## Prerequisite

이 강좌는 C 언어에 대한 기본적인 이해와 활용 능력을 전제로 하고 있습니다.



기본 환경으로 Eclipse 와 MinGW를 사용하고 있습니다.

환경 설치와 관련해서는 다음의 링크를 참고하여 환경을 준비하여 주시기 바랍니다.

* [MinGW, Eclipse 의 설치와 활용](https://drive.google.com/open?id=1FkhYFFAEmGat5U7Kgm_GGp6buNXcvpAE)

    [강의 영상]

    *   [MngGW와 Eclipse 설치 및 확인](https://drive.google.com/file/d/14SHD8eoIiCZvUsSrb5ktnx6DXgHRYQKM/preview)
    * [Build, Debug & Execute in eclipse](https://drive.google.com/file/d/1_m_x13QxEMPcEFXvXC1crUasRlZ_fiPA/preview)



임베디드 프로그래밍을 할 때에 포인터와 구조체의 이해는 매우 중요합니다. 기초가 부족하다고 생각되시는 분은 다음의 강좌로 이해도를 높이시기 바랍니다.

* [Pointer Explained](https://drive.google.com/open?id=1cKt-nrCICur0RolgPjs3Vnoqht87TLCC)

    [강의 영상]

    *   [포인터 설명과 실습](https://drive.google.com/file/d/1SD4caT_NLkwG2wqNwux-GBdDW4dwzni2/preview)


* [Structure Explained](https://drive.google.com/open?id=1oL-zrpJo9GTqf-EiNhd8paEi6IkrKi-v)

    [강의 영상]

    *   [Structure Basics](https://drive.google.com/file/d/18W6ENEpPz5X-rA4iCAkLgZIH6goEMcFg/preview)
    *   [Coordinate Conversion Example](https://drive.google.com/file/d/18B8Skja7U-RaXfz3F6xayb7oO0HLz983/preview)
    *   [eclipse 에서 실습하기](https://drive.google.com/file/d/1BXBUFGQ6lefWss_g_PxaST56gI6CcHuk/preview)
    *   [Multiple file 로 프로그래밍하기](https://drive.google.com/file/d/1Rbf-45qO6XynkK2U5VySJ1r9r4-wuqzO/preview)



------



## Example Project

* [EST_Module_Exercise.zip](https://drive.google.com/open?id=1lqG-vVjvRZo1ia-wUIrsnUuGds661ot6)





## ToC



### **Part I** 모듈화 설계 및 구현 방법



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

	**[강의 영상]**

    * [Include 구조 설계 방법](https://drive.google.com/open?id=1-domEgxfBXBaHZnovtcVfTGlC3kO2-Jg)
    * [include 구조: MinGW32 C99  활용시](https://drive.google.com/open?id=1gE4JBr8AJUy6y6WT4skKjXE3aX6dkyXQ)

    

* [C 변수와 함수의 scope 와 life-time](ScopeLifeTime.md)

    **[강의 영상]**

    * [변수와 함수의 Scope와 Life-time](https://drive.google.com/open?id=1Y-L_W4hO0vLT9yQR3Q05qlEDkmSkV19g)

    * [변수와 관련된 좀 더 깊이있는 이야기](https://drive.google.com/open?id=171N17Bor3TZMEzyfJSEumDBqrUyH-oXL)

    **[강의 실습 영상]**

    * [Unity 간략 설명](https://drive.google.com/file/d/11w7y53zlyKFL466XA88T4Xuesxvpwp14/preview) 
    * [Hystersis 함수 설명과 모듈화 하기](https://drive.google.com/file/d/1nBxdQqpYLkiaClMd5ebEZ0ipYS9XPibe/preview)
    * [Ramp 함수 설명과 모듈화 하기](https://drive.google.com/file/d/1BAkADshPkg4o5BVYhVW0te5E7m1qa3Pk/preview)

    


* [라이브러리 예제](LibExample.md)

    * IntMath lib: C 라이브러리 예제 

        * 모듈화를 위한 코드 템플릿에서 설명
        * `i16Abs()`, `i16Add()`,`i16AbsSat()`,  `i16AddSat()`
        
    * UserLib : 기능 라이브러리 예제 
    
        * C 변수와 함수의 Scope 와 Life-time 에서 설명
    	* `Hyst()`, `Ramp()`
    
	* FltCtrl Lib
    
        * Demo: `fltIirFilter1()`,  `fltPiCtrlP()`,  `fltLut1D()`
    	* Exercise: `fltMaFilter()`,  `fltPiCtrlR()`
    
    
    
    



### PART II Embedded Control System을 위한 SW Architecture 설계

* [소프트웨어 구조와 프래임워크](./ArchFramework.md)  - 상위설계
  
    * 1
    * 모듈과 계층구조
    
* [마이크로컨트롤러용 소프트웨어의 구조적 특징](uControllerFeatures.md) - 하위설계, HAL과의 연결
  
  * 2
    
    * Interrupt
    
  * Time 관련
  
      * Multi-rate
      * time triggered
  
  * Memory 관련
  
      * volatile
      * const vs. #define
      * linker script
  
      
  
* [동작과 자료, 그리고 트리거](BehaviorDataTrigger.md) - 하위설계, App 설계

    * 인터페이스와 트리거링
        * 4.4, 4.5

* [운영체계와 스케쥴링](StaticSche.md) - OS Integration
  
    * 태스크 설명 추가, 태스크 다이어그램
    * [xmc multi-rate scheduler](https://xmctutorial.readthedocs.io/ko/latest/ProgSystemTimerScheduler/index.html)
    * [aurix multiple infinite loops](https://aurixtutorial.readthedocs.io/ko/latest/MultipleInfiniteLoops/index.html)
    * 4.6



* **[example]** MoBeE
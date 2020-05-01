---
title: Module 개발 방법
author: 이우택 (wootaik@changwon.ac.kr)  
date: 2020 04 01
---



# Module 개발 방법



* [객체지향 프로그래밍: 모듈화 프로그래밍이란?](./ModularProgramming.md)

    * [xmc The benefits of architecture & module](https://xmctutorial.readthedocs.io/ko/latest/ProgModuleMultipleFiles/index.html#the-benefits-of-architecture-module)

    

* [모듈화를 위한 코드 템플릿](./ModuleCodeTemplate.md)

    * [xmc module section](https://xmctutorial.readthedocs.io/ko/latest/ProgModuleMultipleFiles/index.html#module-section)

    

* [헤더파일의 인클루드 구조](./Includes.md)



* [C 변수와 함수의 scope 와 life-time](ScopeLifeTime.md)

    * [xmc Using multiple files in C](https://xmctutorial.readthedocs.io/ko/latest/ProgModuleMultipleFiles/index.html#using-multiple-files-in-cc)

    

* [라이브러리 예제](LibExample.md)

    * IntMath lib: Function w/o State

        * `i16Abs()`, `i16Add()`,`i16AbsSat()`,  `i16AddSat()`

    * UserLib : Functions w/ State

        * 함수로 구성된 것을 모듈로 만들기 - 정보 구분하기
        * `Hyst()`, `Ramp()`

    * FltCtrl Lib

        * Demo: `fltIirFilter1()`,  `fltPiCtrlP()`,  `fltLut1D()`
        * Exercise: `fltMaFilter()`,  `fltPiCtrlR()`



[예제 프로젝트] EST_Module_Exercise.zip
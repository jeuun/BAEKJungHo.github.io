---
title: "기능 단위 구현"
layout: post
category: PROJECT
tags: [Java, MySQL, JSP, Servlet]
excerpt: "기능 단위 구현의 중요성에 대해 배워 봅시다."
author: BAEKJungHo
---

* content
{:toc}

## 기능 단위 구현

  `FulfillmentService Project`를 진행하면서 기능 단위 구현의 중요성에 대해 배웠습니다.

  약 3주라는 기간동안 프로젝트를 진행하였는데 1주차때에는 설계만 하고, 2주차 때에는
  M,V,C를 각각 구현해서 합치자는 방식을 선택하여 진행했었습니다. 진행하다보니 문제점이
  같은 일을 두번하게 되는 현상이 발생하며, 합치는 과정에서 또 다시 코딩을 해야해서 너무 비효율적
  이었습니다.

  따라서 3주차때 `기능단위(Bottom-up)`로 하나하나씩 구현하는 방향으로 바꾸었으며, 개발 속도가
  엄청 상승했습니다. 처음에는 기능단위 구현을 왜 해야하는지 잘 몰랐었는데 제가 느낀 바로는 다음과 같습니다.

  - 자바는 객체지향프로그래밍(OOP) 방식이기 때문에 Bottom-up 방식으로 구현
    - Bottom-up : 작은 기능들을 하나씩 구현하고 그 기능들이 모여져서 하나의 프로그램이 되는 것
  - 개발 속도가 상승

  따라서 자바를 사용하여 코딩을 할 때에는 기능단위로 구현을 해야 한다는 것을 느꼈습니다.

  하지만 일반적으로 학원이나 혹은 학교에서 팀장, 팀원들간의 수준차가 심할 경우 어느 한 사람이
  대부분의 기능을 구현하게 될 수도 있으며, 설계부터 여러가지를 종합적으로 담당해야 할 수 있습니다.

  

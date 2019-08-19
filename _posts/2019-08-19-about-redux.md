---
title: "Redux를 이해해봅시다"
date: 2019-08-19 08:26:28 -0400
categories: react redux
---


>https://qiita.com/mpyw/items/a816c6380219b1d5a3bf?utm_campaign=popular_items&utm_medium=feed&utm_source=popular_items 를 참고하였습니다.


<h3>Redux란 무엇인가?</h3><br>

vue를 이용한 대형 프로젝트를 진행했고, vuex를 자유자재로 다룰 줄 알게되었기 때문에,

Redux도 아주 쉽게 이해할 수 있을 줄 알았다...

하지만 vue가 너무 쉬웠던 것.....

React의 길은 험난했다 


<h3>Redux의 기본 플로우</h3><br>
![reduxflow](https://user-images.githubusercontent.com/49894861/63241570-25b15000-c28f-11e9-8120-5754a1e922a5.png)

Redux의 기본 플로우는 vuex와 아주 유사하다

action, store, reducer 이 세가지 개념을 먼저 생각해보자.



<h4>Action</h4><br>
store에 바로 접근할 수 없고, action을 거쳐야만 store에 접근할 수 있다.

따라서 action은 store에 보내는 데이터 묶음, 이벤트 생성자 같은 역할을 한다.


<h4>Reducer</h4><br>

![reducer](https://user-images.githubusercontent.com/49894861/63242331-010aa780-c292-11e9-8ab6-ee139b45443d.png)

>액션은 무언가 일어난다는 사실을 기술하지만, 그 결과 애플리케이션의 상태가 어떻게 바뀌는지는 특정하지 않습니다. 이것은 리듀서가 할 일이죠.



<h4>Store</h4><br>

store는 상태들이 저장된다.




---
title: Unity Engine 보스 몹 구현 공부 - Posts
toc: true
categories:        
    - Unity
tags: 시작이다 Unity
date: 2024-11-04 13:59 +0900
---

### Unity에서 꼭 알아야하는것

#### 1. enum

C#에서 쓰이는 열거형 형식.  
열거형은 enum 키워드로 정의.    

**열거형이란?**  
이름이 지정된 상수 집합    

다음은 예시이다.  
<script src="https://gist.github.com/isruiix/c3da07e2b7a2e7ca34af16ceacc8b789.js"></script>


#### 2. 코루틴

Update문에 코드를 작성하면 특정 코드가 반복적으로 실행되는데, Update 아닌 곳에서도 필요한 경우가 있다.  
이럴때 필요한거다.  

1. **IEnumerator** 반환형으로 시작    
2. **yield return** 반드시 함수 내부에 존재    

예시.  
<script src="https://gist.github.com/isruiix/084d8c17a871d623fb034399a6c65328.js"></script>    

개인적으로 정리한 노트 느낌으로 운영되는 내 끄적 사이트이기에 자세한 내용은 다른 사이트로...ㅎㅎ  
[코루틴](https://coding-of-today.tistory.com/171)


#### 3. 추가 예정
ㅇㅅㅇ

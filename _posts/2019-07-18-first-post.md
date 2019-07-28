---
title: "MARK DOWN 문법 사용해보기"
date: 2019-07-18
categories: study git md
---

# MARKDOWN 작성법

    RAW로 보면 text editor에서는 어떻게 썼었는지 볼 수 있다!
    그냥 사용하면서 익혀 보자.
Tab을 2번 쓰면 위에 있는것 처럼 회색단락이 된다


## 1. 큰 제목 (문서 제목)

This is a H1
=============


## 2. 작은 제목 (문서 부제목)

This is a H2
-------------

## 3. 글머리
1~6까지만 지원한다, html처럼 1이 제일 큰 글씨이다. 7은 안된다!
```#``` 쓰고 띄어쓰기 한 번 꼭 해줘야 문법이 적용된다.
# This is a H1
## This is a H2
### This is a H3
#### This is a H4
##### This is a H5
###### This is a H6


## 4. 블럭인용(BlockQuote)
```>```는 블럭인용문자이다.
아래 문장이면 >를 하나 더 붙인다.
블럭인용 안에서는 다른 마크다운 요소를 포함할 수 있다!
> This is a first blockquote.
>> This is a second blockquote.
>>> This is a second blockquote.


## 5. ordered list
어떤 번호를 입력해도 순서는 내림차순으로 된다.
```
1. 첫번째
2. 두번째
3. 세번쨰
```
1. 첫번째
2. 두번째
3. 세번쨰

```
1. 첫번째
3. 두번째
2. 세번째
```
1. 첫번째
3. 두번째
2. 세번째

## 6. unordered list
글머리 기호, 혼합해서 사용하는것도 가능하다!
```
* A
  * B
    * C
```
* A
  * B
    * C

```
+ A
  + B
    + C
```
+ A
  + B
    + C

```
- A
  - B
    - C
```
- A
  - B
    - C

```
* A
  + B
    - C
```

* A
  + B
    - C
## 7. 수평선
***
---

* * *
- - -


---
layout: post
title: "Github Blog 만들기 "
author: "Wook Hyun"
categories: documentation
tags: [blog]
image: cuba-1.jpg
---


## Github.io 에 블로그 페이지 만들기


## 필요한 툴
  * jekyill

## github에 공간 만들기

  * 일단 [여기](https://angrypark.github.io/starting-my-blog/)에서 시작하자.

## 사용법

일단 로컬에서 작업한 이후 Github에 push를 하는 형태로 개발하면 되는데, 로컬에서 작업할 때 Jekyill로 만들어진 페이지들은 일반 웹서버에서는 보여지지 않는다. 그렇기 떄문에 전용 웹서버를 jekyill 툴로 구동시켜야만 한다. 자세한 내용은 [여기](https://mycyberuniverse.com/web/how-fix-jekyll-build-serve-error-message.html)를 참고하자.

1. 템플릿을 [여기](http://jekyllthemes.org/)에서 다운받아 압축을 푼 디렉토리로 가서.. 아래 명령을 실행한다.
```
$ gem install bundler
$ bundle install
$ bundle exec jekyll serve 
```

2. 그리고 웹 브라우저에서 잘 동작하는지 들여다 보자. 주소는 http://localhost:4000 이다.
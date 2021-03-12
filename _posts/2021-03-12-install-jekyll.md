---
title: Jekyll + Github + Fork 블로그 만들기 
author: Harry JongSeok Lee
date: 2021-03-12 15:00:00 +0900
categories: [Tutorial]
tags: [jekyll, blog]
pin: false
comments: true
---

## Prerequisites 

Jekyll + Github 블로그 만들기는 아래의 순서대로 진행됩니다. 
  
  - 설치 (윈도우 위주)  
  - 테마선택/설정 
  - Post 작성 
  - github page 사이트
  - etcs.

## Installation 

   Jekyll은 Ruby를 사용함으로, 윈도우용 *`Ruby`, `Gem`, `Bundler`* 를 설치합니다. 또한 gem package manager는 git을 통해서 정보를 받기 때문에,  **윈도우용 gitscm**을 설치해야 합니다. 

   [Jekyll 설치문서 (en)](https://jekyllrb.com/docs/installation/)   
   [Jekyll 설치문서 (ko)](http://jekyllrb-ko.github.io/docs/installation/)  
   [GIT SCM 사이트](https://git-scm.com/download/win)

### install Ruby+devkit

   설치문서에 따라, [Ruby+Devkit](https://rubyinstaller.org/downloads/) 에서 **Ruby+Devkit 2.7.2-1 (x64)** 을 다운받아 설치합니다. 
   
   <span style="color:red">!) 설치 시 **ridk install** 을 반드시 선택하셔야 합니다. </span>  

   ![Ruby+Devkit Install1](/assets/post/install.PNG)
   
   **ridk install** 설치화면.   

   ![Ruby+Devkit Install2](/assets/post/install2.PNG)

   설치가 완료되면 시작 -> cmd 창을 여시고, 아래와 같이 명령어를 칩니다.

   ```console
   ruby --version 
   ```

   오류가 안나면 **Ruby+Devkit**이 정상 설치된 것입니다.   
 
   
### Jekyll, Bundler 설치 
   
   Jekyll 설치문서에 따라, **Jekyll, Bundler**를 설치합니다.   
   [Jekyll 설치문서 (ko)](http://jekyllrb-ko.github.io/docs/installation/)
   
   ```console
   bundle install jekyll, Bundler
   ```

   설치가 완료되면 아래 명령어를 쳐보세용 ^^;   

   ```console
   jekyll -v 
   ```  
   
   자 이제 Jekyll 을 사용할 준비가 되었습니다!!.
    
## 테마선택/설정

## Post 작성 

## github page 만들기

## Etcs. 
   







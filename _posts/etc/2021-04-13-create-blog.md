---
layout: single
title:  "GitHub Blog 만들기"

---

다음과 같은 과정을 거쳐서 Blog를 만들었다.



[TOC]



# 1. 전제조건

* GitHub에 계정생성
* GitHub 로그인 상태



# 2. Blog 생성

## 2.1 테마 선택

- jekyll-theme에서 원하는 블로그 테마를 선택
  https://github.com/topics/jekyll-theme 
- 예) 전 여기서 minimal-mistakes를 선택

![image-20210412170601959](../images\2021-04-13\image-20210412170601959.png)



## 2.2 선택한 테마를 fork

- 선택한 테마의 좌상단의 Fork 버튼을 클릭하여 내 GitHub에 Fork함
- Fork가 완료되면 내 GitHub 저장소에 선택한 테마가 복제됨

![image-20210412170932475](../images\2021-04-13\image-20210412170932475.png)



## 2.3 설정 수정

### 2.3.1 설정 수정

* 복제된 블로그의 좌상단에 'Settings' 버튼을 클릭하여 설정 정보를 변경

![image-20210413110436828](../images\2021-04-13\image-20210413110436828.png)

* 설정 정보의 'Repository name'을 {GitHub ID}.github.io 로 변경한 뒤 'Rename' 버튼을 클릭하여 변경 완료

![image-20210413110452231](../images\2021-04-13\image-20210413110452231.png)

* 'Repository name' 변경을 완료하면 다음과 같이 이름이 변경됨을 확인할 수 있음

![image-20210413110910899](../images\2021-04\image-20210413110910899.png)



### 2.3.2 Config 수정

- 소스 목록에서 '_config.yml' 파일을 선택하여 수정

![image-20210413105504048](../images\2021-04-13\image-20210413105504048.png)

- 소스 파일의 우상단의 'Edit this file' 버튼'을 클릭하여 편집

![image-20210413111258986](../images\2021-04-13\image-20210413111258986.png)

- URL 변경
  - 아래와 같이 'Site Settings'를 변경해 준 뒤 화면의 하단의 'Commit changes' 버튼을 클릭하여 변경사항을 저장

```
# Site Settings
locale                   : "ko-KR"
title                    : "{블로그 타이틀}"
title_separator          : "-"
subtitle                 : # site tagline that appears below site title in masthead
name                     : "{블로그명}"
description              : "{블로그 간단 설명}"
url                      : "https://{GitHub ID}.github.io"
```



## 2.4 블로그 생성 확인

* 브라우저에 아래와 같이 url을 입력하고 블로그가 생성되었음을 확인
  * "https://{GitHub ID}.github.io"



## 2.5 새로운 포스팅을 생성

* 버튼 'Add file>Create new File'을 클릭하여 새 파일을 추가

![image-20210413130754796](../images\2021-04-13\image-20210413130754796.png)

* 텍스트 박스에 posts/{년}-{월}-{일}-{이름}.md

![image-20210413130940187](../images\2021-04-13\image-20210413130940187.png)

* 예) 2021-04-13-01.md

![image-20210413131211644](../images\2021-04-13\image-20210413131211644.png)

* MD(Markdown) 문법에 맞추어 페이지를 작성
* 'Commit new file' 버튼을 클릭하여 블로그 페이지 생성



## 2.6 참고 URL

* MD 문법 참고 URL
  * https://jekyllrb.com/docs/posts/
  * https://gist.github.com/ihoneymon/652be052a0727ad59601#file-how-to-write-by-markdown-md
* MD 편집기 Tpora
  * https://typora.io/#windows


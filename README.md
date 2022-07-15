## 마크다운

텍스트 기반의 가벼운 마크업(markup) 언어

​	```마크업이란? 태그를 이용하여 문서의 구조를 나타내는 것```

​	```HTML(Hyper Text Markup Language)가 대표적인 마크업을 이용한 것```

문서의 구조와 내용을 같이 쉽고 빠르게 적고자 탄생  


<br>

<마크다운으로 할 수 있는 것>

* README.md 파일을 통해 오픈 소스의 공식 문서 작성
* 개인 프로젝트의 소개문서 작성
* 매일 학습한 내용 정리
* 마크다운을 이용한 블로그 운영



<br>

<헤딩(Heading)>

문서의 제목이나 소제목으로 사용

#의 개수에 따라 제목의 수준을 구별(h1~h6)



<br>

<리스트(List)>

1., 2., 3., *, - 등등

순서가 있는 리스트와 순서가 없는 리스트

목록을 표시하기 위해 사용

shift+tab => 상위 리스트로 이동

tab => 하위 리스트로 이동



<br>

<코드 블럭(Code Block)>

일반 텍스트와 다르게 코드를 예쁘게 출력

사용하는 프로그램에 딸 특정 언어를 명시하면 구문 강조 지원

구문 강조(Syntax highlighting)


<br>

mattermost에 코드 보낼 때, 이 형식으로 보낼 것!

\``` + py + <shift+enter> +  코드 + <shift+enter> + \```



<br>

<링크(Link)>

 \[string][url]

string은 보여지는 부분,  url은 연결할 곳을 나타냄.

다른 페이지로 이동하는 링크를 삽입.

필요하다면 파일의 경로를 넣어 다운로드 가능한 링크롬 만들 수 있음.



<br>

<이미지(Image)>

\![string]\(img_url)

링크와 비슷하며 이미지를 삽입함.

이미지의 너비와 높이는 조절 불가.

조절이 필요하다면 HTML 사용 필요.

 
<br>

<수평선(Horizontal line)>

\---

가로로 긴 수평선을 작성.


<br>

<텍스트 강조(Text Emphasis)>

\**Bold** 	\*italic\* 	\~~

순서대로 굵게, 기울림, 취소선을 이용해 강조


<br>

<표(Table)>

| 번호 | 이름   | 전화번호      |
| ---- | ------ | ------------- |
| 1    | 황지연 | 010-1234-5678 |
| 2    | 홍길동 | 010-2345-6789 |

표도 삽입 가능함.

|와 --- 을 이용하여 만들 수 있음 (방법은 보기=>소스코드모음로 바꿔서 볼 수 있음)


<br>

<주석(Annotation)>

\> 를 이용하여 주석 표시

> 이것은 주석입니다.

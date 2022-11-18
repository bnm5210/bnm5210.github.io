# 안녕하세요, 방석중입니다. 네이버 클라우드 개발자 과정1기

## 마크다운(MarkDown) 문법, 사용법 정리

- 구글: <https:codesik.github.io/How-To-Use-MarkDown>

## 마크다운(MarkDown)문법

- 마크다운(markdown)은 일반 텍스트 기반의 경량 마크업 언어다. 일반 텍스트로 서식이 있는 문서를 작성하는 데 사용되며, 일반 마크업 언어에 비해 문법이 쉽고 간단한 것이 특징이다.HTML과 리치텍스트(RTF) 등 서식 문서로 쉽게 변환되기 때문에 응용 소프트웨어와 함께 배포되는 README 파일이나 온라인 게시물 등에 많이 사용된다.

## 제목(Header)

### 제목을 작성하는 두가지 방법   

- #을 사용해 표시

- Horizen 을 사용해 표시

## 목록(List)

- 1. 2. 와 같은
 기호로(순서가 정해진 경우), -, *, + 순서가 미정해진 경우 사용합니다. 

### 예시


순서가 있는 목록
1. 짜장면
3. 피자
2. 햄버거

순서가 없는 목록
* 목록 1
  * 목록 1.1
    * 목록 1.2

- 목록 2
+ 목록 3

## 링크
- [텍스트](참조할 주소)를 써주시면 됩니다.
  
[구글](https://google.com)

이렇게 사용하면 구글이라는 텍스트에 주소가 반영됩니다.

꺾쇠를 활용해서 링크를 그대로 반환할 수 있습니다.

구글: <https://google.com>

## 이미지 삽입
- 링크를 쓰는 방법과 비슷합니다. 다만 앞에 !가 붙습니다.

이미지만 삽입
![이미지 설명](이미지 링크)

링크를 포함해서 이미지 삽입
[![이미지 설명](이미지 링크)](연결될 url)

html태그로 삽입
<img src = "주소" width = "50%" height = "50%" >

<img src = "https://www.bing.com/images/search?q=&view=detailv2&id=3C51F03891743F98E8004E8AAA3DDEE71BEBD523&ccid=cn8/nz4u&iss=fav&FORM=SVIM01&idpview=singleimage&mediaurl=https%253a%252f%252fis3-ssl.mzstatic.com%252fimage%252fthumb%252fPurple113%252fv4%252f6b%252f20%252f67%252f6b2067e9-5a55-b8a2-6364-c575ce4e5fca%252fsource%252f512x512bb.jpg&expw=512&exph=512&thid=OIP.cn8_nz4ue8wFVuIb4zgbGAHaHa&idpbck=1" width = "50" heigt = "50%">

이런식으로 이미지를 삽입하면, 크기를 조정해 줄수 있고 %를 붙이지 않으면 픽셀로 조정됩니다. 다만 %는 HTML5에서는 픽셀(pixel) 단위만 적용됩니다.

## 인용문
> 인용문 1
>> 인용문 2
>>> 인용문 3

> 의 갯수에 따라 중첩하여 쓸 수 있습니다. 
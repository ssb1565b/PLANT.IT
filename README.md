# 

<div align="center">
  <br />
  <img width="1418" alt="image" src="https://user-images.githubusercontent.com/86584041/223015659-e10b33ff-c9de-4448-9b1e-c82141d59d4c.png">
  <br />

# 🌱우리의 녹색 행성, 더 싱그러워지도록, PLANT.IT🌱

</div>

<br />

##  ☘ 목차

1. [**프로젝트 소개**](#1)
2. [**기능 소개**](#2)
3. [**개발 환경**](#3)
4. [**기술 스택**](#4)
7. [**Commit & Branch Convention**](#5)

<br />

<div id="1"></div>

## 🌳 프로젝트 소개
```
본격적으로 식물 키우기 전, 재미로 보는 자가진단 테스트와
카테고리별 식물을 소개하며 가드닝의 장점을 널리 퍼트리고
환경을 살리는 목적을 지닌 웹사이트 입니다
```

🔗 배포링크 : https://celadon-madeleine-e74a3c.netlify.app/index.html<br />

🗓️ 프로젝트 기간 :  23.02.26 ~ 23.03.06<br />
<br />
> ###  팀원 소개

<table>
  <tr>
     <td align="center">
      <a href="https://github.com/ssb1565b">
        <img src="https://avatars.githubusercontent.com/u/84695884?v=4" width=170px alt=“송수빈 프로필" />
      </a>
    </td>
    <td align="center">
       <a href="https://github.com/ssb1565b">
        <img src="https://avatars.githubusercontent.com/u/79959246?v=4" width=170px alt=“윤제 프로필" />
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/ssb1565b">
	       <img src="https://avatars.githubusercontent.com/u/104487178?v=4" width=170px alt=“송민선 프로필" />
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/ssb1565b">
	     <img src="https://avatars.githubusercontent.com/u/86584041?v=4" width=170px alt=“박성희 프로필" />
      </a>
    </td>
   
  </tr>

  <tr>
    <td align="center">
     <a href="https://github.com/ssb1565b">
        송수빈
      </a>
    </td>                       
    <td align="center">
      <a href="https://github.com/ssb1565b">
        윤제
      </a>
    </td>
    <td align="center">
     <a href="https://github.com/ssb1565b">
        송민선
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/ssb1565b">
        박성희
      </a>
    </td>
   
  </tr>
<tr>
    <td align="center">
   Front-end<br />Design
    </td>
    <td align="center">
   Front-end<br />
    </td>
    <td align="center">
   Front-end<br />
    </td>
    <td align="center">
   Front-end<br />
    </td>
 
  </tr>
  <tr>
    <td align="center">
      localStorage 활용 필터링<br />
      keyframe animation<br />
      테스트 결과 조회 <br />
      식물 목록 조회 swiper<br/>
      media query 반응형<br/>
    </td>
    <td align="center">
      localStorage 활용 테스트 구현<br/>
      스토리 페이지 slider 구현
    </td>
    <td align="center">
      식물 조회 필터<br />
    </td>
    <td align="center">
      스토리 영상 추가
    </td>
  </tr>
</table>


<div id="2"></div>

## 🌴 기능 소개

<div id="3"></div>
 <table>
  <tr>
    <th>Main</th>
    <td>classlist.add(), remove() 함수를 통해 마우스 오버시 부정적인 단어가 사라지면서 브랜드 소개글이 보여집니다. <br/>
    window,scrollTo()함수와 offsettop을 사 용해 버튼 클릭시 스크롤 이동합니다. <br/>
    media query를 이용한 반응형 페이지로 헤더의 컬러는 scss의 mixin, include 기능을 활용하여 전역적으로 색상값을 전달합니다. <br/>
    localStorage에 식물의 카테고리값을 저장하여 식물카테고리 페이지 이동시 getItem 함수를 통해 필터링하여 식물이 조회됩니다. <br/>
    keyframe animation으로 캐릭터의 움직임이 동적으로 표현됩니다
    </td>
</tr>
<tr>
  <th>Category</th>
  <td>string으로만 구성된 식물 데이터를 객체로 변경하여 화면에 그려줍니다. <br/>
	  로컬 스토리지 값 받아와 검색 결과 초기화합니다. <br/>
	  버튼 click 에 따라 클래스명(clicked)을 부여하여 hover, click 시 디자인 변경됩니다. 또한 각 버튼마다 해당되는 식물의 속성값 저장합니다. <br/>
	  window에 addEventListener를 부여하여 필터링 버튼 클릭시마다 검색결과가 리렌더링되어 보여집니다.
  </td>
</tr>
<str>
  <th>Test</th>
  <td></td>
</str>
<tr>
  <th>TestResult</th>  
  <td>결과 페이지를 컴포넌트화 하여 localStroage 값에 따라 내부 값이 변경됩니다. <br/>
	  swiper의 autoplay.start()를 통하여 추천 식물을 동적으로 그려줍니다. <br/>
  </td>
  </tr>
 <tr>
    <th>Stroy</th>
    <td></td>
</tr>
  </table>
  
## 🌵 개발 환경

<div id="4"></div>

**IDE** 

<img src="https://img.shields.io/badge/Visual_Studio-5C2D91?style=for-the-badge&logo=visual%20studio&logoColor=white">

**테스트 환경**

<img src="https://img.shields.io/badge/googlechromeo-ea4335?style=for-the-badge&logo=googlechrome&logoColor=white">

## 🌿 기술 스택
**Front-end**

![html5](https://img.shields.io/badge/html5-E34F26?style=for-the-badge&logo=html5&logoColor=white) ![css3](https://img.shields.io/badge/css-1572B6?style=for-the-badge&logo=css3&logoColor=white) ![javascript](https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black) ![sass](https://img.shields.io/badge/scss-FF3399?style=for-the-badge&logo=sass&logoColor=white) 

**Cooperation**

![git](https://img.shields.io/badge/git-F05032?style=for-the-badge&logo=git&logoColor=white) ![github](https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white) ![figma](https://img.shields.io/badge/figma-000000?style=for-the-badge&logo=figma&logoColor=white)

<div id="5"></div>

## 🍃 Commit & Issue Convention

| 태그이름 | 설명                                               |
| -------- | -------------------------------------------------- |
| Feat     | 새로운 기능을 추가할 경우                          |
| Fix      | 버그를 고친 경우                                   |
| Design   | CSS 등 사용자 UI 디자인 변경                       |
| Refactor | 프로덕션 코드 리팩토링                             |
| Rename   | 파일 혹은 폴더명을 수정하거나 옮기는 작업만인 경우 |
| Remove   | 파일을 삭제하는 작업만 수행하는 경우               |
| Chore    | 프로젝트 초기설정 및 빌드 관련 부분                |

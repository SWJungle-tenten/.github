# GooglingHelper 
<!--   추가해야하는 부분   -->
<!-- [![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2FSY-Highlighters%2FHighlighters%2Ftree%2Fdevelop&count_bg=%233DB4C8&title_bg=%23555555&icon=krita.svg&icon_color=%23E7E7E7&title=Highlighters&edge_flat=false)](https://hits.seeyoufarm.com) -->
<!--   추가해야하는 부분   -->
<a name="readme-top"></a>

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://googlinghelper.shop" target="_blank">
<!--   추가해야하는 부분   -->
<!--     <img src="https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdn%2F31yWM%2FbtrXCZpaP2S%2FyqPF5xC7b25iYzKE5KflE1%2Fimg.png" alt="Logo" width="" height=""> -->
  </a>

  <p align="center">
   <i>웹서핑을 편리하게</i>
  </p>
  <p align="center">
    <b> 크롬익스텐션을 이용한 사이트 미리보기와 스크랩을 이용한 더 빠르고 편하게 내용을 정리할 수 있는 툴</b>
  </p>
</div>

<!-- TABLE OF CONTENTS -->

## 목차

1. [프로젝트 개요](#GooglingHelper)
2. [서비스 소개](#Intro)
4. [서비스 구조도](#Arch)
5. [프로젝트 포스터](#Poster)

<!-- ABOUT THE PROJECT -->

<a name="GooglingHelper"> </a>

## 프로젝트 개요

프로젝트 기간 : 2023.06.10 ~ 2023.07.08 (4주)

기술 스택 :
| 분류                      | 기술                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| ------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Frontend**              | <img src="https://img.shields.io/badge/react-61DAFB?style=for-the-badge&logo=react&logoColor=black">  <img src="https://img.shields.io/badge/tailwindcss-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white"> |
| **Extension**             | <img src="https://img.shields.io/badge/Extension Manifest v3-4285F4?style=for-the-badge&logo=googlechrome&logoColor=white"> <img src="https://img.shields.io/badge/react-61DAFB?style=for-the-badge&logo=react&logoColor=black">                                                                                                    |
| **Backend**               | <img src="https://img.shields.io/badge/expressjs-E0234E?style=for-the-badge&logo=nestjs&logoColor=white">                                                                                                                                                                                                                                                                                                                                         |
| **Database**              | <img src="https://img.shields.io/badge/mongoDB-DC382D?style=for-the-badge&logo=mongoDB&logoColor=green">                                                                                                                 |
| **Infrastructure/DevOps** | <img src="https://img.shields.io/badge/Load-balance-009639?style=for-the-badge&logo=Load-balance&logoColor=white"> <img src="https://img.shields.io/badge/aws_lambda-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white"> <img src="https://img.shields.io/badge/aws_s3-569A31?style=for-the-badge&logo=amazonaws&logoColor=white">            |

팀원 : [안성범](https://github.com/SungBeum)(TL/FE), [김동진](https://github.com/terrydkim)(FE), [황채림](https://github.com/cofla159)(FE), [이상운](https://github.com/Sangun-Lee-6)(BE), [임혜정](https://github.com/HJUNG118)(BE)

<!-- 서비스 사용 설명서 : [바로가기](https://www.notion.so/yeriiin/Highlighters-b7074bda3ec542e7bd4002babca6e5fc) -->
<!--   추가해야하는 부분   -->
웹사이트 : [바로가기](https://googlinghelper.shop)

- demo 계정 : Guest@tenten.com
- demo 계정 비밀번호 : 1234
- 익스텐션을 설치해야 스크랩기능이 활성화되니, 아래의 스토어에서 설치 후 이용해주시면 감사하겠습니다.

크롬 익스텐션 스토어 : [바로가기](https://chrome.google.com/webstore/detail/googling-helper/hacpklepjhoahlhcipjkocfbdmoefbhl?hl=ko)
<!--   추가해야하는 부분   -->
<!--
시연 영상 : [바로가기](https://www.youtube.com/watch?v=1hC4BrA4MJI)

현장 발표영상 : [바로가기](https://youtu.be/n9EOK_6DOe0)
-->
<!--   추가해야하는 부분   -->
<p align="right">(<a href="#readme-top">맨 위로</a>)</p>

<a name="Intro"> </a>

## 서비스 소개

 <h3 align="left">GooglingHelper 는 4가지 고민에서 시작되었습니다 !</h3>
 
- 사이트를 새로 열 때마다 페이지 전환되는게 싫어 !
- 마음에 들었던 사이트를 모아두고 바로 다시 들어가고 싶어 ! 
- 링크로 접속해서 생기는 많은 탭들을 관리하기 너무 힘들어 !
- 내용을 하나하나 직접 정리하기 귀찮아 !

 <h3 align="left">GooglingHelper는 이런 서비스입니다.</h3>
 
1. 크롬 익스텐션을 통해 사이트에 직접 들어가지 않고 게시글 목록에서 미리볼 수 있습니다. 
2. 링크, 이미지, 텍스트 스크랩을 이용해 홈페이지에서 한 눈에 모아볼 수 있습니다.
3. 이미지, 텍스트 스크랩한 자료를 Drag&Drop 을 이용해 간편하게 내용을 정리할 수 있습니다.

 <h3 align="left">주요 기능</h3>
 
#### 1. 사이트 미리보기

- 게시물 목록의 사이트를 직접 접속하지 않고 미리 볼 수 있습니다.

<table border="0" >
  <tr>
    <!--   추가해야하는 부분   -->
<!--         <td><img width="400" height="200" src="https://user-images.githubusercontent.com/101175828/216561610-7b3c0b07-2924-4414-be78-281ea964e699.gif"> </img></td>
        <td><img width="400" height="200" src="https://user-images.githubusercontent.com/101175828/216561650-8a524521-d6d2-46fd-91af-0f1cedb5fa21.gif"></img></td> -->
  </tr>

</table>

#### 2. 링크 스크랩하기

- 스크랩한 사이트들을 홈페이지에서 한 눈에 모아볼 수 있습니다.
<!--   추가해야하는 부분   -->
  <!-- <div>
    <img width="300" height="160"  src="https://user-images.githubusercontent.com/101175828/216537143-2f7bcd1f-9d30-42f8-86de-10587673a030.gif"></img>
    <img width="300" height="160" src="https://user-images.githubusercontent.com/101175828/216537281-4498ad2d-a8c5-44fa-9c54-e0ab51c337cb.gif"> </img>
  </div> -->
   <table border="0" >
    <tr>
<!--         <td>    <img src="https://user-images.githubusercontent.com/101175828/216537143-2f7bcd1f-9d30-42f8-86de-10587673a030.gif"></img></td>
        <td>    <img src="https://user-images.githubusercontent.com/101175828/216537281-4498ad2d-a8c5-44fa-9c54-e0ab51c337cb.gif"> </img></td> -->
   </tr>

  </table>

#### 3. 이미지 부분스크랩하기

- 캡처기능을 이용해 부분적으로 스크랩하고 싶은 이미지를 스크랩할 수 있습니다.
- 스크랩한 이미지는 홈페이지에서 메모로 Drag&Drop 할 수 있도록 변환되어 있습니다.
  <div>
  <!--   추가해야하는 부분   -->
<!--     <img width="400" height="230" src="https://user-images.githubusercontent.com/101175828/216539463-35aa8836-9b30-41c0-aeac-ef03335c031e.gif"> </img>
    <img width="300" height="230" src="https://user-images.githubusercontent.com/101175828/216539648-c765fe17-f104-4500-96ab-0a074e0e70d2.gif"> </img> -->
  </div>

#### 4. 텍스트 부분스크랩하기

- 캡처기능을 이용해 부분적으로 스크랩하고 싶은 텍스트를 스크랩할 수 있습니다.
- 스크랩한 텍스트는 홈페이지에서 메모에 Drag&Drop 할 수 있도록 변환되어 있습니다.
  <div>
  <!--   추가해야하는 부분   -->
<!--     <img  src="https://user-images.githubusercontent.com/101175828/216539214-8ee34979-d587-49df-a343-38fcc02f5be5.gif"> </img> -->
  </div>
  
#### 5. 메모장

- 스크랩한 자료들을 Drag&Drop 으로 간편하게 메모에 넣을 수 있습니다.
- 메모를 자유롭게 편집할 수 있습니다.
   <div>
   <!--   추가해야하는 부분   -->
<!--     <img width="400" height="400" src="https://user-images.githubusercontent.com/101175828/216554060-f565c9d9-2904-4ed3-890b-ce310bee307f.gif"> </img> -->
  </div>

#### 6. 검색어별/날짜별 모아보기

- **날짜별**로 스크랩한 자료들과 사이트를 홈페이지에서 한 번에 모아볼 수 있습니다.
- **검색어별**로 스크랩한 자료들과 사이트를 홈페이지에서 한 번에 모아볼 수 있습니다.
   <div>
   <!--   추가해야하는 부분   -->
<!--     <img width="400" height="230" src="https://user-images.githubusercontent.com/101175828/216561358-16fb58e4-8401-406f-bdb4-5a42b8dc047b.gif"> </img> -->
  </div>

#### 7. 이미지/텍스트 모아보기

- 부분 스크랩한 **이미지**를 한 번에 모아볼 수 있습니다.
- 부분 스크랩한 **텍스트**를 한 번에 모아볼 수 있습니다.
<table border="0" >
  <tr>
    <!--   추가해야하는 부분   -->
<!--         <td>    <img src="https://user-images.githubusercontent.com/101175828/216554937-47c37f6d-5eb7-4285-86f4-ab150506d98b.png"></img></td>
        <td>    <img src="https://user-images.githubusercontent.com/101175828/216554961-c3c90f2b-6a71-4265-8bb3-d9c8cf8022ed.png"> </img></td>
        <td>    <img src="https://user-images.githubusercontent.com/101175828/216554978-c0545a1f-4705-44f1-bc2e-5c2403cc9777.png"> </img></td> -->
  </tr>

</table>

#### 8. 검색 기능

- 검색한 내용을 포함한 스크랩한 텍스트를 찾아내 보여줍니다.
  
  <div>
  <!--   추가해야하는 부분   -->
<!--     <img src="https://user-images.githubusercontent.com/101175828/216539091-6fe20844-8241-49ef-9c0d-764449dbca8c.gif"> </img> -->
  </div>

<!-- 아키텍처 -->

<a name="Arch"></a>

## 서비스 구조도

  ![image](https://github.com/SWJungle-tenten/.github/assets/126440955/43be9242-df45-4cc7-a44c-5e6659aaa3f6.png)

<p align="right">(<a href="#readme-top">맨 위로</a>)</p>

<!-- 포스터 -->

<a name="Poster"> </a>

## 프로젝트 포스터
![image](https://github.com/SWJungle-tenten/.github/assets/126440955/c6fca7e9-c906-4e76-a4b7-9ddef33098bb.png)

<p align="right">(<a href="#readme-top">맨 위로</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=for-the-badge
[contributors-url]: https://github.com/othneildrew/Best-README-Template/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=for-the-badge
[forks-url]: https://github.com/othneildrew/Best-README-Template/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/othneildrew/Best-README-Template/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/SY-Highlighters/Highlighters/issues
[product-screenshot]: images/screenshot.png
[next.js]: https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white
[next-url]: https://nextjs.org/
[react.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[react-url]: https://reactjs.org/
[vue.js]: https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D
[vue-url]: https://vuejs.org/
[angular.io]: https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white
[angular-url]: https://angular.io/
[svelte.dev]: https://img.shields.io/badge/Svelte-4A4A55?style=for-the-badge&logo=svelte&logoColor=FF3E00
[svelte-url]: https://svelte.dev/
[laravel.com]: https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white
[laravel-url]: https://laravel.com
[bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[bootstrap-url]: https://getbootstrap.com
[jquery.com]: https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white
[jquery-url]: https://jquery.com

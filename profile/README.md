# GooglingHelper [![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2FSWJungle-tenten&count_bg=%2310C634&title_bg=%23126AE1&icon=google.svg&icon_color=%23C20000&title=GooglingHelper&edge_flat=false)](https://hits.seeyoufarm.com)
<a name="readme-top"></a>

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://googlinghelper.shop" target="_blank">
    <img src="https://github.com/SWJungle-tenten/.github/assets/126440955/c972001b-c330-45ee-8737-3f3a4222a73d">
  </a>

  <p align="center">
    <p> 크롬익스텐션을 통한 링크 미리보기&스크랩으로 편리한 문서 작업</p>
  </p>
</div>

<!-- TABLE OF CONTENTS -->

## 목차

1. [프로젝트 개요](#GooglingHelper)
2. [서비스 소개](#Intro)
3. [서비스 구조도](#Arch)
4. [프로젝트 포스터](#Poster)

## 시연 영상

[바로가기](https://youtu.be/xxpbxBdquFA)

## 현장 발표 영상

[바로가기](https://youtu.be/GlJD88dwDxQ)

<a name="GooglingHelper"> </a>

## 프로젝트 개요

프로젝트 기간 : 2023.06.10 ~ 2023.07.08 (4주)

기술 스택 :
| 분류                      | 기술                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| ------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Frontend**              | <img src="https://img.shields.io/badge/react-61DAFB?style=for-the-badge&logo=react&logoColor=black">  <img src="https://img.shields.io/badge/tailwindcss-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white"> |
| **Extension**             | <img src="https://img.shields.io/badge/Extension Manifest v3-4285F4?style=for-the-badge&logo=googlechrome&logoColor=white"> <img src="https://img.shields.io/badge/react-61DAFB?style=for-the-badge&logo=react&logoColor=black">                                                                                                    |
| **Backend**               | <img src="https://img.shields.io/badge/expressjs-E0234E?style=for-the-badge&logo=expressjs&logoColor=white">                                                                                                                                                                                                                                                                                                                                         |
| **Database**              | <img src="https://img.shields.io/badge/mongoDB-DC382D?style=for-the-badge&logo=mongoDB&logoColor=green">                                                                                                                 |
| **Infrastructure/DevOps** | <img src="https://img.shields.io/badge/loadBalance-009639?style=for-the-badge&logo=loadBalance&logoColor=white"> <img src="https://img.shields.io/badge/aws_lambda-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white"> <img src="https://img.shields.io/badge/aws_s3-569A31?style=for-the-badge&logo=amazonaws&logoColor=white">            |

팀원 : [안성범](https://github.com/SungBeum)(TL/FE), [김동진](https://github.com/terrydkim)(FE), [황채림](https://github.com/cofla159)(FE), [이상운](https://github.com/Sangun-Lee-6)(BE), [임혜정](https://github.com/HJUNG118)(BE)

<br>

~~웹사이트 [바로가기](https://googlinghelper.shop)~~

~~- demo 계정 : Guest@tenten.com<br>~~
~~- demo 계정 비밀번호 : 1234~~

<!--※ 익스텐션을 설치해야 스크랩기능이 활성화되니, 아래의 스토어에서 설치 후 이용해주시면 감사하겠습니다.-->
  
크롬 익스텐션 스토어 [바로가기](https://chrome.google.com/webstore/detail/googling-helper/hacpklepjhoahlhcipjkocfbdmoefbhl?hl=ko)

<p align="right">(<a href="#readme-top">맨 위로</a>)</p>

<a name="Intro"> </a>

## 서비스 소개

 <h3 align="left">GooglingHelper 는 4가지 고민에서 시작되었습니다 !</h3>
 
- 웹서핑할 때 링크를 확인할 때마다 페이지 전환되는게 싫어 !
- 마음에 들었던 사이트를 모아두고 바로 다시 보고 싶어 ! 
- 링크로 접속해서 생기는 많은 탭들을 관리하기 너무 힘들어 !
- 내용을 하나하나 직접 정리하기 귀찮아 !

 <h3 align="left">GooglingHelper는 이런 서비스입니다.</h3>
 
1. 크롬 익스텐션을 통해 링크에 직접 접속하지 않고 게시글 목록에서 미리볼 수 있습니다. 
2. 링크, 이미지, 텍스트 스크랩을 이용해 홈페이지에서 한 눈에 모아볼 수 있습니다.
3. 스크랩한 자료를 Drag&Drop으로 간편하게 편집할 수 있습니다.

<br>
 <h3 align="left">주요 기능</h3>
 
#### 1. 사이트 미리보기

- 구글 검색 결과의 링크를 직접 접속하지 않고 미리 볼 수 있습니다.
   <table border="0" >
    <tr>
        <td><img width="500" height="300" src="https://github.com/SWJungle-tenten/.github/assets/109846076/1a1f5909-0f08-4e1f-bfb2-be4df630fbfd.gif"> </img></td>
   </tr>

  </table>
#### 2. 링크 스크랩하기

- 스크랩한 사이트들을 홈페이지에서 한 눈에 모아볼 수 있습니다.

#### 3. 이미지 부분스크랩하기

- 부분적으로 스크랩하고 싶은 구간을 이미지로 스크랩할 수 있습니다.
- 스크랩한 이미지는 홈페이지에서 메모로 Drag&Drop 할 수 있도록 변환되어 있습니다.
  
#### 4. 텍스트 부분스크랩하기

- 부분적으로 스크랩하고 싶은 텍스트를 캡처와 같은 방식으로 스크랩할 수 있습니다.
- 복사 방지가 적용된 글도 스크랩할 수 있습니다.
- 스크랩한 텍스트는 홈페이지에서 메모로 Drag&Drop 할 수 있도록 변환되어 있습니다.
<div style="display:flex; justify-content: space-between;">
<img width="500" height="300" src="https://github.com/SWJungle-tenten/.github/assets/70076564/bbdf73bd-f6d3-4573-a3b1-9ce46e3bf705">
<img width="500" height="300" src="https://github.com/SWJungle-tenten/.github/assets/70076564/33037190-c1a3-4033-8202-269bbffc4d9f">
</div>

  
#### 5. 메모장

- 스크랩한 자료들을 Drag&Drop 으로 간편하게 메모에 넣을 수 있습니다.
- 메모를 자유롭게 편집할 수 있습니다.
   <table border="0" >
    <tr>
        <td><img width="500" height="300" src="https://github.com/SWJungle-tenten/.github/assets/109846076/b3518b20-a65c-4e9f-ab0e-c91a0757adfd.gif"> </img></td>
   </tr>

  </table>

#### 6. 검색어별/날짜별 모아보기

- 스크랩한 자료들과 사이트를 **날짜별**로 홈페이지에서 한 번에 모아볼 수 있습니다.
- **검색어별**로도 모아볼 수 있습니다.
   <table border="0" >
    <tr>
        <td><img width="500" height="300" src="https://github.com/SWJungle-tenten/.github/assets/109846076/85afc612-c31c-4abf-aaf5-a4aea1f83d67.gif"> </img></td>
   </tr>

  </table>

#### 7. 이미지/텍스트 모아보기

- 부분 스크랩한 **이미지**를 모아볼 수 있습니다.
- 부분 스크랩한 **텍스트**를 모아볼 수 있습니다.
   <table border="0" >
    <tr>
        <td><img width="500" height="300" src="https://github.com/SWJungle-tenten/.github/assets/109846076/c060431d-d65b-4c42-b501-0da8ebd9eb66.gif"> </img></td>
   </tr>

  </table>

#### 8. 검색 기능

- 텍스트 스크랩에서 내용을 검색할 수 있습니다.
  <div>
    <img width="500" height="300" src="https://github.com/SWJungle-tenten/.github/assets/109846076/64e976d6-2763-48d0-9220-1886166be442.gif"> </img>
  </div>

<p align="right">(<a href="#readme-top">맨 위로</a>)</p>

<a name="Arch"> </a>
## 서비스 구조도

![image](https://github.com/SWJungle-tenten/.github/assets/126440955/033a80a6-7286-48ec-9863-9dd5cbb4a679)

<p align="right">(<a href="#readme-top">맨 위로</a>)</p>

<a name="Poster"> </a>
## 프로젝트 포스터
![image](https://github.com/SWJungle-tenten/.github/assets/126440955/c6fca7e9-c906-4e76-a4b7-9ddef33098bb)

<p align="right">(<a href="#readme-top">맨 위로</a>)</p>

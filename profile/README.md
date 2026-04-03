<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a id="readme-top"></a>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->



<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->

<!-- [![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![project_license][license-shield]][license-url] -->



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/GetOurRI">
    <img src="../assets/logo.png" alt="Logo" width="80" height="80">
  </a>

<h1 align="center">TryAngle</h1>

  <p align="center">
    온디바이스AI 기반 실시간 촬영 구도 가이드 서비스
    <br />
    <a href="https://example.com"><strong>TryAngle 바로가기</strong></a>
    <br />
    <br />
   📋 온디바이스 AI 기술 특허 준비중(2026.04 완료 예정)<br />
   📋 2026 한이음 드림업 AI 프로젝트 참여<br />
   🏆 2025 CAU 실전 창업 교육 F.A.S.T 1 [대상]<br />
   🏆 2025 2학기 중앙대학교 예술공학대학 과제전 [전체 1등]
  </p>
</div>



<!-- 프로젝트 소개 -->
## 프로젝트 소개

![TryAngle 스크린샷](../assets/main_product_img.jpeg)

TryAngle는 중앙대학교 다빈치 캠퍼스의 학우들이 사진 구도를 잘 모르는 사람들도 사진을 잘 찍을 수 있도록 기획한 프로젝트입니다.<br>
카메라를 켜면 해당 배경의 최적 구도를 AI가 추론하여 화면비, 인물 위치, 카메라 기울기, 포즈 등을 실시간으로 가이드해줍니다.
온디바이스 기반 AI 최적화 및 양자화 기술을 통해 실시간으로 AI피드백을 받을 수 있습니다


<p align="right">(<a href="#readme-top">back to top</a>)</p>


### 🎯 주요기능

<!-- ![TryAngle 이미지 설명](../assets/final_img.png)

✅  **기숙사 룸메이트 구인 설문 제공**  
  TryAngle에서 제공하는 설문을 통해 사용자가 자신의 기숙사 생활 습관 및 선호사항을 입력할 수 있습니다.

✅ **설문 결과 기반 타이틀 생성**  
  입력된 응답을 바탕으로 사용자의 특성을 한 줄로 요약한 소개 문구를 자동으로 생성합니다.
  
✅ **AI를 활용한 자동 이미지 생성 기능**  
  기존에 작성한 룸메이트 구인 글을 그대로 붙여넣으면, AI가 텍스트를 분석하여 설문 항목을 자동으로 완성하고 결과 이미지를 생성합니다.

✅ **최종 결과 이미지 생성 및 다운로드 지원**  
  설문 결과를 한 장의 이미지(1000 x 1000px)로 시각화하고, 이미지를 바로 다운로드하여 룸메이트 구인 게시글에 사용할 수 있습니다. -->

<p align="right">(<a href="#readme-top">back to top</a>)</p>


### 😎 함께한 사람들
TryAngle를 제작한 **TryAngle** 를 소개합니다. 팀 TryAngle은 중앙대 **예술공학부**를 기반에 두고 모였습니다. 

|  | 이름 | 역할 | 참여 기간 | 비고 |
|:---:|:---:|:-------|:---:|:------|
| <img src="../assets/KHS.svg" width="64" height="64" style="margin: 4px;"> | 김현수 | `초기 기획` `AI 개발` `iOS 개발` | MVP 개발 ~ 현재 |  |
| <img src="../assets/KSY.svg" width="64" height="64" style="margin: 4px;"> | 김세영 | `UI 디자인` `마케팅` | MVP 개발 ~ 현재 |  |
| <img src="../assets/CSH.svg" width="64" height="64" style="margin: 4px;"> | 최승혜 | `UX 디자인` `서비스 기획` `PM` | MVP 개발 ~ 현재 | [블로그](https://somiru03.tistory.com) |
| <img src="../assets/IYG.svg" width="64" height="64" style="margin: 4px;"> | 이윤균 | `UI 디자인` `마케팅` | MVP 개발 (~ v0.1.0) |  |
| <img src="../assets/JES.svg" width="64" height="64" style="margin: 4px;"> | 전은서 | `안드로이드 개발` | MVP 개발 (~ v0.1.0) |  |
| <img src="../assets/HSI.svg" width="64" height="64" style="margin: 4px;"> | 홍순일 | `안드로이드 개발` | 서비스 개발 |  |
| <img src="../assets/JEB.svg" width="64" height="64" style="margin: 4px;"> | 조은비 | `백엔드 개발` `MLOps` | 서비스 개발 ~ 현재 | [github](https://github.com/Ebee1205) [블로그](https://wavicle.tistory.com/) |


<p align="right">(<a href="#readme-top">back to top</a>)</p>



### 📚 기술 스택

#### **Backend & Data**
[![Python][Python-badge]][Python-url]
[![FastAPI][FastAPI-badge]][FastAPI-url]
[![Redis][Redis-badge]][Redis-url]
[![MySQL][MySQL-badge]][MySQL-url]
[![MongoDB][MongoDB-badge]][MongoDB-url]

#### **AI & Computer Vision**
[![YOLO][YOLO-badge]][YOLO-url]
[![DwPose][DwPose-badge]][DwPose-url]

#### **Admin Frontend**
[![Vue][Vue.js-badge]][Vue-url]
[![Vuetify][Vuetify-badge]][Vuetify-url]

#### **Infrastructure & DevOps**
[![AWS][AWS-badge]][AWS-url]
[![Cloudflare][Cloudflare-badge]][Cloudflare-url]
[![Github Pages][Github-Pages-badge]][Github-Pages-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- 로드맵 -->
## 🛠️ 로드맵
### ✅ 완료된 기능
<!-- - [x] **관별 색상 차별화 적용**  
  기숙사 관(건물)별로 결과 이미지에 색상 구분을 적용했습니다.  
  (`v1.0.1` 반영 완료) -->

### 🏗️ 예정된 기능
<!-- - [ ] **이어하기 기능 추가**  
  설문 진행 중이거나 완료된 결과를 저장하고 나중에 이어서 작업할 수 있도록 개선할 예정입니다.

- [ ] **룸메이트 구인글 이미지 생성 기능**  
  작성된 룸메이트 구인글을 기반으로 자동 요약 및 이미지 생성을 제공할 예정입니다.  
  (`v2.0.0` 이후 적용 예정) -->

추후 업데이트를 통해 더욱 직관적이고 편리한 기능을 제공할 예정이니 많은 관심 부탁드립니다!

<p align="right">(<a href="#readme-top">back to top</a>)</p>



### 🚀 업데이트 내역
자세한 업데이트 내용은 릴리즈 노트를 참고해 주세요!

| FE 버전     | BE 버전     | 출시 날짜      | 주요 업데이트                              |
| --------- | --------- | ---------- | ------------------------------------ |
| **0.1.0** | –         | 2025.02.07 | 베타버전 배포                              |


<p align="right">(<a href="#readme-top">back to top</a>)</p>



### 📝 작업기
<!-- - 📌 [TryAngle의 시작 - @조은비 [25년 2월 3일]](making/Making_1.md) -->
<!-- - 둥동 만들기 - 
- 둥동 만들기 -->

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/github_username/repo_name.svg?style=for-the-badge
[contributors-url]: https://github.com/github_username/repo_name/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/github_username/repo_name.svg?style=for-the-badge
[forks-url]: https://github.com/github_username/repo_name/network/members
[stars-shield]: https://img.shields.io/github/stars/github_username/repo_name.svg?style=for-the-badge
[stars-url]: https://github.com/github_username/repo_name/stargazers
[issues-shield]: https://img.shields.io/github/issues/github_username/repo_name.svg?style=for-the-badge
[issues-url]: https://github.com/github_username/repo_name/issues
[license-shield]: https://img.shields.io/github/license/github_username/repo_name.svg?style=for-the-badge
[license-url]: https://github.com/github_username/repo_name/blob/master/LICENSE.txt

[product-screenshot]: images/screenshot.png


[Python-badge]: https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54
[Python-url]: https://www.python.org/
[FastAPI-badge]: https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi
[FastAPI-url]: https://fastapi.tiangolo.com/ko/
[Redis-badge]: https://img.shields.io/badge/redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white
[Redis-url]: https://redis.io/
[MySQL-badge]: https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white
[MySQL-url]: https://www.mysql.com/
[MongoDB-badge]: https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white
[MongoDB-url]: https://www.mongodb.com/

[YOLO-badge]: https://img.shields.io/badge/YOLO-00FFFF?style=for-the-badge&logo=target&logoColor=black
[YOLO-url]: https://pjreddie.com/darknet/yolo/
[DwPose-badge]: https://img.shields.io/badge/DwPose-FF6F61?style=for-the-badge&logo=google-cardboard&logoColor=white
[DwPose-url]: https://github.com/IDEA-Research/DWPose

[Vue.js-badge]: https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D
[Vue-url]: https://vuejs.org/
[Vuetify-badge]: https://img.shields.io/badge/Vuetify-1867C0?style=for-the-badge&logo=vuetify&logoColor=AEDDFF
[Vuetify-url]: https://vuetifyjs.com/

[AWS-badge]: https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white
[AWS-url]: https://aws.amazon.com/
[Cloudflare-badge]: https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=cloudflare&logoColor=white
[Cloudflare-url]: https://www.cloudflare.com/
[Render-badge]: https://img.shields.io/badge/Render-%46E3B7.svg?style=for-the-badge&logo=render&logoColor=white
[Render-url]: https://render.com/
[Github-Pages-badge]: https://img.shields.io/badge/github%20pages-121013?style=for-the-badge&logo=github&logoColor=white
[Github-Pages-url]: https://pages.github.com/
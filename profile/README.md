<div align="center"> 
  <img width="50%" src="./image/impresser logo.png" />
</div>

## impresser
**GPU를 활용한 이미지 가속 압축 SW 개발**

- Samsung Software AI Academy For Youth 13기 자율프로젝트

- 세메스 기업연계 프로젝트

- 프로젝트 기간 : 2025.10.06 ~ 2025.11.21

- 참여 인원: 5명

<br>

## 🚀 프로젝트 소개

### 배경
디스플레이 패널 생산에는 RGB 패턴 이미지가 필요하며, 이를 위해 BMP 파일을 TIFF 형식으로 압축해 활용합니다. 하지만 기존 세메스 시스템은 CPU 기반 압축 방식으로 인해 처리 속도와 성능에 한계가 존재합니다

### 목적

GPU 기반으로 고속·고효율 이미지 압축을 수행하는 Impresser 서비스를 개발하여 압축 속도를 개선합니다

### 핵심 대상

제조 장비 소프트웨어 기업

### 특징 / 차별점

- GPU 가속 이미지 압축 (CUDA 기반)

- CPU 대비 4배 속도 향상

- 비동기 압축 대기열 (Queue)

- BMP 패턴 이미지 생성 기능 제

- 압축 성능 비교 시뮬레이션 제공

<br>

## 👨‍👩‍👧‍👦 팀원 소개
<div align="center">

<table>
  <tr>
    <td align="center" width="180" valign="top">
      <img src="./image/박지현.png" alt="박지현" width="100" height="120" style="object-fit:cover; border-radius:50%"/><br/>
      <b>박지현</b><br/>
      <sub>Frontend / Design</sub><br/><br/>
      <div style="height:90px;">
        생산 시뮬레이션<br/>
        성능 비교
      </div>
    </td>
    <td align="center" width="180" valign="top">
      <img src="./image/윤혜진.jpg" alt="윤혜진" width="100" height="120" style="object-fit:cover; border-radius:50%"/><br/>
      <b>윤혜진</b><br/>
      <sub>Frontend / Design</sub><br/><br/>
      <div style="height:90px;">
        로그인<br/>
        대시보드<br/>
        이미지 압축<br/>
        이미지 생성
      </div>
    </td>
    <td align="center" width="180" valign="top">
      <img src="./image/김환수.jpg" alt="김환수" width="100" height="120" style="object-fit:cover; border-radius:50%"/><br/>
      <b>김환수</b><br/>
      <sub>Infra / Backend</sub><br/><br/>
      <div style="height:90px;">
        CI/CD 파이프라인 구축<br/>
        nvTIFF 기반 이미지 압축<br/>
        로그인 / Security
      </div>
    </td>
    <td align="center" width="180" valign="top">
      <img src="./image/이희산.webp" alt="이희산" width="100" height="120" style="object-fit:cover; border-radius:50%"/><br/>
      <b>이희산</b><br/>
      <sub>Backend</sub><br/><br/>
      <div style="height:90px;">
        대시보드/압축 및 변환 내역 조회 API<br/>
        CUDA 기반 이미지 생성<br/>
        S3 대용량 다중 이미지 업로드<br/>
      </div>
    </td>
    <td align="center" width="180" valign="top">
      <img src="./image/김나경.jpg" alt="김나경" width="100" height="120" style="object-fit:cover; border-radius:50%"/><br/>
      <b>김나경</b><br/>
      <sub>Leader / Backend</sub><br/><br/>
      <div style="height:90px;">
        잉크젯 설비 API<br/>
        libTIFF 기반 이미지 압축<br/>
        이미지 압축, 설비 대기열(rabbitMQ) 및 알림(SSE)
      </div>
    </td>
  </tr>
</table>

</div>

<br>

## 🛠 기술 스택

<div align="center">

### Backend
![Java](https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=Java&logoColor=white)
![SpringBoot](https://img.shields.io/badge/SpringBoot-6DB33F?style=for-the-badge&logo=SpringBoot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring%20Security-6DB33F?style=for-the-badge&logo=SpringSecurity&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=MySQL&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-FF4438?style=for-the-badge&logo=Redis&logoColor=white)
![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=Swagger&logoColor=white)
![rabbitMQ](https://img.shields.io/badge/rabbitmq-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white)
![SSE](https://img.shields.io/badge/SSE-4479A1?style=for-the-badge)
![minio](https://img.shields.io/badge/minio-C72E49?style=for-the-badge&logo=minio&logoColor=white)

---

### Image
![nvtiff](https://img.shields.io/badge/NVtiff-76B900?style=for-the-badge&logo=nvidia&logoColor=white)
![libtiff](https://img.shields.io/badge/libtiff-76B900?style=for-the-badge&logo=libtiff&logoColor=white)
![libcurl](https://img.shields.io/badge/libcurl-black?style=for-the-badge&logo=libcurl&logoColor=white)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=for-the-badge&logo=nvidia&logoColor=white)
![RUNPOD](https://img.shields.io/badge/RUNPOD-5D29F0?style=for-the-badge&logo=RUNPOD&logoColor=white)
![nlohmann/json](https://img.shields.io/badge/nlohmann/json-black?style=for-the-badge&logo=nlohmann/json&logoColor=white)

---

### Frontend
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=TypeScript&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-06B6D4?style=for-the-badge&logo=TailwindCSS&logoColor=white)
![Zustand](https://img.shields.io/badge/Zustand-000000?style=for-the-badge&logo=Zustand&logoColor=white)

---

### DevOps / Infra
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=Jenkins&logoColor=white)
![GitLab](https://img.shields.io/badge/GitLab-FC6D26?style=for-the-badge&logo=GitLab&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=Docker&logoColor=white)
![Docker hub](https://img.shields.io/badge/Docker_hub-2496ED?style=for-the-badge&logo=Docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=Nginx&logoColor=white)

---

### Tools
![IntelliJ IDEA](https://img.shields.io/badge/IntelliJ%20IDEA-000000?style=for-the-badge&logo=IntelliJIDEA&logoColor=white)
![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-3EAAF2?style=for-the-badge&logo=VisualStudioCode&logoColor=white)
![Visual Studio](https://img.shields.io/badge/Visual%20Studio-D29BFD?style=for-the-badge&logo=VisualStudio&logoColor=black)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=Figma&logoColor=white)
![Notion](https://img.shields.io/badge/Notion-F3F3F3?style=for-the-badge&logo=Notion&logoColor=black)

</div>

<br>

## 📌 주요 기능

<div align="center"> 
  <table border="1" cellspacing="0" cellpadding="5" 
         style="border-collapse: collapse; width: 100%; text-align: center; vertical-align: middle;">
    <thead> 
      <tr> 
        <th>로그인</th> 
        <th>대시보드</th> 
      </tr>
    </thead>
    <tbody>
      <tr> 
        <td><img width="100%" src="./gif/로그인.gif"/></td> 
        <td><img width="100%" src="./gif/대시보드.gif"/></td> 
      </tr>
      <tr> 
        <th>패턴 생성</th> 
        <th>패턴 생성 미리보기</th> 
      </tr>
      <tr> 
        <td><img width="100%" src="./gif/패턴생성.gif"/></td> 
        <td><img width="100%" src="./gif/패턴생성- 미리보기.gif"/></td> 
      </tr>
      <tr> 
        <th>csv 불러오기</th> 
        <th>성능 비교</th> 
      </tr>
      <tr> 
        <td><img width="100%" src="./gif/csv 불러오기.gif"/></td> 
        <td><img width="100%" src="./gif/성능비교.gif"/></td> 
      </tr>
      <tr> 
        <th>설비 등록</th> 
        <th>생성 시뮬레이션</th> 
      </tr>
      <tr> 
        <td><img width="100%" src="./gif/설비등록.gif"/></td> 
        <td><img width="100%" src="./gif/시뮬레이션.gif"/></td> 
      </tr>
      <tr> 
        <th>패턴 압축</th> 
      </tr>
      <tr> 
        <td><img width="100%" src="./gif/입측.gif"/></td> 
      </tr>
    </tbody>
  </table>
</div>

<br>

## 📁 프로젝트 산출물

### [시스템 아키텍처](./image/Architecture-Diagram.png)
[<img src="./image/Architecture-Diagram.png" width="700"/>](./readme/Architecture-Diagram.png)  


### [ERD (Entity Relationship Diagram)](./image/Entity%20Relationship%20Diagram.png)
[<img src="./image/Entity%20Relationship%20Diagram.png" width="700"/>](./readme/Entity%20Relationship%20Diagram.png)  


### [SWAGGER](./image/swagger-api.png)
[<img src="./image/swagger-api.png" width="700"/>](./image/swagger-api.png)  


### [JIRA](./image/jira.png)
[<img src="./image/jira.png" width="700"/>](./image/jira.png)  


### [API 명세서](https://www.notion.so/hwansu/28d8cbba0b6b800da8b9d015a79cd927)
[<img src="./image/api 명세서.png" width="700"/>](./image/api%20명세서.png)  

### [기능 명세서](https://www.notion.so/hwansu/28d8cbba0b6b800da8b9d015a79cd927)
[<img src="./image/기능 명세서.png" width="700"/>](./image/기능%20명세서.png)  


### [와이어프레임](https://www.figma.com/design/A5DXhea0ImQ2tgjLCOyNAo/S404?node-id=1613-294&p=f&t=0M6kKRCIeOsxDFzr-0)
[<img src="./image/와이어프레임.png" width="700"/>](./image/와이어프레임.png)


### [요구사항 정의서](https://www.notion.so/hwansu/28d8cbba0b6b801a9424c4a100928e5a?v=28d8cbba0b6b80658ecc000c00f8a34e)
[<img src="./image/요구사항 정의서.png" width="700"/>](./image/요구사항%20정의서.png)  

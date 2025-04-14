# **paperplane**

![paperplane 소개](https://github.com/user-attachments/assets/aa284791-1415-49af-88e9-3115d7e648b4)

> 대학생들을 위한 아이디어 공유 서비스, paperplane

---



## 목차

- [프로젝트 개요](#프로젝트-개요)
- [프로젝트 설명](#프로젝트-설명)
  1. [Backend Tech](#1-backend-tech)
  2. [Architecture](#2-architecture)
- [기능 설명](#기능-설명)
  1. [아이디어 작성 및 관리](#1-아이디어-작성-및-관리)
  2. [구매/판매](#2-구매판매)
  3. [다운로드](#3-다운로드)
- [기여](#기여)

---

## 프로젝트 개요

| 항목          | 내용                                                   |
|---------------|------------------------------------------------------|
| **프로젝트 소개** | 아이디어를 공유하고 거래하며 가치를 실현하는 플랫폼 **paperplane** |
| **개발 인원**    | 5명 (PM/디자인 1명 + 프론트엔드 2명 + 백엔드 2명)               |
| **개발 기간**    | 2024. 11. 17 ~ 2024. 11. 24                            |

---

## 프로젝트 설명

### 1. Backend Tech

| 기술             | 사용 기술                                                                 |
|------------------|------------------------------------------------------------------------|
| Language         | ![Java](https://img.shields.io/badge/Java-%23ED8B00.svg?style=for-the-badge&logo=java&logoColor=white) |
| Framework        | ![Spring Boot](https://img.shields.io/badge/Spring_Boot-%236DB33F.svg?style=for-the-badge&logo=spring-boot&logoColor=white) ![Gradle](https://img.shields.io/badge/Gradle-02303A.svg?style=for-the-badge&logo=Gradle&logoColor=white) |
| Database         | ![MySQL](https://img.shields.io/badge/MySQL-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white) |
| Deploy           | ![AWS EC2](https://img.shields.io/badge/Amazon%20EC2-%23FF9900.svg?style=for-the-badge&logo=amazon-ec2&logoColor=white) ![AWS RDS](https://img.shields.io/badge/Amazon%20RDS-527FFF?style=for-the-badge&logo=amazon-rds&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white) |
| Storage          | ![AWS S3](https://img.shields.io/badge/Amazon%20S3-%569A31.svg?style=for-the-badge&logo=amazon-s3&logoColor=white) |
| Reverse Proxy    | ![Nginx](https://img.shields.io/badge/Nginx-%23009639.svg?style=for-the-badge&logo=nginx&logoColor=white) |
| Containerization | ![Docker](https://img.shields.io/badge/Docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white) ![Docker Compose](https://img.shields.io/badge/Docker%20Compose-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white) |
| API              | ![Swagger](https://img.shields.io/badge/Swagger-%23Clojure.svg?style=for-the-badge&logo=swagger&logoColor=white) |
| Cooperative Tool | ![Git](https://img.shields.io/badge/Git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/GitHub-%23121011.svg?style=for-the-badge&logo=github&logoColor=white) |
| IDE              | ![IntelliJ IDEA](https://img.shields.io/badge/IntelliJ_IDEA-000000.svg?style=for-the-badge&logo=intellij-idea&logoColor=white) |

---

### 2. Architecture

![paperplane_BE_architecture drawio](https://github.com/user-attachments/assets/5cc6a844-81db-4b59-88c3-ebe24beb143e)


---

## 기능 설명

### 1. 아이디어 작성 및 관리

![paperplane-1](https://github.com/user-attachments/assets/827e9544-fb3c-43ec-ae6e-fe91cbcab14b)

- **아이디어 작성**: 제목, 카테고리, 설명, 태그, 가격을 입력하고 파일을 첨부하여 아이디어 작성
- **아이디어 수정**: 기존 아이디어 내용을 수정 가능
- **아이디어 삭제**: 본인이 작성한 아이디어를 삭제 가능
- **아이디어 검색**: 키워드, 카테고리, 태그를 기반으로 아이디어를 검색 가능


### 2. 구매/판매

![paperplane - 3](https://github.com/user-attachments/assets/02845a5a-412e-4c05-907e-9ff61dc77277)


- 아이디어를 다른 사용자와 거래
- 구매 내역 및 판매 내역 확인 가능
- 판매자에게 문의하기 기능 

### 3. 다운로드

![paperplane - 2](https://github.com/user-attachments/assets/4d55dc71-23f8-41ce-932c-625d096acfa5)

- 구매한 아이디어의 파일을 다운로드 가능
- 유저 권한 기반 파일 접근 제한
- 다운로드 후 후기 작성 기능
---

## 기여

- **아이디어 기능 구현**
    - 제목, 카테고리, 설명, 태그, 가격, 파일 첨부 포함 전체 작성/수정/삭제 기능 구현
- **검색 기능 구현**
    - 키워드, 카테고리, 태그 기반 필터링 로직 설계 및 개발
- **거래 시스템 개발**
    - 사용자 간 아이디어 구매/판매, 거래 내역 관리 기능 설계 및 구현
- **다운로드 기능 개발**
    - AWS S3 기반의 파일 업로드 및 다운로드 시스템 구축, 권한별 접근 제어 적용
- **CI/CD 파이프라인 설계 및 무중단 배포 적용**
    - AWS EC2, Docker Compose, Github actions, Nginx를 이용한 CI/CD 프로세스 자동화 및 Blue-Green 전략을 통한 무중단 배포 도입

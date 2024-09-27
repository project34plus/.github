# 📚 학술연구논문관리 플랫폼
## 프로젝트명: NonNull

## 목차
- [1. 프로젝트 소개](#1-프로젝트-소개)
    * [개발배경](#개발배경)
    * [주요기능](#주요기능)
    * [기대효과](#기대효과)
- [2. 개발환경 및 기술 스택](#2-개발환경-및-기술-스택)
- [3. 팀원 소개](#3-팀원-소개)
     * [역할 분담](#역할-분담)
- [4. UserFlow](#4-UserFlow)
- [5. 산출물](#5-산출물)
     * [기능 명세서](#기능-명세서)
     * [요구사항 정의서](#요구사항-정의서)
- [6. ERD](#6-ERD)
- [7. 프로젝트 일정표](#7-프로젝트-일정표)
- [8. 화면설계](#8-화면설계)

## 1. 프로젝트 소개
- 개발기간: 2024/09/02 ~ 2024/09/27 (총 4주)

- 배포 URL: &nbsp;&nbsp;http://nonnull.life/

### 📙 개발배경
&nbsp;&nbsp;NONNULL은 대학생, 교수, 학자 등 연구 활동을 하는 모든 사람을 대상으로 논문 및 연구자료를 체계적으로 관리하며 학술 연구를 진행하는 데 필요한 다양한 기능을 제공하는 웹 플랫폼입니다.  
NONNULL에서는 자신의 논문을 등록하여 여러 연구 활동에 공헌하고, 등록된 수많은 논문 자료를 공유함으로써 학문의 이해를 넓히는 데 도움을 주고자 합니다. 또한 관심 있는 논문을 찜하여 참고 자료를 빠르게 확인할 수 있으며, 댓글을 통해 다양한 의견을 나눌 수 있는 특별한 서비스를 제공합니다.  
&nbsp;&nbsp;이와 함께, 사용자의 검색 기록과 관심 분야를 기반으로 개인 맞춤형 논문을 추천하는 기능을 제공하여, 원하는 논문을 더 효율적으로 찾을 수 있도록 지원합니다. 또한, 학문 카테고리별 트렌드와 직업 그룹별 검색 기록 통계를 시각화하여 연구 활동에 필요한 다양한 정보를 제공합니다.


### 📘 주요기능
1. 회원정보 관리<br>
   - 기본 정보를 입력해 회원가입 및 로그인 기능을 이용할 수 있습니다.<br>
   - 마이페이지에서 회원정보, 전공, 관심분야를 수정할 수 있습니다.

3. 논문 관리<br>
   - 사용자가 저자, 기여자 포함, 파일 업로드, 공개여부 설정 등을 통해 논문을 등록하고, 관리자가 등록된 논문의 적절성을 검토하여 논문 등록을 승인하면 논문이 등록되고 최종 업로드가 완료됩니다.<br>
   - 논문 상세페이지에 댓글로 논문에 대한 의견을 입력할 수 있습니다.<br>
   - 논문 자료를 공개, 비공개 상태로 수정할 수 있습니다.

3. 논문 추천 및 검색<br>
   - 사용자의 검색 기록 통계, 관심분야, 전공분야를 바탕으로 개인 맞춤형 논문을 추천합니다.<br>
   - 학문 카테고리별 트렌드를 즐겨찾기, 조회수를 기준으로 막대 그래프로 시각화하여 제공합니다.<br>
   - 직업 그룹별로 검색기록 통계를 원형 그래프로 나타냅니다.

4. 메모 및 작업 관리<br>
   - 논문과 관련된 메모, 아이디어 노트를 기록할 수 있습니다.


### 📗 기대효과
- 논문 등록을 통해 신규 자료가 지속적으로 유입될 수 있습니다.
- 연구 트렌드 변화에 따른 정보를 제공하고, 유행 분야에 대한 정보를 확인할 수 있습니다.
- 관심있는 분야에 대한 논문을 추천하여 다양한 논문 자료를 제공합니다.
- 연구 노트에 구상한 아이디어를 바로 기록하여 아이디어 구체화에 도움을 줍니다.
- 고급 검색 기능을 통해 적절한 논문을 빠르게 탐색할 수 있습니다.


## 2. 개발환경 및 기술 스택
💙 Programming Languages  
&nbsp;&nbsp;<img src="https://img.shields.io/badge/Java-007396?style=flat&logo=Java&logoColor=white" />  

💎 Back-end Development  
&nbsp;&nbsp;<img src="https://img.shields.io/badge/Spring Boot-6DB33F?style=flat&logo=Spring Boot&logoColor=white" />
<img src="https://img.shields.io/badge/Spring-6DB33F?style=flat&logo=Spring&logoColor=white" />
<img src="https://img.shields.io/badge/Spring Security-6DB33F?style=flat&logo=Spring Security&logoColor=white" />
<img src="https://img.shields.io/badge/Gradle-02303A?style=flat&logo=Gradle&logoColor=white" />  

💎 Front-end Development  
&nbsp;&nbsp;<img src="https://img.shields.io/badge/next.js-000000?style=flat&logo=nextdotjs&logoColor=white" />
<img src="https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=CSS3&logoColor=white" />
<img src="https://img.shields.io/badge/React-61DAFB?style=flat&logo=React&logoColor=black" />
<img src="https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=HTML5&logoColor=white" />
<img src="https://img.shields.io/badge/javascript-F7DF1E?style=flat&logo=javascript&logoColor=black" />  

💎 Database  
&nbsp;&nbsp;<img src="https://img.shields.io/badge/Oracle-F80000?style=flat&logo=Oracle&logoColor=white" />
<img src="https://img.shields.io/badge/dbeaver-382923?style=flat&logo=dbeaver&logoColor=white" />  

💙 Devops  
&nbsp;&nbsp;<img src="https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonwebservices&logoColor=white" />
<img src="https://img.shields.io/badge/jenkins-D24939?style=flat&logo=jenkins&logoColor=white" />
<img src="https://img.shields.io/badge/docker-2496ED?style=flat&logo=docker&logoColor=white" />  

## 3. 팀원 소개
|<img src="https://avatars.githubusercontent.com/u/163953938?v=4" width="150" height="150"/>|<img src="https://avatars.githubusercontent.com/u/132132524?v=4" width="150" height="150"/>|<img src="https://avatars.githubusercontent.com/u/136600208?v=4" width="150" height="150"/>|<img src="https://avatars.githubusercontent.com/u/154653812?v=4" width="150" height="150"/>|
|:-:|:-:|:-:|:-:|
|[@hyeon12](https://github.com/hyeon12)|[@heyejiyang](https://github.com/heyejiyang)|[@kth232](https://github.com/kth232)|[@soeunl](https://github.com/soeunl)|

|<img src="https://avatars.githubusercontent.com/u/163953821?v=4" width="150" height="150"/>|<img src="https://avatars.githubusercontent.com/u/145332250?v=4" width="150" height="150"/>|<img src="https://avatars.githubusercontent.com/u/134360817?v=4" width="150" height="150"/>|<img src="https://avatars.githubusercontent.com/u/163953823?v=4" width="150" height="150"/>|
|:-:|:-:|:-:|:-:|
|[@youngsan01](https://github.com/youngsan01)|[@inseokLee999](https://github.com/inseokLee999)|[@jangjangji](https://github.com/jangjangji)|[@minsukim002](https://github.com/minsukim002)|

### 역할 분담
| 팀원 | 역할 |
|-----------|---------|
| 서정현 |인기순/ 최신순 논문 트렌드 조회기능<br>학문별/그룹별로 트렌디한 논문 조회, 시각화 자료 제공|
| 양예지 |내 논문 관리 / 개인 논문 서비스<br>등록한 논문 조회, 수정, 삭제<br>즐겨찾기한 논문 목록 확인하기|
| 강태현 |전체 논문 목록 조회, 논문 상세 조회<br>다운로드 및 댓글 달기 기능 구현<br>논문 조건별 고급 검색 기능|
| 이소은 |메인화면 구성, 서브메뉴 경로 연결<br>로그인 및 회원가입<br>회원 정보 조회, 수정, 탈퇴<br>관리자 페이지 회원 관리|
| 김영산 |연구 노트 작성, 조회|
| 이인석 |개인 사용자의 논문 데이터 이용 기록 저장 기능<br>사용자 이용 기록 기반 논문 추천 알고리즘 및 알림 기능 구현|
| 장성준 |논문 등록 및 수정 프로세스 구현<br>관리자 페이지 논문 등록 관리 기능 구현|
| 김민수 |연구 노트 작성, 조회|

## 4. UserFlow
![flowchart](https://github.com/user-attachments/assets/0976e94a-0f97-481b-a771-2809a5f39bed)

## 5. 산출물
### 📃 기능 명세서
![image](https://github.com/user-attachments/assets/39baf6bc-16ef-45d1-a73d-a0437dea08fb)

### 📋 요구사항 정의서
![요구사항 정의서](https://github.com/user-attachments/assets/9daf6690-0ea3-4d7a-818c-519c30b35738)

## 6. ERD
![project5_502_MSA2](https://github.com/user-attachments/assets/633874e7-6be8-4c70-a38a-3e0742f14b70)

## 7. 프로젝트 일정표
![KakaoTalk_20240925_143517211](https://github.com/user-attachments/assets/91e786c3-3db4-40e5-9b64-26a411f5ddaa)

## 8. 화면설계
![화면정의서](https://github.com/user-attachments/assets/3e73d18f-c935-4027-9c7c-dd92e7e8ea55)

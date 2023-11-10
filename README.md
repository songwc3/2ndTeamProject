![2차 로고](https://github.com/songwc3/2ndTeamProject/assets/133622405/f30f241b-cab8-4978-868b-d886c5a7c7b0)

# 🏢2차 팀프로젝트 : 사내 그룹웨어 만들기 - 그린컴퓨터아카데미🏢
<br/>

## 📌프로젝트 개요
- 개발기간 : 2023. 09. 26 ~ 2023. 10. 26 <br/>
- 주제선정이유 : 직접 다니고있는만큼 다른 주제에 비해 더 익숙하고 학원의 전반적인 시스템에 대해
  익힐수 있는 기회라고 생각해서 학원이라는 주제를 선택했습니다.

## 📂프로젝트 소개
- 학원의 임직원들이 각자의 출/퇴근을 기록하고, 일정 관리, 급여/근태 관리, 수강생 관리,
  그리고 관리자 권한의 경우 사원 관리를 할 수 있는 학원의 사내 그룹웨어입니다.
- Open API(일정과 우편번호)를 활용했습니다.
- Github Actions와 AWS EC2를 이용해 CI/CD 환경을 구축했습니다.
<details>
<summary>메인페이지</summary>

![메인페이지](https://github.com/songwc3/2ndTeamProject/assets/133622405/4c984a66-730c-4074-807b-bfeb5614e6b9)
</details>

## 💻개발환경
- Language : Java11, Javascript, HTML5, CSS3
- Framework : Spring boot
- IDE : IntelliJ IDEA
- Template Engine : Thymeleaf
- Database : MySQL
- ORM : JPA
- Version Management : Git, Github


## 📑DB 구조
<details>
<summary>상세보기(담당한 부분)</summary>

- 사원(Employee) <br/>
  &nbsp;사원 당 하나의 프로필 사진만 등록가능하도록 설정했습니다. <br/>
  &nbsp;사원은 여러번의 출석 기록을 가질수있도록 설정했습니다. <br/>
  &nbsp;사원은 여러번의 결재 문서를 작성할수있도록 설정했습니다. <br/>
  &nbsp;사원은 다수의 결재자를 등록할수있도록 설정했습니다. <br/><br/>

- 수강생(Student) <br/>
  &nbsp;수강생 당 하나의 프로필 사진만 등록가능하도록 설정했습니다. <br/>
  &nbsp;수강생은 여러번의 출석 기록을 가질수있도록 설정했습니다. <br/><br/>
[2차팀프로젝트 DB.pdf](https://github.com/songwc3/2ndTeamProject/files/13314221/2.DB.pdf)
![DB ERD](https://github.com/songwc3/2ndTeamProject/assets/133622405/6f17b3c0-cbf9-4502-9a01-5a34882f6273)
</details>


## 🏓팀 구성 및 역할
### 😃팀원 송원철

<br/>

- 로그인(Spring Security)
<details>
<summary>상세보기</summary>


</details>

<br/>

- 페이지별 권한 및 보안 설정(관리자, 일반사원 별 인사조회 화면 차등)
<details>
<summary>상세보기</summary>


</details>

<br/>

- 사원 및 수강생 CRUD
<details>
<summary>상세보기</summary>


</details>

<br/>

- 네이버 API를 이용한 조직도 불러오기
<details>
<summary>상세보기</summary>


</details>

<br/>

- 팀 PPT 작성

<br/>

팀장 김** : 게시판 및 공지사항 관리 <br/>
팀원 노** : 결재 관리, CI/CD <br/>
팀원 박** : 프론트엔드, Fullcalendar API 이용한 일정 관리 <br/>
팀원 이** : 근태 및 급여 관리
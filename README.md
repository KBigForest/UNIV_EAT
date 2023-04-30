## [프로젝트] 밥밥디라라 UNIV_EAT

### 목차
#### 1. [프로젝트 소개](#프로젝트-소개)
##### (1) 기획의도 및 목적
##### (2) 멤버구성 및 역할
##### (3) 개발 기간
##### (4) 개발 방향성 및 범위
##### (5) 필요 기술 스택 및 개발 환경
#### 2. [프로젝트 세부내용](프로젝트-세부내용)
##### (1) 구현 기능
##### (2) 배운점 & 아쉬운 점
##### (3) 이후의 계획
<br><br>
---

### 프로젝트 소개

#### (1) 기획의도 및 목적
* 목적: 홈페이지를 들어가서 확인하는 번거로움을 줄이기 위해 제작
* 실생활에서 내가 필요한 기능을 실제로 제작하는 경험을 만들고 싶었음.
                                 
#### (2) 멤버구성 및 역할
본인(1명): 크롤링, 기획 및 간단한 디자인 

#### (3) 개발 기간
23.02.15 - 23.04.17 (총 4시간)

#### (4) 개발 방향성 및 범위
* 경북대 생활협동조합 홈페이지 각 홈페이지 크롤링
* tkinter를 통한 레이아웃 디자인 후 application exe파일성생성

#### (5) 개발 환경 및 필요 기술 스택
- Environment<br><img src="https://img.shields.io/badge/windows-0078D6?style=for-the-badge&logo=windows&logoColor=white"/><br><img src="https://img.shields.io/badge/visualstudiocode-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white"/>
- Development
  * tkinter
  * beautifulsoup

---
### 2. 프로젝트 세부내용

#### (1) 구현 기능

<img width="476" alt="bobbobdirara_project" src="https://user-images.githubusercontent.com/99776305/235340511-412e3ab6-53ea-4229-82ba-86c53919a9ad.png">

  * 크롤링 파트
    - url : https://coop.knu.ac.kr/sub03/sub01_01.html?shop_sqno={}
    - {}에 들어가는 숫자에 따라 해당되는 식당이 바뀜
      - 카페테리아 첨성 : 37
      - GP감꽃푸드코트 : 46
      - 공학관교직원식당(외부업체) : 85
    - beautifulsoup를 활용하여 단순 html 파싱을 통해서 식단 가져오기 가능
    
  * 레이아웃
    - 버튼 : 해당 버튼 왼쪽에 위치
      - 공대식당
      - GP
      - 복지관
      - 나가기
    - 메뉴 출력
      - 버튼 클릭 시 오른쪽에 메뉴 출력
    - header 및 프로그램 아이콘, 배경 밥모양으로 설정
    - exe화
    
#### (2) 배운점 & 아쉬운 점
  * 이 당시 가상환경의 중요성과 사용법에 대한 이해가 부족했음.
  * 결과적으로 해당 파일이 가진 기능에 비해 용량이 매우 커졌으며(300MB) 실행에 걸리는 시간이 오래 걸림
  * 이제는 해당 사항에 대해 알고 있으며 가상환경 설정만으로도 해당 문제 해결 가능 및 향후 배포 역시 가능
  
#### (3) 이후의 계획
  * 앞에서의 문제점 해결
  * 보완점 개선 후 학교 학생 및 행정 직원에게 배포


# 사업용 차량:truck: 안전 운행 분석

### :art:개요
- 사업용 차량의 운행 기록 데이터를 바탕으로 안전 운행에 대한 분석을 실시하고, 차량별 운전 위험도를 알려주는 서비스이다.

### 기획 배경(프로젝트가 해결하려고 하는 문제)
- 사업용 차량의 관리 서비스를 제작한다.
- 사업용 차량(트럭, 버스 등)은 같은 노선을 반복적으로 운행하며, 동일한 유형의 데이터가 쌓이므로 분석하여, 차량 관리를 효율적으로 할 수 있다.
- 많은 사업용 차량의 관리를 데이터 분석을 통해서 안전 운행을 하는지 진단 할 수있다.

### 프로젝트 목표(프로젝트가 미칠 영향)
- 문제 해결 역량을 발휘하여 어플리케이션을 기획한다.
- SW 개발을 통해 원하는 서비스를 구현한다.
- 팀 프로젝트를 수행하며 협업 역량을 키운다.

### 서비스 특징
- 차량 운행 기록 데이터를 분석해서 일정 기간 동안 차량별 운행의 안전도를 평가한다.
- 지도에서 모의주행을 하며 위험 또는 돌발 구간을 알 수 있다.
- 차량별 운전자의 운전습관 평가와 운행의 안전도를 분석할 것으로 기대 된다.

### Project
- 2023.01.11 ~ 2023.02.09
- [Github - FrontEnd](https://github.com/K-Digital-Team4/Front_End)
- [Github - BackEnd](https://github.com/K-Digital-Team4/BackEnd)
- [Github - DataAnalysis](https://github.com/K-Digital-Team4/Data-analysis)

--- 
</br>

## :memo:차례  
1. [팀원 소개]
2. [주요 기술 스택] :hammer:
3. [ERD] :wrench:
4. [서비스 소개] :package:
5. [규칙] :bulb:
6. [시작하기] :tada:
</br></br>
### 1. [팀원 소개]
--- 

- **김민수**  - Front_end - https://github.com/Minsu0207  
- **진주호** - Data_Analysis - https://github.com/juho-jin  
- **박경관** - back_end, DB - https://github.com/kyunggwan  
- **김찬준** - back_end, DB - https://github.com/ckswns879  
</br></br>
### 2. [주요 기술 스택]:hammer:

--- 
- FrontEnd
<img src="https://img.shields.io/badge/ Figma-F24E1E?style=flat-square&logo=Figma&logoColor=ffffff" /> <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=React&logoColor=ffffff"/> 

- BackEnd
<img src="https://img.shields.io/badge/Spring Boot-6DB33F?style=flat-square&logo=SpringBoot&logoColor=ffffff" /> <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=MySQL&logoColor=ffffff" /> <img src="https://img.shields.io/badge/Amazon S3-569A31?style=flat-square&logo=Amazon S3&logoColor=ffffff" /> <img src="https://img.shields.io/badge/Amazon RDS-527FFF?style=flat-square&logo=Amazon RDS&logoColor=ffffff" /> <img src="https://img.shields.io/badge/Amazon EC2-FF9900?style=flat-square&logo=Amazon EC2&logoColor=ffffff" />

- Collaboration Tools
 <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=GitHub" />  <img src="https://img.shields.io/badge/Miro-yellow?style=flat-square&logo=Miro&logoColor=000000" /> <img src="https://img.shields.io/badge/ Google Sheets-34A853?style=flat-square&logo=Google Sheets&logoColor=ffffff" /> 
</br></br>

### 3. [ERD] :wrench:
--- 
![ERD](https://user-images.githubusercontent.com/113881846/218421285-ea00b0e1-8270-44b8-b012-99c15590556b.png)
</br></br>
### 4. [서비스 소개] :package:
--- 
##### FrontEnd 주요 버전
```cmd
프론트엔드 주요 버전
1. react : 18.2.0
2. next : 12.3.1
3. axios: 0.27.2
4. Visual Studio : 1.71.0

```

#### BackEnd 주요 버전
```cmd
1. JVM : 1.8.0_192
2. WAS : apache-tomcat-9.0.71
3. IntelliJ : IntelliJ IDEA 2021.3.2 (ultimate)
4. springBootVer : '3.0.1'
5. AWS RDS: 8.0.31
6. ubuntu: 20.04 LTS
7. JAVA: 17
8. 기타 상세 버전 정보
    - SpringBoot : build 도구 Maven 3.0.1
```
</br></br>
### 5. [협업 규칙] :bulb:
---
1. 네이밍 규칙
- 클래스/컴포넌트/인터페이스/메소드 : PascalCase(파스칼 표기법)
- 오브젝트/함수/인스턴스/변수/파라미터 : camelCalse(카멜 표기법)
</br></br>
2. Git Convention
- [태그: 제목] 형태이며 : 뒤에만 space가 있음을 유의한다.
- Feat: 새로운 기능 추가
- Fix: 버그 수정
- Docs: 문서 수정
- Style: 코드 포맷팅, 세미콜론 누락, 코드 변경이 없는 경우
- Refactor: 코드 리펙토링
- Chore: 빌드 업무 수정, 패키지 매니저 수정
- Design: 디자인 수정
- Remove: 파일 삭제
- Rename: 파일명 변경
</br></br>
3. Git Commit 예시
```cmd
- Docs: README추가
- Remove: 명세서 파일 삭제
- Feat: 간단한 필터 적용
- Refactor: upgrade gradle version to 5.2.1
- Rename: 파일명 변경
```

### 6. [시작하기] :tada:
--- 
```cmd
# /backend/
$ java -jar project.jar

# /frontend/
$ npm install
$ npm start
```
</br></br>



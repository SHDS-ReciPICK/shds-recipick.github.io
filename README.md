<div align="center">

<img height="150px" alt="ReciPICK Logo" src="./logo/recipick-logo.svg">

<p>레시피 기반 식재료 쇼핑몰 서비스</p>

<p>
  <a href="#-프로젝트-소개">📌 프로젝트 소개</a> •
  <a href="#-주요-기능">✨ 주요 기능</a> •
  <a href="#-기술-스택">🛠 기술 스택</a> •
  <a href="#-team">👨‍👩‍👧‍👦 팀 소개</a> •
  <a href="#-문서">📄 문서</a> •
  <a href="#-협업">🤝 협업</a>
</p>

</div>

---

## 📌 프로젝트 소개

### 💡 주제
**ReciPICK** - 레시피 기반 식재료 쇼핑몰 서비스

### 📝 개요
- ReciPICK은 '레시피(Recipe)'와 '선택(Pick)'의 합성어로, 요리 초보자를 위한 레시피 기반 통합 식재료 쇼핑 플랫폼입니다.
- 레시피 구매 시 필요한 모든 식재료를 한 번에 담을 수 있고, 취향에 맞게 재료를 조절할 수 있습니다.
- 커뮤니티를 통해 나만의 레시피를 공유하고 소통할 수 있습니다.

### ⏱️ 개발 기간
**2024.12 ~ 2025.01**

### 🎬 시연 영상
[👉 ReciPICK 시연 영상](https://drive.google.com/file/d/1biBtG8z56AI29OchepA8-6I38P7zaO7y/view?usp=sharing)

### 💾 Repository
[1️⃣ ReciPICK Repository](https://github.com/SHDS-ReciPICK/recipick) <br/><br/>
[2️⃣ SOL PICK 연동을 위한 ReciPICK API 추가 개발한 Repository](https://github.com/SHDS-ReciPICK/recipick-v2)

### 🏗️ 디렉토리 구조
```
ReciPICK/
├── src/main/java/
│   ├── kr/co/recipick/
│   │   ├── cart/           # 장바구니 관리
│   │   ├── checkout/       # 주문/결제
│   │   ├── community/      # 커뮤니티
│   │   ├── dashboard/      # 관리자 페이지
│   │   ├── home/          # 메인 페이지
│   │   ├── item/          # 상품 상세
│   │   ├── member/        # 회원 관리
│   │   └── product/       # 상품 목록
│   ├── config/            # 설정 파일
│   └── util/              # 유틸리티
├── src/main/resources/
│   └── kr/co/recipick/    # MyBatis Mapper
├── src/main/webapp/
│   ├── WEB-INF/views/     # JSP 뷰
│   ├── css/               # 스타일시트
│   ├── js/                # JavaScript
│   └── libs/              # 외부 라이브러리
```
---

## ✨ 주요 기능

### 1. 👥 회원 관리 시스템
- 이메일 기반 회원 가입 및 로그인 기능
- 회원 인증/인가 처리
- 개인 정보 관리(마이페이지에서 주분/배송 조회, 좋아요 목록 확인, 리뷰 관리 진행 가능)<br/>


  <table>
    <tr>
      <td align="center" width="450"><b>로그인 페이지</b></td>
      <td align="center" width="450"><b>주문/배송 조회 페이지</b></td>
    </tr>
    <tr>
      <td align="center" height="250">
        <img width="450" alt="로그인 페이지" src="https://github.com/user-attachments/assets/c83c1fe4-a97b-427a-8a63-528e69d53669" />
      </td>
      <td align="center" height="250">
        <img width="450" alt="주문/배송 조회 페이지" src="https://github.com/user-attachments/assets/2ac5aecf-7997-4183-8c5e-b3a6a9e62b92" />
      </td>
    </tr>
    <tr>
      <td align="center" width="450"><b>좋아요 페이지</b></td>
      <td align="center" width="450"><b>리뷰 관리 페이지</b></td>
    </tr>
    <tr>
      <td align="center" height="250">
        <img width="450" alt="좋아요 페이지" src="https://github.com/user-attachments/assets/915bdc2f-4118-402a-8c29-af0accf96c3d" />
      </td>
      <td align="center" height="250">
        <img width="450" alt="리뷰 관리 페이지" src="https://github.com/user-attachments/assets/94f791d6-32ff-43bd-ad4d-aa6c71245249" />
      </td>
    </tr>
  </table>
  
### 2. 🍳 레시피/식재료 검색 및 조회
- 레시피 및 식재료 통합 검색 기능 (제목, 내용, 태그)
- 다중 기준 정렬 기능 (인기순, 신상품순, 평점순, 리뷰많은순 등)
- 다중 조건 필터링 기능 (카테고리, 가격대, 평점 등)
- 페이징 기능
- 동적 가격 계산 시스템 (식재료별 할인율 적용 후 레시피에 대한 가격 산출)
- 검색 결과, 필터, 정렬 조건에 따른 상품 목록 동적 렌더링

  <table>
    <tr>
      <td align="center" width="500"><b>홈 페이지</b></td>
      <td align="center" width="500"><b>상품 목록</b></td>
      <td align="center" width="500"><b>검색 결과, 필터, 정렬 조건에 따른 상품 목록 조회</b></td>
    </tr>
    <tr>
      <td align="center" height="250">
        <img width="500" alt="홈 페이지" src="https://github.com/user-attachments/assets/a83bbf39-3ff3-4725-a252-13e969156c1f" />
      </td>
      <td align="center" height="250">
        <img width="500" alt="상품 목록" src="https://github.com/user-attachments/assets/07ff5aa0-017f-46bf-8e84-2447223cb7f9" />
      </td>
      <td align="center" height="250">
        <img width="500" alt="동적 상품 목록 렌더링" src="https://github.com/user-attachments/assets/dd905836-2171-406c-a550-b1b3a877e3c8" />
      </td>
    </tr>
  </table>

### 3. 🛒 장바구니 시스템 및 결제 프로세스 구현
- 장바구니에 레시피 상품 담을 시 포함된 식재료 함께 담기 기능
- 상품 옵션 수량 조절 및 삭제 기능
- 식재료 품절 시 알림 기능
- 아임포트 결제 시스템 연동
  
  <table>
    <tr>
      <td align="center" width="450"><b>레시피 상세 페이지</b></td>
      <td align="center" width="450"><b>장바구니 페이지</b></td>
    </tr>
    <tr>
      <td align="center" height="250">
        <img width="450" alt="레시피 상세 페이지" src="https://github.com/user-attachments/assets/262bf84e-6dab-45a8-a6d3-0e1d66defa9b" />
      </td>
      <td align="center" height="250">
        <img width="450" alt="장바구니 페이지" src="https://github.com/user-attachments/assets/6f1100a5-1f74-4847-bed5-d4a9a44158a5" />
      </td>
    </tr>
    <tr>
      <td align="center" width="250"><b>레시피 담을 시 식재료 수량 조절</b></td>
      <td align="center" width="250"><b>아임포트 결제 시스템 연동</b></td>
    </tr>
    <tr>
      <td align="center" height="250">
        <img width="450" alt="레시피 담을 시 식재료 수량 조절" src="https://github.com/user-attachments/assets/8ab84437-adff-471e-a0c1-31863deaec1c" />
      </td>
      <td align="center" height="250">
        <img width="450" alt="아임포트 결제 시스템 연동" src="https://github.com/user-attachments/assets/db91b819-23a0-4e3f-9c88-6c356f1a84ab" />
      </td>
    </tr>
  </table>

### 4. 📋 커뮤니티 게시판 서비스
- 사용자 게시글 CRUD 기능
- 사용자 이미지 업로드 처리
- 사용자 댓글 CRUD 기능

  <table>
    <tr>
      <td align="center" width="600"><b>게시판 목록(나만의 레시피)</b></td>
      <td align="center" width="600"><b>게시글 상세 페이지</b></td>
    </tr>
    <tr>
      <td align="center" height="300">
        <img width="600" alt="게시판 목록(나만의 레시피)" src="https://github.com/user-attachments/assets/eb41b608-1b9f-4834-bfa4-bb307253dde5" />
      </td>
      <td align="center" height="30">
        <img width="600" alt="게시글 상세 페이지" src="https://github.com/user-attachments/assets/3559067a-dd28-4b10-9be1-4c7d86a9d7b8" />
      </td>
    </tr>
  </table>

### 5. 관리자 대시보드 시스템
- 관리자 레시피 CRUD 기능 (등록/수정/삭제)
- 관리자 식재료 CRUD 기능 (등록/수정/삭제)
- 식재료 재고 관리 기능

  <table>
    <tr>
      <td align="center" width="450"><b>새 레시피 추가 페이지</b></td>
      <td align="center" width="450"><b>새 식재료 추가 페이지</b></td>
    </tr>
    <tr>
      <td align="center" height="250">
        <img width="450" alt="새 레시피 추가 페이지" src="https://github.com/user-attachments/assets/3864428f-df41-417b-a71b-f9cd22ecb617" />
      </td>
      <td align="center" height="250">
        <img width="450" alt="새 식재료 추가 페이지" src="https://github.com/user-attachments/assets/b19fb625-26d5-4ddf-8ff3-84e9e8d9f97c" />
      </td>
    </tr>
    <tr>
      <td align="center" width="450"><b>레시피 삭제 페이지</b></td>
      <td align="center" width="450"><b>식재료 재고 관리 페이지</b></td>
    </tr>
    <tr>
      <td align="center" height="250">
        <img width="450" alt="레시피 삭제 페이지" src="https://github.com/user-attachments/assets/950a4f23-d42f-4f76-b178-c3e0ce2269ba" />
      </td>
      <td align="center" height="250">
        <img width="450" alt="식재료 재고 관리 페이지" src="https://github.com/user-attachments/assets/d674456a-ad2c-4c12-8e96-76067ea149b3" />
      </td>
    </tr>
  </table>
  
---

## 🛠 기술 스택

### 💻 Frontend
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![jQuery](https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)
![JSP](https://img.shields.io/badge/JSP-007396?style=for-the-badge&logo=java&logoColor=white)

### 🖥 Backend
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring](https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![Spring MVC](https://img.shields.io/badge/Spring_MVC-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![MyBatis](https://img.shields.io/badge/MyBatis-271E1A?style=for-the-badge&logo=mybatis&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white)
![Apache Tomcat](https://img.shields.io/badge/Apache_Tomcat-F8DC75?style=for-the-badge&logo=apachetomcat&logoColor=black)

### 🗃 Database
![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=for-the-badge&logo=mariadb&logoColor=white)
![HikariCP](https://img.shields.io/badge/HikariCP-007DB8?style=for-the-badge&logo=postgresql&logoColor=white)

### 🤝 Collaboration
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Eclipse](https://img.shields.io/badge/Eclipse-2C2255?style=for-the-badge&logo=eclipse&logoColor=white)

## 📚 Additional Libraries
![Lombok](https://img.shields.io/badge/Lombok-BC4521?style=for-the-badge&logo=lombok&logoColor=white)
![JSTL](https://img.shields.io/badge/JSTL-007396?style=for-the-badge&logo=java&logoColor=white)
![Tiny Slider](https://img.shields.io/badge/Tiny_Slider-FF6B6B?style=for-the-badge&logo=javascript&logoColor=white)
![NoUISlider](https://img.shields.io/badge/NoUISlider-4ECDC4?style=for-the-badge&logo=javascript&logoColor=white)
![SimpleBar](https://img.shields.io/badge/SimpleBar-45B7D1?style=for-the-badge&logo=javascript&logoColor=white)

---

## 👨‍👩‍👧‍👦 Team

<div align="center">
  <table>
    <tr>
      <td align="center">
        <img src="https://github.com/jrkim-kr.png" width="120px" height="120px" style="border-radius: 50%"/><br/>
      </td>
      <td align="center">
        <img src="https://github.com/eko147.png" width="120px" height="120px" style="border-radius: 50%"/><br/>
      </td>
      <td align="center">
        <img src="https://github.com/jinyoung1221.png" width="120px" height="120px" style="border-radius: 50%"/><br/>
      </td>
      <td align="center">
        <img src="https://github.com/ayeooong.png" width="120px" height="120px" style="border-radius: 50%"/><br/>
      </td>
      <td align="center">
        <img src="https://github.com/suemer1324.png" width="120px" height="120px" style="border-radius: 50%"/><br/>
      </td>
    </tr>
    <tr>
      <td align="center"><b>김정란</b><br/></td>
      <td align="center"><b>고은지</b><br/></td>
      <td align="center"><b>양진영</b><br/></td>
      <td align="center"><b>임아영</b><br/></td>
      <td align="center"><b>최대욱</b><br/></td>
    </tr>
    <tr>
      <td align="center">팀장 / FE & BE<br/>
        레시피 및 식재료 검색 및 조회<br/>
      </td>
      <td align="center">팀원 / FE & BE<br/>
        장바구니 시스템 및 결제 프로세스<br/>
      </td>
      <td align="center">팀원 / FE & BE<br/>
        회원 관리 시스템<br/>
      </td>
      <td align="center">팀원 / FE & BE & 디자인 <br/>
        커뮤니티 게시판<br/>       
      </td>
      <td align="center">팀원 / FE & BE<br/>
        관리자 대시보드 시스템<br/>       
      </td>
    </tr>
    <tr>
      <td align="center"><a href="https://github.com/jrkim-kr">GitHub</a></td>
      <td align="center"><a href="https://github.com/eko147">GitHub</a></td>
      <td align="center"><a href="https://github.com/jinyoung1221">GitHub</a></td>
      <td align="center"><a href="https://github.com/ayeooong">GitHub</a></td>
      <td align="center"><a href="https://github.com/suemer1324">GitHub</a></td>
    </tr>
  </table>
</div>

---

## 📄 문서

- 📕 [ERD 설계도](https://www.erdcloud.com/d/ydoYdYqYkTHm9RWGa)
- 📙 [화면 설계서]()
- 📘 [기능 명세서]()

---

## 🤝 협업

### 📋 Notion을 활용한 프로젝트 관리
[팀 프로젝트 노션 페이지](https://hongsherry.notion.site/ReciPICK-144341dc2a9380b28c7ad1a0e69ab591)

<table>
  <tr>
    <td align="center" width="400"><b>팀 정보 관리</b></td>
    <td align="center" width="400"><b>프로젝트 타스크 관리</b></td>
    <td align="center" width="400"><b>문서 관리</b></td>
  </tr>
  <tr>
    <td>
      <img width="400" alt="팀 정보" src="https://github.com/user-attachments/assets/ab1b1e4b-bde4-4b50-bb0b-a8644adf9afd" />
    </td>
    <td>
      <img width="400" alt="타스크" src="https://github.com/user-attachments/assets/91c8b0d9-eb35-4bcf-bef3-bc4d1607870b" />
    </td>
    <td>
      <img width="400" alt="문서 관리" src="https://github.com/user-attachments/assets/e123d367-d330-46ad-a215-526cbbcc675a" />
    </td>
  </tr>
  <tr>   
    <td align="center" width="400"><b>회의록</b></td>
    <td align="center" width="400"><b>데일리 스크럼 관리</b></td>
    <td></td>
  </tr>
  <tr>
    <td>
      <img width="400" alt="회의록" src="https://github.com/user-attachments/assets/be7aa982-7558-4104-9a62-1a832b2062f2" />
    </td>
    <td>
      <img width="400" alt="데일리 스크럼" src="https://github.com/user-attachments/assets/042e3d28-2122-4911-b6bb-d34ee6ba7906" />
    </td>
    <td></td>
  </tr>
</table>

### 💬 Discord 채널을 통한 소통

<table>
  <tr>
    <td align="center"><b>일정 공지</b></td>
    <td align="center"><b>컨벤션</b></td>
    <td align="center"><b>사용법</b></td>
  </tr>
  <tr>
    <td>
      <img width="400" alt="일정 공지" src="https://github.com/user-attachments/assets/f8e92041-9c2b-47f2-a28a-b191c548f6ca" />
    </td>
    <td>
      <img width="400" alt="컨벤션" src="https://github.com/user-attachments/assets/73ee2652-b356-4f4c-aa79-966b5e104fce" />
    </td>
    <td>
      <img width="400" alt="사용법" src="https://github.com/user-attachments/assets/8ef5d5b5-73ca-455d-a32d-62c03f1ce5ec" />
    </td>
  </tr>
  <tr>
    <td align="center"><b>협업툴</b></td>
    <td align="center"><b>Github 연동</b></td>
    <td></td>
  </tr>
  <tr>
    <td>
      <img width="400" alt="협업툴" src="https://github.com/user-attachments/assets/c0a1996f-1b69-418f-9c89-f5cf2678472d" />
    </td>
    <td>
      <img width="400" alt="Github 연동" src="https://github.com/user-attachments/assets/0022c9d8-5178-4d2e-9305-cd264ab5c60d" />
    </td>
    <td></td>
  </tr>
</table>

---

<div align="center">
  <sub>ⓒ 2023 ReciPICK Team. All rights reserved.</sub>
</div>

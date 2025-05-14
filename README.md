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

---

## ✨ 주요 기능

### 1. 👥 회원 관리 시스템
- 이메일 기반 회원 가입 및 로그인 기능
- 회원 인증/인가 처리
- 개인 정보 관리(마이페이지에서 주분/배송 조회, 좋아요 목록 확인, 리뷰 관리 진행 가능)<br/>


  <table>
    <tr>
      <td align="center" width="320"><b>로그인 페이지</b></td>
      <td align="center" width="320"><b>주문/배송 조회 페이지</b></td>
    </tr>
    <tr>
      <td align="center" height="450">
        <img width="250" alt="로그인 페이지" src="" />
      </td>
      <td align="center" height="450">
        <img width="250" alt="주문/배송 조회 페이지" src="" />
      </td>
    </tr>
    <tr>
      <td align="center" width="320"><b>좋아요 페이지</b></td>
      <td align="center" width="320"><b>리뷰 관리 페이지</b></td>
    </tr>
    <tr>
      <td align="center" height="450">
        <img width="250" alt="좋아요 페이지" src="" />
      </td>
      <td align="center" height="450">
        <img width="250" alt="리뷰 관리 페이지" src="" />
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
      <td align="center" width="320"><b>홈 페이지</b></td>
      <td align="center" width="320"><b>상품 목록</b></td>
      <td align="center" width="320"><b>검색 결과, 필터, 정렬 조건에 따른 상품 목록 조회</b></td>
    </tr>
    <tr>
      <td align="center" height="450">
        <img width="250" alt="홈 페이지" src="" />
      </td>
      <td align="center" height="450">
        <img width="250" alt="상품 목록" src="" />
      </td>
      <td align="center" height="450">
        <img width="250" alt="동적 상품 목록 렌더링" src="" />
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
      <td align="center" width="320"><b>레시피 상세 페이지</b></td>
      <td align="center" width="320"><b>장바구니 페이지</b></td>
    </tr>
    <tr>
      <td align="center" height="450">
        <img width="250" alt="레시피 상세 페이지" src="" />
      </td>
      <td align="center" height="450">
        <img width="250" alt="장바구니 페이지" src="" />
      </td>
    </tr>
    <tr>
      <td align="center" width="320"><b>레시피 담을 시 식재료 수량 조절</b></td>
      <td align="center" width="320"><b>아임포트 결제 시스템 연동</b></td>
    </tr>
    <tr>
      <td align="center" height="450">
        <img width="250" alt="레시피 담을 시 식재료 수량 조절" src="" />
      </td>
      <td align="center" height="450">
        <img width="250" alt="아임포트 결제 시스템 연동" src="" />
      </td>
    </tr>
  </table>

### 4. 📋 커뮤니티 게시판 서비스
- 사용자 게시글 CRUD 기능
- 사용자 이미지 업로드 처리
- 사용자 댓글 CRUD 기능

  <table>
    <tr>
      <td align="center" width="320"><b>게시판 목록(나만의 레시피)</b></td>
      <td align="center" width="320"><b>게시글 상세 페이지</b></td>
    </tr>
    <tr>
      <td align="center" height="450">
        <img width="250" alt="게시판 목록(나만의 레시피)" src="" />
      </td>
      <td align="center" height="450">
        <img width="250" alt="게시글 상세 페이지" src="" />
      </td>
    </tr>
  </table>

### 5. 관리자 대시보드 시스템
- 관리자 레시피 CRUD 기능 (등록/수정/삭제)
- 관리자 식재료 CRUD 기능 (등록/수정/삭제)
- 식재료 재고 관리 기능

  <table>
    <tr>
      <td align="center" width="320"><b>새 레시피 추가 페이지</b></td>
      <td align="center" width="320"><b>새 식재료 추가 페이지</b></td>
    </tr>
    <tr>
      <td align="center" height="450">
        <img width="250" alt="새 레시피 추가 페이지" src="" />
      </td>
      <td align="center" height="450">
        <img width="250" alt="새 식재료 추가 페이지" src="" />
      </td>
    </tr>
    <tr>
      <td align="center" width="320"><b>레시피 삭제 페이지</b></td>
      <td align="center" width="320"><b>식재료 재고 관리 페이지</b></td>
    </tr>
    <tr>
      <td align="center" height="450">
        <img width="250" alt="레시피 삭제 페이지" src="" />
      </td>
      <td align="center" height="450">
        <img width="250" alt="식재료 재고 관리 페이지" src="" />
      </td>
    </tr>
  </table>
  
---

## 🛠 기술 스택

### 💻 Frontend


### 🖥 Backend


### 🗃 DB


### 🤝 Collaboration

---

## 👨‍👩‍👧‍👦 Team

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

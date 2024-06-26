# REACT 팀프로젝트

![이미지](./public/images/image.png)

## 소개

- 리그오브레전드(https://www.leagueoflegends.com/ko-kr/) 홈페이지를 
  참고하여 만든 사이트 입니다.
- 사이트 : https://shinjunhyeok.github.io/team-project-lol/dist/

## 기술스택

### Skills

<img src="https://img.shields.io/badge/html5-E34F26?style=for-the-badge&logo=html5&logoColor=white"> <img src="https://img.shields.io/badge/css-1572B6?style=for-the-badge&logo=css3&logoColor=white"> <img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"> <img src="https://img.shields.io/badge/react-61DAFB?style=for-the-badge&logo=react&logoColor=black">

### Tools

<img src="https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=Slack&logoColor=white"> <img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white">

## 작업기간

2024.05.29. ~ 2024.06.13.

## 팀원

|                    **이지연**                    |               **이의강**               |                    **신준혁**                    |
| :----------------------------------------------: | :------------------------------------: | :----------------------------------------------: |
| [@a1waysbemine](https://github.com/a1waysbemine) | [@uikang1](https://github.com/uikang1) | [@ShinJunhyeok](https://github.com/ShinJunhyeok) |

## 역할분담 및 기능설명

👉🏻 공통

- HTML, CSS
- styled Components를 활용하여 각 컴포넌트별 스타일링
- 페이지별 데이터 파일 생성
- redux-toolkit을 활용한 slice 생성
- 각 컴포넌트에서 store에 저장된 state에 접근

👉🏻 이지연<br/>
담당 페이지 : 상점, 회원가입, 로그인, 로그아웃

- Local storage를 활용하여 입력받은 사용자의 정보를 저장해 회원가입 기능을 구현하였으며, 로그인한 유저에 대한 정보를 저장하여 페이지 새로고침 시에도 로그인 상태가 변경되지 않도록 함.
- 상품 정보를 담은 데이터 파일을 생성하고, Javascript의 map 메서드를 활용하여 상품 리스트를 구현함.
- 각 상품을 클릭할 경우, 해당 제품의 상세 페이지로 이동
- 유저 로그인 시 장바구니 아이콘이 나타나고, 상품을 장바구니에 추가할 경우 시각적 변화를 줌.
- 검색어 입력 시 해당 검색어를 포함하는 상품만 필터링하여 보여짐
- 각 기준별 상품 정렬

👉🏻 이의강<br/>
담당 페이지 : 메인페이지 , 챔피언 , 공지사항, E스포츠 소식

- 메인 페이지 : 스타일드 컴포넌트를 활용하여 전체 디자인을 구현했습니다. / 다양한 소식 부분에서 작은 사진을 클릭하면 해당 사진에 맞는 오른쪽 원형 영상으로 변경되는 동적 콘텐츠 섹션을 구현했습니다. / 주목할만한 소식 부분에서 두 번째 데이터를 클릭하면 모달 방식으로 영상을 띄우도록 했습니다.
- 챔피언 페이지 : API를 만들어 40개의 챔피언 데이터를 생성하여 모두 표시되도록 했습니다. / 챔피언을 클릭하면 해당 챔피언의 상세 페이지로 이동할 수 있도록 상세 페이지를 구현했습니다.
- 공지사항 페이지 : 24개의 공지사항 데이터를 생성했습니다. / 'useState' 를 사용하여 초기 표시되는 공지사항 개수를 12개로 설정하였고 'slice' 메서드를 사용하여 처음 12개의 데이터만 화면에 표시되도록 하였고 '더보기' 버튼을 클릭하면 setItems를 통해 표시되는 데이터를 전체 공지사항 개수로 업데이트하여 나머지 데이터를 모두 표시하도록 구현하였고 , '더보기' 버튼은 조건부 렌더링을 통해, 표시되는 공지사항의 수가 전체 데이터의 수보다 적을 때만 나타나도록 했습니다.
- E스포츠 소식 페이지 : 24개의 E-스포츠 소식 데이터를 생성했습니다. / 'useState' 를 사용하여 초기 표시되는 E-스포츠 소식 개수를 12개로 설정하였고 , 'slice' 메서드를 사용하여 처음 12개의 데이터만 화면에 표시되도록 하였고 , '더보기' 버튼을 클릭하면 setBtnItems를 통해 표시되는 데이터를 전체 E-스포츠 소식 개수로 업데이트하여 나머지 데이터를 모두 표시하도록 하였고 , '더보기' 버튼은 조건부 렌더링을 통해, 표시되는 E-스포츠 소식의 수가 전체 데이터의 수보다 적을 때만 나타나도록 하였고 , 데이터를 클릭하면 모달 형식으로 유튜브 영상을 보여주도록 구현했습니다.

👉🏻 신준혁<br/>
담당 페이지 : 기본정보, 자유게시판, 문의하기

- 기본정보 페이지의 왼쪽 아이콘 클릭 시 해당 아이콘에 맞는 이미지로 변경됨.
- localStorage를 활용하여 자유 게시판에 글을 작성 또는 삭제한 후에도 새로고침을 해도 원래 데이터로 돌아가지 않고 유지되게 만듦.
- 글 작성 시 빈 칸이 있으면 작성이 안 되게 구현함.
- 작성되어 있는 글들을 수정 버튼을 눌러 수정할 수 있게 구현함.
- 각 포지션 선택 시 그 포지션에 해당하는 글만 보이도록 구현함.
- 각 티어 선택 시 그 티어에 해당하는 글만 보이도록 구현함.
- 문의하기 페이지에서 문의 유형을 선택할 시 그 유형에 맞는 문제 선택 박스가 나오도록 구현함.

## 메뉴트리
```bash
├── README.md
├── index.html
├── package.json
├── public
│   └── images
│       ├── common
│       └── content
│           ├── champions
│           ├── community
│           ├── esports
│           ├── login
│           ├── main
│           ├── notice
│           ├── skills
│           ├── skins
│           └── store
├── src
│   ├── App.css
│   ├── App.jsx
│   ├── assets
│   │   └── api
│   │       ├── Champion.js
│   │       ├── ChampionsDetail.js
│   │       ├── Esport.js
│   │       ├── GameVideo.js
│   │       ├── Mainpagedata.js
│   │       ├── Notice.js
│   │       ├── communityData.js
│   │       └── skin_store.js
│   ├── components
│   │   ├── Layout.jsx
│   │   ├── cart
│   │   │   ├── CartEmpty.jsx
│   │   │   ├── CartItem.jsx
│   │   │   ├── CartList.jsx
│   │   │   └── CartStyle.js
│   │   ├── champions
│   │   │   ├── ChampionDetail.jsx
│   │   │   ├── ChampionItem.jsx
│   │   │   └── ChampionList.jsx
│   │   ├── community
│   │   │   ├── CommunityAdd.jsx
│   │   │   ├── CommunityEdit.jsx
│   │   │   ├── CommunityItem.jsx
│   │   │   ├── CommunityList.jsx
│   │   │   └── CommunitySearch.jsx
│   │   ├── esports
│   │   │   ├── EsportItem.jsx
│   │   │   └── EsportList.jsx
│   │   ├── footer
│   │   │   ├── Footer.jsx
│   │   │   ├── FooterStyle.js
│   │   │   ├── footerList
│   │   │   │   ├── FooterItem.jsx
│   │   │   │   └── FooterList.jsx
│   │   │   └── footerSite
│   │   │       ├── FooterSite.jsx
│   │   │       └── SiteItem.jsx
│   │   ├── header
│   │   │   ├── Header.jsx
│   │   │   ├── HeaderStyle.js
│   │   │   └── Nav.jsx
│   │   ├── howtoplay
│   │   │   ├── ChooseLine.jsx
│   │   │   ├── Enhance.jsx
│   │   │   ├── GameInfo.jsx
│   │   │   ├── GamePlay.jsx
│   │   │   ├── GameUpdate.jsx
│   │   │   └── UseSkills.jsx
│   │   ├── main
│   │   │   ├── ArenaSectioncontainer.jsx
│   │   │   ├── Bottom.jsx
│   │   │   ├── ChampionSectionList.jsx
│   │   │   ├── MapSection.jsx
│   │   │   ├── MoreSection.jsx
│   │   │   ├── NewsSectioncontainer.jsx
│   │   │   └── TopVideo.jsx
│   │   ├── notice
│   │   │   ├── NoticeItem.jsx
│   │   │   └── NoticeList.jsx
│   │   ├── pagination
│   │   │   ├── Pagination.jsx
│   │   │   └── PaginationStyle.js
│   │   ├── requests
│   │   │   ├── RequestForm.jsx
│   │   │   ├── RequestOptions.jsx
│   │   │   └── RequestVisual.jsx
│   │   └── skinstore
│   │       ├── SkinDetail.jsx
│   │       ├── SkinItem.jsx
│   │       ├── SkinList.jsx
│   │       ├── SkinStoreStyle.js
│   │       └── SkinStoreTop.jsx
│   ├── index.css
│   ├── main.jsx
│   ├── pages
│   │   ├── Cart
│   │   │   ├── StoreCart.jsx
│   │   │   └── StoreCartStyle.js
│   │   ├── champions
│   │   │   ├── Champion.jsx
│   │   │   └── championstyle.js
│   │   ├── community
│   │   │   ├── Community.jsx
│   │   │   └── CommunityStyle.js
│   │   ├── esports
│   │   │   ├── Esport.jsx
│   │   │   └── esportstyle.js
│   │   ├── howToPlay
│   │   │   ├── HowToPlay.jsx
│   │   │   └── howtoplayStyle.js
│   │   ├── login
│   │   │   ├── Join.jsx
│   │   │   ├── Login.jsx
│   │   │   ├── LoginStyle.js
│   │   │   ├── Logout.jsx
│   │   │   └── RealLogout.jsx
│   │   ├── main
│   │   │   ├── Mainpage.jsx
│   │   │   └── mainpageStyle.js
│   │   ├── notice
│   │   │   ├── Notice.jsx
│   │   │   └── noticeStyle.js
│   │   ├── requests
│   │   │   ├── Requests.jsx
│   │   │   └── requestsStyle.js
│   │   └── skinstore
│   │       ├── SkinStore.jsx
│   │       └── skinstore_style.js
│   ├── store
│   │   ├── index.jsx
│   │   └── modules
│   │       ├── authSlice.js
│   │       ├── cartSlice.js
│   │       ├── communitySlice.js
│   │       └── paginationSlice.js
│   └── styled
│       └── GlobalStyle.js
├── vite.config.js
└── yarn.lock
```

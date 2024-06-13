# Flownary React Project
기간: 2024-04-16 ~ 2024-06-14<br/>
인원: 6인 (FE 4, BE 1, DB 1) - 이윤주, 안순현, 정성한, 윤영준, 곽주영, 이병학<br/>
주제: SNS 사이트 만들기<br/>
사용 언어: JS (React)<br/>

## Pages(route)
#### home 홈
게시글 목록, 게시글 작성을 겸합니다
#### login 로그인
#### chatting 채팅
채팅방 목록과 채팅 내용을 표시합니다
#### chattingtemp 임시채팅
아직 채팅방이 만들어지지 않은 유저들끼리 채팅방을 만들기 전 채팅방 제목과 첫 채팅만 보내기 위해 제작된 페이지입니다
#### mypage 마이페이지
그냥 들어갈 경우 현재 로그인한 유저의 마이페이지, 타인의 프로필을 클릭하면 타인의 마이페이지가 나옵니다
#### family 패밀리
#### follow 플로우(팔로우)
타 SNS의 팔로우와 거의 유사한 기능으로, 해당 페이지는 자신의 팔로워, 팔로잉 목록을 볼 수 있습니다
#### album 앨범
#### notification 알림
#### verify 인증
설정에 들어가기 전 비밀번호를 입력하는 페이지입니다
#### setting 유저 설정
유저의 개인정보나 프로필 사진을 수정하는 공간입니다
#### team 팀
팀 소개 페이지입니다
#### search 검색
게시글 검색 페이지
#### statistics 이용 통계 (관리자 전용)
이용자의 글 작성 등의 통계 제공 페이지입니다
#### userList 사용자 관리 (관리자 전용)
이용자의 비활성화/활성화를 할 수 있는 관리자 전용 페이지입니다
#### boardList 게시물 관리 (관리자 전용)
글에 대한 신고와 글 목록에 대한 처리를 할 수 있는 페이지입니다


### 기타
1. 최상위 경로에 env.local로 특정 키 등의 정보 필요합니다. 필요한 정보는 아래와 같습니다
- Firebase : REACT_APP_FIREBASE_API_KEY, REACT_APP_FIREBASE_AUTH_DOMAIN, REACT_APP_FIREBASE_PROJECT_ID, REACT_APP_FIREBASE_STORAGE_BUCKET, REACT_APP_FIREBASE_MESSAGING_SEMDER_ID, REACT_APP_FIREBASE_APP_ID
- Cloudinary : REACT_APP_CLOUDINARY_CLOUD_NAME, REACT_APP_CLOUDINARY_UPLOAD_PRESET, REACT_APP_CLOUDINARY_URL
- React : REACT_APP_API_KEY
- Kakao : YOUR_KAKAO_REST_API_KEY (java key)
- GENERATE_SOURCEMAP
- websocket : REACT_APP_WEBSOCKET_URL
- REACT_APP_ADDRESS
2. Spring Boot와 연계하여 사용할 경우 서버의 IP에 대한 웹소켓 연결을 Proxy.js로 하는 것이 필요합니다

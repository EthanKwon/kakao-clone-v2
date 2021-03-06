# :chocolate_bar: kakao-clone-v2

Kakao Clone Coding을 통해 HTML, CSS를 마스터 하자!

### :tv: 참고 영상 : Kakao Clone V2 (Nomad Coders - 노마드 코더)

### :date: 공부 기간 : 19. 12. 02 ~ 19. 12. 09

### :triangular_flag_on_post: 완성된 Kakao Clone : https://ethankwon.github.io/kakao-clone-v2/
---

## 완성된 화면

#### finished friends (카카오톡 친구 화면 창) / finished chats (카카오톡 친구 채팅 창) / finished find (카카오톡 친구 찾기 창)

<div>
   <img src="https://github.com/EthanKwon/kakao-clone-v2/blob/master/finished-image/Friends.png" width="30%"> 
   <img src="https://github.com/EthanKwon/kakao-clone-v2/blob/master/finished-image/chats.png" width="30%">
   <img src="https://github.com/EthanKwon/kakao-clone-v2/blob/master/finished-image/find.png" width="30%">
</div>

#### finished more (카카오톡 더보기 창) / finished settings (카카오톡 설정 창) / finished chat (카카오톡 채팅 창)

<div>
   <img src="https://github.com/EthanKwon/kakao-clone-v2/blob/master/finished-image/more.png" width="30%"> 
   <img src="https://github.com/EthanKwon/kakao-clone-v2/blob/master/finished-image/settings.png" width="30%"> 
   <img src="https://github.com/EthanKwon/kakao-clone-v2/blob/master/finished-image/chat.png" width="30%"> 
</div>

### KaKao Clone - HTML (19. 12. 02 ~ 19. 12. 03)

#### ※ (필수) HTML 작성시 항상 구조를 생각 하면서 작성한다.

1. **Status Bar** 만들기

   - 실제 Kakao Talk 화면을 캡쳐해 브라우저에서 구성 요소를 확인 후 element 구성
   - **BEM** 규칙을 준수하며 Class Name 지정 ([BEM 참고 자료](http://getbem.com/))
   - **Font Awesome**을 이용하여 status bar의 아이콘을 구성 ([Font Awesome](https://fontawesome.com/))

2. **Header & Navigation** 만들기

   - **Font Awesome**을 이용하여 Header와 Navigation 구성
   - 각 페이지에 Header와 Navigation 모두 적용
   - Font Awesome의 **far(reguler icon)** 과 **fas(solid icon)** 을 이용해 선택 페이지 구분

3. **Index Page - Chats** 만들기

   - 하나의 Block에 Element가 많다면, **Element를 새로운 Block으로 지정 후** Class Name 지정
   - instagram을 통해 자신의 프로필 사진을 **개발자 도구** 를 이용하여 추출

4. **Friends Page - Friends Main** 만들기

   - 다른 HTML 파일의 img에 같은 CSS효과를 주기 위해서 **Global Class Name** 지정
   - 다른 부분의 Element들(프로필과 친구 등)이더라도, **같은 CSS Style을 지정해야 할 경우** 같은 Class Name을 지정
   - img 등 크기를 다르게 설정 해야 할 경우, **새로운 클래스 네임을 추가 (변경X)**

5. **Find Page - Find Main** 만들기

   - header에는 icon을 추가하고, ul에 추천 친구 항목을 추가 (Friends에서 한것과 동일)

6. **More Page - More Main** 만들기

   - header에는 Profile과 ul로 메뉴를 넣고, section을 통해 Seggestions를 추가 (동일 방식)

7. **Settings Page - Settings Main** 만들기

   - 이전 페이지와 동일 방식 사용

8. **Chat Page - Chat Main** 만들기
   - 이전 페이지와 동일 방식 사용

### KaKao Clone - CSS (19. 12. 04 ~ 19. 12. 08)

1. **CSS Reset** 적용하기

   - 모든 브라우저에서 **같은 CSS style** 로 부터 시작하기 위해 설정
   - [CSS Reset](https://meyerweb.com/eric/tools/css/reset/)의 내용을 **reset.css에 붙여넣기** 하기
   - styles.css에서 reset 파일을 **@import** 하기
   - [Normalize CSS](https://necolas.github.io/normalize.css/)를 이용하여 설정을 할 수 있음

2. **Google Font** 적용하기

   - [Google Font](https://fonts.google.com/)를 이용하여 Font를 적용
   - 원하는 Font와 필요한 굵기들을 선택한 후, **@import**를 하기
   - 속도를 위해 **원하는 Font** 굵기만 사용 할 것

3. **header style** 적용하기

   - **flex** 로 header의 아이콘 정렬하기
   - **cursor** 변경하기
   - **margin** 으로 공간주기

4. **navgation bar style** 적용하기

   - **fixed**로 navigation bar 위치 고정하기
   - **fixed** 사용시 항상 **width** 지정 할 것
   - **box-sizing**으로 element의 공간 변화 고정하기

5. **message badge style** 적용하기

   - **relative** 와 **absolute**를 이용하여 메세지 아이콘 우측 상단에 위치시키기
   - **flex**를 이용하여 글자를 element 정 가운데 위치시키기
   - **border-radius**를 이용하여 element 원형으로 만들기

6. **user image style** 적용하기

   - **border-radius**를 이용하여 element 테두리 조정하기
   - **flex**를 이용하여 user 정보 위치 조정하기

7. **friend style** 적용하기

   - class 별 **font-size**와 **opacity** 조정하기
   - class 별 **image size** 조정하기

8. **frineds style** 적용하기

   - 위와 같은 방식으로 스타일 조정

9. **find style** 적용하기

   - 위와 같은 방식으로 스타일 조정

10. **more style** 적용하기

    - 위와 같은 방식으로 스타일 조정

11. **setting style** 적용하기

    - **last-child**를 이용하여 리스트에 마지막 항목만 margin 조정하기
    - **curser**를 이용하여 element를 가리키는 커서의 모양 바꾸기

12. **chating style** 적용하기
    - [stripe](https://stripe.com/)에서 **box-shedow** 효과 가져오기
    - [subtle Patterns](https://www.toptal.com/designers/subtlepatterns/)에서 채팅방 배경화면 가져오기
    - **margin : 0 auto , left : 0 , right : 0** 설정을 통해 element 가운데 정렬하기
    - **padding**을 통해 element의 모양을 만들기
    - 클래스별 말풍선에 **border-radius** 개별 적용하기
    - 클래스별 말풍선에 **line-gradient** 적용하기

### Kakao Clone Animation (19. 12. 09)

1. **chating animation** 적용하기

   - **transition**을 통해 focus시 양쪽 아이콘이 사라지도록 효과를 넣기
   - **'display : none;'** 으로는 transition 효과를 줄 수 없기 때문에 **opacity : 0**으로 설정
   - animation 효과를 주기 위해서는 **해당 Element 뒤에 위치** 해야 한다.
   - **transform**과 **transition**을 통해 focus시 위치 이동을 하도록 변경
   - **margin : 0 auto**를 통해 element를 가운데에 위치시킴
   - **animation**을 통해 그림자 효과를 단계별로 적용 및 메세지를 양쪽에서 들어오는 듯한 효과를 줌
   - **forward**는 animation 종료 후에도 마지막 값을 유지 하도록 함
   - **transform rotate**를 이용해 user image 회전 시키기

2. **전체 animation** 적용하기

   - 화면 loading시 **transform**으로 위로 올라가는 animation 효과 넣기
   - **animation-delay**를 통해 시간 지연 후 animation 동작 시키기

3. **media-query** 적용하기
   - **media-query**를 이용하여 화면이 530px이상이면 가려지도록 설정

### Kakao Clone 추가 사항 (19. 12. 08 ~ 19. 12. 09)

1. **Friends 화면** 수정

   - **네비게이션 뱃지** 모든 화면에 추가
   - **친구 목록 화면** 수정 (현재 카카오톡 화면과 동일하게)
   - **친구 목록** 추가

2. **Chats 화면** 수정

   - **대화 리스트** 추가
   - **단체 톡방용 사진** 추가
   - **대화 뱃지** 추가 (인원수, 알람설정, 즐겨찾기)
   - **개별 대화 뱃지** 추가

3. **Find 화면** 수정

   - **추천 친구** 추가
   - 옛 화면 유지 (새로운 html 형식이라 추후에 추가 예정)
   - **header btn**에 cursor 추가

4. **More 화면** 수정

   - **Suggestion** 부분 삭제
   - **Pay** 부분 추가
   - **Button** 추가 및 **flex**로 4개씩 고정
   - **Mail, Calender** 항목 추가
   - **Ad(광고)** 항목 추가

5. **nav-bar** 수정
   - **Nav badge**에 회전 animation 추가

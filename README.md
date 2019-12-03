# kakao-clone-v2
 
Kakao Clone Coding을 통해 HTML, CSS를 마스터 하자!

### :tv: 참고 영상 : Kakao Clone V2 (Nomad Coders - 노마드 코더)
### :date: 공부 기간 : 19. 12. 02 ~ 진행중

---

### KaKao Clone - HTML (19. 12. 02)

1. **Status Bar** 만들기 
     - 실제 Kakao Talk 화면을 캡쳐해 브라우저에서 구성 요소를 확인 후 element 구성
     - **BEM** 규칙을 준수하며 Class Name 지정 ([BEM 참고 자료](http://getbem.com/))
     - **Font Awesome**을 이용하여 status bar의 아이콘을 구성 ([Font Awesome](https://fontawesome.com/))

### KaKao Clone - HTML (19. 12. 03)

1. **Header & Navigation** 만들기
      - **Font Awesome**을 이용하여 Header와 Navigation 구성
      - 각 페이지에 Header와 Navigation 모두 적용
      - Font Awesome의 **far(reguler icon)** 과 **fas(solid icon)** 을 이용해 선택 페이지 구분

2. **Index Page - Chats** 만들기
      - 하나의 Block에 Element가 많다면, **Element를 새로운 Block으로 지정 후** Class Name 지정 
      - instagram을 통해 자신의 프로필 사진을 **개발자 도구** 를 이용하여 추출

3. **Friends Page - Friends** 만들기
      - 다른 HTML 파일의 img에 같은 CSS효과를 주기 위해서 **Global Class Name** 지정 
      - 다른 부분의 Element들(프로필과 친구 등)이더라도, **같은 CSS Style을 지정해야 할 경우** 같은 Class Name을 지정
      - img 등 크기를 다르게 설정 해야 할 경우, **새로운 클래스 네임을 추가 (변경X)**

4. **Find Page - Find** 만들기
      - header에는 icon을 추가하고, ul에 추천 친구 항목을 추가 (Friends에서 한것과 동일)

5. **More Page - More** 만들기
      - header에는 Profile과 ul로 메뉴를 넣고, section을 통해 Seggestions를 추가 (동일 방식)

6. **Settings Page - Settings** 만들기
      - 이전 페이지와 동일 방식 사용
# BreakingNews_CreateImg
HTML5 CANVAS를 이용한 뉴스속보 합성 이미지 만들기 웹 사이트 입니다.

## 기본설명
1. HTML5의 Canvas Tag와 Javascript를 이용하여 합성된 뉴스속보 이미지 파일을 만들어 사용자에게 제공하여 줍니다.
2. 전체적인 UI는 Twitter Bootstrap을 기반으로 만들어졌습니다.
3. 사용자로부터 배경 이미지 혹은 텍스트 문구를 입력받으면 실시간으로 Javascript와 CANVAS 요소를 통해 이미지를 출력해줍니다.
4. 사용자는 생성된 이미지를 파일로 다운로드 받을 수 있습니다.
5. 사용자로부터 선택된 이미지는 서버에 업로드 되지않습니다. 모든 처리는 클라이언트 단에서 이루어집니다.
6. (참고 1) 해당 사이트 - http://myeonguni.com/myeonguni_news/myeonguni_news.html
7. (참고 2) GitHub - https://github.com/myeonguni/BreakingNews_CreateImg

## 스크린샷
![Alt text](/screenshot.JPG)

## 개발환경
1. 사용언어 : HTML5/CSS, JAVSCRIPT
2. 사용 프레임워크 : JQUERY, Twitter Bootstrap
3. 웹 서버 호스팅 : AWS EC2

## 업데이트 해야할 사항
input file type 관련 절대경로 가져오기(구글링 결과 최근 우회방법 마저 보안상 막혀있음. 다른 로직 생각해볼 것. 단, 페이지 이동이 없어야 함.) → 해결완료 : JAVSCRIPT File IO로 읽어오는 방법
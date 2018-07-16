---
layout: post
title: 'Github Meetup. (1/n)'
author: Glee
date: 2018-07-16 12:00
tags: [github]
image: /files/covers/github-meetup-01.jpg
---

#### Meetup for github (1/n)
###### 2018.07.04. wed / with im퍼블리셔님, yung개발자님, Dong개발자님

- - -

드디어 첫 Github Meetup!
디자이너, 개발자, 퍼블리셔. 다양한 시각으로 각자 느낀점을 가볍게 애기해보기로 했다.
글을 작성하다가 날아가서(멘탈 털림) 다른 분들의 황금같은 의견이 기억이 안난다. ㅠㅠ
그래서 내가 애기했던 내용 위주로 정리해본다.

** [ 디자이너의 눈물나는 깃헙 도전기 ] **
  - ** 기본적으로 '겁'이 기본값인 사람**
  내가 먼저 제안했는데 내가 제일 진도가 느렸다.
  어떻게 깔았는지에 대해서는 ++[지난번 글](https://eternalglee.github.io/2018/07/10/start_github/)++에서 언급했으니 넘어가기로.
  내가 2주걸려도 해결 못한거 개발자님이 2시간만에 파악하고 방법 알랴줌. 찬양하라 갓개발자여.
  
  - ** 잘 만들어진 걸 파헤치며 배우자 **
  ++[지킬테마사이트](https://jekyllthemes.org/)++에서 수 많은 테마를 적용해보았으나, 마음에 들지 않는건 둘째치고 짠-하고 한 번에 적용되는 경우가 적었다.
  그래서 이미 만들어져서 활발하게 글이 올라오고 있는 카카오톡 기술블로그를 통째로 Fork해왔다.
  로컬로 다운받아 실제 사이트와 비교해가면서 어떻게 파일이 구성되어있고 폴더는 어떻게 나눠져있는지 확인했다. 그리고 README파일을 정독. 깃헙블로그 이후 글이나 작성자 등록을 어떻게하는지 상세하게 나와있다.
  
  1. _config.yml 파일 수정.
   <img src="files/config-edit.png">
   블로그 정보를 내 정보로 교체했다.
   타이틀이나 깃헙정보등을 수정했고, 나머지 모르는 부분들은 그냥 패스.
   config파일은 수정사항이 간단해서 그냥 깃헙 사이트에서 수정하는게 편하다.
   
  2. 글 작성자 정보 등록
  authors폴더에 내 이름으로 된 md파일을 생성해준다.아래와 같이 정보를 입력해준다.
  *name: Glee
  title: 김지선
  image: /files/authors/Glee.jpg*
  이미지는 해당 폴더로 이동해서 내가 사용하고자하는 이미지로 바꿔줬다.
  
  3. 기타 이미지 변경
  assets > images 안에 블로그를 이루고있는 이미지 요소들이 모여있다.
  커버이미지나 푸터에 SNS정보에 들어가는 아이콘들을 수정해줬다.
  카카오는 모바일과 PC용 이미지를 따로 구분해줬다.
  모바일 파일명을 보니 스케치로 디자인하시고 후에 적용하신 느낌이 났다.
  나도.. 나도 나중에 직접 디자인해서 처음부터 블로그 만들어보고 싶다.
  
  4. 글 작성
  글 작성은 _posts 폴더 안에 있는 글 들중 하나를 복사해서 수정해서 적용했다.
  작성자 정보도 내 정보로 교체하니 사이트에서 내 프로필 이미지가 뜨는게 신기했다.
  아직 마크다운 형식으로 적는게 어색하지만 가볍게 틈틈히 적기엔 또 괜찮네.
  원래 글쓸 때 환경에 예민한 편인데, 나름 잘 적응하고 있는 듯하다.
  
  <img src="files/write-in-pages.png">
  예민한 사람의 평소 글쓰기 환경.
  pages어플에서 내 맘에 드는 폰트로 작성해야 기분이 좋거든요.
  
  그리고 ++[하루패드](http://pad.haroopress.com/page.html)++를 사용해서 마크다운문법과 친해지려고 무진장 애쓰고 있다.
  
  5. 웹폰트 적용
  카카오 기술블로그에 웹폰트가 이미 적용되어있어서 내가 적용해보고싶었던 폰트로 적용
  assets > fonts 폴더 안에 폴더들을 지우고 내가 쓰고 싶어했던 ++[이롭게](http://font.iropke.com/batang/)++ 폰트를 적용했다.
  고딕체보다 요즘은 명조체가 말하는 느낌이 전달되서 더 좋다. 
  
  
 - ** 외울 때까지 무한 반복 **
  맥북을 3~4년 가까이 사용해오면서 터미널을 사용해본 적이 없다.
  일단 화면 너무 무섭지않나? 어렸을 때 컴퓨터 고장나면 뜨던 화면들이랑 너무 닮았다.
  근데 깃헙을 하면서 터미널 사용을 피할 수 없었다.
  왜냐면 설명해놓은 블로그들도 그렇고 개발자분들도 다 터미널을 이용해서 가르쳐주셨기 때문이지.
  그래서 몇가지 가르쳐주신 터미널 명령어들을 반복해서 외울때까지 사용해봤다.
  파일 하나 수정하고 터미널 열어서 명령어쓰고 또 파일 수정해서 터미널 명령어 입력하고.
  이걸 한 50번정도 반복하면 자동으로 외워진다. 역시 머리가 나쁘면 몸이 고생이지. 
  
  - 터미널 열고 깃헙폴더로 이동 : cd Documents / cd eternaglee.github.io
    cd가 아마 change Directory겠지? 무튼 폴더명 너무 기니까 몇글자만 적어주고 tab키 누르면 자동으로 불러와준다. 똑똑해.
  
  - 업데이트 할 파일이 있나 체크해줘 : git status
    수정한 파일이 있다면 해당 내역들이 빨간색으로 뜬다.
    
  - 그 파일들 커밋해줘 : git commit -m "업데이트 내용 간략 설명"
    커밋 후 다시 git status명령을 입력하면 아까 빨간색으로 떴던 파일명이 초록색으로 뜬다.
  
  - 오 이제 깃헙블로그에 적용해줄래? : git push origin master
    업로드 퍼센트가 쫘르르 올라가면 성공인데 error가 많이뜨면 나는 push 뒤에 -f를 붙여서 강제적으로 업로드 해버린다.
    
  그런데 최근에 느낀건데 굳이 터미널로 안해도 될것같다.(좌절)
  주로 글 적을 용도라, 글을 적고서 해당 md파일을 github사이트에서 바로 업로드해줘도 된다.
  어째 이게 적용되는 시간이 빠른거 같기도하고, 잦은 수정이 아니면 굳이 터미널 켤 필요 없다.
  다만 터미널이랑 친해지고 싶거나 잦은 수정이 발생할 경우에는 터미널 사용도 추천.
  나만해도 깃헙하면서 터미널에 명령어 넣는게 한결 자연스러워졌고, 이거해! 라고 하면 대답하는 터미널이 가끔 인격화되서 귀엽기까지 하다.
  
  
  
  다음주에 해보고 싶은 것.
  1. tags영역 공부. 몇번 건들여봤는데 자꾸 에러가나서 좀 더 깊이 알아봐야할 것 같다.
  2. 댓글기능 추가하기
  3. 글 몇개 더 적어보기
  4. 포트폴리오 페이지를 위한 갤러리기능 자료조사
  
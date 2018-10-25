1. emit

vscode에는 기본 내장되어있음.
특정코드를 입력함으로써 쉽게 문서를 작성해주는 플러그인
- ! (메타태그를 포함한 html,head,body 태그를 만들어준다.)
- div*5 (div 구조를 5개 만든다.)
- div.box*3 (box라는 클래스 네임을 가진 div를 3개 만든다.)
- ul>li.list*5 (ul 자식으로 list라는 클래스 네임을 가진 li를 5개 만든다.)   



2. vscode가 제공하는 에디팅 기능

- 중복의 라인에서 같이 작성하기, 다중커서 <alt+왼쪽클릭>
- 블록을 지정하지않고, 라인의 마지막줄에서 커서를 지정해주고 <ctrl+c>을 하면 라인 자체를 복사한다.
- 원하는 라인들에 커서 또는, 블록을 지정해주고 <위,아래 방향키> 를 누르면 라인 전체가 이동한다.
- 주석달기 <ctrl+/>



3. vscode 환경설정 - 현재는 GUI 환경이 잘되어있음

- 텍스트 편집기 (사용자 설정)
글꼴 : https://github.com/naver/d2codingfont => zip파일 설치후 ttf 파일 설치
{
  "editor.fontSize" : 18 (폰트크기설정)
  "editor.renderWhitespace" : "all" (공백 . 으로 보임)
  "editor.wordWrap" : "on" (화면에서만 편집기 줄 바뀜-코드라인은 그대로)
  "editor.fontFamily" : "D2Coding, Consolas, 'Courier New', monospace",
  }



4. 마켓플레이스 설치(설치후 각각 다시로드를 해주어야함) 
<보기 - 명령 팔레트>를 선택하면 명령어를 확인할수있음.

- color Highlight => css에서 color를 줄때 색상 미리보기(컬러 팔렛트)및 선택이 가능함
- Prettier-Code formatter => 코드포맷을 자동으로 완성시켜줌 <ctrl+shift+p>
- 왼쪽 밑의 톱니바퀴 아이콘을 누른후 색 테마로 vscode의 테마를 바꿀수있음



5. SASS에 관한 확장

- sass => vscode에서 sass 문법 지원하도록 하는것
- Live Sass Compiler(live server 도 자동으로 함께 설치됨) => sass적용된 파일에서 <오른쪽클릭=>open with live server>를 눌러서 server를 활성화 하면, 파일을 저장할때마다  hot loder 기능이 됨
  => port 에러 나올시.vs환경설정에서  "liveServer.settings.port": 0 추가
  => 하단 설정창에 (Watch Sass) 라는 버튼을 누르면 활성화되고, sass파일을 css로 컴파일 해줌
- Sass Lint =>
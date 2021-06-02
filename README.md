# validation-check

### HTML에서 id와 class 명은 지정해줬다.

- 목적 selector
- 비밀번호 입력 창 #password
- 비밀번호 확인 입력 창 #password-retype
- 시각적 피드백 .mismatch-message

### isMatch 함수를 꼭 사용!

- 함수 isMatch 가 파일 script.js 에 작성되어야 합니다.
- 이 함수는 문자열 두 개를 입력으로 받고, boolean 타입을 리턴합니다.
- 작성 후 개발자 콘솔에서 isMatch('암호1', '암호2') 와 같이 테스트해보세요.

### 수도코드다.

- [비밀번호 확인] 입력창에서 값을 입력(keyup)하면
- [비밀번호] 값과 [비밀번호 확인] 값이 일치하는지 확인하고,
- 일치하지 않은 경우, 불일치 메시지를 화면에 표시합니다.

### 우리의 도전 - 비밀번호

- ~~10자 이상 입력~~
- ~~영문/숫자/특수문자(공백 제외)만 허용하며, 2개 이상 조합~~
  1. ~~영문이 있니? - true~~
  2. ~~숫자가 있니? - tre~~
  3. ~~특수문자가 있니? - true~~
  4. ~~공백이 없니? - true~~
  5. ~~1~3까지 2개 이상 조합되었니? - true가 2개 이상이니?~~
- ~~동일한 숫자 3개 이상 연속 사용 불가~~
- ~~CSS Style Custom~~

### if( 에너지가.. 아직 남았니..? ) {

- ~~영문자 중에 대문자 하나이상 포함.~~
- ~~모든 조건이 충족됐을 때, 회원가입 버튼 배경 색상이 활성화가 되게한다. + 팝업창 + 모든 것이 초기화~~
- ~~만약 조건이 충족되지 않았을 때는 회원가입 버튼 클릭시 에러 메세지 팝업 창이 뜬다.~~

#### }

#### 혼자 추가 기능 구현
- ~~스타일 : 성공 메세지 공통 클래스 추가 HTML addClass (color: green)~~

- ~~비밀번호 : 사용 가능 메시지 출력 (HTML DOM)~~
- ~~비밀번호 : 영문,숫자,특수문자 조합만 가능 - 한글 등 불가능 (새로운 함수 정의 및 사용)~~

- ~~비밀번호 확인 : 매치 메세지가 비밀번호 input에서도 성공실패 여부 발생하도록 수정~~
- ~~비밀번호 확인 : 빈 문자열이어서 비밀번호가 매치된거면 실패 메세지 출력 (isMatch() 함수에서 비밀번호가 빈 문자일 경우 false)~~
- ~~비밀번호 확인 : 공백이 추가된 경우 실패 메세지 출력 (비밀번호 확인 input 유효성 검사 함수에 isPasswordBlank() 함수 사용)~~

- ~~아이디 : 영문, 숫자 조합만 가능 - 특수문자, 한글 등 불가능 (새로운 함수 정의 및 사용)~~
- ~~회원가입 버튼 : 클릭시 모든 성공 메시지 히든~~
- ~~모든 DOM 이벤트를 addEventListener()로 변경~~
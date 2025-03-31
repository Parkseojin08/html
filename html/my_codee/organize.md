# 폼작성 태그

\<form\> 폼과 폼의 시작과 끝
\<fielset\> 폼의 요소를 그룹으로 묶는거<br>
\<legend\> 폼 요소의 제목<br>
\<input\> 사용자가 입력할 필드를 삽입<br>
\(여러종류의 input태그가 존재)
<P></P>

\<select\> \<option\> 드롭다운목록 만들기<br>
\<textarea>텍스트를 여러줄 입력할수있다.


## \<input\>의 태그 유형(type)
input과 같이쓰이는 type의 유형<br>
쓰는 방법
```html
<input type = "옵션">
```
"옵션"에 들어가는 유형

text = 텍스트입력 상자를 넣는다. 단 한줄짜리임<br>
password = 비밀번호 입력상자를 만든다<br>
&nbsp; ex) 비밀번호를 입력할때 "****"로 보이는 텍스트입력박스
<p></p>
search = 검색하는 입력상자를 만든다<br>
&nbsp; ex) 텍스트 검색창 옆에 "X"아이콘이 뜸 (검색 내역지우기)<br>
&nbsp; search로 만든 텍스트입력상자는 자동적으로 최근 작성내용저장됨
<p></p>
url = url주소를 입력할수 있는 필드를 넣는다<br>
&nbsp; ex)text옵션이랑 다를게 없음 왜 구분?<br>
&nbsp; -> Html의 태그를 "시멘틱태그"이기 때문 시멘틱태그의 주요 목적 <b>"가독성"</b> (코드 쉽게이해)
<p></p>

email = 이메일을 입력할수있는 텍스트창을 만든다<br>
&nbsp; ex)여기도 텍스트박스랑 비슷함 만약에 형식에 구애받음
&nbsp; ex)required = 이 옵션은 필수항목을 표시하는 즉 항목 입력 X submit되지 않는 <br>
&nbsp;항목 각각 input 필드의 항목에 적용하면 그 형태가 다다름
<br>
&nbsp;ex)

```html 
<input type = "email">
```
내가 lgyaho 라고 입력하면 submit을 누르는 형식이 틀리다고 입력되지 않음<br>
"형식의 구애받음"
<p></p>
tel = 전화번호 입력 텍스트 박스를 만든다.
<br>
checkbox = 주어진 항목에 선택할 수 있는 박스를 생성(중복 가능)<br>
&nbsp; 모양 = "네모"
<p></p>
radio = 주어진 항목에서 선택할 수 있는 박스를 생성 (중복 불가)
&nbsp; radio박스를 묶어주는 작업이 필요<br>
&nbsp; 옵션 name 과 for 이 두가지<br>
&nbsp; name은 묶어줄떄 for은 연결할때 쓰는 옵션

&nbsp;ex)
```html
<input type = "radio" name = "2-1"> 
<input type = "radio" name튼<br>
reset = 천체 리셋(폼 내용 삭제)<br>
image = submit 버튼 대신 넣을 사진<br>
button = 일단버튼 생성 기능 X<br>
file = file 첨부버튼 생성  <br>
hidden = 사용자에게 안보이지만 서버로 넘겨주는 값이 있는 필드를 생성<br>
&nbsp;ex) 주석이랑은 다르지만 주석처럼 사용가능<br>
```

```html
<input type="text" name="name"> 이름
<input type="hidden" name="hiddenName" value="나즈나">
```
이름을 "나나쿠사" 라고 입력하지만 서버로는 나나쿠사 + 나즈나 두 값이 전송

## \<input\> 태그의 속성 (단일 태그)
autofocus = 웹문서가 열리면 기본으로 커서<br>
placeholder = 텍스트 필드의 "힌트" or "안내문구 등 표시할 수 있음<br>
readonly = 읽기 전용 필드 -> 사용자 입력 X<br>
required = 필수 입력 필드 생성 [입력 X -> submit이 입력 X]<br>
max = 숫자 입력필드의 최대값<Br>
min = 숫자 입력필드의 최소값<br>
step = 숫자 입력팔드의 "증가값"을 지정
```html
<input type = "number" step = "2">사랑
```
1 -> 3 -> 5 이런식으로
<p></p>
maxlength = 최대 문자의 길이 설정<br>
minlength = 최소 문자의 길이 설정<br>
size = 텍스트필드에 표시할 수 있는 글자갯수<br>
list = 연갈할 데이터의 목록을 지정함<br>







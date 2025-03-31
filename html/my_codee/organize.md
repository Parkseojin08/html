# 폼작성 태그

<form> 폼과 폼의 시작과 끝
<fielset> 폼의 요소를 그룹으로 묶는거
<legend> 폼 요소의 제목
<input> 사용자가 입력할 필드를 삽입
(여러종류의 input태그가 존재)
<select>,<option> 드롭다운목록 만들기
<textarea>텍스트를 여러줄 입력할수있다.


## <input>의 태그 유형(type)
input과 같이쓰이는 type의 유형
쓰는 방법
```html
<input type = "옵션">
```
"옵션"에 들어가는 유형

text = 텍스트입력 상자를 넣는다. 단 한줄짜리임
password = 비밀번호 입력상자를 만든다
&nbsp; ex) 비밀번호를 입력할때 "****"로 보이는 텍스트입력박스
search = 검색하는 입력상자를 만든다
&nbsp; ex) 텍스트 검색창 옆에 "X"아이콘이 뜸 (검색 내역지우기)
&nbsp; search로 만든 텍스트입력상자는 자동적으로 최근 작성내용저장됨
url = url주소를 입력할수 있는 필드를 넣는다
&nbsp; ex)text옵션이랑 다를게 없음 왜 구분?
&nbsp; -> Html의 태그를 "시멘틱태그"이기 때문 시멘틱태그의 주요 목적 "가독성" (코드 쉽게이해)
email = 이메일을 입력할수있는 텍스트창을 만든다
&nbsp; ex)여기도 텍스트박스랑 비슷함 만약에 형식에 구애받음
<P></P>
ex)required = 이 옵션은 필수항목을 표시하는 즉 항목 입력 X submit되지 않는 항목 각각 input 필드의 항목에 적용하면 그 형태가 다다름

ex) <input type = "email"> 라고 만든창에
내가 lgyaho 라고 입력하면 submit을 누르는 형식이 틀리다고 입력되지 않음
"형식의 구애받음"

tel = 전화번호 입력 텍스트 박스를 만든다.

checkbox = 주어진 항목에 선택할 수 있는 박스를 생성(중복 가능)
&nbsp; 모양 = "네모"

radio = 주어진 항목에서 선택할 수 있는 박스를 생성 (중복 불가)
&nbsp; radio박스를 묶어주는 작업이 필요
&nbsp; 옵션 name 과 for 이 두가지
&nbsp; name은 묶어줄떄 for은 연결할때 쓰는 옵션

ex)
```html
<input type = "radio" name = "2-1"> 
<input type = "radio" name = "2-2"> 
```
이런식으로 묶는 작업 필요

number = 숫자 조절 스핀 박스(텍스트 박스 끝에 위 아래 누르는 화살표)
range = 숫자를 조절할 수 있는 슬라이드 박스(횡스크롤 박스(세로형태))
data = 날자를 입력하는 창 (년 월 일) 사용자 사용 기준







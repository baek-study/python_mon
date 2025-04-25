# python 프로그래밍 입문
파이썬 프로그래밍 입문 수강자가 핵심 내용을 쉽게 알고, 실행 시켜 보는 페이지 입니다. <br> <br>

<hr size = "10px", width ="500px">

<br>

## 1주차
<ul>
  <li>
    파이썬 소개 - 인터프리터(Interpreter) 언어, 객체지향 언어     
  </li>
  <li>
    파이썬 통합 개발 환경 - IDLE, Colab, Jupyter Notebook 등    
  </li>
</ul>



<br>

## [2주차 실습&nbsp;-&nbsp;기본 구조](https://github.com/baek-study/python/blob/main/source/week2_answer.ipynb) <br>
[2주차 실습&nbsp;-&nbsp;프레임](https://github.com/baek-study/python/blob/main/source/week2.ipynb) 

### [파이썬 문장 구조]()
<ul>
  <li>주석: 한줄(#), 여러줄(''', """)  </li>
  <li> 문장: 처리를 수행하는 명령어 </li>
</ul>

### [표준출력함수 print()]()
<ul>
    <li> 문자열 : print('hello') </li>
    <li> 다양한자료형 : print(1004);print(3.14);</li>
    <li> 여러개 값: print(2, '+', 3)</li>
    <li> 출력제어문자: print('탭키\t줄바꿈\n')</li>
  </li>
</ul>

### [자료형(Data Type)]()
<ul>
  <li> 정수/int : print(123); print(123_456);</li>
  <li>  실수/float : print(3.14);print(3.14e12); </li>
  <li>  문자열/str: print("hello");print('100'+'200');</li>
  <li>  논리/bool: print(True); print(False);</li>
  <li>  type() : type(1234) # 자료형 확인</li>
  <li>  int() : int("100") #  정수로 변환 </li>
</ul>
<br>

## [3주차 실습&nbsp;-&nbsp;변수와 표준입력함수]()

### [변수 개념]()
<ul>
  <li>변수 : 데이터를 저장하는 공간 </li>
  <li>이름 규칙 : 알파벳(a~z, A~Z), 숫자(0~9), 밑줄(_)로 구성 </li>
  <li> 시작시 숫자 안됨, 이름내 공백 안됨, 예약어 안됨 </li>
</ul>

### [파이썬에서 변수]()
<ul>
  <li>변수이름 = 값 &ensp; </li>
  <li> 왼쪽은 항상 변수이름 </li>

  <li> x=1; y=3.14; z='hi'; b=True; </li>
</ul>

### [표준 입력함수 input()]()
<ul>
   <li>키보드를 통해 입력한 값을 하나의 '문자열' 형태로 반환</li>
    <li> msg = input('[안내메시지] 나이는?')&ensp;#문자열로 반환</li>
    <li> age = int(msg)&ensp;#정수변환</li>
    <li> fage = float(msg)&ensp;#실수변환</li>
</ul>

<br>

## [4주차 실습&nbsp;-&nbsp;연산자]()

### [산술/대입/복합 연산자]()
<ul>
  <li>산술: + - * / %(나머지) //(몫) **(제곱)</li>
  <li>대입: x=3; x=x+1; x=y=z=1;<br>
   &ensp; x,y = 1, 2; x, y = y,x; # 다중 대입 </li> 
  <li>복합: x+=3 &ensp;# x=x+3 같은의미  <br>
  &ensp;- 대입과 산술/기타 연산자 결합 </li>
</ul>

### [비교/논리 연산자]()
<ul>
  <li>비교 : == != > < >= <= <br>
  &ensp;- ==(같다), !=(같지않다)<br>
  &ensp;- >=, <=에서 =가 항상 뒤 </li>
  <li>논리 : and or not</li>
</ul>

<br>

## [5주차 실습&nbsp;-&nbsp;조건문]()

### [단순 if문 - 선택 명령 1개]()
<ul>    
  <li><b>if</b> score >= 60<b>:</b>&ensp;<br>
    &ensp;&nbsp;  print('pass') <br>
  </li>
</ul>

### [if~else 문- 선택 명령 2개]()
<ul>    
  <li><b>if</b> score >= 60<b>:</b>&ensp;<br>
    &ensp;&nbsp;  print('pass') <br>
    <b>else:</b>&ensp; <br>
    &ensp;&nbsp;  print('fail')
  </li>
</ul>

### [연속 if 문 - 선택 명령 3개 이상]()
  <ul>
  <li><b>if</b> score >= 90<b>:</b>&ensp;  <br>
    &ensp;&nbsp;print('A') <br>
    <b>elif</b> score >= 80<b>:</b>&ensp; <br>
    &ensp;&nbsp;print('B') <br>
    <b>else :</b>&ensp; <br>
    &ensp;&nbsp;print('C') <br>
  </li>
  </ul>

### [중첩 if 문 - if 안에 if]()  
<ul>
  <li><b>if</b> score >= 80<b>:</b>&ensp;  <br>
    &ensp;&ensp;&nbsp;<b>if</b> score >= 90<b>:</b>&ensp; <br>
    &ensp;&ensp;&nbsp;&ensp;&ensp;print('A') <br>
    &ensp;&ensp;&nbsp;<b>else :</b>&ensp; <br>
    &ensp;&ensp;&nbsp;&ensp;&ensp;print('B') <br>
    <b>else :</b>&ensp; <br>
    &ensp;&ensp;&nbsp;print('C') <br>
  </li>
</ul>
<br>

## [6주차 실습&nbsp;-&nbsp;문자열]()

### [문자열 생성 및 조작]()
<ul>
  <li> 생성 : msg = '안녕하세요' </li>
  <li> 인덱싱[순번] : msg[0]&ensp; #'안' </li>
  <li> 슬라이싱[시작:끝] : msg[2:4] &ensp; #'하세' <br>
  시작부터 (끝-1)까지 부분문자열</li>
  <li> 연산(+,*,in) : 'hi'+'mju'*3 <br>
    'm' in 'mju' # not in
  </li>  
</ul>

### [문자열 함수/메소드]()
<ul>
  <li> len(msg) : 문자열 길이 함수 </li>  
  <li> msg.split('/') : 문자열 분리 메소드 </li>  
  <li> msg.count('안') : 문자열 발견 횟수</li>  
  <li> msg.find('안') : 문자열 발견 위치 </li>  
</ul>
<br>

## [7주차 실습&nbsp;-&nbsp;반복문]()

### [서식 : f-문자열]()
<ul>
  <li> f'..{표현식}..' # 중괄호 사용  <br>
    ex) print(f'hi. {name}, age {25}') </li>
  <li> 형식지정: 정수 d, 실수 f, 문자 s </li>
  <li> 자릿수: {25:5d} &ensp; #다섯자리 확보 </li>
  <li> 정밀도: {3.145:.2f} &ensp; #소수점 몇자리 <br>
    ex) print(f'hi.{name:10s}, age {25:5d}, {PI:.2f}’)
  </li>  
</ul>

### [while 문]()
<ul>
  <li>범위 반복 : 초기, 반복조건(끝), 증감
  count = 0 # 초기값<br>
  <b>while</b> count < 5 <b>:</b> # 반복조건(끝) <br>
  &ensp;&ensp;print(f'{count}회') <br> 
  &ensp;&ensp;count += 1 # 즘감 <br> 
  </li>
  <li>조건 반복 : 조건이 만족되는 동안
  pwd = ' ' # 초기화<br>
  <b>while</b> pwd != 'mju' <b>:</b> # 조건 만족하는지? <br>
  &ensp;&ensp;pwd=input() <br> 
  </li>
</li>
</ul>

### [무한 루프]()
<ul>
  <li> <b>while True :</b> #  무한 루프<br>
  &nbsp; &nbsp; 문장들<br>
  &nbsp; &nbsp; if pwd == 'mju':
   &nbsp; &nbsp;&nbsp; &nbsp; break # 무한 루프 탈출 
</li>
<br>
  

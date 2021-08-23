# Caesar Cipher
#### 카이사르 암호

## 카이사르 암호란?
- Julius Caesar의 이름에서 유래됐다.
- 가장 간단하고 널리 알려진 암호기법 중 하나다.
- 치환 암호의 일종으로 알파벳을 암호키 숫자만큼 내려 적는다.
    - 암호키가 2 A<img src="https://render.githubusercontent.com/render/math?math=\rightarrow">Y, B<img src="https://render.githubusercontent.com/render/math?math=\rightarrow">Z, F<img src="https://render.githubusercontent.com/render/math?math=\rightarrow">D...
- 현대의 복잡한 암호 체계에서도 일부 사용된다.

## 카이사르 암호의 예

암호키가 3인 카이사르 암호

- ### 암호표

|원본문자|A|B|C|D|E|F|G|H|I|J|K|L|M|N|O|P|Q|R|S|T|U|V|W|X|Y|Z|
|--------|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
|암호문자|X|Y|Z|A|B|C|D|E|F|G|H|I|J|K|L|M|N|O|P|Q|R|S|T|U|V|W|

**Python<img src="https://render.githubusercontent.com/render/math?math=\rightarrow">Mvqelk**

- ### 수학적 접근

각 알파벳을 숫자로 치환
<br/>
A = 0, B = 1,...., Z = 25

**BIG DATA<img src="https://render.githubusercontent.com/render/math?math=\rightarrow">1 8 6&nbsp;&nbsp;3 0 19 0**
<br/>
<br/>
암호화

<img src="https://render.githubusercontent.com/render/math?math=E_n(x) = ( x"> - <img src="https://render.githubusercontent.com/render/math?math=n)"> mod 26.

**1 8 6&nbsp;&nbsp;3 0 19 0<img src="https://render.githubusercontent.com/render/math?math=\rightarrow">24 5 3&nbsp;&nbsp;0 23 16 23<img src="https://render.githubusercontent.com/render/math?math=\rightarrow">YFD AXQX**
<br/>
<br/>
복호화

<img src="https://render.githubusercontent.com/render/math?math=D_n(x) = (x ">+ <img src="https://render.githubusercontent.com/render/math?math=n)"> mod 26.

**YFD AXQX<img src="https://render.githubusercontent.com/render/math?math=\rightarrow">24 5 3&nbsp;&nbsp;0 23 16 23<img src="https://render.githubusercontent.com/render/math?math=\rightarrow">1 8 6&nbsp;&nbsp;3 0 19 0**

## 역사 및 사용

- Julias Caesar가 군사적 메시지를 전달하기 위해 사용하며 기록되었으며  암호는 기록 이전부터  계속 사용되어 왔다.

- 당시 암호는 효과적이였지만 암호의 보안이 뛰어난 것이  아닌 적 군사의 대부분이 문맹이였기 때문이라 주장되어진다.

- 19세기 신문의 개인광고를 통해  카이사르 암호를 사용한 간단한 암호문의 교환이 이루어졌다.

- 1915년 러시아군은 카이사르 암호를 사용했으며  독일군과 오스트리아 군은 이를 쉽게 해독해냈다.

- 2006년 Bernardo Provenzano라는 마피아보스는 변형된 카이사르 암호를 사용하다가 체포되었다.

- 오늘날 Caesar Cipher는 어린이 장난감의 암호해독링 등에서 볼 수 있다.

## 카이사르 암호의 보안성

카이사르 암호는 단순한만큼 누구나 쉽게 사용할 수 있다는 장점이 있다.  
하지만 단순한만큼 암호가 쉽게 해독될 수 있다.  
카이사르 암호는 카이사르 암호가 사용된다는 것을 알지만 암호값을 알지 못하는 상황과 카이사르 암호가 사용된다는 사실을 모르는 상황 모두 쉽게 해독될 수 있다.  
첫 번째 상황의 경우 카이사르 암호가 사용된다는 것을 아는 상황이기 때문에 무작위 대입 등을 통해 쉽게 해독이 가능하다.  
두번째 상황이라도 단순 대체 암호가 사용된다는 것을 알고 단어와 철자의 사용 빈도 등의 통계적 분석법으로 쉽게 해독이 가능하다.

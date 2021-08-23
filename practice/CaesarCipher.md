# Caesar Cipher
#### 카이사르 암호

## 카이사르 암호란?
- Julius Caesar의 이름에서 유래됐다.
- 가장 간단하고 널리 알려진 암호기법 중 하나다.
- 치환 암호의 일종으로 알파벳을 암호키 숫자만큼 내려 적는다.
    - 암호키가 2 A $\rightarrow$ Y, B $\rightarrow$ Z, F $\rightarrow$ D...
- 현대의 복잡한 암호 체계에서도 일부 사용된다.

## 카이사르 암호의 예

암호키가 3인 카이사르 암호

- ### 암호표

|원본문자|A|B|C|D|E|F|G|H|I|J|K|L|M|N|O|P|Q|R|S|T|U|V|W|X|Y|Z|
|--------|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
|암호문자|Y|Z|A|B|C|D|E|F|G|H|I|J|K|L|M|N|O|P|Q|R|S|T|U|V|W|X|

**Python $\rightarrow$ Nwrfml**

- ### 수학적 접근

각 알파벳을 숫자로 치환
<br/>
A = 0, B = 1,...., Z = 25

**BIG DATA %\rightarrow% 1 8 6&nbsp;&nbsp;3 0 19 0**
<br/>
<br/>
암호화

$E_n(x) = (x - n)$ mod 26.

**1 8 6&nbsp;&nbsp;3 0 19 0 $\rightarrow$ 24 5 3&nbsp;&nbsp;0 23 16 23 $\rightarrow$ YFD AXQX**
<br/>
<br/>
복호화

$D_n(x) = (x + n)$ mod 26.

**YFD AXQX $\rightarrow$ 24 5 3&nbsp;&nbsp;0 23 16 23 $\rightarrow$ 1 8 6&nbsp;&nbsp;3 0 19 0**

## 역사 및 사용

- Julias Caesar가 군사적 메시지를 전달하기 위해 사용하며 기록되었으며  암호는 기록 이전부터  계속 사용되어 왔다.

- 당시 암호는 효과적이였지만 암호의 보안이 뛰어난 것이  아닌 적 군사의 대부분이 문맹이였기 때문이라 주장되어진다.

- 19세기 신문의 개인광고를 통해  Caesar Cipher를 사용한 간단한 암호문의 교환이 이루어졌다.

- 1915년 러시아군은 Caesar Cipher를 사용했으며  독일군과 오스트리아 군은 이를 쉽게 해독해냈다.

- 2006년 Bernardo Provenzano라는 마피아보스는 변형된 Caesar Cipher를 사용하다가 체포되었다.

- 오늘날 Caesar Cipher는 어린이 장난감의 암호해독링 등에서 볼 수 있다.



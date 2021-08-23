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

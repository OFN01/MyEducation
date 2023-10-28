<style>
table.ncol {
    background: transparent !important;
    border: 0px !important;
    width: 100% !important;
}
.col {
    background: transparent !important;
    border: 0px !important;
}


span.frac {
  display: inline-block;
  text-align: center;
  vertical-align: middle;
}
span.frac > sup, span.frac > sub {
  display: block;
  font: inherit;
  padding: 0 0.3em;
}
span.frac > sup {border-bottom: 0.08em solid;}
span.frac > span {display: none;}
</style>

# TYT-Matematik
## Sayı Kümeleri

<table class="ncol" markdown=1 class=col>
<td markdown=1 class=col>**`N`**: Doğal sayılar `(0, 1, 2, 3, 4, ...)`
**`Z`**: Tam sayılar `(..., -2, -1, 0, 1, 2, ...)`
**<code markdown=1>Z<sup>+</sup></code>**: Pozitif tam sayılar `(1, 2, 3, 4, 5, ...)`
**<code markdown=1>Z<sup>-</sup></code>**: Negatif tam sayılar `(..., -5, -4, -3, -2, -1)`
**`R`**: Reel sayılar (Karesi pozitif olan bütün sayılar)
**`Q`**: Rasyonel sayılar `(..., -1/2, -1/5, 2/5, 3/4, 9/5, ...)`
**`Q'`**: İrrasyonel sayılar `(..., e=2.718281828459045, π=3.14159265359, ...)`
</td>
<td markdown=1 class=col><img width="300" src="https://matematikproje.files.wordpress.com/2017/03/sayi-kumeleri1.jpg?w=640" alt="Sayı kümeleri">
</td>
</table>

<pre markdown=1><h6>Örnek Soru:</h6>m ve n gerçel sayılardır. <b>m + n = 21</b> olduğuna göre m * n çarpımı en yüksek kaç olur?
<div align=left>A) 110&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;B) 108&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;C) 112&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<b>D) 225/4</b>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;E) 441/2</div></pre>

## Pozitif ve Negatif Sayılar
<table class="ncol" markdown=1>
<td markdown=1 class=col>`+` + `+` = `+`
`-` + `-` = `-`
</td>
<td markdown=1 class=col>`+` * `+` = `+`
`+` / `+` = `+`
</td>
<td markdown=1 class=col>`+` * `-` = `-`
`+` / `-` = `-`
</td>
<td markdown=1 class=col>`-` * `-` = `+`
`-` / `-` = `+`
</td>
</table>

### Kuvvet alma
`n` bir tam sayı olmak üzere.
<table class="ncol" markdown=1>
<td markdown=1 class=col>`a > 0` **ise** <code>a<sup>n</sup> > 0</code>
</td>
<td markdown=1 class=col>`a < 0` **ise** <code>a<sup>2n</sup> > 0</code>
`a < 0` **ise** <code>a<sup>2n-1</sup> < 0</code>
</td>
</table>

## Asal Sayılar
<table class=ncol markdown=1>
<td class=col markdown=1>Asal sayılar sadece kendisine ve 1'e tam bölünen sayılardır.
`2, 3, 5, 7, 11, 13, ...`
- 2'den başka çift asal sayı yoktur.
- 5'den başka sonu 5 ya da 0 ile biten asal sayı da yoktur.
Bir sayının asal sayı olup olmadığını bulmanın en kolay yolu son hanesinin çift, ya da 5 olup olmadığına bakmak, eğer ikisi de değilse kareköküne kadar olan asal sayılara bölmektir.
</td>
<td class=col markdown=1 style="width: 20%;"><h4>Mersenne Asalı</h4>`n` asal sayı ise,
<code markdown=1>2<sup>n</sup> - 1</code> asal sayıdır.
</td>
</table>

## Sonlu Toplamlar
<table class=ncol markdown=1>
<td aclass=col markdown=1>`1+2+3+4+...+n` = <span class="frac"><sup>n(n+1)</sup><span>&frasl;</span><sub>2</sub></span>

`2+4+6+8+...+2n` = n(n+1)

`1+3+5+7+...+2n-1` = n<sup>2</sup>
</td>
<td aclass=col markdown=1 width=50%>
`Terim Sayısı` = <span class="frac"><sup><code>Son Terim</code> - <code>İlk Terim</code></sup><span>&frasl;</span><sub><code>Artış Miktarı</code></sub></span>+1

`Terimler Toplamı` = <span class="frac"><sup><code>Son Terim</code> + <code>İlk Terim</code></sup><span>&frasl;</span><sub>2</sub></span>*`Terim Sayısı`
</td>
</table>

<br><br>

## EBOB - EKOK
<table class=ncol markdown=1><td padding-top=0px class=col markdown=1>EBOB = `En Büyük Ortak Bölen`
EKOK = `En Küçük Ortak Kat`


EKOK(a,b) = <span class="frac"><sup>|a * b|</sup><span>&frasl;</span><sub>EBOB(a,b)</sub></span>
<br><br><br>

</td>
<td class=col markdown=1 width=45%><div class=crop><img width=450px src="https://gcdnb.pbrd.co/images/RUjH3FIvFXKS.png?o=1">
</div>
</td>
</table>

## Asal Çarpanlara Ayırma
<code>X<sub>1</sub>, X<sub>2</sub>, X<sub>3</sub>, X<sub>4</sub>, ...</code> `asal sayılar` ve <code>Y<sub>1</sub>, Y<sub>2</sub>, Y<sub>3</sub>, Y<sub>4</sub>, ...</code> `pozitif tam sayılar` olmak üzere **A** tam sayısını,

A = X<sub>1</sub><sup>Y<sub>1</sub></sup> * X<sub>2</sub><sup>Y<sub>2</sub></sup> * X<sub>3</sub><sup>Y<sub>3</sub></sup> * X<sub>4</sub><sup>Y<sub>4</sub></sup>*...

şeklinde yazmaya **asal çarpanlara ayırmak** denir.

X<sub>1</sub><sup>Y<sub>1</sub></sup> * X<sub>2</sub><sup>Y<sub>2</sub></sup> * X<sub>3</sub><sup>Y<sub>3</sub></sup> * X<sub>4</sub><sup>Y<sub>4</sub></sup>*... sayısının `pozitif bölen sayısı` = (Y<sub>1</sub>+1) + (Y<sub>2</sub>+1) + (Y<sub>3</sub>+1) + (Y<sub>4</sub>+1) + ...
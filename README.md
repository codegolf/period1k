JS1K 2016 ENTRY: PERIOD1K
===

(updated in june 2016 with the names of the four new elements)

by @MaximeEuziere, @innovati and @subzey

JS1k submission:

- Commented source: http://codegolf.github.io/period1k/final.html
- Minified (1764b JS): http://codegolf.github.io/period1k/final.min.html
- Minified and packed (1020b JS): http://codegolf.github.io/period1k/final.min.pack.html

Wallpaper:

- 4000x3000 (0.3Mb, PNG): http://codegolf.github.io/period1k/wallpaper.png

----

After JS1k:

- Golfed (1024b HTML+ES6, no canvas): http://codegolf.github.io/period1k/final.min.golfed.html
- Commented: http://codegolf.github.io/period1k/golfed.commented.html
- Source code:

````html
<body onload="i=j=b.bgColor=0;'H9xc#He3yk#Li0zmBe1y9B8w5C9sdNqt#
Op8#F2qg#Ne3mm#Na0nbMg1jvAl7k6Si8g5P9h1ScyCl2f9#Ar3kn#K0b6Ca16sS
c6d8Tie7VfmCrbgMnciFe7xCo9dNi1lCu7zZn5yGa7awGe8bvAsb4Se9f9Br2aq~
Kr3eg#Rb0bzSr1auY67bZr6mNb47Mo5jTc3vRu5jRh3jPd66Ag33Cd8lIn786Snb
vSb8d8TemcI2daXe3id#Cs0frBa1kxLa4i7CeegPr9jNdboPm6fSmegEubsGdjdT
bgxDyjqHojdEriqTmg9Yb5vLu443Hf66rTa6hW7eRe6vOsaxIr9cPta6Au8bHgb9
~Tl7eoPbfeBid8Po64At21tRn3s4#Fr0nsRa1p1Ac5kpThriPahmUtxNpk3PuwgA
mmkCmqlBkjhCfniEsj6Fmq0MdloNohcLr5tqRf6peDbl3SgmbBhcfHsotMtkiDsl
rRghfCnioNh7edFlflMc8hLvciTs287Og313#H'.replace(/(..*?)(\d)?(..)
(#)?(~)?(?=[A-Z])/g,(u,v,w,x,y,z)=>{b.innerHTML+=`<center style=
'position:absolute;top:${~~(j/18)*5.4+2}vw;left:${j%18*5+4.5}vw;
font:1vw arial;width:4vw;padding:.4vw;color:#fff;background:hsl(
${35*(w?t=w:t)},70%,40%)'>${i+1} ${y?'G':z?'L':'S'}<h2 style='ma
rgin:0;text-shadow:3px 2px #222'>${v}</h2>`+((parseInt(x,36)+256
*i-(68<i?570:1100))/100).toFixed(2)+'* '[42!=i^60!=i^83>i];j+={0
:17,3:11,11:11,69:-68,55:54,87:54,101:-68}[i++]|1})"id=b>
````

````
Legend
======

    :        : 
    : group  :
 ...:________:
    |        |
 p  |  1  G -|--> state at room temperature (Gas / Liquid / Solid)
 e  |  ^-----|--> atomic number (Z)
 r  |   H ---|--> name
 i  |        |  
 o  |  1.00 -|--> atomic mass + stability (* = has no stable isotope)
 d  |       -|--> type: green = noble gas
 ...|________|          light green = halogen
                        purple = metalloid
                        dark blue = poor metal
                        blue = transition metal
                        light blue = lanthanoid
                        light green = actinoid
                        brown = alkaline earth metal
                        pink = alkali metal
                        red = non-metal
````
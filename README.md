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
<body onload='for(i=j=z=0;j<178;j++,(z=z?z-1:{117:20,0:16,3:10,1
1:10,69:4}[i]|0)||(i+={117:-61,87:15,69:18,55:15}[i]|1))[w,y]="H
1He1LiBeBCN1O1F1Ne1NaMgAlSiPSCl1Ar1KCaScTiVCrMnFeCoNiCuZnGaGeAsS
eBr2Kr1RbSrYZrNbMoTcRuRhPdAgCdInSnSbTeIXe1CsBaLaCePrNdPmSmEuGdTb
DyHoErTmYbLuHfTaWReOsIrPtAuHg2TlPbBiPoAtRn1FrRaAcThPaUNpPuAmCmBk
CfEsFmMdNoLrRfDbSgBhHsMtDsRgCnNhFlMcLvTsOg1".split(/(?=[A-Z])/)[
i].split(/(?=\d)/),b.innerHTML+=`<center style="font:1vw arial;f
loat:left;width:4vw;margin:.2vw;padding:.4vw;color:#fff${";"[z]}
background:hsl(${35*(.1*("#{p 7{n 7{bbbbbnp7{bbbbbmx7{LLLLLLLNbb
bbmm7{WWWWWWWXbbbbmm7".charCodeAt(i/2)-32)+"")[i%2*2]|0},70%,40%
)">${i+1} ${"SGL"[y||0]}<h2>${w}</h2>`+((parseInt("xcykzmy9w5sdq
tp8qgmmnbjvk6g5h1cyf9knb66sd8e7fmbgci7x9d1l7z5yawbvb4f9aqegbzau7
b6m475j3v5j3j66338l86bvd8mcdaidfrkxi7eg9jbo6fegbsjdgxjqjdiqg95v4
36r6h7e6vax9ca68bb9eofed8641ts4nsp1kprihmtxk3wgmkqljhnij6q0lohct
qpel3mbcfotkilrhfioedfl8hci8713".substr(2*i,2),36)+256*i-(68<i?5
70:1100))/100).toFixed(2)+"* "[42!=i^60!=i^83>i]'id=b bgColor=0>
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
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

After JS1k:

- Golfed (1023b HTML+ES6, no canvas): http://codegolf.github.io/period1k/final.min.golfed.html

````html
<body onload='for(i=j=z=0;j<178;j++,(z=z?z-1:{117:20,0:16,3:10,1
1:10,69:4}[i]|0)||(i+={117:-61,87:15,69:18,55:15}[i]|1))y=0,b.in
nerHTML+=`<center style="font:.9vw arial;float:left;width:4vw;ma
rgin:.2vw;padding:.5vw;color:#fff${";"[z]}background:hsl(${35*(.
1*("#{p 7{n 7{bbbbbnp7{bbbbbmx7{LLLLLLLNbbbbmm7{WWWWWWWXbbbbmm7"
.charCodeAt(i/2|0)-32)+"")[i%2*2]|0},80%,35%)">${i+1}<h2 style=m
argin:0>${"H1He1LiBeBCN1O1F1Ne1NaMgAlSiPSCl1Ar1KCaScTiVCrMnFeCoN
iCuZnGaGeAsSeBr2Kr1RbSrYZrNbMoTcRuRhPdAgCdInSnSbTeIXe1CsBaLaCePr
NdPmSmEuGdTbDyHoErTmYbLuHfTaWReOsIrPtAuHg2TlPbBiPoAtRn1FrRaAcThP
aUNpPuAmCmBkCfEsFmMdNoLrRfDbSgBhHsMtDsRgCnNhFlMcLvTsOg1".split(/
(?=[A-Z])/)[i].replace(/\d/,d=>[[][y=d]])}</h2>${((parseInt("xcy
kzmy9w5sdqtp8qgmmnbjvk6g5h1cyf9knb66sd8e7fmbgci7x9d1l7z5yawbvb4f
9aqegbzau7b6m475j3v5j3j66338l86bvd8mcdaidfrkxi7eg9jbo6fegbsjdgxj
qjdiqg95v436r6h7e6vax9ca68bb9eofed8641ts4nsp1kprihmtxk3wgmkqljhn
ij6q0lohctqpel3mbcfotkilrhfioedfl8hci8713".substr(2*i,2),36)+256
*i-(68<i?570:1100))/100).toFixed(2)} `+"sgl"[y]'id=b bgColor=0>
````

````
Legend
======

     |        | 
     | group  |
 ____|________|
  p  |        |
  e  |        |
  r  |   1 ---|--> atomic number (Z)
  i  |   H ---|--> name + state at room temperature (. = gas / ~ = liquid)
  o  |  1.00 -|--> atomic mass + stability (* = no stable isotope)
  d  |       -|--> type: green = noble gas
 ____|________|          light green = halogen
                         purple = metalloid
                         dark blue = poor metal
                         blue = transition metal
                         light blue = lanthanoid
                         light green = actinoid
                         brown = alkaline earth metal
                         pink = alkali metal
                         red = non-metal
````
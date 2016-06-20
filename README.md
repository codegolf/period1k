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

- Golfed (1020b HTML+ES6, no canvas): http://codegolf.github.io/period1k/final.min.golfed.html

````html
<body onload='for(i=j=0;178>j;j+={117:21,0:17,3:11,11:11,69:5}[i]|1,
i+={117:-61,87:15,69:18,55:15}[i]|1)b.innerHTML+=`<font face=arial><
center style=background:hsl(${35*(.1*("#{p 7{n 7{bbbbbnp7{bbbbbmx7{L
LLLLLLNbbbbmm7{WWWWWWWXbbbbmm7".charCodeAt(i/2|0)-32)+"")[i%2*2]|0},
60%,45%);position:absolute;left:${50+j%18*80}px;top:${30+(j/18|0)*83
}px;width:4em;color:#fff;padding:6px>${i+1}<h2 style=margin:0>${"H.H
e.LiBeBCN.O.F.Ne.NaMgAlSiPSCl.Ar.KCaScTiVCrMnFeCoNiCuZnGaGeAsSeBr ~K
r.RbSrYZrNbMoTcRuRhPdAgCdInSnSbTeIXe.CsBaLaCePrNdPmSmEuGdTbDyHoErTmY
bLuHfTaWReOsIrPtAuHg ~TlPbBiPoAtRn.FrRaAcThPaUNpPuAmCmBkCfEsFmMdNoLr
RfDbSgBhHsMtDsRgCnNhFlMcLvTsOg.".split(/(?=[A-Z])/)[i]}</h2>${(parse
Int("xcykzmy9w5sdqtp8qgmmnbjvk6g5h1cyf9knb66sd8e7fmbgci7x9d1l7z5yawb
vb4f9aqegbzau7b6m475j3v5j3j66338l86bvd8mcdaidfrkxi7eg9jbo6fegbsjdgxj
qjdiqg95v436r6h7e6vax9ca68bb9eofed8641ts4nsp1kprihmtxk3wgmkqljhnij6q
0lohctqpel3mbcfotkilrhfioedfl8hci8713".substr(2*i,2),36)+256*i-(68<i
?570:1100))/100..toFixed(2)}`+"* "[42!=i^60!=i^83>i]'bgColor=0 id=b>
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
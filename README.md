```Con el siguiente código podemos crear una tabla periódica de los elementos químicos en HTML y JavaScript```

```Con el siguiente código iniciamos el documento HTML:```
```<HTML>```

```Con el siguiente código iniciamos la cabeza del documento HTML y le colocamos el título al documento```
```<HEAD>
<title>Tabla Periódica de Elementos</title>

Con el siguiente cóodigo creamos la función JavaScript llamada click()

<script language="JavaScript">
function click() { 
if (event.button==2) { 
alert ('Este boton esta desabilitado.') 
} 
}

Aqui asociamos el evento onmousedown a la función click, este permite que cuando
coloquemos el apuntador del mouse sobre cada elemeto aparezca en el formulario su información

document.onmousedown=click

Aquí asociamos la información de los elementos químicos a los cuadros de texto del formulario

function prop(elem,num,pes,dens,estruc,punt,desc)  {
Box = document.tabper
Box.elemento.value =elem;
Box.numero.value =num;
Box.descubridor.value =desc;
Box.peso.value =pes;
Box.punto.value =punt;
Box.densidad.value =dens;
Box.estructura.value =estruc;
}
function nada() {return}
</script>
</HEAD>

Aqui creamos dentro del cuerpo del documento HTML una tabla para almacenar la información de la tabla periódica

<BODY TEXT="#000000" BGCOLOR="#FFFFFF">
<CENTER>
<TABLE border="6" cellspacing="2" name="introduccion" WIDTH=700>
<tr>
<td WIDTH="10" bgcolor="#FFFFFF" height=30></td>
<td height=30 colspan="16" bgcolor="#FFEFD5" align=CENTER><b><font size="3" face="Arial" color="#000000">LA TABLA PERIÓDICA</font></b></td>
<td WIDTH="10" bgcolor="#FFFFFF" height=30></td>
</tr>
</table>
<div align=CENTER> <form name="tabper"> 
<table border="6" cellspacing="2" name="elementos">
<tr>
<td colspan="1" bgcolor="#FFFFFF" height=30></td>
<td  height=30 colspan="16" bgcolor="#FFEFD5" align=CENTER><b><font size="3" face="Arial">CLASIFICACIÓN</font></b></td>
<td colspan="1" bgcolor="#FFFFFF" height=30></td>
</tr>
<tr>
<td colspan="1" bgcolor="#FFFFFF" height=24></td> 
<td height=30 colspan="4" bgcolor="#6495ED" align=CENTER valign=MIDDLE> 
<b><font size="3" face="Arial">SOLIDOS</font></b></td>
<td colspan="4" bgcolor="#CC99CC" align=CENTER><b><font size="3" face="Arial">LÍQUIDOS</font></b></td>
<td colspan="4" bgcolor="#98FB98" align=CENTER><b><font size="3" face="Arial">GASEOSOS</font></b></td>
<td colspan="4" bgcolor="#FFCC99" align=CENTER><b><font size="3" face="Arial">OTROS</font></b></td>
<td colspan="1" bgcolor="#FFFFFF" height=30></td>
</tr>
<tr>
<td colspan="18" bgcolor="#FFFFFF" height=4></td>
</tr>
<tr>
<td colspan="1" bgcolor="#FFFFFF" height=24></td>
<td  height=30 colspan="16" bgcolor="#FFEFD5" align=CENTER><b><font size="3" face="Arial">TABLA DE LOS ELEMENTOS</font></b></td>
<td colspan="1" bgcolor="#FFFFFF" height=30></td>
</tr>
<tr>
</tr>
<tr> 
<td width=32 height=30 align=CENTER bgcolor="#98FB98"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Hidrógeno','1','1.0079','0.071','1s1','-252.7','Cavendish 1766');">1<br>
H</a></font></td>
<td colspan="16"  height=30 align="LEFT" bgcolor="#FFFFFF"></td>
<td width=32 height=30 align=CENTER bgcolor="#98FB98"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Hélio','2','4.0026','0.126','1s2','-268.9','Janssen 1868');">2<br>
He</a></font></td>
</tr>
<tr> 
<td width=32 height=30 align=CENTER bgcolor="#6495ED"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Litio','3','6.939','0.53','2s1','1330','Arfvedson 1817');">3<br>
Li</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#6495ED"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Berilio','4','9.0122','1.85','2s2','2770','Vauquelin 1798');">4<br>
Be</a></font></td>
<td colspan="10"  height=30 align="LEFT" bgcolor="#FFFFFF"></td>
<td width=32 height=30 align=CENTER bgcolor="#6495ED"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Boro','5','10.811','2.34','2p1','2550','Gay-Lussac & Thenard-Davy 1808');">5<br>
B</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#6495ED"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Carbono','6','12.011','2.26','2p2','4830','(Origen natural)');">6<br>
C</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#98FB98"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Nitrógeno','7','14.0067','0.81','2p3','-195.8','Rutherford 1772');">7<br>
N</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#98FB98"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Oxígeno','8','15.999','1.14','2p4','-183.0','Preistley 1774');">8<br>
O</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#98FB98"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Fluor','9','18.998','1.505','2p5','-188.14','Moissan 1886');">9<br>
F</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#98FB98"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Neón','10','20.183','1.20','2p6','-246.1','Ramsay & Travers 1898');">10<br>
Ne</a></font></td>
</tr>
<tr> 
<td width=32 height=30 align=CENTER bgcolor="#6495ED"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Sodio','11','22.98977','0.97','3s1','882.9','Davy 1807');">11<br>
Na</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#6495ED"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Manganeso','12','24.305','1.74','3s2','1090','Black 1775');">12<br>
Mg</a></font></td>
<td colspan="10"  height=30 bgcolor="#FFFFFF" align=LEFT></td>
<td width=32 height=30 align=CENTER bgcolor="#6495ED"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Aluminio','13','26.98154','2.70','3p1','2467','Wohler 1827');">13<br>
Al</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#6495ED"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Silicio','14','28.0855','2.33','3p2','2355','Berzelius 1824');">14<br>
Si</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#6495ED"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Fósforo','15','30.97376','1.82','3p3','280','Brand 1669');">15<br>
P</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#6495ED"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Azufre','16','32.06','2.07','3p4','444.6','(Origen natural)');">16<br>
S</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#98FB98"><font face="Arial" size="3"><a href="javascript:nada()" onMouseOver="prop('Cloro','17','35.453','1.56','3p5','-34.6','Scheele 1774');">17<br>
Cl</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#98FB98"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Argón','18','39.948','1.40','3p6','-186','Rayleigh & Ramsay 1894');">18<br>
Ar</a></font></td>
</tr>
<tr> 
<td width=32 height=30 align=CENTER bgcolor="#6495ED"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Potasio','19','39.0983','0.86','4s1','774','Davy 1807');">19<br>
K</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#6495ED"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Calcio','20','40.08','1.55','4s2','1484.4','Davy 1808');">20<br>
Ca</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#6495ED"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Escandio','21','44.9559','3.0','3d1','2832','Nilson 1879');">21<br>
Sc</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#6495ED"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Titanio','22','47.90','4.51','3d2','3287','Gregor 1791');">22<br>
Ti</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#6495ED"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Vanadio','23','50.9415','6.1','3d3','3380','del Rio 1901','6.11','9');">23<br>
V</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#6495ED"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Cromo','24','51.996','7.19','3d5','2672','Vauquelin 1797');">24<br>
Cr</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#6495ED"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Manganeso','25','54.9380','7.43','3d5','1962','Gahn, Scheele & Bergman 1774');">25<br>
Mn</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#6495ED"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Hierro','26','55.847','7.86','3d6','2750','(Origen natural)');">26<br>
Fe</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#6495ED"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Cobalto','27','58.9332','8.9','3d7','2870','Brandt c.1735');">27<br>
Co</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#6495ED"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Niquel','28','58.71','8.9','3d8','2732','Cronstedt 1751');">28<br>
Ni</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#6495ED"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Cobre','29','63.546','8.96','3d10','2567','(Origen natural)');">29<br>
Cu</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#6495ED"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Cinc','30','65.38','7.14','3d10','907','(Origen natural)');">30<br>
Zn</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#6495ED"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Galio','31','69.735','5.91','4p1','2403','Boisbaudran 1875');">31<br>
Ga</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#6495ED"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Germanio','32','72.59','5.32','4p2','2830','Winkler 1886');">32<br>
Ge</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#6495ED"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Arsénico','33','74.9216','5.72','4p3','613','Albertus Magnus 1250');">33<br>
As</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#6495ED"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Selenio','34','78.96','4.79','4p4','684.9','Berzelius 1817');">34<br>
Se</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#CC99CC"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Bromo','35','79.904','3.12','4p5','58.78','Balard 1826');">35<br>
Br</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#98FB98"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Kripton','36','83.80','2.6','4p6','-153.4','Ramsay & Travers 1898');">36<br>
Kr</a></font></td>
</tr>
<tr> 
<td width=32 height=30 align=CENTER bgcolor="#6495ED"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Rubídio','37','85.467','1.53','5s1','688','Bunsen & Kirchoff 1861');">37<br>
Rb</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#6495ED"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Estroncio','38','87.62','2.6','5s2','1384','Davy 1808');">38<br>
Sr</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#6495ED"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Itrio','39','88.9059','4.47','4d1','3337','Gadolin 1794');">39<br>
Y</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#6495ED"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Circonio','40','91.22','6.49','4d2','4377','Klaproth 1789');">40<br>
Zr</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#6495ED"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Niobio','41','92.9064','8.4','4d4','4927','Hatchett 1801');">41<br>
Nb</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#6495ED"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Molibdeno','42','95.94','10.2','4d5','4612','Scheele 1778');">42<br>
Mo</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#FFCC99"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Tecnecio','43','98.9062','11.5','4d6','4877','Perrier & Segre 1937');">43<br>
Tc</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#6495ED"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Rutenio','44','101.07','12.2','4d7','3900','Klaus 1844');">44<br>
Ru</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#6495ED"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Radio','45','102.9055','12.4','4d8','3727','Wollaston 1803');">45<br>
Rh</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#6495ED"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Paladio','46','106.4','12.0','4d10','2927','Wollaston 1803');">46<br>
Pd</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#6495ED"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Plata','47','107.868','10.5','4d10'','2212','(Origen natural)');">47<br>
Ag</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#6495ED"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Cadmio','48','112.41','8.65','4d10','765','Stromeyer 1817');">48<br>
Cd</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#6495ED"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Indio','49','114.82','7.31','5p1','2000±10','Riech & Richter 1863');">49<br>
In</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#6495ED"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Estaño','50','118.69','7.30','5p2','2270','(Origen natural)');">50<br>
Sn</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#6495ED"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Antimonio','51','121.75','6.62','5p3','1750','(Origen natural)');">51<br>
Sb</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#6495ED"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Telurio','52','127.60','6.24','5p4','989.8','von Reichenstein 1782');">52<br>
Te</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#6495ED"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Yodo','53','126.9045','4.94','5p5','183','Cortois 1811');">53<br>
I</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#98FB98"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Xenón','54','131.30','3.06','5p6','-108.1','Ramsay & Travers 1898');">54<br>
Xe</a></font></td>
</tr>
<tr> 
<td width=32 height=30 align=CENTER bgcolor="#6495ED"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Cesio','55','132.9054','1.90','6s1','678.4','Bunsen & Kirchoff 1863');">55<br>
Cs</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#6495ED"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Bario','56','137.33','3.5','6s2','1140','Davy 1808');">56<br>
Ba</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#6495ED"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Lantano','57','138.9055','6.17','5d1','3469','Mosander 1839');">57<br>
La</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#6495ED"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Hafnio','72','178.49','13.1','5d2','5400','Coster & von Hevesy 1923');">72<br>
Hf</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#6495ED"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Tántalo','73','180.947','16.6','5d3','5425±100','Ekeberg 1801');">73<br>
Ta</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#6495ED"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Volframio','74','183.85','19.3','5d4','5660','J. & F. d\'Elhuyar 1783');">74<br>
W</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#6495ED"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Renio','75','186.207','21.0','5d5','5627','Noddack, Berg & Tacke 1925');">75<br>
Re</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#6495ED"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Osmio','76','190.2','22.6','5d6','5027','Tennant 1803');">76<br>
Os</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#6495ED"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Iridio','77','192.22','22.5','5d7','4527±100','Tennant 1803');">77<br>
Ir</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#6495ED"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Platino','78','195.09','21.4','5d9','3827','Ulloa 1735');">78<br>
Pt</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#6495ED"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Oro','79','196.9665','19.3','5d10','2807','(Origen natural)');">79<br>
Au</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#CC99CC"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Mercurio','80','200.59','13.6','5d10','356.58','(Origen natural)');">80<br>
Hg</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#6495ED"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Talio','81','204.37','11.85','6p1','1457±10C','Crookes 1861');">81<br>
Tl</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#6495ED"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Plomo','82','207.2','11.4','6p2','1740','(Origen natural)');">82<br>
Pb</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#6495ED"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Bismuto','83','208.9804','9.8','6p3','1560±5C','Geoffroy 1753');">83<br>
Bi</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#6495ED"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Polonio','84','(209)','9.2','6p4','962','Curie 1898');">84<br>
Po</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#6495ED"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Astato','85','(210)','--','6p5','337','Corson et al. 1940');">85<br>
At</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#98FB98"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Radón','86','(222)','--','6p6','-61.8','Dorn 1900');">86<br>
Rn</a></font></td>
</tr>
<tr> 
<td width=32 height=30 align=CENTER bgcolor="#6495ED"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Francio','87','(223)','--','7s1','677','Perey 1938');">87<br>
Fr</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#6495ED"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Radio','88','226.0254','5.0','7s2','1737','P. & M. Curie 1898');">88<br>
Ra</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#6495ED"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Actinio','89','(227)','--','6d1','3200±300','Debierne 1899');">89<br>
Ac</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#FFCC99"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Kurchatovio','104','(261)','18','6d2','2','Lawrence Berkeley Lab-USA 1964');"> 104<br>
Ku</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#FFCC99"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Hamnium','105','(262)','--','6d3','--','Lawrence Berkeley Lab-USA 1967');"> 105<br>
Ha</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#FFCC99"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Unnilhexium','106','(263)','--','6d4','--','Lawrence Berkeley Lab-USA 1974');"> 106<br>
Unh</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#FFCC99"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Unilseptio','107','(262)','--','6d5','--','Armbruster, Münzenber 1981');"> 107<br>
Uns</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#FFCC99"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Unniloctio','108','(265)','--','--','--','Armbruster, Munzenber 1984');"> 108<br>
Uno</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#FFCC99"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Unnilenium','109','(266)','--','--','--','Armbruster, Munzenber  1982');"> 109<br>
Une</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#FFCC99"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Ununnilio','110','(269)','--','--','--','Hofmann, Ninov  GSI-Germany 1994');"> 110<br>
Uun</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#FFCC99"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Unununio','111','(272)','--','--','--','Hofmann, Ninov  GSI-Germany 1994');"> 111<br>
Uuu</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#FFCC99"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Ununbio','112','(277)','--','--','--','Hofmann, Ninov GSI-Germany 1996');"> 112<br>
Uub</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#FFCC99"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Ununtrio','113','--','--','--','--','(no se ha descubierto aún)');">113<br>
Uut</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#FFCC99"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Ununquadio','114','--','--','--','--','(no se ha descubierto aún)');">114<br>
Uuq</a></font></td>
<td colspan="4" height="30" bgcolor="#FFFFFF"></td>
</tr>
<tr> 
</tr>
<tr> 
<td colspan="3" bgcolor="#FFFFFF"></td>
<td width=32 height=30 align=CENTER bgcolor="#6495ED"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Cerio','58','140.12','6.67','4f2','3257','Berzelius & Hisinger; Klaproth 1803');"> 58<br>
Ce</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#6495ED"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Praseodimio','59','140.9077','6.77','4f3','3127','von Weisbach 1885');">59<br>
Pr</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#6495ED"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Neodimio','60','144.24','7.0','4f4','3127','von Weisbach 1885');">60<br>
Nd</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#6495ED"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Prometio','61','(145)','--','4f5','--','Marinsky et al. 1945');">61<br>
Pm</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#6495ED"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Samario','62','150.4','7.54','4f6','1900','Boisbaudran 1879');">62<br>
Sm</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#6495ED"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Europio','63','151.96','5.26','4f7','1597','Demarcay 1896');">53<br>
Eu</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#6495ED"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Gadolinio','64','157.25','7.89','4f7','3233','Marignac 1880');">64<br>
Gd</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#6495ED"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Terbio','65','158.9254','8.27','4f9','3041','Mosander 1843');">65<br>
Tb</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#6495ED"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Disprosio','66','162.50','8.54','4f10','2562','Boisbaudran 1886');">66<br>
Dy</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#6495ED"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Holmio','67','164.9304','8.80','4f11','2720','Delafontaine 1878');">67<br>
Ho</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#6495ED"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Erbio','68','167.26','9.05','4f12','2510','Mosander 1843');">68<br>
Er</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#6495ED"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Tulio','69','168.9342','9.33','4f13','1727','Cleve 1879');">69<br>
Tm</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#6495ED"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Yterbio','70','173.04','6.96','4f14','1466','Marignac 1878');">70<br>
Yb</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#6495ED"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Lutecio','71','174.96','9.84','4f14','3315','Urbain 1907');">71<br>
Lu</a></font></td>
<td width=32 height=30  bgcolor="#FFFFFF"></td>
</tr>
<tr> 
<td colspan="3" bgcolor="#FFFFFF"></td>
<br>
<td width=32 height=30 align=CENTER bgcolor="#6495ED"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Torio','90','232.0381','11.7','6d2','4790','Berzelius 1828');">90<br>
Th</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#6495ED"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Proactinio','91','231.0359','15.4','5f2','--','Hahn & Meitner 1917');">91<br>
Pa</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#6495ED"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Uranio','92','238.029','19.07','5f3','3818','Peligot 1841');">92<br>
U</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#FFCC99"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Neptunio','93','237.0482','19.5','5f4','3902','McMillan & Abelson 1940');">93<br>
Np</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#FFCC999"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Plutonio','94','(244)','--','5f6','3235±19','Seaborg 1940');">94<br>
Pu</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#FFCC99"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Americio','95','(243)','11.7','5f7','2607','Seaborg  1944');">95<br>
Am</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#FFCC99"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Curio','96','(247)','--','5f7','--','Seaborg  1944');">96<br>
Cm</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#FFCC99"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Berkelio','97','(247)','--','5f8','--','Seaborg  1949');">97<br>
Bk</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#FFCC99"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Californio','98','(251)','--','5f9','--','Seaborg  1950');">98<br>
Cf</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#FFCC99"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Einstenio','99','(254)','--','5f11','--','Ghiorso  1952');">99<br>
Es</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#FFCC99"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Fermio','100','(257)','--','5f12'','--','Ghiorso  1953');">100<br>
Fm</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#FFCC99"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Mendelevio','101','(258)','--','5f13'','--','Ghiorso  1955');">101<br>
Md</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#FFCC99"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Nobelio','102','(259)','--','5f14','--','Ghiorso  1957');">102<br>
No</a></font></td>
<td width=32 height=30 align=CENTER bgcolor="#FFCC99"><font size="3" face="Arial"><a href="javascript:nada()" onMouseOver="prop('Lawrencio','103','(260)','--','5f14','--','Ghiorso  1961');">103<br>
Lw</a></font></td>
<td width=32 height=30 bgcolor="#FFFFFF"></td>
</tr>
<tr>
<td colspan="18" bgcolor="#FFFFFF" height=30></td>
</tr>
<tr>
<td colspan="1" bgcolor="#FFFFFF" height=30></td>
<td  height=30 colspan="16" bgcolor="#FFEFD5" align=CENTER><b><font size="3" face="Arial">CARACTERÍSTICAS</font></b></td>
<td colspan="1" bgcolor="#FFFFFF" height=30></td>
</tr>
<tr bgcolor="#00FFFF">
<td colspan="1" bgcolor="#FFFFFF" height=30></td> 
<td colspan="16" align=CENTER  height=30><div align="center"><font size="4" face="Arial"><tt> 
<b>NOMBRE DEL ELEMENTO:</b> 
<input type="text" name="elemento" size="30">
</tt></font></div></td>
<td colspan="1" bgcolor="#FFFFFF" height=30></td>
</tr>
<tr bgcolor="#00FFFF">
<td colspan="1" bgcolor="#FFFFFF" height=30></td>
<td colspan="16" align=CENTER valign=MIDDLE height=30><div align="center"><font size="4" face="Arial"><tt> 
<b>CIENTÍFICO DESCUBRIDOR Y AÑO:</b>
<input type="text" size="40" name="descubridor">
</tt></font></div></td>
<td colspan="1" bgcolor="#FFFFFF" height=30></td>
</tr>
<tr>
<td colspan="1" bgcolor="#FFFFFF" height=30></td>
<td colspan="16" align="CENTER" bgcolor="#00FFFF"><div align="center"><font size="4" face="Arial"><tt> 
<b>PESO ATÓMICO:</b> 
<input type="text" size="20" name="peso">
</tt></font></div>
<td colspan="1" bgcolor="#FFFFFF" height=30></td>
</td>
</tr>
<tr>
<td colspan="1" bgcolor="#FFFFFF" height=30></td>
<td colspan="16" align="CENTER" bgcolor="#00FFFF"><div align="center"><font size="4" face="Arial"><tt> 
<b>PUNTO DE EBULLICIÓN (ºC):</b> 
<input type="text" size="20" name="punto">
</tt></font></div></td>
<td colspan="1" bgcolor="#FFFFFF" height=30></td>
</tr>
<tr>
<td colspan="1" bgcolor="#FFFFFF" height=30></td>
<td colspan="16" bgcolor="#00FFFF" align=CENTER><div align="center"><font size="4" face="Arial"><tt> 
<b>DENSIDAD en (g/ml^3):</b> 
<input type="text" size="20" name="densidad">
</tt></font></div></td>
<td colspan="1" bgcolor="#FFFFFF" height=30></td>
</tr>
<tr>
<td colspan="1" bgcolor="#FFFFFF" height=30></td>
<td colspan="16"  bgcolor="#00FFFF" align=CENTER><div align="center"><font size="4" face="Arial"><tt> 
<b>ESTRUCTURA ELECTRÓNICA</b> 
<input type="text" size="20" name="estructura">
</tt></font></div></td>
<td colspan="1" bgcolor="#FFFFFF" height=30></td>
</tr>
<tr>
<td colspan="1" bgcolor="#FFFFFF" height=30></td>
<td colspan="16"  bgcolor="#00FFFF" align=CENTER><div align="center"><font size="4" face="Arial"><tt> 
<b>NÚMERO ATÓMICO</b>
<input type="text" size="20" name="numero">
</tt></font></div></td>
<td colspan="1" bgcolor="#FFFFFF" height=30></td>
</tr>
<td colspan="18" bgcolor="#FFFFFF" height=30></td>
</table>
</div>
</FORM>
</BODY>

Aqui finalizamos el documento HTML
</HTML>```

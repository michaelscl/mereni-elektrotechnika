## 3E1 - Charakteristika žárovky
 - Vypracoval: Meinlschmidt Jakub
 - Třída: 3D/PRA2
 - Varianta: E1-K
 - Datum: 18. 09. 2017

### Zadání
 - Sestrojte charakteristiky žárovky I=f(U), R=f(U)
 - Graf vypracujte jak na počítači, tak i ručně na milimetrový papír
 - Do čísla úlohy zapište označení varianty K, kterou jste dostali při zadání úlohy od vyučujícího
 
### Teorie
V první řadě je zde aplikován tzv. Ohmův zákon, jež vyjadřuje vztah mezi elektrickým odporem, napětím a proudem v elektricky vodivém prostředí a zároveň přináší definici elektrického odporu R=U/I  [Ω].

Elektrický odpor R [Ω] je skalární fyzikální veličina, která charakterizuje schopnost elektrických vodičů vést elektrický proud, ten je definován jako uspořádaný pohyb nosičů elektrického náboje. Těmi jsou v kovech zpravidla valenční elektrony, které se mohou působením elektrického napětí volně pohybovat v krystalové mřížce daného kovu.

Elektrický proud I [A] je jakožto skalární fyzikální veličina roven množství elektrického náboje, který projde průřezem vodiče za jednotku času.
	

Elektrický náboj Q [C] vyjadřuje určitou vlastnost částic, vzájemně působit na ostatní částice elektrickou silou v elektrickém poli podobně, jako probíhá působení sil v poli gravitačním. Elektrické pole má původ právě v částicích s elektrickým nábojem, který může být neutrální, kladný nebo také záporný. Kladný a záporný náboj je dán pouze konvencí, která elektronu přisuzuje náboj záporný, tím pádem je nositelem kladného náboje proton. Velikost náboje obou těchto částic je stejná a je považována za elementární elektrický náboj e, který je po zaokrouhlení roven e = 1,602177 ∙ 10^(-19) °C.

Na elektrický náboj svým způsobem navazuje elektrický potenciál φ [V], který jakožto skalární fyzikální veličina popisuje potenciální energii bodu v neměnném elektrickém poli. Tento potenciál lze zjistit následujícím vzorcem, kde r značí polohový vektor a ε permitivitu prostředí, φ(r) = Q/4πrε.

Od elektrického potenciálu se dále odvíjí elektrické napětí U [V], které je definováno jako skalární fyzikální veličina vyjadřující rozdíl dvou elektrických potenciálů U = φ(r_1) - φ(r_2), napětí mezi dvěma body lze také vypočítat s užitím elektrické intenzity a vzdálenosti mezi body v elektrickém poli. Vzniklým napětím lze přemístit elektrický náboj Q po určité dráze o délce l. Vykonanou práci při tomto přenosu lze zapsat jako W = Q ∙ U [J]. Jak bylo řečeno, uspořádaný pohyb nosičů elektrického náboje nazýváme elektrický proud.

Tomu je zpravidla kladen elektrický odpor daného prostředí, který je dán užitým materiálem, tvarem, teplotou (zabaleno do rezistivity materiálu), délkou vodiče a jeho průřezem. Základní vztah zde platí R = ρl / S [Ω], kde ρ je rezistivita vodiče [Ωm], l jeho délka [m] a S jeho průřez [m^2].

Pro účely této úlohy, kde teplota vodiče hraje u žárovky klíčovou roli (při dostatečném zahřátí vodiče dochází k tomu, že září jak v infračervené oblasti, tak i ve viditelném spektru), proto k teorii přidáme ještě vliv teploty materiálu na jeho rezistivitu a to p = p_0 (1 + α∆t), kde p_0 se rovná počáteční rezistivitě (v tabulkách měřena zpravidla při 20 °C), α je teplotní součinitel elektrického odporu a ∆t rozdíl teplot ve [°C].

### Odpovědi na otázky
**Jaký je odpor vypnuté žárovky?** Vzhledem k neúplnosti zadání nelze poskytnout úplnou odpověď. Odpor vlákna je možné zjistit za pomoci charakteristiky v bodě U = 0 V, bohužel průběh byl vzhledem k nepřesnostem měření aproximován a tudíž hodnota odporu by byla v daném místě velmi nepřesná. Pokud bychom chtěli zjistit odpor vlákna za studena (při 20 °C), potřebovali bychom znát ze zadání alespoň výkon a teplotu vlákna při daném proudu.

### Schéma zapojení
![alt text](https://github.com/jmeinlschmidt/mereni-sps-cl/blob/master/3E/3E1/3E1-schema.jpg "Schéma zapojení")

### Použité měřící přístroje a pomůcky
Nebyly užity žádné měřící přístroje ani zařízení.

### Popis práce
Žádné měření s tímto protokolem neprobíhalo.

### Tabulky
**U[V]**|**I[mA]**|**R[Ω]**|**U[V]**|**I[mA]**|**R[Ω]**
:-----:|:-----:|:-----:|:-----:|:-----:|:-----:
0,000|0,000| - |13,000|318,000|40,881
1,000|116,000|8,621|14,000|328,000|42,683
2,000|123,000|16,260|15,000|344,000|43,605
3,000|170,000|17,647|16,000|353,000|45,326
4,000|186,000|21,505|17,000|359,000|47,354
5,000|204,000|24,510|18,000|378,000|47,619
6,000|221,000|27,149|19,000|383,000|49,608
7,000|227,000|30,837|20,000|391,000|51,151
8,000|249,000|32,129|21,000|398,000|52,764
9,000|260,000|34,615|22,000|404,000|54,455
10,000|276,000|36,232|23,000|411,000|55,961
11,000|287,000|38,328|24,000|416,000|57,692
12,000|301,000|39,867| - | - | -

### Výpočty
R = U / I

R = 1,000 / (116,000 ∙ 10^(-3) )

R = 8,621 Ω

### Graf
![alt text](https://github.com/jmeinlschmidt/mereni-sps-cl/blob/master/3E/3E1/3E1-graf.png "Graf")

### Spolupracovali
Úloha byla vypracována samostatně.

### Závěr
Byly splněny všechny úkoly ze zadání. Mezi získané poznatky patří stručný výklad základů elektrotechniky v kapitole teorie, kde jsem jednoduše shrnul základní vztahy mezi veličinami. Dále jsem si oživil vliv teploty a dalších veličin na odpor vodiče a dozvěděl se o průběhu voltampérové charakteristiky žárovky. Jelikož průběh proudu není vzhledem ke „skoku“ na začátku měření přímo lineární, rozhodl jsem se pro spojení jednotlivých hodnot využít polynomickou funkci, která je blíže skutečnému průběhu.

### Ke stažení
[3E1.docx](https://github.com/jmeinlschmidt/mereni-sps-cl/blob/master/3E/3E1/3E1.docx) | [3E1.pdf](https://github.com/jmeinlschmidt/mereni-sps-cl/blob/master/3E/3E1/3E1.pdf) | [3E1-vypocty.xlsx](https://github.com/jmeinlschmidt/mereni-sps-cl/blob/master/3E/3E1/3E1-vypocty.xlsx)
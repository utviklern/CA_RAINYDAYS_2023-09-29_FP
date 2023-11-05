# CA_RAINYDAYS_2023-09-29_UF_
 
Netlify link: 

https://fastidious-donut-56fc71.netlify.app/

___________________________________________________________



# Rapport


Jeg startet med å lage oppbyggingen av siden og Figma design så langt det lot seg gjøre. Jeg har lært mye bedre hvordan man skal designe og strukturere nettsider gjennom dette prosjektet. 

Jeg har tatt utganspunkt i respnsivness helt ned til iPhone SE med width på 375px. de fleste sidene funker uten noe som helst vertikal scroll ned til 317px. 





### Diverse problemer som har fått meg til å klø godt i hodet:

* "A" er inline element default, lettere å posisjonere hvis man endrer til block eller annet.

* For at margin auto skal funke må patent være flex.

* Hvis man har position fixed må man ha left:0 og right:0 for at man kan ta "calc" for å width med vw.

* Å spesifisere height utenom veldig spesifikke ting som eks bilder, er en dårlig ide.

På https://wave.webaim.org har jeg fått warning for at beskrivelsen av linker er vanskelig å tolke ut av kontekst, da aria er lik på footer og topnav. De sier også at kontrasten på slogan over parallax bilder har for lav kontrast. Jeg ser ikke på dette som en feil. 


### kilder
* https://stackoverflow.com/questions/9913293/change-text-on-hover-then-return-to-the-previous-text
* https://cssgenerator.org/box-shadow-css-generator.html
* https://nekocalc.com/px-to-rem-converter
* 
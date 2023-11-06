# CA_RAINYDAYS_2023-09-29_FP
 
Netlify link: 

https://rainydaysstore.netlify.app/

___________________________________________________________



# Rapport

### Generelt

Jeg startet med å lage oppbyggingen av siden. Jeg fulgte Figma designet så langt det lot seg gjøre. Jeg har lært mye bedre hvordan man skal designe og strukturere nettsider gjennom dette prosjektet, noe som er veldig bra for fremtidige prosjekter. 

Jeg droppet "tilbake" knapp på produkt spesifikk side, siden knappen hadde krevd JS som ikke er lov i dette prosjektet. Dette resulterte igjen at det ikke ble 3 forksjellige produktspesifikke sider på mobilutgave. ellers er det meste tilnærmet likt figma.


### Responsivness
Jeg har tatt utganspunkt i respnsivness helt ned til iPhone SE med width på 375px. De fleste sidene funker uten noe som helst vertikal scroll ned til 320px. Jeg valgte å skrive diverse mål i rem, siden alt vil scale bra hvis siden blir brukt av noen som har satt default font størrelse i browser. 

Underveis har jeg kjørt validering via https://wave.webaim.org har jeg fått warning for at beskrivelsen av linker er vanskelig å tolke ut av kontekst, at aria er lik på footer og topnav (samme endepunkt). De sier også at kontrasten på slogan over parallax bilder har for lav kontrast. Jeg ser ikke på dette som en feil, da kontrasten ikke er visuelt synlig siden det ligger ett bilde mellom bakgrunn og teksten, og en person som hadde brukt skjermleser ville forstått konteskten ved knappene, da jeg har aria-label på de. 


### Diverse problemer som har fått meg til å klø godt i hodet:

* "A" er inline element default, lettere å posisjonere hvis man endrer til block eller annet.

* Viktigheten med z-index. uten Z-index på navbar ville produktbilder som har scale propery gå over navbar.

* For at margin auto skal funke må parent være eks flex.

* Hvis man har position fixed på ett element må man ha left:0 og right:0 for at man kan ta "calc" for å width med vw.

* Å spesifisere height utenom veldig spesifikke ting som eks bilder, er en dårlig ide.


### konklusjon
Alt i alt er jeg fornøyd med resultatet. Jeg synes dette har vært ett givende prosjekt, da jeg føler jeg har lært mer av dette enn det jeg har gjort med eks. mollify oppgaver.


### diverse nettsider som har hjulpet meg underveis
* https://stackoverflow.com/questions/9913293/change-text-on-hover-then-return-to-the-previous-text
* https://cssgenerator.org/box-shadow-css-generator.html
* https://nekocalc.com/px-to-rem-converter
* https://cssgradient.io/

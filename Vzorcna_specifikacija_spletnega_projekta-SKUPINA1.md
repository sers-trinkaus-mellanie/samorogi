# Specifikacija spletne aplikacije 

_VZORČNI IZPOLNJENI DOKUMENT  |  Naročanje malice z aplikacijo_ 

Primer za skupinski projekt dijakov (HTML, CSS, JavaScript, PHP, MySQL). Dokument opisuje, kaj bo aplikacija omogočala, ne pa še podrobne izvedbe. 

|**Podatek**|**Vrednost**|
|---|---|
|**Naziv projekta**|Naročanje malice z aplikacijo|
|**Skupina / člani**|Skupina 1 / Ana Marija, Asja, Mellanie, Lorena|
|**Verzija / datum**|1.0 / 19. 10. 2026|
|**Status**|Osnutek za pregled profesorjev|



## **1. Opis problema** 

Dijaki si morajo naročati malice v šoli in je to možno le za 1 dan naprej. Aplikacija bo omogočala, da si dijaki naročijo malice na daljavo in za več dni naprej. 

## **2. Ciljna skupina** 

|**Ciljna skupina**|**Potrebe**|
|---|---|
|**SERŠ dijaki in oslužbenci**|Naročanje malice brez obiska šole.|



## **3. Funkcionalne zahteve** 

Vsaka zahteva ima enolično oznako. Obvezne zahteve sestavljajo prvo delujočo različico (MVP). 

|**ID**|**Funkcionalna zahteva**|**Prioriteta**|
|---|---|---|
|**F01**|Uporabnik se prijavi s šolsko e-<br>pošto in geslom.|Obvezno|
|**F02**|Uporabnik se prijavi in odjavi.|Obvezno|
|**F03**|Uporabnik vidi meni za<br>prihodnji teden.|Obvezno|
|**F04**|Uporabnik se prijavi in odjavi iz<br>malice.|Obvezno|
|**F05**|Uporabnik izbere malice.|Obvezno|
|**F06**|Uporabnik potrdi izbiro oz.<br>izbire malice.|Obvezno|
|**F07**|Uporabnik lahko vidi alergene.|Obvezno|
|**F08**|Uporabnik lahko vidi stranski<br>meni (prigrizki in cenik).|Obvezno|



Vzorec za dijake • Specifikacija spletne aplikacije 

|**F09**|Uporabnik lahko poda svoje<br>mnenje in predloge.|Obvezno|
|---|---|---|
|**F10**|Uporabnik lahko vidi Koliko<br>denarja ima za malice in koliko<br>ga je že porabil ter višino<br>subvencije (če jo ima)|Obvezno|
|**F11**|Uporabnik ima koleadarski<br>pogled naročenih malic|Neobvezno|



## **4. Uporabniške vloge** 

|**Vloga**|**Dovoljenja / omejitve**|
|---|---|
|**Registrirani uporabnik**|Naroča malice.|
|**Administrator**|Lahko vidi število prijavljenih na malice,|
||predloge uporabnikov, spreminja cene in meni<br>oz. jedilnik.|



## **5. Podatki** 

Predvidene entitete in podatki (natančne povezave in tipi bodo določeni v ER-diagramu): 

|**Tabela**|**Predvideni podatki**|
|---|---|
|**uporabniki**|Id_uporabnika, ime, priimek, razred, e-mail,|
||geslo|
|**izbira**|Id, id_uporabnika, id_malice,|
|predlog|Id_predlog, predlog|



Povezave: Uporanik si lahko naroči eno ali več malic (izbira), uporabnik lahko poda en ali več predlogov. 

Vzorec za dijake • Specifikacija spletne aplikacije 

## **6. Uporabniški scenariji** 

### **Scenarij S01: Naročanje malice** 

- uporabnik se prijavi 

- uporabnik preveri stanje na svoji kartici 

- uporabnik preveri meni oz. jedilnik in si izbere malice 

### **Scenarij S02: Preklic malice** 

Uporabnik izbere malico, ki jo želi preklicati (to lahko stori najmanj 1 dan pred samo malico). 

### **Scenarij S03: Dodajanje menijev** 

- Administrator se prijavi 

- Administrator posodobi novi meni in alergene. 

## **7. Obseg projekta** 

### **7.1 Prva delujoča različica (MVP)** 

Obvezno: F01–F09; najmanj dve uporabniški vlogi; povezava s podatkovno bazo; odziven uporabniški vmesnik; preverjanje vnosov in pravic; delovanje na šolskem gostovanju. 

### **7.2 Dodatne funkcionalnosti** 

Koledarski pogled naročenih malic. 

### **7.3 Izven obsega** 

Spletno plačevanje ni del tega projekta. 

## **Dodatek A. Skupne tehnične zahteve** 

HTML, CSS, MySQL, omejevanje dostopa glede na vlogo, GitHub 

## **Dodatek B. Potrditev specifikacije** 

|**Pregledovalec**|**Status / pripomba**|
|---|---|
|**Profesor A – programiranje in podatkovna**|____________________________|
|**baza**||
|**Profesor B – dizajn in UX**|____________________________|
|**Datum potrditve**|____________________________|



Vzorec za dijake • Specifikacija spletne aplikacije 


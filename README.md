# JavaPrvaVjezba
Prva laboratorijska vježba iz kolegija programiranja u Java jeziku


1.2. ZADATAK ZA PRIPREMU
Napisati Java program koji će se sastojati od nekoliko klasa
pohranjenih u različitim paketima. Klase simuliraju strukturu za
implementaciju aplikacije za vođenje evidencije o zaraženim osobama
Covid-19 virusom i osoba u samoizolaciji. Program je potrebno
implementirati prema sljedećim koracima:
1. Preuzeti najnoviju verziju Jave 15 sa stranica https://jdk.java.net/15/
i raspakirati arhivu na željenu lokaciju.
2. Preuzeti najnoviju inačicu IntelliJ IDEA Ultimate razvojnog
okruženja s poveznice: https://www.jetbrains.com/idea/download/.
Na stranici https://account.jetbrains.com/login je potrebno kreirati
JetBrains korisnički račun korištenjem e-maila od TVZ-a. Nakon
aktivacije korisničkog računa potrebno je aktivirati Intellij IDEA
licencu korištenjem ovih uputa:
https://www.jetbrains.com/help/idea/register.html.
3. Kreirati projekt s nazivom koji odgovara Vašem prezimenu i rednom
broju vježbe (npr. „Radovan-1“) korištenjem sljedećih uputa:
https://www.jetbrains.com/help/idea/creating-and-running-yourfirst-java-application.html.
4. Unutar projekta iz prošlog zadatka unutar „src“ mape kreirati paket
pod nazivom „hr.java.covidportal.model“.
5. U paketu iz četvrtog zadatka kreirati klasu „Simptom“ koja sadrži dva
objekta klase „String“: „naziv“ i „vrijednost“. Korištenjem uputa sa
stranice https://www.jetbrains.com/help/idea/generatingcode.html#generate-getters-setters generirati konstruktor koji
prima oba ulazna parametra, te „getter“ i „setter“ metode za te
varijable.
6. U paketu iz četvrtog zadatka kreirati Java klasu pod nazivom „Bolest“
koja sadrži varijable „naziv“ (tipa String) i „simptomi“ (tipa polje
objekata klase „Simptom“). Na sličan način kao što je opisano u
prošlom zadatku je potrebno generirati konstruktor koji prima sve
ulazne parametre, te „getter“ i „setter“ metode za te varijable.
7. U paketu iz četvrtog zadatka kreirati Java klasu pod nazivom
„Zupanija“ koja sadrži varijable „naziv“ (tipa „String“) i
„brojStanovnika“ (tipa „Integer“). Na sličan način kao što je opisano u
prošlim zadacima je potrebno generirati konstruktor koji prima sve
ulazne parametre, te „getter“ i „setter“ metode za te varijable.
8. U paketu iz četvrtog zadatka kreirati Java klasu pod nazivom „Osoba“
koja sadrži varijable „ime“ i „prezime“ (tipa String), „starost“ (tipa
„Integer“), „zupanija“ (tipa „Zupanija“), „zarazenBolescu“ (tipa
„Bolest“) i „kontaktiraneOsobe“ (tipa polje objekata klase „Osoba“). Na
sličan način kao što je opisano u prošlim zadacima je potrebno
generirati konstruktor koji prima sve ulazne parametre, te „getter“ i
„setter“ metode za te varijable.
9. Kreirati novi paket pod nazivom „hr.java.covidportal.main“.
10. U paketu iz prošlog zadatka kreirati klasu „Glavna“ koja sadrži
„main“ metodu. U toj metodi je potrebno zatražiti unos podataka za
tri županije, tri simptoma, tri bolesti i tri osobe. U slučaju neispravnog
unosa, korisniku je potrebno prijaviti pogrešku i zatražiti novi unos.
11. Logiku unosa svakog od entiteta je potrebno izdvojiti u zasebnu
metodu. Prilikom unosa osoba s kojima je osoba bila u kontaktu je
potrebno ponuditi samo otprije unesene osobe. Na primjer, kod unosa
prve osobe nije potrebno ponuditi nijednu osobu s kojim je prva osoba
bila u kontaktu.
12. Projekt iz trećeg zadatka je potrebno pretvoriti u Maven projekt
korištenjem uputa s ove poveznice:
https://www.jetbrains.com/help/idea/convert-a-regular-project-intoa-maven-project.html. 

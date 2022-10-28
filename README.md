# Obligatorisk oppgave 3 i Algoritmer og Datastrukturer

Denne oppgaven er en innlevering i Algoritmer og Datastrukturer. 
Oppgaven er levert av følgende student:
* Magnus Høistad, s362051, s362051@oslomet.no


# Oppgavebeskrivelse

I oppgave 1 brukte jeg kode fra kompendiet, men måtte endre litt siden konstruktøren var annerledes. Brukte ikke så lang tid på denne.

I oppgave 2 har jeg lånt kode fra kap 5.2.6 i kompendiet. Denne metoden begynner i rot, og går gjennom hele treet mens den sammenlikner verdi og p.verdi.
Til å sammenligne brukes en komparator cmp, og om cmp == 0 så vil antall økes. Til slutt returneres antall.

I oppgave 3 brukes en while-løkke til å finne p.venstre helt til jeg kommer til første postorden.
I nestePostorden brukes først en if-setning til å sjekke om p.forelder eller p.forelder.høyre er 0 eller p.
Om ikke returneres p.forelder.høyre.

I oppgave 4 (postorden) begynner jeg i rot og bruker førstePostorden(p) til å finne første postorden.
Deretter bruker jeg nestePostorden(p) til å finne neste postorden i en while-løkke helt til p == null.
Den vil da bryte ut av løkka og oppgaven kan gjennomføres.

Jeg har hatt veldig lite tid til å arbeide med denne obligen da jeg startet i ny jobb denne uken,
og har hatt kurs hver dag. Derfor er det kun oppgave 1-4 som passerer testene.
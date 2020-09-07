# Reservations app til cafe

Denne app vil indeholde 2 forskellige brugertyper

+ Kunder
+ Medarbejdere

Måske vil der være 2 apps, en for hver brugertype.

---

# KundeView

En kunde vil kunne oprette sig selv som bruger og logge ind for derefter at kunne:

+ Oprette reservation
+ Manage reservation

Derudover får en kunde 1 kupon pr. person i reservationen som kan indløses for drikkevarer i caféen, disse kuponner føres system over i appen.

---

## Oprette reservation

Reservationen oprettes ved et bord meget lignende en biograf reservation hvor kunden vælger et bord som passer til hans parametre:

+ Antal personer
    + stole ved bord kan max være 2 mere end antal personer
+ Tidspunkt (afhænger af)
    + dag på ugen
    + andre reservationer

----

Ud over bord reservationen kan man også bestille en eller flere guruer som kommer og spiller med en. (Der skal være plads ved bordet)

---

### Kort over cafeen

+ Borde vil vises grafisk på et kort over cafeen
+ tilgængelige borde vil være grønne andre røde

---


## Manage reservation

Hvis en kunde vil ændre sin reservation så er det muligt at gøre det ind til dagen derpå klokken 12.

+ tilføjelse af personer uden at skifte bord er muligt ind til reservationen starter hvis bordet har ekstra stole
+ tilføjelse af flere personer kræver nyt bord
+ aflysning koster et gebyr

---


# MedarbejderView
En medarbejder vil kunne logge ind og se listen over dagens reservationer, listen indeholder:

---

## Dagens reservationer

+ Bordnummer
+ Navn
+ Antal

Hvis man trykker på reservationen vil man få yderligere information, om reservationen og kunden i et enkelt reservations view.

---

## Enkelt reservation view.

Dette view indeholder alt information om en reservation.

+ Guru
+ Pris
+ Datoer
    + Oprettelse

----

+ Evt ændringer
    + Datoer
    + Pris
+ Kundeinfo
    + Navn
    + Email
    + Telefon

---

## Statistik

Man kan muligvis indsætte et view med statestik over hvornår der er mange reservationer osv, med grafer osv. 

---

## Redigering af modeller

Man kan (muligvis med extra admin rettigheder) gå ind og ændre et bords QR kode og antal sæder, tilføje og fjerne borde. 

---

## Kallender view

Man kan se en kallender for en måned af gangen hvor hver dag viser antallet af reservationer.
Man kan gå ind og se reservationer på andre dage, det er det samme view som **Dagens reservationer** bare for en anden dato.

# Betillings App til café

Dette er en app som har flere forskellige brugertyper. 

- Kunder
- Køkkenmedarbejder
- Bartender

---

# Kunder
En kunde vil komme ind på caffeen og sætte sig ved et bord. Her kan kunden scanne en qr kode med appen for at identificere at han sidder ved dette bord.

Kunden skal også identificere sig selv, ved hjælp af nemId eller andet fordi at cafeen serverer alkoholiske drikkevarer. Kundens **Main view** vil være menuen. I menuen kan kunden browse forskellige kategorier bla. 

---

## Kategorier

- Varme drikke
- Mad 
- Øl /vin
- Cocktails
- Snacks

----

Under hver kategori vil en dynamisk vejledende ventetid stå som anfhænger af hvor mange bestillinger der er på tidspunket af bestillingen. (Mad er sepparat fra alt andet, så der vil være 2 tidspunkter) 

En kunde vil kunne vælge de ting som han/hun vil bestille, tingene tilføjes til kurv og kunden foretager checkout med mobilepay eller lign.

---

## Ventetid 

Efter bestillingen vil ventetiden fortsat dynamisk ændre sig på baggrund af:

+ hvornår bestillingen er godkendt
+ hvor lang tid der er gået siden den er godkendt.
+ evt +minutter som medarbejderen har givet bestillingen.

----

Når en bestilling er klar vil produkterne blive leveret til bordet, men hvis personalet er presset vil telefonen virke som en buzzer og notify kunden med larm og vibrering og blink at han/hun skal gå op og hente det som de har bestilt.

---

# Køkkenarbejder
En køkkenmedarbejder vil have en tablet i køkkenet med en liste af bestillinger. Når en bestilling med mad modtages, vil den appendes til listen og få en farve som viser at den er modtaget men ikke godkendt, køkkenmedarbejderen klikker godkendt når han begynder at lave den og farven skifter. Når maden er klar klikker medarbejderen igen og en kvitering printes på den trådløse printer. 

---

## Kvittering

Kvitteringen indeholder:

+ Kundens navn
+ Bordnummer
+ Bestillingens indhold (kun mad)

---

# Bartender
En bartender vil lige som en køkkenbedarbejder have en tablet og en liste, han vil dog kun modtage den del af bestillinger som indeholder ikke-mad produkter. Når han klikker på en bestilling første gang er den godkendt og han begynder at lave bestillingen, når han klikker anden gang er bestillingen klar og han leverer den.

---

# Panic mode
Nogle gange er caféen underbemandet i forhold til antallet af kunder og derfor bliver der spildt en masse tid når maden skal leveres, derfor introduceres panic mode, som hvis det sættes til, vil skifte skærmens farve for at symbolisere fare. Kunderne vil blive informeret med en ekstra bar i toppen at man selv skal hente mad/drikkevarer når bestillingen er klar. Og de vil blive notified derom ved at telefonen kommer til at virke som en buzzer, men man får også løbende info om :

----

+ bestillingen er gokendt
+ forventet estimat af tid tilbage
+ bestillingen er klar

---

# Opdeling af bestillinger
Hvis en kunde bestiller både mad og drikkevarer, bliver bestillingen delt op i 2. Køkkenet vil modtage mad og baren vil modtage drikkevarer. 

hvis appen er i panic mode så vil kunden få notifikationer 2 gange, og vil dermed skulle gå op i baren og hente sine varer i 2 omgange.


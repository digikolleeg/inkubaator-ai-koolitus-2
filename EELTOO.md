# Tee enne töötuba need kolm asja ära

26. augustil ehitame sulle müügiagendi, mis:

1. leiab või võtab ette sinu valitud ettevõtted;
2. uurib iga ettevõtet;
3. kirjutab personaalse esimese sõnumi sinu ettevõtte pakkumise ja hääle järgi.

Et me ei kulutaks kohapeal esimest tundi kontode ja failidega võitlemisele, tee enne tulekut allolev eeltöö.

Arvesta 30 kuni 45 minutiga. Kui tehniline kontroll või intervjuu jääb pooleli, tule ikka kohale. Võta pooleli töö kaasa.

## Valmis tähendab seda

Töötoa alguseks on sul arvutis üks kaust, kus on:

```text
minu-muugiagent/
├── identity.md
├── current-projects.md
├── communication-style.md
├── writing-samples.md
└── sihtkliendid.csv
```

Failinimed peavad olema täpselt sellised. Kui Gemini, ChatGPT või mõni muu tööriist paneb allalaaditud failile automaatse nime, nimeta fail ise ümber.

## 1. Pane Claude Desktop tööle

Töötoa ühine osa toimub Claude Desktopi Coworkis.

1. Loo konto [claude.ai](https://claude.ai) lehel.
2. Võta Claude Pro või mõni teine tasuline plaan, mis sisaldab Coworki.
3. Paigalda [Claude Desktop](https://claude.com/download) ja logi sisse.
4. Loo arvutisse kaust `minu-muugiagent`.
5. Ava Cowork, vali **Add folder** ja anna Claude'ile ligipääs sellele kaustale.
6. Kirjuta Coworki:

```text
Tee sellesse kausta fail test.md, kus on üks lause.
```

Kui `test.md` ilmub kausta, on tehniline osa korras. Võid testfaili kustutada.

Töötoa näited teen Coworkis, kuid sama kausta ja samu markdown-faile saad kasutada ka Codexis. Mõlemad on täiesti sobivad.

## 2. Tee müügiagendi konteksti-intervjuu

Intervjuu aitab sul sõnastada, mida sa müüd, kellele, mis olukorras klient sinu abi vajab ja kuidas sinu nimel kirjutada. AI võib sinuga valikuid arutada ja pakkuda variante.

Erinevad mudelid viivad sama intervjuu natuke erinevalt läbi. Kui tahad, proovi Claude'i, ChatGPT-d või Geminit ja vali see vestlus, kus mõtete vahetamine töötab sinu jaoks kõige paremini.

### Lihtsaim tee: töötab igas AI vestluses

1. Ava [intervjuu puhas tekst](https://raw.githubusercontent.com/digikolleeg/isiklik-kontekst/main/quick-interview.md).
2. Vali kogu tekst ja kopeeri see.
3. Kleebi see uue AI vestluse esimeseks sõnumiks.
4. Lisa lõppu: `töötoa intervjuu`.
5. Vasta üks küsimus korraga.
6. Laadi lõpus neli faili alla ja pane need kausta `minu-muugiagent`.

### Mugavam tee: lase failid otse kausta kirjutada

Kui kasutad Claude Desktopi Coworki või Codexit:

1. ava kaust `minu-muugiagent` ja anna rakendusele ligipääs;
2. anna talle sama intervjuutekst;
3. lisa: `töötoa intervjuu. Kirjuta valmis failid avatud kausta.`

Kontrolli lõpus, et kaustas oleks neli õige nimega faili.

### Kui tahad Skilli kohe proovida

See ei ole eeltöö tegemiseks vajalik. Kui sind huvitab, kuidas sama intervjuud hiljem ühe lühikese käsuga uuesti kasutada, paigalda [Konteksti-looja Skill](https://github.com/digikolleeg/isiklik-kontekst/tree/main/skills/konteksti-looja) ja ütle talle `töötoa intervjuu`.

Kui tahad sama konteksti hiljem mõne teise agendi jaoks täiendada, ütle Skillile `laienda konteksti uue agendi jaoks`. Olemasolevaid vastuseid ei pea nullist uuesti andma.

### Mida intervjuule anda

Viska alguses sisse kõik, mis aitab AI-l sinust kiiremini aru saada:

1. ettevõtte või teenuse kirjeldus;
2. pakkumine või veebilehe tekst;
3. päriselt saadetud meilid ja sõnumid;
4. LinkedIni postitused või muud sinu enda tekstid;
5. CV või lühike taust, kui see aitab sinu kogemust mõista.

Kirjutamisnäiteid võid anda nii palju, kui sul on. Vähemalt kaks päris näidet on vajalikud. Turundustekst annab fakte, aga sinu hääl tuleb tekstidest, mille sa ise kirjutasid või enne saatmist üle tegid.

Enne kleepimist vaata materjal üle. Kui tahad tundliku info välja jätta, asenda see nii:

```text
päris inimene -> [kliendi tegevjuht]
ettevõte -> [üks e-pood]
hind -> [neljakohaline summa]
```

E-posti aadress, telefon, isikukood ja konfidentsiaalsed lepingutingimused jäta välja.

### Vaata failid ise üle

AI ei tunne sind paremini kui sina ise. Loe neli faili läbi ja paranda:

1. faktid, mis on valed;
2. valikud, mida sa tegelikult ei teinud;
3. liiga kõvad reeglid;
4. laused, mis kõlavad turundusvahu või võõra inimesena.

## 3. Vali kolm päris ettevõtet

Laadi alla [sihtkliendid.csv](eeltoo/sihtkliendid.csv) ja täida kolm rida.

Vali ettevõtted, kellele sa päriselt võiksid kirjutada. Kui sul pole veel kindlat sihtrühma, vali kolm ettevõtet sellest nišist, mida tahad esimesena katsetada.

Töötoas ühendame konteksti, uurija Skilli, ettevõtete andmebaasi MCP connectori ja kirjutaja Skilli üheks töövooks. Nende kolme ettevõtte peal saad kohe näha, kas tulemus on kasutatav.

## Võta kaasa

1. sülearvuti ja laadija;
2. paigaldatud Claude Desktop;
3. aktiivne tasuline Claude'i plaan;
4. kaust `minu-muugiagent`, kus on neli kontekstifaili ja `sihtkliendid.csv`.

Kui tehniline kontroll ei tööta, kirjuta enne töötuba: heigo@digikolleeg.ee

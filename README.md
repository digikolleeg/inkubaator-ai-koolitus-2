# AI agentide töötuba

Tallinna Ettevõtlusinkubaator, 26. august 2026, Poldri 3/1.

## Osaleja

Alusta siit:

**[Tee töötoa eeltöö](EELTOO.md)**

Arvesta 30 kuni 45 minutiga. Tulemuseks on üks kaust nelja kontekstifaili ja kolme päris sihtkliendiga.

## Mida töötoas ehitame

```text
ettevõtete andmebaasi MCP connector -> ettevõtted
                    |
                    v
uurija Skill -> kontrollitud uuring
                    |
                    v
kirjutaja Skill + sinu kontekst -> sõnumi mustand
                    |
                    v
sinu parandus -> järgmise korra parem kontekst
```

Neli põhimõistet:

1. **Kontekst** ütleb, kelle heaks agent töötab.
2. **Skill** ütleb, kuidas üks tööetapp käib.
3. **Connector** annab ligipääsu välistele andmetele.
4. **Loop** kordab sama töövoogu järgmiste ettevõtetega.

Töötoa lõpuks on sul töötav müügiagent, mitte lihtsalt promptide kogumik.

## Avalikud materjalid

1. [Eeltöö juhend](EELTOO.md)
2. [Kopeeritava intervjuu stardileht](eeltoo/intervjuu-prompt.md)
3. [Sihtklientide CSV](eeltoo/sihtkliendid.csv)
4. [Isikliku konteksti süsteem](https://github.com/digikolleeg/isiklik-kontekst)

## Kontakt

Heigo Tolppa

heigo@digikolleeg.ee

[digikolleeg.ee](https://digikolleeg.ee)

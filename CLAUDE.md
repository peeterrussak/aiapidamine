# CLAUDE.md

Juhised AI assistendile selle projekti kohta.

## Projekti ülevaade

See on eestikeelne aiapidamise teadmusbaas kaevamisvaba (no-dig) aia jaoks Eestis.

## Struktuur

```
aiapidamine/
├── hooajaline-kalender.md       # Aastaringne tööde kalender kuude kaupa
├── säilitamine-ja-hoiustamine.md # Saagi säilitamine ja talveks ettevalmistamine
├── varustus-ja-toeriistad.md    # Tööriistad, varustus ja kulud
├── muld-ja-vaetamine.md         # Muld, kompost, väetised kaevamisvabas aias
├── kahjurid-ja-haigused.md      # Kahjurite ja haiguste koondtabel
├── kulvikorrad-ja-rotatsioon.md # Külvikorra põhimõtted ja planeerimine
├── seemnete-kogumine.md         # Seemnete kogumine ja säilitamine
├── köögiviljad/
│   └── köögiviljade-plaan.md    # Peamine köögiviljade fail (~1500 rida)
├── tomatid/
│   └── tomatite-hooldus.md      # Tomatite kasvatamine (sordid, hooldus, kahjurid)
├── kurgid/
│   └── kurkide-hooldus.md       # Kurkide kasvatamine (kasvuhoone ja avamaa)
├── küüslauk/
│   └── küüslaugu-hooldus.md     # Küüslaugu sordid ja kasvatamine
├── maasikad/
│   └── maasikate-hooldus.md     # Maasikate hooldusplaan
├── kasvuhoone/
│   └── kasvuhoone-plaan.md      # Kasvuhoone kultuurid (kurk, tomat, arbuus)
├── vaarikad/
│   └── vaarikate-hooldus.md     # Vaarikate hooldus
├── kuslapuud/
│   └── kuslapuude-hooldus.md    # Kuslapuude hooldus
├── sõstrad/
│   └── sõstarde-hooldus.md      # Sõstarde hooldus (must, punane, valge)
└── õunapuud/
    └── õunapuude-hooldus.md     # Õunapuude hooldus ja lõikus
```

## Aia parameetrid

- **Tüüp:** Kaevamisvaba (no-dig)
- **Peenrad:** 4 tk, igaüks 1 × 9 m
- **Peenarde vahe:** 60 cm
- **Asukoht:** Rõngu, Lõuna-Eesti (külmavöönd ~6a)

## 2026 peenarde jaotus

| Peenar | Kultuurid |
|--------|-----------|
| P1 | Maasikad + küüslauk + kurgirohi |
| P2 | Maavitsalised (tomat, tšilli, füüsal) |
| P3 | Liblikõielised + juurviljad (herned, oad, porgand, sibul, porru) |
| P4 | Kõrvitsalised (kurk, suvikõrvits, patisson) |

**Eraldi alad:**
- Kasvuhoone (kurk 'Suyu Long', tomatid, arbuus)
- Kartul 'Solist' (eraldi ala, jaanipäevaks)
- Marjapõõsad (vaarikad, kuslapuud)

## Keelelised konventsioonid

Kasuta korrektseid eestikeelseid botaanilisi termineid:

| Õige | Vale | Ladina |
|------|------|--------|
| Maavitsalised | ~~Ööviljalaadsed~~ | Solanaceae |
| Laugud | ~~Sibulalised~~ | Allium |
| Kõrvitsalised | – | Cucurbitaceae |
| Liblikõielised | – | Fabaceae |

### "Uba" käänamine

| Kääne | Ainsus | Mitmus |
|-------|--------|--------|
| Nimetav | uba | oad |
| Omastav | oa | **ubade** (mitte ~~oade~~) |
| Osastav | uba | ube |

## Testitud sordid 2025

### Head sordid (jätkata)

| Kultuur | Sordid |
|---------|--------|
| Tomat | 'Malle', 'Pille', 'Erk F1' |
| Maasikas | 'Asia' |
| Hernes | 'Looming', 'Aamisepp' |
| Kurk (KH) | 'Suyu Long' |
| Suvikõrvits | 'Black Beauty' |
| Patisson | 'Disco' |
| Küüslauk | Eesti sort |

### Probleemid 2025

- **Sibul:** 'Stuttgarter' segusort ei kasvanud → proovi 'Sturon' või 'Hercules'
- **Tomat:** Viinamarjatüüpi sordid ei toiminud
- **Arbuus:** Avamaal riskantne → kasvuhoonesse

## Failide redigeerimine

- Kõik failid on Markdown formaadis
- Kasuta eesti keelt
- Ära lisa emotikone, v.a ⭐ heade sortide märkimiseks ja ⚠️ hoiatuste jaoks
- Tabelid on levinud – kasuta neid info struktureerimiseks
- Kontrollnimekirjad kasutavad `- [ ]` formaati

## Hooajaline kontekst

- **Kevad:** märts–mai (ettekasvatamine, istutamine)
- **Suvi:** juuni–august (hooldus, saak)
- **Sügis:** september–november (koristamine, ettevalmistus talveks)
- **Talv:** detsember–veebruar (puhkeaeg, planeerimine)

## Viited failide vahel

Kasuta suhtelisi linke:
```markdown
Vt [maasikate-hooldus.md](../maasikad/maasikate-hooldus.md)
```

---
name: k2-regelverk
description: K2 Årsredovisning i mindre företag (BFNAR 2016:10) — svensk redovisningsrådgivning med exakt punktreferens. Aktiveras vid frågor om K2, årsredovisning, bokslut, redovisning, BFN, eller när användaren arbetar med redovisningsrelaterad kod.
---

# K2 Årsredovisning i mindre företag

Kunskapsbas för BFNAR 2016:10, uppdaterad 2025-06-16. Innehåller lagregler, allmänna råd och kommentarer för årsredovisning i mindre företag.

## När ska denna skill användas?

- Frågor om K2-regler, årsredovisning, bokslut, redovisningsprinciper
- Frågor om hur poster ska redovisas (intäkter, kostnader, tillgångar, skulder)
- Frågor om specifika punkter (t.ex. "vad säger punkt 6.16?")
- Frågor om BFN, BFNAR, ÅRL, BFL
- Byggande av redovisningsrelaterade applikationer eller AI-rådgivning
- Alla frågor om svensk redovisning för mindre företag

## Källdokument

Extraherad markdown finns i: `/Users/andersbratland/@code/k2-rådgivning/k2-arsredovisning/chapters/`

Docling-extraherad referensfil (exakt text): `/Users/andersbratland/@code/k2-rådgivning/k2-arsredovisning/docling-output.md`

## Hur du ska svara

1. **Citera exakt punkt** — ange alltid punktnummer (t.ex. "enligt punkt 6.16")
2. **Ange innehållstyp** — skilj mellan lagtext (tvingande), allmänt råd (bindande) och kommentar (vägledande)
3. **Ladda rätt kapitel** — läs relevant fil från chapters/ innan du svarar
4. **Kontrollera företagsform** — särskilda regler kan gälla för AB, HB, stiftelser, ideella föreningar etc.
5. **Svara på svenska** — regelverket är svenskt, svaren bör vara det också

## Innehållstyper (hierarki)

| Typ | Bindande? | Beskrivning |
|---|---|---|
| **Lagtext** (ÅRL, BFL, IL) | Ja, lag | Direkt citat ur lagstiftningen |
| **Allmänt råd** (punkt X.Y) | Ja, normgivning | BFN:s bindande tolkningsregler |
| **Kommentar** | Nej, vägledande | BFN:s förklarande text och exempel |

## Kapitelöversikt — Vilken fil ska laddas?

### Avsnitt I — Tillämpning och principer
| Fråga om | Läs fil |
|---|---|
| Vilka företag, K2 vs K3, punkt 1.7 | `01-tillämpning.md` |
| Redovisningsprinciper, periodisering, väsentlighet, försiktighet | `02-redovisningsprinciper.md` |

### Avsnitt II — Årsredovisningens utformning
| Fråga om | Läs fil |
|---|---|
| Presentation, språk, undertecknande | `03-årsredovisningens-utformning.md` |
| Resultaträkningens poster | `04a-uppställningsformer-resultaträkning.md` |
| Balansräkningens poster | `04b-uppställningsformer-balansräkning.md` |
| Uppställningsformer per företagsform (AB, HB, stiftelse etc.) | `04c-uppställningsformer-särskilda-regler.md` |

### Avsnitt III — Förvaltningsberättelsen
| Fråga om | Läs fil |
|---|---|
| Förvaltningsberättelse, verksamhet, flerårsöversikt, hållbarhet | `05-förvaltningsberättelsen.md` |

### Avsnitt IV — Resultaträkning
| Fråga om | Läs fil |
|---|---|
| Intäkter, inkomst vs intäkt, varuförsäljning, uppdrag (löpande/fast pris) | `06a-rörelseintäkter-grundregler.md` |
| Bidrag, realisationsvinst, hyra, royalty, provision, särskilda regler | `06b-rörelseintäkter-övriga-och-särskilda.md` |
| Kostnader, utgift vs kostnad, personal, leasing, utrangering | `07-rörelsekostnader.md` |
| Finansiella poster, räntor, utdelning, skatter, bokslutsdispositioner | `08-finansiella-poster.md` |

### Avsnitt V — Balansräkning
| Fråga om | Läs fil |
|---|---|
| Tillgångar allmänt, anskaffningsvärde, anläggningstillgång vs omsättning | `09-tillgångar.md` |
| Immateriella/materiella anl.tillgångar, avskrivning, anskaffning | `10a-anläggningstillgångar-anskaffning-avskrivning.md` |
| Nedskrivning av anl.tillgångar, uppskrivning (AB), särskilda regler | `10b-anläggningstillgångar-nedskrivning-särskilda.md` |
| Finansiella anläggningstillgångar, aktier, obligationer, nedskrivning | `11-finansiella-anläggningstillgångar.md` |
| Varulager, anskaffningsvärde, nettoförsäljningsvärde | `12-varulager.md` |
| Kortfristiga fordringar, kundfordringar, nedskrivning | `13-kortfristiga-fordringar.md` |
| Kortfristiga placeringar, kassa, bank | `14-kortfristiga-placeringar.md` |
| Eget kapital, obeskattade reserver | `15-eget-kapital.md` |
| Avsättningar, garantier, pensioner | `16-avsättningar.md` |
| Skulder, leverantörsskulder, semesterlöneskuld | `17-skulder.md` |

### Avsnitt VI — Noter
| Fråga om | Läs fil |
|---|---|
| Noter, upplysningskrav, redovisningsprinciper | `18-noter.md` |

### Avsnitt VII — Koncern/intresseföretag
| Fråga om | Läs fil |
|---|---|
| Koncernföretag, intresseföretag, gemensamt styrda företag | `19-koncern-intresseföretag.md` |

### Avsnitt VIII — Byte av regelverk
| Fråga om | Läs fil |
|---|---|
| Byte till K2, övergångsregler, korrigeringar | `20-byte-till-detta-allmänna-råd.md` |

### Avsnitt IX — Kassaflödesanalys
| Fråga om | Läs fil |
|---|---|
| Kassaflödesanalys (frivillig) | `21-kassaflödesanalys.md` |

### Exempel
| Fråga om | Läs fil i `exempel/` |
|---|---|
| Förvaltningsberättelse-exempel | `05-förvaltningsberättelsen-exempel.md` |
| Intäktsredovisning-exempel | `06-rörelseintäkter-exempel.md` |
| Kostnadsredovisning-exempel | `07-rörelsekostnader-exempel.md` |
| Tillgångsklassificering-exempel | `09-tillgångar-exempel.md` |
| Avskrivning/förvärv-exempel | `10-anläggningstillgångar-exempel.md` |
| Aktier/obligationer-exempel | `11-finansiella-anläggningstillgångar-exempel.md` |
| Lagervärdering-exempel | `12-varulager-exempel.md` |
| Eget kapital-exempel | `15-eget-kapital-exempel.md` |
| Avsättningar-exempel | `16-avsättningar-exempel.md` |
| Skulder-exempel | `17-skulder-exempel.md` |
| Noter-exempel | `18-noter-exempel.md` |

## Vanliga frågor och var svaret finns

| Fråga | Nyckelregel |
|---|---|
| Får jag aktivera egenupparbetade immateriella tillgångar? | Nej, punkt 10.4 förbjuder det i K2. Använd punkt 1.7 (K3) om du vill. |
| Hur skrivs inventarier av? | Punkt 10.27: linjärt över nyttjandeperioden. Punkt 10.29: nyttjandeperiod 5 år om <50K kr. |
| Måste jag periodisera? | Punkt 2.4: ej nödvändigt under 7 000 kr per faktura. |
| Huvudregel vs alternativregel för uppdrag till fast pris? | Punkt 6.15-6.25. Huvudregel = successiv vinstavräkning. Alternativregel = när väsentligen fullgjort. |
| Vad ska förvaltningsberättelsen innehålla? | Punkt 5.2-5.7 + särskilda regler per företagsform. |
| Hur redovisas koncernbidrag? | Punkt 19.14-19.15 under bokslutsdispositioner. |

## Viktiga gränsvärden

| Gränsvärde | Regel | Punkt |
|---|---|---|
| 7 000 kr | Periodiseringsgräns (behöver ej periodisera under) | 2.4 |
| 25 000 kr | Inventarier av mindre värde (direktavdrag) | 10.5 |
| 50 000 kr | Inventarier med nyttjandeperiod 5 år (schablonregel) | 10.29 |
| 500 000 kr | Avsättningar under detta belopp behöver ej beräknas exakt | 16.6 |

## Lagförkortningar

| Förkortning | Lag |
|---|---|
| ÅRL | Årsredovisningslagen (1995:1554) |
| BFL | Bokföringslagen (1999:1078) |
| IL | Inkomstskattelagen (1999:1229) |
| ABL | Aktiebolagslagen (2005:551) |
| BFNAR 2016:10 | Detta allmänna råd (K2 Årsredovisning) |
| BFNAR 2012:1 | K3 Årsredovisning och koncernredovisning |

---
name: k3-regelverk
description: K3 Årsredovisning och koncernredovisning (BFNAR 2012:1) — svensk redovisningsrådgivning med exakt punktreferens. Aktiveras vid frågor om K3, årsredovisning, koncernredovisning, IFRS for SMEs, eller när användaren arbetar med redovisningsrelaterad kod för större företag.
---

# K3 Årsredovisning och koncernredovisning

Kunskapsbas för BFNAR 2012:1, uppdaterad 2025-12-15. Principbaserat regelverk baserat på IFRS for SMEs. Innehåller lagregler, allmänna råd och kommentarer för årsredovisning och koncernredovisning.

## När ska denna skill användas?

- Frågor om K3-regler, årsredovisning för större företag, koncernredovisning
- Frågor om IFRS for SMEs-relaterade principer
- Frågor om poster som inte finns i K2 (uppskjuten skatt, finansiella instrument till verkligt värde, komponentavskrivning, leasing)
- Frågor om koncernredovisning, rörelseförvärv, goodwill, intresseföretag, joint ventures
- Jämförelser mellan K2 och K3
- Alla frågor om redovisning där K2 inte räcker till

## Skillnad mot K2

| Aspekt | K2 (BFNAR 2016:10) | K3 (BFNAR 2012:1) |
|---|---|---|
| Karaktär | Regelbaserat, förenklat | Principbaserat (IFRS for SMEs) |
| Egenupparbetade immateriella | Får ej aktiveras | Får aktiveras (kap 18) |
| Uppskjuten skatt | Ej tillåtet | Obligatoriskt (kap 29) |
| Komponentavskrivning | Ej krav | Obligatoriskt (kap 17) |
| Leasing | Alltid operationell | Finansiell/operationell klassificering (kap 20) |
| Finansiella instrument | Anskaffningsvärde | Anskaffning (kap 11) eller verkligt värde (kap 12) |
| Koncernredovisning | Ej tillämpligt | Fullständiga regler (kap 9) |

## Källdokument

Extraherad markdown: `/Users/andersbratland/@code/k2-rådgivning/k3-arsredovisning/chapters/`

## Hur du ska svara

1. **Citera exakt punkt** — ange alltid punktnummer (t.ex. "enligt punkt 17.4")
2. **Ange innehållstyp** — skilj mellan lagtext, allmänt råd och kommentar
3. **Ladda rätt kapitel** — läs relevant fil från chapters/ innan du svarar
4. **Skilj koncern vs juridisk person** — K3 har ofta separata regler
5. **Svara på svenska**

## Innehållstyper (hierarki)

| Typ | Bindande? | Beskrivning |
|---|---|---|
| **Lagtext** (ÅRL, BFL) | Ja, lag | Direkt citat ur lagstiftningen |
| **Allmänt råd** (punkt X.Y) | Ja, normgivning | BFN:s bindande tolkningsregler |
| **Kommentar** | Nej, vägledande | BFN:s förklarande text |

## Kapitelöversikt — Vilken fil ska laddas?

### Grundläggande (kap 1-3)
| Fråga om | Läs fil |
|---|---|
| Vilka företag, tillämpning, K2 vs K3 | `01-tillämpning.md` |
| Principer, definitioner, tillgångar/skulder/intäkter/kostnader, värderingsgrunder | `02-begrepp-principer.md` |
| Utformning, förvaltningsberättelse, juridisk person | `03-utformning.md` |

### Finansiella rapporter (kap 4-8)
| Fråga om | Läs fil |
|---|---|
| Balansräkning, uppställningsform, klassificering | `04-balansräkning.md` |
| Resultaträkning, uppställningsform | `05-resultaträkning.md` |
| Förändring i eget kapital, koncernbidrag | `06-förändring-eget-kapital.md` |
| Kassaflödesanalys, direkt/indirekt metod | `07-kassaflödesanalys.md` |
| Noter, upplysningskrav (mindre/större företag) | `08-noter.md` |

### Koncern och ägarintressen (kap 9, 14-15)
| Fråga om | Läs fil |
|---|---|
| Koncernredovisning, dotterföretag, förvärvsanalys | `09-koncernredovisning.md` |
| Intresseföretag, kapitalandelsmetoden | `14-intresseföretag.md` |
| Joint venture, gemensamt styrda verksamheter | `15-joint-venture.md` |

### Redovisningsprinciper (kap 10)
| Fråga om | Läs fil |
|---|---|
| Byte av princip, ändrad uppskattning, rättelse av fel | `10-byte-princip.md` |

### Finansiella instrument (kap 11-12)
| Fråga om | Läs fil |
|---|---|
| Finansiella instrument till anskaffningsvärde | `11-finansiella-instrument-anskaffning.md` |
| Finansiella instrument till verkligt värde (4 kap 14a-e ÅRL) | `12-finansiella-instrument-verkligt-värde.md` |

### Tillgångar (kap 13, 16-19)
| Fråga om | Läs fil |
|---|---|
| Varulager, anskaffningsvärde, inkurans | `13-varulager.md` |
| Förvaltningsfastigheter | `16-förvaltningsfastigheter.md` |
| Materiella anläggningstillgångar, komponentavskrivning | `17-materiella-anläggningstillgångar.md` |
| Immateriella tillgångar, egenupparbetade, FoU | `18-immateriella-tillgångar.md` |
| Rörelseförvärv, goodwill | `19-rörelseförvärv-goodwill.md` |

### Skulder och åtaganden (kap 20-22)
| Fråga om | Läs fil |
|---|---|
| Leasingavtal, finansiell/operationell, sale-leaseback | `20-leasingavtal.md` |
| Avsättningar, eventualförpliktelser, eventualtillgångar | `21-avsättningar.md` |
| Skulder vs eget kapital, klassificering | `22-skulder-eget-kapital.md` |

### Intäkter och kostnader (kap 23-27)
| Fråga om | Läs fil |
|---|---|
| Intäktsredovisning, varor, tjänster, entreprenad | `23-intäkter.md` |
| Offentliga bidrag | `24-offentliga-bidrag.md` |
| Låneutgifter, aktivering | `25-låneutgifter.md` |
| Aktierelaterade ersättningar | `26-aktierelaterade-ersättningar.md` |
| Nedskrivningar, kassagenererande enheter | `27-nedskrivningar.md` |

### Övrigt (kap 28-35)
| Fråga om | Läs fil |
|---|---|
| Ersättningar till anställda, pensioner | `28-ersättningar-anställda.md` |
| Inkomstskatter, uppskjuten skatt | `29-inkomstskatter.md` |
| Valutakurser, omräkning | `30-valutakurser.md` |
| Höginflationsländer | `31-höginflationsländer.md` |
| Händelser efter balansdagen | `32-händelser-efter-balansdagen.md` |
| Närstående, upplysningar | `33-närstående.md` |
| Jord- och skogsbruk | `34-jord-skogsbruk.md` |
| Första gången K3 tillämpas | `35-första-gången.md` |

### Särskilda företagsformer (kap 36-38)
| Fråga om | Läs fil |
|---|---|
| Stiftelser | `36-stiftelser.md` |
| Ideella föreningar | `37-ideella-föreningar.md` |
| Bostadsrättsföreningar | `38-bostadsrättsföreningar.md` |

### Definitioner och exempel
| Fråga om | Läs fil |
|---|---|
| Definitioner av begrepp | `bilaga-definitioner.md` |
| Kassaflödesanalys-exempel | `exempel/kassaflödesanalys-exempel.md` |
| Rörelseförvärv-exempel | `exempel/rörelseförvärv-exempel.md` |

## Vanliga frågor och var svaret finns

| Fråga | Nyckelregel |
|---|---|
| Hur beräknas uppskjuten skatt? | Kap 29: temporära skillnader × skattesats. Punkt 29.11-29.15. |
| Får jag aktivera egenupparbetade immateriella? | Ja, kap 18 punkt 18.12-18.13 (utvecklingsfas, ej forskningsfas). |
| Vad är komponentavskrivning? | Kap 17 punkt 17.4: varje del med väsentligt anskaffningsvärde ska skrivas av separat. |
| Hur klassificeras leasing? | Kap 20 punkt 20.3-20.4: finansiellt om väsentliga risker/förmåner överförts, annars operationellt. |
| Hur görs förvärvsanalys? | Kap 19 punkt 19.6-19.7: identifiera tillgångar/skulder till verkligt värde, överskott = goodwill. |
| Vad är en kassagenererande enhet? | Kap 27: minsta identifierbara grupp av tillgångar som ger kassaflöden oberoende av andra. |
| Successiv vinstavräkning i K3? | Kap 23 punkt 23.22-23.24: baserat på färdigställandegrad, tvingande (ej valfritt som i K2). |

## Lagförkortningar

| Förkortning | Lag |
|---|---|
| ÅRL | Årsredovisningslagen (1995:1554) |
| BFL | Bokföringslagen (1999:1078) |
| IL | Inkomstskattelagen (1999:1229) |
| ABL | Aktiebolagslagen (2005:551) |
| BFNAR 2012:1 | Detta allmänna råd (K3) |
| BFNAR 2016:10 | K2 Årsredovisning i mindre företag |
| IFRS for SMEs | International Financial Reporting Standard for Small and Medium-sized Entities |

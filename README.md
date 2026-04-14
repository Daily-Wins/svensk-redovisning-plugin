# Svensk Redovisning — Claude Code Plugin

Svenska redovisningsregelverk (BFNAR) paketerade som Claude Code skills för AI-rådgivning med exakt punktreferens.

## Skills

| Skill | Regelverk |
|-------|-----------|
| `k1-enskilda` | BFNAR 2006:1 — Enskilda näringsidkare, förenklat årsbokslut |
| `k1-ideella` | BFNAR 2010:1 — Ideella föreningar, förenklat årsbokslut |
| `k2-regelverk` | BFNAR 2016:10 — Årsredovisning i mindre företag |
| `k3-regelverk` | BFNAR 2012:1 — Årsredovisning och koncernredovisning |
| `arsbokslut` | BFNAR 2017:3 — Årsbokslut |
| `bokforing` | BFNAR 2013:2 — Bokföring |
| `brf-upplysningar` | BFNAR 2023:1 — Kompletterande upplysningar i BRF-årsredovisning |
| `fusioner` | BFNAR 2020:5 — Redovisning av fusion |
| `gransvarden` | BFNAR 2006:11 — Gränsvärden (K1/K2/K3-val) |

## Installation

Kör kommandona **var för sig** i Claude Code:

```
/plugin marketplace add Daily-Wins/svensk-redovisning-plugin
```

Vänta tills marketplace är tillagd, sen:

```
/plugin install svensk-redovisning
```

Och slutligen:

```
/reload-plugins
```

Skills blir då tillgängliga som `svensk-redovisning:k2-regelverk`, `svensk-redovisning:bokforing` osv. och aktiveras automatiskt av Claude när du ställer frågor om det aktuella regelverket.

## Användning

Skills triggas automatiskt på relevanta frågor. Exempel:

- *"Vad säger K2 om avskrivning av byggnad?"* → `k2-regelverk` aktiveras
- *"Hur bokförs en fusion genom absorption?"* → `fusioner` aktiveras
- *"Vilka gränsvärden gäller för att räknas som mindre företag?"* → `gransvarden` aktiveras

Du kan även tvinga aktivering genom att nämna skill-namnet direkt.

## Uppdatera

```
/plugin marketplace update Daily-Wins/svensk-redovisning-plugin
```

## Avinstallera

```
/plugin uninstall svensk-redovisning
/plugin marketplace remove Daily-Wins/svensk-redovisning-plugin
```

## Källor

Samtliga regelverk bygger på officiell vägledning från [Bokföringsnämnden (BFN)](https://www.bfn.se/). Innehållet är strukturerat för LLM-konsumtion men refererar alltid till exakt punkt i källdokumentet.

## Bidra

Issues och PR:er välkomnas: https://github.com/Daily-Wins/svensk-redovisning-plugin

## Licens

MIT (plugin-strukturen). Regelverkstexterna är offentligt material från BFN.

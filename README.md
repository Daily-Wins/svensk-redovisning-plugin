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

```bash
/plugin marketplace add Daily-Wins/svensk-redovisning-plugin
/plugin install svensk-redovisning
```

Kör sedan `/reload-plugins`. Skills dyker upp som `svensk-redovisning:k2-regelverk`, `svensk-redovisning:bokforing` osv.

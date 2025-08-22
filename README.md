# Forteiknsskjemagenerator 🪄

Ein nettbasert applikasjon for å lage matematiske forteiknsskjema. Verktøyet er designa for lærarar og elevar som treng å lage forteiknsskjema for løysingsforslag, innleveringar eller undervisning. Appen er bygd med HTML, CSS og JavaScript, og bruker MathJax for å teikne matematisk notasjon med LaTeX. 

## Funksjonalitet
- Legg til og fjern faktorar dynamisk.
- Spesifiser om ein faktor høyrer til i teljar eller nemnar.
- Støtte for avansert input som koeffisientar, brøkar, konstantar (pi, e) og funksjonar (rot(), ^).
- Automatisk eller manuelt definert tallinje.
- Intelligent plassering av merkelappar for å unngå kollisjon.
- Grensesnitt på nynorsk og engelsk.

## Input
Faktorane kan vera litt ulikt, men det er fare for at ting ikkje fungerer feilfritt enno... Under ser du eit par døme på faktorar som skal kunna tolkast rett. `pi` og `e` funkar, det samme med `rot()` og `^`. 

```2x - 1```

```x - 2^2```

```x + 1/2```

```x - pi```

```rot(3) - x```

```-x```

```4```

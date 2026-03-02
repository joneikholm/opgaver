# Lektion 6 – Assembly Opgaver

---

Brug denne [online editor](https://www.mycompiler.io/new/asm-x86_64)

## Opgave 1 – To Linjer

Ret *Hello World*, så programmet printer:

```
Hello world!
Assembly er sjovt!
```

Krav:
- Brug kun `write`
- Ret byte-længden korrekt

---

## Opgave 2 – Hele Udtrykket

Udvid programmet, så det printer:

```
3 + 5 = 8
```

Krav:
- Tallene skal beregnes
- Konverter tal til ASCII
- Må gerne bruge flere `write`

---

## Opgave 3 – Kun Lige Tal

Ret løkken, så programmet printer:

```
0 2 4 6 8
```

Krav:
- Brug en løkke
- Må ikke hardcodes

---

## Opgave 4 – Kald Funktionen To Gange

Programmet skal:

1. Starte med tallet `2`
2. Kalde `add_five`
3. Kalde `add_five` igen
4. Printe resultatet

Forventet output:

```
12
```

---

## Opgave 5 – Udfordring: To-cifret Resultat

Udvid jeres additionsprogram, så det virker korrekt,
selv hvis resultatet er **to cifre**.

Eksempel:

```
7 + 8 = 15
```

Krav:
- Resultatet må ikke hardcodes
- Begge cifre skal printes korrekt
- Brug division og rest (`div`) til at finde tier og ener

Hint:
- 15 / 10 → 1 (tier)
- 15 % 10 → 5 (ener)
- Konverter begge til ASCII før print

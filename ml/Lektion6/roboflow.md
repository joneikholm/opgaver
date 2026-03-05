# Vi samler billeder og labels til ét fælles datasæt

---

## Forberedelse — underviser gør dette én gang

1. Opret et gratis Roboflow-projekt
2. Beslut klassenavn: f.eks. `person` — alle skal stave det præcis sådan, med lille p
3. Upload 200 billeder til projektet
4. Fordel billederne, så hver studerende ved hvilke 10 billeder de skal annotere

---

## Hver studerende gør følgende

1. Opret en gratis konto på [roboflow.com](https://roboflow.com)
2. Opret et nyt projekt
3. Upload dine 10 billeder
4. Annotér billederne — tegn bounding boxes rundt om hver person
5. Eksportér projektet som en zip-fil i YOLOv8-format
6. Send zip-filen til koordinatorstuderende

---

## Koordinatorstuderende gør følgende

1. Importér alle zip-filer fra de andre studerende ind i ét Roboflow-projekt
2. Tjek at alle labels hedder `person` — ret eventuelle fejl
3. Eksportér det samlede projekt som én stor zip-fil i YOLOv8-format
4. Del zip-filen med hele klassen

---

## Alle studerende gør herefter

1. Importér den store zip-fil ind i dit eget Roboflow-projekt
2. Generér en ny version af datasættet
3. Træn modellen i Google Colab eller på lokal maskine
4. Sammenlign jeres mAP50-resultater med hinanden

---

## ⚠️ Vigtigt at huske

1. Klassenavnet skal være `person` — ikke `Person`, ikke `menneske`, ikke `human`
2. Én enkelt stavefejl betyder at modellen tror der er to forskellige klasser

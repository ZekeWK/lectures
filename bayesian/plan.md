# Mer exakt uppdelning och struktur:

## Beskrivning
Bayesian Inference - Updating beliefs with evidence!

Motivating problem:
Your friends have been arguing about who will win this years flaming-axe-throwing-championship, but you are a bit uncertain. The three contestants all have different averages, but also a different number of previous competitions, such that the higher the score, the less experience. You, an avid spectator of the sport, also have some knowledge of how good previous competitors have been. How would you go ahead to decide your pick?

Bayesian inference is a part of statistics where we combine prior knowledge and observations to update our beliefs. Using this philosophy, we can create a quite rigorous and beautiful version of statistics without relying on a bunch of ill-motivated tricks and confusing measures.

The course will contain three lectures:
1. A fast paced (!!!) crash course of probability theory, covering everything up to multivariate distribution functions of stochastic variables and operations on these.
2. Bayesian inference using the prior distribution, and updating it to a posterior distribution.
3. Applying our new knowledge (the posterior distribution) to elegantly solve all manners of statistical questions.

The only real prerequisite is basic calculus. It is advantageous to have some experience with basic set theory and especially multivariate integration.

## Prerequisites:
- Mängdlära fördelaktigt
- Axiom
- Gärna viss tidigare sannolikhetslära
- Bekväm med derivering och integrering (inte på så hög nivå nödvändigtvis)

## Lektion 1: Sannolikhetslära
- Handlar om att förstå sig på slumpmässiga system (5m)
- Sannolikhetsmåttet, ofta frekventistisk tolkning, men kan vara annorlunda. (5m)
- Axiomen för sannolikhetslära. Både diskreta och kontinuerliga fall. (10m)
- Sannolikhet givet (10m)
- Baye's Rule (5m)
- Oberoende (10m)

- Slumpvariabler, sätta ett värde på utfall + hur de beter sig (10 m)
- Fördelningsfunktion och täthetsfunktion (10m)
- Några typiska fördelningsfunktioner (10m)
- Manipulationer av dessa med täthets och fördelningsfunktioner (10m)
- Flerdimensionella slumpvariabler (10m)
- Marginalfördelning och summering (15m)

- Uppgifter om: Alla grunderna

## Lektion 2: Bayesiansk inferens
- Vi har en situation och vill veta vad den gömda variabeln är.
- I traditionell statistik, gör vi många konstiga tricks för detta.
- I Bayesiansk statistik låter vi parametern vara en slumpvariabel i sig.
- Apriorifördelning
- Datafördelning
- Aposteriorifördelning

- Exempel på detta

- Kan nu fråga allt!
- Prediktiva fördelningar
- Resten nästa föreläsning

- Uppgifter där de får öva på dessa (alltid med konjugerande fördelningar)

## Lektion 3: Appliceringar
- Har nu apposteriorifördelningen och kan fråga allt!
- Prediktiv fördelning
- Kredibilitetsintervall

- Eventuellt beslutsteori??? (Ta kanske bort? Det kräver väntevärde, och lite sånt)
- Kostnadsfunktion
- Riskfunktion
- Beslutet

- Att nu har alla exempel varit snälla
- Exempel på konjugerande fördelningar
- Finns vissa situationer där det ej möjligt
- Då kan vi approximera integraler, eller slumpa variabler på andra sätt.









Första lektionen är menad att motsvara prerequisites, denna bör innehåll:
- Definition av statistik från axiom
- Vi har händelser, kan sedan skapa funktioner på dem
- Slumpvariabler
- Fördelningsfunktioner och täthetsfunktioner
- Marginalfördelning
- Bayesregel, + hur statistik fungerar från början
- Diskreta mot kontinuerliga situationer

Uppgifter där man får bekanta sig med matten lite, speciellt kring täthetsfunktioner

Andra lektionen är menad att berätta om konceptet kring bayesian inference
- Prata om hur vi nu tänker oss att fördelningen beror på en slumpvariabel och inte en gömd
- Filosofin bakom
- Apriori fördelning, datafördelning, aposteriori fördelning
- Att detta är exakt, men diskutera tillåtna saker vi har också typ integrerings approximering
- Att då blir allt så enkelt, för vi kan bara kolla på faktiska fördelningen!

- Mycket uppgifter där de får sätta in det i huvudet
- Inte så mycket kring applikationer

Tredje lektionen om vidare applikationer:
- Konjugerande och uppdateringsregler
- Hypotesprövningar
- Aposteriori fördelningar

- Kanske en faktiskt praktisk grej vi kan göra?
- Även att göra med gömda parametrar


#flashcards/4/Farmakologi 

- Opskriv langmuir-ligningen::  $\frac{[LR]}{[R_{tot}]} = \frac{[L]}{[L] + K_D}$ Hvor $K_D $ er dissociationskonstanten
- Hvad bruges langmuir-ligningen til?:: Beskrive hvor stor en andel af receptorer der er bundet

![[Dissociationskonstanten]]


- Hvordan kan dissciationskonstanten regnes?
        - $\ce{K_D=\frac{K_{off}}{K_{on}}}$ Hvor $\ce{K_{on}}$ er associationshastighedkonstanten ig $\ce{K_{off}}$ er dissociationshastighedkonstanten
        - $\ce{K_D=\frac{[R][L]}{[RL]}}$
    - Hvad er dissociationskonstanten et mål for?:: 50% okkupans dvs affinitet
        - Hvis $K_D$ er {{32915802619351187::lav}} er affiniteten mellem receptor og ligand {{18844865522239818::høj}}
        - Hvis $K_D$ er {{32915802619351187::høj}} er affiniteten mellem receptor og ligand {{18844865522239818::lav}}
    - Hvilen enhed har $K_D$?:: M (mol/L)
    - Saturationsforsøg
        - Hvad sker overordnet i et saturationsforsøg?:: En randioaktiv ligand tilsættes et vævshomogenat i stigende koncentrationer, herefter "renses" vævshomogenatet så kun det bundede stof sidder tilbage, nu kan radioaktiviteten bruges som mål for affiniteten
            - Hvad er et vævshomogenat?:: En homogen blanding af vævsfragmenter, der er blevet homogeniseret for at frigøre og gøre receptorproteiner tilgængelige for ligander
        - Hvad menes med fejlkilden uspecifik binding?:: At liganden binder et sted der ikke er den ønskede receptor og vil derfor ikke skyldes væv
            - Hvordan testes dette for?:: Man starter med at mætte receptorene med en ikke-radioaktiv ligand, (samme ligand bare ikke radioaktiv) derefter tilsættes den radioaktive ligand, der "renses" og måles radioaktivitet som før
    - Bestemmelse af $K_D$ udfra $K_{on}$ og $K_{off}$
        - Hvad er vigtigt ved concentrationen af ligand når $K_{obs}$ måles?:: Den skal vær meget højere end koncentarationen af receptorer
        - Hvilken grafisk afbildning bruges her?:: $K_{obs} $ som funktion af ligandkoncentration ![](https://remnote-user-data.s3.amazonaws.com/ns9VgSNYQUhEFLSo33FxgLN3fAkxQH_tP1ObHyZfP6wvmB8CBLhiViJ3FT5rlKtZwGRSQ7Btwi24Xbw8XP19yUAIROWecoyHorR5FAciqsfOtFQwnBeoFTI2pEuQCkV2.png)
            - Udfra dette hvordan findes $K_{off}$?:: Skæring med y-aksen
            - Udfra dette hvorda findes $K_{on}$?:: Hældningen
            - Hvilken overordnet funktionsforskrift har kurven?:: $$K_{obs}=K_{on}\cdot [L]+k_{off}$$
        - Hvilket overordnet forsøg laves her?:: Store mængder flurosence-mærket (eller andet der kan måles/ses) tilsættes "noget" med receptorer det observeres hvornår en ligevægt finder sted
        - Hvordan findes $k_{obs}$?:: Det er den reciprokke værdi af hvor lang tid det tog om at opnå ligevægt
        - Hvilket forsøg kan laves for at finde $K_{off}$ uden at bruge $K_{obs}$?:: Receptorer mættes med mærket ligand hvorefter store mængder umærket ligand tilsættes
            - Hvordan findes $K_{off}$ udfra dette?:: Der laves en dissociationskurve hvor $K_{off} $ er hældningen
    - Bindingsassay
        - Hvor meget mærket ligand bruges her?:: Lidt (< 1/10 $K_D$)
        - Hvad sker gøres overordnet i et bidnigsassay?:: En lille mængde mærket ligand tilføjes hvorefter stigende mængder umærket ligand tilføjes
        - Hvad kaldes det når den umærkede ligand har "fjernet"/udkonkureret 50% af den mærkede ligand?:: $IC_{50}$
        - Hvilken konstant leder man efter her?:: $K_i$ den inhibatorisek konstant, som er den konocentartion hvor den umærkede ligand vil binde 50% af receptorene hvis den mærkede ligand ikke var til stede
        - Hvordan regnes den inhibatoriske konstant?:: $$K_i = \frac{IC_{50}}{1 + \frac{[L_{mærket}]}{K_{D(mærket)}}}$$
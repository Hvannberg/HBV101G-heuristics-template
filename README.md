# Heuristics rýni — verkefnasniðmát (HBV101G)

Þetta repo er sniðmát fyrir Nielsen heuristics rýni (5–7 einfaldaðir flokkar) í 3 manna hópum.
Allt fer fram á GitHub: issues, labels og Project board.

## Skref

## TASKS.md (hópa- og task-skrá)
- Fyllið út hópanúmer og nöfn allra í hópnum.
- Skráið 5–7 tasks og númerið þau.
- Í hverju issue, **sláið inn task-númer** í reitnum „Tengt task (# úr TASKS.md)“.

1. **Búið til repo úr sniðmátinu** (`Use this template`).
2. **Kveikið á labels og Project** (sjá neðar).
3. **Hver nemandi** finnur 5–10 vandamál á valinni vefsíðu og **býr til issue** með „Heuristic Evaluation Issue“ formi.
4. **Merkið hvert issue** með viðeigandi heuristic (dropdown í forminu) og severity.
5. **Dragið issues á Project board** í dálk fyrir réttan flokk. Notið „In Review“ og „Done“ eftir þörfum.
6. **Hópsamantekt**: Takið stöðutöflu / innsýn (t.d. 3 stærstu vandamál og tillögur).

## Einfaldaðir flokkar (Nielsen)
1. **Visibility & Feedback**  
2. **Match to real world**  
3. **User control & error prevention**  
4. **Consistency & standards**  
5. **Recognition over recall**  
6. **Flexibility & efficiency**  
7. **Aesthetics & minimalism**  

> Ath.: „Help & documentation“ má teljast með #7 eða #3 eftir samhenginu.

## Labels
- `usability`, `heuristic`, `severity:1` … `severity:5` og einn label fyrir hvern flokk.
- Keyrið workflow **“Sync labels”** (Actions flipi) til að búa þá til.

## Project board
Við ætlum að nota **GitHub Projects (Board view)** til að flokka öll issues eftir Nielsen heuristics.

### Skref 1 – Búa til nýtt Project
1. Farið í repo ykkar → smellið á **Projects** (efst).
2. Smellið á **New project**.
3. Veljið *Create from scratch*.
4. Gefið verkefninu heiti: **Heuristics Board**.

### Skref 2 – Stillt layout sem Board
1. Þegar verkefnið opnast birtist það oft sem tafla (*Table*).
2. Smellið á **⋯ View options** (uppi hægra megin).
3. Veljið **Layout → Board**.
   - Nú sjáið þið dálka líkt og í Kanban-töflu.

### Skref 3 – Búa til dálka fyrir heuristics
Við notum **Status** reitinn til að tákna heuristics-flokka.

1. Smellið á **⋯ View options → Manage fields**.
2. Finnið **Status** og veljið **Edit values**.
3. Breytið options þannig að þau samsvari eftirfarandi heuristics-flokkum:
   - Visibility & Feedback
   - Match to real world
   - User control & error prevention
   - Consistency & standards
   - Recognition over recall
   - Flexibility & efficiency
   - Aesthetics & minimalism

> Þið getið fjarlægt upprunalegu stöðurnar eins og *Todo, In progress, Done* og notað bara heuristics-flokkana.

### Skref 4 – Tengja issues við Project
1. Opnið issue sem þið viljið flokka.
2. Hægra megin undir **Projects**: smellið á **+** og veljið *Heuristics Board*.
3. Veljið **Status = réttur heuristic flokkur** fyrir það issue.
   - Þá raðast issue-ið sjálfkrafa í réttan dálk.

### Skref 5 – Skoða heildaryfirlit
Nú sést á borðinu:
- Hversu mörg vandamál féllu undir hvern heuristics-flokk.
- Hvaða issues eru skráð í hópnum.


## Skil
- Exportið stöðutöflu sem mynd/pdf ef óskað er, eða vísið í repo + Project.


## Discussions (valkvætt)
- Notið **Discussions** flipann fyrir spurningar, umræðu og almennar athugasemdir.
- Kennari getur sett pinned Discussions fyrir Q&A eða leiðbeiningar.
- **Issues eru eingöngu fyrir heuristics-vandamál**, en Discussions er frjálsari vettvangur.

---

### Flýtileiðbeiningar fyrir kennara
- Stillið repo sem **Template repository** (Settings → General).
- Uppfærið texta í `.github/ISSUE_TEMPLATE/heuristic-issue.yml` ef þið breytið flokkum.
- **Optional:** Breytið `workflows/setup-project.yml` ef þið viljið Projects (beta) í stað classic.


## Discussions (valkvætt)
- Notið **Discussions** flipann fyrir spurningar, umræðu og almennar athugasemdir.
- Kennari getur sett pinned Discussions fyrir Q&A eða leiðbeiningar.
- **Issues eru eingöngu fyrir heuristics-vandamál**, en Discussions er frjálsari vettvangur.

---

© HBV101G

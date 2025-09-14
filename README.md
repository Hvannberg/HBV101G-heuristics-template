## A3 Heuristics rýni — verkefnasniðmát (HBV101G)

Þetta repository er sniðmát fyrir Nielsen heuristics rýni (5–7 einfaldaðir flokkar) sem er framkvæmt í 2 - 3 manna hópum.
Allt fer fram á GitHub: issues, labels og Project board.

## Skref

## Skref 1. Stofnið reikning á github.com 
Stofnið reikning á github.com og setjið upp

## Skref 2. Búið til eigið repo 
1. **Búið til repo úr sniðmátinu og gefið því nafn** (`Use this template`).
2. **Kveikið á labels og Project** (sjá neðar).


## Skref 3. TASKS.md (hópa- og task-skrá)
- Fyllið út hópanúmer og nöfn allra í hópnum.
- Skráið 5–7 tasks (verkefni) sem hægt er að leysa á vefsíðunni og númerið þau.
- Í hverju issue (sjá hér að neðan), **sláið inn task-númer** í reitnum „Tengt task (# úr TASKS.md)“.
  

## Skref 4. Labels
- `usability`, `heuristic`, `severity:1` … `severity:5` og einn label fyrir hvern flokk.
- Keyrið workflow **“Sync labels”** (Actions flipi) til að búa þá til.

### Skref 5 – Búa til nýtt Project
Við ætlum að nota **GitHub Projects (Board view)** til að flokka öll issues eftir Nielsen heuristics.
1. Farið í repo ykkar → smellið á **Projects** (efst).
2. Smellið á **New project**.
3. Veljið *Create from scratch*.
4. Gefið verkefninu heiti: **Heuristics Board**.

### Skref 6 – Stillt layout sem Board
1. Þegar verkefnið opnast birtist það oft sem tafla (*Table*).
2. Smellið á **⋯ View options** (uppi hægra megin).
3. Veljið **Layout → Board**.
   - Nú sjáið þið dálka líkt og í töflu.

### Skref 7 – Búa til dálka fyrir heuristics
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

### Skref 8 - nemendur finna vandamál á vefsíðunni 
3. **Hver nemandi** finnur 5–10 vandamál á valinni vefsíðu og **býr til issue** (New issue) með „Heuristic Evaluation Issue“ formi fyrir hvert vandamál.
4. **Merkið hvert issue** með viðeigandi heuristic (dropdown í forminu) og **alvarleika** (severity).
5. **Dragið issues á Project board** í dálk fyrir réttan flokk. (sjá næsta skref) 

   
### Skref 9 – Tengja issues við Project
1. Opnið issue sem þið viljið flokka.
2. Hægra megin undir **Projects**: smellið á **+** og veljið *Heuristics Board*.
3. Veljið **Status = réttur heuristic flokkur** fyrir það issue.
   - Þá raðast issue-ið sjálfkrafa í réttan dálk.

### Skref 10 – Skoða heildaryfirlit
Nú sést á borðinu:
- Hversu mörg vandamál féllu undir hvern heuristics-flokk.
- Hvaða issues eru skráð í hópnum.


## Skil
- Exportið stöðutöflu sem mynd/pdf ef óskað er, eða vísið í repo + Project á Gradescope 


## Discussions (valkvætt)
- Notið **Discussions** flipann fyrir spurningar, umræðu og almennar athugasemdir.
- Kennari getur sett pinned Discussions fyrir Q&A eða leiðbeiningar.
- **Issues eru eingöngu fyrir heuristics-vandamál**, en Discussions er frjálsari vettvangur.

---

### Flýtileiðbeiningar fyrir kennara
- Stillið repo sem **Template repository** (Settings → General).
- Uppfærið texta í `.github/ISSUE_TEMPLATE/heuristic-issue.yml` ef þið breytið flokkum.
- **Optional:** Breytið `workflows/setup-project.yml` ef þið viljið Projects (beta) í stað classic.



---

© HBV101G

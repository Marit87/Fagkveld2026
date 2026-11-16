# Rapportplan

## Mål og målgruppe
- Målgruppe: Ledere og beslutningstakere som ønsker en rask oversikt over utviklingen i dataene.
- Beslutning rapporten skal støtte: Gi brukeren et overordnet bilde av status og utvikling, og gjøre det enkelt å identifisere områder som bør undersøkes nærmere.

## Første leveranse
- Side 1: En enkel oversiktsside som viser de viktigste nøkkeltallene og utviklingen i dataene.
- Visualer:
  - Nøkkeltall/KPI-er øverst på siden.
  - Ett visual som viser utvikling over tid.
  - Ett visual som viser fordeling eller sammenligning mellom relevante kategorier.
- Filtre/slicere:
  - Bruk relevante eksisterende dimensjoner i modellen.
  - Begrens antall slicere slik at siden er enkel å bruke.

## Data og beregninger
- Eksisterende felter/measures:
  - Bruk eksisterende felter og measures i den semantiske modellen der det er mulig.
  - Agenten skal undersøke modellen og velge relevante eksisterende modellobjekter.
- Må avklares:
  - Dersom nødvendige measures eller dimensjoner ikke finnes, skal agenten stoppe og beskrive hva som mangler før nye modellobjekter opprettes.
  - Agenten skal ikke gjette betydningen av uklare felter eller measures.

## Akseptansekriterier
- [ ] PBIP åpner uten feil
- [ ] Rapporten inneholder én ferdig rapportside
- [ ] Siden gir målgruppen en tydelig oversikt over de viktigste nøkkeltallene
- [ ] Alle visualer bruker eksisterende modellobjekter
- [ ] Rapporten følger en enkel og konsistent visuell struktur
- [ ] Ingen legitimasjon eller cache er lagt til
- [ ] Agenten har ikke opprettet nye measures uten at dette er avklart

## Ikke-mål
- Det skal ikke bygges en komplett rapport med flere sider.
- Den semantiske modellen skal ikke bygges om.
- Nye datakilder skal ikke legges til.
- Det skal ikke gjøres større endringer utenfor det som er nødvendig for første rapportside.
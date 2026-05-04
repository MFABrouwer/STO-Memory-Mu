# STO-Memory-Mu

Persoonlijke single source of truth voor mijn Star Trek Online characters, builds, gear en progressie. Public repo — gaming hoort bij wie ik ben, en als een recruiter daar moeite mee heeft is dat een red flag voor de werkomgeving.

De naam **Memory-Mu** is een knipoog naar Memory Alpha (de Trek wiki) en Miran'**U**kan, mijn huidige main captain.

## Doel

Voorheen scrollde ik door oude chats om Phoenix store inhoud, BOff traits of ship loadouts terug te vinden. Nu staat alles hier, gestructureerd, en kan ik per onderwerp updaten zonder een hele chat door te ploeteren.

## Folderstructuur

| Folder | Inhoud |
|--------|--------|
| `01-captain/` | Captain info: race, career, skills, personal traits |
| `02-boffs/` | Bridge Officer roster (space + ground) met traits per BOff |
| `03-ships/` | Per ship een eigen markdown met volledige loadout |
| `04-traits/` | Personal Space, Personal Ground, Starship traits, Active Reputation |
| `05-reputation/` | Reputation tiers, gear bezit, target items, DOff/Admiralty/R&D |
| `06-stores/` | Phoenix, C-store, Mudd's, Fleet, Lobi store inhoud + bezit-status |
| `07-doctrines/` | Build-filosofie en design documents (Sharande Doctrine 2.0) |
| `08-doffs/` | Active duty officers + lopende assignments |

Elke folder heeft een `screenshots/` subfolder voor visuele referenties.

## Werkmethode met Claude

Bij start van een nieuwe STO chat: paste de URL van deze repo of de relevante files in. Omdat de repo public is kan Claude via web_fetch direct lezen wat hier staat — geen copy-paste nodig.

Voorbeeld eerste prompt:
> "STO sessie. Check mijn repo https://github.com/MFABrouwer/STO-Memory-Mu — bekijk in elk geval `03-ships/ankylosaur.md` en `07-doctrines/sharande-doctrine-2.md`. Vandaag wil ik [onderwerp]."

Voor specifieke vragen kan Claude gerichte fetches doen op individuele bestanden via `https://raw.githubusercontent.com/MFABrouwer/STO-Memory-Mu/main/[pad]`.

## Update-momenten

Werk dit bij wanneer:
- Een ship-loadout fundamenteel verandert (nieuw wapen, nieuw console, nieuwe set)
- Een BOff trait wordt aangepast of een nieuwe BOff wordt geslot
- Een rep een nieuwe tier bereikt of een rep store item wordt gekocht
- Een Phoenix/Mudd's/Lobi item wordt aangeschaft
- De doctrine zelf evolueert (nieuwe target stats, nieuwe filosofie)

Niet bijwerken voor tijdelijke zaken (lopende dailies, kortdurende events).

## Status per file

| File | Initieel ingevuld | Volledig |
|------|-------------------|----------|
| `01-captain/README.md` | Ja | Nee — skills tab nog leeg |
| `02-boffs/README.md` | Template | Nee |
| `03-ships/ankylosaur.md` | Ja, basis | Deflector/engines/shields/core nog open |
| `03-ships/nagh-sar.md` | Template | Nee |
| `04-traits/README.md` | Ja, alle 4 categorieën | Nee — Active Rep slots beperkt |
| `05-reputation/*.md` | Templates | Nee |
| `06-stores/phoenix-store.md` | Template | Nee — vraagt screenshots per tier |
| `06-stores/c-store.md` | Template | Nee — Zen balance teller op 4826 |
| `06-stores/fleet-stores.md` | Template | Nee — Space + Ground secties |
| `06-stores/mudds-market.md` | Template | Nee |
| `06-stores/lobi-store.md` | Template | Nee |
| `07-doctrines/sharande-doctrine-2.md` | Ja | Levend document |
| `08-doffs/README.md` | Template | Nee |

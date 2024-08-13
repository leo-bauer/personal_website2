---
layout: default
---

## Converting SRDP Faction IDs to UCDP Actor IDs

This project creates an interface between the SRDP dataset and the UCDP universe. The conversion table provides a comprehensive list of SRDP factions that exist in the UCDP universe as well. Matches were obtained using a two-step approach: First, an automated string matching technique was employed to match SRDP factions with UCDP non-state actors and then manually validated. Second, SRDP factions not matched with this technique were then manually searched in UCDP and matched. As SRDP factions are sometimes more disaggregated than UCDP actors, several SRDP factions may match with the same UCDP actor but not the other way around. The approach allowed for 230 SRDP factions matching with 141 non-state actors in UCDP.

The conversion spreadsheet includes the primary name of the SRDP faction, its self-determination dispute ID, faction ID and the corresponding UCDP actor ID. It can be downloaded [here](/files/srdp-ucdp_conversion.csv){:target="_blank"}{:rel="noopener noreferrer"}.

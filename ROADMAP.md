<img src="assets/sec-build.svg" alt="Bathyal development roadmap" width="100%">

# Public roadmap

Bathyal is an alpha project. This page tracks what is working, what has been tested in the game, what still needs
balance or polish, and what may be added later. It is updated alongside public builds; a checked system can still
receive tuning or more content.

**Current public build:** v0.10.91 · **Last updated:** 2 October 2026

| Status | Meaning |
|---|---|
| **Implemented** | The intended current system exists in code and content. |
| **Verified** | A person has exercised its main path in the running pack. |
| **Partial** | Useful parts exist, but scope, integration or testing remains. |
| **Planned** | Approved direction without a complete implementation. |
| **Potential** | An idea under consideration, not a promise. |

The internal audit currently tracks **85 system groups: 58 implemented, 18 partial and 9 not implemented**.

## Current feature sets

| Area | Current state | Verification, balance and polish still needed |
|---|---|---|
| **World generation** | **Implemented and verified.** A fixed, multi-layer map system builds the continents, climate bands, coastlines and regional terrain. | Retain a reproducible full-world test fixture; decide the long-term pregeneration and update policy. |
| **Settlements and roads** | **Implemented and largely verified.** Forty settlements, regional architecture, interiors, walls, roads and service buildings generate from authored plans. | Investigate rare generation faults when a repeatable location is found; add diagonal gatehouse variants and minor visual polish. |
| **Harbours** | **Implemented and verified.** Port approaches, stairs, piers and working dock services are present. | Minor presentation polish and more port activity. |
| **Survival** | **Implemented and verified.** Thirst, temperature, injury, seasons, clothing, restrained healing, death costs and graves form the baseline. | Campaign-length pacing and accessibility tuning. |
| **Food, preservation and alchemy** | **Partial.** Regional ingredients, spoilage, preserved food, drinks and useful alchemical products are wired. | Full recipe/effect playthrough, pacing, price and scarcity balance. |
| **Character creation and races** | **Implemented and verified.** Six playable races, adaptive starting regions, callings and difficulty contracts are active. | Presentation polish and long-run balance across climates and disciplines. |
| **Skills and progression** | **Implemented and verified.** Twenty-six work-driven trees include exclusive authored forks, gates, abilities and capstones. | Cross-mod exploit coverage, clearer descriptions and late-game progression tuning. |
| **Training and respecialisation** | **Implemented and verified.** Craft professionals offer paid apprenticeships, staged work and costly discipline resets. | Tune prices, materials, rewards and pacing in a normal survival playthrough. |
| **Equipment and materials** | **Partial.** Custom ores, processing, four equipment families, held models and worn armour visuals are active. | Give each material a stronger mechanical identity and finish the highest-tier equipment and crafting uses. |
| **Combat** | **Implemented and verified.** Faster exchanges, precise positioning, aerial and rear attacks, narrow perfect guards, rolls and weapon movesets coexist. | Boss-by-boss balance, encounter pacing and accessibility options while preserving a high skill ceiling. |
| **Magic** | **Partial.** Three public schools, study, spell progression, mana, reagents, arts and social reactions are active. | More spectacle, additional crafted foci and broader casting-mod coverage. One progression reveal repair in v0.10.91 awaits focused retesting. |
| **Society and trade** | **Implemented.** Regional populations, personal and local standing, daily shop stock, scarcity pricing, resale limits and private trade are active. | Wider income sources, taxes and major money sinks; longer economic balance runs. |
| **Law and stealth** | **Implemented and mostly verified.** Theft, witnesses, assault, murder, arrest, fines, jail, resistance and civilian reactions have distinct outcomes. | Retest fixed shop proprietors as witnesses in v0.10.91 and continue adversarial edge-case testing. |
| **Travel and services** | **Implemented and verified.** Regional transport, mount purchase/storage, inns, shipwrights and refit services use the same economy. | Tune service prices and add more local presentation. |
| **Quests and dialogue** | **Partial.** The runtime loads 335 quests and 394 stages with branching conditions, moods, adaptive locations and named-character chains. | Full end-to-end playthrough, more world interactions, stronger dialogue presentation and relationship systems. |
| **Ships and crews** | **Implemented and partly verified.** Ships are commissioned, crewed, armed, supplied and moved by adaptive port-to-port navigation; merchants, patrols and pirates operate at sea. | Capture a repeatable case for rare terrain collisions, stress-test busy seas, and tune combat, wages and trade. |
| **Discovery and presentation** | **Implemented and verified.** Compass markers, atlas markers, settlement reveals, regional music, menus and character creation presentation work in the current client. | Remaining third-party screens, tooltip consistency, resolution coverage and general UI polish. |
| **Packaging and public safeguards** | **Implemented and verified.** Development and public packages are built separately; public world-creation and item-give restrictions are enforced. | Clean-install, update-path, multiplayer and distribution-platform acceptance later in alpha. |

## Work order

1. Retest the three focused v0.10.91 repairs: crafting refusal placement, one progression reveal and fixed-proprietor
   theft witnessing.
2. Complete and balance food, preservation and alchemy as a full survival loop.
3. Configure the rarity/reforging economy and finish advanced material identities and top-tier equipment.
4. Reproduce any remaining vessel collision, then harden adaptive navigation against the exact terrain case.
5. Run the existing quest graph end to end and complete its missing world interactions and character content.
6. Build deeper relationships, faction play and authored exploration content.
7. Establish the canonical-world/update policy, then perform clean install, multiplayer, performance and complete
   survival-to-endgame testing.

## Planned systems

- A complete rarity, affix and reforging economy tied to Bathyal materials.
- Stronger individual identities and endgame uses for advanced ores and crafted equipment.
- Deeper personal relationships and optional romance content.
- Playable faction conflicts, treaties and political consequences.
- More authored dungeons, regional encounters and deep-sea exploration hazards.
- Player ship capture, re-helming and late-game airships.
- A regional dust-storm cycle in Suraza.
- A stable world-update policy once the alpha format settles.

## Potential additions

These remain proposals and may change or be dropped:

- Authored diagonal gatehouses where angled roads meet angled walls.
- Apprenticeships for selected non-craft disciplines.
- A larger tavern loop joining brewing, music, performance and social benefits.
- More settlement-specific services, local events and ambient work routines.

<img src="assets/footer.svg" alt="The depths remain, and so do the stories." width="100%">

<img src="assets/sec-build.svg" alt="Bathyal development roadmap" width="100%">

# Public roadmap

Bathyal is an alpha project. This page is updated with public builds and records implementation, verification,
balance and remaining work. Features can be implemented while their wider playthrough or multiplayer tests remain
unfinished. There is no promised release schedule.

**Current public build:** [v0.10.99](https://github.com/TAS-69/bathyal/releases/tag/v0.10.99) · **Last updated:** 4 October 2026

| Status | Meaning |
|---|---|
| **Implemented** | The current system exists in code and content. |
| **Player verified** | Its main path has been exercised by the creator in the running pack; later changes can need retesting. |
| **Runtime checked** | A controlled native game test passed; this is narrower than a complete pack playthrough. |
| **Partial** | Useful parts exist; content, integration or acceptance remains. |
| **Planned** | Approved direction without a complete implementation. |
| **Potential** | An idea under consideration, not a promise. |

## Current feature sets

| Area | Current state and evidence | Balance, polish and remaining acceptance |
|---|---|---|
| **World generation** | **Implemented; core player verified.** A fixed multi-layer map system builds continents, climate bands, coasts and regional terrain. | Full-world generation performance and the long-term world/update policy. |
| **Settlements and roads** | **Implemented; latest layouts runtime checked.** Forty settlements use regional structure variants, furnished interiors, civic amenities, accessible farms and full-height diagonal gatehouses. Controlled entrance, wall and support samples pass. | Review the latest tree-court grading, keep placement, wall alignment and interiors in a fresh world. Older player verification predates the overhaul; rare generation faults and visual polish remain. |
| **Harbours** | **Implemented; three updated port routes runtime checked.** Continuous street-to-pier approaches, port buildings, cargo and services are present. | Check the other ports, coastal terrain variations and busy port activity. |
| **Survival** | **Implemented; core player verified.** Thirst, temperature, injury, seasons, clothing, healing limits, death costs and graves form the baseline. | Campaign pacing, accessibility and climate balance with mixed clothing/armour. |
| **Food, preservation and alchemy** | **Partial.** Regional ingredients, spoilage, preservation, drinks and useful alchemical products are wired. | Full recipe/effect playthrough, scarcity, prices and survival-loop pacing. |
| **Character creation and races** | **Implemented; core player verified.** Six races, adaptive starting regions, callings and difficulty contracts are active. | Long-run discipline and climate balance; presentation polish. |
| **Skills and progression** | **Implemented; catalogue and selected paths runtime checked.** Twenty-six activity-driven trees, exclusive forks and gates remain. The installed server registry has 3,139 blocks and 5,386 items categorised, with zero unknown entries. Hay uses Farming. | Check individual material tiers, third-party crafting/automation and acquisition exploits. Catalogue coverage is not proof that every mod interaction is balanced or tested. |
| **Training and respecialisation** | **Implemented; connected transactions runtime checked.** Paid apprenticeships, staged craft work and costly discipline resets are available. Unavailable actions explain their requirements. | Prices, materials, XP and reward pacing during normal survival. |
| **Equipment and materials** | **Partial; current armour resistance runtime checked.** Regional equipment has distinct textures; all sixteen custom metal armour pieces provide temperature resistance through the survival system. | Armour appearance and climate balance, stronger advanced-material mechanics and endgame uses. |
| **Combat** | **Implemented; core player verified.** Faster exchanges, positioning, aerial/rear attacks, precise guards, rolls and weapon movesets coexist. | Boss-by-boss tuning, encounter pacing and accessibility while retaining the skill ceiling. |
| **Magic** | **Partial; core public-school play player verified.** Three schools support study, spell progression, mana, reagents, arts and social reactions. | Visual spectacle, crafted foci and wider casting-mod coverage. |
| **Society and trade** | **Implemented; selected transactions runtime checked.** Regional populations, personal/local standing, stock, scarcity pricing, resale limits and private trade remain. Guards offer talk, bribes and pickpocket interactions, without trade. | Long economic balance runs, service prices and personal-relationship responses. Bribes affect settlement standing, not individual regard. |
| **Law and stealth** | **Implemented; recent witness/LOS scenarios runtime checked.** Shop proprietors and watch can witness theft. Cover and viewing direction affect detection; undetected crouched players do not draw passive gaze. The crouched eye replaces the crosshair. | Crowded settlements, darkness, skill upgrades, pursuit and multiplayer edge cases. |
| **Travel and services** | **Implemented; core player verification and transaction checks.** Regional transport, mounts, inns, shipwrights and refits use the same economy. | Further pet/mount progression verification, prices and local polish. |
| **Quests and dialogue** | **Partial; navigation and tracking runtime checked.** The custom interface uses two-column choices, Back navigation, disabled-action reasons and a closer shoulder camera with temporary interaction holds. Journal clicks toggle up to three compact tracked quests; current main/character world markers stay blue/purple. Job icons gain a silhouette-shaped yellow offer glow. | Full quest-chain playthroughs, adaptive-location cases, remaining character content and relationships. Latest offer-outline appearance awaits player confirmation. NarrativeCraft remains available for optional scripted scenes. |
| **Ships and crews** | **Implemented; controlled sailing/fleet checks pass.** Merchants, pirates, patrols, crews, trading and unloaded fleet travel remain. Navigation, target priority and sail/cannon stability have received repairs. | Long voyages, narrow channels, live obstacles, multiple competing ships, combat and wages. Controlled tests do not establish universally optimal or collision-free travel. |
| **Residents and appearance** | **Implemented with partial cast acceptance.** Full names, separate trade badges, race/region naming, outfit repairs, lighting and home/work/rest routines are present. Controlled identity and sleep/wake checks pass. | Remaining named cast placement, portrait likeness, voice matching, all occupation badges and complete daily cycles in the full client. |
| **Performance** | **Partial; measured improvements in a controlled runtime comparison.** Ship route planning, hull/traffic scans, home/bed path work and appearance-cache churn were reduced while retaining their features. | Whole-pack client/shader stress, new chunks, dense towns, busy seas, item cleanup and multiplayer profiling. No universal FPS or stutter-free claim. |
| **Discovery and presentation** | **Implemented; core player verified.** Compass/atlas markers, settlement aerial reveals, regional music, menus and creation presentation remain. | Remaining third-party screens, tooltips, resolutions and UI polish. |
| **Packaging and safeguards** | **Implemented; both flavours build and integrity checks pass.** Public world-creation and item-give restrictions remain enabled; the public release contains only that flavour. | Clean-install/update-path/multiplayer distribution acceptance is lower priority during alpha. |

## Next work

1. Confirm the latest UI, offer-icon outline, tracking, theft/stealth and armour changes in the full client.
2. Review the latest settlement overhaul in fresh worlds and record precise locations for remaining terrain or access faults.
3. Complete and balance food, preservation and alchemy as one survival loop.
4. Validate cross-mod progression gates, advanced materials, rarity/reforging and endgame equipment.
5. Profile busy settlements, seas and new-chunk travel; reproduce ship problems before further tuning.
6. Play linked quest chains end to end, including adaptive starts, and complete remaining character interactions.
7. Deepen relationships and faction play, then perform broader survival-to-endgame balance runs.
8. Establish world/update policy and complete multiplayer, clean-install and distribution acceptance later in alpha.

## Planned systems

- A complete rarity, affix and reforging economy tied to Bathyal materials.
- Stronger individual identities and endgame uses for advanced equipment.
- Deeper personal relationships and optional romance.
- Playable faction conflicts, treaties and political consequences.
- More authored dungeons, regional encounters and exploration hazards.
- Player ship capture, re-helming and late-game airships.
- A regional dust-storm cycle in Suraza.
- A stable world-update policy once the alpha format settles.

## Potential additions

These remain proposals and may change or be dropped:

- Apprenticeships for selected non-craft disciplines.
- A larger tavern loop joining brewing, music, performance and social benefits.
- More settlement-specific services, local events and ambient work routines.

<img src="assets/footer.svg" alt="The depths remain, and so do the stories." width="100%">

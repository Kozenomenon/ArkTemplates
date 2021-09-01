# ArkTemplates
 Template BPs for modding Ark: Survival Evolved

## Contents
- Template_CCA
  - Parent: Actor
  - Will not persist / Does not replicate
- Template_CCA_Rep
  - Parent: Actor
  - Will not persist / Replicates to clients
- Template_CCA_Save
  - Parent: SaveGameActor
  - Persists w/ worldsave / Does not replicate
- Template_CCA_Save_Rep
  - Parent: SaveGameActor
  - Persists w/ worldsave / Replicates to clients
 
## Functionality
- Highlander Check
  - There can be only one / Singleton enforcement
- CAL Registration
  - Easily find your CCA from other blueprints
- Logging
  - For PIE and Live Game (enabled via INI setting)
  - Includes handling for client logs if replicated
- Custom Admin Commands
  - Example functions included
- Mod Comm Interface
  - Example function included
- Apply Player Buffs on spawn

_Tooltips / comments included in the source._
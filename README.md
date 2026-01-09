# [DotaFlow](https://dotaflow.online)

## Folders
### experimental/public/staging
- **_VersionsHistory.json**: saved history of Dota Client updates
- **GetClientVersion.json**: latest response from IGCVersion_*/GetClientVersion steam API
- **GetServerVersion.json**: latest response from IGCVersion_*/GetServerVersion steam API
- **GetSDRConfig.**: latest response from ISteamApps/GetSDRConfig steam API
- **GetHeroes.json**: latest response from IEconDOTA2_*/GetHeroes steam API
- **GetStoreMetaData.json**: latest response from IEconItems_*/GetStoreMetaData steam API
____
- - ___Checked app IDs___
- - - Experimental - 247040 
- - - Staging - 2305270
- - - Public - 570
____
### web
- #### abilities
- - **_AbilityList.json**: latest response from /datafeed/abilitylist dota2 API
- - ...All abilities passed through /datafeed/abilitydata from the abilitylist (**arc_warden_flux.json** for example)
____
- #### heroes
- - **_HeroesList.json**: latest response from /datafeed/herolist dota2 API
- - ...All heroes passed through /datafeed/herodata from the herolist (**npc_dota_hero_axe.json** for example)
____
- #### items
- - **_ItemsList.json**: latest response from /datafeed/itemlist dota2 API
- - ...All items passed through /datafeed/itemdata from the itemlist (**item_blink.json** for example)
____
- #### patches
- - **_PatchesList.json**: latest response from /datafeed/patchnoteslist dota2 API
- - ...All patches passed through /datafeed/patchnotes from the patchnoteslist (**7.08.json** for example)
____
- #### other
- - **_DotaUniqueUsers.json**: latest response from /datafeed/uniqueusers dota2 API
____
- #### steamEvents
- - **_News%app_id%.json**: last 5 news for app_id (cs2, dota2, deadlock checked)
____

## Links
- Telegram with updates notifications: [t.me/dotaflowupdates](https://t.me/dotaflowupdates)
- Telegram with news/datamine: [t.me/DotaFlowNews](https://t.me/DotaFlowNews)
- Our website: [dotaflow.online](https://dotaflow.online)
- Contact: contact@dotaflow.online (or t.me/notrenuit for some private staff)
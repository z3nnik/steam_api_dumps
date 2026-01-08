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
- abilities (folder)
- - **_AbilityList.jsom**: latest response from /datafeed/abilitylist dota2 API
- - ...All abilities passed through /datafeed/abilitydata from the abilitylist (**arc_warden_flux.json** for example)
____
- heroes (folder)
- - **_HeroesList.jsom**: latest response from /datafeed/herolist dota2 API
- - ...All heroes passed through /datafeed/herodata from the herolist (**npc_dota_hero_axe.json** for example)
____
- items (folder)
- - **_ItemsList.jsom**: latest response from /datafeed/itemlist dota2 API
- - ...All items passed through /datafeed/itemdata from the itemlist (**item_blink.json** for example)
____
- patches (folder)
- - **_PatchesList.jsom**: latest response from /datafeed/patchnoteslist dota2 API
- - ...All patches passed through /datafeed/patchnotes from the patchnoteslist (**7.08.json** for example)
____

- - **CS2Events.json** (3 latest news-events for cs2 public app)
- - **DeadlockEvents.json** (3 latest news-events for deadlock public app)
- - **DotaEvents.json** (3 latest news-events for dota2 public app)
- - **DotaPatches.json** (latest response from /datafeed/patchnoteslist; legacy, but updating too)
- - **DotaUniqueUsers.json** (latest response from /datafeed/uniqueusers)
- - **HeroList.json** (latest response from /datafeed/herolist, legacy, but updating too)
- - **HeroListCN.json** (latest response from /datafeed/herolist for dota2.com.cn, legacy, but updating too)

## Links
- Telegram with updates notifications: [t.me/dotaflowupdates](https://t.me/dotaflowupdates)
- Telegram with news/datamine: [t.me/DotaFlowNews](https://t.me/DotaFlowNews)
- Our website: [dotaflow.online](https://dotaflow.online)
- Contact: contact@dotaflow.online (or t.me/notrenuit for some private staff)
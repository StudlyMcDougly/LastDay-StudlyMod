# LastDay-StudlyMod

My setup for [S.T.A.L.K.E.R.: Last Day](http://www.moddb.com/mods/stalker-last-day). Includes a collection of mods as well as some of my own tweaks.<br/>
<br/>
Requires:<br/>
[S.T.A.L.K.E.R.: Last Day — version 1.3 + patch](http://www.moddb.com/mods/stalker-last-day/downloads/last-day-1-3)<br/>
[Last Day — fix (2018/3/14)](https://drive.google.com/file/d/1BFSO2yjtKZIClWsBmrrINI8_EBkPMlQP/view)<br/>
## Mods
**_[S.T.A.L.K.E.R.: Last Day — Translation [0.11.2] (Ver: 4/23/2018)](http://www.moddb.com/mods/stalker-last-day/downloads/last-day-english-translation)_**<br/>
*Translates the mod to English*<br/>
<br/>
**_[TRX: Fixes 'n' Tweaks (6.5) [LD 1.3 +Patch] (Ver: 4/22/2018)](http://www.moddb.com/mods/stalker-last-day/addons/trx-fixes-improvements-last-day-13-patch)_**<br/>
Optional Tweaks:
- Feature - Choose the Route You're Paying For
- Feature - DRX Dynamic Faction Relations
- Sounds - Restore Anomalies Beeping Sound

**_[Call of Misery English Voices Addon (1.5) (Ver: 4/2/2017)](http://www.moddb.com/mods/call-of-chernobyl/addons/coc-english-voices-addon)_**<br/>
*Adds in English Voices. Used all sound files so NPCs will probably have multiple voices.*<br/>
<br/>
**_[CoM Mutant Ambient Sound Removal [1.0d+] (Ver: 5/24/2017)](http://www.moddb.com/mods/stalker-com/addons/com-mutant-ambient-sound-removal)_**<br/>
*Removes the random ambient mutant sounds (like bloodsucker roar etc) you hear when walking around even though the mutant isn't actually there. Supposed to be scary but just annoying.*<br/>
<br/>
**_[Last Day 1.3+ Last Wishes 15 (Ver: 4/13/2018)](http://www.moddb.com/mods/stalker-last-day/addons/last-day-13-last-wishes)_**<br/>
**Last Wish Traders**<br>
*Gives traders a slightly better selection so there isnt as much RNG when buying equipment, food etc. Lowers goodwill needed for better tiers. Installed version that just adds stock and lowers goodwill, not all stock.*
>Traders will have more selections and high quantities available for misc items and equipment. Armor and weapons selections are spread out more now so you wont be seeing any modern or new weapons in supply level 2 for example (few exceptions), however all trader supply levels require less goodwill making further supply levels easier to reach. Last Wishes traders have a max of 1000 goodwill and start upgrading their supply at 400 goodwill with each new supply level earned every 200 goodwill after (1000,800,600,400).

**Last Wish Less Spongy Monsters**<br>
*Boars suck at extremely low level. Makes it easier when first starting out but they will still mess you up good.*
>Reduced damage resistance for boar, burer, chimera, flesh, giant and snork. resistances were lowered about 1/3 or 1/4 so they should no longer eat shotgun blasts to the face and just shrug it off.

**_[QoL Addons for LD [1.3+] (Ver: 2/3/2018)](http://www.moddb.com/mods/stalker-last-day/addons/qol-addons-for-ld-13)_**<br/>
**OTHER - No blackouts and input blocks**<br/>
*Disables camera blackout and input block when using items and putting on gear.*<br/>
<br/>
**_[TRX: Global Weather (2.1) (Ver: 4/25/2018)](http://www.moddb.com/mods/stalker-last-day/addons/trx-global-weather)_**<br/>
*Synchronizes weather throughout the Zone*<br/>
## My Mods
**English Duty Loudspeaker**<br/>
*Restores Duty propaganda and announcments in the Bar/Duty area. So now you can hear more about deadly anomalies, dangerous mutants, anarchists, and bandits!*<br/>
`gamedata\sounds\characters_voice\scenario\bar\megafon`<br/>
<br/>
**Remove Near Death Aurora Borealis Effect**<br/>
*Removes the Aurora Borealis effect (which is an amped up Alchohol effect) that happens when you reach below 30% health. Supposed to make is challenging but is more annoying. Might find a better effect later.*<br/>
`gamedata\scripts\dinamic_hud.script`<br/>
<br/>
**Drink Mod**<br/>
*Adds a HUD message whenever you are fully hydrated (Drink meter reaches 0).*<br/>
`gamedata\scripts\drink.script`<br/>
<br/>
**Actor.ltx Mod**<br/>
*Changes the grenade awareness time from 0.4 seconds to 1 second. Gives you a little bit more awareness time of grenades to avoid cheap kills. Will adjust.*<br/>
`gamedata\configs\creatures\actor.ltx`<br/>
<br/>
**Trader Mod**<br/>
*Changes 2 traders to bring them in line with the Last Wishes mod. Only modifies the goodwill needed. Discount, item condition needed, and stock remain unchanged*<br/>
`gamedata\configs\misc\trade\trade_esc_owl.ltx`<br/>
`gamedata\configs\misc\trade\trade_military_esc.ltx`<br/>
<br/>
**Translation Fixes**<br/>
_Fixes translation files that fall through the gap from the original translation mod as well as incompatibility between mods_<br/>
`gamedata\configs\text\eng\ui_st_encyclopedia_area.xml`<br/>
<br/>
**Radiation Level Reporting UI Normalize**<br/>
_Normalizes the radiation levels as reported in game. Different mods reported radiation levels at different factors, thus you didn't know what your radiation was and exactly how much something would hurt you. Does not change any items/artifacts but just reports them to be more in line with real life where:<br/>
0.35 in game rads (Yellow) = 2,000 mSv (Severe Radiation Poisoning)<br/>
0.7 in game rads (Red) = 4,000 mSv (Usually Fatal unless immediately treated)<br/>
1 in game rad = 5,714 mSv_<br/>
`gamedata\configs\ui\af_params.xml`
`gamedata\configs\ui\af_params_16.xml`
`gamedata\configs\ui\booster_params.xml`
`gamedata\configs\ui\booster_params_16.xml`
`gamedata\scripts\itms_manager.script`
`gamedata\configs\text\eng\st_items_mutant_parts.xml'

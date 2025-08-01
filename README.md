## 2025-07-25
- Merge branch 'master' into Playerbot
- chore(DB): import pending files
- fix(Script/Creature): Add random delay to Gargoyle casts (#22512)
- fix(DB/Event): Scourge Invasion Shadow of Doom and rare loot (#22518)

## 2025-07-24
- chore(DB): import pending files
- fix(DB/Spawns) Removes 6x creature spawns for "Lordaeron Citizen" (#22552)
- feat(Core/Load): Add debug logs for zone and area assignment (#22509)
- fix(Conf/Misc): Update max visibility description (#22187)
- chore(DB): import pending files
- fix(DB/SAI): Implement various missing Culling of Stratholme behaviours (part 2). (#22550)
- fix(Core/Spell): skip Guardian pets when searching for Party/Raid members (#22528)
- fix(Core/Account): Change account flag updates to async connection (#22547)
- chore(DB): import pending files
- feat(Core/Account): Add account flags support (#22533)
- fix(Core/Unit): wrong behavior of `HasUnitMovementFlag` (#22529)
- chore(DB): import pending files
- fix(DB/SAI): Implement various missing Culling of Stratholme behaviours (#22545)
- fix(Scripts/Northrend): Ulduar Mimiron plasma ball always target victim (#22543)
- chore(DB): import pending files
- fix(DB/Creature): Update Amanitar spawn position (#22542)

## 2025-07-23
- fix(DB/SQL): Do not give all permissions to user "acore" upon creation via the sql file (#22540)
- fix(Core/Player): Only mark spells as invalid when none of the Skills match (#22537)
- chore(DB): import pending files
- fix(DB/Creature): Rhunok cannot be attacked anymore without using first Tormentor's Incense. (#22534)

## 2025-07-22
- chore(DB): import pending files
- fix (DB/Creature) Edit Geirrvif's position. (#22531)
- chore(DB): import pending files
- fix (DB/Creature) Set right faction for Ice Steppe Rhinos. (#22530)
- chore(DB): import pending files
- fix (DB/Gameobject) Vordrassil Seeds now have a corrected spawn point. (#22527)
- chore(DB): import pending files
- fix (DB/Creature) Eyes Above quest issues are now solved. (#22513)

## 2025-07-21
- chore(DB): import pending files
- fix(Scripts/GrizzlyHills): Refactor Red Rocket quest to use SmartAI s… (#22517)
- chore(DB): import pending files
- fix(DB/Event): Scourge Invasion vendor conditions (#22519)

## 2025-07-20
- fix(Scripts/Ulduar): Phase 1 of Thorim (#22037)
- fix(Scripts/Spells): killing with Victory Rush grants Victory Rush (#22514)
- chore(DB): import pending files
- fix(DB/Custom): Stackable debuffs for wotlk dungeons/T7 raids (#22062)
- chore(DB): import pending files
- fix(DB/Custom): Stackable debuffs for wotlk T8 and up raids (#22105)
- chore(DB): import pending files
- fix(Scripts/Spells): Update Death Knight Ebon Gargoyle auras and damage, and Ghoul auras (#22398)

## 2025-07-19
- fix(Core/Metrics): InfluxDB v1 config check #22358 (#22479)

## 2025-07-20
- fix(Core/Authserver): HandleLogonProof query as async (#22510)

## 2025-07-19
- chore(DB): import pending files
- fix(DB/Event): Scourge Invasion creature_template, quest mail, loot (#22501)
- feat(DB): Release ACDB 13.0.0 (#22508)
- refactor(Core/PlayerSettings): Refactor Player settings handling for efficiency (#22494)
- refactor(Core/Misc): string handling and use smart pointer for strand (#22351)
- fix(Core/Player): Unlearn invalid spells for race/class on login (#22370)
- fix(Core/Creatures): Always update temp summons (#22484)

## 2025-07-18
- chore(DB): import pending files
- fix(DB/Spells): Update Killing Machine PPM rate (#22477)
- fix(Core/Player): implement Character flag `CHARACTER_FLAG_RESTING` (#22499)

## 2025-07-16
- fix(Scripts/AuchenaiCrypts): Remove debuff on summon death (#22461)
- fix(Script/ScarletEnclave) Acherus Soul Prisons now reset properly. (#22496)

## 2025-07-15
- chore(DB): import pending files
- fix(Scripts/Midsummer): improve torch tossing based on sniffs (#22378)
- Merge branch 'master' into Playerbot
- fix(Core/Config): align worldconfig default values to .conf.dist (#22475)
- chore(DB): import pending files
- fix(Core/Spells): Fixed explosive shot ammo consumption (#21501)
- fix(Scripts/Kalimdor): Fix hardcoded gossip in zone_felwood (#21931)

## 2025-07-14
- fix(Core/FleeingMovementGenerator): Prevent fleeing players from moving off cliffs (#22462)
- fix(Core/AI): prevent PetAI autocast leap to self and allies (#22472)
- chore(DB): import pending files
- fix (DB/Creature) Remove Blood Plague, Frost Fever etc... from various Scarlet Enclave npcs. (#22471)

## 2025-07-13
- fix (Script/Scarlet Enclave) Named Npcs can no longer be attacked after the end of the The Light of Dawn battle. (#22463)

## 2025-07-12
- chore(Core/Config): Finish removing config option. (#22464)

## 2025-07-13
- fix(Scripts/World): fix windows/mac build (#22465)

## 2025-07-12
- chore(DB): import pending files
- feat(Core/WorldState): init Scourge Invasion pre-wrath event (#22286)
- chore(DB): import pending files
- fix(Scripts/EasternKingdoms): Add quest requirement to Orbaz Bloodbane's Ebon Hold portal (#22443)

## 2025-07-11
- chore(CI): Corrected the name of workflow in action tab to be more clear. (#22459)
- fix(Core/FleeingMovementGenerator): Prevent fear movement from causing characters to fall through the ground (#22451)
- feat(Core/Maps): Improve map object updater (#22392)
- fix(Core/Group): incorrect parameter type in RegisterGroupId (#22448)
- feat(Codestyle/SQL): Ensure InnoDB is used as DB Engine (#22457)
- chore(DB): import pending files
- fix(DB/world_state): Update engine to InnoDB (#22456)
- fix(Core/Battlegrounds): Add Call to Arms bonus data to Alterac Valley and fix bonuses for other battlegrounds. (#21923)
- feat(Core): Add config for legacy arena team start rating. (#22080)
- fix(Core/Unit): Don't extend leash when taking self-inflicted damage. (#22449)

## 2025-07-10
- fix(Core/SharedDefines): Define creature static flags. (#22127)
- fix(Core/Opcodes): Crash fix (#22453)
- fix(Script/ScarletEnclave): Darion now have Corrupter Ashbringer on respawn. (#22452)
- fix(Core/LFG): revert #22360 (#22436)
- chore(DB): import pending files
- fix (DB/Creature) Ensure that Scarlet Npcs respawn without the NON_ATTACKABLE flag. (#22450)

## 2025-07-09
- chore(DB): import pending files
- fix (DB/Quest) Chapter V aura is now added to players when “The Light of Dawn” is delivered. (#22437)

## 2025-07-08
- chore(DB): import pending files
- fix(DB/CreatureFormations): Add formations to NPCs in the Magister's Terrace (#22440)
- feat(Core/Chat): Allow whispers to Game Masters regardless of sender … (#22417)
- chore(DB): import pending files
- fix(Scripts/ScarletEnclave): Refactor 'How to Win Friends' quest scri… (#22432)
- fix(Core/Spells): Glyph of Scourge Strike can prolong diseases that were reapplied (#22438)

## 2025-07-07
- chore(DB): import pending files
- fix (DB/Creature) The Eye of Acherus now removes the aura from the player on death. (#22428)

## 2025-07-06
- feat(tests): add BATS test parallel conf and integration tests for compiler module (#22421)
- feat: improve session management and PM2 support in startup scripts (#22420)

## 2025-07-05
- fix(bash): Improve session management and GDB handling in service scripts (#22418)
- BREAKINGCHANGE(Metrics): Support InfluxDB v2 (#22358)

## 2025-07-04
- Merge branch 'master' into Playerbot

## 2025-07-03
- fix(installer/windows): update OpenSSL version to 3.5.1 to fix gh build errors (#22416)
- chore(DB): import pending files
- fix(DB/SAI): Use Holy Fire spell for Draenei Anchorite (#22414)
- chore(DB): import pending files
- fix(DB/Autobroadcast): Update 'text' column in autobroadcast_locale t… (#22382)
- chore(DB): import pending files
- fix(DB/Quests) - Corrected the Reputation requirements for the Scryers and Aldor  (#22362)
- chore(DB): import pending files
- fix(DB/ArathiBasin): Replacement for previously lost tabards added and adjustements to quests (#22338)
- fix(Scripts/Spells): Don't proc Misdirection from Mend Pet's heal effect. (#22293)
- fix(Core/Unit): Add previously unreferenced DealDamage script hook in Unit (#22207)
- fix(Core/Spells): No longer add a signature to items created by NPCs (#22415)
- feat(Core/LFG): RDF CF (#22360)
- fix(CI): update build job to support multiple Ubuntu versions (#22413)
- chore(DB): import pending files
- fix(DB/SAI) - Corrects Corpse.Decay for Patchwerk from the end of the Death Knight zone (#22412)

## 2025-07-02
- chore(DB): import pending files
- fix(DB/SAI: Fix Archerus Deathcharger not despawning if players move … (#22411)
- chore(DB): import pending files
- fix (DB/Creature) Tirion doesn't get back on his horse anymore during The Light of Dawn event. (#22406)

## 2025-07-01
- fix(Core/Reputation): Remove `At War` flag when rising above hated reputation. (#22386)
- chore(DB): import pending files
- fix (DB/Creature) A couple of simple SmartAI corrections for Scarlet Ghouls and Scourge Gryphons. (#22405)
- chore(DB): import pending files
- fix (DB/Creature) Elite npcs no longer die during The Light of Dawn battle. (#22402)
- chore(DB): import pending files
- fix (DB/Creature/Scarlet Enclave) Implement Ghouls and Gryphon spawn and behaviour. (#22348)
- feat(bash): startup-scripts reworked + bash scripts workflow  integration (#22401)
- chore(DB): import pending files
- fix(Scripts/ScarletEnclave): Correct Tirion spawn position in Light o… (#22394)

## 2025-06-30
- refactor(Scripts/Pet): Death Knight use creature register macros (#22399)
- feat(Core/Config): Improvements to config caching (#21647)
- chore(DB): import pending files
- feat(Core/Command): add GM spectator to allow cross-faction `/follow` (#22393)

## 2025-06-29
- chore(DB): import pending files
- fix(Core/Spells): Fix SPELL_EFFECT_LEAP_BACK not working on targeted … (#22389)
- chore(DB): import pending files
- feat(Scripts/Commands): Add guild ranks display to guild info command (#22380)
- fix(Scripts/Spells): Death Knight Bone shield charges now have a 2 second delay between uses. (#22340)
- chore(DB): import pending files
- fix(DB/Creature): Make Captured Raptor immune to player characters. (#22387)
- chore(DB): import pending files
- fix(Scripts/Spells): add script to GM spell CooldownAll (#22383)
- Merge branch 'master' into Playerbot

## 2025-06-28
- refactor(db-scripts): replace PowerShell database tools with Bash scripts and update documentation (#22372)
- fix(Core/Player): Mutilate + Cold Blood crit fix (#22308)
- fix(CI/Codestyle): Add directory check to SQL codestyle script (#22376)
- chore(DB): import pending files
- fix(DB/Creature): Remove respawn time from the smartAI of some npc's in the scarlet enclave. (#22375)
- Merge branch 'master' into Playerbot

## 2025-06-27
- fix (Core/SmartScript) Improve SMART_ACTION_START_CLOSEST_WAYPOINT. (#22364)
- chore(DB): import pending files
- feat(Script/Commands): allow to pass email in account create (#22310)
- fix(Player/Skills): Improve skill validation and logging in Player::_… (#22369)
- refactor(Core/Scripting): Forward-declare AuctionEntry as a struct rather than a class. (#22282)
- chore(DB): import pending files
- feature(Scripts/Commands) choose Xth spawn of entry for go creature/gameobject id (#22363)
- chore(DB): import pending files

## 2025-06-26
- fix(DB/Creature): Bound Air, Fire and Water Elemental damage and immu… (#22300)
- fix(Script/SWP): unify events that interact with Anveena in P5 Kil'Jaeden (#22366)
- fix(CORE/SAI): Properly Implement START_CLOSEST_WAYPOINT (#22256)

## 2025-06-24
- refactor(Core/AI): rename FarthestTargetSelector to RangeSelector (#22026)
- fix(Core/Movement): Use attack speed for leash reset period and only extend timer if in melee range or can't move freely. (#22350)
- fix(Core/AI): crashfix(#22352) (#22353)

## 2025-06-23
- fix(Core/Grids): Crash fix (#22347)
- fix(Core/Spell): implement SPELL_ATTR5_NOT_ON_PLAYER and SPELL_ATTR5_NOT_ON_PLAYER_CONTROLLED_NPC (#22332)
- fix(Core/SAI): Exclude GMs for player target/event (#22345)

## 2025-06-22
- fix (Core) update comments on unused SpellAttributes (#22343)
- fix(Scripts/Spell): snapshot %dmg and crit when spreading or refreshing diseases with pestilence (#22306)

## 2025-06-21
- chore(DB): import pending files
- fix (DB/Script/Scarlet Enclave) Corrects some spell timers and adds a new spell for Darion Mograine. (#22324)
- chore(DB): import pending files
- fix(Scripts/ScarletEnclave): City guards should throw stuff at new DKs (#22317)
- chore(DB): import pending files
- fix(Scripts/ScarletEnclave): Rewrite Brothers in Death (#22303)
- chore(DB): import pending files
- fix(DB/Condition): Deliver Stolen Horse only works near Salanar. (#22341)

## 2025-06-20
- feat(Core/Utilities): add `Seconds` overload for `randtime` (#22337)

## 2025-06-18
- fix(Core/PlayerTaxi): prevent pop_front crash (#22292)
- chore(DB): import pending files
- fix(Scripts/ZulDrak): Fix Ghymer not being healed by storm clouds (#22302)

## 2025-06-17
- chore(vscode): update extensions, settings, tasks (#22200)
- chore(DB): import pending files
- fix(DB/Creature) add CC immunities to the Fel Crystals in the Selin Fireheart encounter (#22304)
- fix(core/SMART_EVENT_LINK) - Seperation and clarification of "not found or invalid, skipped" (#22240)
- chore(DB): import pending files
- fix(Scripts/HoL): Ionar's Static Overload missing knockback (#22049)
- chore(DB): import pending files
- fix(DB): set game_event_* tables to use smallint (#22309)
- chore(DB): import pending files
- fix(DB/Creature): Molten War Golem - Added immunities (#22315)
- fix(bash): repository initialization bugs and update configurations (#22311)

## 2025-06-16
- chore(DB): import pending files
- fix(Scripts/Items): Bloodsail Admiral's hat should despawn parrot on … (#22327)

## 2025-06-15
- chore(DB): import pending files
- fix(DB/Gameobject): Correct Area 52 Mailbox faction. (#22319)
- chore(DB): import pending files
- fix(Scripts/ScarletEnclave): Improve Might of Mograine aura behavior. (#22320)
- chore(DB): import pending files
- fix(DB/Loot) - Archimonde now properly drops the Helms (#22322)
- 
## 2025-06-14
- Merge branch 'master' into Playerbot

## 2025-06-13
- fix(Scripts/AhnKahet): Fix Taldaram Spheres duration, spawn position … (#22296)

## 2025-06-12
- chore(DB): import pending files
- fix(DB/SAI/Scripts) [Sholazar Basin] Quest: A Hero's Burden -- Behavior of all NPCs (#22278)
- chore(DB): import pending files
- fix(DB/SAI): Fix Eye of Taldaram not casting Shadowfury on death (#22297)
- chore(DB): import pending files
- fix(DB/SAI): Fix Bonegrinder not casting Frightening Shout (#22299)
- chore(DB): import pending files
- fix(DB/Creature): Herald Volaj despawn on evade (#22295)
- fix(DB/SAI): Savage Cave Beast should enrage every 30-35s (#22294)

## 2025-06-11
- fix(Scripts/UtgardePinnacle): Svala Sorrowgrave should not be unattac… (#22298)

## 2025-06-10
- fix(Core/Spells): Fix Element 115 Perpetual Instability not preventin… (#22301)
- fix(Core/Spell): Halve healing threat generated by paladins (#22271)

## 2025-06-09
- fix(Core/Unit): use casttime for ppm calculation of spells (#22019)
- refactor(Scripts/SunwellPlateau): use existing functions for Dark Fiend target search (#22025)
- chore(DB): import pending files
- fix(DB/SAI): Leaping Hatchling pet is not leaping around (#22287)

## 2025-06-08
- chore(DB): import pending files
- fix(DB): Correct an area trigger teleport entry. (#22290)
- chore(DB): import pending files
- Quest - Imprisoned in the Citadel -  Can now be completed. (#22231)
- fix(DB/areatrigger_teleport) - Multiple updated areatriggers. (#22190)
- chore(DB): import pending files
- fix(DB/CreatureLoot) Fix loot table for Archimonde (#21785)
- chore(DB): import pending files

## 2025-06-07
- fix(DB): Significantly increase opcode limit for guild member note opcodes. (#22258)

## 2025-06-08
- chore(DB): import pending files

## 2025-06-07
- fix(Core/Scripting): `UnitScript::DealDamage` always returns the original damage value (#22206)

## 2025-06-08
- fix(DB/Quest) Added/Fix missing russian quest locale and fix wrong russian locale. #3 (#22277)
- fix(DB/creature_loot) - Durar's and Kathorn's Power Cell corrected drop rate to 100% (#22203)

## 2025-06-07
- fix(Core/SAI): Don't try to reposition SMC creatures while moving (fi… (#22280)
- fix(Core/Spells): channels no longer update player server-side orientation (#22138)
- refactor(Core/Channel): Cast moderation level to account types and avoid boolean evaluation. (#22283)
- fix(Conf/Logs): Change Errors.log to overwrite (#22151)
- chore(DB): import pending files
- fix(DB/Command): update `wchange` help (#22281)
- refactor(Core/Spells): Remove effectively unused switch case. (#22284)

## 2025-06-06
- chore(DB): import pending files
- fix(Quest/DB) - Removed the prequesite for Observing the Sporelings (#22004)
- fix(DB/Quest) - "Fine Gold Thread" is now repeatable (#22146)

## 2025-06-05
- refactor(Core/Player): revert equip item aura duration core fix with a spell correction (#22167)
- fix(Scripts/UP): King Ymiron should use only 1 boat ability at a time & Spirit Fount speed (#22081)
- chore(DB): import pending files
- refactor(Core): Make use of standard config usage for guild member limit option. (#22259)
- fix(Core/Creature): Use minimum template level instead of current level for leash timer. (#22250)
- fix(Core/Spells): simplify and fix Blood-Caked Strike calculation (#22243)
- chore(Core): Remove unused and inaccurate comment headers for various script-related files. (#22263)
- fix(DB/Misc): Gundrak formations and SAI (#22107)
- chore(Core/Guild): Adjust variable declaration name to match usage. (#22257)
- fix(Core/Spells): weapon damage based magic abilities gain too much effect from spell aura % damage increase (#22232)
- fix(Core/Spell): Revert paladin seal hackfixes (#22264)
- chore(DB): import pending files
- fix(DB/Creature): Remove extra Shaffar adds (#22255)
- chore(DB): import pending files
- fix(Scripts/ScarletEnclave): Death Knight Initiates now despawn when defeated. (#22268)
- chore(DB): import pending files
- fix(Core/LFG): Lock Deathknights from the dungeonfinder until they complete their starting zone (#22270)

## 2025-06-03
- chore(Core/Unit): Correct typo of `Controlled`. (#22260)

## 2025-06-01
- fix(Scripts/AhnKahet): Modernize Amanitar script (#22254)

## 2025-05-31
- chore(DB): import pending files
- fix (DB/Script) Move Eye of Acherus event to SmartAI. (#22249)
- chore(DB): import pending files
- fix(Scripts/SunwellPlateau): Eredar Twins blaze trap delay (#22253)

## 2025-05-30
- chore(DB): import pending files
- fix(DB/Creature) Edit Sinister Reflection spell timers. (#22233)
- chore(DB): import pending files
- feat(Scripts/Commands): Add group revive command (#22204)
- chore(DB): import pending files
- fix(Scripts/Oculus): Varos Cloudstrider does not summon Azure Ring Captain (#22198)
- chore(DB): import pending files
- feat(Scripts/Commands): `.debug boundary` to visualize `CreatureBoundary`  (#22099)
- chore(DB): import pending files
- fix(Scripts/AhnKahet): Ahn'kahar Spell Flinger failing to channel S… (#22082)
- chore(DB): import pending files
- fix(Scripts/Items): Noblegarden Chocolate instantly giving Well Fed buff (#22150)
- fix(Core/Creature): Use home position for leash distance check for creatures with no movement. (#22245)
- chore(DB): import pending files
- fix(Scripts/VioletHold): Sinclari gossip order, crystals being spamma… (#22195)
- fix(Scripts/TheEye): Al'ar don't attack other players if the onlyone tank died (#22118)
- chore(DB): import pending files
- fix(Scripts/Karazhan): Script Wrath of the Titans (#22165)
- fix(Scripts/AhnKahet): Amanitar shouldn't be immune to nature damage (#22244)
- chore(DB): import pending files
- fix(DB/Creature): Remove Set_Active from some creatures in dk starting area. (#22234)
- fix(Scripts/AhnKahet): Elder Nadox enrage & health check (#22208)

## 2025-05-29
- chore(DB): import pending files
- fix(DB/Creature): Jedoga Shadowseeker should be disarmable and hard r… (#22215)
- chore(DB): import pending files
- fix(DB/SAI) - SAI for NPCs related to ETC event to no longer display errors. (#22222)

## 2025-05-27
- fix(Scripts/SunwellPlateau): Don't inflict Darkness damage if Darkness aura is removed by death. (#22223)
- chore(DB): import pending files
- fix(DB/Command) - Updates the "guild rank" command to be more clear. (#22186)
- chore(DB): import pending files
- refactor(Core): Use database tables for Shaman totems and Druid shapeshift forms. (#22104)
- chore(DB): import pending files
- fix(DB/SAI): Portal Keepers now uses the correct Arcane Missiles spell (#22209)

## 2025-05-26
- chore(DB): import pending files
- fix(Scripts/ScarletEnclave): Script Recall Eye of Acherus & fix Summo… (#22205)

## 2025-05-24
- fix(Core/Spells): Siphon Bloodgem now channels no matter the player's orientation. (#22143)
- fix(Scripts/SWP): Breath: Haste now removes impairing auras (#22192)
- chore(DB): import pending files
- fix(Scripts/Spells): - Weapon Coating Enchant (#22060)
- chore(DB): import pending files
- fix(Scripts/ScarletEnclave): Devour Humanoid castable without target … (#22196)
- fix(Scripts/SunwellPlateau): crash in Sinister Reflection Clone spellscript (#22201)
- chore(DB): import pending files
- fix(DB/Spells): Shield of the Blue output damage reduction (#22191)

## 2025-05-23
- chore(DB): import pending files
- fix(DB/Creature): Warp Storm doesn't do anything (#22144)
- chore(DB): import pending files
- fix(DB/Creature): Captured Totem shouldn't be attackable (#22142)
- chore(DB): import pending files
- Fix(DB/Spells): Hallows End candies should not give Well Fed buff. (#22141)
- chore(DB): import pending files
- fix(Scripts/Northrend): Crashing wave should do double damage to frozen … (#22057)
- fix(Scripts/OldKingdom): Jedoga Shadowseeker boundary (#22084)
- fix(Scripts/Spells): re-add startDelay for some traps (#22102)
- refactor(Core/Worldstate): Remove redundant worldstate usage. (#22126)
- fix(Core/Creature): Leashing improvements. (#22129)
- chore(DB): import pending files
- Update 2 mobs with broken damage (#22149)
- Worldserver conf table reference correction (#22177)
- chore(DB): import pending files
- fix (DB/Creature) Improve Citizen of Havenshire SmartAI. (#22185)
- fix(DB/Creature) Configure Set_Active on various npcs in dk starting area. (#22175)
- Merge branch 'master' into Playerbot

## 2025-05-22
- chore(DB): import pending files
- fix (DB/Creature) Kil'Jaeden Sinister Reflections now have 3 seconds of delay before attacking. (#22162)

## 2025-05-21
- chore(DB): import pending files
- fix(DB/SAI): Correct Fireball spell ID used by Wyrmcult Scouts and Zealots. (#22147)

## 2025-05-22
- fix(Core/Player): aura removal logic to equipped "Use" items (#22164)

## 2025-05-21
- chore(DB): import pending files
- fix(DB/Spells): Shadow Bolt Volley of Hand of Deceivers on the Kil'jaeden fight stack (#22156)

## 2025-05-20
- chore(DB): import pending files
- fix(DB/Loot): Adjust Thori'dal drop chance. (#22124)

## 2025-05-19
- docs(AUTHORS): add Cross-project Collaboration section (#22034)
- chore(DB): import pending files
- fix(DB/Loot) - Dalaran Wizard's Robe no longer drops from un-wanted creatures. (#22091)

## 2025-05-18
- chore(DB): import pending files
- fix(DB/SAI) - Removes Link in Smart AI for creature Ziggurat Defender (#22137)
- fix(Scripts/Zone): Quest 'Fire At Will!' should give group credit (#22145)

## 2025-05-17
- fix(Scripts/SunwellPlateau): Fix Killjaeden text spam (#22139)
- fix(Scripts/Spells): Kil'Jaeden Fire Bloom AoE pet damage (#22133)

## 2025-05-16
- Merge branch 'master' into Playerbot

## 2025-05-15
- chore(DB): import pending files
- fix(Scripts/SunwellPlateau): Spell Fury spellsteal resets stacks and is no longer consumes on dot ticks (#22125)
- feat(apps/extractor): add extractor for non windows (#22123)

## 2025-05-13
- chore(DB): import pending files
- fix(DB/Creature): Correct Kil'jaeden's model info. (#22120)
- fixup! refactor(Core/World): Move various worldstate related function… (#22119)
- fix(Scripts/SunwellPlateau): Fix flame dart timers and cast in all ph… (#22113)

## 2025-05-12
- chore(DB): import pending files
- fix(DB/Creature) Scarlet Crusaders don't hook invisible Eye of Acherus anymore (phase 2). (#22106)
- fix (Script/Sunwell Plateau) Edit Kil'Jaeden Darkness Timers. (#22115)
- chore(DB): import pending files
- fix(DB/Creature): Add Taunt Immunity to Kil'Jaeden. (#22114)

## 2025-05-10
- fix(Scripts): Use distinct sound entry for BRD L70ETC Music Doodad. (#22029)
- chore(DB): import pending files
- fix(DB/Commands) Corrected syntax for "help server exit" and "help reload config". (#22100)
- chore(DB): import pending files
- fix(Core/Spells) reimplement SPELL_ATTR3_CAN_PROC_FROM_PROCS (#22072)
- fix(Spells/Paladin) remove custom cooldown and procFlags from Judgement of Wisdom/Light (#22018)
- chore(DB): import pending files
- fix(Scripts/Paladin): Add cast check to Hand of Protection for casting spell on non-self targets. (#22077)
- chore(DB): import pending files
- fix(DB/Conditions): 'Opening the Backdoor' pre-quests (#22097)
- fix(Scripts/Desolace): Kodo Roundup (#22052)
- fix (Script/SunwellPlateau): Edit some Kil'jaeden dialogue and spells' timers. (#22093)
- chore(DB): import pending files
- fix(DB/Loot) - Lorgalis Manuscript no longer drops from creatures. (#22092)

## 2025-05-09
- Merge branch 'master' into Playerbot
- refactor(Core): Add definition file for area table entries. (#22054)
- chore(DB): import pending files
- fix(DB/Creature): Ahn'kahar Watcher will no longer spawn in normal mode. (#22083)
- chore(DB): import pending files
- refactor(Core/World): Move various worldstate related functions to worldstate class. (#22086)
- fix(DB/Creature): Remove Wrath Enforcer damage requirement (#22065)
- fix(Core/Spells): Heart of the Crusader (#22070)

## 2025-05-07
- fix(Scripts/SunwellPlateau): Ensure Kil'jaeden encounter resets correctly on evade (#22006)
- fix(Scripts/SunwellPlateau): Kiljaeden shouldnt interrupt Darkness of… (#21982)

## 2025-05-06
- Revert "fix(Core/Spells): Allow glyphed PS to be casted while Seduced… (#22067)

## 2025-05-05
- chore(DB): import pending files
- fix(DB/Creature) Havenshire Horses now have a blizz-like behaviour when dismounted or die. (#22059)
- fix(Core/Spells): Allow glyphed PS to be casted while Seduced (#22047)
- refactor(Core/AI) don't add currentTarget to the front of the SelectTargetList for MaxThreat/Random (#21965)

## 2025-05-04
- chore(DB): import pending files

## 2025-05-05
- fix(DB/Conditions): Quest 'Harp on This!' not allowing interaction wi… (#22051)
- fix(DB/Conditions): Gather Lumber not despawning Coldwind Tree GOs (#22050)

## 2025-05-04
- chore(DB): import pending files

## 2025-05-05
- fix(DB/Custom): UP Avenging Spirit's Wither should stack from multip… (#22056)
- fix(Scripts/CoS): First trio transforming on low HP (#22055)

## 2025-05-04
- chore(DB): import pending files
- fix(DB/Formations): Naxxramas - Embalming Slime (#22046)
- fix(Core/Player): smooth energy regeneration with `SPELL_AURA_MOD_POWER_REGEN_PERCENT` mods (#22041)
- chore(DB): import pending files
- fix(DB/GameObject): place Alchemy Lab on the Alchemy Table (#22045)

## 2025-05-03
- chore(DB): import pending files
- fix(DB/Spells) Thunderfury does not stack with Infected Wounds/Thunderclap/Icy Touch anymore (#22035)
- refactor(Scripts/BlackTemple) remove tanks from Fatal Attraction after setting the target amount (#22038)

## 2025-05-02
- Merge branch 'master' into Playerbot

## 2025-05-01
- chore(DB): import pending files
- fix (DB/Creature) The Horses' pack and the single horse now have a path and jump the fence. (#22033)
- Revert "Fix(Core/Player): Energy regen rate bonuses (#20321)" (#22032)

## 2025-04-30
- chore(DB): import pending files
- chore(Core/Spells): move db `spell_dbc` corrections to SpellInfoCorre… (#21819)

## 2025-04-29
- fix(Scripts/SunwellPlateau): Ensure proper reset for Kil'jaeden encounter (#22024)
- fix(Scripts/SunwellPlateau): Dark Fiends should use threat table and not deal melee damage (#21991)
- fix(Core/Creature): Implement respond to call for help faction flag. (#21959)

## 2025-04-30
- fix(Script/Spell) exclude original target from glyph of holy light (#22002)
- fix(Core/Player): correct SpellPriority logic  (#21052)
- chore(DB): import pending files
- fix(DB/Spells) add K'iru's Song of Victory to Intellect and Stamina aura stack groups (#22022)
- chore(DB): import pending files
- fix(DB/Spells) add Battle Squawk to Melee Haste aura stack group (#22021)
- chore(DB): import pending files
- fix(db/locale): Added missing Russian translation for the (Shaman) Totems (#22012)
- chore(DB): import pending files
- fix(Scripts/SunwellPlateau): exclude tank from flame sear (#22014)

## 2025-04-29
- chore(DB): import pending files
- fix(DB/Creature) Solve a wrong SmartAI update in my previous PR. (#22020)
- chore(DB): import pending files
- fix(DB/Creature) Solve various issues on dk starting area (phase 4). (#22017)
- fix(Core/worldserver.conf) Clarification for AllowTwoSide.Interaction.Auction (#22013)

## 2025-04-27
- fix(Scripts/SunwellPlateau): Make Twin special abilities target one of the highest 6 in threat of the other twin (#21964)

## 2025-04-26
- chore(DB): import pending files
- fix (DB/Creature) Citizen of New Avalon inside Scarlet Tavern now remain dead. (#21996)
- fix(deps/PackageList.txt): update for current state of dependencies (#21968)
- fix(Core/Player) internally handle expertise as float (#21967)
- fix (Script/Gruul) Kiggler polymorph targets his tank (#21966)
- refactor(Core/WorldState): Initial addition of world state definition file. (#21875)
- fix(SmartAI): Ensure immediate combat engagement (#21854)
- chore(Core/Auth): align mysql ping log level and name to worldserver (#21986)

## 2025-04-25
- chore(DB): import pending files
- fix(Scripts/SunwellPlateau): Make Blue Dragon Breath Haste apply 25% haste effect (#21984)
- fix(Scripts/SunwellPlateau): Make Kil'jaeden's Sinister Reflections clone the same player (#21949)
- chore(DB): import pending files
- fix(DB/SAI): Despawn Mu'ru Void Spawns on evade (#21989)

## 2025-04-24
- fix (Script/SWP) use enrage function for brutallus enrage (#21987)
- fix(Scripts/SunwellPlateau): Fix Entropius wrong spell ID and timers (#21970)
- fix(Core/Maps): Do not allow entering an instance if the player is (#21973)

## 2025-04-23
- fix(Script/Sunwell): Use raycast to prevent Singularity throwing players through walls (#21928)

## 2025-04-21
- chore(Deps/Zlib): Upgrade zlib to 1.3.1 (#21940)
- fix(Core/AI): Ignore PvP flagged players for aggressive pets if owner is not PvP flagged. (#21922)

## 2025-04-20
- chore(DB): import pending files
- fix(DB): Add and correct arena season rewards. (#21960)
- chore(DB): import pending files
- fix(DB/Loot): Consolidate Sunwell trash recipe drops into one reference table and update chance. (#21962)
- fix(Core/Spells): Suppress Crystal Spire of Karabor procs (#21961)

## 2025-04-19
- fix(Deps/Boost): Fix build for boost 1.88. (#21952)
- chore(DB): import pending files
- fix(Scripts/Noblegarden): fix bunny transformation on egg looting (#21957)
- fix(Scripts/SunwellPlateau): Correct Felmyst landing pos variable names (#21954)

## 2025-04-18
- fix(Battlefield/WG): set default maxplayer 120, minlevel 75 (#21937)
- Merge branch 'master' into Playerbot

## 2025-04-17
- fix(Core/AutobroadcastMgr): correctly check for existing textId in SendWorldAnnouncement (#21911)
- fix(Scripts/SunwellPlateau): Fix Alythess not casting Flame Sear in p… (#21948)
- chore(DB): import pending files
- fix(DB/Creature): Some SwP packs are now in formation. (#21951)
- chore(DB): import pending files
- fix(Scripts/SunwellPlateau): Void Sentinels spawn at floor level (#21946)
- fix(Core/Scripts): Fix heap-use-after-free in Fingers of Frost proc handler (#21943)

## 2025-04-16
- fix(Scripts/SunwellPlateau): Limit Kil'jaeden's Armageddon ability (#21932)
- fix(Script/Sunwell): M'uru height check (#21942)

## 2025-04-15
- chore(DB): import pending files
- fix(Script/Sunwell): Adjust Singularity behaviors (#21919)
- chore(DB): import pending files
- fix(DB/Quest) Return to Thrallmar has proper prerequisite quest Mission: Gateways Murketh and Shaadraz (#21856)

## 2025-04-14
- chore(DB): import pending files
- fix(Scripts/SunwellPlateau): Move Dark Fiend from SmartAI to ScriptedAI with corrected despawn behavior (#21910)
- fix(Scripts/Creature): Crash for npc_captured_beryl_sorcerer by secur… (#21889)

## 2025-04-13
- chore(DB): import pending files
- fix(DB/Creature): Remove unnecessary Netherwing targetting dummy creatures. (#21867)
- chore(DB): import pending files
- fix(Scripts/SunwellPlateau): Add taunt immunity to Entropius (#21918)
- chore(DB): import pending files
- fix(DB/Creature): Add model data for Entropius display. (#21920)
- chore(DB): import pending files
- fix(DB/Creature) Add Verified Build. (#21915)
- fix(Scripts/SunwellPlateau): Entropius' darkness spawn height (#21914)
- chore(DB): import pending files
- fix(DB/Creature) Locate more Death Knight Initiates on their sniffed spawn points. (#21912)

## 2025-04-12
- fix(Scripts/SunwellPlateau): Prevent spell casting if nearing air phase (#21873)
- chore(DB): import pending files
- fix(Core/Player): Force UpdateZone on resurrect to apply Zone auras (#21888)
- fix(DB/Creature): Implement Crusader assaults during the dk chain quest (phase 64). (#21881)
- fix(Scripts/SunwellPlateau): Correct timing for Eredar Twins (#21894)
- chore(DB): import pending files
- fix(Scripts/SunwellPlateau): Add Blink with Nove Arch Mage (#21904)
- Fix(Script) Remove a Trailing whitespace from brutallus script. (#21909)
- fix(Scripts/SunwellPlateau): Set Brutallus corpse despawn timer to 3 minutes (#21896)
- fix(Script/SunwellPlateau): Kil'jaeden now has a more offy-like last phase. (#21907)

## 2025-04-11
- chore(DB): import pending files
- fix(DB/Creature): Add Shadow Bolt Volley to Void Spawn's spells (#21898)
- chore(DB): import pending files
- fix(DB/SpellCustomAttr): make Spell Fury spellstealable (#21897)
- fix(Scripts/SunwellPlateau): Correct Singularity behavior in Entropius encounter (#21892)

## 2025-04-10
- chore(DB): import pending files
- fix(DB/Creature): Hand of the Deceiver is no longer immune to silence and stun. (#21890)
- chore(DB): import pending files
- fix (db/Conditions) -  Kael'thas Sunstrider's Heroic loot ref will drop the correct recipes to their respective proffesion. (#21884)

## 2025-04-09
- Merge branch 'master' into Playerbot
- fix(Scripts/BlackTemple): Shahraz Fatal Attraction number of targets can be fewer than 3 (#21859)
- fix(Scripts/BlackTemple): Shahraz Fatal Attraction Teleport (#21858)
- chore(DB): import pending files
- fix(DB/Loot) Add gold drop, Netherweave Cloth and a drop chance for Gan'arg Analyzer. (#21883)

## 2025-04-08
- feat(Core/World) add an error message when closing due to not finding the starting area map files (#21879)
- chore(DB): import pending files
- fix(DB/Creature) Solve some npc issues on DK starting area (Phase 64). (#21848)

## 2025-04-07
- fix(Scripts/SunwellPlateau): Felmyst should choose the closest side (#21865)

## 2025-04-05
- chore(DB): import pending files

## 2025-04-06
- fix(DB/CreatureAddon): Remove `auras` Sunwell Radiance (#21857)

## 2025-04-05
- chore(DB): import pending files
- fix(DB/GossipMenuOption): Swap Exarch Nasuun Anvil and Harbor progress (#21864)

## 2025-04-04
- chore(DB): import pending files
- fix(Scripts/SunwellPlateau): Fix Darkness spawning midair (#21851)

## 2025-04-03
- chore(DB): import pending files
- fix(DB/SpellCooldownOverrides): remove overrides of player spells (#21850)
- fix(Script/ZulAmen) Hexlord now has fallback behavior as warrior (#21829)

## 2025-04-02
- fix(Scripts/Commands): Fix crash in unstuck command (#21846)
- chore(DB): import pending files
- fix(Scripts/SunwellPlateau): Add Moorba's teleporter gossip (#21845)
- chore(DB): import pending files
- fix(DB/SpellCooldownOverrides): remove overrides of player spells (#21844)
- chore(DB): import pending files
- fix(Scripts/ZulAman): Add Beast Tamer missing abilities (#21821)
- chore(DB): import pending files
- fix(DB/Conditions) Requires Spirit Calling Aura to loot Lesser Nether Drake Spirit (QuestID: 10853) (#21841)
- chore(DB): import pending files
- fix(DB/Creature) Citizen of New Avalon now have a more blizzlike behaviour. (#21842)

## 2025-04-01
- chore(DB): import pending files
- fix(DB/Creature) Shadow Image now only use one ability at a time.  (#21834)
- chore(DB): import pending files
- fix(DB/SpellCooldownOverrides): Add Data from SmartAI timers (#21830)
- chore(DB): import pending files
- fix(DB/Creature) Reduce Dark Fiend range to explode. (#21840)
- chore(DB): import pending files
- fix(DB/Creature) Add various immunities to Void Sentinel, Berserkers and Fury Mages. (#21839)
- chore(DB): import pending files
- Added/Corrected missing russian quest locale and fix wrong russian locale. #2 (#21837)
- chore(DB): import pending files
- fix(DB/Creature) Solve some Dark Fiend's behaviour. (#21818)
- fix(Script/Sunwell) Solve some Eredar Twins' timer issues. (#21835)
- chore(DB): import pending files

## 2025-03-31
- fix(DB/Quest) Gammerita, Mon! Now has no quest requirement (#21833)

## 2025-04-01
- chore(DB): import pending files
- fix(DB/Creature): set Charm immune (`mechanic_immune_mask`) for SWP Trash demons  (#21826)

## 2025-03-31
- chore(DB): import pending files

## 2025-04-01
- fix(DB/Creature) fix Bannok Grimaxe's Axe Toss has a missing model (#21780)

## 2025-03-31
- chore(DB): import pending files

## 2025-04-01
- Fix(DB/Loot) Remove Sunglow Vest from Eredar Twins loot. (#21831)

## 2025-03-31
- chore(DB): import pending files
- fix(DB/Quest) Added missing russian quest locale and fix wrong russian locale. #1 (#21758)
- fix(Warden) Warden Anti-Cheat Timing Attack Protection MAC (#21824)
- fix(Warden) Warden Anti-Cheat Timing Attack Protection WINDOWS (#21823)
- chore(DB): import pending files
- fix(DB/Creature) Locate some Death Knight Initiates on their sniffed spawn points. (#21825)
- fix(Scripts/SunwellPlateau): M'uru should be passive (#21822)

## 2025-03-30
- chore(DB): import pending files
- fix(db/CreatureLoot) - Removal of "Rod of Lianthe" and "Nightmare Vine" from "Eclipsion Hawkstrider"'s Loot (#21816)
- chore(DB): import pending files
- fix(DB/Creature) Remove Immune to Distract Flag on M'uru. (#21815)
- chore(DB): import pending files
- fix(DB/Creatures) Fix various issues on DK starting area (phase 1 and 64). (#21814)
- Fix(Core/Wintergrasp): Retrieve the missing Tower Cannon (#21752)

## 2025-03-29
- fix(Script/Sunwell) Edit Felmyst timers and move emote in the right spell cast.  (#21809)
- chore(DB): import pending files
- fix(DB/Creature) Southshore Assassins now despawn when OOC for 30 seconds. (#21757)
- fix(DB/Creature) Remove Random in Radius and edit orientation for some Scarlet Peasants. (#21797)
- Merge branch 'master' into Playerbot
- chore(DB): import pending files
- (db/Creautre) - Adds Heroic version of Brann Bronzebeard to Halls of Stone (#21755)

## 2025-03-28
- chore(DB): import pending files
- fix(DB/Condition) Scarlet Cannons now require Massacre at Light’s Point to be used. (#21796)
- fix(Core/Spells): implement `SPELL_ATTR7_TREAT_AS_NPC_AOE` (#21787)

## 2025-03-27
- chore(DB): import pending files
- fix(DB/Creature) Set Kirtonos the Herald to level 60 (#21784)
- chore(DB): import pending files
- fix(DB/SunwellPlateau) M'uru should Hard Reset. (#21791)

## 2025-03-26
- fix(Scripts/SunwellPlateau): Update twin timers and Flame Sear target… (#21777)

## 2025-03-25
- chore(DB): import pending files
- fix(DB/SmartScript) Alumeth the Ascended will now repeat cast Psychicscream around 20 seconds (#21772)
- fix(Scripts/SunwellPlateau): Fix Alythess chasing players after casting (#21773)
- chore(DB): import pending files
- fix(DB/Creature) Eredar Twins should be immune to taunt. (#21770)

## 2025-03-24
- chore(DB): import pending files
- fix(Scripts/SunwellPlateau): Remove despawn on evade flag from KJ and… (#21753)

## 2025-03-22
- chore(DB): import pending files
- fix(DB/Creature) Dark Fiends now despawn when dispelled. (#21749)
- fix(Scripts/SunwellPlateau): Fix twin emotes in phase 2 (#21751)
- chore(DB): import pending files
- fix(Creature/Formations) Volatile Fiend Packs now are in formation. (#21750)
- fix(Scripts/SunwellPlateau): M'Uru ability DARKNESS now spawns dispellable skulls (#21747)
- chore(DB): import pending files
- fix(Scripts/SunwellPlateau): Felmyst Strafe strafe spells (#21745)
- fix(Scripts/SunwellPlateau): Implement twins boundary wipe mechanic (#21746)
- Merge branch 'master' into Playerbot

## 2025-03-21
- fix(Scripts/Nexus): Magus Telestra death (#21744)
- chore(DB): import pending files
- fix(DB/Gameobject): Sniffed Values for 'SWP / MGT' spawns (#21699)
- fix(Scripts/SunwellPlateau): Vapor should chase the player targeted b… (#21740)

## 2025-03-20
- fix(Script/Boss) Decrease Kalecgos human form spawn timer. (#21738)

## 2025-03-19
- chore(DB): import pending files
- fix(DB/Creature) Add formation for the the last pack before Kalecgos. (#21735)
- fix(Core/Spell): Prevent Blink from causing character to fall through ground (#21537)
- fix(Scripts/SunwellPlateau): Increase delay before choosing lane and … (#21733)
- chore(DB): import pending files
- fix(Scripts/SunwellPlateau): Sathrovarr's Curse of Boundless Agony (#21730)

## 2025-03-18
- fix(Scripts/Outland): add missing `return` if no target is found (#21731)

## 2025-03-17
- chore(DB): import pending files
- fix(DB/POI): update poi for Anthion's Old Friend quest with sniffed data (#20980)
- chore(DB): import pending files
- fix(Scripts/Zuldrak) Npc: Blightguard; Spell: Scourge Disguise and related things (#21536)
- fix(Scripts/AzjolNerub): Boss Herald Volazj - Insanity spell cast (#21287)
- chore(DB): import pending files
- fix(DB/FISHING): Fix "Disarmed!" fishing quest (#21310)
- chore(DB): import pending files
- fix(Scripts/Spells): add warrior heroic strike daze bonus damage (#21650)

## 2025-03-16
- chore(DB): import pending files
- fix(DB/Quest): Fixes missing prerequisite quest for "Pushed Too Far" (#21721)
- chore(DB): import pending files
- fix(DB/Core/Quests): Fix the quest "Load'er Up" (#20241)
- chore(DB): import pending files
- fix(DB/Halls of Lightning) Trash inside dungeon now drop [Relic of Ulduar] (#21713)
- chore(DB): import pending files
- fix(DB/Halls of Stone) Trash inside dungeon now drops [Relic of Ulduar] (#21710)
- chore(DB): import pending files
- fix(DB/Quest): Fixes the prerequisite quest for "A Job Undone" (#21714)

## 2025-03-15
- fix(Core/Movement): Allow MoveFollow to not inherit speed of the target (#21711)
- chore(DB): import pending files
- fix(Scripts/SunwellPlateau): Felmyst Demonic Vapor (#21709)

## 2025-03-14
- Merge branch 'master' into Playerbot
- fix(Core/Calendar): Fix crash on deletion while iterating through calendar events. (#21667)
- fix(Script/SunwellPlateau): Correct Meteror Slash Timer. (#21688)

## 2025-03-13
- chore(DB): import pending files
- fix(DB/Loot) Add missing recipes to SwP trashes (#21701)
- fix(Script/SunwellPlateau): Correct some spell's timers. (#21689)
- fix(Script/SunwellPlateau): Demonic Vapor Trail now despawn. (#21687)

## 2025-03-12
- fix(Scripts/ZulAman): text with symbol and improved frog movement (#21206)

## 2025-03-11
- chore(DB): import pending files
- fix(DB/Gameobject): Sniffed Values for 'Orb of the Blue Flight' spawns (#21696)
- chore(DB): import pending files
- fix(DB/Loot) Add missing loots on Eredar Twins and Entropius. (#21693)
- feat(Core/Entities): Add OnPlayerSendListInventory script hook (#21676)
- chore(DB): import pending files

## 2025-03-10
- fix(DB/Quest): Zapped Giants now behave correctly (#21100)
- fix(Core/Group): fix group loot for quest items (#21683)
- fix(Scripts/Hyjal): Fix hyjal trash (#21194)
- chore(DB): import pending files
- fix(Scripts/SunwellPlateau): Add Brutallus Flame Ring explosion (#21681)
- feat(Core/Entities): add OnPlayerCanGiveLevel script hook (#21666)
- fix(Script/SunwellPlateau): duplicate keys instance objects (#21679)

## 2025-03-09
- chore(DB): import pending files
- fix(DB/Loot Comments) - Added Missing Reference and Creature Loot Comments (#21672)
- chore(DB): import pending files
- fix(Quest/HillsbradFoothills) Elixir of Pain quest now has no prerequisite (#21662)

## 2025-03-10
- fix(deps/zlib): CVE-2022-37434: Potential Vulnerability in Cloned Function (#21599)
- fix(Core/PvP): OutdoorPvPZM - fetch creature spawnId correctly (#21634)

## 2025-03-09
- chore(DB): import pending files

## 2025-03-10
- fix(DB/SpellProc): Update Fists of fury proc chance to 5% (#21454)

## 2025-03-09
- fix(Core/SpellInfoCorrections): Fix "Throw Bomb" spell (#21463)
- chore(DB): import pending files
- refactor(Core/ServerMail): Refactor to Dedicated Manager Class with Multi-Item & Condition Support (#21590)
- chore(DB): import pending files
- fix(DB/SAI) add Wind trader mu'fah smart script (#21366)

## 2025-03-08
- chore(DB): import pending files
- fix(Scripts/SunwellPlateau): Sunblade Scout activate protector (#21629)
- Core/Unit: Revert AutoRepeatSpell delay application to Auto Shot (#19603)
- chore(DB): import pending files
- fix(DB/Creature) Adds Disable Gravity to Shield Orb. (#21671)

## 2025-03-07
- fix(Core/Tickets): Fix crash in `ticket complete` command. (#21665)

## 2025-03-06
- chore(DB): import pending files
- fix(DB/Creature) Solve some Shadowsword Assassin issues. (#21658)
- chore(DB): import pending files
- fix(DB/Gameobject): Sniffed Values for 'Isle Daily Gobs' spawns (#21655)

## 2025-03-05
- fix(CI/modules-build): enable mod-antifarming (#21654)
- fix(Core/Spells): readd 33% chance for lightning overload to fail on chain lightning (#21645)
- chore(DB): import pending files
- fix(Scripts/Ulduar): Fix Kologarn script (#21595)

## 2025-03-04
- Merge branch 'master' into Playerbot
- fix(Core/PvP): Sometimes mobs and objects fail to spawn in OutdoorPvP (#21636)
- fix(Core/Bones): Unable to create bones (#21635)

## 2025-03-03
- feat(CI/modules-build): add all current azerothcore modules (#21624)
- chore(DB): import pending files
- fix(DB): Add spawns for Tenris Mirkblood room in Karazhan. (#21638)
- chore(DB): import pending files

## 2025-03-02
- fix(DB/Creature): Disable Felmyst pathfinding (#21641)
- fix(CI/linux-build): use correct OS name for cache key (#21640)
- chore(DB): import pending files
- fix(DB/Disables): Remove incorrectly disabled quests. (#21628)
- chore(DB): import pending files
- fix(DB): Add Argent Dawn spawns for Scourge Invasion. (#21630)
- chore(DB): import pending files
- fix(Scripts/SunwellPlateau): Fix Felmyst air phase (#21637)
- fix(CI/Codestyle): Minor typo in insert_delete_safety_check (#21639)
- fix(CI/Codestyle): Imrpove semicolon check and general improvements (#21632)
- fix(CI/Codestyle): Escape all MySQL keywords and skip /* comments (#21631)
- fix (Core/Wintergrasp) Fix map and battle icon (#21622)

## 2025-03-01
- chore(DB): import pending files
- feat(DB): clarify IDs for faction changes  (#20480)
- fix (Core/Wintergrasp) hearthstone was visibly on cooldown when player left WG (#21620)
- fix (Core/Wintergrasp) Icon now disappears when player leaves queue (#21619)
- fix (Core/Wintergrasp) Change spell used by WG NPCs (#21621)
- chore(DB): import pending files
- fix(DB/Text) Add correct text on Sunblade Scouts. (#21626)
- feat(Core/BG): Allow battlegrounds to be configurable (#20320) (#21124)
- fix(Core/Spells): remove custom loop so that one lightning damage instance can only proc one lightning overload (#21625)

## 2025-02-28
- chore(DB): import pending files
- fix(DB/Creature) Various trash's issues on the road between Felmyst and Eredar Twins are now solved. (#21623)

## 2025-02-27
- chore(DB): import pending files
- fix(DB/Item) - Envolpe Assignment loot no longer gives you empty loot. (#21073)

## 2025-02-26
- chore(DB): import pending files
- fix(DB/Gameobject): Sniffed Values for 'Smuggled Mana Cell' spawns (#21617)
- chore(DB): import pending files
- fix(DB/Creature) Add formations to Scout's packs. (#21614)
- chore(DB): import pending files
- fix(DB/Creature) Elf patrols are now in formation. (#21613)
- fix(DB/Creature) Volatile Fiends now reach the end of the ramp. (#21600)

## 2025-02-25
- fix(Core/Server): Disable out of world packet requeuing (#21608)
- fix(Core/Spell) Removed Prey on the Weak triggering on dead targets (#21611)
- fix(scripts/SWP): remove whitespaces to fix codestyle check (#21609)
- chore(DB): import pending files
- fix(Scripts/Naxxramas): refactored instance script (#21539)

## 2025-02-24
- fix(Core/Threading): Refactored Map class - some code optimization (#21288)
- fix(Scripts/SunwellPlateau) Fix flame touched stacking (#21594)
- fix(Scripts/SunwellPlateau): Fix twins respawn (#21598)
- feat(Core/Scripting): Implement ScheduleEnrageTimer() helper (#21597)
- fix(Scripts/SunwellPlateau): Felmyst should cast Noxious Cloud only a… (#21596)
- chore(DB): import pending files
- fix(DB/Creature): Fix Felmyst flying animation in p1 and add despawn on evade (#21396)
- fix(CI/Codestyle): skip SQL keyword 'NOT' (#21591)

## 2025-02-23
- fix(Core/Logging): revert commit e3432102f7e66968f53c6e9afb11d7844e95… (#21593)
- fix(Core/Spells): Fixed pet swoop ability not rooting target (#21559)
- fix(Core/Spells): Fix "Repelling Wave" stun radius (#21587)
- fix(Core/Misc): Fix NextPage Data Type in PageText Structure and Improve Logging Messages (#21586)

## 2025-02-22
- fix(Scripts/SilverpineForest): Fix double spawn in Pyrewood Ambush an… (#21584)
- fix(Scripts/OutdoorPvP): Fix Halaa guards not spawning (#21585)
- Merge pull request #40 from liyunfan1223/Playerbot_20250219
- Merge branch 'master' into Playerbot_20250219
- chore(DB): import pending files

## 2025-02-21
- fix(Core/Spells): Ingvar Smash and Dark Smash should not ignore LOS (#21581)
- fix(DB/Creature): Fix Steel Gate Flying Machine inhabit type (#21582)

## 2025-02-22
- fix(Core/Spells): Fixed misdirection triggering from mend pet (#21526)

## 2025-02-21
- chore(DB): import pending files
- fix(DB/Creature): let Magister's Terrace Normal bosses give reputation until exalted and reduce Kael'thas reputation gain (#21532)
- fix(Scripts/ZulAman): scout drum and hard CC interaction (#21281)
- chore(DB): import pending files
- fix(DB/SAI): Fix Kael Flamestrikes chasing players (#21579)
- fix(Core/Maps): Fix instance factions (#21577)
- chore(DB): import pending files
- fix(Scripts/SunwellPlateau): Fix twin marks not applying from dots (#21415)
- chore(DB): import pending files

## 2025-02-20
- refactor(Core/Server): Improvements to antidos opcode handling (#21502)
- chore(CI): Add mod-costumes (#21548)

## 2025-02-19
- Remove MOD_PLAYERBOTS macro to compile without mod-playerbots
- Merge branch 'master' into Playerbot
- chore(DB): import pending files
- fix (DB/SAI) [Howling Fjord] Bjorn Halgurdsson behavior (#21474)
- chore(CI): Add mod-arena-3v3-solo-queue.git (#21530)
- refactor(Core/Packet): use WorldPackets::WorldState::InitWorldStates definition (#20475)
- chore(DB): import pending files
- fix(Scripts/Spell): Priest shadowfiend attack and Shadowfiend Death proc  (#20987)

## 2025-02-18
- fix(Core/Auth): prevent expansion overflow in SendAuthResponse (#21503)
- chore(DB): import pending files
- fix (DB/Creature) Alarmed Blightguards now spawn as they should. (#21489)
- fix(Core/Server): Add bytebuffer exception handling to addoninfo read (#21500)

## 2025-02-17
- fix(Core/Grids): Standardize grid coordinates (#21479)
- docs(README): update JetBrains logo (#21478)
- fix(UnitTest): fixes unit tests not compiling under windows (#21299)
- feat(Core/Scripting): Add new hooks for Ticket (#21238)
- fix(Core/Spell): Corrected values for event food (#21465)

## 2025-02-16
- feat(Script/Instance): added generic instance map script (#21218)
- fix(Scripts/Spells): Warrior IntimidationShout (#20969)
- chore(DB): import pending files
- fix(Scripts/Naxxramas): Add post-Gothik Four Horsemen introduction (#20550)
- chore(DB): import pending files
- fix(DB/Quest): Allow both factions to get quest "The Multiphase Survey" [id: 11880] (#21433)
- fix(Core/Spells): Implement SPELL_ATTR2_ALLOW_LOW_LEVEL_BUFF (#21470)
- chore(DB): import pending files
- fix(DB/Auth): allow autobroadcast_locale to have multiple locales for… (#21467)
- feat(Core/DBUpdater): include pending path (#21469)
- chore(DB): import pending files
- fix(DB/Creatures) Various Northrend NPCs now have a SmartAI. (#21471)
- - Added support for playerbots message hyperlink (#37)
- fix(Core/PlayerScript) Align player script function names (#21020)

## 2025-02-15
- chore(DB): import pending files

## 2025-02-16
- fix(DB/SAI) Quest Feedin' Da Goolz (12652) (#21264)

## 2025-02-15
- fix(Core/World): Load metric and log configs at start (#21243)
- feat(Core/Scripting): Add Player skill based hook (#21273)
- fix(Core/Spells): Chain heal shoudln't jump to other players who are at full hp. (#21387)

## 2025-02-16
- fix(Scripts/Naxxramas): Maexxna's Outer Web Door (#21445)

## 2025-02-15
- fix(Core/Common): Container fixes use after free  (#21460)

## 2025-02-16
- fix(Apps/Codestyle) corrected wrong text in the sql codestyle check (#21466)
- fix(Core/Creature): Correctly get flag from cinfo in IsDungeonBoss & IsImmuneToKnockback (#21456)

## 2025-02-15
- chore(DB): import pending files
- fix(Core/Spells): Hand of Protection no longer removes Nalorak's Mangle (#21413)
- fix (DB/Creature) Correct a missing link in Valgarde Harpoon Target SmartAI (#21462)
- fix(CI/nopch-module-build): ensure build continues after errors (#21457)
- fix(Scripts/Outland): LoadMinionData buffer overflow (#21461)
- chore(DB): import pending files
- fix (DB/SAI) [Howling Fjord] Attack to Valgarde. Dragonflayer Invader and Worg. Valgarde Defender. (#21434)
- fix(CI/Windows): Bump openssl version (#21458)
- fix(Scripts/Spells): Corrected shaman 8/8 T2 set bonus damage proc (#21432)
- fix(Core/SpellQueue): Fix undefined behavior when processing SpellQueue. (#21459)

## 2025-02-14
- fix(Core/Grids): Grid improvements (#20955)
- fix(Core/Chat): Fix lower security check for GM commands. (#21382)
- fix(Core/Spell): Reset insignia spell target when it is deleted. (#21437)
- chore(DB): import pending files
- fix(DB/Creature): Sniffed Values for 'Chemical Wagon' spawns (#21446)
- fix(Core/Pet): Fix possible heap-use-after-free of charmInfo when handling pet action. (#21439)
- fix(Core/Player): SpellQueue avoid possible undefined behavior by copying instead of move (#21444)
- fix(Scripts/ShadowmoonValley): Illidan buffer overflow (#21442)
- fix(Scripts/BlackTemple): Illidan buffer overflow (#21441)
- fix(Core/Map): Dynamic respawns: preserve original respawn timer and skip rares (#21440)
- fix(Scripts/ICC): Fix crash in npc_darnavan when killer is nil. (#21438)

## 2025-02-13
- fix(Core/Channels): Don't use deleted pointer in channel name creation. (#21435)
- fix(Core/Creature): Creatures should skip confused targets (#21410)
- chore(Config): Improve DynamicRates description (#21431)
- fix(Core/Worldstate): fix Sanctums Wards triggering phase transition too early (#21430)
- chore(DB): import pending files
- fix(Scripts/SunwellPlateau): Fix Felmyst death event (#21425)
- chore(DB): import pending files
- fix(Scripts/Naxxramas): Update Faerlina script (#21375)

## 2025-02-12
- refactor(Core/World): Create WorldSessionMgr to split session logic out of World (#21400)
- fix(Scripts/SunwellPlateau): Fix Brutallus burn timer (#21423)
- fix(Core/Group): Fix use of a deleted pointer in the group invites list. (#21422)
- fix(Core/Guild): Fix use of guild members' data after deletion. (#21421)
- fix(Core/Pet): Fix possible crash when using dangling pointer as pets spell target and fix possible memory leak. (#21420)
- fix(Core/Scripts): Fix buffer-overflow errors in scripts. (#21419)
- chore(DB): import pending files
- fix(DB/Creature): Sacrolash and Alythess should be taunt immune (#21418)
- feat(Core/Maps): Implement dynamic respawn rates (#21417)
- fix(Core/Disables): Optimize DisableMgr container (#21416)
- feat(Core/Unit): Add SpellSchoolMask info to the DamageDealt() hook (#21411)
- chore(DB): import pending files
- feat(Core/Arena): Add support for arena seasons completion with progression in runtime. (#19858)
- refactor(Misc): improve issue templates (#21391)

## 2025-02-11
- fix(Core/SQLField): Fix heap-buffer-overflow issue when interacting with mysql field value. (#21393)
- fix(Core/Items): Fix duplication exploit where a player could loot infinitely from bags containing gold. (#21394)
- Merge branch 'master' into Playerbot
- fix(Scripts/SunwellPlateau): Don't replay Felmyst intro after wipes (#21398)

## 2025-02-10
- chore(DB): import pending files
- fix(DB/Creature) Dawnblade Hawkriders and Shattered Sun Marksmen behaviours. (#21341)
- fix(CI/Codestyle): correct double semicolon check (#21388)
- fix(Core/PacketIO): Implemented CMSG_BUSY_TRADE and CMSG_IGNORE_TRADE. (#21385)
- fix(Scripts/SunwellPlateau): Clear basic events on death (#21374)
- fix(Scripts/SunwellPlateau): Prevent Sathrovarr summon event from dou… (#21376)
- chore(DB): import pending files
- fix(DB/SAI): Fix Doomfire Shard Avenging Wrath spell (#21377)
- fix(Core/Creature): Allow temp summons to respawn when despawning on … (#21363)

## 2025-02-09
- chore(DB): import pending files
- fix(Scripts/SunwellPlateau): Correct Felmyst spawn event (#21360)
- fix(Scripts/SunwellPleateau): Remove invincibility from human kalecgos (#21369)
- fix(Core/Worldstate): sunsreach print correct counter (#21356)
- chore(DB): import pending files
- fix(DB/Creature): Correct run speed of Kael'thas's Arcane Spheres on heroic. (#21367)
- chore(DB): Add missing file extension for query. (#21368)
- chore(DB): import pending files
- fix(DB/Conditions): Sunwell Gates progress gossip (#21344)
- chore(DB): import pending files
- fix(DB/SAI) add Kaylaan smart ai (#21293)

## 2025-02-08
- Revert "chore(Deps/Zlib): move to Cloudflare fork (#21028)" (#21364)
- feat(Core/Creature): Implement HasFlagsExtra() helper to creature (#21362)
- fix(CI/Codestyle): Final fixes to backtick check (#21361)
- fix(Core/Transport): Fix for passengers dropped in the middle of nowhere  (#21296)

## 2025-02-07
- chore(DB): import pending files
- fix(DB/Quest): Remove Failed Incursion requirement from Lost in Action (#21353)

## 2025-02-08
- fix(Core): Fix After PR#21213 Crash (#21327)

## 2025-02-07
- chore(DB): import pending files
- fix(DB/Creature): Remove aggro from Abandoned Fuel Tank (#21352)
- chore(Core/EventMgr): Align code to Code standard & improve LoadFromDB function (#21151)
- fix(DB/Creature) Theremis, Archmage and Yrma floating now. (#21349)
- chore(DB): import pending files
- fix(DB/Creature) Thornvine Creeper is skinnable with herbalism. (#21350)
- fix(DB/Creature) Enable mining for Iron Rune Sentinel (#21348)
- fix(CI): typo (#21347)
- chore(DB): import pending files
- fix(DB/CreatureAddon): add hawkstriker mount to Sun's Reach patrol (#21345)
- fix(CI/Codestyle): ignore lines starting with @ (#21346)
- fix(CI/Codestyle): Ignore comments for backtick check (#21343)

## 2025-02-06
- chore(DB): import pending files
- fix(DB/Creature): Fix gold drop rate for sunfury mobs in netherstorm (#21250)
- fix(Scripts/Northrend): Exclude Dalaran Sewer Exit Pipe from GUARD teleport checks (#21222)
- chore(Deps/Zlib): move to Cloudflare fork (#21028)
- chore(DB): import pending files
- fix(DB/creature_template-skinning_loot_template): Removed some wrong skinloot template (#18626)
- chore(DB): import pending files
- fix(DB/SAI): Add target type correction for spell 43458 (Secrets of Wyrmskull) (#20294)
- fix(Script/ICC): Make Sindragosa Tail Smash - ignore LOS(#20935)
- fix(Scripts/IcecrownCitadel): Sindragosa P3 Exploit (#20938)
- fix(Core/Battlefield): Wintergrasp out of bounds error when setting neutral faction of stalker (#21340)
- chore(DB): import pending files
- fix(DB/Text): Fix Brutallus text language (#21338)
- chore(DB): import pending files
- fix(Scripts/SunwellPlateau): Felmyst should be invincible while flying (#21336)
- fix(DB/Creature): Kalecgos should despawn on evade (#21335)

## 2025-02-05
- chore(DB): import pending files
- fix(DB/Creature) Various Northrend NPCs have SmartAI now. (#21330)
- fix(CI/Codestyle): Backtick check SET, quote and REPLACE case (#21333)
- fix(DB/world): delete base/db_world/player_classlevelstats.sql (#21329)
- chore(DB): import pending files
- fix(Scripts/Spells): Fix Isle of Queldanas Orb of Translocation (#21325)

## 2025-02-04
- Merge branch 'master' into Playerbot
- chore(DB): import pending files
- fix(DB/SAI): Escape from Jaedanar group completion (#21286)
- Feat(Core/Player): Add ExtraBonusTalentCount methods (#21271)
- feat(Core/Scripting): Add new hook OnUnitSetShapeshiftForm (#21235)

## 2025-02-03
- fix(CI/Windows): fix windows build (#21322)
- feat(CI/Codestyle): backtick check for sql (#21321)
- fix(DB/updates): add missing backticks to 2025_02_03_00.sql (#21320)
- Feat(Core/Scripting): Add new hook CanPlayerResurrect to simplify HardCore mod etc. (#21272)
- fix(Scripts/Oculus): Prevent boss Urom teleportation to nowhere on fast kill (#21305)
- fix(Script/ZulAman): Don't start the timer before Harrison Johnes event (#21311)
- chore(DB): import pending files
- fix(Scripts/SunwellPlateau): Remove Sunwell Radiance from mobs (#21312)
- chore(DB): import pending files
- fix(DB/Locale) Minor fix Russian locale of quests (#21313)

## 2025-02-01
- feat(Core/SAI): implement SMART_ACTION_DISABLE_REWARD (#21105)
- refactor(Core/Disables): Convert from Namespace to Class Structure (#21109)
- chore(DB): import pending files
- refactor(Core/ObjectMgr): Change GetAcoreString from char const* to s… (#21213)
- fix(DB/Misc): Bad delete in update file (#21307)
- chore(DB): import pending files
- refactor(Scripts/MagisterTerrace): Clean up Vexallus instance script … (#21303)
- chore(DB): import pending files
- fix(DB/SAI): Fix Brightscale Wyrm Energy Infusion (#21304)

## 2025-01-31
- chore(DB): import pending files
- fix(Scripts/MagisterTerrace/DB) Vexallus Boss Complete Overhaul (#21266)
- chore(DB): import pending files
- feat(Core/WorldState): implement Battle for Sun's Reach Event (#21219)
- Merge branch 'master' into Playerbot

## 2025-01-30
- fix(Scripts/SunwellPlateau): Fix Felmyst start fight (#21291)

## 2025-01-29
- fix(Scripts/MagisterTerrace): Fix Kael's outro and close door during … (#21289)
- fix(Scripts/SunwellPlateau): Fix Madrigosa flight movement (#21290)

## 2025-01-28
- chore(DB): import pending files
- fix(DB/Creature) Update Amani Trainer SmartAI comments. (#21282)

## 2025-01-27
- chore(DB): import pending files
- fix(DB/SAI) Fix Amani Trainer Abilities (#21269)
- chore(DB): import pending files
- fix(Scripts/MagisterTerrace): Rescript Kael's intro (#21278)
- chore(DB): import pending files
- refactor(Core/Motd): improve and simplify (#21252)
- feat(Core/Unit): Implement SetEmoteState() and ClearEmoteState() helpers (#21279)

## 2025-01-26
- chore(DB): import pending files
- fix(DB/SAI) - Fixes quest Counterattack! sometimes not being completed and adds 1 ability to the creature. (#21050)
- chore(DB): import pending files
- fix(DB/Creature) Several Dragonflayers now have a SmartAI. (#21275)
- chore(DB): import pending files
- feat(Core/Creatures): implement a sparring system (#19824)
- chore(DB): import pending files
- feat(Core/Autobroacast): Add autobroadcast locale (#20946)
- SECURITY.md File Update  (#20190)

## 2025-01-25
- fix(Scripts/BlackTemple): Fix Gurtogg will not use acidic wound in phase 2 (#21253)
- fix(Core/Auction):  Fix  usable item search in auction (#21267)
- chore(DB): import pending files
- fix(DB/SAI): Correct Phoenix/Egg rebirth and combat behaviour (#21261)
- fix(Apps/Codestyle): ignore comments for some checks (#21268)

## 2025-01-24
- chore(DB): import pending files
- fix(DB/Gameobject): remove extra Sanctum Planetarium (#21251)
- chore(DB): import pending files
- fix(DB/Loot) Clean up loot of bosses in MGT HC (#21262)
- fix(Scripts/MagisterTerrace): Fix Phoenixes and eggs not despawning (#21260)

## 2025-01-23
- chore(DB): import pending files
- fix(DB/Creature): Fix Flamestrike inhabit types (#21249)
- Merge branch 'master' into Playerbot
- fix(Core/Threading): Refactored LockedQueue / MPSCQueue - Improve thread safety, performance, and memory management (#21127)
- chore(DB): import pending files
- fix(DB/Creature): Correct Sunblade Sentinel fel lightning (#21245)
- chore(DB): import pending files
- fix(Scripts/MagisterTerrace): Implement missing Kaelthas text line (#21247)
- fix(DB/Creature): Felblood Kael'thas should despawn on evade (#21246)

## 2025-01-22
- fix(Scripts/MagistersTerrace) Add 5s Vexallus Pure Energy (#21239)

## 2025-01-23
- chore(DB): import pending files

## 2025-01-22
- fix(Scripts/MagistersTerrace): Pheonix will now reset after death (#21240)

## 2025-01-23
- fix(DB/SAI): Kael'Thas Phoenix now only use fireball during gravity Lapse. (#21244)

## 2025-01-22
- chore(DB): import pending files
- fix(DB/Creature) Sunblade Sentinel "Fel Lighting" has different timers and comment updated. (#21229)
- chore(DB): import pending files
- fix(DB/Creature) Fel Crystals no longer follow players. (#21227)
- fix(DB/Creature) Various Shoveltusk SmartAI added. (#21234)

## 2025-01-21
- fix(Core/Instances): Ensure team is acquired before spawning creatures (#21221)
- refactor(Core/Player): Improve Channel.RestrictedLfg handling (#21145)
- chore(Apps/Codestyle): add new checks for SQL files (#21026)

## 2025-01-20
- refactor(Core/Loot): Simplify GetFishLoot with for loop and merge Get… (#21217)

## 2025-01-19
- fix(Core/Gameobject): prevent getting empty fishing loot (#21216)
- refactor(Scripts/BloodFurnace): Clean up instance script (#21207)
- fix(Core/ObjectMgr): Potential crash in GetModuleString() (#21211)
- chore(Docker): Update dev container to ubuntu24.04 (#21044)
- chore(DB): import pending files
- fix(Scripts/ScarletMonastery): improvement ScarletMonastery (#17558)
- chore(DB): import pending files
- fix(Core/DB) - Correct the max length of a username to 17 characters (#21183)
- fix(Scripts/Naxxramas): fixed invalid horseman state on instance init (#21167)
- feat(Core) - Additional "ActionButton" log information. (#21201)
- chore(DB): import pending files
- fix(DB/Gameobject): Pooling and sniffed Values for 2744 'Giant Clam' spawns (#21203)

## 2025-01-18
- feat(Scripting/Spell): Add new hooks for Spell (OnSpellCast, OnSpellPrepare, OnSpellCancel) (#21149)
- chore(DB): import pending files
- fix(DB/Creature) Kel'thuzad no longer attacks players. (#21199)
- chore(DB): import pending files
- fix(DB/Gameobject): pooling and sniffed Values for 19018 'Giant Clam' spawns (#21197)
- fix(Core/Unit): Fix fast creatures chasing indefinitely (#21200)

## 2025-01-17
- refactor(Core/Instances): Implement GetTeamIdInInstance() for two-fac… (#21168)
- chore(DB): import pending files
- fix(Script/WP): correct output of wp show command (#21193)
- fix(Core/Misc): Resolve output formatting issues with fmt library (#21191)
- chore(DB): import pending files
- fix(DB/Creature): Remove rooted inhabit type from Coilfang Beast Tamer (#21196)

## 2025-01-16
- chore(DB): import pending files
- fix(DB/Creature) Bloodscalp Witch Doctor can now move during combat. (#21189)
- refactor(Github/Misc): Deprecate Suggestion label and use Github Type (#21192)
- refactor(Core/SmartScripts): Clean up validation logic by replacing A… (#21184)
- chore(DB): import pending files
- fix(DB/Spell): Add sniffed data for Medallion of Karabor. (#21185)
- chore(DB): import pending files
- fix(DB/SAI): Tamed Amani Crocolisk abilities (#21188)
- fix(DB/SAI): Amani Lynx shouldn't use dash (#21187)
- chore(DB): import pending files

## 2025-01-15
- fix(Scripts/Silverpine): Fix Fearleia not reseting and modernize Pyre… (#21159)
- chore(DB): import pending files
- fix(Scripts/ZulAman): prevent early engaging of door guardians to skip timed event (#21177)
- Merge branch 'master' into Playerbot
- chore(DB): import pending files
- fix(DB/Spell): Correct map ID for Medallion of Karabor. (#21175)
- chore(DB): import pending files
- fix(DB/Creature) Some Borean Tundra npcs now have a smartai.  (#21171)
- chore(DB): import pending files

## 2025-01-14
- fix(DB/Spell): fix item "Blessed Medallion of Karabor" (#20948)

## 2025-01-15
- chore(DB): import pending files
- fix(Scripts/ZulAman): Zul'Jin reduce procs of Energy Storm Aura (#21169)

## 2025-01-14
- chore(DB): import pending files
- fix(DB/SAI): Amani'shi Berserker SAI (#21165)
- chore(DB): import pending files
- fix(DB/Creature) Solve some npc problems along the road to Drakos. (#21152)
- chore(DB): import pending files
- fix(Scripts/ZulAman): Akilzon Gauntlet hyperspawn, handling Eagle Trash Triggers (#21129)
- chore(DB): import pending files
- fix(DB/Creature) Remove double Nerub'ar Victims and set a Crystalline Tender movement type to 0. (#21153)
- chore(DB): import pending files
- fix(Scripts/ZulAman): Store chest count in DB (#21160)
- fix(DB/page_text) - Added Sniffed Texts to the plaques in Hall of Champions (Scarlet Monastery Armoury) (#21157)
- chore(DB): import pending files

## 2025-01-13
- fix(DB/SAI): Sunfury Bloodwarder do not intercept anymore (#21147)
- fix(Core/Map): Fix crash OnPlayerLeave() (#21155)
- chore(DB): import pending files
- fix(DB/Conditions): Havenshire horses spellclick should require Grand… (#21154)
- fix(Core/Group): CF Faction Assign & Leader Instance Faction (#21118)

## 2025-01-12
- fix(Scripts/ZulAman): Use Zul'jins threatlist to search for cyclone t… (#21138)
- chore(DB): import pending files
- fix(DB/Loot): Malacrass should drop 2 pieces of loot and sometimes Tiny Vodoo Mask (#21139)
- chore(DB): import pending files
- fix(DB/Creature) - Removes weapons from Rorgish Jowl (#21142)

## 2025-01-11
- feat(CMake/Eluna): Update CMakeLists for modules to allow Eluna to switch Lua version (#21123)
- chore(DB): import pending files

## 2025-01-10
- fix(DB/SAI): Fix Marauding Bursters repositioning in combat (#21135)

## 2025-01-11
- chore(DB): import pending files

## 2025-01-10
- fix(DB/Creature): Akil'zon interrupt immunity (#21130)
- chore(DB): import pending files
- feat(Scripts/Commands): Implement opendoor command (#21136)
- chore(DB): import pending files
- feat(Scripts/Commands): Update GetBossState to display all states (#21134)
- fix(Player/SpellQueue): bandaid crashfix (#21103)
- fix(Scripts/ZulAman): Fix Hexlord gate not opening after crashes (#21133)
- chore(DB): import pending files
- fix(Scripts/ZulAman): Zul'jin Add Cooldown to EnergyStorm proc (#21132)
- fix(Scripts/ZulAman): Limit target search range for Cyclones (#21131)
- chore(DB): import pending files
- fix(Scripts/ShatteredHalls): Add scripts & spawn for quest "Imprisoned in the citadel" (#21114)

## 2025-01-09
- chore(DB): import pending files
- fix(DB/Creature)Badlands Reagent Run II dragons don't aggro when sucking blood (#21021)
- fix(Core/World): edge case when last Char on realm was deleted (#20864)
- chore(DB): import pending files
- fix(Scripts/Spells): Move Curse of Mending (7098 & 39647) to spell sc… (#21117)
- Merge branch 'master' into Playerbot
- chore(DB): import pending files
- fix(DB/Creatures) Remove Tanzar from his cage and activate group loot for its chest. (#21120)

## 2025-01-08
- fix(Scripts/SunwellPlateau): Muru - Changed the amount of Tick Negative Energy Periodic (#21102)
- fix(Core/Threading): Modernize/Improve thread safety, performance, and maintainability of the MapUpdater class (#21081)
- fix(Scripts/ZulAman): Increase Jan'alai teleport exclusion zone (#21115)

## 2025-01-07
- fix(Scripts/ZulAman): Scout's hut search should ignore the world trigger near Jan'alai (#21113)
- fix(Scripts/Halion): Halion freeze against "Feign Death" hunters (#21093)
- chore(DB): import pending files
- fix(DB/Conditions): remove conditions for Rune of Mazthoril (#21053)
- chore(DB): import pending files

## 2025-01-06
- fix(DB/Loot) Sealed Craftsman's Writ loot problem (#20981)

## 2025-01-07
- fix(Core/Misc): Correct some fmt logs (#21106)
- chore(DB): import pending files
- fix(DB/Creature) Add Waypoint and Creature Formation for Medicine Man and Wind Walker (#21108)
- chore(DB): import pending files
- fix(DB/Creature) Clean road to Halazzi. (#21110)

## 2025-01-06
- fix(Scripts/ZulAman): make sure Malacrass timer is delayed only when it should be triggered during channel of Spirit Bolts (#21089)
- Merge branch 'master' into Playerbot
- refactor(Scripts/ZulAman): clean up Helazzi code (#21101)

## 2025-01-05
- chore(DB): import pending files
- fix(Scripts/ZulAman): Fix initial pack not chasing distant players (#21098)
- chore(DB): import pending files
- fix(DB/SmartAI): `HEALTH_PCT` where Min equals Max (#21097)
- chore(DB): import pending files
- fix(DB/Creature) Rain of Darkness and Saronite Arrows spawn. (#21094)
- fix(Scripts/ZulAman): add Scout run to drums (#21095)
- chore(DB): import pending files
- fix(DB/SmartAI): more consistent bear summon, despawn bear on reset (#21096)
- chore(DB): import pending files
- fix(DB/Creature): Correct behavior and emote of oil-covered birds (#20923)
- chore(DB): import pending files
- fix(DB/Creature): Set respawn to 15s for Soul Fragments in the Shrine of Lost Souls (#20992)
- chore(DB): import pending files
- fix (DB/Creature) Remove some Amanshi Scouts and add a Waypoint for two of them. (#21092)

## 2025-01-04
- fix (Boss/Script) Increase Spell Hatch Egg cooldown by one second. (#21090)
- chore(DB): import pending files
- fix(Scripts/ZulAman): initial Amani'shi pack (#21084)
- chore(Core/World): improve server restart/shutdown logging (#21046)
- chore(DB): import pending files
- fix(DB/SAI): Add dialogue between creature argah 27440 and creature sagai 27441 (#21075)
- chore(DB): import pending files
- fix(DB/Locale): deDE fixes for quest offer reward entry 8346 (#21076)

## 2025-01-03
- fix(Scripts/ZulAman): make Zul'Jin p3 cyclones go to random targets (#21087)
- chore(DB): import pending files
- fix(Scripts/ZulAman): Fix Jan'lai teleport spells (#21083)

## 2025-01-02
- fix(Scripts/ZulAman): reset Nalorakk's intro on wipe (#21063)
- fix(Core/Spells): Remove level scaling from Booming Voice (#21054)

## 2024-12-31
- Merge branch 'master' into Playerbot
- chore(DB): import pending files
- fix (DB/Creature) Citizen of Havenshire waypoints and SmartAI. (#21048)
- fix(DB/Creature) Scarlet Peasant SmartAI. (#21069)

## 2024-12-30
- chore(DB): import pending files
- fix(Scripts/ZulAman): Eagle Gauntlet behavior (#20947)
- fix(Scripts/PitOfSaron): Fix Scourgelord Tyrannus not respawning afte… (#21070)
- chore(DB): import pending files
- fix(DB/Locale): deDE fixes for quest greetings (#21067)
- fix(Scripts/PitOfSauron): Reset Scourgelord Tyrannus encounter state (#21057)
- fix(Core/Player): fix output for disabled maps (#21068)
- chore(DB): import pending files
- fix(DB/SAI): restore Drakuru’s (id: 28802) health to 100% upon charming (#21037)
- fix(Scripts/ZulAman): add Boss Boundaries (#21065)
- fix(Scripts/ZulAman): add Altar Torch visuals (#21064)

## 2024-12-29
- chore(DB): import pending files
- fix(DB/Locale): deDE fixes cata quest texts to wrath state - part 2 (#21059)
- chore(DB): import pending files
- fix(DB/Locale): deDE fixes cata quest texts to wrath state (#21049)
- fix(Scripts/Karazhan): Chess pieces reset to correct positions (#21061)
- chore(DB): import pending files
- fix(Scripts/Zul'Aman): Band-Aid fix for hostage loot. (#21060)
- chore(DB): import pending files
- chore(DB): Delete empty/null entries (#21058)
- chore(DB): import pending files
- fix(DB/Creature): Arcanist Helion gossip text (#21062)
- Merge pull request #33 from liyunfan1223/move_backwards
- Add MovePointBackwards in MotionMaster.h

## 2024-12-28
- chore(DB): import pending files
- fix(DB/SAI): SAI overhaul of Deadwood Warrior, Gardener and Pathfinder (#20901)
- chore(DB): import pending files
- fix(Scripts/Spells): Death Knight Army of the Dead auras (#19795)
- chore(DB): import pending files
- fix(Scripts/ICC): Use threatlist for vampiric bite (#21012)

## 2024-12-26
- fix(Core/Spells): Initial threat for periodic effects (#21045)
- chore(DB): import pending files
- fix(Scripts/SSC): Fix console panel gate not opening (#21047)
- feat(Unit/Misc): HasAnyAuras() HasAllAuras() HasAuras() (#21040)
- chore(Scripts/SSC): Move Vashj summons to the new format (#21042)
- chore(DB): import pending files
- fix(DB/Creature): Add Illidari Nightlord interrupt immunity (#21031)
- chore(DB): import pending files
- fix(DB/Creature)Ashtongue Stormcaller missing interrupt immunity (#21030)

## 2024-12-25
- fix(Core/Log): fmt output for appender (#21043)
- feat(CI/linux-build): introduce option to set maxerrors for compilation (#21022)
- fix(Script/Zul'Aman): adjust Zuljin timers (#20919)
- chore(DB): import pending files
- fix(DB/page_text_locale): deDE name and location fixes (#21035)
- Merge pull request #32 from liyunfan1223/modify_char_sel
- Add class and race to CHAR_SEL_CHARS_BY_ACCOUNT_ID

## 2024-12-24
- chore(DB): import pending files
- fix(DB/Object) Sniffed Saronite Arrows spawn in phase 1. (#21029)
- fix(Apps/Codestyle): rewrite semi-colon check (#21027)

## 2024-12-23
- fix(Core/Network): fix high idle cpu load in NetworkThread (#21033)
- fix(Scripts/Hyjal) First wave should not grant reputation (#21004)
- chore(CI): Update CI run types (#21015)

## 2024-12-22
- fix(Core/Auctionhouse): Fix auctionhouse searches with locales other than enUS (#21019)
- chore(DB): import pending files
- chore(DB/quest_request_items_locale): Remove empty or NULL entries (#21013)
- refactor(CI/Codestyle): Move the SQL check to python (#21002)
- fix(Scripts/ICC): Make Blood-Queen Lana'thel bite tanks as well (#17834)
- chore(DB): import pending files
- feat(Core/Creature): Add new config option for npc speeds (#20617)
- refactor(Core/Event): Load event vendors seperatly (#20906)
- refactor(Core/Time): Introduce GetExpirationTime instead of calculati… (#21006)
- fix(Script/Command): Allow guid for npc move and delete (#21008)
- Core/TempSummons: avoid use MoveInLineOfSight before InitSummon (#20999)
- fix(CI): do not run on draft PRs (#21009)
- refactor(Core/Unit): Add naming for all ShapeshiftFlags (#20989)
- chore(DB): import pending files
- fix(Creature/Loot) Remove Black Pearl item from all creatures. (#20988)
- Merge branch 'master' into Playerbot
- feat(CI/Codestyle): Check for tabs (#20998)

## 2024-12-21
- feat(CI/modules_build): trigger on file change instead label (#20997)
- feat(CI/Codestyle); Check for double semicolons (#20996)

## 2024-12-20
- Revert "chore(Licence): Add an agreement to relicense for futur PRs" (#20986)
- chore(DB): import pending files
- fix(DB/Object) Add Saronite Arrows in Phase 2. (#20975)
- chore(DB): import pending files
- fix(DB/Loot)Add missing heavy stone loot entries (#20971)
- fix(Core/WorldSession): incorrect fmt formatting (#20926)
- chore(DB): import pending files
- fix(DB/item_loot_template): fix Santa sometimes handing out empty pr… (#20978)
- chore(Licence): Add an agreement to relicense for futur PRs (#20910)

## 2024-12-19
- feat(CI/Codestyle): check for curly brackets before/after if/else statements (#20977)
- docker-compose: ac-database: bump to mysql LTS (#20976)
- feat(tools/vmap4_extractor) Add detection of collision-only material IDs (#20822)
- refactor(Deps/MySQL): replace hardcoded MySQL paths (#20870)
- refactor(Core/Misc): Use steady_timer instead of deadline_timer (#20940)
- chore(DB): import pending files

## 2024-12-20
- Fix(DB/SAI): Add dialogue between Archmage Mordent Evenshade and Sentinel Stillbough (#20913)

## 2024-12-19
- fix(Scripts/Spells): Fix Aether Ray behaviour for quest Wrangle Aethe… (#20972)

## 2024-12-18
- fix(Scripts/BlackTemple): Update AreaBoundary to avoid reset in the corners with Illidari council (#20957)
- fix(Core/Player): Quest failure sound when inventory full (#20970)
- fix(Core/Database): Gracefully close database workers (#20936)
- fix(Core/Movement): Fix creatures not resuming movement after being talked to (#20945)
- feat(Core/AuctionHouse): Rework auctionhouse search threading (#20830)
- refactor(Core/Random): Remove unused map based RNG (#20939)
- chore(DB): import pending files
- fix(DB/Creature) Scarlet Land Cannons (#20922)
- ci: fix codestyle and cppcheck reports (#20962)
- fix(apps/DatabaseExporter): fix utf-8 encoding for sql export (#20951)
- fix(Script/ZulAman): Nalorakk abilities. (#20937)
- feat(DB): Release ACDB 12.0.1 (#20954)

## 2024-12-17
- feat(Scripts/Command): Update gm fly to behave like a toggle (#20925)
- fix(Scripts/ZulAman): Fix Electric Storm shouldnt hit safe players (#20897)
- chore(DB): import pending files
- fix(DB/CreatureSAI) - Removed "Charm" Flag from Frayfeather Stagwing and Frayfeather Skystormer (#20943)
- fix(Core/Player): SpellQueue fix typo StartRecoveryCategory (#20944)

## 2024-12-16
- feat(DB): New DB exporter and versioning tools for DB squashes (#20920)

## 2024-12-15
- chore(DB): import pending files
- feat(Core/Motd): Allow localized motd (#20542)
- feat(DB): Release ACDB 12.0.0 (#20921)

## 2024-12-14
- feat(Core/Player) Option to adjust max rest bonus via config (#20836)
- chore(DB): import pending files
- fix(DB/SAI): several missing abilities in Zul'Aman (#20918)
- fix(Scripts/TheEye): Kaelthas reduce time until all advisors phase (#20914)
- chore(DB): import pending files
- fix(DB/Creature): Illidari Nightlord remove distract and add banish i… (#20912)
- feat(Core/Player)Add quest failure sound when inventory is full or quest failed (#20917)

## 2024-12-13
- Merge branch 'master' into Playerbot
- feat(Core/WorldObjects): implement Heartbeat timers (#20872)

## 2024-12-12
- feat(Core/Player): implement Spell Queue (#20797)
- chore(DB): import pending files
- fix(Scripts/TrialOfChampion): fail and send custom spell error when trying to mount without lance equipped (#19932)
- Fix(Core/Player): Energy regen rate bonuses (#20321)
- chore(DB): import pending files
- feat(Core/SAI): Implement SMART_ACTION_DISMOUNT (206) (#20899)
- chore(DB): import pending files
- fix(DB/Creature): Fix ZA bosses not despawning on evade (#20900)

## 2024-12-11
- fix(Scripts/IcecrownCitadel): Vengeful Shade unroot timer fix (#20902)
- chore(DB): import pending files
- fix(DB/Creature): Amanishi Tempest should be immune to taunts, fears … (#20898)

## 2024-12-10
- fix(Scripts/ZulAman): Malacrass adds shouldnt change on wipes (#20894)
- chore(DB): import pending files
- fix(DB/Creature) Havenshire Horses run from Stables to New Havalon. (#20884)
- fix(Scripts/ZulAman): Dont update Hexlord timers while casting (#20876)
- chore(DB): import pending files
- fix(DB/Loot): improve Illidan loot (#20767)
- fix(DB/Creature)Amani Eagle doesn't use Talon ability. (#20888)

## 2024-12-09
- chore(DB): import pending files
- fix(DB/Creature) - Removed the profession requirement to interact with trainer (#20763)
- fix(Scripts/ZulAman): Zuljin abilities shouldnt overlap (#20875)
- fix(Scripts/SunwellPlateau): Fix Entropius despawning (#20874)

## 2024-12-08
- chore(DB): import pending files
- fix(DB/Creature): Sniffed Values for 'Lunar - Revelers' spawns (#20866)
- fix(Core/AI): Increase movement leash extension interval. (#20867)
- chore(DB): import pending files
- Fix(DB/Spawn) Silt Crawlers under the landscape (another two). (#20861)
- chore(DB): import pending files
- fix(DB/Creatures) Scarlet Enclave phase 4 npcs (2-2). (#20852)

## 2024-12-07
- chore(DB): import pending files
- fix(DB/Gameobject): Improve spawns positions of 180867 `Greater Moonl… (#20849)
- chore(DB): import pending files
- fix(DB/Gameobject): Sniffed Values for 'Lucky Red Envelope' spawns (#20850)
- fix(DB/Gameobject): Sniffed Values for 'Starsong Scroll' spawns (#20851)
- fix(DB/Gameobject): Sniffed Values for 'DwarvenTableSmall' spawns (#20853)
- fix(DB/Gameobject): Sniffed Values for 'Boss Fight Altar' spawns (#20854)

## 2024-12-06
- chore(DB): import pending files
- fix(DB/Creatures) Scarlet Enclave phase 4 npcs (1-2). (#20827)
- fix(Core/SpellAuraEffects): use caster's level to scale amount to break crowd control auras (#20153)

## 2024-12-05
- chore(DB): import pending files
- fix(Scripts/ZulAman): Akil'zon storm damage should multiply per tick (#20842)
- fix(Scripts/ZulAman): Zul'jin gate should be unlocked instead auto open (#20841)

## 2024-12-04
- fix(Scripts/Karazhan): Nightbane Speed (#20838)

## 2024-12-05
- Merge branch 'master' into Playerbot

## 2024-12-04
- fix(CI/nopch-modules): bump to ubuntu-24.04/clang-18, align with nopc… (#20832)
- fix(CI): make tools build able to run on PRs again (#20831)

## 2024-12-03
- chore(DB): import pending files

## 2024-12-04
- fix(DB/SAI): Swiftmane Waypoint ReactState (#20833)

## 2024-12-03
- request(git): Update .gitignore (#20748)
- chore(DB): import pending files
- Fix(DB/Script): Halls of Stone, Brann escort (#20312)
- fix(DB/Conditions): 'Zeth'Gor Must Burn!' setting the sky on fire (#20447)
- fix(Scripts/ZulAman): Overpower spell cooldown (#20828)

## 2024-12-02
- chore(DB): import pending files
- fix (DB/Loot) Old Hillsbrad Foothills guards should not skinnable (#20818)
- chore(DB): import pending files
- Fix(DB/SAI) - Quest: "Escape from Silverbrook" [WotLK] (#20211)
- chore(DB): import pending files
- fix(DB/Creature) - Eydis Darkbane no longer stuck under the ground (#20813)
- feat(Core/Unit): Implement GetCompanionPet() helper (#20819)
- chore(DB): import pending files
- fix(DB/Loot): Critters are not skinnable (#20817)
- fix(Tools/MapExtractor) Update MPQ patch iterator to also load patch files 4 through 9 (#20815)
- refactor(Scripts/UtgardeKeep): Modernize Prince Keleseth script (#20806)
- feat(Core/Scripting): Implement SetAutoAttackAllowed() to disable aut… (#20805)
- chore(DB): import pending files
- fix(DB/Quest) - Remove breadcrumb quest from The Crown of Will (2/5) (#20814)
- chore(DB): import pending files
- fix(DB/Gameobject): Sniffed Values for 'Log Pile' spawns (#20812)

## 2024-12-01
- chore(DB): import pending files
- fix(DB/Quest) - Add the missing NPC Starters for Regthar Deathgate (#20762)
- refactor(Apps/Startup): replace 'set logging on` command with 'set logging enabled on' (#20778)
- fix(Core/Pet): Remove unnecessary Pet Class reassignments (#20614)
- fix(Core/Vmaps): Do not ignore model rotation when calculating liquid level (#20760)
- fix(Core/Players): don't set full heath/mana/rage while Dead (#20723)
- chore(Scripts/Karazhan): Remove unused variables (#20810)
- fix(Scripts/ZulAman): Fix Zuljin targetting players during eagle phase (#20808)
- fix(Scripts/ZulAman): Delay static disruption by 3s after storm (#20809)
- feat(Core/SAI): Add pet variable to SMART_TARGET_INVOKER_PARTY (#20804)
- chore(DB): import pending files
- fix(Scripts/ZulAman): eagle gauntlet (#20719)
- refactor(Core/Spells): Add helpers for HasAuraType (#20802)
- chore(DB): import pending files
- refactor(Scripts/VioletHold): Move all spells to spelldifficul… (#20796)
- fix(Core/Spells): Logic misstake for spells that can be cast on dead … (#20800)
- fix(Scripts/Commands) fix formatting in server debug (#20801)
- chore(DB): import pending files
- fix(DB/Creature) Scarlet Infantrymen. (#20768)
- Merge pull request #30 from noisiver/update-character-online
- Merge pull request #29 from Raz0r1337/Playerbot

## 2024-11-30
- refactor(Scripts/UtgardeKeep): Upgrade scripts to new register method (#20795)

## 2024-12-01
- fix(Script/Commands): tele add should only check exact match (#20785)

## 2024-11-30
- chore(DB): import pending files
- fix(DB/Creature): Fix Zul'jin formations (#20781)
- refactor(Scripts/TheNexus): Update Command Kolurg script (#20783)
- fix(Scripts/ZulAman): Hex Lord Malacrass shouldn't use previous class… (#20784)
- fix(Core/Spells): Resolve invalid spell casts on dead players when the cast is valid. (#20712)
- fix(Scripts/ZulAman): Reset threat after Zuljin does his phase transi… (#20782)
- Add a new statement to update character online by guid
- fix(Scripts/ZulAman): Fix Vortex not following players and also spell… (#20780)
- fix(Core/Database): prevent crash due to special chars in branch name (#20776)
- chore(DB): import pending files
- fix(DB/Gameobject): Sniffed values for 'Lunar Festival' spawns (#20769)
- fix(DB/Gameobject): Sniffed Values for 'Dwarf Hero / Gnome Hero' spawns (#20779)
- chore(DB): import pending files
- fix(Core/LootMgr): add startup error for unsupported reference minCou… (#20725)
- chore(DB): import pending files
- fix(DB/Quest) - Remove the wrong prerequisite Escape from Skettis and Hungry Nether Rays (#20753)

## 2024-11-29
- fix(Scripts/ZulAman): Fix Soul Siphon visual effect (#20765)
- Update worldserver.conf.dist
- fix(Scripts/ZulAman): Halazzi Lynx Ability Timers (#20761)

## 2024-11-28
- fix(Scripts/ZulAman): Hex Lord Malacrass' Drain Power Timer (#20754)

## 2024-11-27
- chore(DB): import pending files
- fix(DB/item_template): add flag CU_DURATION_REAL_TIME to Pilgrim's Bo… (#20756)
- chore(DB): import pending files
- fix(DB/Creature): Scarlet Miners and Cars don't follow a path. (#20701)
- chore(DB): import pending files
- Fix(DB/Spawn/WP) Scarlet Medics. (#20738)

## 2024-11-26
- chore(DB): import pending files
- Fix(DB/Spawn/WP) Scarlet Captains. (#20720)
- chore(DB): import pending files
- fix(DB/Spells): Malacrass Drain Power should stack from different cas… (#20749)
- feat(Core/Spells): Allow modifying MiscValues during cast (#20731)
- chore(DB): import pending files
- fix(DB/Creature) - Adds "Disarm" Immunity to Boss: Nalorakk [Zul'Aman] (#20746)

## 2024-11-25
- Merge branch 'master' into Playerbot
- chore(DB): import pending files
- fix(DB/Creature): Taunt Immunity to Boss: "Hex Lord Malacrass" (Zul'aman) (#20737)
- chore(DB): import pending files
- fix(DB/SAI): Fix Grimtotem Raider using net under crowd control effects (#20733)
- fix(Scripts/ZulAman): Fix Malacrass not using Slice and Dice (#20735)
- refactor(Scripts/Nexus): Update creature scripts to new register method (#20728)
- fix(Scripts/Events): Earning Spirit of Sharing should remove the othe… (#20732)

## 2024-11-24
- fix(Scripts/MagisterTerrace): Fix Selin's crystal drain being interru… (#20727)
- fix(Scripts/ZulAman): Fix Berserk crash and Corrupted Totems not atta… (#20726)
- chore(DB): import pending files

## 2024-11-25
- fix(Scripts/Spell): Added random whispers of the Death Knight Newbie Village Lich King (#19006)

## 2024-11-24
- chore(DB): import pending files
- feat(Core/SmartAI): add startup error for non existent SmartAI entries (#20694)
- chore(DB/Spells): Add missing Charm of the Bloodletter gender (#20724)
- refactor(Core): fix few static analysis (#20566)
- chore(DB): import pending files
- fix(DB/Spell): Correct gender requirement for ZA charm spells (#20722)
- chore(DB): import pending files
- fix(DB/SAI): Fix Disciple of Naralex despawning if talked while in co… (#20718)
- fix(Scripts/ZulAman): Dont cast Gust of Wind if about to start Electr… (#20717)
- fix(Scripts/ZulAman): remove cast transfigure when going into lynx (#20716)
- feat(Core/Scripting): Implement TaskScheduler GetNextGroupOccurrence() (#20714)
- chore(DB): import pending files
- fix(Scripts/ZulAman): Harrison Jones gong event RP with taskscheduler (#20713)
- refactor(Deps/mysqllite): Nuke it (#20710)
- fix(Scripts/ZulAman): Despawn Zuljin spirits shortly after death (#20711)
- fix(Scripts/ZulAman): Nalorakk in Bearform should not be attacking wi… (#20707)
- fix(Scripts/ZulAman): Fix Amani Hatcher behaviour (#20687)
- chore(DB): import pending files
- fix(DB/Conditions): Fix Jan'lai not hatching all eggs (#20686)
- fix(Scripts/Zulaman): Halazzi double scheduling of lynx abilties in the first phase 1 (#20708)
- chore(DB): import pending files
- fix(DB/Creature): Adds "Disarm" Mechanic Flag Immunity to Halazzi  (#20696)
- fix(DB/Creature): add spawns Eagle Trash Aggro Trigger (#20693)

## 2024-11-23
- chore(DB): import pending files
- fix(DB/Conditions): add Jan'alai's Summon Hatchers implicit target entry (#20692)
- fix(Core/Creature): Don't call reset if still in combat (#20675)
- chore(DB): import pending files
- fix(DB/Creature) Removal of Turkeys outside of the expected zones. (#20685)

## 2024-11-22
- chore(DB): import pending files
- fix(DB/Spells): Amani Hatchling Flame Buffet should stack from differ… (#20668)
- fix(Core/Creature): Set RespawnTime before AI Reset (#20684)
- chore(DB): import pending files
- fix(DB/Creature): Boneschewer removal of Distract immuninty (#20670)
- chore(DB): import pending files
- fix(DB/Quest): Makes a bunch of "mandatory" quests into "optional" 2.0 (#20671)
- chore(DB): import pending files

## 2024-11-21
- fix(DB/Loot): Malacrass should drop 2-3 pieces of loot (#20674)
- chore(DB): import pending files

## 2024-11-22
- fix(DB/pickpocketloot): add missing pickpocketloot (#20672)

## 2024-11-21
- chore(DB): import pending files
- fix(DB/Quest) - Makes a bunch of "mandatory" quests into "optional" (#20610)
- chore(DB): import pending files
- fix(DB/Loot): First 4 Zul'Aman bosses should only drop 1 item (#20666)
- fix(Scripts/ZulAman): Jan'alai eggs should not respawn during encounter (#20664)
- fix(Scripts/ZulAman): Correct gate ids (#20665)

## 2024-11-20
- refactor(Scripts/MagistersTerrace): Felblood Kael'thas (#20642)
- fix(Scripts/ZulAman): Hexlord: missing update to last commit (#20663)
- fix(Scripts/ZulAman): Fix Narolakk Mangle timer and Bear phase not la… (#20648)
- fix(Scripts/ZulAman): Fix Halazzi lynx not moving on spawn (#20649)
- fix(Scripts/ZulAman): Remove Zul'jin Electrical Storm on phase change (#20651)
- fix(Scripts/ZulAman): Fix Malacrass not casting correct class abilities (#20653)
- fix(Scripts/ZulAman): Fix Janalai Enrage/Berserk behaviour (#20662)
- chore(DB): import pending files
- fix(DB/Creature): Jan'alai taunt immunity (#20660)
- chore(DB): import pending files
- fix(Scripts/ZulAman): Halazzi Phases (#20650)
- chore(DB): import pending files
- fix(DB/Skinning): add missing skinloot 2/4 (#20644)
- fix(DB/skinning): missing skinloot 4/4 (#20646)
- fix(DB/Skinning): add missing skinloot 3/4  (#20645)
- fix(DB/skinning): add missing skinning loot 1/4 (#20643)
- chore(DB): import pending files
- feat(Core/SmartAI): introduce new `SMART_EVENT_IS_IN_MELEE_RANGE` (#20575)
- chore(DB): import pending files
- fix(DB/Conditions): Mana Remnants can be used only near Crystal Wards (#20647)

## 2024-11-19
- chore(DB): import pending files
- fix(DB/Creature): Remove Amani Bear Mounts from Zul'Aman. (#20641)
- chore(DB): import pending files
- fix(Scripts/Item): Multiphase Goggles not showing disturbances on minimap (#20446)
- chore(DB): import pending files
- fix(DB/Conditions): Ur'dan require quest to buy stardust (#20639)
- chore(DB): import pending files
- fix(DB/Spawn) - Drywallow Daggermaw under the map (#20621)
- fix(Scripts/ZulAman): Restore hatcher side switch (#20633)
- fix(Scripts/ZulAman): Fix Gust of Wind targetting tanks and eagles no… (#20632)

## 2024-11-18
- refactor(Scripts/MagistersTerrace): refactor Selin Fireheart (#20604)
- fix(Scripts/TheEye): Advisors add Sanguinar's Bellowing Roar (#20620)
- Merge pull request #27 from hermensbas/feature/alignment_core_data_folder
- chore(DB): import pending files
- fix(DB/SAI): Fix Sunblade Protector behaviour (#20598)
- fix(Scripts/ZulAman): Fix Janalai berserk (#20612)
- fix(Scripts/ZulAman): Narolakk dont engage after wave dies and attack… (#20615)
- chore(DB): import pending files
- fix(DB/Quest) - Vital Supplies [1477] and Report to Mountaineer Rockgar [468] are now Optional (#20608)

## 2024-11-17
- refactor(Scripts/MagisterTerrace): Update Priestess Delrissa (#20611)
- chore(DB): import pending files
- fix(DB/Creature): Zul'jin and Akil'zon should be taunt immune (#20609)
- chore(DB): import pending files
- Fix(DB/Spawn) Silt Crawlers under the landscape. (#20600)
- refactor(Scripts/SunwellPlateau): Update Felmyst script (#20602)
- refactor(Scripts/ZulGurub): Modernize Gahzranka script (#20603)
- chore(DB): import pending files
- fix(DB/Quest): Morgan Stern [1260] not required for 1204 (#20579)

## 2024-11-16
- placed sql into the data folder as core/module describes
- fix(Core/Player): properly update m_usedTalentCount (#20232)
- refactor(Scripts/Naxxramas): Modernize Anubrekhan script (#20596)
- chore(DB): import pending files
- fix(DB/Creature) - Darkfang Venomspitter under the map (#20597)
- chore(DB): import pending files
- refactor(Scripts/ZulAman): Move Amani Hatchling to SAI (#20589)
- chore(DB): import pending files
- fix(Core/Spells): implicit target selection for chain spells that should ignore crowd controlled targets (#20068)
- fix(DB/Creature): Sniffed Values for 'Lunar - Misc' spawns (#20593)
- refactor(Scripts/SunwellPlateau): Update Kalecgos script (#20588)
- refactor(Scripts/SunwellPlateau): Modernize Kil'jaeden script (#20583)
- chore(DB): import pending files
- fix(DB/Creature): M'uru should not reposition in combat (#20587)
- chore(DB): import pending files
- Fix(SQL/SAI): dawnblade marksman distance (#20543)
- refactor(Scripts/SunwellPlateau): Move summons to the new summon data… (#20586)
- Merge branch 'master' into Playerbot

## 2024-11-15
- fix(conf/worldserver): add Logger.sql.updates option (#20578)
- chore(DB): import pending files
- fix(DB/Gameobject): Sniffed Values for 'The Dark Portal and the Fall … (#20576)
- fix(DB/Creature): Sniffed Values for 'Lunar - Elders' spawns (#20581)
- feat(Core/Instances): Implement SummonData (#20582)
- chore(DB): import pending files
- Fix(DB/creature_template): Fix quest 12028 - Spiritual Insight (#20376)
- fix(Scripts/ZulAman): Update Malacrass adds spawn positions (#20580)
- fix(Scripts/TheEye): Fix Al'ar berserk timer (#20572)
- chore(DB): import pending files
- chore(DB): move 2023 update files (#20470)
- chore(DB): import pending files
- Fix(DB/SAI) Stonard talking to the NPCs in the refuge camp (#20301)
- fix(Scripts/ZulAman): Save Massive Gate state to DB (#20568)
- fix(Core/Spell): EffectQuestComplete, set quest to rewarded instead of complete (#20358)
- fixup(Scripts/TheEye): spawn Kaelthas' advisors with full hp (#20573)

## 2024-11-14
- chore(DB): import pending files
- fix(DB/SAI): Remove SAI to set unselectable flag from Sunblade Protectors (#20563)
- fix(Scripts/ZulAman): Despawn Harisson Jones after he "dies" (#20565)
- feat(Core/Scripting): Add hook during command security evaluation. (#20564)
- chore(DB): import pending files
- fix(Scripts/Spells): Spell school reflectors should have failure chan… (#20560)
- chore(DB): import pending files
- fix(DB/SAI): Correct Dawnblade Summoner timers and combat movement (#20562)
- chore(DB): import pending files
- fix(Scripts/TheEye): Kael'thas advisors, refactor and RP (#20188)
- feat(Core/Scripting): Add hook for applying weapon damage (#20350)
- fix(Core/Spells): Fix Lay on Hands healing bypassing Cyclone (#20552)
- chore(Scripts/ZulAman): Update Akilzon to new register method (#20556)
- chore(DB): import pending files
- fix(Core/Instance): Save persistent data to DB on updates (#20555)
- refactor(Scripts/SunwellPlateau): Modernize Muru script (#20551)

## 2024-11-13
- fix(Scripts/ZulAman): Permbind players when using the gong (#20554)

## 2024-11-14
- chore(DB): import pending files

## 2024-11-13
- fix(Scripts/ZulAman): Remove Eletrical Storm hacks (#20553)
- fix(Scripts/TheEye): Fix Wrath of the Astromancer's original caster (#20549)
- chore(DB): import pending files

## 2024-11-14
- Fix(DB/SAI) Added dialogue and emotes for Creature (19316). (#20348)

## 2024-11-13
- chore(DB): import pending files

## 2024-11-14
- Fix(Sql/Creature): Correct felguard annihilator ids (#20435)

## 2024-11-13
- fix(Core/Player): Nerfing Heirloom Weapons Damage (#20357)
- chore(DB): import pending files
- fix(Scripts/ZulAman): speed up gong event (#20547)
- refactor(Scripts/SunwellPlateau): Update Brutallus script (#20548)
- chore(DB): import pending files
- fix(DB/gameobject): Wrong faction banners while event 20 running. (#20539)
- chore(DB): import pending files
- fix(DB/Tele): Updated for Wrath of the Lich King (#20265)
- refactor(src/server/game): optimise imports (#20541)
- refactor(src/server/scripts): remove unused imports (#20540)

## 2024-11-12
- fix(Scripts/Commands): Fix crash when using npc set origin faction wi… (#20536)
- chore(DB): import pending files
- fix(DB/Gameobject): Sniffed Values for 'Zul' Aman Misc (2)' spawns (#20533)
- refactor(Scripts/SunwellPlateau): Modernize instance script (#20519)
- fix(Core/Spells): Jump Speed Calculations (#20479)
- chore(DB): import pending files
- feat(Core/WorldState): improved WorldState scripting (#20141)
- fix(Scripts/ZulAman): Set Akilzon encounter in progress when engaged (#20531)
- chore(DB): import pending files
- fix(DB/Gameobject): Sniffed Values for 'Zul' Aman Misc' spawns (#20526)

## 2024-11-11
- fix(Build/Deps): Increase minimal Boost versions and remove old compatibilities (#20287)
- chore(DB): import pending files
- fix(DB/Spell): Link triggered Unstable flask effects to flask aura and proper area. (#20353)
- fix(Scripts/BoreanTundra): make Escape from the Winterfin Caverns group completable (#20359)
- chore(DB): import pending files
- fix(DB/Creature): Adjust Harrison Jones's movement type. (#20523)
- chore(DB): import pending files
- fix(DB/Creature): Fix Hexlord Malacrass spawn position and remove Har… (#20520)
- refactor(Scripts/SunwellPlateau): Modernize Eredar Twins script (#20516)
- chore(DB): import pending files
- fix(Scripts/ZulAman): Amani Hatchers should hatch eggs at increasing … (#20497)
- chore(DB): import pending files
- fix(DB/Loot): Humbert's set (#20451)
- refactor(Scripts/SunwellPlateau): Refactor areatriggers to OnlyOnceAr… (#20515)
- feat(Core/Scripting): Implement SetInvincibility() to prevent creatur… (#20508)

## 2024-11-10
- chore(DB): import pending files
- refactor(Scripts/MagisterTerrace): Move Kalecgos script to SAI (#20495)
- chore(DB): import pending files
- fix(Scripts/MagisterTerrace): Add all spells to SpellDifficulty dbc (#20502)
- chore(DB): import pending files
- fix(Scripts/SSC): Improve Tainted Elemental combat behaviour (#20505)
- refactor(Scripts/SWP): Update creature scripts to new register  method (#20503)
- fix(Scripts/Commands): Remove Spirit of Redemption when using Revive … (#20492)
- chore(DB): import pending files
- refactor(Scripts/ZulAman): Move Spirit of the Lynx to SAI (#20498)
- fix(Scripts/Spells): Limit Cyclone (39594) to 4 targets (#20506)
- fix(Scripts/SSC): Fix Leotheras running in melee range in demon phase (#20507)
- fix(Scripts/ZulAman): Fix crash in Nalorakk script (#20499)
- chore(Core/Creature): Fix typo (#20510)
- chore(DB): import pending files
- fix(Scripts/ZulAman): Fix Akilzon not spawning eagles and update script (#20493)
- fix(Scripts/ZulAman): Fix Sacrifice timers not updating after latest … (#20490)
- fix(Core/SAI): Don't try to reposition Rooted inhabit type creatures (#20504)

## 2024-11-09
- chore(DB): import pending files
- refactor(Scripts/ZulAman): Move Jan'alai Fire Bomb to SAI (#20496)
- chore(DB): import pending files
- fix(Scripts/ZulAman): Move Harrison Jones spawn to DB (#20491)
- chore(DB): import pending files
- fix(DB/Creature): Magma Elemental interrupt (#20458)
- chore(DB): import pending files

## 2024-11-08
- refactor(Scripts/ZA): Update Zul'jin (#20456)
- refactor(src/tools): remove unused imports (#20487)
- chore(DB): import pending files
- fix(DB/SAI): Arzeth the Merciless not moving on respawn (#20442)
- fix(Scripts/MagisterTerrace): Kael'thas' Arcane Spheres & Phoenix should despawn (#20481)
- Merge branch 'master' into Playerbot

## 2024-11-07
- chore(DB): import pending files
- fix(DB/Gameobject): Sniffed Values for 'Winter Veil' spawns (#20440)
- fix(DB/Gameobject): Sniffed Values for 'Zul' Aman doors' spawns (#20478)
- chore(DB): import pending files
- fix(DB/Creature): Fix Zul'jin spawn position (#20477)
- chore(DB): import pending files
- fix(DB/Procs): Ephemeral Snowflake having wrong icd (#20469)
- chore(DB): import pending files
- fix(DB/Creature): Sniffed Values for 'Winter Veil Gifts' spawns (#20472)
- fix(DB/Gameobject): Sniffed Values for 'Zul' Aman cages' spawns (#20474)
- fix(DB/Gameobject): Sniffed Values for 'Sitting Skeleton 04' spawns (#20473)

## 2024-11-06
- chore(DB): import pending files
- fix(DB/Creature): Sniffed Values for 'Winter Veil' spawns (#20466)
- chore(DB): import pending files
- fix(DB/Creature): Darting Hatchling missing periodic aura (#20459)
- fix(Core/Unit): Fix crash during Judgement of Light/Wisdom proc (#20467)
- fix(Scripts/AQ20): Set General Rajaxx's Thundercrash to min 100 dmg (#20461)
- chore(DB): import pending files
- fix(DB/Gameobject): Sniffed Values for 'Lauranna's Guide to Zangarmar… (#20464)
- chore(DB): import pending files
- fix(DB/Gameobject): Sniffed Values for 'Winter Veil Gifts' spawns (#20462)
- chore(DB): import pending files
- fix(Scripts/ZG): Poisonous Blood not being removed after Blood Siphon (#20463)
- chore(DB): import pending files
- fix(Scripts/Item): Obsidian Armor & Frostfire Regalia Set (#20453)
- chore(DB): import pending files
- fix(DB/Quests): 'Strange Energy' having prerequisites (#20444)
- chore(DB): import pending files

## 2024-11-05
- fix(DB/Spell): Add spell effect data for Shattered Sun transform auras. (#20433)

## 2024-11-06
- fix(DB/Gameobject): Sniffed Values for 'Winter Veil' spawns (part 2)  (#20452)
- fix(Core/Spells): 'Black Qiraji Battle Tank' being removed on map change/teleport (#20455)

## 2024-11-05
- chore(DB): import pending files
- fix(DB/Event): 'New Year Celebrations!' should show only on new … (#20450)
- fix(CI/SQL import): don't use octal (#20449)
- refactor(Scripts/ZulAman): refactor set data to instance boss states and refactor Hex Lord Malacrass (#20206)
- chore(DB): import pending files
- fix(DB/Gameobject): Sniffed Values for 'Xmas*' spawns (#20434)

## 2024-11-04
- Fix(Sql/npc_vendor): Elixir of Major Defense Recipe incrtime (#20436)
- fix(Core/Spells): Luffa removing bleeds over level 60 (#20411)
- fix(Scripts/Kalimdor): Prophecy of Akida not giving group credit (#20437)
- chore(DB): import pending files
- Fix(SQL): deactivated sunblade protectors is not linked properly (#20404)
- chore(DB): import pending files
- Fix(SQL): Unleashed Hellion's Rain of Fire (#20421)

## 2024-11-03
- fix(Core/Spells): Adjust logic for removing/applying auras related to areas. (#20299)

## 2024-11-04
- chore(DB): import pending files

## 2024-11-03
- fix(Core/Unit): Only allow Judgement of Light/Wisdom to proc for targets friendly to caster. (#20374)

## 2024-11-04
- fix(DB/Formations):  Pack near the first scout is not linked properly (#20403)
- fix(DB/Formations): First Blood Elf packs are not linked properly. (#20405)
- chore(DB): import pending files
- fix(DB/Custom): Spotlight aura stacking (#20429)
- fix(DB/Creature): Sniffed Values for 'Hallow's End' spawns (#20426)
- fix(DB/Gameobject): Sniffed Values for 'Lights' spawns (#20427)
- fix(DB/Gameobject): Sniffed Values for 'Christmas Tree' spawns (#20428)
- chore(DB): import pending files
- fix(DB/Procs): Eye of Magtheridon not procing on miss (#20432)

## 2024-11-03
- fix(Core/Movement): remove unecessary reset() (#20419)
- chore(DB): import pending files
- Fix(DB/Creature) Add Grikkin Copperspring spawn point. (#20393)
- chore(DB): import pending files
- fix(DB/Creature): Sniffed Values for 'Pilgrim's Bounty' spawns (#20422)

## 2024-11-02
- fix(Spells/SpellScript): fix CI, rename the log for Validate (#20418)
- fixup(Scripts/CrusaderColiseum)spellscripts (#20417)
- chore(DB): import pending files
- fix(DB/Loot): Add Weighted Jack-o'-Lanterns to Crudely Wrapped Gift. (#20332)
- chore(DB): import pending files
- fix(DB/gameobject_queststarter): Add queststarter records for GameObject 142122 (#20293)
- fix(Scripts/Kalimdor): Cavern of Time custodian escort quest group completion (#20355)
- chore(DB): import pending files
- fix(Scripts/Events): Hallow's End Headless Horsemen fly intro (#20366)
- fix(Scripts/Netherstorm): make "Mark V is Alive!" group completable  (#20360)
- chore(DB): import pending files
- fix(DB/Gameobject): Sniffed Values for "Pilgrim's Bounty" spawns (#20406)
- fix(Docker): Updated env.docker (#20383)

## 2024-11-01
- fix(Scripts/Outland): Fix crash in dragonmaw_race_npc by refreshing players pointer in lambda function. (#20333)
- chore(DB): import pending files
- feat(DB): Expand `game_event_npc_vendor` key to include event entry. (#20398)
- chore(DB): import pending files
- refactor(Scripts/EasternKingdoms): spell scripts use registry macros (#20399)
- refactor(scripts/CrusadersColiseum): spell scripts use registry macros  (#20400)
- chore(DB): import pending files
- refactor(Scripts/Northrend): spell scripts use registry macros  (#20401)
- chore(DB): import pending files
- fix(DB/Creature): Remove stunned flag from Syndicate Thiefs (#20396)
- fix(Core/Spells): Fix Gurtogg Bloodboil applying Acid Wound to himself (#20394)
- fix(Scripts/BlackTemple): Parasitic Shadowfiends only target players (#20395)
- fix(Core/Movement): fix a small memory leak in RandomMovementGenerator (#20258)
- refactor(src/common

## 2024-10-31
- chore(DB): import pending files
- fix(DB/Creature): Shadow Demon knockback immunity (#20368)
- refactor(src/common
- chore(DB): import pending files
- fix(DB/Creature): Add auras to Sunblade Scout. (#20375)

## 2024-10-30
- chore(DB): import pending files
- fix(DB/SAI): Replace bad spell ID for Sunblade Vindicator's Mortal Strike. (#20365)
- Merge branch 'master' into Playerbot
- fix(Docker): Fix env name for data volume (#20337)

## 2024-10-29
- fix(Script/BlackTemple): Spawn Shadow Demons 30s into phase 4 (#20335)
- fix(Core/BattlegroundAV): Add Hallow's End decorations to Alterac Valley (#20317)
- fix(Scripts/Icecrown Citadel): Correct pipe pathing for Vengeful Fles… (#20048)

## 2024-10-28
- chore(DB): import pending files
- Fix(DB/Creature) Feral Dragonhawk Hatchling are skinnable. (#20330)
- chore(DB): import pending files
- fix(DB/game_event): Fix Kalu'ak Fishing Derby starting times (#20290)
- refactor(src/server/database
- chore(DB): import pending files
- fix(DB): Adjust faction change swap for Sergeant's Heavy back. (#20319)

## 2024-10-27
- chore(DB): import pending files
- fix(DB/Gameobject): final cleanup of Hallow's End decorations (#20318)
- refactor(src/server/game/*): remove unused imports (big part 3) (#20315)
- chore(DB): import pending files
- fix(DB/Gameobject): Sniffed Values for 'Laying Skeleton 03' spawns (#20308)
- fix(DB/Gameobject): Sniffed Values for 'Sitting Skeleton 01' spawns (#20305)
- fix(DB/Gameobject): Sniffed Values for 'Huge Sitting Skeleton 03' spawns (#20309)
- refactor(src/server/game/*): remove unused imports (big part 1) (#20310)
- refactor(src/server/game/*): remove unused imports (big part 2) (#20311)
- chore(DB): import pending files

## 2024-10-26
- fix(DB/Creature): Add STATE_WORK_MINING emote to certain iron rune laborers (#20297)
- chore(DB): import pending files
- fix(DB/Gameobject): Sniffed Values for 'Laying Skeleton 02' spawns (#20307)
- chore(DB): import pending files
- fix(DB/Gameobject): Sniffed Values for 'Hallow's End - Misc' spawns (#20302)
- chore(DB): import pending files
- fix(DB/creature_loot_template): Removing Dalaran Wizard's Robe from Witchwing harpies (#20291)
- chore(DB): import pending files
- fix(DB/Gameobject): Sniffed Values for 'HangingSkullLight0x' spawns (#20300)
- refactor(Scripts/ZulAman): refactor Jan'alai (#20195)

## 2024-10-25
- chore(DB): import pending files
- fix(DB/Gameobject): Sniffed Values for 'Candy Bucket' spawns (#20295)
- fix(Scripts/BlackTemple): Prevent further code execution if Illidan e… (#20292)

## 2024-10-24
- chore(DB): import pending files
- fix(DB/Creature): Sniffed Values for 'Headless Horseman - Fire (DND)'… (#20288)
- fix(Core/BG): Fix double method call on removing a player (#20156)
- fix(Scripts/BlackTemple): Fix Illidan Demon Phase being delayed indef… (#20286)
- fix(Scripts/BlackTemple): Prevent Illidan transformation during cutscene (#20271)
- fix(Core/SAI): rooted check blocks vehicles from casting quest credit (#20283)
- chore(DB): import pending files
- fix(Scripts/BlackTemple): Apply Shadow Prison spell immunities (#20272)
- fix(DB/SmartScript): Fix Illidan Shadow Demons not killing their targets (#20273)
- chore(DB): import pending files
- fix(DB/Gameobject): Sniffed Values for 'Apple Bob' spawns (#20279)
- chore(DB): import pending files
- fix(DB/Gameobject): Sniffed Values for 'Water Barrel' spawns (#20280)
- fix(DB/Gameobject): Sniffed Values for 'Water Bucket(s)' spawns (#20281)
- fix(DB/Gameobject): Sniffed Values for 'Fire Effigy' spawns (#20282)

## 2024-10-23
- fix(Scripts/BlackTemple): Reset Illidan combat movement (#20276)
- refactor(Core/Unit): cleanup header file - part 3 (#20072)

## 2024-10-22
- chore(DB): import pending files
- fix(DB/Gameobject): Sniffed Values for 'Bat01/Bat02' spawns (#20255)
- fix(Core/SmartAI) : use explicit stack DS for ProcessAction instead of recursion (#16739)

## 2024-10-21
- fix(Scripts/BlackTemple): Properly randomize Illidan initial Eye Beam and order. (#20264)
- fix(Scripts/BlackTemple): Randomize Eye Beam target position. (#20262)
- chore(DB): import pending files
- fix(DB/Gameobject): Sniffed Values for 'G_HangingSkeleton_01' spawns (#20251)
- fix(DB/Gameobject): Sniffed Values for 'G_Ghost_01' spawns (#20252)
- fix(DB/Gameobject): Sniffed Values for 'SkullCandle01' spawns (#20253)
- fix(DB/Gameobject): Sniffed Values for 'Skull 01' spawns (#20254)
- Merge branch 'master' into Playerbot

## 2024-10-20
- chore(DB): import pending files
- fix(DB/Gameobject): Sniffed Values for 'G_Pumpkin*' spawns (#20248)
- fix(DB/Gameobject): Sniffed Values for 'CandleBlack01' spawns (#20249)
- fix(DB/Gameobject): Sniffed Values for 'G_Witch*' spawns (#20247)
- Update README.md - update build status logos and links (#20228)

## 2024-10-19
- Revert "fix(Core/Spells): SPELL_ATTR1_IMMUNITY_PURGES_EFFECT should not remov…" (#20245)
- chore(DB): import pending files
- fix(DB/Quest): fix Standards and Practices Quest spawns (#20243)

## 2024-10-18
- fix(Core/CharmInfo): Adjust how spells are given to charmed creatures. (#20227)
- fix(Core/Spells): SPELL_ATTR1_IMMUNITY_PURGES_EFFECT should not remov… (#20032)

## 2024-10-17
- chore(DB): import pending files

## 2024-10-18
- Fix(DB) Scarlet Commanders and Crusaders group and waypoints. (#20213)

## 2024-10-17
- chore(Core): Correct typo of `Suppress`. (#20229)

## 2024-10-16
- chore(DB): import pending files
- fix(DB/Creature): Adjust various values of Magister's Terrace creatures. (#20223)
- fix(Core/Items): Don't remove all owned auras on removing enchantments. (#20220)
- chore(DB): import pending files
- fix(DB/Creature): Adjust various values of Zul'Aman creatures. (#20222)
- chore(DB): import pending files
- Fix(DB) Scarlet Preachers phase 2 correction. (#20212)
- chore(DB): import pending files
- fix(DB/Creature): Sniffed Values for 'Oomailiq' spawns (#20221)

## 2024-10-15
- chore(DB): import pending files
- fix(DB/Creature): Adjust various values of Sunwell Plateau creatures. (#20218)
- fix(CI/Import SQL): reference previous pending update in header (#20219)
- chore(DB): import pending files
- Fix(DB) Preachers path. (#20202)
- chore(DB): import pending files
- Fix(DB) Resolve Stable Master Kitrik missing path. (#20210)

## 2024-10-14
- fix(CI): simplify ci-pending-sql.sh and make it safer (#20209)
- chore(DB): import pending files
- fix(DB): Fix importer part 2 (#20208)
- fix(DB): Fix importer (#20207)
- chore(DB): import pending files
- chore(DB): import pending files
- chore(DB): import pending files
- chore(DB): import pending files
- chore(DB): import pending files
- chore(DB): import pending files
- chore(DB): import pending files
- chore(DB): import pending files
- chore(DB): import pending files
- chore(DB): import pending files
- chore(DB): import pending files
- chore(DB): import pending files
- chore(DB): import pending files
- chore(DB): import pending files
- chore(DB): import pending files
- chore(DB): import pending files
- chore(DB): import pending files
- chore(DB): import pending files
- chore(DB): import pending files
- chore(DB): import pending files
- chore(DB): import pending files
- chore(DB): import pending files
- chore(DB): import pending files
- chore(DB): import pending files
- chore(DB): import pending files
- Fix(DB)Stable Master Kitrik adding path. (#20192)
- fix(DB/Gameobject): Sniffed Values for 'Draenethyst Mine Crystal' spawns (#20205)
- chore(DB): import pending files
- fix(DB/Creature): Sniffed Values for 'Raging Soul' spawns (#20204)
- chore(DB): import pending files
- fix(DB): Missing additional crashed flying machines gameobjects (#20197)
- chore(DB): import pending files

## 2024-10-13
- fix(DB/Creature): Illidari Council skip player damage req (#20198)
- fix(Scripts/BlackTemple): Clear events on evade (so he doesnt move wh… (#20199)
- fix(Scripts/BlackTemple): Fix Gathios not recasting Consecration (#20200)
- fix(Scripts/BlackTemple): Grant proper encounter credit for Illidari Council. (#20201)
- chore(DB): import pending files
- fix(DB/Creature): update Shandy's creature_text (#20180)
- chore(DB): import pending files
- fix(DB/Creature): Sniffed Values for 'Venture Co. Gemologist' spawns (#20189)
- chore(DB): import pending files
- Fix(DB/Script): Phase change for DK starter area Eye of Acherus and npcs. (#20170)
- chore(DB): import pending files
- refactor(Scripts/ZulAman): Move Hexlord adds to SAI (#20185)
- chore(DB): import pending files
- fix(DB/Quest): Assign proper quest starters for Brewfest souvenir quests. (#20105)

## 2024-10-12
- chore(DB): import pending files
- fix(cpp/db):  how to win friends and infleunce enemies missing dialogue (#20132)
- chore(DB): import pending files
- fix(Core/Spells):  supress caster procs for Siphon Life heal (#20175)
- Fix(DB/SAI) Into The realm of Shadows issues (#20152)
- fix(Scripts/BlackTemple): Ensure root state is cleared on wipes (#20183)
- fix(Scripts/BlackTemple): Flames should not charge players within 25y… (#20182)
- fix(Script/DeathKnight): A Special Surprise Npcs issues. (#20178)

## 2024-10-11
- chore(DB): import pending files
- fix(DB/Creature): Adjust Teron Gorefiend's model data. (#20181)
- chore(DB): import pending files
- fix(Scripts/BlackTemple): Remove Naj'entus Spines from players on engage. (#20176)
- fix(Scripts/BlackTemple): Adjust cast behavior for Supremus's charge. (#20173)
- fix(Core/Spells): Fix crash (#20179)
- fix(Core/SpellInfoCorrections): Add Arcane Missiles spell info correction. (#20165)
- chore(DB): import pending files
- fix(DB/Creature): Sniffed Values for 'Monstrous Kaliri Egg Trigger' s… (#20063)
- chore(DB): import pending files
- fix(SQL/smart_scripts) target in script 1436800 (#20151)
- fix(Scripts/ZulAman): Nalorakk can't able to trigger instance events when death (#19895)
- chore(DB): import pending files
- fix(Core/Vehicles): feat vehicle seat addon, vehicle enter/exit positions (#20082)

## 2024-10-10
- fix(Core/QuestHandler): Question marks not being shown (#20099)
- refactor(Core/Misc): Use emplace_back instead of push_back to avoid extra copy/m… (#20114)
- chore(DB): import pending files
- fix(DB/Creature): Adjust model probability for Whirling Blade trigger creatures. (#20177)
- fix(Scripts/BlackTemple): Add resets for enrage events with death. (#20174)
- fix(Scripts/BlackTemple): Adjust caster of Blaze spell. (#20172)
- Merge branch 'master' into Playerbot
- fix(Script): Fix npc following player after starting duel (#20161)

## 2024-10-09
- fix(Core/Scripts): Further improve the ScheduleHealthCheck() function (#20163)
- chore(DB): import pending files
- fix(DB/Spell): Remove Arcane Missile spell info overrides. (#20054)
- fix(Core/Unit): Add mana drain effect to Black Bow of the Betrayer. (#20155)

## 2024-10-08
- fix(Core/Unit):  add rage gain when attack is fully blocked, dodged or parried (#19377)
- chore(DB): import pending files
- fix(DB/Spell): Add armor ignore attribute to Shared Rule damage spell. (#20160)
- fix(Script/Mother Shahraz) Add new teleport points. (#20137)

## 2024-10-07
- fix(Core/Spell): Include damaging spells for starting combat. (#20154)
- fix(Core/CharmInfo): Add exception for Kil'jaeden dragon charm spells. (#20150)

## 2024-10-05
- fix(Scripts/Dragonblight): Fix Torturer Leclaft spamming abilities (#20130)
- fix(Scripts/BlackTemple): exclude off tank of the Azzinoth Flame's charge (#20133)
- Merge pull request #24 from liyunfan1223/fix_header_include

## 2024-10-04
- Fix header include for playerbots
- fix(Core/Unit): update death state before handling RemoveAllAurasOnDeath() (#20124)
- Merge branch 'master' into Playerbot
- chore(DB): import pending files
- fix(DB/Spell): Link triggered Shattrath flask effects to flask aura and proper area. (#20122)
- fix(Core/Items): Fix exploit where multiple auras could be applied from a single enchantment. (#20128)

## 2024-10-03
- fix(Scripts/BlackTemple): Reset Illidan threat with phase four. (#20125)
- chore(DB): import pending files

## 2024-10-02
- fix(DB/Creature): Adjust move type of various Black Temple creatures. (#20120)
- chore(DB): import pending files
- fix(DB/WailingCaverns): make Boahn cast snake form (#20119)
- chore(DB): import pending files
- fix(Creature/Model): Model probability change (#20062)
- fix(Scripts/TheBlackTemple): remove gossip option on Akama when Illidan is dead (#20118)

## 2024-10-01
- chore(DB): import pending files
- fix(DB/Gameobject): add gameobjects to transports (#20117)
- fix(Core/Unit): Flight Form riding crop, vehicle speed auras (#20079)
- chore(DB): import pending files
- fix(Scripts/TheBlackTemple): resetting behaviour in p1 for Shade of Akama (#20076)
- fix(Core/Spells): Restricted aura application prevention when immune to banish effects (e.g cyclone) (#20060)
- chore(DB): import pending files
- fix(DB/Creature): Icecrown Orgrim's Hammer and The Skybreaker map icons (#20104)
- refactor(src/server/game/Globals): remove unused imports (#20088)
- refactor(src/server/game/World): remove unused imports (#20090)
- refactor(src/server/game/Spells): remove unused imports (#20092)
- refactor(src/server/game/Chat): remove unused imports (#20093)
- refactor(src/server/game/Grids): remove unused imports (#20094)
- refactor(src/server/game/AI): remove unused imports (#20095)
- chore(DB): import pending files
- fix(DB/Creature): Adjust Flame of Azzinoth model data. (#20115)

## 2024-09-30
- fix(Core/GuardAI): crash when killer is null (#20100)

## 2024-09-29
- refactor(src/server/game/Entities): remove unused imports (#20096)
- refactor(src/server/game/Battle*): remove unused imports (#20097)
- refactor(src/server/game/Movement): remove unused imports (#20098)
- refactor(src/server/apps
- Merge branch 'master' into Playerbot
- feat(Core/BG): allow MinPlayersPerTeam override for low-levels (#20083)
- refactor(Scripts): remove unused imports (#20086)
- refactor(src/server/game/Handlers): remove unused imports (#20087)
- fix(Core/Battlefield): shapeshift aura removal from players on leaving arena or battleground (#20069)
- fix(Scripts/ICC): Fix Valkyr "teleportation" effect caused by movement desynchronization between server and client. (#20080)
- fix(CI/Codestyle): Fix codestyle CI error introduced with the new rule for ifs. (#20081)

## 2024-09-28
- fix(Core/Script) - Black Temple - Gurtogg Bloodboil - Bewildering Strike mechanics doesnt work as it should (#20074)
- chore(Apps/Codestyle): add a new check for if statements (#20073)
- chore(DB): import pending files
- fix(DB/Spells): Add extra craft chance for Super Healing Potion. (#20064)
- chore(DB): import pending files
- fix(DB/Creature): remove stun immunity from Coilfang Strider (#20071)
- fix(Script/BlackTemple): teleport position with fatal attraction (#19971)
- chore(DB): import pending files
- (DB/Creatures): fixup Dual Wield for creatures, remove some CREATURE_FLAG_EXTRA_USE_OFFHAND_ATTACK (#20061)

## 2024-09-27
- new BattlegroundDesertionTypes for hook OnBattlegroundDesertion (#20039)
- chore(DB): import pending files
- chore(DB/CreatureText) Translate text in city guards (#20034)

## 2024-09-26
- chore(DB): import pending files
- fix(DB/Creature): Add proper unit flags to Phantom Leotheras. (#20049)
- fix(Core/Unit): fix Dual Wield for more creatures... (#20047)

## 2024-09-25
- chore(DB): import pending files
- fix(DB/Creature): SSC - Leotheras the blind - Adds are not chained (#20023)
- fix(Scripts/Spells): Remove immunity application from Preparation buff (#20042)
- chore(DB): import pending files
- fix(Core/Unit): fix Dual Wield for more creatures, CREATURE_FLAG_EXTRA_USE_OFFHAND_ATTACK, creature disarm damage (#20015)
- chore(DB): import pending files
- refactor(SQL/Quest) Rescuing the Rescuers ID 11244 (#20030)
- chore(DB): import pending files
- fix(DB/Creature): Fix Illidan walking to waypoints instead of flying (#20035)
- fix(Scripts/BlackTemple): Correct the door announcement to only annou… (#20036)

## 2024-09-24
- fix(Core/Spells): Prevent aura application if the target is immune (#20031)
- chore(DB): import pending files
- fix(Scripts/TheEye): Kael'thas p5 transition, flight, MotionMaster:MoveTakeoff (#20005)
- fix(Core/Loot): Fix crash for round robin loot mode when solving quest item for offline loot owner. (#20033)
- chore(DB): import pending files
- fix(DB/Event): Love is in the Air event missing Love Boat vehicles 1 (#19987)

## 2024-09-23
- chore(DB): import pending files
- fix(DB/Creature Loot) - Update Eye and Hound Culuthas loot tables (#19706)
- refactor(Core/Database): improve abort messages for mysql errors (#20013)
- fix(Scripts/BlackTemple): Fix Fatal Attraction not being removed if t… (#20021)
- chore(DB): import pending files
- fix(Scripts/Quest): Fires Over Skettis (#19567)
- chore(DB): import pending files
- fix(DB/Quest) - Omit deprecated Pledge of Secrecy from Goblin and Gnome Engineering Questlines. (#19577)

## 2024-09-22
- chore(DB): import pending files
- fix(DB/Item): Buycount adjustment for Star's Lament and Star's Tear (#18887)
- fix(Core/Spells): Fix Fatal Attraction procing multiple times for eac… (#20014)
- Merge branch 'master' into Playerbot
- chore(DB): import pending files
- fix(DB/creature_text): (Pit of Saron, AzjolNerub) assign BroadcastTextId to creature_text (#18611)
- chore(DB): import pending files
- fix(DB/Creature): [Loot] Unyielding mobs low drop of Runecloth (#19910)
- chore(DB): import pending files
- fix(DB/quest_offer_reward): C'Thun's Legacy turnin dialogue (#19130)
- chore(DB): import pending files
- feat(Core/Items): Delete old item id from recovery item (#18332)

## 2024-09-21
- chore(DB): import pending files
- feat(Core/Commands): Add debug command for applying a spell cooldown. (#20004)
- fix(DB/Creature) Ebon Blade Commander Equipment (#19846)
- fix(Scripts/Commands): Prevent crash if you use doublequotes in go cr… (#20012)
- chore(Core/AllMapScript) Update structure (#19979)
- fix(Core/Object): do not add Object to Transport when summoned by a Vehicle (#19920)
- chore(Core/Misc): Some cleanup (#19970)
- chore(DB): import pending files
- fix(DB/ArgentTournament): Stabled Campaign Warhorse missing error message (#19926)
- fix(CI/macOS): Fix macOS CI dependency installation by updating macOS version. (#19997)

## 2024-09-20
- fix(apps/installer): fix Debian 12 build with mysql (#20003)
- chore(DB): import pending files
- Fix(db/creature) black temple   illidari assassin riposte ability missing (#19957)

## 2024-09-19
- fix(Core/Loot)  fix bug with loot (#19882)
- fix(Core/Spells): Resolve a case of triggered spells prolonging combat. (#19991)
- refactor(Deps/MySQL): Drop MariaDB and MySQL 5.7/8.1 and add MySQL 8.… (#19451)

## 2024-09-18
- fix(Scripts/BlackTemple): Flames of Azzinoth - Fix the charge logic (#19968)

## 2024-09-17
- Merge branch 'master' into Playerbot
- Revert "Revert "Merge branch 'master' into Playerbot""

## 2024-09-16
- chore(DB): import pending files
- fix(DB/Command): Add help values for various commands. (#19984)
- fix(Core/Spells): Revert triggered spell logic change. (#19983)

## 2024-09-15
- chore(DB): import pending files
- fix(Core/PlayerQuest): Introduce flag QUEST_SPECIAL_FLAGS_NO_LOREMAST… (#19962)
- chore(Core/Achievement): cleanup offline achievement (#19976)
- fix(Scripts/Commands): Fix level up achievements not being granted (#19969)
- fix(Scripts/BT): correct illidari council enrage timer (#19975)
- chore(DB): import pending files
- fix(Scripts/BlackTemple): Implement emotes when opening Najentus and … (#19946)
- fix(Scripts/BlackTemple): Parasitic Shadowfiends should not target pl… (#19944)
- Merge pull request #22 from manstfu/Playerbot

## 2024-09-14
- Updated with master branch
- fix(Core/Spells): Shadow demon - Allow to move while casting Paralyze (#19948)
- fix(Scripts/BlackTemple): fix blaze and flame bast casting for Flame of Azzinoth (#19967)
- Update PlayerQuest.cpp

## 2024-09-13
- fix(Scripts/BlackTemple): Fix variable not being set to true when Ak… (#19947)
- fix(Core/Creature): Add support for CREATURE_FLAG_EXTRA_NO_PARRY_HAST… (#19927)
- fix(Core/PlayerStorage): Equip OH, 2H, Titan's Grip weapon swapping  (#19884)
- Merge pull request #21 from liyunfan1223/revert_spell_crash
- Revert "Merge branch 'master' into Playerbot"
- fix(Battlegrounds/AlteracValley): Adding missing Tower Archers (#18746)

## 2024-09-12
- Fix continuous integration workflow
- Merge branch 'master' into Playerbot
- Revert "chore(Debug/Scripting): improve debug errors during the unloading scripts (#19643)" (#19951)
- refactor(Scripts/TempestKeep): remove an dev residual from Kael'Thas revamp (#19950)
- fix(Scripts/BlackTemple): Ajust Judgment timers and pass all the script to std::chrono (#19945)

## 2024-09-11
- fix(Core/Spell): Summoning Portal position (#19705)
- fix(Core/Spell): Refreshment Table position (#19704)
- fix(Core/Spells): Resolve a case of triggered spells prolonging combat. (#19819)
- chore: remove unused hooks (#19919)
- fix: default bgarenas visibility distance default value (#19938)
- refactor(Cote/Unit): cleanup - part2 (#19821)
- chore(DB): import pending files
- fix(DB/SAI): Missings spells for few creatures in Blade's Edge Mountains (#19617)
- fix(Scripts/UBRS): increase Drakkisath's conflagrate interval from 10s..13s to 18s..25s, avoiding near infinite CC chains (#19806)
- feat(ScriptMgr): add OnArenaStart hook (#19922)
- fix(Core/Pet): Control Infernal without enslave (#19784)
- chore(DB): import pending files
- fix(DB/Creature) Black Temple - Shadowmoon Blood Mages dont use Blood… (#19812)
- fix(Core/AI): Reduce movement leash extension interval. (#19923)

## 2024-09-09
- chore(DB): import pending files
- fix(Scripts/BlackTemple): Shade of Akama should despawn on evade and Akama despawns before dying (#19894)
- fix(Core/AI): creature leashing behavior. (#19897)

## 2024-09-08
- fix(Core/AI): Initialize movement leash timer to five seconds. (#19898)
- fix(Core/AI): Add back leash update. (#19916)
- feat(Battlegrounds): make it compatible with custom arena type (#18679)

## 2024-09-07
- fix(Scripts/ZulAman): Nalorakk sometimes not move when player close (#19893)
- fix(Scripts/BlackTemple): Gurtogg Bloodboil shouldnt cast bloodboil o… (#19886)
- fix(Scripts/BlackTemple): blade_of_azzinoth...and Possible crash (#19891)
- Merge branch 'master' into Playerbot
- fix(Scripts/Commands): .gps formatting transport offset (#19890)
- fix(Core/AI): Creature SetInCombatState Leashing. (#19889)

## 2024-09-06
- fix(Scripts/BlackTemple): Remove Shear from Illidan following wrath p… (#19881)

## 2024-09-07
- fix(Scripts/Commands): .gps formatting transport offset (#19888)

## 2024-09-06
- fix(Core/Unit): Add leash extension with damage dealt. (#19880)
- fix(docker): Modules SQL do not get updated or populated for docker set ups (#19870)

## 2024-09-05
- fix(Core/Creature): Creature Scale. (#19722)
- chore(DB): import pending files
- fix(Scripts/BlackTemple): Rewrite Illidan Stormrage Fight (#19574)
- Fix(Core/Misc): Acore::StringFormat to fmt format (#19867)

## 2024-09-04
- Merge branch 'master' into Playerbot
- feat(Core/Scripting): add OnBeforeArenaCheckWinConditions hook for mod-arena-replay compatibility (#19856)

## 2024-09-03
- fix(Core/AI): Improve creature leashing behavior. (#19751)
- refactor(Core): Make more use of helpers. (#19835)
- fix(Core/Handlers): Only remove emote if player is moving. (#19740)
- chore(DB): import pending files
- feat(Core/Achievements): Add possibility to complete achievements and update achievement criteria for offline players. (#19851)
- chore(Apps/Codestyle): add new codestyle checks for pointers and range loops (#19841)
- fix(Conf): sync default values with core defaults (#19708)
- chore(Core/Misc): update floor and ceil to std (#19837)
- refactor(Core/Misc): Acore::StringFormat to fmt format (#19838)
- chore(DB): import pending files
- fix(DB/Creature): Steamvault - Coilfang Oracle casts Frostshock twice (#19844)
- chore(DB): import pending files
- fix(DB/Creature): Black Temple - Dragonmaw Wyrmcallers don't use Jab … (#19855)

## 2024-09-02
- fix(Scripts/BlackTemple): Fix Zerevor not casting Dampen Magic OOC (#19768)
- fix(Core/Handlers): Don't allow data to be sent while not grouped. (#19852)
- fix(Core/GameObject): fixup allow use of Mage portal if caster is offline and still in group (#19853)
- fix(Scripts/BlackTemple): Adjust order of damage calculations for Shared Rule. (#19849)
- chore(DB): import pending files

## 2024-09-01
- fix(DB/Spell): Don't allow Molten Flame damage to stack from multiple spawns. (#19848)

## 2024-09-02
- chore(DB): import pending files

## 2024-09-01
- fix(DB/Creature): Adjust Shadowy Construct run speed. (#19847)

## 2024-09-02
- fix(Core/Spell): warrior stances proccing darkmoon card vengeance damage (#19796)

## 2024-09-01
- fix(Core/Movement): Don't move for change in orientation only (#19687)

## 2024-09-02
- fix(Core/GameObject): Allow use of Mage portal if caster is offline and still in group (#19797)

## 2024-09-01
- chore(DB): import pending files
- fix(DB/Creature): Fix unit flags for Arcane Charge trigger npc (#19833)

## 2024-08-31
- fix(Core/Guild): Require repair rights in order to make use of guild repairs. (#19836)

## 2024-09-01
- refactor(Core/Item): Add helpers (#19828)

## 2024-08-31
- refactor(Core): Correct typo. (#19830)
- fix(Scripts/BlackTemple): Fix Mother Shahraz teleport (#19820)
- fix(Scripts/ICC): NPC Muradin Dialogues (#18931)
- fix(CI/codestyle): bump dependencies for Node.js 20 (#19778)
- chore(DB): import pending files
- fix(DB/Item): Feathermoon Headdress has the wrong stats (#19814)
- chore(DB): import pending files
- fix(DB/Creature): SSC - Greyheart Spellbinder miss Banish ability (#19813)
- fix(Core/AI): remove an unused variable in ScriptedAI (#19816)
- fix(Core/CharmInfo): Respect charm spell indices when adding to action bar. (#19811)
- fix(Scripts/BlackTemple): Call evade for Council creature when members evade. (#19808)
- fix(Scripts/BlackTemple): Ensure Illidari council health is balanced across wipes. (#19809)

## 2024-08-30
- chore(DB): import pending files
- fix(Scripts/TheEye): Kaelthas remove enchanted weapons (#19801)
- fix(Scripts/TempestKeep): revamp Kael'Thas (#19648)
- chore(DB): import pending files
- fix(DB/Creature): Add taunt immunity to Gurtogg Bloodboil. (#19800)
- Merge branch 'master' into Playerbot
- fix(Conf): drop unused options from worldserver.conf.dist (#19725)
- feat(Core/Player): add OnCalculateTalentsPoints hook (#19749)
- chore(DB): import pending files
- fix(Scripts/BlackTemple): Adjust handling for Shared Rule spell. (#19770)
- feature(Core/Chat): allow fmt-chrono formatting (#19794)

## 2024-08-29
- chore(DB): import pending files
- fix(DB/Creature): Correct Promenade Sentinel speed. (#19779)
- chore(DB): import pending files
- fix(DB/GossipMenu): Dalaran guide guards (#19787)

## 2024-08-28
- chore(DB): import pending files

## 2024-08-29
- fix(scripts/npc_calvin_montague): Convert to SAI, Add emotes when completing quests (#18087)

## 2024-08-28
- fix(DB/Waypoints): Set Promenade Sentinels to walk their paths. (#19775)
- chore(DB): import pending files
- fix(DB/creature_text) Remove Quel'dorei Ghosts/Wraiths broadcast_text 12690 (#19542)
- chore(SQL): Collision in 2024_08_28_03.sql (#19772)
- chore(DB): import pending files
- feat(Core/SmartScripts): Implement Scripted Spawn System (#19499)
- docs(Core): improve several functions documentation (#19677)
- chore(DB): import pending files
- fix(DB/Creature):Quest Precarious Predicament does not complete (#19707)
- chore(DB): import pending files
- fix(DB/Creature): Quest Escape through Force - party completion issue (#19733)
- chore(DB): import pending files
- fix(DB/Creature): Quest Therylune's Escape - party completion issue (#19734)
- fix(Core/Pool): Fix degradation of pools over time (#19750)
- refactor(Core/SpellMgr): Remove nested ifs for binary evaluation. (#19762)
- fix(Core/Creature): Fix grace period for can attack check. (#19763)

## 2024-08-27
- chore(DB): import pending files

## 2024-08-28
- fix(DB/Creature): Added SmartAi to the creature "Warlord Zim'bo" (26544). (#19731)

## 2024-08-27
- feat(Scripts/Commands): Implement "pct" optional to the damage command (#19745)
- chore(DB): import pending files
- fix(Scripts/Spells): L1 Arcane Charge should hit 3 targets (#19752)
- fix(Scripts/Spells): General's Heart trinket (#19756)
- chore(DB): import pending files
- fix(Scripts/BlackTemple): Improve Illidari Council Empyreal Balance. (#19757)
- fix(Core/SpellMgr): Remove binary attribute from Drain Soul. (#19760)
- chore(DB): import pending files
- fix(DB/Creature): Adjust Illidan Stormrage's class. (#19755)
- chore(DB): import pending files
- fix(DB/Creature): Adjust Veras Darkshadow's level. (#19754)
- chore(Apps/CodeStyle): rewrite Ci-codestyle in python (#19714)

## 2024-08-26
- refactor(Scripts/BlackTemple): Update the Illidari Council script to the new registration method  (#19744)
- refactor(Core/BossAI): Improve the ScheduleHealthCheck() code (#19743)
- fix(apps/installer): update for Ubuntu 22.04/24.04 with mysql 8.4 LTS (#19737)
- chore(DB): import pending files
- fix(DB/Creature): Added dialogue for the mob "Pilot Bellowfiz" (1378) when idle (#19732)
- Naxx scripts header
- Merge branch 'master' into Playerbot
- refactor(Scripts/RuinsOfAhnQiraj): Clean up Ayamiss script (#19742)
- fix (Core/Unit): add AutoRpeatSpell delay to Auto Shot as well (#19603)
- chore(DB): import pending files
- fix(Scripts/BlackTemple): L5 Arcane Charge should be modified by dama… (#19730)
- chore(DB): import pending files
- fix(DB/SAI): Twilight Prophet - Incorrect target type resulting to an… (#19614)

## 2024-08-25
- fix(Core/Spell): Reset cd on some channeled spells (#19696)

## 2024-08-26
- fix(Core/BG): Fix fmt issue for bg sent notifications (#19718)

## 2024-08-25
- refactor(Scripts/TempleOfAhnQiraj): Clean up Cthun script (#19736)
- chore(DB): import pending files
- fix(DB/RP): Add missing RP for Recover the Cargo! (#19611)
- fix(Scripts/BlackTemple) Gathios the Shatterer shouldnt use the same spell twice in a row (#19672)
- refactor(Core/Object): adds consistency in the use of type object check (#19671)
- fix(Server): remove double blank lines at the end of several files (#19735)

## 2024-08-24
- fix(apps/installer): update for Debian 12 using mysql (#19649)

## 2024-08-23
- fix(Core/WorldSocketMgr): sync default Network.OutUBuff with worldser… (#19702)

## 2024-08-22
- fix (Core/Spells) partially revert #19529 (#19703)
- fix(Core/Spells): Fix movement impairment auras not being removed (#19684)
- chore(DB): import pending files
- fix(DB/Quest): deeprun rat roundup (#19573)
- chore(DB): import pending files
- fix(Scripts/SethekkHalls): Prevent multiple spawns of Anzu (#19636)
- refactor(Core/Battleground): rewrite SpiritOfCompetitionEvent() (#19675)

## 2024-08-21
- chore(DB): import pending files
- fix(sql): added end RP for Harlan Needs a Resupply Quest (#18897)
- chore(Debug/Scripting): improve debug errors during the unloading scripts (#19643)
- fix(Core/Spells): Power of the Guardian should persist through death (#19638)

## 2024-08-20
- chore(DB): import pending files

## 2024-08-19
- fix(Scripts/BlackTemple): Fatal Attraction (#19641)
- chore(DB): import pending files
- fix(DB/Creature): Correct Greater Fire Elemental template values. (#19686)
- chore(DB): import pending files

## 2024-08-20
- fix(DB/SAI): Hemathion spells and timers (#19621)

## 2024-08-19
- fix(Core/PetHandler): Allow PetAI to handle flags (#19446)
- Merge branch 'master' into Playerbot
- refactor(Core/Misc): Use NpcFlag helpers (#19676)
- chore(DB): import pending files
- fix(DB/Creature): Essence of Desire & Essence of Suffering taunt immu… (#19682)
- fix(Scripts/BlackTemple): Gathios the Shatterer shouldnt use Hammer of Justice on random players (#19653)

## 2024-08-18
- fix (Core/Spells): remove object size for hit calculation of aoe aura spells that target enemies (#19529)
- chore(DB): import pending files

## 2024-08-19
- fix(DB/SAI): Aether Ray spells and timers (#19620)

## 2024-08-18
- fix(Core/Map): Exempt raids from the hourly limit (#19650)

## 2024-08-19
- fix(Script/Vehicles): The next player entering Salvaged Siege Engine … (#19674)

## 2024-08-18
- Merge branch 'master' into Playerbot
- fix(Dep/Boost): corrects a warning about path changes in boost process (#19629)
- fix(Core/Creature): Nullcheck for questgreeting greeting (#19669)
- fix(Scripts/BlackTemple): Gathios Judgment spell should consume seals (#19640)
- fix(Core/Spell): check for player before dereferencing (#19666)
- apps(docker): Fix Warnings in Dockerfile (#19537)

## 2024-08-17
- fix(Core/Spells): Revert ownership and follow logic adjustment for guardian summons. (#19664)
- chore(APPS/installer): Detection of BSD* OS (#19285)
- chore(DB): import pending files
- fix(DB/Creature): Remove Veras Darkshadow stun immunity (#19642)
- chore(DB): import pending files
- fix(DB/Creature): Gathios the Shatterer taunt immunity (#19639)
- chore(DB): import pending files
- fix(DB/Creature): High Nethermancer Zerevor taunt & interrupt immunity (#19646)

## 2024-08-16
- fix(CI/MacOS): Fix macOS mysql setup. (#19634)

## 2024-08-15
- fix(Core/PlayerUpdates): incorrect backslash in a debug_log (#19630)
- fix(Core/Entities): crash fix cause by a pointer change in #19622 (#19633)
- refactor(Core/Entities): Cleanup Unit header file (#19622)
- Revert "chore(Script/Misc): cleanup" (#19627)

## 2024-08-14
- chore(Script/Misc): cleanup (#19619)
- feat(Core/LFG): Option to disable deserter (#19618)

## 2024-08-13
- chore(DB): import pending files
- fix(Core/Creature): quest_greeting_locale (#19615)
- chore(DB): import pending files
- feat(DB/Module): introduce module_string table (#19475)
- fix(Core): Adjustments to summoning ritual object handling. (#19600)
- fix(Core/Spell) Ritual spells cooldown on cancel (#19604)
- chore(DB): import pending files
- fix(Scripts): Rewrite Level 70 Elite Tauren Chieftain. (#19546)
- docs: small improvements to the AUTHORS page (#19545)
- fix(Core): Ritual animations (#19602)
- fix(Core/Spells): Adjust ownership and follow logic for guardian summons. (#19599)
- fix(Core/SpellInfo): Disallow damage scaling trigger spells to get scaled twice. (#19605)
- fix(Shared/Socket): incorrect nodiscard flag (#19612)

## 2024-08-12
- fix(Core/Entities): Only add use to spell caster objects if cast succeeds. (#19601)
- Merge branch 'master' into Playerbot

## 2024-08-11
- fix(Core/Chat): Correct misstake in b81bcfb causing outputs to CLI not working properly (#19593)

## 2024-08-10
- refactor(Core/ChatHandler): Cleanup retriving session and checking fo… (#19585)
- refactor(Core/Chat): Move SendNotification to ChatHander (#19491)

## 2024-08-08
- chore(DB): import pending files

## 2024-08-09
- refactor(Core/World): Move SendGMText to ChatHandler and allow `fmt` (#19490)

## 2024-08-07
- refactor(Deps/OpenSSL): Deprecate OpenSSL 1.x (#19452)
- fix(Scripts/ShadowmoonValley): Dragonmaw Races Reset (#19570)

## 2024-08-06
- chore(DB): import pending files
- fix(DB/Creature): Adjust various values of Black Temple creatures. (#19563)
- fix(Scripts/BlackTemple): Mother Shahraz Periodic part 2 (#19561)
- fix(Scripts/Hyjal): Anetheron dont sleep main tank (#19544)
- chore(DB): import pending files

## 2024-08-05
- fix(DB/Loot): Update uncommon drops for Ethereum prisoner creatures. (#19560)
- feat(Scripts/Commands): Morph Mount (#19558)

## 2024-08-06
- chore(DB): import pending files
- fix(DB/Creature): Adjust Warpslinter max standing to go above friendly (#19557)

## 2024-08-05
- chore(DB): import pending files
- fix(DB/Creature): Add taunt immunity to Archimonde. (#19556)
- Merge branch 'master' into Playerbot

## 2024-08-03
- fix(Core/Spells): Chromatic Resistance Aura shouldn't give holy resis… (#19549)
- Merge pull request #20 from atidot3/Playerbot
- Merge branch 'liyunfan1223:Playerbot' into Playerbot
- fix chat warning

## 2024-08-02
- chore(DB): import pending files
- fix(Core/Spells): Flame Wave (#19144)
- fix(Scripts/BlackTemple): Mother Shahraz should not use frenzy (#19543)

## 2024-08-01
- chore(DB): import pending files
- fix(Scripts/HyjalSummit): Adjust Air Burst cast targetting. (#19488)
- Merge branch 'master' into Playerbot
- Merge pull request #19 from liyunfan1223/movement-rewrite
- Merge pull request #18 from atidot3/Playerbot
- Merge pull request #17 from noisiver/playerbots

## 2024-07-30
- Add MoveKnockbackFromForPlayer

## 2024-07-31
- Playerbot helper
- chore(DB): import pending files
- fix(DB/Event): Adjustments to BlizzCon L70ETC concert event. (#19539)
- fix(Core/Common): add missing import (#19535)
- refactor(src/common): remove unused imports (#19506)

## 2024-07-30
- fix(Core/GroupHandler): Remove bad party invite check. (#19530)
- chore(Scripts/BlackTemple): Move Gurtogg Bloodboil to TaskScheduler (#19532)
- fix(Core/World): Crash on SendWorldText(Optional) (#19531)
- fix(Scripts/BlackTemple): Reliquary of Souls move to TaskScheduler and Spirit Shock timer (#19523)
- chore(DB): import pending files
- fix(DB/Creature): Remove Essence of Desire interrupt immunity (#19526)
- Fix warnings
- feat(Scripts/Commands): account set email (#19481)

## 2024-07-29
- fix(Scripts/BlackTemple): Mother Shahraz Periodic Beams (#19525)

## 2024-07-30
- chore(DB): import pending files

## 2024-07-29
- fix(DB/Spells): Acidic Wounds (#19524)

## 2024-07-30
- chore(DB): import pending files
- fix(Core/Spells): [TK] Wing Buffet should be a cone. (#19382)

## 2024-07-29
- chore(DB): import pending files
- fix(Scripts/BlackTemple): Mother Shahraz Taunt Immunity and Enrage cancelling (#19521)
- refactor(Scripts): remove unused imports (#19503)
- refactor(Core/Chat): Move SendWorldText(optional) to ChatHandler and … (#19501)
- Fix macos build
- chore(DB): import pending files
- refactor(Scripts/IcecrownCitadel): Spell Scripts use registry macros (#19508)
- fix docker warning about "FromAsCasing" (#19368)
- fix (Core/Movement) Allow MoveFollow to not inherit walkstate of the target to fix Enchanted Elemental speed (#19498)
- Merge branch 'master' into Playerbot

## 2024-07-28
- chore(DB): import pending files
- fix(DB/Creature): Adjust various values of Tempest Keep creatures. (#19502)
- fix(Core/AchievementMgr): Check for null achievement before being derefenced. (#19504)
- refactor(src/server/game/Entities): remove unused imports (#19507)

## 2024-07-27
- chore(DB): import pending files

## 2024-07-28
- fix(Scritps/AV): Use db defined text for Herald (#19486)
- refactor(Core/WorldSession): Make SendNotification use `fmt` and parse acore_string (#19489)

## 2024-07-27
- chore(DB): import pending files
- fix(DB/SAI): Disgusting Oozeling's Dark Iron Ale interaction (#19375)
- Merge pull request #15 from atidot3/Playerbot
- fix(Core/Chat): Exempt addon messages from CONFIG_CHAT_MUTE_FIRST_LOGIN (#19472)
- chore(DB): import pending files
- chore(Deps/Boost): Cleanup pre-c++11 checks and silence CMake warning (#19450)
- refactor(Scripts/RubySanctum): Spell Scripts registry macros (#19487)
- chore(Core/Authserver): Remove redundant conversion during Reconnect Proof cmd (#18957)
- chore(DB): import pending files
- refactor(Core/SmartScripts): Change invoker to be WorldObject (#19408)
- fix(Scripts/ShadowmoonValley): Rewrite Dragonmaw Races (#19084)
- fix(Core/Unit): Split Damage auras should ignore LOS (#19357)
- fix(Core/LootMgr): Improved drop checks for items that start quests (#19463)
- chore(DB): import pending files

## 2024-07-26
- fix(Scripts/BlackTemple): Move Supremus to TaskScheduler and tweak a bit (#19418)

## 2024-07-27
- chore(DB): import pending files
- fix (script/SSC) Enchanted Elementals follow Vashj (#19477)
- fix (Core/Spells): Commanding Shout and Blood Pact remember percentage of health (#19479)

## 2024-07-26
- chore(DB): import pending files

## 2024-07-27
- feat(Scripts/Commands): .aura stack - Modify aura stacks (#19462)
- refactor(Scripts/Kalimdor): remove unused imports (#19459)
- refactor(Scripts/Northrend): remove unused imports (#19460)

## 2024-07-26
- Playerbot fixes and functionnality to talk in channels

## 2024-07-25
- chore(DB): import pending files
- fix(DB/Gameobject): Pool Ragveil and Flamecap together in Zangarmarsh (#19470)
- fix(Scripts/HyjalSummit): Adjust Doomfire Spirit movement logic. (#19469)
- fix(Scripts/Commands): serv info (#19478)

## 2024-07-24
- fix(scripts/HyjalSummit): Make Doomfire Spirit move away from Archimonde at first (#19467)
- Merge branch 'master' into Playerbot

## 2024-07-23
- debloat(apps): remove unneeded script (#19466)
- chore(DB): import pending files
- refactor(Core/Chat): PSendSysMessage to `fmt` (#19449)
- chore(DB): import pending files
- fix(DB/Creature): Illidan taunt immunity (#19464)
- chore(DB): import pending files

## 2024-07-24
- fix(DB/Creature): Implement Apprentice Morlann RP Event (#19044)

## 2024-07-23
- refactor(Scripts/EasternKingdoms): remove unused imports (#19457)
- Merge branch 'master' into Playerbot

## 2024-07-22
- refactor(Scripts/misc): remove unused imports (#19458)
- refactor(Scripts/Outland): remove unused imports (#19461)

## 2024-07-21
- chore(DB): import pending files

## 2024-07-20
- fix(DB/Spells): Mortal Wound and Sunder Armor stack from different ca… (#19455)
- feat(Core/Unit): Enable/Disable Daze config (#19454)
- fix(CI): tools (#19453)
- chore(Core/Misc): Remove deprecated code (#19413)
- fix(Core/Config): Allow `#` outside of comments (#19447)

## 2024-07-19
- chore(DB): import pending files

## 2024-07-20
- fix(DB/Creature): Ormus the Penitent (#19444)

## 2024-07-19
- fix(Scripts/FireworkShow): set firework gameobjects active (#19403)
- chore(Github): Update issue template to further emphasize the require… (#19442)
- fix(Scripts/ChatLogger): Differentiate addon whisper from player whisper (#19441)
- chore(DB): import pending files
- fix(DB/Item): Bouquet of Orange Marigolds (#19417)
- fix(Scripts/Reload): Only send reload output to GMs (#19443)
- chore(DB): import pending files
- fix(Scripts/BlackTemple): Vengeful Spirit, Shadow of Death Remove (#19432)
- fix(Scripts/BlackTemple): Ashtongue Defenders unable to attack Akama (#19435)
- chore(DB): import pending files
- fix(DB/BlackTemple): A couple more of immunity and AI fixes to BT (#19436)
- fix(Core): Further adjust packet structure for attack stop opcode. (#19438)
- Merge branch 'master' into Playerbot
- fix(Spells/SpellInfoCorrections): remove AURA_INTERRUPT_FLAG_NOT_ABOVEWATER from some mounts (#19431)

## 2024-07-18
- fix(Core): Correct packet structure for combat stop messages. (#19434)

## 2024-07-19
- fix(Scripts/ChatLog): Whoopsies (#19430)

## 2024-07-18
- chore(Scripts/ChatLog): Cleanup the code (#19411)
- docs(DB): Database Squash (#19415)
- chore(DB): import pending files
- fix(Core/Spell): Allow using SpellDifficulty in bg (#19422)
- fix(DB): Correct collation for c_t_model (#19428)

## 2024-07-17
- chore(DB): import pending files
- fix(DB/game_event): revert squash 11.0.0 changes  (#19424)
- fix(Core/Spells): Restore sending SMSG_CAST_FAILED for spells in SPEL… (#19102)
- fix(Core/Spell): Implement SPELL_ATTR6_NO_PUSHBACK (#19292)
- chore(DB): import pending files
- fix(Script/Quest): Protecting Our Own (#19247)
- chore(DB): import pending files
- fix(DB/Creature): fix spout emote text for The Lurker Below (#19404)
- chore(DB): import pending files
- fix(Scripts/BlackwingLair): Nefarian say low health and rewrite p3 (#19405)
- fix(Core/Unit): add melee spell breaking for spells with cast time (#19376)
- fix(Core/Pets): Add option to revive pets with full mana (#19383)
- chore(DB): import pending files
- fix(DB/Creature): Small Black Temple adjustments (#19420)
- fix(DB/Creature): Hellfire Training Dummies shouldn't be attackable (#19421)
- chore(DB): import pending files
- fix(DB/Import): Why did the bot fail? (#19416)

## 2024-07-16
- chore(DB): import pending files

## 2024-07-17
- fix(DB/PageText): Glyphic Scroll text (#19114)

## 2024-07-16
- chore(DB): import pending files

## 2024-07-17
- fix(Scripts/Spells): warlock seed of corruption (#19322)

## 2024-07-16
- chore(DB): import pending files

## 2024-07-17
- fix(Scripts/Karazhan): Nightbane Combat Abilities (#19321)

## 2024-07-16
- chore(DB): import pending files

## 2024-07-17
- fix(Script/Spells): Script Glumdor's Steal Weapon (#19258)
- chore(Scripts/ServerMail): Cleanup the code (#19412)
- feat(DB): Release ACDB 11.0.0 (#19414)
- chore(Core/GameObjectAI): Cleanup register macro (#19409)

## 2024-07-16
- chore(DB): import pending files
- fix(DB/Loot): Add loot for Tenris Mirkblood event boss. (#19410)
- chore(DB): import pending files
- fix(Scripts/Commands): Ticket response (#19406)

## 2024-07-15
- chore(DB): import pending files
- fix(DB/Creature): Remove disable movement flag from Shadowy Construct (#19402)

## 2024-07-14
- fix(Scripts/ZG): Jin'do using wrong hex spell (#19389)
- chore(DB): import pending files
- fix(Creature): Remove bad SmartAI entries. (#19380)
- fix(Core/Unit): Adjust melee attack stop logic. (#19397)
- chore(DB): import pending files
- fix(Scripts/Netherstorm): Rewrite Phase Hunter AI (#19401)
- chore(DB): import pending files
- fix(Scripts/Midsummer): correctly despawn gameobjects (#19387)
- chore(DB): import pending files
- fix(DB/Creature): Rewrite Skettis mini bosses (#19400)
- fix(Core/Spells): BT - Summon Shadowfiens should spawn 11, instead of 1 (#19391)
- fix(Scripts/TK): KT Mindcontrol should respect Line of Sight (#19398)

## 2024-07-13
- chore(DB): import pending files
- fix(DB/Conditions): Spawn only 1 'Zelfrax' (#19365)
- chore(DB): import pending files
- fix(DB/Creature): Time-Lost Skettis High Priest & Talonpriests (#19385)
- chore(DB): import pending files
- fix(Scripts/Spells): warlock demonic pact (#19386)
- chore(DB): import pending files
- fix(DB/Item): add flag CU_DURATION_REAL_TIME to 21174 'Empty Festive … (#19392)
- fix(DB/Creature): Update Hyjal boss swing timers. (#19394)

## 2024-07-12
- fix(Scripts/HyjalSummit): Adjust Azgalor's Rain of Fire timings. (#19393)
- chore(DB): import pending files
- fix(DB/Creature): Adjust some values of Hyjal trash creatures. (#19395)

## 2024-07-11
- Merge branch 'master' into Playerbot

## 2024-07-10
- feat(Core/Unit): Implement munching as a configurable option. (#19188)
- fix(Core/GameObject): Use correct spell at meeting stone (#19311)

## 2024-07-09
- chore(DB): import pending files
- fix(DB/Creature): Add pet spells to Tempest-Smith (#19348)
- refactor(Scripts/BlackTemple): Update Mother Sharahz script (#19378)
- chore(DB): import pending files
- fix(DB/Creature): Sturdy Plate shouldn't be selectable. (#19366)
- fix(Core/Totem): Totems shouldn't be immune to intervene. (#19372)
- chore(DB): import pending files
- fix(DB/Custom): Introspection aura(s) should be a debuff (#19364)
- chore(DB): import pending files
- fix(DB/Creature): Tweak timers for Crystalcore Devastator (#19349)
- refactor(Scripts/Commands): remove unused imports (#19340)
- fix(Core/Pets): Correct Pet size for pets 3 (#19319)
- chore(DB): import pending files
- fix(DB/Loot): Normalize Epic Gear Zone Drops in The Eye (#19336)
- fix(Scripts/HyjalSummit): Correct Soul Charge color assignments. (#19345)
- fix(DB/Quest): Add SpecialFlags to Scale of Sands ring swap quests (#19354)
- chore(DB): import pending files
- fix(DB/Creature): Shadowlord Deathwail's respawn time (#19333)
- fix(DB/Quest): 'A Special Thank You' should require friendly rep (#19363)
- chore(DB): import pending files
- fix(DB/Creature): Damage Requirement for Infernal Attacker (#19350)
- fix(DB/Creature): Add Blink to Netherstrand Longbow (#19337)
- chore(DB): import pending files
- fix(DB/Formations): Solarian static trash packs (#19334)
- chore(DB): import pending files
- fix(DB/Creature): Attempt to avoid Timed Event overlap in Underbog Colossus (#19332)
- chore(DB): import pending files
- refactor(Scripts/Northrend): spell scripts registry macros (#19346)
- chore(DB): import pending files
- fix(DB/Creature): Mo'grosh Shaman (#19355)
- chore(DB): import pending files
- fix(DB/Creature): Don't continue Crystalcore Sentinel RP script when combat starts (#19338)
- chore(DB): import pending files
- fix(DB/Gameobject): Add more locations for Glinting Mud (#19351)
- fix(Scripts/AuchenaiCrypts): Remove double scheduling of Carnivorous Bite (#19353)
- chore(DB): import pending files
- fix(DB/Quest): Add ability to request missing quest item Manna-Enriched Horse Feed (#19356)
- chore(DB): import pending files
- fix(DB/SAI): 'Threat from Above' giving double credit on kill (#19373)

## 2024-07-08
- chore(DB): import pending files

## 2024-07-07
- fix(DB/Gameobject): Replace all The Eye gameobjects (#19347)
- fix(CI): linux-build: add -Werror parameter (#19240)
- fix(Build): -Wsign-compare (#19320)
- chore(DB): import pending files
- fix(DB/Karazhan): Respawn Skeletal Gryphons. (#19329)
- chore(DB): import pending files
- fix(DB/OnyxiasLair): Respawn Onyxian Warders. (#19328)
- fix(Core/Spells): Greater Fireball should ignore resistances (#19326)
- chore(DB): import pending files
- fix(DB/Creature): Remove Bleed immunities from mechanical & undead creatures (#19304)
- fix(DB/Creature): Talon King Ikiss should be immune to interrupts (#19331)
- fix(Scripts/HyjalSummit): Rage Winterchill Spells (#19335)
- chore(DB): import pending files
- fix(DB/Item): Increase ppm of Netherstrand Longbow (#19306)
- fix(DB/Gossip): Allow Estelle Gendry to give players Thieves' Tools (#19303)
- Merge branch 'master' into Playerbot

## 2024-07-06
- chore(DB): import pending files
- fix(Scripts/HyjalSummit): Add damage over time component to Doomfire debuff. (#19317)
- feat(Core/Chat): Provide a fully-formed protocol for addons to intera… (#19305)
- chore(DB): import pending files
- fix(DB/Quest): Spirits of the Feralfen (#19310)
- fix(DB/TheBlackTemple): Ashtongue Feral Spirit detection range (#19315)
- fix(DB/TheBlackTemple): make Promenade Sentinel kick immune (#19316)
- fix(Core/Player): Vertical Message distance (#19302)
- chore(DB): import pending files
- fix(DB/SAI): Zeppit's RP for collecting blood (#19318)
- feat(Core/SAI): SetData now has invoker (#19296)
- chore(DB): import pending files
- fix(DB/Creature): Prevent Hellfire Peninsula's Pit Commander from cancelling Timed Event (#19307)
- chore(DB): import pending files
- fix(DB/Creature): Verog the Dervish ReactState (#19308)
- fix(Scripts/ShadeOfAran): Make immune to Mind-numbing and Cure of Tongue (#19309)
- chore(DB): import pending files

## 2024-07-05
- fix(DB/Quests): Marks of Kil'Jaeden and Firewing Signets quests should be available at Neutral 0 (#19301)

## 2024-07-06
- chore(DB): import pending files

## 2024-07-05
- fix(DB/Creature): Skyguard Prisoner shoul spawn with ReactState Passive (#19300)

## 2024-07-06
- chore(DB): import pending files

## 2024-07-05
- fix(Scripts/BlackTemple): Move Teron Gorefiend to scheduler and add Berserk (#19288)
- fix(DB/Condition): Fix condition type for restoring Scale of the Sands exalted ring (#19291)
- fix(DB/Creature): Add AI to Affray Challenger (#19298)
- chore(DB/Loot): Remove Metzen's Letters and Notes from creature loot tables (#19299)

## 2024-07-06
- chore(Scripts/Commands): QOL server debug (#19297)

## 2024-07-05
- chore(DB): import pending files
- fix(DB/Creature): Rewrite Voidshrieker AI (#19290)
- fix(Core/Unit): Invalidate update object cache when changing health in the same world update tick. (#19287)
- chore(DB): import pending files
- fix(Scripts/SmartAI): Rewrite ACTION_MOVE_TO_POS (#19190)
- fix(Core/Misc): unused param (#19286)
- chore(DB): import pending files

## 2024-07-06
- fix(DB/Misc): Migrate SQL files to the correct folder (#19282)

## 2024-07-05
- fix(Core/dbc): GlyphPropertiesfmt ERROR (#19284)
- fix(Core/Handlers): Adjust start swing handler. (#19267)
- chore(DB): import pending files
- fix(Scripts/Item): Fix Fel Mana Potion not benefiting from Alchemist'… (#19281)

## 2024-07-04
- chore(DB): import pending files
- fix(DB/Spells): Allow Sablemane's Sleeping Powder to bypass stun immu… (#19280)
- fix(Core/Pets): Correct Pet size for bigger pets 2 (#18867)
- chore(DB): import pending files
- fix(Scripts/Shattrath): Daily Dungeon quests holograms (#19233)
- chore(DB): import pending files
- refactor(Scripts/ZulAman): Nalorakk refactored (#19010)
- chore(DB): import pending files

## 2024-07-05
- fix(DB/SAI): Added healing options for the Silver Dawn Healer in the Eastern Plaguelands (#18852)

## 2024-07-04
- fix(Scripts/Naxxramas): Razuvious' Death Knight Understudy RP (#19183)
- chore(Core/Spells): Fix compile warning (#19278)
- chore(DB): import pending files
- fix(DB/Creature): set Idol Room Spawner no longer visible (#19276)
- fix(Scripts/HyjalSummit): Couple Archimonde adjustments. (#19193)
- fix(Core/Spell): Implement SPELL_ATTR1_AURA_STAYS_AFTER_COMBAT (#19254)
- fix(Core/Character): TeleportTo() in HandlePlayerLoginFromDB() causes… (#19237)
- refactor(Script/Dalaran): Minigob Manabonk (#19244)
- chore(Core/Conf): Show better logging when fatal config options are m… (#19236)
- chore(Core/DBC): define unused unknown dbc fields (#19262)
- fix(Core/Spells): Shapeshift should show in Old Hillsbrad Foothills a… (#19274)
- fix(Core/Loot): implement automatic pass in group loot for items that… (#19272)
- feat(Core/SAI): implement new removeObjectFromWorld param for SMART_A… (#19275)
- fix(Core/Pet): prevent LoadPetFromDB to trigger a fake summon spell cast in most cases (#19277)
- fix(Scripts/TK): Kael'thas mind control should reset threat (#19264)
- chore(DB): import pending files
- fix(DB/Gameobject): Move Karazhan chess chest. (#19273)
- fix(Core/Quest): typo in RewardQuest makes LFG quests not reward if dead (#19271)
- fix(Scripts/TheEye): Kael'thas adjustments. (#19213)
- fix(Core/Arena): Check to see if other members in your arena team are queued or in a r… (#18808)

## 2024-07-03
- fix(Core/Scripting): fix OnBeforeCreateInstanceScript hook (#19252)
- Merge branch 'master' into Playerbot
- Rollback name check
- fix(Core/Player): Allow players to enter the world (#19261)
- Merge branch 'master' into Playerbot
- refactor(Core/ObjectMgr): Handle Profanity & Reserved Names in load (#19259)

## 2024-07-02
- Revert "Add (core\db): Support for Homebind Orientation (#13389)" (#19257)
- chore(DB): import pending files
- fix(DB/Creature): Correct movement speed of Hyjal bosses. (#19251)
- chore(Core/Misc): #include cleanup (#19255)

## 2024-07-01
- refactor(Scripts/EasternKingdoms): RegisterSpellScript macro (#19241)
- chore(DB): import pending files
- fix(DB/SAI): Xeleth (#19250)
- chore(DB): import pending files
- fix(Script/Commands): output lookup quest and npc near (#19243)

## 2024-06-30
- fix(Script/GunshipBattle): Wipe if no player is on the deck (#19239)
- fix(Scripts/Hyjal): Workaround bosses getting stuck in progress (#19231)
- fix(DB): correct query (#19235)

## 2024-06-29
- chore(DB): import pending files
- fix(Scripts/Naxxramas): Gothik missing visuals at minions death (#18666)
- chore(DB): import pending files
- fix(DB/SAI): Port 'Finding the Keymaster' RP from TDB (#19206)
- chore(DB): import pending files
- fix(Core/Spell): implement taunt DR CREATURE_FLAG_EXTRA_OBEYS_TAUNT_DIMINISHING_RETURNS  (#19128)
- fix(build): mac (#19229)
- chore(DB): import pending files
- Merge branch 'master' into Playerbot
- fix(core/character-creation): get main part of cyrillic name (#18971)
- fix(DB/Creature): remove duplicate 25962 'Fire Eater' spawns (#19227)
- chore(DB): import pending files
- fix(Core/Spells): Eye of Grillok improvements (#19148)
- fix(Scripts/World): Emerald Dragons no longer have 0% health events (#18893)
- refactor(Scripts/Spells): Spell Scripts registry macros, rogue killing spree (#19226)
- chore(DB): import pending files
- fix(DB/Creature): Port Tideress WP from mangos-wotlk (#19129)
- fix(DB/SAI): Shadowy Summoner (#19151)
- chore(DB): import pending files
- fix(DB/SAI): Eclipsion Spellbinder from TDB (#19214)
- refactor(Scripts/World): Spell Scripts registry macros (#19224)
- refactor(Scripts/SunwellPlateau): Spell Scripts registry macros (#19223)
- fix(Spells/SpellInfoCorrections) Remove friendly mask on goblins (#18912)
- chore(DB): import pending files
- fix(DB/Area): Horvon the Armorer & Greatfather Aldrimus phasing (#19138)
- chore(DB): import pending files
- chore(Core/DBC): Comment unused CreatureDisplayInfoExtraEntry field (#19170)
- fix(DB/SAI): Worg Master Kruush, Ripp & Feng (#19145)
- chore(DB): import pending files

## 2024-06-28
- fix(Loot/Midsummer): Add loot to Pocket Full of Snow. (#19218)
- chore(DB): import pending files
- fix(DB/Creature): Correct model info for Ahune related mobs. (#19219)
- fix(DB/Midsummer): Add missing slippery floor bunny. (#19217)
- chore(DB): import pending files
- fix(Scripts/Midsummer): Add despawn to Ice Stones and drop respawn time. (#19215)
- fix(Core/Spells): Midsummer spinning visual interrupt on gossip (#19211)
- Merge branch 'master' into Playerbot
- fix(Scripts/Karazhan): Destroy Netherspite portals on death. (#19203)
- chore(DB): import pending files
- fix(DB/SAI): Lashh'an Wing Guard (#19169)
- fix(Scripts/Karazhan): Allow portal color effects to overlap on players. (#19204)
- chore(DB): import pending files
- fix(Core/Auras): Add SPELL_ATTR0_CU_ONLY_ONE_AREA_AURA (#19209)

## 2024-06-27
- fix(Scripts/SlavePens): Adjust Ahune spell casts. (#19202)
- chore(DB): import pending files
- fix(DB/Creature): Blight Geist using wrong target_type (#19189)
- fix(Core/Misc): fmt (#19192)
- chore(DB): import pending files
- fix(Scripts/Karazhan) Nightbane take off phase handling (#18934)
- refactor(Scripts/BlackrockMountain): Spell Scripts registry macros (#19186)
- chore(DB): import pending files
- fix(DB/Creature): Port Treebole WP from mangos-wotlk (#19165)

## 2024-06-26
- fix(Core/AI): Don't set boss state to none if already complete (#19139)
- chore(DB): import pending files
- fix(DB/Spells): Bleeding Hollow Necrolyte - Raise Dead no… (#19153)
- fix(Scripts/AzjolNerub): Anub'Arak clear debuff spell (#19140)
- chore(DB): import pending files
- fix(DB/Creature): Fleshbeasts formations (#19172)
- chore(DB): import pending files
- fix(DB): Booty Bay / Gnomegeran Transpolyporter (#19182)
- chore(DB): import pending files
- fix(Scripts/SlavePens): Remove permanent knockback aura on ice spear bunny. (#19152)
- refactor(Scripts/Kalimdor): Spell Scripts registry macros (#19185)
- refactor(Scripts/Karazhan): Spell Scripts registry macros (#19184)
- feat(Core/Movement): implement Pause and Resume to WaypointMovementGenerator (#19176)
- fix(Core/Spell): Bladestorm remove reset swing and allow meleeSwingSpell during (#19093)
- fix(DB/SAI): A large number of SAI are lost (#19177)

## 2024-06-25
- chore(DB): import pending files

## 2024-06-26
- fix(DB/SAI): Tormented Soul & Soulbind spell (#19162)

## 2024-06-25
- chore(DB): import pending files
- fix(DB/SAI): Lashh'an Talonite pets (#19154)
- fix(DB/Loot): Add guaranteed drops to Ethereum Prisoner loot tables. (#19156)
- fix(DB/Creature): Link Durnholde Lodges formation (#19159)
- fix(DB/SAI): Kirin'Var Apprentice not throwing hammer and missing aura (#19163)
- fix(Core/Spells):  Script Drunken Haze & Drunken Skull Crack (#19164)
- chore(DB): import pending files
- fix(DB/Loot): Correct chances related to Captain Rumsey's Lager recipe. (#19166)
- chore(DB): import pending files
- fix(DB/Conditions): Zaxxis Insignia should drop without any conditions. (#19158)
- chore(DB): import pending files
- refactor(Scripts/Outland): spell scripts use registry macros (#19132)
- fix(CI): fix Error.log check (#19161)
- chore(DB): import pending files
- fix(Creature): Adjust Ahune Frozen Core level. (#19150)

## 2024-06-24
- chore(DB): import pending files
- fix(DB/Creature): Add parry hasting exception for a few TBC raid bosses. (#19149)
- Merge branch 'master' into Playerbot
- chore(DB): import pending files
- fix(DB/SAI): Torek's Assault not completing for party members (#19143)
- chore(DB): import pending files
- refactor(Scripts/Northrend): fixup spell_hadronox_summon_periodic_crypt_fiend_aura (#19142)
- fix(Script/ICC): Make Plagueworks Release Valves noninteractable afte… (#19133)
- chore(DB): import pending files
- fix(Scripts/Midsummer): fix handling of unwanted npc and gameobject s… (#19141)

## 2024-06-23
- chore(DB): import pending files
- refactor(Scripts/Northrend): dungeons Spell Scripts registry macros (#19134)

## 2024-06-22
- chore(DB): import pending files
- refactor(Scripts/Hodir): spellscripts use registry macros (#19126)
- chore(DB): import pending files
- fix(DB/Conditions): Thrall's WCB fixup (#19125)
- chore(DB): import pending files
- fix(DB/Creature): Fix Dragonmaw Wind Rider interrupt immunity (#19118)
- fix(DB/Spells): Scourgebane Draugh & Infusion should stack with flask… (#19119)
- fix(DB/Creature): Fix Dragonmaw Wind Rider and Sky Stalker taunt immu… (#19120)
- chore(DB): import pending files
- refactor(Scripts/BlackTemple): Spell Scripts use registry macros (#19122)
- refactor(Scripts/TempestKeep): Spell Scripts use registry macros (#19123)
- Merge branch 'master' into Playerbot
- chore(DB): import pending files
- fix(Scripts/Kalimdor) Thrall Warchief's Blessing, add level and reputation requirement, spike activation (#19121)
- chore(DB): import pending files
- fix(Core/PlayerQuest): Introduce flag QUEST_SPECIAL_FLAGS_CAN_FAIL_IN… (#19116)
- chore(DB): import pending files
- fix(DB/Gossip): Refik missing text for lowlevel tailoring (#19111)

## 2024-06-21
- chore(DB): import pending files
- fix(DB/Creature): add TRIGGER flag to 'Ribbon Pole Fire Spiral Bunny' (#19115)
- fix(Scripts/Midsummer): use GUID storage rather than Player object (#19109)
- chore(DB): import pending files
- fix(DB/Creature): Finish correcting Doomfire Spirit speed.  (#19110)
- fix(Core/Ahune): Chest and Quest (#19106)

## 2024-06-20
- fix(Scripts/Midsummer): Resolve Ribbon Pole crash. (#19108)

## 2024-06-21
- chore(DB): import pending files

## 2024-06-20
- fix(DB/Creature): Correct Doomfire/Spirit speed. (#19105)
- chore(DB): import pending files
- fix(Scripts/Spell): adjust Thrall's and Herald WCB timings, limit to Orgrimmar and Crossroads (#19026)
- chore(DB): import pending files
- fix(DB/Creature): Spirit of Zandalar limit to 63 and below, apply to Booty Bay (#19024)
- fix(DB/Kalimdor): limit Warchief's Blessing to Horde only (#19025)
- chore(DB): import pending files
- fix(DB/Conditions): Spell Protection of Elune only targets players (#19094)
- fix(DB/Creature): Bonechewer Taskmaster taunt immunity (#19098)
- fix(DB/Creature): Illidari Fearbringer immunities (#19099)
- fix(Core/Spells): Partially revert spell cancel behavior change. (#19101)
- chore(DB): import pending files
- fix(DB/Loot): Adjust Ancient Gem Vein loot table. (#19097)
- fix(Scripts/Hyjal): Fix wave count not showing for Rage Winterchill waves
- chore(DB): import pending files

## 2024-06-19
- fix(DB/Loot): Correct oversight with Hyjal trash loot. (#19095)

## 2024-06-20
- chore(DB): import pending files
- fix(DB/Command): fix help typo 'trigered' for .cast commands (#19092)
- fix(Core/SmartAI): add prevent almost infinite spinning of mutual target to pets (#19090)

## 2024-06-19
- Merge branch 'master' into Playerbot

## 2024-06-18
- chore(DB): import pending files
- fix(DB/Creature): Fix minor issues with Dragonmaw Peons (#19091)
- chore(DB): import pending files
- fix(Scripts/Spells): Implement damage scaling based off DoT stack count for Seal of Vengeance and Corruption. (#19073)
- fix(Scripts/ICC): Fix Valithria reseting (#19087)
- chore(DB): import pending files

## 2024-06-19
- fix(DB/Creature): Mote of Shadow incorrect low value for 2 npcs (#19088)

## 2024-06-18
- chore(DB): import pending files

## 2024-06-19
- fix(DB/Creature): Port Force-Commander Gorax patrol from mangos-wotlk (#19089)
- fix(Core/Quest): Correct XP Display when modified by SPELL_AURA_MOD_XP_QUEST_PCT (#19060)

## 2024-06-18
- chore(DB): import pending files
- fix(DB/Hyjal): Update conditions after boss index change  (#19086)
- chore(DB): import pending files

## 2024-06-17
- fix(DB/Procs): Add proc info for lower ranks of Reckoning talent. (#19071)

## 2024-06-18
- chore(DB): import pending files
- fix(Core/Spells): Don't send SMSG_CAST_FAILED for interrupted spells … (#19082)
- fix(DB/Creature): Archmage Xylem patrol from mangos-wotlk (#19083)

## 2024-06-17
- fix(core/spell): Presence of Mind should not apply cooldown mods on c… (#17890)
- chore(DB): import pending files
- fix(Scripts/SlavePens): Rewrite Ahune. (#19075)
- fix(Scripts/BlackTemple): Akama shade missing says (#19076)

## 2024-06-18
- fix(Scripts/Misc) CanExecuteCommand renamed and moved to be executed for all commands. (#19081)

## 2024-06-17
- chore(DB): import pending files
- chore(Scripts/Hyjal): Remove unneeded Archimonde spell scripts (#19080)

## 2024-06-16
- chore(DB): import pending files

## 2024-06-17
- fix(Scripts/ObsidianSanctum): add Flame Tsunami knockback (#19078)

## 2024-06-16
- chore(DB): import pending files
- fix(DB/Creature): Correct model info for Black Temple bosses. (#19079)
- fix(Scripts/Hyjal): Archimonde should gain charges regardless of deat… (#19069)
- fix(Core/AI): Fix bosses being stuck IN_PROGRESS if despawnonevade fl… (#19070)
- chore(DB): import pending files
- fix(DB/Spells): Infinity Blade's Magic Disruption should stack for di… (#19077)
- chore(DB): import pending files
- refactor(Core/ObjectMgr): Implement display probabilities. (#19068)
- fix(Scripts/BlackTemple): Fix najentus enrage not reseting (#19074)
- fix(Scripts/Spells): Flag of Ownership (#18757)

## 2024-06-15
- chore(DB): import pending files
- fix(DB/Achievement): Pilgrim reward mail (#19067)
- fix(Scripts/BlackTemple): Fix Najentus not enraging after 8 min (#19066)
- fix(Scripts/BlackTemple): Fix Free Friend spell (#19065)
- chore(DB): import pending files
- feat(CI): enable fail-fast for pch/nopch (#19058)
- fix(DB/Item): Stormherald PPM adjustment. (#19059)
- chore(DB): import pending files
- fix(DB/Creature): Aquaneous Lord taunt immunity (#19061)
- fix(DB/Spell): Sludge Nova stack from different casters (#19063)
- fix(DB/Creature): Aqueous Lord formation behaviour (#19064)

## 2024-06-14
- chore(DB): import pending files

## 2024-06-15
- fix(DB/Creature): Reth'hedron spawn timer (#19055)

## 2024-06-13
- fix(docs): sync SECURITY.md with current CI config (#19057)
- fix(Core/Pet): Warlock pet handling (#19054)
- chore(DB): import pending files
- fix(CI): reintroduce ubuntu-22.04 checks (#19052)
- fix(DB/Creature): Kadrak's wrong axe model (#19047)

## 2024-06-11
- fix(CI/labeler): update Core, Documentation, Cmake labelling (#19022)
- chore(DB): import pending files
- fix(DB/Gameobject): unlink 'Mighty Blaze' spawns from game events (#19049)
- chore(DB): import pending files
- refactor(Scripts/Ulduar): Spell Scripts use registry macros (#19045)
- fix(Scripts/Hyjal): remove very scary call by reference and posis without initialization (#19046)

## 2024-06-10
- fix(Scripts/NPC): Fix arcanite dragonling attacking non flagged players (#19039)
- chore(DB): import pending files
- fix(DB/Creature): Crystalcore Sentinals & Devastators knockback immunity (#19040)
- fix(Scripts/SSC): Fix Serpentshrine Parasites not being summoned (#19041)
- chore(DB): import pending files
- fix(DB/Creature): Vashj elementals disorient immunity (#19042)

## 2024-06-11
- fix:(DB/creatures) Repair the position of the chicken in Southshore (#19043)

## 2024-06-09
- chore(DB): import pending files
- fix(DB/SAI): Watoosun Polluted Essence shouldnt cast Acid Splash (#19038)
- chore(Scripts/Hyjal): Clean up redundancy (#19035)
- chore(DB): import pending files
- fix(Scripts/Hyjal): Air Burst back to random target (#19037)
- fix(DB/SAI): Subdue the Subduer should credit group (#19036)

## 2024-06-10
- Merge branch 'master' into Playerbot

## 2024-06-09
- chore(Command/unstuck) use command with offline players (#18913)
- chore(DB): import pending files
- refactor(Scripts/Naxxramas): Spell Scripts use registry macros (#19034)

## 2024-06-08
- chore(DB): import pending files
- fix(DB/Creature): Correct model info for Hyjal bosses. (#19032)
- chore(DB): import pending files
- fix(Scripts/Hyjal): some Archimonde fixes (#19031)
- chore(DB): import pending files
- fix(Scripts/Hyjal): Change the spawn and the movement of Doomfire (#19027)

## 2024-06-07
- Merge branch 'master' into Playerbot
- fix(Scripts/HyjalSummit): Assign Death Knight Soul Charge. (#19020)
- chore(DB): import pending files
- fix(DB/Gameobject): Rebuild all Kalimdor gathering nodes using sniffed data (#18982)
- fix(DB/Item): Egg Basket (#19021)
- chore(DB): import pending files
- fix(DB/achievement_reward): Glory of the Ulduar Raider mail subject line (#19018)
- chore(DB): import pending files
- fix(DB/Stratholme): add Magistrate Barthilas escape event in Stratholme (#17669)

## 2024-06-06
- fix(Scripts/HallsofStone): corrected Brann dialogue to match live game (#19019)
- fix(CI/labeler): fix some paths for proper labeling (#19016)
- fix(Core/Player): Delete by group (#19015)
- chore(DB): import pending files
- fix(Script/Item): Fetch Ball (#18906)

## 2024-06-05
- fix(Scripts/Hyjal): Fix Azgalor Doom targetting tanks since its an AoE spell (#19012)
- fix(Core/Networking): Fix crash in Proxy Protocol when removing closed sockets. (#19011)

## 2024-06-04
- fix(CI): add missing ticks to labeler.yml file paths (#18995)
- fix(Core/Battleground): Adjust Eye of the Storm tick rate. (#19007)
- fix(Core/PlayerQuest): make timed quests failable (#18940)
- chore(CI): drop checks - only keep latest Ubuntu 24.04 (#18991)

## 2024-06-03
- chore(Scripts/Hyjal): Clean up unsafe calls and code style (#19004)
- fix(Scripts/Hyjal): Anetheron cast Carrion Swarm on non player targets (#19005)
- fix(Scripts/Hyjal): archimonde enrage after 10 minutes (#19003)
- Merge branch 'master' into Playerbot
- fix(Core/PetHandler): when dismissing a charmed unit owned by another unit; stop the charm instead of despawning (#18989)
- fix(Script/Hyjal): Fix encounter states not reseting if bosses are de… (#19000)

## 2024-06-02
- chore(DB): import pending files
- fix(Scripts/Hyjal): correctly despawn summoned creatures on Jaina/Thrall death (#18997)
- fix(DB/achievement_reward): award title on Hand of A'dal FoS (#18998)
- fix(Core/Mail): calculate unReadMails and m_nextMailDelivereTime usin… (#18996)
- fix(CI): fix labeler (#18990)

## 2024-06-01
- chore(DB): import pending files
- fix(DB/Creature): Couple Netherwing related fixes. (#18981)
- fix(CI): bump pr-labeler dependencies for usage of Node.js 20 (#18983)
- fix(Scripts/Hyjal): fix some build warnings for unused parameters (#18986)
- fix(CI): fix ubuntu-24.04 build (#18984)

## 2024-05-29
- fix(Scripts/Hyjal): increase ranges on doomfire to make movement less inclined to stick close to the boss (#18976)
- fix(Scripts/Hyjal): remove summoned mobs on boss evade and reset waves (#18975)
- fix(Unit/ProcessTerrainStatusUpdate): prevent removal swimming auras if swimming (#18902)
- fix(LICENSE): update license file paths (#18972)
- chore(DB): import pending files
- fix(Scripts/Hyjal): tweak movement of Doomfire (#18970)

## 2024-05-28
- fix(Scripts/Hyjal): Anetheron dont cast sleep on tank (#18969)
- fix(Scripts/Hyjal): Fix Doom spawning Doomguards twice on expire (#18968)
- fix(Scripts/Hyjal): Azgalor doom shouldnt target tank MKII (#18964)
- chore(DB): import pending files
- fix(Ulduar/Tram): add rocket booster, turnaround visuals, button logic (#18900)

## 2024-05-27
- chore(DB): import pending files
- fix(Scripts/Hyjal): Implement Eternal Silence spell when going into t… (#18960)
- fix(Scripts/IcecrownCitadel): Gunship Cannons generates heat on Cast not on Hit (#18805)
- chore(DB): import pending files
- fix(Scripts/Hyjal): Azgalor mark of doom spawn demons on target death (#18959)
- fix(Scripts/Hyjal): Anetheron should not cast sleep on MT (#18948)
- chore(DB): import pending files

## 2024-05-28
- Fix creatures combat AI missing (#18947)

## 2024-05-27
- chore(Scripts/Hyjal): Update Mark of Kazrogal script (#18958)
- fix(Scripts/Hyjal): Azgalor Rain of Fire should target non-player tar… (#18956)
- fix(Scripts/Ulduar): adjust Mimiron outro RP sleep visuals (#18950)

## 2024-05-26
- chore(DB): import pending files
- fix(Scripts/Ulduar): falling down Kologarn's pit should kill (#18945)
- chore(DB): import pending files
- fix(ICC/Sindragosa): add a cooldown to proccing Unchained Magic (#18901)
- fix(Scripts/Ulduar): Add emote for opening of the Ancient Gate of the Keepers (#18949)
- [Scripts] Naxxramas scripts refactor with namespace
- Merge branch 'master' into Playerbot

## 2024-05-25
- fix(Scripts/Ulduar) Kologarn becomes a bridge (#18944)
- chore(DB): import pending files
- fix(DB/Loot): Fix mistake in generic overworld profession drops (#18941)
- chore(DB): import pending files
- fix(Scripts/Ulduar): update Boss Keepers, Gossip Keepers, Yogg Keepers, Yogg-Saron (#18943)

## 2024-05-23
- chore(Scripts/Hyjal): Don't initialize headers twice (#18939)

## 2024-05-22
- fix(Scripts/Hyjal): initialize/reset local private variables in Reset function (#18932)

## 2024-05-21
- chore(DB): import pending files
- fix(Scripts/Hyjal): Air Burst should not be cast on MT (#18933)

## 2024-05-20
- chore(DB): import pending files
- fix(Scripts/Hyjal): Archimonde shouldn't cast other spells during enr… (#18928)
- fix(Scripts/Hyjal): Limit Anetheron sleep to 3 targets (#18929)
- fix(Scripts/Ulduar): disable Mimiron's and Thorim's Targetting crystal when talking to Bran (#18927)

## 2024-05-19
- fix(Scripts/Commands): Fix .lookup item command for most locales (#18922)
- chore(DB): import pending files
- fix(DB/Creature): Correct TBC boss gold rewards. (#18899)
- fix(CI): bump dependencies for usage of Node.js 20 (#18914)
- chore(DB): import pending files
- fix(DB/Gameobject): Sniffed Values for 'Crossroads' Supply Crates' spawns (#18904)

## 2024-05-18
- chore(DB): import pending files
- fix(DB/creature_text) add missing broadcastID to Elder Clearwater txt lines to supp… (#18917)
- fix(Docker): Check write access for config dir (#18238)
- chore(Docker): update docker compose file schema (#18686)
- chore(DB): import pending files
- feat(Scripts/Commands): Add quality colors to .item lookup command (#18907)
- feat(core): add hooks for applying item mods (#18760)
- chore(DB): import pending files
- fix(DB/creature_text): localize Arcanist Braedin txt line about WG (#18886)

## 2024-05-17
- feat(CI): add CI for ubuntu-24.04 (#18909)
- fix(CI): revert ubuntu-22.04 to gcc12 (#18905)
- fix(Scripts/ShadowmoonValley): minor fixes to Enslaved Netherwing Drakes (#18883)

## 2024-05-15
- chore(DB): import pending files
- fix(Core/BattlegroundAV): spawn generic gameobjects in Alterac Valley (#18764)

## 2024-05-14
- chore(DB): import pending files
- fix(DB/Gameobject): Rebuild all Eastern Kingdoms gathering nodes using sniffed data (#18898)
- chore(DB): import pending files
- fix(DB/Loot): Near complete loot rework of Vanilla overworld zones (#18796)
- chore(DB): import pending files
- fix(DB/Hyjal): allow Giant Infernal to use Flame Buffet (#18885)

## 2024-05-13
- chore(DB): import pending files

## 2024-05-14
- fix(DB/gameobject):Remove the Church of the Holy Light with flowers and small mounds (#18879)

## 2024-05-13
- fix(Karazhan/Nightbane): Rain of Bones cast on one random player/pet, summon Skeletons at that location (#18892)

## 2024-05-12
- chore(DB): import pending files
- fix(DB/Hyjal): Archimonde aggro range (#18884)
- fix(Karazhan/Nightbane): no longer killable during flight (#18890)
- fix(Scripts/Naxxramas): Re enable Portal Hub teleport requirement  (#18844)
- chore(DB): import pending files
- fix(Core/Events) Implement Fireworks Spectacular (#18860)
- fix(DB/updates): fix downquery to match up (#18888)
- fix(Scripts/Zones/Creature): Infra-Green Bomber (#18752)
- chore(DB): import pending files
- fix(DB/asi）Added some small events to the creature "Shen'dralar Ancient (14364)".... (#18880)
- fix(DB/Creature):  Correct spells order for Broken-down Shredder (issue 18729) (#18866)

## 2024-05-11
- fix(Scripts/TheEye): correct first phoenix in p5 (#18802)
- chore(DB): import pending files
- fix(Scripts/Spell): Fix Void Zone damage calcs for Netherspite, Blaumeux (#18807)
- chore(DB): import pending files
- fix(Scripts/Naxxramas): Maexxna more blizzlike web wrap (#18843)
- chore(DB): import pending files
- fix(Core/Unit):  SPELLMOD_RESIST_MISS_CHANCE should decrease miss chance (#18849)
- fix(db/sai) Some contents of the restoration of creature (27210 and 27951) (#18850)
- chore(DB): import pending files
- fix(DB/spell_target_position): Mara Portal tp location (#18876)
- fix(Conf): align LeaveGroupOnLogout default in core with worldserver.conf.dist (#18859)
- chore(DB): import pending files
- fix(AQ40/SmartGameObjectAI): remove locked status from scarab coffer upon opening (#18877)

## 2024-05-09
- chore(DB): import pending files
- fix(DB/Creature): Zul'Aman prisoner loot (#18869)
- fix(Core/Misc): Correct typo when loading reference loot templates (#18872)

## 2024-05-07
- Merge branch 'master' into Playerbot

## 2024-05-06
- fix(Docs/PR-Template): update discord invite link (#18862)

## 2024-05-04
- feat(Core/Network): Add Proxy Protocol v2 support. (#18839)
- Merge branch 'master' into Playerbot
- feat(Map): Add open world LOS settings (#18816)
- chore(DB): import pending files
- fix(Scripts/Magtheridon): Clicking cubes should Banish Magtheridon (#18856)

## 2024-04-30
- fix(Core/Map): remove hackfix that blocked update of GOs beeing set active (#18812)
- chore(DB): import pending files
- fix(DB/Creature): fixed Timber respawn time (#18625)
- fix(Scripts/Arenas): Updating timer for Shadow Sight spawns (#18748)

## 2024-04-29
- Merge branch 'master' into Playerbot
- chore(DB): import pending files
- fix(DB/Gossip_Menu_Option_Locale): fix german umlauts (#18781)
- fix(Scripts/PlayerScript): PlayerScript Error (#18806)

## 2024-04-27
- refactor(Scripts/Karazhan): 'uint' It can never be less than 0 (#18726)
- fix(Core/Battleground): EOTS adjust flag respawn timer (#18759)
- chore(DB): import pending files
- fix(DB/Gameobject): Sniffed Values for 'AuctionNode' spawns (#18780)
- fix(Core/GameObject): load guid based scripts correctly (#18811)

## 2024-04-26
- Merge branch 'master' into Playerbot

## 2024-04-25
- chore(DB): import pending files

## 2024-04-26
- fix(DB/Creature): Manually apply 'automated z correction' to DB spawns (#18692)

## 2024-04-25
- chore(DB): import pending files

## 2024-04-26
- fix(DB/Gameobject): Sniffed Values for 'Doodad_DwarfSign_Alchemist01' spawns (#18777)

## 2024-04-24
- fix(Core/Pet): Fix pets chasing when pet and target spins uncontrollable (#18798)
- fix(Core/SmartAI) fatal error: unused parameter pathId (#18795)
- chore(DB): import pending files
- fix(DB/Creature): Add a small event for mission 1781 (#18739)

## 2024-04-23
- fix(Scripts/TheEye): Update Alar Dive Bomb timings (#18654)

## 2024-04-22
- Merge branch 'master' into Playerbot
- fix(Scripts/TheEye): Update Astromancer timings and add phase (#18655)

## 2024-04-21
- chore(DB): import pending files

## 2024-04-22
- fix(DB/Creature)Added paths for patrolling mobs in the Scarlet Abbey chapel area (#18734)

## 2024-04-21
- chore(DB): import pending files

## 2024-04-22
- fix(DB/Spell) Fix the Spell Upgrade Zigguraut  visuals (#18771)

## 2024-04-21
- chore(DB): import pending files
- fix(DB/Gameobject): add missing script to some fire places (#18768)
- fix(Scripts/TheEye): Update Kaelthas Phoenix timers (#18657)
- fix(DB/Gameobject): Sniffed Values for 179548 'A Dusty Tome' spawns (#18775)
- fix(DB/Gameobject): Sniffed Values for '%Cauldron%' spawns (#18762)
- fix(DB/SAI): make 'Midsummer Celebrants' talk regularly (#18770)

## 2024-04-20
- chore(DB): import pending files
- fix(Scripts/Hyjal): Cannibalize should heal more than 1 (#18766)

## 2024-04-19
- chore(DB/Creature): worldserver error (#18765)
- chore(DB): import pending files
- fix(DB/Gameobject): Sniffed Values for 'Fire' spawns (#18610)

## 2024-04-18
- chore(DB): import pending files
- feat(Core/SmartAI): Add support for waypoint_data in SAI (#18706)

## 2024-04-17
- fix(Core/Characters): Fix crash on characters deletion with COD mails. (#18754)
- fix(Scripts/Pet): Fix crash when spawning lightwell by hand (#18660)

## 2024-04-15
- Merge branch 'master' into Playerbot

## 2024-04-14
- fix(Scripts/Hyjal): fatal error: comparison of integers of different signs (#18755)
- fix(Scripts/Hyjal): fix Mark of Kaz'rogal timer (#18753)
- chore(DB): import pending files
- chore(DB/Creature): Make use of comment field to make explicit which creatures have GUID-specific scripting (#18707)
- Merge branch 'master' into Playerbot
- chore(DB): import pending files
- fix(DB/Spells): Add Pet Spells to Shadowy Necromancer (#18745)
- chore(DB): import pending files
- fix(DB/Creature): Remove Distract immunity from Hyjal bosses except A… (#18737)
- fix(DB/Creature): Al'lar should despawn on evade (#18736)
- fix(Scripts/Hyjal): Azgalor Doom should not be cast on the MT (#18738)
- fix(Core/Spells): Dive Bomb should not share damage (#18740)
- fix. Prevent character deletion if you have an email (#18743)

## 2024-04-13
- fix(Docker): Fix docker compose build failed when using USER with UID:GID != 1000 (#18731)
- fix(Scripts/Hyjal): Fix Mark of Kazrogal not dealing damage when unab… (#18732)
- chore(DB): import pending files
- fix(DB/Creature): Towering Infernals should be immune to taunt (#18733)
- fix(Core/Spells): Fix Anetheron sleep only targetting himself (#18735)

## 2024-04-12
- fix(Core/Scripts): Fix one more typo after scripts refactoring (#18730)
- fix(Scripts/Hyjal): Archimonde finger of death condition (#18681)
- fix(Core/PlayerScript): Fix adding XP on quest completion and other overlooks. (#18728)
- feat(Core/Scripts): Optimize AchievementScript (#18705)
- feat(Core/Scripts): Optimize AllBattlegroundScript (#18704)
- feat(Core/Scripts): Optimize AllCommandScript (#18703)
- feat(Core/Scripts): Optimize AllSpellScript (#18702)
- feat(Core/Scripts): Optimize GameEventScript (#18711)
- feat(Core/Scripts): Optimize GroupScript (#18713)
- feat(Core/Scripts): Optimize GuildScript (#18714)
- feat(Core/Scripts): Optimize LootScript (#18715)
- feat(Core/Scripts): Optimize MailScript (#18716)
- feat(Core/Scripts): Optimize MiscScript (#18719)
- feat(Core/Scripts): Optimize PetScript (#18720)
- feat(Core/Scripts): Optimize ServerScript (#18721)
- feat(Core/Scripts): Optimize UnitScript (#18722)
- feat(Core/Scripts): Optimize WorldObjectScript (#18723)
- feat(Core/Scripts): Optimize WorldScript (#18724)
- feat(Core/Scripts): Optimize GlobalScript (#18712)
- feat(Core/Scripts): Optimize FormulaScript (#18710)
- feat(Core/Scripts): Optimize DatabaseScript (#18709)
- refactor(Core/Scripts): Optimize Script (#18708)
- fix(Core/Scripts): Fix build and crash when calling uninitialized scripts (#18718)
- feat(Core/Scripts): Optimize AuctionHouseScript need#18672 (#18698)
- feat(Core/Scripts): Optimize ArenaTeamScript need#18672 (#18699)
- feat(Core/Scripts): Optimize ArenaScript need#18672 (#18700)
- feat(Core/Scripts): Optimize MovementHandlerScript need#18672  (#18701)
- feat(Core/Scripts): Optimize AccountScript need#18672 (#18697)

## 2024-04-11
- feat(Core/Scripts): Optimize PlayerScripts by calling only overridden/implemented functions. (#18672)

## 2024-04-10
- fix(Scripts/Karazhan): Fix crash in chess event. (#18695)
- fix(Scripts/TheEye): Kaelthas: Roar timer (#18677)
- fix(Scripts/TheEye): make Al'ar not get stuck during dive bomb when no enemies in melee range (#18693)
- Merge branch 'master' into Playerbot

## 2024-04-09
- (Scripts/Ahnkahet): Fixed problem gathering GUIDS from bosses. (#18689)

## 2024-04-08
- fix(Scripts/Hyjal): make sure Jaina takes no damage from Death and Decay (#18680)

## 2024-04-07
- chore(DB): import pending files

## 2024-04-08
- fix(DB/Hyjal): weird loot format for Archimonde (#18682)
- fix(Scripts/TheEye): increase Void Reaver boundary so he does not reset when tanked against the wall (#18683)

## 2024-04-07
- Merge branch 'master' into Playerbot

## 2024-04-06
- fix(Scripts/TheEye): Fix Alar not using abilities if no target is in … (#18678)
- feat(Core/Optimization): Correctly document sendBuffer size and optimize it. (#18647)
- fix(Scripts/TempleOfAhnQiraj): Fix Vem enrage (#18652)
- fix(Scripts/Commands): "go xyz" command crash (#18676)

## 2024-04-05
- fix(Script/BlackTemple): Add override in EnterEvadeMode (#18673)
- fix(CI): Don't cache pch builds (#18674)
- fix(Core/Player): Fix memory leak. (#18671)
- feat(Core/Optimization): Optimize build of units update object by leveraging cache (#18637)

## 2024-04-04
- fix(Core/Battleground): correctly limit Eye of the Storm max points to 1600 (#18669)

## 2024-04-03
- chore(DB): import pending files
- fix(Scripts/BlackTemple): Illidan not accessing Akama's guid (#18665)
- chore(DB): import pending files
- fix(DB/Gameobject): remove duplicate 'Door' spawns in Black Temple (#18656)

## 2024-04-02
- chore(DB): import pending files
- fix(Scripts/BlackTemple): Rewrite Shade of Akama (#18601)
- fix: Loch Modan multiple ore spawn (#18616)
- fix(DB/Gameobject): Sniffed Values for 'Forge' spawns (#18620)
- fix(Scripts/TheEye): Fix crash in Kaelthas. (#18653)
- chore(DB): import pending files
- fix(Scripts/TheEye): Lord Sanguinar's Bellowing Roar timer (#18651)
- fix(DB/Creature): Void Reaver Movement Speed and Model Info (#18650)
- chore(DB): import pending files
- fix(DB/TheEye): remove unused reference and add Talon of the Phoenix back (#18643)
- fix(DB/TheEye): allow Kael to drop 2 non-token items (#18639)

## 2024-04-01
- fix(Scripts/TheEye): fix targetting logic in Void Reaver (#18646)
- feat(Core/Optimization): Create index for sSkillLineAbilityStore to speedup search by skillLine. (#18622)
- feat(Core/Optimization): Reduce CPU consumption by allocating sendBuffer only when it is needed. (#18628)

## 2024-03-31
- chore(DB): import pending files
- fix(Scripts/Hyjal): Shadowy Necromancers now use Unholy Frenzy + Skeleton mage abilities (#18640)
- fix(DB/TheEye): remove faulty talon of al'ar reference from reference loot template (#18641)
- Merge branch 'master' into Playerbot

## 2024-03-30
- chore(DB): import pending files
- fix(DB/TheEye): make Thaladred walk (#18629)
- fix(CI): correct name suffix of PCH jobs (#18632)
- chore(DB): import pending files
- fix(DB/Gameobject): update initial state of some Brazier spawns (#18633)
- fix(Scripts/BossAI): add optional variable to BossAI class to make sure the boss calls for help (#18630)
- fix(ci): ensure module build clones modules (#18631)

## 2024-03-29
- Fix(CI): Don't use PCH on nopch builds (#18627)

## 2024-03-28
- feat(Core/Compression): Move packets compression from map to network thread (#18602)
- Merge branch 'master' into Playerbot

## 2024-03-27
- feat(CI): rework core ubuntu build, ubuntu-22 support (#17281)
- fix(Scripts/Hyjal): Archimonde refactored (#18594)
- chore(PlayerScript/Hook) : Add CanSetTradeItem Hook in PlayerScript (#18583)
- feat(core): account delete hook (#18605)

## 2024-03-26
- fix(Scripts/SSC): make adds reset when one leaves the room (#18614)
- fix(Scripts/TheEye): make Void Reaver abilities ignore LOS (#18613)

## 2024-03-25
- docs(README): update Authors & Contributors (#18589)

## 2024-03-24
- chore(DB): import pending files
- (Instance/Culling of Stratholme/Trial of Crusader) removed duplicated gossip_menus, fixed hardcoded texts (#18516)
- chore(DB): import pending files
- fix(DB/Gameobject): Sniffed Values for 'Mighty Blaze' spawns (#18560)
- fix(DB/Gameobject): Sniffed Values for 'Blazing Fire' spawns (#18562)
- chore(DB): import pending files
- fix(DB/Gameobject): Sniffed Values for '%Anvil%' spawns (#18600)
- fix(DB/Quest): Quest chaining for quest 9759 (#18325)
- chore(DB): import pending files
- fix(DB\Creatures): updating npcflags on Blackrock Bar mobs (#17236)
- chore(DB): import pending files
- fix(DB/Item): Change races for Fluorescent Green Mechanostrider (#18069)
- chore(DB): import pending files
- fix(db/sai) Modified summoned felhunter smart AI (#18126)
- chore(DB): import pending files
- fix(DB/SAI): Added a talking event between Creature 26828  (#18503)
- chore(DB): import pending files
- fix(DB/Gameobject): Sniffed Values for '%Brazier%' spawns (#18609)

## 2024-03-23
- chore(DB): import pending files
- fix(DB/Gameobject): Sniffed Values for 'Campfire' spawns (part 2) (#18606)
- fix(DB/Gameobject): Sniffed Values for 'Burning Embers' spawns (#18607)

## 2024-03-22
- fix(Scripts/HyjalSummit): Frost Wyrms casting wrong spell (#18603)
- fix(Scripts/HyjalSummit): Don't reset trash counter on scheduled waves (#18604)
- Merge branch 'master' into Playerbot

## 2024-03-21
- fix(Scripts/TheEye): Alar dont take 2% damage during dive bomb (#18599)
- fix(Scripts/TheEye): make sure schedules are cancelled when advisors die in p1 (#18592)

## 2024-03-20
- fix(Scripts/TheEye): Make Solarian visible on phase transition (#18585)
- fix(Scripts/Mechanar): Fix Ranging Flames should choose a new target … (#18586)
- fix(Scripts/TheEye): Fix Ember of Alar ember blast percent damage (#18588)
- fix(Core/Spell): Fix spell 35329 (Vibrant Blood) (#18587)
- feat(build): initial development nix flake (#18296)
- chore(DB): import pending files
- fix(DB/Formation) Scholo: Make Alexei Barov's adds respawn correctly (#17590)
- fix(Core/Spells): Fixed work of sobering spells and other improvements for drunk system (#18390)
- chore. Correctly disable gm command dbg messages by default (#18315)
- chore(DB): import pending files
- fix(DB/Gameobject): Sniffed Values for 'Wooden Bench' spawns (part 2) (#18528)
- fix (Core/Scripting): SMART_EVENT_NEAR_PLAYERS  (#18514)
- fix(DB/Gameobject): Sniffed Values for 'Door' spawns (#18566)

## 2024-03-19
- fix(Scripts/TheEye): fix MC overlap (#18584)
- chore(DB): import pending files
- fix(Scripts/HyjalSummit): Rewrite Battle for Mount Hyjal (#18512)
- Merge branch 'azerothcore:master' into Playerbot

## 2024-03-18
- chore(DB): import pending files
- fix(DB/BlackTemple): Rework Black Temple (#18569)
- chore(DB): import pending files
- fix(DB/Gameobject): Sniffed Values for 'Warm Fire' spawns (#18565)
- chore(DB): import pending files
- fix(DB/Gameobject): Sniffed Values for 'Dwarven Campfire' spawns (#18578)
- chore(DB): import pending files
- fix(Scripts/TheEye): fix Kael progress bug and some other issues (#18580)
- Fix macos CI
- Disable test build for macos CI
- CI ignore warnings
- Fix macos compilation
- Fix macos CI

## 2024-03-17
- Fix macos CI
- chore(DB): import pending files
- fix(DB/Creature) Underground Orgrimmar Grunt (#18532)
- Merge branch 'azerothcore:master' into Playerbot

## 2024-03-16
- chore(DB): import pending files
- fix(Scripts/TheEye): increase dagger proc chance and make sure mind control only targets players (#18563)
- fix(Scripts/Commands): Fix crash when using additem from console (#18559)

## 2024-03-15
- chore. Avoid failures in the tests of custom items (#18519)
- chore(DB): import pending files
- feat(Scripts/Commands): Implement ".reset items" command (#18393)
- fix(Core/Spells): Domination affect max 5 targets (#18555)
- fix(SpellInfoCorrections) Raid buffs should ignore LoS (#18518)
- fix(Scripts/TheEye): another Al'ar hotfix (#18554)

## 2024-03-14
- fix(Scripts/TheEye): make sure Al'ar doesn't schedule abilities multiple times (#18553)

## 2024-03-13
- fix(Scripts/TheEye): maybe fix Al'ar transition (#18552)
- chore(DB): import pending files
- refactor(Core): remove some unused variables (#18538)
- fix(DB/Gameobject): fix phaseMask of two 'Bench' spawns (#18541)
- chore(DB): import pending files
- fix(Scripts/TheEye): remove auras from Solarian on invisiblity and sniffed spell (#18544)
- fix(DB/TheEye): make falconer move towards you (#18542)

## 2024-03-12
- fix(Scripts/TheEye): allow Solarian to cast on pets/totems (#18539)
- fix(Scripts/TheEye): make sure Al'ar doesn't cast anything during rebirt + phoenix spawning (#18540)
- Merge branch 'azerothcore:master' into Playerbot
- Update core-build.yml
- Update workflows
- Fix variable unused warning
- Fix workflows
- Fix workflows
- Merge pull request #6 from liyunfan1223/revert-5-Playerbot
- Revert "Split Ulduar's script files"
- Merge pull request #5 from Garashan/Playerbot

## 2024-03-11
- chore(DB): import pending files
- fix(Scripts/TempestKeep): Kael pyroblast target only main target (#18531)
- chore(DB): import pending files
- fix(DB/Gameobject): Sniffed Values for 'Bonfire' spawns (#18537)
- Split Ulduar's script files

## 2024-03-10
- fix(CI/MacOS): Fix MacOS dependency installation (#18507)
- fix(Docs): readme: fix broken license links (#18500)
- fix(Docs): readme: fix broken link to CODE_OF_CONDUCT.md (#18499)
- fix(CI): fix tools_build (#18505)
- fix(Core/PVP): Fix OutDoorPVP CustomSpell handling (#18389)
- fix(Scripts/TheEye): boss boundaries and Kael door (#18517)
- chore(DB): import pending files
- fix(DB/Item): 44844 'Turkey Caller' - add flag CU_DURATION_REAL_TIME (#18328)

## 2024-03-09
- fix(Scripts/Karazhan): Correct chess piece gossip faction check. (#18513)
- fix(Scripts/TheEye): ensure Ember of Al'ar always spawn in the right spot (#18511)
- chore(DB): import pending files
- fix(DB/Gameobject): Sniffed Values for 'Bench' spawns (#18448)
- fix(Scripts/Karazhan): Chess Event Cross Faction (#18478)
- Merge branch 'master' into Playerbot

## 2024-03-08
- chore(DB): import pending files
- fix(DB/Gameobject): Sniffed Values for 'Chair' spawns (part 2) (#18509)
- fix(Core/SmartScripts): LOS check  spell  for SmartScipts (#18501)
- chore(DB): import pending files
- fix(DB/SAI): Remove Shadowlord Deathwail's immunity. (#18508)
- chore(DB): import pending files
- fix(Scripts/TheEye): make Solarian not overlap casts and not cast arcane missiles into p2 transition (#18480)

## 2024-03-06
- fix(Scripts/TheEye): Al'ar phoenix spawn positions in p2 (#18504)
- Merge pull request #4 from MrSlntGhost/Playerbot
- chore(DB): import pending files
- fix(DB/Creature): Kael Phoenix should not be immune to slows (#18502)

## 2024-03-05
- Fix docker load metadata error

## 2024-03-04
- fix(Scripts/TheEye): make sure Solarian does not cast arcane missiles on target with Wrath of the Astromancer active (#18496)
- chore(DB): import pending files
- Fix(DB/SAI) update quest 6002 poi and text (#18465)
- chore(DB): import pending files
- fix(DB/Gameobject): Add some missing 'Anvil, Forge, Alchemy Lab' spawns (#18432)
- chore(DB): import pending files
- fix(DB/Creature): High King Maulgar's council saving you to the insta… (#18494)
- fix(Scripts/TheEye): amend Al'ar divebomb timer in p2 (#18495)
- chore(DB): import pending files
- fix(DB/TheEye): Nether Scryer and Phoenix Hawk spell behaviour (#18492)
- chore(DB): import pending files
- fix(DB/Spell): Correct Al'ar flame quill target positions (#18490)
- chore(DB): import pending files
- fix(DB/Translation/FR) : Deputy Willem greetings gossip text (#18370)
- fix(Scripts/TheEye): make sure Telonicus doesn't erroneously cast Conflagration and cast Remote Toy instead (#18481)
- fix(Scripts/TheEye): make sure Al'ar does not melee during transitions (#18479)
- fix(Scripts/TheEye): make legendary TK dagger have  100% proc chance (#18482)
- Merge branch 'master' into Playerbot

## 2024-03-03
- chore(DB): import pending files
- fix(DB/Gameobject): Sniffed Values for 'Barber Chair' spawns (#18450)
- chore(DB): import pending files
- fix(DB/World): Creatures not respawning within pools of their own (#18464)
- Fix ServerScript.h
- Merge branch 'master' into Playerbot

## 2024-03-01
- fix(Scripts/SerpentshrineCavern) Filter Watery Grave Target (#18463)

## 2024-02-27
- chore(DB): import pending files
- fix(DB/Gameobject): Sniffed Values for 'Wooden Chair' spawns (#18378)
- fix(Core/Creature): Prevent combat movement disabled creatures from r… (#18428)
- chore(DB): import pending files
- fix(DB/Gameobject): Sniffed Values for 'Chair' spawns (#18427)

## 2024-02-26
- chore(DB): import pending files
- fix(DB/Creature): Remove interrupt immunity from Staff of Disintegrat… (#18415)
- fix(Cmake): using policy 0153 if exist (#18416)

## 2024-02-25
- fix(Core/Spell): Fix crash in Rogue T10 4P Bonus (#18413)
- fix(Scripts/TheEye): Fix Capernian not casting if at max range (#18402)
- feat(Core/UpdateTime): Improve diff time measurement. (#18387)
- chore(Common/Debugging): change report codestyle (#18383)
- feat(Cmake): add support old policy 0153 (#18384)
- chore(Core/Shared): little cleanup (#18385)
- fix(Conf): remove ThreatRadius (unused) (#18329)
- fix(Core/SmartAI): implement param maxCount for SMART_TARGET_PLAYER_RANGE (#18394)
- chore(DB): import pending files
- fix(Scripts/TheEye): remove faulty aurascript and do visual transition in normal script instead (#18395)
- chore(DB): import pending files
- fix(Scripts/TheEye): Kael'thas - allow phases to progress as well when all creatures die as well as other fixes (#18397)
- chore(DB): import pending files
- fix(DB/Spells): allow Armor Disruption from Netherstrand Longbow to stack (#18398)
- fix(DB/Conditions): allow Crystalcore Mechanics to only repair mechanicals (#18400)

## 2024-02-24
- Merge branch 'master' of github.com:azerothcore/azerothcore-wotlk into Playerbot

## 2024-02-23
- chore(DB): import pending files
- fix(DB/Gameobject): Sniffed Values for 'Stone Bench' spawns (#18381)
- chore(DB): import pending files
- fix(DB/Gameobject): Sniffed Values for 'Wooden Bench' spawns (#18382)
- fix(DB/Gameobject): Sniffed Values for 'Highback Chair' spawns (#18380)
- fix(Crash/Quest/Spell) : The Boon of Remulos (#18379)

## 2024-02-22
- Merge branch 'master' into Playerbot

## 2024-02-21
- fix(Scripts/TheEye): Fix Capernian chase distance (#18372)
- chore(DB): import pending files
- fix(Scripts/TerokkarForest): fix behaviour of skull piles in Skettis (#18371)

## 2024-02-20
- chore(DB): import pending files
- fix(DB/Custom): Wand of Holiday Cheer PVP tagging. (#18333)
- fix(Core/ItemStorage): Fix container items count on server load (#18367)
- chore(DB): import pending files
- fix(DB/Creature): Crystalcore Sentinel interrupt immunity (#18366)
- fix(Scripts/TheEye): Thaladred should only chase players (#18365)
- fix(DB/SAI): unlink non-existing entry from SAI 17671 (#18368)
- chore(DB): import pending files
- fix(DB/HellfirePeninsula): remove faulty Blizzard spell from Arch Mage Xintor and add rp events (#18362)
- chore(DB): import pending files
- fix(DB/Hinterlands): make Innkeeper Thulfram patrol (#18357)
- chore(DB): import pending files
- fix(Scripts/SSC): remove double spawn of Seer Olum and implement correctly (#18364)

## 2024-02-19
- fix(Core): Prevent gift wrapping of limited duration items (#18334)
- fix(Core/Guild): Prevent swapping limited duration items into guild bank (#18335)
- chore(DB): import pending files
- fix(DB/Gameobject): Sniffed Values for 'Subway Bench' (#18355)
- Merge branch 'master' into Playerbot
- fix(Scripts/SSC): do reset threat list for p3 in the right place (#18354)

## 2024-02-18
- fix(Core/GameObject): Remove unneeded ClearGossipMenuFor call (#18331)
- chore(DB): import pending files
- fix(DB/Creature): Sniffed Values for 37214 'Crown Lackey' (#18341)
- chore(DB): import pending files
- fix(DB/Creature): Sniffed Values for 37917 'Crown Thug' (#18342)
- fix(DB/Creature): Sniffed Values for 37984 'Crown Duster' (#18343)
- chore(DB): import pending files
- fix(DB/Creature): Sniffed Values for 38006 'Crown Hoodlum' (#18344)
- chore(DB): import pending files
- fix(DB/Creature): Sniffed Values for 38016 'Crown Agent' (#18345)
- chore(DB): import pending files
- fix(DB/Creature): Sniffed Values for 38023 'Crown Sprinkler' (#18346)
- fix(DB/Creature): Sniffed Values for 38030 'Crown Underling' (#18347)
- chore(DB): import pending files
- fix(DB/Creature): Sniffed Values for 38032 'Crown Sprayer' (#18348)
- fix(DB/Gameobject): Sniffed Values for 19878 'Parts Crate' (#18352)

## 2024-02-13
- chore(DB): import pending files
- fix(DB/Spell): Valentine event buffs grouping (#18319)

## 2024-02-14
- Merge branch 'master' into Playerbot

## 2024-02-13
- Fix(Docker): Add missing dollar sign (#18314)
- chore(DB): import pending files
- Fix(DB) Heart of Acherus seeable daemons (#18199)

## 2024-02-12
- chore(DB): import pending files
- feat(SQL/creature_text) Assign missing BroadcastTextId (#18294)
- fix(Scripts/TheEye): A'lar stop casting flame buffet when any valid t… (#18313)
- chore(DB): import pending files
- fix(Core/Taxi): Fixes crash when player logins and continues flight (#18270)
- fix(Scripts/Hyjal): move Hyjal boss waypoints to DB (#18299)
- fix(Scripts/TheEye): make sure Solarian always get reset to REACT STATE aggressive on reset (#18302)
- chore(DB): import pending files
- fix(DB/Creature): Astromancer and Star Scryer MC immunity (#18303)
- fix(Scripts/TheEye): some Al'ar fixes (#18305)
- chore(DB): import pending files
- fix(DB/SAI): add abilities to Nether Scryer (#18308)
- fix(DB/SAI): change the way Phoenix Hawk targets players with its abilities (#18309)
- fix(DB/Gameobject): Sniffed Values for 201716 'Chemical Wagon' (#18311)

## 2024-02-11
- Merge branch 'master' into Playerbot
- feat(fix/build) ignore mariadb in the conditional (#18310)
- feat(Core/Hooks): Add the KillRewarder reference to the OnRewardKillRewarder hook. (#18290)

## 2024-02-10
- fix(Core/Database) mysql_stmt_bind_param deprecated in MySQL 8.3 (#18295)
- fix(Deps): Fixed finding openssl 3.2 on windows (#18284)
- feat(Core/Unit): New helper IsClass and script hook OnPlayerIsClass (#18243)

## 2024-02-09
- fix(Conf): disable LeaveGroupOnLogout by default (#18245)
- feat(Core/Unit): New helper HasActivePowerType and script hook OnPlayerHasActivePowerType (#18293)

## 2024-02-08
- chore(deps/boost): Update cmake file compatible with new policies (#18283)
- fix(Scripts/TheEye): Solarian movement (#18268)
- chore(DB): import pending files
- fix(Core/Creature): hardcoded gossip in zone_azshara (#18289)
- chore(DB): import pending files
- refactor(Scripts/ZulAman): refactor Halazzi (#18267)
- fix(Scripts/TheEye): refactor Al'ar (#18264)
- fix(Scripts/TheEye): Re-factor Kael'thas (#18272)

## 2024-02-06
- chore(DB): import pending files
- fix(Scripts/SSC): some Vashj fixes (#18276)
- Merge branch 'master' into Playerbot

## 2024-02-05
- chore(DB): import pending files

## 2024-02-06
- fix(DB/Karazhan): remove smart_script linking so Mana Warps properly die even when stunned (#18255)

## 2024-02-05
- chore(DB): import pending files
- fix(DB/Creature): 'Shaman Bonfire Bunny' spawns with sniffed values (#18275)
- chore(DB): import pending files
- fix(DB/Gameobject): Update 'Campfire' spawns with sniffed values (#18235)
- chore(DB): import pending files
- fix(DB/Creature): Sniffed Values for 25924 'Twilight Speaker Viktor' (#18273)
- chore(DB): import pending files
- fix(DB/Creature): reassign equipment_id to creatures 25949, 26221 (#18274)

## 2024-02-04
- chore(DB): import pending files
- fix(DB/ShadowmoonValley): add Arcane Explosion to Arcane Bursts and make them despawn (#18271)
- fix(Scripts/TheEye): add Kael adds to the cpp script (#18257)

## 2024-02-03
- chore(DB): import pending files
- fix(Scripts/Dalaran): Update Toy Shop Toy Plane behaviour based on sniffs (#18239)
- Fix(Core/CharacterHandler): Incorrect behavior using an equipment set… (#18253)
- chore(DB): import pending files
- fix(DB/Midsummer): disable unrelated debris spawns in front of the Ex… (#18252)
- Check if triggered spell has cast time (#18231)
- chore(DB): import pending files
- fix(DB/Creature): Sniffed Values for 26221 'Earthen Ring Elder' (#18263)
- chore(DB): import pending files
- fix(DB/Creature): Sniffed Values for 25949 'Ice Caller Briatha' (#18262)
- fix(DB/Creature): Sniffed Values for 25951 'Heretic Emissary' (#18261)
- fix(DB/Creature): Sniffed Values for 26124 'Midsummer Merchant' (#18259)
- fix(DB/Creature): Sniffed Values for 25980 'Heretic Bodyguard' (#18260)
- fix(DB/Creature): Sniffed Values for 26123 'Midsummer Supplier' (#18258)

## 2024-02-01
- chore(DB): import pending files
- fix(DB/Creature): Add Repair npcflag to 28344 Blazzle (#18242)
- chore(Docker): update mysql image to 8.3 version (#18244)
- chore(DB): import pending files
- fix(Scripts/Midsummer): Add SpellScript for "Fire Festival Fortitude" (#18246)

## 2024-01-31
- chore(DB): import pending files
- fix(Core/Quests): Create quest money reward config and adjust max level bonus reward function. (#18222)

## 2024-01-30
- fix(Scripts/SSC): make sure Vashj faces the random people when doing Forked Lightning (#18232)

## 2024-01-29
- Merge branch 'master' into Playerbot
- chore(DB): import pending files
- fix(DB/TheEye): fix some trash immunities in The Tempest Keep (#18233)

## 2024-01-26
- feat(Core/Spell): Add helper for TriggeredCastFlag (#18227)

## 2024-01-23
- fix(Core/Misc): typo (#18221)
- chore(DB): import pending files
- fix(DB/Events): Correct some GameEvent changes (#18216)
- fix(Conf): typo (#18209)
- Merge branch 'master' into Playerbot

## 2024-01-21
- fix(Core/DatabseWorkerPool): implement DatabaseIncompatibleVersion to better support MariaDB (#18201)
- fix(Core/Creature): Remove automated z spawn correction (#18200)
- chore(DB): import pending files
- fix(DB): Collation error (#18204)

## 2024-01-20
- chore(DB): import pending files
- fix(Scripts/Midsummer): Correct behavior for Striking Back quests. (#18171)

## 2024-01-21
- fix(Scripts/Command): prevent crash on set motd (#18203)

## 2024-01-20
- feat(DB): Release ACDB 10.0.0 (#18197)
- chore(DB): import pending files
- refactor(DB): Move old archive files to old dir (#18164)
- chore(DB): import pending files
- fix(DB/Gameobject): Sniffed Values for 181637 'Sha'naar Relic' (#18188)
- fix(DB/TheEye): change spelltimers based on sniffs (#18186)
- fix (Core/Unit) Apply Capacitor cooldown on trigger proc instead of on stack add (#18189)
- chore(DB): import pending files
- fix(DB/Creature): Update Dalaran 'The Wonderworks' creatures with SAI… (#18192)
- fix(DB/Creature): fix additional guid conflicts (#18195)
- fix(Scripts/SSC): make sure Vashj doesn't move during P2 (#18187)

## 2024-01-16
- chore(DB): import pending files
- fix(DB/SAI): make sure conjured elementals on Aran don't move after spawning (#18183)
- chore(DB): import pending files
- fix(DB/SAI): Make sure Lurker archers don't move after spawning (#18184)
- fix(DB/SAI): Make sure Tainted Elementals on Vashj have better movement (#18185)
- fix(Scripts/IcecrownCitadel): Fix Sindragosa respawn (#18179)

## 2024-01-15
- Merge branch 'master' into Playerbot
- chore(DB): import pending files

## 2024-01-14
- chore(DB/Creature): fix guid conflicts (#18170)
- chore(DB): import pending files
- fix(CORE/OPvP): Halaa Mechanics not working properly (#15634)
- chore(DB): import pending files
- fix(DB/IcecrownCitadel): Fix Rotface resetting behaviour (#17878)
- chore(DB): import pending files
- fix(Scripts/Karazhan): Add cleave and threat resets to Nightbane (#18133)
- fix(DB/Creature): Update all commoneer talking intervals to 300s (#18165)
- chore(DB): import pending files
- fix(Scripts/IcecrownCitadel): Lich King Whispers uses localized languages (#18125)
- chore(DB): import pending files
- fix(DB/SAI): Move GameObjectScript go_midsummer_bonfire to SAI (#18135)
- fix(Core/Player): Fix Player not starting at full health (#18136)
- fix(DB/Gameobject): Sniffed Values for 180665 'Draconic for Dummies' (#18137)
- fix(DB/Gameobject): Sniffed Values for 181305 'Camp Table' (#18138)
- chore(DB): import pending files
- fix(DB/Gameobject): Sniffed Values for 180045 'Stormwind Gypsy Wagon' (#18144)
- chore(DB): import pending files
- fix(DB/Creature): Update 'Magical Menagerie' Cosmetic creature spawns… (#18152)
- fix(DB/Gameobject): Sniffed Values for 181306 'Camp Jug' (#18159)
- fix(DB/Gameobject): Sniffed Values for 181302 'Camp Crate' (#18158)
- fix(DB/Gameobject): Sniffed Values for 180046 'Chair' (#18145)
- chore(DB): import pending files
- fix(DB/Gameobject): Sniffed Values for 181307 'Camp Mug' (#18160)
- fix(DB/Creature): Warlock trainers in Orgrimmar should talk orcish (#18166)
- fix(DB/Gameobject): Midsummer gameobject spawn cleanups (#18168)
- Merge branch 'master' into Playerbot

## 2024-01-13
- feat(Core/Scripting): Implement new hook OnBeforePlayerLogout() (#18163)
- fix(Core/ThreatMgr): Remove temp threat on resetting threat list (#18162)

## 2024-01-12
- fix(Scripts/Rogue): Fix Vanish not granting stealth (#18155)

## 2024-01-11
- chore(DB): import pending files
- fix(DB/Creature): Sniffed Values for 28344 'Blazzle' (#18154)
- fix(Core/Creature): Reduce z offset for automated spawn correction (#18153)

## 2024-01-10
- fix(CI): revert `if` in job conditionals on docker build (#18147)

## 2024-01-08
- fix(CI): Probably fix vanishing CIs from PRs (#18124)
- chore(DB): import pending files
- fix(DB/Creature): Orgrimmar Grunt directions for barber shop (#18131)
- chore(DB): import pending files
- fix(Scripts/Quest): improve Securing the Celestial Ridge (#17847)

## 2024-01-09
- fix(Scripts/PilgrimsBounty): Correct text for Turkey Tracker (#18123)

## 2024-01-08
- refactor(CI): Squash docker ci into one workflow (#17880)
- Merge branch 'master' into Playerbot
- chore(DB): import pending files
- fix(DB/Conditions): Fix Midsummer Bonfire gossip menu option conditions (#18134)
- chore(DB): import pending files
- fix(DB/Creature): Vashj's Enchanted Elementals knockback immunity (#18132)

## 2024-01-07
- fix(Scripts/SerpentshrineCavern): Fix Lurker pool not respawning afte… (#18130)
- chore(DB): import pending files
- feat(Scripts/Commands): Implement gameobject respawn command (#18129)
- chore(DB): import pending files
- fix(DB/Loot): port drop chances for Insane Strength Potion and Mana Pot Injector recipes from CMaNGOS (#18091)
- fix(Core/Player): Sometimes Player whisper is sent as boss whisper (#18128)
- chore(DB): import pending files
- fix(Script/Spell): Vanish Purge behavior (#18127)
- Merge branch 'master' into Playerbot
- fix(DB): Bad query (#18122)
- chore(DB): import pending files
- fix(DB/Creature): Fixed a dialogue error when "Tendris Warpwood" died (#18088)
- fix(DB): Correct bad delete query (#18121)

## 2024-01-06
- chore(DB): import pending files
- fix(DB/Loot): change Ranger-General's Chestguard on Lurker to The Seal of Danzalar (#18117)
- fix(Scripts/SSC): Update Hydross Mark Timers (#18114)
- Merge branch 'master' into Playerbot
- chore(DB): import pending files
- fix(DB/Gameobject): Update 'Caribou Trap' spawns with sniffed values (#18085)

## 2024-01-05
- chore(DB): import pending files
- fix(DB/Creature): Fix Shadow of Leotheras banish immunity (#18111)
- chore(DB): import pending files
- fix(DB/Creature): Fix '(Master) Fire Eater' / '(Master) Flame Eater' spawns and SAI based on sniffs (#18073)
- chore(DB): import pending files
- fix(DB/SAI): remove botched caster movement scripting from Arch Mage Xintor (#18108)
- fix(DB/Creature): Update 'Commoner' spawns with sniffed values (#18110)

## 2024-01-04
- fix(Core/Quest): Calculate reward money with RATE_REWARD_BONUS_MONEY … (#18104)
- Merge branch 'master' into Playerbot

## 2024-01-03
- chore(DB): import pending files
- fix(DB/TempestKeep): Rebuild Tempest Keep (#18105)
- chore(DB): import pending files
- fix(DB/TerokkarForest): add patrol movement to Ironjaw (#18086)
- fix(Core/LFG): Hide XP from max players (#18103)
- chore(DB): import pending files
- fix(DB/Conditions): Quest Sniffing Out the Perpetrator (#18098)
- chore(DB): import pending files
- Fix combat movement (#18026)

## 2024-01-02
- chore(DB): import pending files
- fix(DB/Nagrand): script Gava'xi OOC rp with sniffs (#18089)

## 2024-01-01
- fix(Core/Player): Check if the player can summon the warlock pet on B… (#18064)
- chore(DB): import pending files
- refactor(Scripts/Areatrigger): Move Scholazar Waygate script to SAI (#18054)
- refactor(Scripts/TheEye): Update Astromancer's spellscripts to new re… (#18058)
- feat(Core/World): Implement DoForAllPlayers() helper for all online p… (#18060)
- chore(DB): import pending files
- fix(Scripts/Midsummer): Improve Torch Catching based on sniffs (#18071)
- chore(DB): import pending files
- fix(DB/Creature): change Morogrim's combat reach and model bounds based on sniffs (#18094)
- chore(DB): import pending files
- fix(DB/BloodmystIsle): add sniffed abilities to Sunhawk Spy (#18093)
- fix(Core): Fix item disappearing on selling item on auction (#18090)
- chore(DB): import pending files
- fix(DB/SAI): add sniffed abilities to Zarakh (#18092)
- fix(Core/Unit): Remove delay for Conflagrate aura state (#18068)
- chore(DB): import pending files
- fix(DB/Gameobject): Update all 'Mailbox' spawns with sniffed values (#18072)
- refactor(Core/GameObject): Move the GameObject state save handling to… (#18080)

## 2023-12-30
- chore(DB): import pending files
- fix(DB/Custom): Rotting Touch should stack from different sources (#18079)
- fix(Scripts/ScarletMonastery): Prevent Whitemane from dying before resurrecting Mograine (#18082)

## 2023-12-28
- chore(Scripts/EK): remove useless includes (#18075)
- Merge pull request #2 from oiuv/Playerbot
- Merge pull request #1 from AlvinZhu/Playerbot
- Merge branch 'master' into Playerbot
- chore(DB): import pending files
- fix(DB/Creature): Update 'Flame Keeper' / 'Flame Warden' spawns with … (#18067)

## 2023-12-27
- Force playerbots locale enUS
- Fix multi-language DBC loading

## 2023-12-26
- chore(DB): import pending files
- fix(DB/Creature): Spawn NPC 'Crown Apothecary' for event 'Love is in the Air' … (#18066)
- chore(Scripts/Kalimdor): remove useless includes (#18065)

## 2023-12-25
- chore(DB): import pending files
- fix(DB/Creature): Leotheras the Blind banish immunity (#18057)
- feat(Core/Spells): Implement SPELL_ATTR0_CU_BYPASS_MECHANIC_IMMUNITY (#18056)
- chore(DB): import pending files
- fix(Scripts/Midsummer): Implement Midsummer Bonfire mechanics (#18023)
- chore(Scripts/Northrend): remove useless includes (#18061)

## 2023-12-24
- chore(Scripts/Outland): Remove useless includes (#18049)
- chore(Scripts): Remove placeholder Ironforge/AlteracMountains files (#18047)
- chore(Scripts/World): Remove unused legacy scripts (#18048)
- chore(DB): import pending files
- fix(DB/Creature): update various midsummer spawns with sniffed values (#18025)
- chore(DB): import pending files
- fix(DB/Procs): Spell Bomb not having cooldown (#18029)
- fix(Scripts/Spells): Fix Ritual of Souls with Improved Healthstone

## 2023-12-23
- chore(Core): remove useless includes (#18036)
- fix(Scripts/SerpentshrineCavern): Despawn Lurker's pool and fix visua… (#18037)

## 2023-12-22
- refactor(Scripts): remove useless includes (#18004)

## 2023-12-17
- Merge branch 'master' into Playerbot
- playerbot logout

## 2023-12-15
- feat(Core/SmartScripts): SMART_EVENT_SUMMONED_UNIT_EVADE (#18018)

## 2023-12-14
- fix(Scripts/SerpentshrineCavern): Fix Lurker spawn coords and spout s… (#18014)

## 2023-12-13
- feat(Core/Object): Play radius sound/music. (#18011)
- fix(Scripts/SSC): play emerge animation on the Lurker Below and make sure whirl doesn't happen during spout (#18009)

## 2023-12-12
- chore(DB): import pending files
- fix(Core/SSC): Rancid Mushroom mechanic (#18008)
- chore(DB): import pending files
- fix(DB/SSC): Trash linked spawn (#18005)
- chore(DB): import pending files
- fix(DB/SSC): Fathom-Guard Caribdis should be able to be interrupted (#18006)
- chore(DB): import pending files
- fix(DB/SAI): Vashj'ir Honor Guard should cast Freightening Shout (#18007)
- fix scripts issue
- Merge branch 'master' into Playerbot
- chore(DB): import pending files
- fix(Scripts/SerpentshrineCavern): fix Hydross not casting Water Tomb … (#18003)
- fix(Scripts/SerpentshrineCavern): Use proper spells to handle the Lur… (#18002)
- chore(Core/Entities): remove useless includes (#17994)
- chore(DB): import pending files
- fix(Event/Midsummer): miscellaneous cleanups of spawns (#17964)
- fix(DB/Creature): Sniffed Values for 17066 'Ribbon Pole Debug Target' (#17956)
- fix(DB/Creature): Sniffed Values for 16592 'Midsummer Bonfire' (#17951)
- fix(Scripts/SerpentshrineCaverns): fix  double submerge phases (#18001)
- chore(DB): import pending files
- fix(DB/Creature): Sniffed Values for 26401 'Summer Scorchling' (#17963)
- chore(DB): import pending files
- fix(DB/Creature): Sniffed Values for 26258 '[DND] Midsummer Bonfire F… (#17957)
- chore(DB): import pending files
- fix(DB/SAI): Events are added after completing a mission (#17974)
- chore(DB): import pending files
- fix(Scripts/Commands): fix wpgps and add sai option for formating (#17990)

## 2023-12-11
- fix(DB/Item): Tainted Core loot rules (#17997)

## 2023-12-12
- chore(DB): import pending files

## 2023-12-11
- fix(DB/SSC): Coilfang Strider should not be immune to snare/root (#17995)
- fix(DB/SSC): Fix Toxic Sporebats Z Position (#17998)

## 2023-12-12
- chore(DB): import pending files

## 2023-12-11
- fix(DB/SSC): update bosses movement speed (#18000)

## 2023-12-12
- chore(DB): import pending files

## 2023-12-11
- fix(DB/Loot): Lady Vashj non-set items (#17996)
- chore(DB): import pending files
- fix(Core/SAI/SSC): Allow Farthest target to set a min distance (#17992)
- fix(Scripts/SSC): make The Lurker Below spout rotate faster again (#17993)
- fix(Core): Build (#17989)
- chore(DB): import pending files
- refactor(Scripts/Outland): Update Doomwalker to new register model (#17987)
- fix(DB/Creature) Add items to Creature hands (#17846)
- refactor(Scripts/UtgardeKeep): Clean up unused variables (#17985)
- chore(DB): import pending files
- fix(DB/SpellScript): remove spell_script_names entry that is no longer used (#17986)
- fix(Scripts/SerpentshrineCavern): The Lurker should emerge once all a… (#17984)
- fix(Scripts/SerpentshrineCavern): Leotheras should engage once adds a… (#17983)
- chore(DB): import pending files
- fix(Core/SSC): Fix Lady Vashj summons (#17982)
- fix(Core/SSC): Added boss boundaries (#17981)

## 2023-12-10
- fix(Scripts/SerpentshrineCavern): Randomize the Lurker spout direction (#17980)
- fix(Core/Spells): Add ignore LOS to Tidal Wave (#17979)
- fix(Scripts/SerpentshrineCavern): Leotheras inner demons should only … (#17976)
- chore(DB): import pending files
- fix(DB/SSC): Added mechanic_immune_mask to a couple creatures (#17977)
- fix(DB/SSC): Added knockback immunity Fathom-Lord adds (#17978)
- chore(DB): import pending files
- fix(DB/Creature): Sniffed Values for 26355 '[DND] Midsummer Bonfire F… (#17958)
- chore(DB): import pending files
- fix(DB/Creature): Sniffed Values for 26520 'Festival Scorchling' (#17959)
- fix(Scripts/SerpentshrineCavern): Fix Hydross not moving before grid … (#17975)

## 2023-12-11
- feat(Core/Hooks): Add OnPlayerJustDied hook (#17973)

## 2023-12-10
- fix(Scripts/Karazhan): fixing the Aran drink routine and reset behavior (#17849)

## 2023-12-09
- chore(DB): import pending files
- fix(DB/Gameobject): Sniffed Values for 181371 'Midsummer Bonfire Spel… (#17966)

## 2023-12-08
- chore(Core/Player): remove unused AnticheatSetSkipOnePacketForASH() function (#17947)

## 2023-12-09
- fix(Scripts/Commands): Crash on go xyz with invalid mapid (#17962)

## 2023-12-08
- refactor(Scripts/Midsummer): use scheduler provided by CreatureAI (#17955)

## 2023-12-07
- chore(DB): import pending files

## 2023-12-08
- fix(Scripts/SSC): codestyle fix in SSC after recent PR (#17952)
- fix(Scripts/SSC): Leotheras demon form fixes (#17953)

## 2023-12-07
- chore(DB): import pending files

## 2023-12-08
- fix(scripts/SerpentShrine): #17918 Errors generated (#17939)

## 2023-12-07
- fix(Game/Scripting): add loading missing lfg scripts (#17949)

## 2023-12-06
- chore(Docs): Update CONTRIBUTING (#17950)
- chore(DB): import pending files
- fix(DB/Pools): Correct Inconspicuous Landmark (#17946)

## 2023-12-04
- chore(DB): import pending files
- fix(DB/Spell): Hellfire Peninsula portal XYZ. (#17937)
- chore(DB): import pending files
- fix(DB/BloodmystIsle): add wander movement to Deathclaw (#17927)
- chore(DB): import pending files
- fix(DB/BloodmystIsle): add SAI to Nazzivus Felsworn (#17920)
- fix(DB/Stormwind): Little Noah now walks around the tanner shop room (#17930)

## 2023-12-03
- refactor(Scripts/SerpetnshrineCavern): Clear up unused variables (#17934)
- feat(Core/Scripting): Implement AfterInstanceGameObjectCreate() global hook (#17935)
- chore(DB): import pending files
- fix(Scripts/HellfirePeninsula): fix quest 9410 a spirit guide (#17925)
- chore(DB): import pending files
- fix(Script/Stormpeaks) fix quest 12862 and 13060 When All Else Fails (#17916)
- chore(DB): import pending files
- fix(Scripts/AlteracValley): Balinda Stoneheart (#17933)
- chore(DB): import pending files
- fix(DB/Quest): Typo in rep requirement for quest 11026 (#17928)
- fix(Core/Quest): Throw error if quest_template RewardItemId is not se… (#17924)
- chore(DB): import pending files
- fix(DB/Gameobject): Sniffed Values - "Striking Back" Quest Midsummer … (#17909)
- chore(DB): import pending files
- fix(DB/SAI): add SAI to Zevrax (#17926)
- chore(DB): import pending files
- fix(DB/SerpentshrineCavern): Rebuild Serpentshrine Cavern from retail sniffs (#17918)
- chore(DB): import pending files
- feat(Scripts/Commands): introduce go creature name (#17910)
- feat(Core/Scripting): move all script objects to separated files (#17860)

## 2023-12-02
- chore(DB): import pending files
- fix(Scripts/Command): Allow player name/guid in additem (#17915)
- feat(Core/ChatHandler): Add SendErrorMessage helper (#17919)
- chore(Core/Misc): rename spellInfo pointers (#17914)

## 2023-11-30
- chore(CI): bump issue labeler version (#17913)
- fix(Core/Channel): potential nullptr reference in Channel::SetOwner() (#17906)
- chore(DB): import pending files
- fix(DB/Quest): Kaw the Mammoth Destroyer (#17859)

## 2023-11-29
- chore(DB): import pending files
- fix(Script/Commands): Make sure learn all lang also give you the skill (#17902)
- fix(DB/Quest): Blade Edge Mountains (#17903)
- refactor(Scripts/MagisterTerrace): Update Vexallus script (#17892)
- fix(Scripts/Commands): Display GUID on gob info (#17900)
- chore(DB): import pending files
- Remove unnecessary SetActive in DK start zone (#17888)
- fix(Scripts/Command): ticket comment should allow input (#17891)
- fix(CI): Maybe baby this will solve our problemos (#17889)
- chore(docs): update security.md (#17287)

## 2023-11-28
- chore(DB): import pending files

## 2023-11-29
- fix(DB/Gameobject): Sniffed Values for "The Zoram Strand" Midsummer s… (#17887)

## 2023-11-28
- chore(docs): bump coc to 2.1 with modificatiosn (#17302)
- chore(Core/Account): move AccountMgr::IsGMAccount() to class WorldSession (#17845)

## 2023-11-27
- chore(DB): import pending files
- chore(CI): rename CI to easier determain which is which (#17879)
- fix(DB/Gameobject): Sniffed Values for "The Slave Pens" Midsummer spawns (#17881)

## 2023-11-26
- fix(Scripts/Darkshore): Rabid Thistle Bear spawning with StandState Dead (#17875)

## 2023-11-27
- chore(Core/Misc): Clean up workarounds (#17870)

## 2023-11-26
- fix(Scripts/Quest): Correct respawn logic for Isla Starmane and Rin'ji (#17874)
- refactor(Scripts/BlackTemple): Modernize Najentus boss script (#17871)
- chore(CI): no cache for core-build-pch.yml (#17873)
- Update core_modules_build.yml (#17872)
- chore(Scripts/BlackTemple): Update Akama, Supremus, Gorefiend and Naj… (#17867)
- fix(Core/Groups): Create the group at first invite (#17869)
- fix(Core/Spells): Haunted should not be right-clickable (#17864)
- fix(Docs): readme update with new CI (#17865)
- chore(CI): Make some changes (#17861)
- fix(Core/Creature): Improve chase movement (#17557)
- chore(DB): import pending files
- fix(DB/Spells): Game In Session (#17862)
- fix(Scripts/Commands): Use the argument parser to parse guild names (#17863)
- chore(DB): import pending files
- fix(DB/Gameobject): Sniffed Values for 181393 'Hanging, Tall/Thin, Me… (#17829)
- fix(DB/Gameobject): Sniffed Values for 181390 'Hanging, Square, Mediu… (#17831)
- fix(DB/Gameobject): Sniffed Values for 181389 'Hanging, Tall/Thin, La… (#17830)
- fix(DB/Gameobject): Sniffed Values for 181391 'Standing, Interior, Sm… (#17837)
- fix(Core/Creature): Make `Respawn()` respect conditions and linked respawns (#17597)
- chore(DB): import pending files
- fix(DB/Gameobject): Sniffed Values for 187572 'Candle 01 - MFF' (#17848)
- chore(DB): import pending files
- fix(DB/Gameobject): Sniffed Values for 181392 'Hanging, Streamer - MFF' (#17838)
- chore(DB): import pending files
- fix(DB/Gameobject): Sniffed Values for 187576 'Hanging, Square, Small… (#17851)
- chore(DB): import pending files
- fix(DB/Gameobject): Sniffed Values for 181401 'Hanging, Streamer x3 -… (#17844)
- fix(DB/Gameobject): Sniffed Values for 187573 'Candle 02 - MFF' (#17850)
- chore(DB): import pending files
- fix(DB/Gameobject): Sniffed Values for 187653 'Standing, Post - MFF' (#17852)
- fix(DB/Gameobject): Sniffed Values for 187667 'Hanging, Tall/Thin, Sm… (#17853)
- fix(DB/Gameobject): Sniffed Values for 187708 'Torch Target Brazier' (#17854)
- chore(DB): import pending files
- fix(DB/Gameobject): Sniffed Values for 188020 'Camp Banner' (#17857)
- fix(DB/Gameobject): Sniffed Values for 188021 'Camp Pavilion' (#17858)
- chore(Shared/Network): make all pointers to `std::unique_ptr` (#17787)

## 2023-11-24
- chore(Core/Player): codestyle (#17841)
- chore(Core/Chat): add Channel::ShouldAnnouncePlayer() method (#17819)
- fix(Scripts/Commands): make sure no invalid IDs can be passed in map creation for `.go xyz` (#17836)

## 2023-11-23
- fix(Scripts/SholazarBasin) update the code to ensure the vehicle catches fire (#17833)
- fix(Core/Spells): Fix aura interruption flags for Scarlet Raven Priest Image for quest A Fall From Grace (#17828)

## 2023-11-22
- chore(Core/World): Fix typo in the previous commit (#17826)
- feat(Core/Battleground): Add config to allow giving points at level 7… (#17821)
- chore(DB): import pending files
- fix(DB/Gameobject): Scarlet Monastery: Add Midsummer decorations (#17818)

## 2023-11-21
- refactor(Scripts/Botanica): Update Laj's script after latest changes (#17814)

## 2023-11-20
- fix(Scripts/RuinsOfAhnQiraj): Andorov does not respawn after being killed (#17788)
- feat(Core/AI): Implement ScheduleTimedEvent() helper (#17813)
- fix(Scripts/TheEye): adjust Solarian timers based on sniffs (#17812)
- chore(DB): import pending files
- fix(DB/Gameobject): Sniffed Values for 181388 'Standing, Interior, Me… (#17810)
- chore(DB): import pending files
- fix(Scripts/ThousandNeedles): Improve the handling of quest 5151 (Hyp… (#17811)
- chore(DB): import pending files
- fix(DB/Creature): make sure Enchanted Elementals always walk and not run towards Lady Vashj (#17809)
- chore(DB): import pending files
- fix(DB/GameObject): Fix being able to target Vashj's bridge (#17808)
- chore(DB): import pending files
- fix(DB/SAI): allow Vashj'ir Honor Guard to use Frightening Shout (#17807)
- chore(DB): import pending files
- fix(DB/Gameobject): Sniffed Values for 181358 'Hanging, Square, Large… (#17802)
- fix(Core/Creature): Move DespawnOnEvade() respawn handling to map level (#17806)
- fix(Scripts/ICC/Sindragosa) Airphase should not be forced after 50s if already in p2 (under 35%) (#17722)
- chore(DB): import pending files
- fix(DB/Creature): Lady Vashj should despawn on evade (#17805)
- chore(DB): import pending files
- fix(Scripts/SSC): Script Hydross OOC event (#17804)
- chore(DB): import pending files
- fix(DB/Spells): Prayer of Mending should proc Inspiration (#17796)
- fix(Core/Spells): Spotlight having a duration (#17799)
- chore(DB): import pending files
- fix (DB\Creatures): Added an event for Warlock NPCs to craft gems when a quest is completed (#17777)

## 2023-11-19
- chore(DB): import pending files
- feat (core/cs): Make `.go xyz` ignore non-numeric data to improve copy-paste usability (#17772)
- chore(DB): import pending files
- fix(DB/Creature): Port Ethereal Spellfilcher immunities/detection fro… (#17801)
- fix(Scripts/Commands): guild commands revert back to using guild names in quotes (#17798)
- chore(DB): import pending files
- fix(DB/Gameobject): Sniffed Values for 181300 'Standing, Large - MFF' (#17797)
- fix(DB/Gameobject): Sniffed Values for 181021 'Hanging, Door - Val' (#17795)
- chore(DB): import pending files
- fix(DB/Spells): Static Shock proccing on non-melee attacks and abilities (#17794)
- fix(Scripts/Midsummer): AuraEffectRemoveFn -> AuraEffectApplyFn (#17793)
- chore(DB): import pending files
- fix(DB/SAI): Doomguard Commander - Crystal Prison (#17782)
- fix(Scripts/ManaTombs): Pandemonius should aggro the enitre room (#17764)
- chore(DB): import pending files
- fix(DB/Gameobject): Sniffed Values for remaining 'Horde Bonfire' spawns (#17783)
- fix(Scripts/SSC): Fix being able to damage Leo's minions if you are n… (#17786)
- fix(Core/LFG): Correct checks for teleport in/out (#17780)
- chore(Cleanup): added new lines to the end of files where they are not present (#17774)

## 2023-11-18
- feat(Core/Scripting): Implement Unit hooks to modify damage before ca… (#17785)
- chore(DB): import pending files

## 2023-11-19
- fix(DB/Gameobject): Sniffed Values for remaining City Bonfire spawns (#17784)

## 2023-11-18
- chore(DB): import pending files
- fix(DB/Gameobject): Sniffed Values for remaining 'Alliance Bonfire' s… (#17781)
- chore(DB): import pending files
- fix(DB/Creature): Delete previous spawn of Leotheras (#17779)
- chore(Core/Misc): sort includes (#17776)
- chore(Core/OutdoorPvP): cleanup ptr's, rename private fields (#17778)
- chore(DB): import pending files
- fix(DB/Spell): Bomb should proc only on cast (#17741)
- chore(Core/Misc): delete double include (#17775)
- chore(DB): import pending files
- fix(Scripts/Quest): Improve The Force of Neltharaku (#17088)
- chore(DB): import pending files
- fix(DB/Gameobject): Sniffed Values for 187923 'Alliance Bonfire' (#17755)
- fix(Scripts/ShadowLabs): Script Mark of Malice (#17773)
- chore(DB): import pending files
- fix(DB/Gameobject): Sniffed Values for 187931 'Alliance Bonfire' (#17763)
- chore(DB): import pending files
- fix(DB/Gameobject): Sniffed Values for 187933 'Alliance Bonfire' (#17766)
- chore(DB): import pending files
- fix(DB/Gameobject): Sniffed Values for 187921 'Alliance Bonfire' (#17753)
- fix(DB/Gameobject): Sniffed Values for 187920 'Alliance Bonfire' (#17752)
- fix(DB/Gameobject): Sniffed Values for 187919 'Alliance Bonfire' (#17751)
- chore(DB): import pending files
- fix(DB/Gameobject): Sniffed Values for 187936 'Alliance Bonfire' (#17769)
- chore(DB): import pending files
- fix(DB/Gameobject): Sniffed Values for 187917 'Alliance Bonfire' (#17750)
- chore(DB): import pending files
- fix(DB/Gameobject): Sniffed Values for 187937 'Alliance Bonfire' (#17770)
- chore(DB): import pending files
- fix(DB/Gameobject): Sniffed Values for 187932 'Alliance Bonfire' (#17765)
- chore(DB): import pending files
- fix(DB/Gameobject): Sniffed Values for 187916 'Alliance Bonfire' (#17749)
- fix(DB/Gameobject): Sniffed Values for 187914 'Alliance Bonfire' (#17748)
- fix(DB/Gameobject): Sniffed Values for 187934 'Alliance Bonfire' (#17767)

## 2023-11-17
- chore(DB): import pending files
- fix(DB/Gameobject): Sniffed Values for 181605 'Ribbon Pole' (#17742)
- chore(DB): import pending files
- fix(DB/Gameobject): Sniffed Values for 181355 'Standing, Exterior, Medium - MFF' (#17739)
- chore(DB): import pending files
- fix(DB/Gameobject): Sniffed Values for 187559 'Horde Bonfire' (#17743)
- chore(DB): import pending files
- fix(DB/Gameobject): Sniffed Values for 188352 'Flame of Shattrath' (#17744)
- fix(DB/Gameobject): Sniffed Values for 187564 'Alliance Bonfire' (#17745)

## 2023-11-16
- chore(DB): import pending files
- fix(DB/Gameobject): Update 181354 Floating, Medium - MFF with sniffed… (#17738)
- chore(DB): import pending files
- refactor(Scripts/AI) ZG20: Venoxis (Snake Boss) modernization (#17699)
- chore(DB): import pending files
- fix(DB/Creature): Port Arcane Annihilator WP from Mangos (#17737)
- chore(DB): import pending files
- fix(DB/Spell): Sunder Armor should stack from different sources (#17695)
- chore(DB): import pending files
- fix(DB/Gameobject): Port Bloodsail Charts spawns from Mangos (#17736)
- chore(DB): import pending files
- fix(DB/Creature): Port Underbog Colossus immunities from Mangos (#17706)
- refactor(Scripts/AI) ZG20: Mar'li (Spider Boss) modernization (#17715)
- fix(Scripts/Karazhan): Fix chess and optional boss not saving players (#17729)
- chore(DB): import pending files
- fix(DB/Creature): Add Fear proc aura to Fear Fiend (#17735)
- refactor(Scripts/TempestKeep): Clean up script files (#17727)
- refactor(Scripts/SCC): Update spell scripts to the new register model (#17726)
- refactor(Scripts/World): Clean up script files (#17728)
- refactor(Scripts/Karazhan): Move Malchezaar door handling to the inst… (#17730)
- chore(DB): import pending files
- refactor(Scripts/Stormwind): Move Bartleby script to SAI (#17731)
- refactor(Scripts/Ashenvale): Move Naga Brazier script to SAI (#17733)
- refactor(Scripts/AhnKahet): Move Ancient Nerubian Device script to SAI (#17734)
- chore(Misc/Lang): rename LANG_YOU_NOT_HAVE_PERMISSION to LANG_PERMISSION_DENIED (#17732)
- chore(DB): import pending files
- fix(DB\SAI): Port completion event for quest Hilary's Necklace from Trinity (#17719)

## 2023-11-15
- refactor(Scripts/MagistersTerrace): Update scripts to new register model (#17725)
- fix(Scripts/SCC): Clear Leotheras' Whirlwind aura on demon phase (#17721)
- refactor(Scripts/OHF): Clean up script files (#17724)
- refactor(Scripts/RuinsOfAhnQiraj): Clean up script files (#17723)
- chore(DB): import pending files
- fix(Scripts/SSC): Respawn Leotheras and fix last phase transition (#17720)
- refactor(Scripts/TempleOfAhnQiraj): Clean up script files (#17718)
- refactor(Core/Instance): Modernize a few player iterations (#17717)
- fix(Core/Misc): Mac build (#17714)
- chore(DB): import pending files
- fix(Scripts/Karazhan): Fix being able to interact with Nightbane's doors (#17713)
- chore(DB): import pending files
- fix(DB/Creature): Port SSC boss detection range from Mangos (#17707)

## 2023-11-14
- chore(DB): import pending files
- fix(Scripts/Karazhan): Fix Temptation target (#17710)
- fix(Scripts/Karazhan): Use actual spell interruption timers to handle… (#17709)
- fix(Core/InstanceScript): Fix new Remove function conversion miss (#17708)
- chore(DB): import pending files
- fix(Scripts/Karazhan): Implement Aran's Atiesh interaction (#17692)
- feat(Core/Guild): Allow to limit the amount of members within a guild (#17697)
- fix(Docker): Tweak entrypoint permissions (#17698)
- fix(Core/Spells): Banish should only be dispelled by Mass Dispel (#17703)
- chore(DB): import pending files
- fix(DB/SAI): Obsidia talk target (#17704)
- feat(Core/Instance): InstanceScript: create `Remove` functions (#17702)
- feat(Core/AI): Add built-in `TaskScheduler` to `CreatureAI` (#17700)
- fix(Scripts/DurnholdeKeep): Captain Skarloc spawning double/wrong adds (#17667)

## 2023-11-13
- fix(Scripts/ZulGurub): Jeklik (Bat Boss) - fix double-run scheduler (#17693)
- chore(DB): import pending files
- fix(Scripts/Karazhan): Implement Nightbane summon emote and despawn on evade (#17690)

## 2023-11-12
- feat(Core/Scripts): Prevent the inherited TaskScheduler from updating… (#17689)
- chore(DB): import pending files
- fix(DB/Quest): improve Quenching the Blade (#17340)
- chore(DB): import pending files
- fix(Script/Quest): Improve A Spirit Ally? (#16893)
- fix(Core/Spell): Titan's Grip check if player has 2H and shield equipped (#16984)
- chore(DB): import pending files
- fix(DB/Quest): improve Veil Lithic: Preemptive Strike (#16883)
- chore(DB): import pending files
- fix(DB/Spell): Darkmoon Card: Vengeance should proc on blocks (#17574)
- fix(Metric/Misc): Change default updatetime to 1s (#17627)
- chore(DB): import pending files
- fix(Script/Spell): Carinda's Scroll of Retribution usable on players (#17601)
- chore(DB): import pending files
- fix(DB/Creature): Change humans emote to sit/sleep in CoS (#17670)
- chore(DB): import pending files
- fix(DB/BladesEdgeMountains): several SAI fixes for the mobs in the upper forge camps (#17686)
- fix(DB/Loot): add Mark of the Illidari to trash loot tables (#17685)
- chore(DB): import pending files
- fix(DB/Creature): Dustbelcher NPC MovementType issue (#17663)
- chore(DB): import pending files
- (Scripts/AI) ZG20: Jeklik (Bat Boss) - Implement Bat Riders, other fixes and improvements (#17573)
- feature(Core/Pet): Add pet talent rate config (#17678)
- Revert Visibility Notifier changes (#17682)
- fix(Core/Character): fix worldserver with autobalance mod crash when character creation fails (#17625)
- fix(ci): macos (#17681)

## 2023-11-11
- chore(DB): import pending files
- fix(Scripts/SSC): make sure adds properly respawn and DoAction only fires on Tidalvess alive (#17680)
- chore(DB): import pending files
- fix(DB/SAI): Require 'Triangulation Point' buff to complete quests (#17640)
- chore(DB): import pending files
- fix(Scripts/SSC): make Fathomlord use his Spitfire Totem ability (#17674)
- fix(Scripts/TheEye): Void Reaver sniffed timers (#17676)
- fix(Scripts/SSC): make sure Insidious Whispers demons don't instantly despawn (#17672)
- chore(DB): import pending files
- fix(DB/SSC): make sure Fathomguard Caribdis Cyclone is visible (#17675)
- chore(DB): import pending files
- (Scripts/AI) ZG20: Improvements to Thekal (Tiger Boss) (#17603)

## 2023-11-10
- refactor(Scripts/RuinsOfAhnQiraj)Ç AQ20: Modernize Kurinnaxx (#17671)
- chore(DB): import pending files
- fix(Events): fix commoner spawns, auras and equips for all events (#17632)
- chore(DB): import pending files
- fix(DB/Custom): Sunder Armor should stack from different sources (#17665)
- chore(DB): import pending files
- fix(DB/Custom): Tunneler Acid should stack from different sources (#17666)

## 2023-11-09
- fix(Docker): Ensure default install prefix dirs exist (#17661)
- chore(DB): import pending files
- fix(DB/Custom): Acidic Bite should stack from different sources (#17662)

## 2023-11-08
- chore(DB): import pending files

## 2023-11-09
- fix(DB/Conditions): Require Torgos to be alive to use Trachela's Carcass (#17624)
- fix(Script/Spell): fix AOE circle bug on Midsummer Torch Catching (#17654)

## 2023-11-08
- fix(Core/Creature): Resolve issue with dialog options randomly not working (#17596)
- refactor(Core/Network): remove redundant logging calls from some message handlers (#17565)
- fix(Core/Unit): Implement GetDisplayRace() (#17609)
- Feat (Core) Add CustomData to Groups (#17628)
- chore(DB): import pending files
- fix(DB/Creature): Add vendor food flags to Feranin (#17660)
- chore(DB): import pending files
- fix(DB/Custom): Bloodburn should stack from different sources (#17659)
- chore(DB): import pending files
- fix(Core/Spells): Correct spell scaling formula. (#17649)
- fix(DB/Custom): Virulent Poison should stack from different sources (#17657)
- chore(DB): import pending files
- fix(DB/Custom): Carnivorous Bite, Sticky Ooze stack from different so… (#17648)
- chore(DB): import pending files
- fix(DB/Custom): Sundering Swipe should stack from different sources (#17638)
- chore(DB): import pending files
- fix(DB/SAI): Naberius (#17639)

## 2023-11-07
- refactor(Scripts/TheEye): High Astromancer Solarian script refactored using taskscheduler (#17653)
- chore(DB): import pending files
- fix(DB/SAI): Gargantuan Abyssal's Meteor should target only players (#17652)
- chore(DB): import pending files
- fix(DB/Loch Modan): adjusting x, y and z axes for nodes (#17614)
- chore(DB): import pending files
- fix(DB/Creature): Add vendor food flags to Targrom (#17647)
- feat(Core/Scripts): added `OnAfterSpecSlotChanged` hook (#17637)
- chore(DB): import pending files
- fix(DB/Creature): Add vendor food flags to Boots & Gant (#17641)

## 2023-11-05
- chore(DB): import pending files
- fix(DB/Creature): Correct IF Priest trainer gossip (#17401)
- feat(Deps/Fmt): update fmt lib to 10.1.1 (#17643)

## 2023-11-02
- fix(Core/Spells): T5 Warlock 4 Set (#17589)
- chore(DB): import pending files
- fix(DB/Procs):  Skullflame Shield & Demon Forged Breastplate (#17579)
- fix(Core/Spells): T4 Shadow Priest 4 Set (#17587)
- chore(DB): import pending files
- fix(DB/Creature): Hellfire Peninsula - Stonescythe mobs (#17604)
- fix(Core/Spells): Script Choking Vines  (#17615)
- fix(DB/Creature): Port spawns for 'Captive Child' from Mangos (#17626)

## 2023-10-31
- chore(DB): import pending files
- fix(DB/Creature): Fire Nova Totem VII - using wrong Fire Nova spell (#17592)
- chore(DB): import pending files
- fix(DB/Custom): Venom Sting should stack from different sources (#17583)
- fix(DB/Custom): Blistering Rot should stack from different sources (#17600)
- feat(Core/Hooks): Add `OnAfterDatabaseLoadCreatureTemplates` hook (#17621)

## 2023-10-30
- fix(Build): nopch build (#17617)

## 2023-10-29
- chore(DB): import pending files

## 2023-10-30
- fix(DB/Spells): Paladin Retribution Set T5 - 4P (#17563)
- fix(Core/Spells): T5 Holy Paladin 2 set (#17566)
- fix(DB/SAI): Unyielding Knight - not healing & not calling for help (#17591)

## 2023-10-28
- refactor(Core/Misc): Make DeathState enum class (#17607)

## 2023-10-27
- Merge branch 'master' into Playerbot
- fix(Core/Grid): Implement missing GridUnload setting (#17569)

## 2023-10-25
- chore(DB): import pending files

## 2023-10-26
- fix(DB/SAI): Dark Portal mages missing animation (#17585)

## 2023-10-25
- fix(Scripts/Karazhan): Fix Flame Wreath affecting pets (#17581)
- fix (Scripts/ICC): Make Valithria starting health dynamic, fix broken channeling spell (#17586)
- fix(Scripts/ObsidianSanctum): Fix Tenebron respawning (#17576)
- chore(DB): import pending files
- fix(DB/CreatureText): Medivh cheat emote should be a boss emote (#17572)
- chore(DB): import pending files
- fix(DB/SAI): Wanton Hostess not removing all auras (#17567)

## 2023-10-24
- chore(DB): import pending files
- fix(DB/Gameobject): Shadow Labyrinth Enterance Lever (#17568)

## 2023-10-23
- fix(Core/Grid): Address bugs and performance issues introduced by visibility notifier implementation (#17480)
- fix(Scripts/Karazhan): Update Aran with the new OnPowerUpdate() hook (#17561)

## 2023-10-22
- fix(Scripts/Ulduar): Don't treat Algalon respawns as if they were the… (#17562)
- feat(Core/Unit): Implement OnPowerUpdate() unit script hook (#17560)
- Merge branch 'master' of github.com:azerothcore/azerothcore-wotlk into Playerbot
- chore(DB): import pending files
- fix(DB/Quest): Improve The Summoning Chamber (#16588)
- fix(Core/BG): Relocate cannon in WG (#16673)
- chore(DB): import pending files
- refactor(DB/reputation_spillover_template): Reputation spillover table expansion (#14763)
- chore(DB): import pending files

## 2023-10-21
- chore(DB/Transports): Replace transport `name` fields with consistent text. (#14894)

## 2023-10-22
- chore(DB): import pending files

## 2023-10-21
- fix(Scripts/Karazhan): Implement the side entrance door area trigger … (#17556)

## 2023-10-22
- fix(Script/Misc): Replace hardcoded gossip and texts with DB ones. (#17502)

## 2023-10-21
- fix(Scripts/Karazhan): Opera left door should stay open in case of wipe (#17553)

## 2023-10-22
- chore(DB): import pending files
- fix(DB/Creature): Use sniffed values for 16781 Midsummer Celebrant spawns (#17549)
- chore(DB): import pending files

## 2023-10-21
- fix:(DB/Gameobject) Re-arrange location of Webwinder Path's signpost gps so they sit on the sign (#17308)

## 2023-10-22
- chore(DB): import pending files
- fix(DB/Conditions): Restriction AB_Effect_000 (28441) Spell effects only work on NPCs rel… (#17535)
- chore(DB): import pending files
- fix(DB/Quests): Darkshore emotes (#17552)
- chore(DB): import pending files

## 2023-10-21
- fix(Scripts/Karazhan): Script Aran's Flame Wreath ability (#17551)

## 2023-10-22
- chore(DB): import pending files
- fix(DB/SAI): Move the Ashbringer event AI of the Bloody Monastery mob to Smartai (#17078)

## 2023-10-21
- chore(DB): import pending files
- fix(DB/Creature): Shade of Aran should not path (#17550)
- chore(DB): import pending files

## 2023-10-22
- feat(DB): Add column for comment (spell_cooldown_overrides) (#17487)

## 2023-10-21
- fix(Scripts/Mechanar): Remove polarity shift stacks on polarity change (#17548)
- chore(DB): import pending files
- fix(DB/SAI): Quest: Corrupted Sabers (#17435)
- chore(DB): import pending files
- fix(Core/Spells): Marked for Death affecting wrong spells. (#17406)
- fix(DB/Gameobject): Witherbark Village spell focus locations (#17463)
- chore(DB): import pending files
- fix(Core/Scripts): ScriptEffect Frog Kiss (#17482)
-  fix(DB/Spell): Karazhan  Shadow Mend/Healing (#17496)
- refactor(Scripts/Commands): convert cs_ticket to new system (#17547)
- fix(Core/Arena): Fix logging scores in db (#17504)
- chore(DB): import pending files
- fix(Core/Player) Stop small durability loss from still occuring when DurabilityLoss options in worldserver.conf are set to 0 (#17407)
- fix(Core/Spells): Script Yeh'kinya's Bramble (#17516)
- fix(Scripts/EscortAI): Do not remove auras on evade (#17542)

## 2023-10-20
- chore(DB): import pending files
- fix(CI): Ensure targeted stage for docker is specified in CI (#17545)

## 2023-10-21
- fix(DB/Items): Unhatched Jubling Egg obtaining + RP (#17478)
- feat(Core/Conditions): Add GoState condition for near gameobject. (#17524)
- refactor(Scripts/Commands): convert cs_reset to new system (#17546)

## 2023-10-20
- chore(Core/Conf): Remove unused config (#17544)
- chore(DB): import pending files
- fix(DB/Spell): Karazhan Bloodlust/Heroism (#17486)
- chore(DB): import pending files
- fix(DB/SSC): add Frostbrand Weapon proc to Greyheart Tidecaller (#17528)
- chore(DB): import pending files

## 2023-10-19
- fix(Scripts/Quest): improve Path of Conquest (#16353)

## 2023-10-20
- chore(DB): import pending files
- fix(DB/Creature): Adyen the Lightwarden being immune to PC. (#17414)
- chore(DB): import pending files
- fix(Core/Spells): interrupt midsummer ribbonpole dance on mount or sp… (#17442)
- fix(DB/Conditions): Scryer/Aldor repeatable quests (#17533)

## 2023-10-19
- fix(ci): docker build double quotes typo (#17541)
- fix(Scripts/Paladin): ensure Judgements of the Just procs Seal of Vengeance/Corruption (#17470)
- fix(Core/Spells): Demonic Knowledge missing 1% per rank (#17495)

## 2023-10-18
- chore(DB): import pending files

## 2023-10-19
- fix(Scripts/Spells): Script Leggings of Beast Mastery. (#17428)
- fix(DB/Loot): Strange Engine Part should be fishable (#17520)

## 2023-10-18
- fix(CI): Ensure eluna is installed for acore-docker (#17530)
- fix(CI): check ref name instead of non-existent step (#17529)
- refactor(Scripts/Commands): convert cs_guild to new system (#17515)
- chore(DB): import pending files
- fix(DB): Use sniffed values for Midsummer Music Doodad spawns (#17518)
- chore(DB): import pending files
- fix(Scripts/Midsummer): Implement Ribbon Pole dance effects (#17417)

## 2023-10-17
- chore(DB): import pending files
- fix(DB/Creature): Baron Rafe Dreuger level (#17497)
- chore(DB): import pending files
- fix(DB/SAI): Ravenous Windroc not stacking eagle claw (#17531)
- chore(DB): import pending files
- fix(DB/Creature): Drunken Brewfest Reveler model (#17494)
- fix(Scripts/SSC): fix issues with Fathomlord and add interactions (#17525)
- chore(DB): import pending files
- fix(DB/Creature): Minor Manifestation of Earth stealth (#17498)
- fix(DB/SAI): Make Midsummer Celebrants applaud/cheer (#17503)
- fix(DB/SAI): Correct Eridan Bluewind not ending RP (#17534)
- Merge commit '26c583c24ab7dbbf1fecf3dcd737c1ad543c8b33' into Playerbot_1017
- chore(DB): import pending files
- fix (DB/SAI): Stratholme/Baron Rivendare (10440) encounter fixes (#17398)

## 2023-10-16
- Fix (core/SpellEffects): Don't randomize summoned guardian position if target is in the DB (#17506)
- chore(DB): import pending files

## 2023-10-17
- fix(DB/spell_proc_event): Shamanistic Rage ppm (#17499)

## 2023-10-16
- chore(DB): import pending files

## 2023-10-17
- fix(DB/SAI): Port Elder Cloud Serpent from Mangos (#17521)
- fix(DB/spell_proc_event): Bloodwarder Protector Spell Reflection (#17522)

## 2023-10-16
- chore(DB): import pending files

## 2023-10-17
- fix(Core/Spells): Script Scourge Banner (#17523)

## 2023-10-16
- chore(DB): import pending files
- fix(DB/Creature): Make Hydross the Unstable immune to taunt (#17514)

## 2023-10-15
- refactor(Docker): remove prod container distinction (#17419)
- chore(DB): import pending files
- fix(DB/Conditions): Fix Paelarin race conditions (#17501)

## 2023-10-12
- chore(DB): import pending files
- fix(DB/SAI): Port Guile of the Raptor RP from Trinity. (#17412)
- fix(Scripts/Karazhan): Side Enterance Door check (#17493)
- chore(DB): import pending files
- fix(DB/Quests): The Test of Righteousness required quests. (#17471)
- chore(DB): import pending files
- fix(DB/Spell): Correct Charred Twilight Scale ICD. (#17409)
- fix(Script/Spells): Script Priest Heal T4 4P Bonus (#17490)
- chore(DB): import pending files
- fix(DB/gob): Remove Replace Repool Durotar Herbs (#17459)

## 2023-10-11
- chore(DB): import pending files
- fix(Core/Spells): Call of the Wild targeting other players (#17485)
- chore(DB): import pending files
- fix(DB/Creature): Various Crocolisk NPCs Using pet ability (#17466)

## 2023-10-10
- chore(DB): import pending files

## 2023-10-11
- fix(DB/Creature): Power Core Fragment should stay on. (#17421)

## 2023-10-10
- chore(DB): import pending files

## 2023-10-11
- fix(DB/SAI): Nexus Clerics casting while frozen. (#17411)

## 2023-10-10
- chore(DB): import pending files

## 2023-10-11
- fix(DB/Quest): Port Cleansing Witch Hill from Trinity. (#17420)

## 2023-10-10
- chore(DB): import pending files

## 2023-10-11
- fix(Core/Scripts): Venomhide Hatchling improvements (#17454)

## 2023-10-10
- chore(DB): import pending files

## 2023-10-11
- fix(DB/Conditions): Mrs. Dalson's Diary gossip & Outhouse Key (#17469)
- fix(Core/Spells): Allow casting ground mounts in water (#17481)

## 2023-10-10
- fix(Core/Spells): Script Void Star Talisman resistances. (#17427)
- chore(DB): import pending files
- fix(DB/Gameobject): Pool triple Truesilver Vein in Desolace (#17444)
- chore(DB): import pending files
- fix(DB/Gameobject): Remove wagon duplicate. (#17422)
- chore(DB): import pending files
- fix(DB/SAI):  Cuergo's Gold improvements (#17462)
- fix(DB/Conditions): Pilot Xiggs Fuselighter spawning multiple times (#17476)
- chore(DB): import pending files
- fix(DB/Creature): Hex Lord Malacrass missing weapon (#17475)
- fix(DB/Loot): Shellfish Trap giving only 1 shellfish (#17473)
- chore(DB): import pending files
- fix(DB/SAI): Port J.D. Collie RP from Trinity (#17464)
- chore(DB): import pending files
- fix(Core/ChatHandler): SPELL_AURA_MOD_LANGUAGE should affect only Say… (#17465)
- fix(DB/Gameobject): Ores/Herbs should be visible in visible in all phases (#17477)
- chore(DB): import pending files
- fix(DB/SAI): Port Eridan Bluewind RP from Trinity (#17468)
- fix(DB/Conditions): 'Place Draenei Banner' conditions (#17474)

## 2023-10-08
- fix(Scripts/Karazhan): Replace Big Bad Wolf chase mechanic with prope… (#17458)
- feat(Core/Scripting): Implement hook `OnAfterCalculateLootGroupAmount()` (#17456)
- fix(Scripts/Karazhan): Nightbane clean-up script (#17446)
- fix(core/scripting) Calculate percent-based damage before `ModifyPeriodicDamageAurasTick` hook (#17387)
- fix(Core/Creature): Update movement in UpdateEntry() (#17291)
- chore(DB): import pending files
- fix(DB/Spell): Allow Armor Shatter/Puncture armor to stack (#17429)
- chore(DB): import pending files
- fix(Core/Spells): Script Shaman T8 Elemental 4P Bonus (#17424)
- chore(DB): import pending files
- fix(DB/SAI): Terrorclaw correct cleave timer and add fear. (#17415)
- fix(DB/SAI): Port Pamela Redpath from Trinity. (#17451)
- chore(DB): import pending files
- refactor(Core/Creature): Calculate BaseArmor as float (#17448)
- fix(DB/SAI):  The Legend of Stalvan spawns (#17433)
- chore(DB): import pending files
- fix(DB/Creature): "Dirty" Michael Crowe continuous animation loop (#17452)
- fix(DB/Loot): Ghostweave Patterns (#17437)
- chore(DB): import pending files
- fix(DB/Gameobject): Port BRD - Dark Iron Deposits from Mangos (#17445)
- chore(DB): import pending files
- feat(Core/Player): Implement commentator tag (#17449)
- chore(Core/Misc): warhead -> acore (#17447)

## 2023-10-07
- refactor(apps): remove docker image prune in dashboard (#17405)
- chore(DB): import pending files
- fix(DB/Waypoint): Port Stone Fury waypoints from Trinity. (#17443)
- fix(Core): GridCleanUpDelay Log (#17436)
- chore(DB): import pending files
- fix(Core/Spells): Script Lord Valthalak's Amulet (#17431)
- chore(DB): import pending files
- fix(DB/Conditions): Don't allow multiple Banner of Provocation (#17430)
- docs(template): Comment out changes proposed info. (#17438)

## 2023-10-05
- fix(CI): windows (#17423)
- chore(DB): import pending files
- fix(DB/Threat): Innervate having threat modifier. (#17404)
- feat(Core/Player): Move SaveSkills() to the public scope (#17418)

## 2023-10-01
- chore(DB): import pending files
- fix(Scripts/Midsummer): Randomize ribbon pole beam color (#17380)
- chore(DB): import pending files
- fix(DB/SSC): update timers of trash and boss adds in Serpentshrine Cavern with sniffs (#17108)
- refactor(Scripts/SSC): The Lurker Below boss script updated (#17082)
- refactor(Scripts/SSC): Leotheras the Blind boss script updated (#17080)
- chore(DB): import pending files
- feat(Core/Scripting): Implement `OnBeforeCreatureSelectLevel()` hook (#17391)
- fix(Scripts/Karazhan): Fix Dorothee yell once Tito dies and clean up … (#17395)
- chore(DB): import pending files

## 2023-09-30
- fix(DB/Creature): Fiendish Portals should not move (#17396)
- fix(Scripts/Karazhan): Fix Curator arcane immunity (#17397)

## 2023-10-01
- chore(DB): import pending files

## 2023-09-30
- fix(Scripts/Karazhan): Several Aran fixes (#17394)
- fix(Scripts/Spells): Fix Dash applying bonuses in other forms (restor… (#17393)
- fix(Scripts/Karazhan): Restore Netherspite DestroyPortals() function (#17392)
- refactor(Scripts/Midsummer): Add/Update Validate() for spell checks (#17390)

## 2023-09-29
- chore(DB): import pending files
- fix(DB/Conditions): Archmage Leryda ring retrieve gossip should requi… (#17385)
- refactor(Scripts/Midsummer): Assign enum values to gameobjects and sp… (#17379)

## 2023-09-28
- feat(Core/GameObject): Implement `OnGameObjectModifyHealth()` hook (#17374)
- feat(Core/Grids): Implement visibility notifier (#15919)
- fix(Scripts/Magtheridon): make the timers of Quake and Blast Nova independent from each other (#17364)
- fix(Scripts/Karazhan): Clear Netherspite portal targets on transition (#17377)

## 2023-09-27
- fix(Scripts/Karazhan): Update Aran script to use boss states (#17376)

## 2023-09-28
- fix(Scripts/Karazhan): allow Aran to cast pyroblast also when interrupted (#17375)

## 2023-09-27
- chore(DB): import pending files
- fix(Core/Quest): AllowableRaces to uint32 for custom Racemasks (#17372)
- fix(Scripts/SSC): Morogrim Tidewalker now summons the water globules again (#17373)
- chore(DB): import pending files
- fix(DB/Vendor): NPC Arcanist Ivrenne remove Heirlooms (#17371)
- chore(DB): import pending files
- fix(DB/reference_loot_template): Corrected Shadow Labyrinth gem drops (#17190)

## 2023-09-26
- chore(DB): import pending files

## 2023-09-27
- refactor(Scripts/SSC): Fathomlord Karathress boss script updated (#17079)

## 2023-09-26
- chore: fix sql (#17365)

## 2023-09-27
- refactor(Scripts/SSC): Lady Vashj boss script updated (#17083)

## 2023-09-26
- chore(DB): import pending files
- fix(Scripts/Midsummer): Make beam target Ribbon Pole top (#17358)
- fix(DB/Creature): make Malchezaar interrupt immune (#17363)
- fix(Scripts/Karazhan): Fix Aran combat movement behavior (#17359)
- fix(Script/Karazhan): Netherspite resets threat after portal phase (#17362)
- fix(Core/Unit): Threat from energize effects should be proportional t… (#17352)
- chore(DB): import pending files

## 2023-09-25
- fix(Scripts/Spells): Fix Furious Howl not giving ranged attack power … (#17345)
- fix(Player/Achievement): fix crash (#17357)
- chore(DB): import pending files
- fix(DB/Conditions): Argent Dawn shoulder enchant quest fixes (#17354)
- fix(Core/Spells): Correct swapped TARGET_UNIT_NEARBY_ALLY and TARGET_… (#17339)
- chore(DB): import pending files
- fix(Scripts/Ulduar): Respawn Algalon on wipes (#17344)
- fix(Scripts/Spells): Fix Glyph of Voidwalker applying to every pet (#17342)
- fix(Scripts/Spells): Druid Dash require Cat Form (#17343)
- fix(Scripts/SethekkHalls): Fix Anzu not leaving banish phase when all… (#17337)
- chore(DB): import pending files
- fix(DB/Conditions): Fix Berthold teleport gossip conditions (#17336)
- fix(Scripts/SlavePens): Correct target selector for Quagmirran Acid Spray (#17341)
- fix(DB/Text): Add missing Netherspite text emotes (#17335)
- chore(DB): import pending files
- fix(Scripts/Karazhan): Fix Shade of Aran Blizzard and use proper spel… (#17329)
- fix(Scripts/Karazhan): Fix Julliane awarding no loot (#17334)
- chore(DB): import pending files
- fix(Scripts/Karazhan): Make Chess door non interactable (#17349)
- refactor(Scripts/MagistersTerrace): Clean up instance script (#17346)
- refactor(Scripts/GruulsLair): Clean up instance script (#17347)
- fix(Scripts/Spells): Fix Healing & Mana injectors not giving bonus to… (#17348)
- fix(Scripts/Commands): Fix list creature string output (#17351)
- chore(DB): import pending files
- fix(DB/GameObject): fix Malchezaar door being selectable (#16275)

## 2023-09-24
- chore(DB): import pending files
- fix(Scripts/Midsummer): Add missing torch shadows (#17323)
- fix(Scripts/Quest): improve Catch the Wild Wolpertinger! (#17333)
- fix(Scripts/Karazhan): Sync Enfeeble and Shadow Nova (#17314)
- chore(DB): import pending files
- feat(Scripts/Commands): Display creature entry when using the npc nea… (#17331)
- chore(DB): import pending files
- fix(DB/Quests): adding AllowableRaces flags for Quests 'The Mark of the Lightbringer' and 'Tomb of the Lightbringer' (#17301)

## 2023-09-23
- refactor(Scripts/Midsummer): Remove old unused code for spell 45644 (#17324)
- fix(CI): windows build (#17328)
- fix(Core/Unit): Fix CanSwim method not accurate for players (#17320)
- Merge branch 'master' of github.com:azerothcore/azerothcore-wotlk into Playerbot
- fix(Script/Karazhan): Voidzones should only happen in Portal Phase (#17315)

## 2023-09-22
- fix(Core/Achievement): Implement ACHIEVEMENT_CRITERIA_TYPE_COMPLETE_RAID (#17316)
- fix(Scripts/Karazhan): Aran now evades when pulled out of the room (#17264)
- fix(Core/Achievement): Implement ACHIEVEMENT_CRITERIA_TYPE_ROLL_DISENCHANT (#17319)

## 2023-09-21
- fix(Core/Achivement): Implement ACHIEVEMENT_FLAG_AVERAGE (#17263)
- fix(CI): cppcheck failure step (#17240)

## 2023-09-20
- refactor(Core): Source config more aggressively from env, rephrase a few of the messages (#17114)
- chore(DB): import pending files
- fix(DB/Item) Update some mismatched items from 12340 (#16452)
- fix(Core/Unit): Added bluewall AoE check (#17064)
- chore(DB): import pending files

## 2023-09-21
- fix(DB/Quest): Script The Binding (#17042)

## 2023-09-20
- chore(DB): import pending files
- fix(DB/SAI) Add spore burst with 15% trigger chance (#16985)
- fix(DB/Quest): Return To Obadei (#16891)
- chore(DB): import pending files
- fx(DB/Quest): The Stories Dead Men Tell Quest Fix (#16887)
- fix(DB/Quest): Return to Brock completion text (#16711)
- fix(DB/Quest): Soothing Turtle Bisque POI (#16710)
- feat(Core/Player): Addition of a Hook in CanFlyInZone check (#16590)
- chore(DB): import pending files

## 2023-09-19
- fix(Scripts/Karazhan): Delay chain spawning so it spawns on proper place (#17311)
- fix(Scripts/Karazhan): Move Aran's elemental AI to SAI (#17312)
- chore(DB): import pending files
- fix(Scripts/Karazhan): Fix fear immunity for Strawman (#17307)
- fix(Scripts/Karazhan): Regen Curator mana on reset (#17310)
- chore(DB): import pending files
- fix(DB/Creature): make infernal helper targets in Kara invisible to players (#17309)
- fix(Scripts/Karazhan): fix visual of infernals on Malchezaar (#17304)

## 2023-09-18
- chore(DB): import pending files
- chore(CI): revert previous changes to import_pending.yml (#17303)
- fix(Scripts/Karazhan): Fix Aran's chase distance and Blink conditions (#17296)
- fix(Scripts/Karazhan): Fix Terestrian Illhoof not summoning any imps (#17297)

## 2023-09-17
- fix(DB/SAI): Worldserver Error in Dalaran (#17292)
- fix(Scripts/MagistersTerrace): Script Kalecgos' appearance after usin… (#17286)

## 2023-09-18
- fix(DB/Creature): Godrick Farsan event (#16607)

## 2023-09-17
- chore(DB): import pending files
- fix(DB/Quest) Know Thine Enemy RP event (#16258)
- chore(CI): Hello Github Bot and Update actions version (#17285)
- chore(DB): import pending files

## 2023-09-18
- fix(DB/Creature): move Fairbanks gossip to the database (#16974)

## 2023-09-17
- chore(DB): import pending files

## 2023-09-18
- fix(Core/Position): Normalize Position.GetRelativeAngle (#16825)

## 2023-09-17
- fix(Scripts/Karazhan): Fix Enfeeble hitting more than 5 targets (#17290)
- fix(DB/Creature): Removed duplicated fire festival Flame Wardens (#16671)
- fix(Scrpits/Quest): Improve Recharging the Batteries (#16597)
- fix(Core/Item): Reduce amount of excessive logging for enforeDBCAttributes (#16508)
- chore(misc): Mordenize maths (#17273)
- fix(Scripts/Karazhan): Shade of Aran now no longer casts spells whilst he should be drinking (#17282)
- feat(Core/Instance): Add TaskScheduler to the InstanceScript class (#17284)
- chore(DB): import pending files
- fix(Scripts/Karazhan): Curator fixes (#17270)
- fix(DB/SAI): Rework Sethekk Halls SAI (#17257)
- chore(Worldserver/Config): Clean up and reorganize config file (#17272)
- chore(misc): cleanup (#17274)
- fix(Core/GameObject): Also send EventInform() calls for GAMEOBJECT_TY… (#17283)
- fix(Core/TaskScheduler): warning (#17275)
- chore(DB): import pending files
- fix(Scripts/Darkshore): ensure Kerlonian Evershade is always in bear form (#17062)
- chore(DB): import pending files
- fix(DB/Creature): Ravenous Flayer Matriarch (#17256)
- fix(Scripts/BlackwingLair): Orb of Domination can no longer be used when you are controlling a pet (#16880)
- chore(DB): import pending files
- fix(DB/Creature): The Big Bad Wolf should be Taunt immune (#17255)
- refactor(Scripts/SSC): Hydross the Unstable boss script updated (#17081)
- chore(DB): import pending files
- fix(Scripts/MagtheridonLair): Magtheridon Debris (#17249)
- fix(DB/Karazhan): fix Curator's patrol movement using sniffs (#17234)
- fix(Scripts/Karazhan): remove redundant spellcasting check on Netherspite to ensure he moves back to phase 1 (#17269)
- chore(DB): import pending files
- fix(DB/Creature): Netherspite is immune to taunts (#17261)
- fix(DB/Creature): Modernize and follow-up on PR #9912 #9943 #10052 #10282 #10285 #12702 #12751 #12765 #12854 (#17217)
- chore(Scripts/DK): Move CheckCast to spell_dk_raise_ally script (#17221)

## 2023-09-16
- chore(DB): import pending files
- fix(DB/Character): Allow profanity_name and reserved_name to be accen… (#17224)
- chore(Core/enumutils): regenerate enumutils (#17087)
- fix(Scripts/Chat): Fix chat logger (#17102)

## 2023-09-15
- refactor(Scripts/Spells): Check for existence of AD debuff instead of adding a custom cooldown to heal (#17265)
- fix(Scripts/Karazhan): decrease Aran cast cooldown on normal spells (#17260)
- chore(DB): import pending files
- fix(DB/Creature): Correct Orc Warlock controlled spell (#17232)
- chore(DB): import pending files

## 2023-09-14
- refactor(DB/Player): Unify two player stat tables. (#17188)

## 2023-09-15
- chore(DB): import pending files

## 2023-09-14
- feat(DB): Add another column for comments (#17241)

## 2023-09-15
- chore(docs): remove reference to BountySource (#17253)
- chore(CI): Update deps for Windows and Mac builds (#17252)
- chore(Core/Misc): Silence compile warning in boost::process with vers… (#17251)

## 2023-09-14
- chore(DB): import pending files
- fix(Core/Achievement): Implement ACHIEVEMENT_CRITERIA_TYPE_OWN_RANK (#17180)
- chore(DB): import pending files
- fix(Scripts/Karazhan): Should always be able to talk to chess pieces … (#17246)

## 2023-09-13
- chore(DB): import pending files

## 2023-09-14
- fix(Scripts/Karazhan): Malchezaar infernals now spawn in the correct locations under the right conditions (#17237)

## 2023-09-11
- chore(DB): import pending files
- chore(DB/Creature): Correct VerifiedBuild for unverified chess piece spells. (#17233)
- fix(CI): only run cpp check on AC (#17230)

## 2023-09-10
- fix(apps/Docker): Missing arg for build:prod (#17231)
- chore(DB): import pending files
- fix(CI): pending files (#17229)
- feat(DB/Creature): Add CreateObject column in the creature table (#17187)
- feat(Core/SmartAI): Implement a few more stuff (#17090)
- fix(CI): rebase instead of unshallow fetch (#17226)

## 2023-09-09
- fix(CI): pending sql changelog script's invocation (#17225)

## 2023-09-10
- fix(Core/Conf): log error in case configuration not found for DBImport (#17066)

## 2023-09-09
- refactor(Apps/Dashboard): Remove Deno as a dependency to the dashboard (#16934)
- fix(Core/AuctionHouse): fix crash in BuildListAuctionItems (#17222)

## 2023-09-08
- feat(Core/Scripting): Implement OnAllowedToLootContainerCheck() hook (#17209)

## 2023-09-06
- fix(Scripts/Magtheridon): add correct way to reset threat list (#17198)

## 2023-09-05
- refactor(Scripts/TheEye): Refactor Void Reaver boss script to new scheduler (#17044)
- Merge branch 'master' into Playerbot
- chore(DB): import pending files
- fix(Scripts/Ulduar): update Winter Jormungar and Snow Mound creature script (#17054)
- fix(Scripts/Magtheridon): Remove ThreatList before release (#17128)
- fix(Core/InstanceMap): Stop using deleted player in RemovePlayerFromMap (#17069)
- fix(Core/Player): Allow to swap bags when they are filled (#17086)
- fix(Scripts/MagtheridonsLair): make it so no attack is being done during Quake and fix p1 cheese tactic (#17136)

## 2023-09-04
- fix(Scripts/Karazhan): Remove redundant Garrote cast and despawn gues… (#17152)
- fix(Scripts/Karazhan): Remove hacked knockback effect from Aran Flame… (#17174)
- fix(Scripts/Karazhan): Fix Nightbane health phase percentages (#17173)
- chore(DB): import pending files

## 2023-09-05
- fix(DB/Creature): Add movement and events to Haggle in Deeprun Tram (#17095)

## 2023-09-04
- chore(DB): import pending files
- fix(DB/Creature): Add CC immunities to Ethereum Prisoners (#17107)
- fix(DB/Gameobject): Adjust position for unsniffed Truesilver node (#17112)

## 2023-09-05
- Merge branch 'master' into Playerbot

## 2023-09-03
- fix(Scripts/Karazhan): change to right gossip menu for Barnes (#17151)
- fix(Scripts/Karazhan): make it so door closes when Big Bad Wolf is engaged in Little Red Riding Hood in the Opera (#17172)
- fix(Scripts/Karazhan): Maiden of Virtue repentance should have a cast… (#17153)
- Merge branch 'master' into Playerbot

## 2023-09-02
- fix(Scripts/Karazhan): fix gossip from the Grandmother in the Big Bad Wolf fight (#17155)

## 2023-09-01
- Merge branch 'master' into Playerbot

## 2023-08-30
- chore(DB): import pending files
- fix(DB/Conditions): quests 8353-8355-8356-8357-8311 (#17031)

## 2023-08-29
- Merge branch 'master' into Playerbot
- chore(Deps/Misc): Print an EOL Deprecation warning for MySQL 5.7 and … (#17101)

## 2023-08-28
- fix(Core/Crypto): fix crash (#17100)
- refactor(Core): remove unused imports (#17094)
- refactor(Scripts): remove unused imports (#17097)

## 2023-08-27
- fix(Scripts/Karazhan): allow Moroes and adds to reset when an add is pulled out of the room (#17072)
- chore(Core/Misc): Correct some fmt outputs (#17091)
- Merge branch 'master' into Playerbot

## 2023-08-26
- fix(Spell): set torment of the worgen to have 3% proc chance (#17005)

## 2023-08-25
- fix(Apps/Docker): ensure conf files always exist (#17071)
- chore(DB): import pending files
- fix(DB/Creature): rework Agamand Family Crypt creature positions to make sure creatures don't aggro weirdly anymore (#17022)
- chore(DB): import pending files
- fix(DB/Creature): Add Taunt immunity to Magtheridon (#17076)
- fix(Core/MiscHandler): Dungeon requirements Message (#16701)
- fix(Core/Scripts): Fix scripts where LoadObjectData can leave arrays boundaries. (#17070)
- fix(Core/Spell): Stop `Blink` from the falling player to move upward by 1y and stop moving backward when facing a wall (#16657)
- fix(Scripts/Karazhan): allow sequence of releases to continue even if Dorothee dies early (#17077)
- fix(Core/Spells): Add SPELL_ATTR7_DONT_CAUSE_SPELL_PUSHBACK to Hand of Sac and Divine Sac spells (#17041)
- fix(Scripts/Orgrimmar): replace hardcoded gossips in zone_orgrimmar (#16947)
- chore(DB): import pending files
- fix(Core/Item): Complimentary Brewfest Sampler (#16992)
- refactor(Scripts/SSC): modernise Morogrim Tidewalker with BossAI (#17028)
- Merge branch 'master' into Playerbot

## 2023-08-24
- chore(DB): import pending files
- fix(DB/SAI): Adjust "Stinky"'s ReactState on waypoints (#17075)
- chore(DB): import pending files
- fix(DB/Creature): add `path_id` to some Ulduar mobs that were missing it (#17055)
- Merge branch 'master' into Playerbot
- chore(DB): import pending files
- fix(DB/SAI): Change Delmanis the Hated ReactState (#17059)
- MOD_PLAYERBOTS macro

## 2023-08-23
- chore(DB): import pending files
- fix(DB/Item): Deep Thunder ppm adjustment (#17049)
- chore(DB): import pending files
- fix(DB/SAI): Correct Giselda the Crone's SAI. (#17008)

## 2023-08-22
- fix(Core/Vehicles): Fix crash in Vehicle::AddPassenger (#17038)
- feat(Core/SmartAI): Implement SMART_ACTION_FOLLOW_GROUP (#17033)
- fix(Apps/Docker): ensure env var is used for db password (#17050)
- refactor(Misc/Conf): DBErrors is now Errors (#17053)
- fix(Scripts/Arcatraz): Fix not being able to try Skyriss a second time after wipes (#17018)

## 2023-08-21
- chore(DB): import pending files
- fix(Script/Spells): Book of Fel Names (#17051)
- chore(DB): import pending files
- fix(Core/Pet): Correct (most) warlock pet scaling (#16769)

## 2023-08-20
- chore(DB): import pending files
- fix(Scripts/OHF): Don't update the escort steps when Drake dies (#17024)
- feat(Apps/Docker): Use Env Vars for docker configuration (#17040)

## 2023-08-19
- chore(DB): import pending files

## 2023-08-20
- fix(Core/Events): Implement Spirit of Competition event (#16963)

## 2023-08-19
- fix(Scripts/Dragonblight): Fix crash from Wintergarde Gryphon. (#17032)
- fix(Core/Pets): Fix crash when pet tries to attack deleted object (#17034)
- chore(DB): import pending files

## 2023-08-20
- fix(DB/Creature): Njorndar Proto-Drake vehicle unable to fly in “Vile Like Fire” (#16672)

## 2023-08-19
- fix(Scripts/Quest): Improved Varedis Must Be Stopped (#16799)
- chore(apps): remove deprecated db_assembler and erroneous .gitmodules (#17039)
- refactor(docs): Clean up readme a bit (#16849)
- fix(Tools/DBImport): Add Env var support to DBimport tool (#17019)

## 2023-08-18
- fix(Core/Transport): Fixes crash with loading player on deleted transport (#17021)

## 2023-08-14
- refactor(Deps/MySQL): Tidy up FindMySQL for windows (#16948)
- fix(build): macOS (#17007)
- feat(Core/Config): Implement config override with env vars (#16817)
- chore(DB): import pending files
- fix(DB/Creature) Horrified Drakkari Shaman/Warrior (#16953)
- fix(Scripts/OHF): Fix not being able to start the escort if you already killed Lt. Drake (#17006)
- chore(DB): import pending files
- fix(DB/Creature): Kara Banquet Hall Formations (#16900)
- chore(DB): import pending files
- fix(DB/Creature): Hellfire Warder Immunities (#17003)

## 2023-08-13
- fix(DB/SAI): Jandice Barov correct spell IDs (#17004)

## 2023-08-14
- fix(DB/Creature): Set Maleki the Palid to not respond to call for assistance (#16999)

## 2023-08-13
- chore(DB): import pending files
- fix(DB/Creature): Kara Arcane Protector improvements (#16901)
- chore(DB): import pending files
- fix(Scripts/Karazhan): Fix Servant Quarters rares not spawning (#17001)
- chore(DB): import pending files
- fix(Scripts/OHF): Killing Drake should not be required to start Thral… (#17000)
- chore(DB): import pending files
- refactor(DB/SAI): Port 'The Dread Relic' from event_scripts to SmartAI (#16998)

## 2023-08-12
- fix(Apps/Docker): adduser/addgroup commands in dockerfile (#14914)
- chore(DB): import pending files
- feat(Core/SmartAI): Add new event parameter, event_param6 (#16944)
- chore(DB): import pending files
- fix(DB/Gossip): Change MenuID to INT from SMALLINT (#16982)
- chore(DB): import pending files
- fix(DB/Creature) Wrathscale Sorceress casts Frostbolt (#16927)
- fix(Apps/Docker): Git version resolution in docker build (#16379)

## 2023-08-11
- chore(DB): import pending files
- fix(Scripts/Spell): Improve Inoculation quest (#15759)
- chore(Scripts/Karazhan): Clean up Maiden of Virtue script (#16977)

## 2023-08-12
- fix(DB/UBRS): change rep on kill for Pyroguard Emberseer from 50 to 20 (#16888)
- fix(DB/Creature): Infected Wildkin uses Infected Wound (#16929)

## 2023-08-11
- chore(DB): import pending files

## 2023-08-12
- fix(Scripts/Command): Improve output of event commands (#16980)

## 2023-08-11
- fix(Scripts/UBRS): typo in Blackrock Spire instance (#16976)

## 2023-08-10
- fix(Spells/Scripts): Gnomish Poultryizer (#15554)
- chore(DB): import pending files
- fix(DB/Locale): deDE fixes for request items 7 (#16288)
- fix(DB/Locale): deDE fixes for request items 6 (#16287)
- chore(Scripts/Karazhan): rework Opera scripts using TaskScheduler (#16688)
- docs: Simplify the pull request template (#16869)
- chore(DB): import pending files
- fix(DB/Creature): Desolace Kolkar have no resistances. (#16972)
- change gitmodules
- Merge branch 'master' into Playerbot
- conf for playerbots log

## 2023-08-09
- fix(Core/Arena): Fix LegacyArenaPoints logic (#16967)
- chore(DB): import pending files
- feat(Core/Conf): add CONFIG_ARENA_QUEUE_ANNOUNCER_DETAIL (#16850)
- feat(Core/Config): Add Legacy Arena Points config option (#16940)
- chore(DB): import pending files
- fix(DB/Quest): Hellfire Fortifications adjustments (#16960)

## 2023-08-08
- fix(Core/Unit): Fix Arena Preparation aura being removed on player ac… (#16925)

## 2023-08-09
- fix(DB/Creature): Infernal Warbringer immune to horror (#16961)
- fix(Core/Pets): Hunter pet scaling (#16959)

## 2023-08-08
- chore(DB): import pending files
- fix(DB/Creature): make sure The Crone can no longer be disarmed or interrupted (#16956)

## 2023-08-07
- Merge branch 'master' into Playerbot
- chore(DB): import pending files
- fix(DB/SAI): Hellfire Warder should not overlap rain of fire (#16941)

## 2023-08-06
- refactor(Core/Motd): Move motd to MotdMgr (#16933)
- fix(DB): Correct collation of create script (#16853)
- chore(Docs): Specify MySQL 8.1 support (#16903)
- feat(Core/SmartAI): Implement castFlag THREATLIST_NOT_SINGLE (#16911)
- chore(DB): import pending files
- fix(Script/Quest): Doing Your Duty (#16923)
- chore(DB): import pending files
- fix(DB/Creature): Arcane Anomaly should not be immune to arcane (#16921)
- chore(DB): import pending files
- fix(DB/Creature): Netherspite, Nightbane should be immune to interrupt (#16922)
- chore(DB): import pending files
- fix(DB/Creature): Hellfire Channeler should be immune to silence (#16894)
- chore(CI): fix `ci-pending.sh` script for linting SQL (#16913)
- fix(Core/Spells): Warrior T5 2p  (#16749)
- chore(DB): import pending files

## 2023-08-05
- fix(DB/SAI) Adds missing (36332) Rake ability to (17350) Royal Blue Flutterer (#16909)

## 2023-08-06
- fix(DB/Item): Blade of Unquenched Thirst PPM fix (#16908)
- fix(Core/Spells): Silent Fang proc should not work in … (#16907)

## 2023-08-05
- fix(DB/Creature): Gremnik Rizzlesprang gossip (#16871)

## 2023-08-06
- fix(DB/Creature): Ethereal Darkcaster (H) should be pickpocketable (#16852)
- fix(Core/Movement) Smoother movement of hunter pets when following players (#16796)

## 2023-08-05
- fix(Script/Quest): Arelion's Secret. Add combat sequence to Magister … (#15878)
- fix(DB/Quest): improve A Dip in the Moonwell (#15259)

## 2023-08-06
- fix(Core/Spells): Taunt always set proper target while channelling sp… (#13948)
- fix(DB/TheBarrens): fix Verog the Dervish spawn position and add movement down to ramp with sniffs (#16906)
- fix(Core/Pets): Corret Pet size for normal and exotics & bigger pets (#16910)

## 2023-08-05
- Merge branch 'master' into Playerbot

## 2023-08-04
- chore(DB): import pending files
- fix(DB/SAI) Wood Mites should skitter around (#14806)

## 2023-08-03
- chore(DB): import pending files
- fix(DB/Loot): Karazhan Boss Loot (#16859)

## 2023-08-02
- chore(DB): import pending files
- fix(DB/Creature): fix mechanical immunities of Ghostly Steward as well as fixing/improving Frenzy (#16228)
- fix(Scripts/EscapeFromDurnholde): Fix escort mission getting stuck (#16636)
- fix(Core/Pets) Pet scaling only being applied to pets with DB Entry (#16401)
- fix(Core/Battleground): Fix auto arena flush interval (#16877)
- fix(Scripts/Commands): Allow using flusharenapoints from console (#16879)

## 2023-08-01
- chore(DB): import pending files
- fix(Scripts/MagtheridonLair): Script Manticron Cube conditions (#16867)
- fix(Core/Spells) Add Explosive Shot exception (#16854)
- fix(Scripts/Gruuls) Kiggler no longer chases after target (#16866)
- Merge branch 'master' into Playerbot

## 2023-07-31
- fix(Scripts/World): Fix XP disable NPC script (#16828)
- fix(Scripts/Azuregos): Arcane Vacuum should also reset pet threat (#16868)
- chore(DB): import pending files
- fix(Core/Item): Mirror client logic when determining whether to apply… (#16861)
- fix(DB/Loot): Shadowmoon Technician Heroic should be pickpocketable (#16863)

## 2023-07-30
- fix(Core/PacketIO): Prevent HandleGameobjectReportUse when Gob is not… (#16707)
- chore(DB): import pending files
- fix(DB/Creature): Captain Skarloc should be interruptable (#16856)
- feat(Core/SmartAI): Implement AoE variants of VICTIM_CASTING and RANGE events (#16720)
- Merge branch 'master' into Playerbot

## 2023-07-29
- chore(DB): import pending files
- fix(DB/Creature): Change CombatReach and Bounding Radius for Doom Lord Kazzak (#16842)
- chore(DB): import pending files
- fix(Core/Spells): Curse of Pain (#16844)
- chore(CI): Update checkout and cache to v3 (#16847)
- fix(CI): Update macos openssl to 3 (#16846)
- fix(CI): Windows build (#16843)

## 2023-07-28
- chore(DB): import pending files
- fix(DB/Creature): High Executor Darthalia movement and position (#16835)

## 2023-07-27
- fix(Scripts/MagtheridonLair): Fix double schedule (#16831)
- chore(DB): import pending files
- fix(DB/SAI): remove SAI from Defias Cutpurse (#16795)
- chore(DB): import pending files
- fix(DB/SAI): improve timers from Shattered Rumblers using sniffs (#16818)
- chore(DB): import pending files
- fix(DB/Creature): High Executor Darthalia movement (#16829)
- chore(DB): import pending files
- fix(DB/Spell): Add 20% buff to Spotlight (#16819)
- fix(Core/Raid): Archimonde's Unable to kill (#15128)
- chore(DB): import pending files
- fix(Core/Spells): Set Crashin' Thrashin' Robot duration to 3 min. (#15342)
- chore(Scripts/Karazhan): rewrite Nightbane with scheduler + some fixes (#16687)
- refactor(Scripts/Karazhan): Update Netherspite (#16756)
- fix(Core/Arena): allow crossfaction arena teams (#16823)
- chore(DB): import pending files
- fix(DB/Creature): add pathing to Garn Mathers (#16824)

## 2023-07-26
- chore(DB): import pending files
- fix(Scripts/Quest): improved Curing the Sick (#16798)
- fix(Script/Professions): Unlearn alchemy profession mastery at 325 (#16810)
- chore(DB): import pending files
- fix(DB/BlackrockSpire): Add teleport trigger for crater (#16718)
- chore(DB): import pending files
- fix(DB/Smartscript): Shattered Hand Champion should not threat drop (#16808)
- fix(DB/Spell): Darkmoon Card: Heroism should only trigger on melee autoattacks (#16775)
- fix(DB/Spell) Fix WOTLK trinket procs (#16790)
- Merge branch 'master' into Playerbot
- Fix(scripts): bot receive CMSG packet

## 2023-07-24
- chore(DB): import pending files
- fix(DB/Loot): HC ramparts chest should drop a badge of justice (#16807)
- Merge branch 'master' into Playerbot

## 2023-07-23
- chore(DB): import pending files
- fix(Scripts/Magtheridon): allow for Magtheridon to also break free immediately when all Hellfire Channelers are killed (#16794)

## 2023-07-22
- chore(DB): import pending files
- fix(DB/Quest): Port quests regarding Corki from Trinity (#16080)

## 2023-07-21
- fix(Core/Session): don't refund soul shards when logging out with warlock pets (#16803)

## 2023-07-19
- chore(DB): import pending files
- fix(DB/Spell): Darkmoon Card: Blue Dragon should only trigger on spellcast (#16779)
- fix(DB/Spell): Talisman of Ascendance should only proc on spell casts (#16776)
- fix(DB/Spell): Badge of the Swarmguard PPM fix (#16777)
- fix(DB/Spell): Bangle of Endless Blessing ICD adjustment (#16780)
- fix(DB/Spell) Fix trinkets procs TBC and Vanilla (#16783)

## 2023-07-18
- refactor(Scripts/Karazhan): Update Servant Quarters (#16680)
- chore(Scripts/Karazhan): change Moroes to use TaskScheduler instead of events (#16791)
- chore(DB): import pending files
- fix(Scripts/Pets): Darting Hatchling not running around. (#15251)
- fix(DB/Commands): Fix typo in `wp show` command description. (#16591)
- refactor(Scripts/Karazhan): Update Attumen and Midnight (#16681)
- chore(Scripts/Karazhan): rework Shade of Aran using TaskScheduler and fixes (#16689)
- fix(Scripts/TempleOfAhnQiraj): make C'thun Dark Glare face location of last eyebeam before cast, instead of random target (#16785)
- Merge branch 'master' into Playerbot
- refactor naxxramas
- chore(DB): import pending files
- fix(DB/Loot): Incorrect Skinning Loot in Red Mesa (#16789)

## 2023-07-17
- fix(Scripts/TempleOfAhnQiraj): let small Eye Tentacles attack the raid (#16784)
- chore(DB): import pending files
- chore(Scripts/Spells): Reduce the amount of player checks (#16719)
- fix(DB/Creature): fix Horizon Crew in sunken ship on Azshara (#16778)
- refactor(Scripts/Karazhan): Update Maiden of Virtue (#16683)
- refactor(Scripts/Karazhan): Update Moroes (#16682)
- fix(Core/Spells): Implement ENCHANT_PROC_ATTR_WHITE_HIT (#16771)

## 2023-07-16
- chore(DB): import pending files

## 2023-07-17
- fix(DB/Loot): Outcast's Cache Loot adjustment (#16734)
- fix(DB/Quest): 1582 - Moonglow Vest req. skill (#16724)
- fix(DB/Creature): Add Immunities Knockback and Horror to Gruul trash (#16753)

## 2023-07-16
- chore(Scripts/Karazhan): The Curator - KilledUnit (#16770)

## 2023-07-17
- fix(DB/Spells): Add Deathfrost ICD (#16768)

## 2023-07-15
- chore(DB): import pending files
- fix(Scripts/SethekkHalls): Script Anzu Bird Spirit Adds (#16490)
- chore(Scripts/Misc): Improve server debug (#16708)
- fix(Scripts/Karazhan): Rewrite Terestian Illhoof (#16755)
- refactor(Scripts/Karazhan): Update The Curator (#16754)
- fix(Core/Player): don't dismiss warlock pets on logout (#16766)
- fix(Scripts/ShadowLabyrinth): Fix Vorpil voidwalkers getting stuck (#16767)
- chore(DB): import pending files
- fix(DB/Loot): Membership Benefits item loot adjustment (#16729)
- chore(DB): import pending files
- fix(DB/Spells): Add Blade of Wizardry ICD (#16758)
- chore(DB): import pending files
- fix(DB/SAI): Or'Kaos the Insane smartscript (#16765)
- fix(DB/SAI): Sand Sifter and Hai'shulud despawning after 1 minute (#16759)
- logout bots in kickall

## 2023-07-14
- Merge branch 'master' into Playerbot

## 2023-07-12
- chore(DB): import pending files
- fix(DB/SAI): Mosh'Ogg Witch Doctor SAI fix (#16742)
- fix(Scripts/MagtheridonsLair): Fix emote spam (#16746)
- fix(Core/Magtheridon): Fix Manticron Cube mechanic (#16745)
- chore(DB): Fix Blast Wave ID (#16744)
- fix(Core/Gossip): Fix gossip menu for locale clients (#16531)
- fix(Scripts/GruulLair): Fix Maulgar not casting intimidating shout (#16743)

## 2023-07-11
- chore(DB): import pending files
- fix(DB/Loot): Remove loot from Hellfire Channeler (#16738)
- fix(DB/SAI): Fingrom Blast Wave (#16737)
- chore(DB): import pending files

## 2023-07-10
- fix(DB/Loot): Correct Loot for several TBC Heroics (#16716)
- chore(Scripts/GruulsLair): Adjust timers for Reverberation and Hurtful Strike (#16732)
- fix(Scripts/MagtheridonsLair): fix Magtheridon's Quake spell (#16730)
- chore(DB): import pending files
- fix(DB/Creature): Burning Abyssal immune mask (#16731)
- chore(DB): import pending files
- fix(DB/SAI): Claw shouldn't be killable (#16713)
- fix(DB/SAI): Adjust Spell Timers for Magtheridon's Lair adds (#16722)
- fix(DB/Creature): Link Hellfire Channelers in Magtheridon's Lair (#16721)
- chore(Scripts/MagtheridonsLair): Adjust Magtheridon's timers (#16723)

## 2023-07-09
- chore(DB): import pending files
- fix(DB/Text): 7998 - Blastmaster emi shortfuse dialogue issues (#16715)
- chore(DB): import pending files
- fix(DB/Text): Darnassus Sentinels' incorrect gossip texts (#16714)

## 2023-07-08
- fix(Scripts/HellfirePeninsula): Improve Wounded Blood Elf Pilgrim (#16566)

## 2023-07-09
- fix(Scripts/HellfireRamparts): Nazan and Vazruden properly reset (#16694)

## 2023-07-08
- feat(Core/Object): Add helper to allow removing allowed looters (#16709)
- chore(DB): import pending files
- fix(DB/Quest): It's a Fel Reaver, But with Heart (#16472)
- chore(DB): import pending files
- fix(DB/Creature): Add correct stealth to Crag Stalker (#16574)
- fix(DB/Creature): Turn 'Guard Untula' as female (#16568)
- chore(DB): import pending files

## 2023-07-09
- chore(DB/Quest): Fix typo in quest reward offer for ID 9175 (#16695)

## 2023-07-08
- chore(DB): import pending files
- chore(DB/Quest): Fix typo in quest reward offer text for ID 9145 (#16686)
- chore(DB): import pending files
- fix(DB/SAI): Un'Goro's Crystal Pylons (#16605)
- fix(DB/SAI) Cabal Spellbinder adjustment to Spell Shock target type (#16648)
- fix(DB/SAI): Gnarlpine Mystic uses the right 'Wrath' (#16690)
- chore(DB): import pending files
- fix(DB/SAI): fix Blackpaw Shaman Combat Movement (#16706)
- chore(DB): import pending files
- fix(Core/Spells): Shriveling Gaze (#15939)
- fix(Scripts/Outlands): Fix Doomwalker not reseting abilities (#16700)
- Merge branch 'master' into Playerbot

## 2023-07-06
- fix(Scripts/ShadowmoonValley): Enraged Spirits' abilities (#16571)

## 2023-07-05
- fix(Scripts/Outlands): Fix Kazzak not reseting his timers (#16675)
- fix(Core/SmartScripts): Fix a check (#16663)

## 2023-07-04
- Merge branch 'master' into Playerbot

## 2023-07-03
- feat(Core/Achievements):Add getter for completed achievement map in AchievementManager (#16662)

## 2023-07-02
- fix(Core/Reputation): remove reputation splitting for being partied (#16660)
- chore(Core/SmartAI): Add min/max timer error check for NEAR_PLAYERS (#16661)
- chore(DB): import pending files
- feat(Core/SmartAI): Add more smart events (#16642)

## 2023-07-01
- fix(Core/Spells): Add Beast Lord 4P bonus (#16655)

## 2023-06-30
- fix(Scripts/Underbog): Fix Swamplord Musel'ek combat movement (#16647)
- chore(DB): import pending files
- fix (Core/Spells) Apply Seals of Pure talent to Seal of Vengeance/Corruption again (#16559)
- fix(DB/Creature): Rework Avatar of the Martyred (#16523)

## 2023-06-29
- chore(DB): import pending files
- fix(DB/SAI): Yenniku (#16631)
- chore(scripts/Steamvault): Remove unused spells from Mekgineer Steamrigger (#16644)
- chore(DB): import pending files
- fix(DB/Creature): Make "O'Mally's Instrument Bunny" invisible to players (#16645)
- chore(DB): import pending files
- fix(DB/quest_offer_reward_locale): Add ruRU localization to "An Aggressive Defense" quest (#14205)

## 2023-06-28
- fix(Core/Worldserver): correct macros platform (#16640)

## 2023-06-27
- chore(DB): import pending files

## 2023-06-28
- fix(DB/Spells): Shoulder Charge being a buff. (#15414)
- fix(Scripts/Ionar): Remove nature damage immunity (#16586)

## 2023-06-27
- feat(Core/SAI): Implement New Smart Actions SET_SCALE & SUMMON_RADIAL (#16444)
- fix(Core/AuctionHouse): Fix AH searches with high number of auctions (#13467)
- fix(Scripts/Player): correct the parameter order in OnUpdateGatheringSkill (#16635)
- feat(Apps): Account creation script that isn't worldserver dependent (#14774)

## 2023-06-26
- fix(Scripts/SlavePens): Despawn Frozen Core after Ahune emerges (#16633)
- fix(Scripts/SlavePens): Ahune shouldn't spawn more than a single Hailstone per phase
- chore(DB): import pending files
- fix(DB/SAI): Shay Leafrunner (#16454)

## 2023-06-25
- fix(DB/Gameobject): Spawn Midsummer Bonfires in gameobject table instead (#16627)
- chore(Core/SAI): Allow ACTION_FOLLOW to stop follow movement if target type is SELF or NONE (#16445)
- fix(Scripts/AuchenaiCrypts): Fix Exarch Maladaar despawning the avata… (#16625)
- fix(Scripts/SlavePens): Add Chilling Aura to Ahune adds (#16623)

## 2023-06-24
- chore(DB): import pending files
- fix(Scripts/Midsummer): Stop Bonfires from spawning more gameobjects (#16618)
- chore(DB): import pending files
- refactor(Scripts/SlavePens): Clean up Ahune script (#16613)
- chore(DB): import pending files
- fix(DB/Trainer): Add missing Powerheal 4000 Lens to Engineering trainers (#16614)
- chore(DB): import pending files
- fix(Scripts/Mechanar): Fix Polarity shift mechanic (#16601)
- chore(DB): import pending files
- fix(DB/Trainer): Add TBC Goggles and Frost Grenades to proper reference (#16565)
- chore(DB): import pending files
- chore(Core/ScriptMgr): Hooks used in mod-aoe-loot (#16589)
- fix(DB/Creature): Avoid Chain-pulling in Auchenai Crypts (#16611)
- chore(DB): import pending files

## 2023-06-23
- Fix(DB/Quest): Inoculation - ID: 9303 (#16599)
- chore(DB): import pending files
- fix(DB/Creature): Dustbelcher NPC Movement (#16499)
- fix(DB/SAI): Mai'Zoth casts Frost Armor (#16603)

## 2023-06-22
- fix(Scripts/SlavePens): Remove the Magma Totem requirement to summoni… (#16602)

## 2023-06-21
- fix(Scripts/HellfireRamparts): Fix Nazan not casting abilities (#16598)

## 2023-06-22
- chore(DB): import pending files

## 2023-06-21
- fix(Scripts/ShadowLabyrinth): Murmur's Touch (#16600)

## 2023-06-22
- Merge branch 'master' into Playerbot

## 2023-06-21
- chore(DB): import pending files
- fix(DB/Creature): Netherweb Victim should not move or attack (#14407)

## 2023-06-19
- chore(Core/ScriptMgr): Add Hooks for profession skill gains (#16526)

## 2023-06-18
- fix(Scripts/Karazhan): Malchezaar should not cast Enfeeble on phase 3 (#16587)
- chore(DB): import pending files
- fix(DB/Item): Remove wrong RandomProperties enchantments (#16584)
- fix(Scripts/ZulFarrak): add Hearthstone mechanic to Blys party when event not started in time (#16333)
- chore(DB): import pending files
- fix(Scripts/HellfireRamparts): Fix Gargolmar Retalliation procs with … (#16585)
- fix(Scripts/TheBlackMorass): rework time rift event logic (#16535)
- chore(DB): import pending files
- fix(DB/Creature): Lower TBC Heroic bosses to level 72 (#16522)
- chore(Scripts/GruulsLair): modernise boss scripts + make timers more accurate (#16576)
- split anubrekhan, grobbulus scripts
- Merge branch 'master' into Playerbot
- chore(DB): import pending files

## 2023-06-17
- fix(DB/Creature): Make 'Grandmaster Vorpil' not interruptible (#16577)
- chore(DB): import pending files
- fix(DB/Creature): Make "Ambient Minion of Terokk" not selectable (#16569)
- fix(DB/Creature): Set level of Durnholde Mage in OHF heroic appropriate for heroic (#16563)
- chore(DB): import pending files
- fix(DB/Quest): Change quest requirement for "The Troll Cave" (#16572)
- chore(DB): import pending files
- fix(DB/SAI) Zul'Farrak: make Antu'sul (8127) despawn his summoned adds (8156) when reset (#16361)
- chore(DB): import pending files
- fix(DB/Creature): Add missing immunities to Yor (#16558)
- fix(DB/Smart Scripts) Quest 437: The Dead Fields (#16550)
- Fix(DB/Events): Disable LoS for Cluster Launcher (#16476)
- fix(DB/Quest): Correct AllowedRaces for Shattered Halls quests (#16517)
- chore(DB): import pending files
- fix(DB/Spell): Add ICD to Spellsurge and some PVP trinkets (#16551)
- chore(DB): import pending files
- fix(DB/SAI): Add Scatter Shot to Shattered Hand Sharpshooter (#16534)
- fix(DB/Gameobject): Add heroic version of Cache of the Legion (#16524)
- fix(DB/Loot): Remove normal loot drops from OHF bosses (#16553)
- chore(DB): import pending files
- fix(DB/Gameobject): Add game_event_object entry for Midsummer Banners in Shattrath (#16562)

## 2023-06-16
- chore(DB): import pending files

## 2023-06-15
- fix(DB/Creature): Add CC immunity to (H) Blood Guard Porung (#16544)

## 2023-06-16
- chore(DB): import pending files

## 2023-06-15
- fix(DB/Creature): Make Shadow Labyrinth triggers invisible to players (#16546)
- fix(DB/Creature): Make Shattered Halls triggers invisible to players (#16545)
- chore(Core/MiscHandler): SendAreaTriggerMessage with integer parameter (#16506)

## 2023-06-14
- chore(Scripts/MagtheridonsLair): rework Magtheridon boss script (#16527)

## 2023-06-13
- chore(Core/ScriptMgr):Add Hook OnBeforeFillQuestLootItem (#16509)
- Merge branch 'master' into Playerbot

## 2023-06-11
- chore(DB): import pending files
- fix(DB/Creature): Lower Doom Lord Kazzak's damage (#16488)
- chore(DB): import pending files
- fix(Scripts/Underbog): Lower range check for Tentacle Lash (#16497)
- fix(DB/SAI): Rework Black Morass Elites SmartAI (#16514)
- chore(DB): import pending files
- fix(DB/Creature): Reanimated Bones pulling too much (#16498)
- Spell(item check): turn ItemLevel to RequiredLevel

## 2023-06-09
- fix(Scripts/ShadowLabirynth): Fix Murmur not using abilities (#16505)
- Merge branch 'master' into Playerbot
- split heigan
- chore(DB): import pending files

## 2023-06-08
- fix(DB/Creature): Root Mennu the Betrayer totems (#16501)

## 2023-06-09
- fix(Scripts/Karazhan): Opera Wizard of Oz fight correct start timers for combat as well fixing restart of the event (#16303)
- chore(CI): Restore broadcast_text check (#16483)
- chore(Core/Conf): Move DungeonFinder.OptionsMask to rest of lfg stuff (#16398)
- fix(Core/Spell): Net-o-Matic (#16482)

## 2023-06-08
- chore(DB): import pending files
- refactor(Scripts/Auchindoun): Mass struct/model update (#16266)
- split grobbulus

## 2023-06-07
- Merge branch 'master' into Playerbot
- fix(Core/Scripts): Ghaz'an acid spit should hit just one target (#16410)
- chore(DB): import pending files
- fix(DB/Gameobject): Instance portal in Escape from Durnholde Keep not showing (#16491)
- fix(DB/ShatteredHalls): add CC immunities to a variety of trash mobs (#16478)
- chore(DB): Fix Typo Again (#16479)
- chore(DB): import pending files

## 2023-06-06
- fix(DB/Creature): Add missing mechanic immunities to Rift Lord/Keeper (#16487)

## 2023-06-07
- chore(DB): import pending files

## 2023-06-06
- refactor(Scripts/ShatteredHalls): move Porung from SAI to cpp (#16417)
- spilit boss_heigan to .cpp and .h
- Merge branch 'master' into Playerbot

## 2023-06-05
- chore(DB): import pending files
- fix(Scripts/Underbog): modernise boss scripts (#16149)

## 2023-06-04
- fix(DB/SAI): Archaedas despawns his adds after dying (#16446)
- fix(DB): Fix typo in 2023_05_28_03.sql (#16473)

## 2023-06-05
- chore(DB): import pending files

## 2023-06-04
- fix(DB/Holidays): Add the next 75 Darkmoon Faires (#16474)

## 2023-06-02
- chore(DB): import pending files

## 2023-06-03
- fix(DB/Creature): Correct position of Jin'Zallah the Sandbringer (#16413)

## 2023-06-02
- chore(DB): import pending files
- fix(DB/Creature): Make Gargantuan Abyssal immune to knockbacks (#16450)
- chore(DB): import pending files
- fix(DB/Creature): Charming Totem Movement (Heroic) (#16449)
- chore(DB): import pending files
- fix(DB/Creature): Remove Sha'tar rep gain from Restless Skeletons (#16276)
- fix(DB/Creature): Ghostly Philanthropists drop no gold in wotlk (#16406)
- fix(DB/Creature): NPC Barkeep Daniels - Texts missing (#16257)
- add(DB/NPC) Missing Text for Tavernkeep Smitts (#16259)
- fix(DB/Quest): improve Teleport This! (#16377)
- fix(DB/Creature): Correct Old Man Barlo position (#16405)
- chore(DB): import pending files
- fix(DB/SAI): Add Magnetic Pull to Living Cyclone and remove wrong… (#16364)
- Merge branch 'master' into Playerbot

## 2023-06-01
- chore(DB): import pending files
- fix(Scripts/Spells): Convert some Druid spells to SpellScript (#16414)
- fix(Scripts/UBRS): Update UBRS/Pyroguard Emberseer script to fix issues and increase accuracy (#16352)
- fix(Scripts/Quest): Make quest "Triage" (6622/6624) completable (#16335)
- chore(DB): import pending files

## 2023-05-31
- fix(DB/SAI): Zul'Farrak - Adds creature_formations for trash in the last boss room (#16363)
- fix(Core/SmartScripts): Allow SAI_ACTION_DIE to accept params (#16411)

## 2023-06-01
- chore(DB): import pending files

## 2023-05-31
- fix(DB/SAI): Lupine Delusion (5097) and Illusionary Phantasm (6493) properly despawn when hit (#16382)
- fix(Core/Scripts): Sepethrea should prioritize players that don't hav… (#16412)

## 2023-06-01
- chore(DB): import pending files
- fix(Scripts/ShatteredHalls): hack fix to prevent pets from pulling the non-attackable peons in Nethekurse room (#16396)

## 2023-05-31
- fix(Core/Scripts): Rework Pandemonius (#16407)
- fix(DB/Creature): Immunity mask for Rift Lord/Keeper (#16408)
- fix(Core/Scripts): Ikiss polymorph target (#16409)

## 2023-05-29
- Merge branch 'master' into Playerbot
- command setskill range allow 0
- chore(DB): import pending files
- fix(Script/HellfirePeninsula):  Beacons not attracting mobs. (#15296)
- fix(DB/Creature): remove very strange resistance from Kaliri Swooper, Matriarch and the Hatchlings (#16367)

## 2023-05-28
- fix(DB/Creature): add immunities to Uvuros (#16380)
- fix(Scripts/ShatteredHalls): Nethekurse shouldn't roleplay in combat (#16395)
- fix(Scripts/ShatteredHalls): Fire Executioner's call on heroic only (#16394)
- refactor(Scripts/CavernsOfTime): Mass struct/model update (#16268)
- fix(Scripts/Commands): Fix '.send items' command to no longer require an itemId count (#16340)
- refactor(Scripts/Outland): World Boss model update (#16279)
- chore(DB): import pending files
- fix(Scripts/ShatteredHalls): Implement the Flame Gauntlet event (#16383)
- chore(DB): import pending files
- fix(Scripts/ShatteredHalls): Prevent boss from being pulled early (#16389)
- chore(DB): import pending files
- fix(Core/Creature): Re-Add IGNORE_ASSISTANCE_CALL flag (#16387)
- fix(Core/Script): Kargath should prevent adds spawn on death (#16388)
- chore(DB): import pending files
- fix(DB/Loot): Lower chance on pattern drops for Shattered Hand Legionnaire (#16386)
- fix(Scripts/ShatteredHalls): Fix Nethekurse delay after peon dies (#16384)
- chore(DB): import pending files
- fix(DB/ShatteredHalls): Fix Legionnaires in Sparring Hall calling 2 adds at a time (#16381)

## 2023-05-27
- fix(Scripts/Npc) Experience Eliminator only asks pertinent questions (#16310)
- chore(SQL): fix delete query (#16378)

## 2023-05-26
- HandlePlayerLoginFromDB
- Prevent GUID from exhausting

## 2023-05-24
- chore(DB): import pending files
- fix(DB/Loot): Overtuned loot drops in Hellfire Citadel dungeons (#16322)
- chore(DB): import pending files
- fix(Core/SAI): Allow LINK events to use event_chance (#16308)
- fix(Core/Player): Logic (#16305)
- fix(DB/ArathiHighlands): set Kenata Dabyrie's run speed to a more realistic value (#16338)
- fix(DB/creature_template_spell): Add "Threaten" spell to "Wild Fel Stalker" (#16342)
- fix(DB/SAI): Update Blackrock Summoner (9818) summoning logic (#16350)
- feat: fix warning and configuration
- Merge branch 'master' into Playerbot

## 2023-05-23
- fix(Core/Spells): Hunter snake trap damage (#16326)
- chore(DB): import pending files
- fix(DB/Character): Allow names to be accent senstive (#16344)
- chore(DB): import pending files
- fix(Scripts/ShatteredHalls): Rewrite Warchief Kargath Bladefist (#16355)

## 2023-05-21
- chore(DB): import pending files
- fix(Core/Scripts): Rewrite Warbringer O'mrogg (#16346)
- chore(DB): import pending files
- fix(Scripts/ShatteredHalls): Rework Nethekurse (#16265)
- chore(DB): import pending files
- fix(DB/ShatteredHalls): Implement scripted adds for Porung and Kargath (#16334)

## 2023-05-20
- chore(DB): import pending files
- fix(DB/Creature): Missing stealth detection to some creatures (#16331)
- fix(DB/Creature): Misc fixes for TBC Heroic dungeons (#16330)
- chore(Scripts/BloodFurnace): Clean up Keli'dan script (#16321)

## 2023-05-18
- fix(Core/Player): Instance.IgnoreRaid kicking people out (#16306)
- fix(Scripts/ZulGurub): fix timing regression for Venoxis cobras (#16309)

## 2023-05-17
- chore(DB): import pending files
- feat(Core/SAI): Implement SMART_ACTION_DISABLE  (#16254)

## 2023-05-16
- feat(apps/scripts): set a logging file for gdb using starter app (#16278)

## 2023-05-15
- chore(DB): import pending files

## 2023-05-14
- fix(DB/Quest): All Clear! - Missing RP Event (#16255)
- chore(DB): import pending files
- fix(Scripts/HellfireCitadel): Mass struct/model update (#16264)
- chore(DB): import pending files
- fix(DB/Quest): Plundering the Plunderers - Polly improvements. (#15265)
- fix(Core/Spells): Dungeon T3 2P Bonuses for Wastewalker & Doomplate. (#16076)
- chore(DB): import pending files
- fix(DB/Loot): Orphic Bracers (#16188)
- chore(DB): import pending files
- fix(DB/Creature): NPC Harold Lane is not performing emotes (#16260)
- fix(DB/Creature): Jessera of Mac'Aree and Messenger Hermesius  (#16253)
-  fix(DB/Quest): Missing RP event after completing the quest "Deciphering the Book" (#16252)
- feat(Core/Loot): Add `Rate.Drop.Item.GroupAmount` to increase loot generated from loot groups (#16220)
- chore(DB): import pending files
- fix(DB/Quest): Add RP for Quest - `Strange Brew` completion. (#16098)

## 2023-05-13
- fix(DB/Creature): Adjust Flameshocker (#16194)

## 2023-05-14
- Revert "fix(DB/Conditions): Gordok Shackle Key should not be seen if you already have one. (#12792)"

## 2023-05-13
- chore(DB): import pending files
- fix(Scripts/ShatteredHalls): fix some timers/mechanics of Grand Warlock Nethekurse (#16167)
- fix(Core/Spells): Seal of Command, Seal of Vengeance and Seal of Corruption do not benefit from percentage damage increases (#15940)
- chore(DB): import pending files
- fix(DB/SAI): Move Floon,Raliq the Drunk and Sal'salabim to SAI. (#15505)
- fix(Core/Player): Double health regen from spirit (#15955)
- fix(Scripts/HallsOfReflection): Improve Halls of Reflection Events (Horde) (#16165)
- fix(DB/Loot): fix gold drops of ethereal mobs in Bash'ir Landing (#16118)

## 2023-05-14
- chore(core): Cleanup code p2 (#16041)

## 2023-05-13
- fix(DB/GameObject): Remove dynamically spawned necropoli gameobjects. (#16251)
- fix(DB/Nagrand): add missing ability to Ravenous Windroc (#16195)
- fix(DB/Warden): New checks (Detects PQR)  (#16163)
- fix(Scripts/Deadmines): Fix Factory Door in Deadmines being closable (#15201)
- fix(Scripts/Mechanar): Avoid Nether Charge despawn (#16190)
- fix(Scripts/HellfireRamparts): modernise boss scripts for Hellfire Ramparts (#16250)
- fix(Core/Player): Apply equip effect auras with -1 duration (#14809)
- fix(DB/Creature): Several equipment fixes (#14929)
- fix(Scripts/VioletHold): Activation Crystals (#13176)
- fix(DB/Creature): Root Ironhand Guardian (#13759)

## 2023-05-14
- fix(Core/mail): letter paper (#15039)

## 2023-05-13
- fix(Scripts/Underbog): Rework Swamplord Muselek (#14724)
- chore(DB): import pending files
- Revert "fix(Core/Spells): Seal of Command, Seal of Vengeance and Seal… (#15938)

## 2023-05-14
- fix(Core/ObjectMgr.cpp): Wrong format occurred (invalid format string) (#16168)

## 2023-05-13
- fix(DB/SAI): Rework Auchenai Crypts trash SAI (#16186)
- fix(Core/Spells): Apply AURA_STATE_FAERIE_FIRE to Lambent Blood. (#16103)
- chore(DB): import pending files
- fix(DB/Creature): Update immunities to make Spectral Performers immune to CC (#16048)
- fix(Scripts/ShatteredHalls): fixes to Warbring O'mrogg combat scripts and timers (#16091)
- revert(Core/Player): Revert Delayed Damage System (#16246)

## 2023-05-12
- chore(DB): import pending files
- fix(Scripts/Underbog): Underbat's Tentacle Lash should be casted only … (#14566)
- chore(DB): import pending files
- fix(DB/SAI): add RP event for Lieutenant Gravelhammer and Captain Auric Sunchaser in Allerian Stronghold (port from TC) (#16196)
- chore(DB): import pending files
- fix(Scripts/Outland): add missing C++ code and remove SAI scripts from Tavarok and Darkweaver Syth (#16178)
- chore(DB): import pending files
- fix(Scripts/TheSlavePens): port SAI from bosses to C++ (#16169)

## 2023-05-10
- chore(DB): import pending files
- fix(DB/Creature): Reduce HP of unit_class paladin level 66 to 4892 (#16147)
- chore(DB): import pending files
- fix(DB/Creature): Remove Erroneous Mind Control Spell from Creature 601 (#16181)
- chore(DB): import pending files
- fix(DB/Creature): Remove Creature Entry 621 (#16182)
- fix(Vehicle): Crash (#16184)
- chore(DB): import pending files
- fix(DB/SAI): Void Baron Galaxis encounter. (#15312)
- fix(DB/SAI): Rework Trash SAI for Blood Furnace (#16123)
- chore(DB): import pending files
- fix(DB/BloodmystIsle): Add Tzerak Pathing and missing Nazzivius gameobjects (#16151)
- fix(DB/SAI): Revamp Underbog Trash SAI (#16129)
- fix(DB/Creature): Correct Cleric and Ghostrider of Karabor factions (#16170)
- fix(DB/Creature): Add pathing to Zandras (#16175)
- fix(DB/Quest): Correct quest progression in Children's Week Alliance Side (#16173)
- fix(Scripts/ShadowLabyrinth): Improve Grandmaster Vorpil script (#16126)

## 2023-05-09
- chore(DB): import pending files
- fix(DB/Creature): Implement Antonio Perelli script (#16156)
- chore(DB): import pending files
- fix(DB/SAI): Rework The Slave Pens Trash SAI (#16130)
- fix(DB/MagtheridonLair): Revamp Magtheridon's Lair spawns (#16174)

## 2023-05-07
- fix(Core/Spells): Delayed Damage system (#16183)

## 2023-05-06
- feat(Core/Hooks): Add parameter to detect XP origin for OnGiveXP hook. (#16109)

## 2023-05-03
- chore(DB): import pending files
- fix(DB/Creature): Add missing pathing to Exodar Peacekeeper (#16152)
- fix(DB/Creature): Add Namdo Bizzfizzle (#16153)
- fix(DB/Event): Correct Orphan Matron Mercy item restoration gossip (#16159)
- fix: Crash on ProcessDelayedDamages (#16166)
- chore(DB): import pending files
- fix(DB/SAI): Rework Trash SAI for The Botanica (#16135)

## 2023-05-01
- Merge branch 'azerothcore:master' into Playerbot
- Merge pull request #6 from kjack9/Playerbot
- fix(Docker): add libboost-thread-dev dependency to Dockerfile
- chore(Scripts/BloodFurnace): Clean up unused code in Broggok script (#16145)
- chore(DB): import pending files
- revert(DB/Warden): Remove the Warden checks recently added (#16144)

## 2023-04-30
- chore(DB): import pending files
- fix(DB/Warden): New checks (#16133)

## 2023-04-29
- fix(Core/Instance): AhnQiraj crash (#16124)
- chore(DB): import pending files
- feat(Core/Unit): anticheat helper (#16115)

## 2023-04-30
- fix(DB/Spell): Essence of Wintergrasp  (#16132)

## 2023-04-29
- chore(DB): import pending files

## 2023-04-30
- fix(DB/Spell): Correct Essence of Wintergrasp zones (#16131)

## 2023-04-29
- fix(DB/SAI): Tweak SAI for Hellfire Ramparts (#16121)
- fix(DB/SAI): Correct Bonechewer Beastmaster in Hellfire Ramparts (#16117)

## 2023-04-30
- fix(DB/Creature): Spawn and Script Pool of Souls (#14923)

## 2023-04-29
- chore(DB): import pending files
- revert(Core): ChrRace.dbc full implementation (#16114)
- chore(DB): import pending files
- fix(core\player): Missing combat animation (#14199)
- update (core\store): sLFGDungeonStore update (#15325)

## 2023-04-28
- fix(Scripts/ShadowLabyrinth): Fix Murmur combat bug caused by Suppres… (#16122)

## 2023-04-27
- chore(DB): import pending files
- chore(core/instance): Move to switch case (#16084)
- fix(core/dbc): improve ChrRace DBC handling (#14843)
- chore(DB): import pending files
- feat(core\dbc): item.dbc, sItemStore, item_dbc, item enforcement conf, subclass fix (#14675)
- chore(DB): import pending files
- fix(Scripts/IcecrownCitadel): Tirion Fordring attacks the Lich King empty-handed (#15823)

## 2023-04-26
- chore(DB): import pending files
- fix(DB/ShadowLabyrinth): Fixes for Heroic Shadow Labyrinth (#16087)
- Merge branch 'azerothcore:master' into Playerbot
- chore(DB): import pending files
- fix(DB/Creature): Fixed chain pulling in Blackheart's Arena (#16055)
- fix(DB/Creature): Remove vendor flag from Anchorite Yazmina. (#16081)
- fix(DB/Creature): Add missing Blood Guard Porung to Shattered Halls (#16068)

## 2023-04-25
- fix(Core/SmartScripts): Add Triggered Flags for CAST & INVOKER_CAST (#16045)
- feat(DB): Release ACDB 9.0.0 (#16069)

## 2023-04-24
- Merge branch 'azerothcore:master' into Playerbot
- chore(core): cleanup code p3 (#16073)

## 2023-04-23
- chore(DB): import pending files
- refactor(DB/Misc): Improve loading time (#15433)
- fix(DB/Creature): Revamp TBC DamageModifier and ArmorModifier values (#15807)
- fix(DB/Creature): Use sniffed speeds for Heroic versions of TBC creatures (#15813)
- fix(DB/Creature): Port more VMangos Walk/Run Values (#15820)
- Merge branch 'azerothcore:master' into Playerbot
- chore(DB): import pending files
- fix(DB/SAI): Correct Daggerfen npcs (#16067)
- chore(DB): import pending files
- fix(Scripts/ShatteredHalls): Update Grand Warlock Netherkurse (#16063)
- fix(Scripts/ShadowLabirynth): Clean up script and fix doors (#16061)
- chore(DB): import pending files

## 2023-04-22
- fix:(DB/Loot): Put Item 1219 onto the correct loot table (#15922)
- refactor(Scripts/ShadowLabirynth): Rework Grandmaster Vorpil (#16053)
- fix(Scripts/ShadowLabs): Fix Murmur Touch dealing damage twice (#16058)
- chore(DB): import pending files
- fix(DB/Reputation): Correct Rep for Heroic Nexus Terror (#15801)
- chore(DB): import pending files
- feat: Allow Float Rep Values (#15818)
- chore(DB): import pending files
- fix(DB/SAI): Outland Crumbling giants. (#15604)
- fix(DB/Loot): Darkwood Fishing Pole (#15639)
- fix(DB/Locale): deDE fixes for achievement reward (#15302)
- fix(DB/SAI): Use SAI for Spitelash Naga in Azshara (#15808)
- chore(DB): import pending files
- fix(DB/ShatteredHalls): Re-Construct Shattered Halls (#15990)
- fix(DB/Creature): The Curator - Aggro range (#16039)
- fix(Core): Save bonus talent points to DB (#14099)
- fix(DB/Creature): Tamed Kodo - Remove gosisp flag. (#15165)
- fix(Core/Spells): Fixed somed Druid idols not being modified by spell… (#15452)
- fix(Scripts/ManaTombs): Yor stomp added (#15986)
- fix(DB/ShadowLabyrinth): Adjust values for Murmur's Arena (#16054)
- fix(DB/Loot): Correct MinCount for Cabal Acolyte Fel Armaments (#16056)

## 2023-04-21
- Merge branch 'azerothcore:master' into Playerbot
- fix(Core/Player): Reduce Health Regeneration bonus while sitting to 33% (#15954)
- chore(DB): import pending files
- fix(Scripts/Creature): Add Ravenclaw Apparition event. (#15200)
- fix(Scripts/Naxxramas): Improve Gothik's minions (#15979)
- fix(Core/Player): Food healing does not increased by sitting down (#15959)
- refactor(Scripts/ShadowLabirynth): Update Blackheart the Inciter to t… (#16049)
- fix(Scripts/ShadowLabirynth): Fixed Blackheart's Incite Chaos. (#15583)
- fix(Core/Player): Apply SPELL_AURA_MOD_HEALTH_REGEN_PERCENT to in combat health regen (#15961)
- chore(Spell/Effects): Small improvement to EffectDistract (#15920)

## 2023-04-20
- Merge branch 'azerothcore:master' into Playerbot
- chore(DB): import pending files
- fix(Core/Creature): Adjust IGNORE ASSISTANCE CALL flag to prevent assistance on initial aggro only (#16046)
- chore(core): Cleanup code (#16012)

## 2023-04-19
- fix(Scripts/ShadowLabyrinth): Update Grandmaster Vorpil's script (#16018)
- chore(DB): import pending files

## 2023-04-20
- fix(DB/Conditions):  Add missing gossip text for Rathis Tomber. (#16007)

## 2023-04-19
- chore(DB): import pending files
- fix(DB/SAI): Port Wickerman Guardian from Mangos. (#15844)
- chore(DB): import pending files
- fix(DB/Conditions): Costume Scraps not having quest status requirements. (#15929)
- fix(DB/Creature): Spitelash Serpent Guard equipment (#16036)
- chore(DB): import pending files
- fix(DB/SAI): Bogblossom trap - knockback and despawn. (#16003)
- fix(DB/Loot): Remove Head of Ortor of Murkblood from pickpocketing loot (#16015)
- Merge branch 'azerothcore:master' into Playerbot
- chore(DB): import pending files
- fix typo for Clutchmother. (#16034)
- fix(DB/Quest): Fix for Boiling Point (11627) (#16001)
- fix(DB/Quest): Correct creature/objects for quest Whispers of the Raven God. (#15933)
- fix(DB/Creature): Port Immunities for Ogrila quest npcs from Mangos. (#15999)
- chore(DB): import pending files

## 2023-04-18
- fix(Scripts/ShadowLabyrinth): Blackheart the Inciter's room link (#15994)
- chore(DB/SAI): Delete duplicate SAI rows for new SAI override system (#16011)
- fix: Channel Crash (#15909)

## 2023-04-19
- fix(DB/SAI): Port Quest: 'By Any Means Necessary' from Trinity (#15822)

## 2023-04-18
- fix(DB/ShadowLabyrinth): Apply 'Incite Chaos' as debuff (#15997)

## 2023-04-19
- chore(DB): import pending files
- fix(DB/Spell):  Fel Reaver Sentinel spells not having CD. (#15982)
- chore(DB): import pending files
- fix(DB/Creature): Update En'kilah Hatchling Faction (#15921)
- chore(DB): import pending files
- fix(DB/String): Update the zhCN value of id 586 (#15943)
- chore(DB): import pending files
- fix(DB/Conditions): Allow gossip with Ethereal Teleport Pad after quest 10270. (#15991)

## 2023-04-18
- fix(DB/SAI): Fel Overseer - Frightening Shout (#15995)

## 2023-04-19
- fix(DB/Scripts): Infernal Oversoul spawn position. (#15983)
- chore(DB): import pending files

## 2023-04-18
- fix:(DB/Creature): Correct respawn timer for Corporal Keeshan (#15891)

## 2023-04-19
- fix(DB/SAI) Curtains Call is now only casted on death. (#15969)
- fix(DB/SAI): Correct Slaag, Maggoc and Grulloc. (#16002)
- chore(DB): import pending files

## 2023-04-18
- fix(DB/Loot): Remove Roughshod Pikes from creature loot (#15916)

## 2023-04-19
- fix(DB/Creature): Remove npc flags from outland First Aid Trainers. (#16005)
- fix(DB/Vendor): Remove vendor flag and items from Prospector Ryedol. (#16008)
- fix(DB/SAI): Remove wrong spell from Fiendling Flesh Beast. (#16004)
- fix(DB/SAI): Harbinger of the Raven falling instead of flying. (#15947)
- fix(DB/Creature): Correct Cyrukh the Firelord immunity mask. (#15968)

## 2023-04-18
- fix(DB/Creature): Update Patchwerk visibilityDistance (#15973)

## 2023-04-19
- fix(DB/SAI): Bloodmaul Geomancer does not cast Chilled (#15949)
- fix(DB/Spells): Restore Fiery Payback to have no ICD. (#15981)
- fix(DB/Formations): Aggro Strider Clutchmother adds  (#15863)

## 2023-04-18
- fix(DB/Loot): Add missing Tailoring Patterns in TBC Normals (#16009)
- fix(DB/SAI): Enables and Adds SAI for Zem Leeward (348) (#15890)
- fix(Scripts/ShadowLabyrinth): Murmur - Sonic Shock's timer (#16006)
- fix(DB/Loot): Remove skinning loot from several Buzzard type mobs (#15908)

## 2023-04-19
- chore(DB): import pending files

## 2023-04-18
- fix(DB/Creature): Add Interrupt Immunity to Murmur (#16010)
- Merge branch 'azerothcore:master' into Playerbot
- chore(DB): import pending files

## 2023-04-17
- fix(DB/Creature): Correct damage school of Steamvault Surgers (#15926)

## 2023-04-18
- fix(Core/Hook): Fix OnAuraRemove not being called for owned auras. (#15930)
- fix(Scripts/ShadowLabyrinth): Boss spell timers correct values (#15984)
- chore(DB): import pending files
- feat(Core/SmartScripts): SMART_ACTION_SELF_CAST (#14371)

## 2023-04-17
- feat: Add CanPlaceAuctionBid hook (#15154)

## 2023-04-18
- chore(DB): import pending files
- fix(Scripts/ShadowLabyrinth): fix Grandmaster Vorpil (#15962)

## 2023-04-17
- fix(DB/SAI): Correct Bog Overlord Trample being cast twice (#15927)
- chore(DB): import pending files

## 2023-04-18
- fix(DB/SAI): Power Converter not despawning. (#15957)

## 2023-04-17
- chore(DB): import pending files
- fix(Scripts/ShadowLabirynth): Fix OOC Murmur Supperssion Barrage (#15992)
- chore(DB): import pending files
- fix(Scripts/ShadowLabyrinth): Update Murmur script (#15970)

## 2023-04-16
- Merge branch 'azerothcore:master' into Playerbot
- chore (core): Clean up (#15977)
- feat(Core/SAI): Implement SMART_ACTION_SET_GUID (#15978)
- feat(Core/Creature): Implement CREATURE_FLAG_EXTRA_DONT_OVERRIDE_ENTR… (#15976)

## 2023-04-15
- chore(DB): import pending files
- fix(DB/Loot): Murmur loot count correction (#15964)
- Revert "fix(Core/SAI): Set minions in combat with their master's vict… (#15967)
- fix(Scripts/GruulsLair): timing/scripting fixes for High King Maulgar fight (#15924)

## 2023-04-14
- chore(Scripts/ShadowLabyrinth): Modernize Ambassador Hellmaw (#15944)

## 2023-04-13
- Merge branch 'azerothcore:master' into Playerbot

## 2023-04-12
- chore(DB): import pending files
- fix(DB/Loot) Remove Netherweave Tunic drop (#15923)
- chore(DB): import pending files
- fix(Script/Spell): Fix animal blood pool effect and position (#15918)
- chore(DB): import pending files
- fix(Scripts/Netherstorm): Remove hardcode from zone_netherstorm. (#15805)

## 2023-04-10
- Merge branch 'azerothcore:master' into Playerbot

## 2023-04-09
- fix(Core/SmartAI): Prevent MOVE_TO_POS from creating large distances between target (#15899)
- fix(Scripts/Steamvault): Despawn Thespia's adds on death (#15898)
- chore(DB): import pending files
- fix(Scripts/Steamvault): Rework Mekgineer Steamrigger (#15896)
- chore(DB): import pending files
- fix(Script/Ahnkahet): Jedoga Shadowseeke sacrifice (#15153)
- fix(DB/Loot): Fel Orc Blood Vial should drop only inside Blood Furnace. (#15340)
- fix(Spells/Scripts): Raise Ally improvements. (#15545)
- fix(DB/SAI): Outland Basilisks. (#15578)
- fix(Script/ToC5): Remove hardcoded text(s) and some minor adjustments. (#15046)
- feat(Core/Scripts): Allow scheduling multiple hp checks at once for i… (#15897)
- chore(DB): import pending files
- fix(Scripts/ShadowLabirynth): Ambassador Hellmaw: (#15761)
- chore(DB): import pending files
- fix(DB/Creature): Correct respawn timers for 2 TBC quest mobs (#15886)
- chore(DB): import pending files
- fix(DB/Quest): Improve Quest Betrayed (3506) and port from event_script to SAI (#15852)
- fix(DB/Loot): Remove Pattern: Drums of Restoration from reference loot. (#15877)
- fix(DB/Conditions): Add missing SmartAI conditions to Blood Furnace (#15875)
- chore(DB): import pending files

## 2023-04-08
- fix(DB/Reputation): Correct onkill reputation for Shattered Halls (#15881)
- chore(SQL): Remove select query (#15888)
- fix(Core/Events): fix infinite loop (#15887)

## 2023-04-09
- chore(DB): import pending files

## 2023-04-08
- fix(Scripts/Steamvault): Rework Kalithresh (#15883)
- chore(DB): import pending files
- refactor(DB/SAI): Cleanup Shattered Halls SAI (#15880)
- fix(CI): Windows build (#15879)
- fix(Scripts/SethekkHalls) Fix Talon King Ikiss Blink (#15876)

## 2023-04-07
- chore(DB): Correct typo in 2023_04_02_02.sql (#15874)
- fix(Scripts/IcecrownCitadel): Fix Svalna crash (#15862)

## 2023-04-06
- fix(Scripts/IcecrownCitadel): Fix Putricide crash (#15846)
- Merge branch 'azerothcore:master' into Playerbot
- chore(DB): import pending files
- chore(SQL): Rename fix-spire-frostwyrm-remnant-alliance to fix-spire-frostwyrm-re… (#15841)
- chore(DB): import pending files

## 2023-04-05
- fix(DB/ShadowLab): Re-Construct Shadow Labyrinth (#15635)
- fix(Scripts/Steamvault): Correct timers and add missing events (#15840)

## 2023-04-06
- fix(DB/Creature)> Remove the Spire Frostwyrm remnant in alliance side (#15838)

## 2023-04-05
- fix(Scripts/Arcatraz): Remove Skyriss' immunity at reset (#15833)
- chore(DB): import pending files
- fix(DB/Creature): Remove Spire Frostwyrm leftovers
- fix(Scripts/IcecrownCitadel): Fix Sindragosa's icewall poping up prem… (#15836)
- Merge branch 'azerothcore:master' into Playerbot
- chore(DB): import pending files
- fix(DB/Loot): Ferra add in DM:W not dropping correct loot (#15782)
- fix(DB/Loot): Junk Loot from Water Barrels removed (#15540)
- fix(Scripts/IcecrownCitadel): Fix possible crash if bosses engage off… (#15832)
- fix(Scripts/Arcatraz): Fix Harbringer Skyriss not splitting if castin… (#15811)
- chore(DB): import pending files
- chore(DB/SAI): Remove unused SAI from Yor (#15828)
- fix:(DB/Creature): Removes unused creature 290 data (#15826)

## 2023-04-04
- Merge branch 'azerothcore:master' into Playerbot
- chore(DB): import pending files
- fix(DB/Creatures): Corrected Snivel Rustrocket's position. (#15353)
- fix (DB/Loot) Add Tailoring condition for the Battlecast Hood Recipe (#15797)
- Underbog frenzy aggro (#15581)
- Merge branch 'azerothcore:master' into Playerbot
- chore(DB): import pending files
- fix(DB/Quest): Prevent Earthmender Wilda to fail quest abruptly (#15816)
- fix(DB/Creature): fix damage modifier of Razormaw (#15785)
- fix(DB/SAI): Port On Nethery Wing visuals from Trinity. (#15806)
- fix(Scripts/IcecrownCitadel): Prevent Sindragosa's landing trigger fr… (#15814)
- chore(DB): import pending files
- fix(Scripts/SlavePens): Added waypoint movement to Quagmirran. (#15582)

## 2023-04-03
- Merge branch 'azerothcore:master' into Playerbot

## 2023-04-04
- chore(DB): import pending files
- fix(DB/Reputation): Onkill rep for Steamvault and Shadow Labyrinth (#15809)
- fix(DB/SAI): Sentinel Keldara Sunblade attacking while feign death (#15784)
- fix(DB/Conditions): Jesse Masters selling items without quest completion (#15777)
- fix(DB/Loot): Blood of the Mountain dropping from wrong mobs. (#15768)
- fix(DB/SAI): Port The Knife Revealed RP from Trinity. (#15796)
- fix(DB/SAI): Correct Bael'dun creatures not fleeing. (#15794)

## 2023-04-03
- fix(DB/SAI): Slow down Darkshire City Hall broadcasts (#15791)

## 2023-04-04
- fix(DB/creature_addon): Remove deprecated bytes2 flags. (#15788)

## 2023-04-03
- feat(Scripts/IcecrownCitadel): Allow game masters to skip boss checks (#15810)
- Merge branch 'Playerbot' of https://github.com/ZhengPeiRu21/azerothcore-wotlk into Playerbot
- Merge branch 'master' into Playerbot
- chore(DB): import pending files
- fix(Scripts/IcecrownCitadel): Script Sindragosa's respawn/waypoints (#15792)

## 2023-04-02
- chore(DB): import pending files
- fix(DB/Spells): Added 8sec cooldown to Stormchops proc. (#15756)
- fix(DB) Deadmines Cleaver should only drop from Defias Henchman (#14807)
- chore(DB): import pending files
- fix(DB/Conditions): Lok'delar & Rhok'delar should not be mutually exclusive. (#15183)
- chore(DB): import pending files
- fix(Scripts/VioletHold): Remove hardcoded text and add some of the missing gossips. (#15058)
- fix(Core/Spell): Remove channeled auras when caster and target are no… (#15419)
- fix(Scripts/MoltenCore): Correct Baron Geddon Inferno damage values (#15637)
- fix(Core/SmartScripts): Fixed `SMART_EVENT_FRIENDLY_HEALTH_PCT` event. (#15579)
- fix(DB/SAI): Yet another fix for Teron Gorefiend not resetting (#15315)
- fix(Core/Players): Added error message for death knights attempting to lea… (#15420)
- fix(Core/Guilds): Improve HandleRoster performance (#15421)
- fix(Core/World): Remove artificially high minimal update intervals an… (#15422)
- chore(Conf/Misc): Make it easier to find FreezeDetector (#15451)
- fix(Core/Item): Fixed incorrect damage mod for Heirloom 2H weapons (#15443)
- fix(Core/Player): Send player's own auras before all visible objects (#15445)
- fix(Scripts/Karazhan): Fixed locking Shad of Aran entrance door. (#15450)
- fix(DB/Loot): Fix Warlord Kalithresh Normal Loot (#15760)
- fix(Core/Spells): Implemented `ENCHANT_PROC_ATTR_EXCLUSIVE`. (#15476)
- fix(Core/Spells): Fixed Battlegear of Eternal Justice set bonus. (#15593)
- fix(DB/SAI): Change castflags for Death Watcher's Death Count (#15739)
- fix(DB/Creature): Some immunities in Arcatraz (#15750)
- fix(Scripts/Arcatraz): fix Trial of the Naaru: Tenacity complete condition (#15742)
- chore(DB): import pending files
- fix(DB/Creature): Grunda Bronzewing is now mounted (#15783)
- Merge branch 'azerothcore:master' into Playerbot
- chore(DB): import pending files
- fix(DB/Loot): Mote of Shadow dropping from wrong creatures. (#15590)
- chore(Github): clarify OS in issue themplates (#15765)
- fix(DB/SAI): Fix Arcatraz Sentinels spawning at 1 health (#15762)
- fix(Core/Spells): Fixed Spiritual Attunement not working with partial… (#15767)
- fix(DB/Quest): Prevent infinite spawning of [DND]Spirit 1 (#15774)
- fix(Core/Pet): fix Pet::resetTalentsForAllPetsOf for stabled pets (#15779)
- fix(Scripts/SethekkHalls): Prevent pets from pulling Ikiss from behin… (#15764)

## 2023-04-01
- Merge branch 'azerothcore:master' into Playerbot
- chore(DB): import pending files

## 2023-03-31
- fix(DB/Loot): Harbinger Skyriss Normal Loot (#15752)
- chore(DB/SAI): Move Arcane Container script to SAI (#15754)

## 2023-04-01
- fix (DB/SAI) Also remove Death Count from non-players (pets) (#15749)

## 2023-03-31
- chore(DB): import pending files
- fix(DB/SAI) Stone Keepers now use Self Destruct (#15744)
- fix (DB/SAI) Negaton Screamer Aura removal on element reset (#15745)
- fix(DB/SAI): Crashfix (#15747)
- fix(DB/Reputation): Make High Admiral "Shelly" Jorrik give reputation all the way through exalted (#15748)
- chore(DB): import pending files
- fix(DB/SAI): Corrections to Death Watcher (#15729)
- fix(Core/Groups): Implement MSG_RAID_READY_CHECK_FINISHED (#15442)
- fix(Scripts/Arcatraz): Update timers after research (#15726)
- chore(DB): import pending files

## 2023-03-30
- fix(DB/Spell): Correct Effect of all Summon dbc spells (#15652)
- chore(DB): import pending files

## 2023-03-31
- fix(DB/Gameobject): Snap Floating Ivory Bell to ground. (#15596)

## 2023-03-30
- fix(DB/Loot): Remove Bloodforged Guard and Gold-Trimmed Cuffs from reference loot (#15609)
- fix(DB/SAI): Shaleskin Flayer should cast Shaleskin out of combat (#15687)
- fix(DB/SAI): Rewrite Nether Charge SAI (#15647)
- chore(DB): import pending files
- fix(Scripts/Mechanar): Add missing Enrage event for Pathaleon the Calculator (#15650)
- fix(DB/Creature): Remove rep rewards for killing Skyriss Images (#15646)
- fix(DB/SAI): Correct combat mechanics in Mechanar's Gauntlet Event (#15649)
- chore(DB): import pending files
- fix(Scripts/Arcatraz): Delay abilities during charge and delete trigg… (#15653)
- Merge branch 'azerothcore:master' into Playerbot
- fix (core) : Violating Flag correction (#15648)
- fix(Scripts/IcecrownCitadel): Fixing last issue on Nerubs in ICC (#15651)

## 2023-03-29
- Merge branch 'azerothcore:master' into Playerbot
- fix(Scripts/Arcatraz): Adjust Soccrothar charge timer and implement emote (#15643)
- fix(Scripts/Arcatraz): Millhouse uses Iceblock under 50 percent hp (#15644)
- chore(DB): import pending files
- fix(Scripts/SethekkHalls): Talon King Ikiss (#15471)
- fix(DB/SAI): Update Shadow Labyrinth combat SAI (#15565)
- fix(DB/Creature): Add missing trash pack in Mechanar (#15569)
- fix(Scripts/Steamvault): Improved Door Controller event. (#15580)
- fix(Core/Spells): Lightning Overload  should not proc off from itself. (#15595)
- fix(Core/Spells): Shadow Word: Death vs critters. (#15594)
- chore(DB): import pending files
- fix(Scripts/IcecrownCitadel): Fix Nerubar Broodkeeper flickering anim… (#15642)
- chore(DB): import pending files
- fix(DB/Creature): Added trigger flag to Gnome Cannor Shooter. (#15584)
- fix(Scripts/Spells): Fixed Improved Healthstone not affecting Ritual … (#15588)
- fix(Core/Spells): Turn the Tables can stack with itself. (#15597)
- fix(Scripts/Steamvault): Correct Timers for Thespia and add missing line (#15640)

## 2023-03-28
- Merge branch 'azerothcore:master' into Playerbot
- chore(DB): import pending files
- fix(DB/Steamvault): Rebuild Steamvault creature spawns and implement RP events (#15548)
- fix(DB/Gameobject): Nethermancer Sepethrea door should not be useable by players (#15568)
- fix(DB/Gameobject): Rebuild The Steamvault ores and herbs (#15556)
- chore(DB): import pending files

## 2023-03-27
- fix(Scripts/IcecrownCitadel): Fix Blood-Queen Lana`thel reset and fli… (#15601)
- chore(DB): import pending files
- fix(db/loot): Repair Pathaleon the Calculator Loot (#15574)
- fix(DB/Creature): Add Knockback immunity to Raging Flames (#15570)
- fix(DB/SAI): Correct timers for Arcane Servant's Arcane Volley (#15572)
- fix(DB/Creature): Correct faction of Time-Lost Skettis NPCs (#15608)
- fix(Scripts/Arcatraz): Fix Soccothrates fel flame charge (#15600)
- fix(Scripts/IcecrownCitadel): Sindragosa shouldn't kill everything on… (#15602)

## 2023-03-25
- chore(DB): import pending files
- fix(Scripts/Mechanar): Fix Mechano-Lord Nether Charges not spawning (#15575)
- Merge branch 'azerothcore:master' into Playerbot
- fix(Scripts/IcecrownCitadel): Lichking "Harvest Soul" Fix (#15573)
- feat(Core/ChatHandler): ignore chat level requirement when whispering self (#15564)

## 2023-03-24
- chore(DB): import pending files
- fix(DB/SAI): Authentic delay on dialog for Verna and Farmer… (#15560)
- fix(DB/Creature): Use addon instead of SAI for Eyeless Watcher and Unseen Servant (#15551)
- fix(DB/Creature): All Violet Hold Guard having emote 333. (#15513)
- fix(DB/Event): (Mulgore) DMF Building event GOs in Brewfest. (#15478)
- fix(DB/SAI): Ethereal Thief disarm timer. (#15413)
- fix(DB/SAI): Mosh'Ogg Spellcrafter spmming flamestrike. (#15380)
- fix(DB/SAI): Thule Ravenclaw - remove ranged movement (#15187)
- fix(DB/SAI): Shadowmoon Warlock's Fel Power should be used out of com… (#15104)
- fix(DB/SAI): Unstable Voidwrath explosion (#15105)
- fix(Scripts/IcecrownCitadel): Prevent the LK from despawning Tirion F… (#15561)
- fix(Core/Spells): Seed of Corruption cannot be reflected. (#15473)
- chore(Core/Players): Fix typo (#15552)

## 2023-03-23
- feat(Core/Mail): call CanSendMail() when returning to sender (#15553)
- Merge branch 'azerothcore:master' into Playerbot
- chore(DB): import pending files
- fix(Scripts/UtgardeKeep):  Prince Keleseth not aggroing (#15523)
- fix(Core/Players): Set environmental lava damage timer to 2.02 sec. (#15475)
- fix(DB/SAI): Update Steamvault combat SAI (#15531)
- fix(Core/SAI): Remove duplicated GO_STATE (#15530)
- chore(DB): import pending files
- fix(Scripts/Mechanar): Implement Pathaleon's spawn (#15536)

## 2023-03-22
- fix(Scripts/Mechanar): Raging Flames may target tanks (#15543)
- Merge branch 'azerothcore:master' into Playerbot
- revert (core): Dismount helper (#15544)
- Merge branch 'azerothcore:master' into Playerbot
- chore(DB): import pending files
- fix(DB/SAI): Eyeless Watcher and Unseen Servant use Greater Invisibil… (#15456)
- refactor(Scripts/Item): Make Goblin Weather Machiene script more read… (#15467)
- fix(DB/SAI): Brazen & Erozion having wrong gossips. (#15521)
- chore(DB): import pending files

## 2023-03-21
- fix(DB/Creature): Correct Onkill Reputation for Mechanar and Arcatraz (#15532)
- fix(Core/Spells): Add more exceptions to Aura of Despair. (#15231)
- fix(Core/Gossip): Do not close gossip on target deselection. (#15457)
- chore(DB): import pending files
- fix(Scripts/Zangarmarsh): Move zangarmarsh npcs to SAI (#15504)
- chore(DB/Spells): Remove duplicated entries from spelldifficulty_dbc (#15526)
- chore(DB): import pending files
- fix(DB/Trainer) Add Flying Carpet to Tailoring trainers (#15161)
- chore(DB): import pending files
- fix(Scripts/Misc): Fix bosses not reseting after the despawn update (#15507)
- fix(Scripts/Naxxramas): Improve Four Horsemen (#14247)
- fix(Core): Crashfix. (#15448)
- Merge branch 'azerothcore:master' into Playerbot
- chore(DB): import pending files
- fix(DB/SAI): Implement Gauntlet/Bridge Event in The Mechanar (#15525)
- chore(DB): import pending files
- fix(DB/SAI): Update Arcatraz Trash SAI (#15519)

## 2023-03-20
- chore(DB): import pending files
- fix(DB/Arcatraz): Re-Construct all Arcatraz spawns and rebuild and script all pathing (#15440)
- fix(Scripts/Spells): Bladestorm vs Sweeping Strikes. (#15472)
- add (core): Dismount Helper (#15511)
- chore(DB): import pending files
- fix(DB/SAI): Move Ashyen & Keleth to SAI. (#15502)
- chore(DB): import pending files
- fix(DB/Mechanar): Update The Mechanar SAI scripts for trash mobs (#15508)
- fix(Core/Object): Permanently invisible creatures should be able to e… (#15498)
- chore(DB): import pending files
- fix(DB/Gameobject): Rebuild spawns of Mana Berry Bush (#15447)
- fix(Core/Grids): Creatures should attack when loaded into grid. (#15453)
- fix(DB/Arcatraz): Fix Arcatraz Sentinels and Corpses (#15482)
- fix(Scripts/OldHillsbrad): Old Hillsbrad Foothills - Captain Skarloc casting wrong spell (#15486)
- chore(DB): import pending files
- fix(Core/Spells): Improve Feign Death scripts (#15496)
- fix(DB/Creature): Use sniffed flags for Fen Ray in Underbog (#15497)
- chore(DB): import pending files
- fix(Scripts/Mechanar): Few updates to Sepethrea (#15500)

## 2023-03-19
- refactor(Scripts/Mechanar): Modernize Pathaleon's script (#15494)
- chore(DB): import pending files
- refactor(Scripts/Mechanar): Modernize Serpethrea script (#15493)
- fix(Scripts/Mechanar): Fix Mechano-Lord Capacitus's Nether Charges (#15495)
- refactor(Scripts/Mechanar): Modernize Gatewatchers script (#15492)
- refactor(Scripts/Mechanar): Modernize Mechano Lord Capacitus script (#15491)
- fix(Scripts/IcecrownCitadel): Rewrite the Spire Frostwyrms (#15490)
- fix(Scripts): Crashfix. (#15459)
- chore(DB): import pending files
- fix(DB/Creature): Update Charming Totem movement (#15468)

## 2023-03-18
- fix(Core/Arena): Fix lag caused by arena distribution (#15444)

## 2023-03-17
- fix(Core/Spells): Healing Salve having cast time. (#15329)
- fix(Script/Core): Remove hardcoded gossips in npc_taxi (#15052)
- fix(Core/Battlefield): Wintergrasp Workshops SW/SE (#14104)
- fix(Core/Mail): Reorder mail attachment checks (#15418)
- fix(Core/Spell): Removed gathering failure chance from herbalism and … (#15423)
- fix(Core/Achievements): Add log for missing achievement (#15425)
- fix(Core/PacketIO): Require valid WorldSession for CMSG_KEEP_ALIVE (#15426)
- fix(Core/Debugging): Improve SymInitialize fail message (#15424)
- chore(DB): import pending files
- fix(DB/Creature): Misc auras added to several creatures (#14926)

## 2023-03-16
- chore(DB): import pending files
- fix(DB/Creature): Correct level for Sethekk Spirit for Heroic (#15417)
- chore(DB): import pending files
- fix(DB/SAI): Corrected Sethekk Spirit's level. Added Spirit Burst  to… (#15341)
- chore(DB): import pending files
- fix(DB/Spells) Fix Summon Morcrush Shardling Serverside Spells (#15416)
- fix(Core/Spells): Do not remove item casted auras on respec. (#15350)
- chore(DB): import pending files
- fix(DB/spell_custom_attr): Warchief's Blessing - add NO_PVP_FLAG. (#15212)
- fix(Core/Spells): Draenei Call of Air 4/4 Susurrus buff duration. (#15255)
- chore(DB): import pending files
- fix(Core/GameObject): Pumpkin Shrine (#13460)
- chore(DB): import pending files
- fix(Core/BattlefieldWG): Workshops/Graveyard not changing to neutral (#14002)
- fix(DB): Missing Gnomeregan Pathing and Formations (#12973)
- Merge branch 'Playerbot' of https://github.com/ZhengPeiRu21/azerothcore-wotlk into Playerbot
- Merge branch 'master' into Playerbot
- fix(DB): fix query (#15411)
- fix(Scripts/IcecrownCitadel): Fix ICC buff not being reapplied after … (#15407)
- chore(DB): import pending files
- fix(DB/Spell): Mr Pinchy's Blessing stacking with similar effects. (#15381)

## 2023-03-15
- chore(DB): import pending files
- fix(DB/Quest): Fix Manaforge Questline not being completable while in party (#15393)
- fix(DB/SAI): Griftah not greeting players. (#15387)
- fix(DB/Quest): Fix Stasis Chamber Alpha not respawning (#15391)
- fix(DB/Pools): Temporary fix for Arakkoa Eggs until Core is fixed (#15392)
- fix(DB/Quest): Fix Earthmender Wilda not properly resetting (#15394)
- fix(DB/SAI): Brother Sarno not greeting players. (#15385)
- fix(DB/SAI): Karaaz incorrect text target. (#15384)
- fix(DB/Creature): Port Ridgespine mobs from Mangos. (#15374)
- fix(DB/Loot): Fix Warp splinter Normal Loot Drops (#15348)
- chore(DB): import pending files
- fix(DB/SAI): Implement You, Robot failure event and properly award quest credit on success (#15324)
- chore(DB): import pending files
- fix(Scripts/Karazhan): Chess Event. (#14736)

## 2023-03-14
- chore(DB): import pending files
- fix(DB/Quest): Fixed rep requirements for some Darkmoon quests. (#15196)
- fix(DB/Quest): Improvements for request texts (#15309)
- chore(DB): import pending files
- fix(DB/Quest): Improvements for request texts #2 (#15343)
- chore(DB): import pending files
- fix(DB/Gameobjects): Fixed one spawn position of Stranglekelp. (#15356)
- chore(DB): import pending files
- fix(DB/Spells): Treat Chocolate Sample as a positive spell. (#15351)
- fix(DB/Creature): Correct movement speeds for Black Morass Heroic (#15368)

## 2023-03-13
- chore(DB): import pending files
- fix(Core): Crashfix. (#15337)
- fix(DB/Mechanar): Re-Construct The Mechanar spawns and remove custom scripts (#15372)
-  chore(Data): Add `/data/sql/custom` to gitignore (#14735)
- fix(Core/Logs): Fix warden fmt logs (#15327)
- chore(DB): import pending files
- fix(DB/Locale): deDE fixes for request items 5 (#15345)
- fix(DB/Locale): deDE fixes for request items 4 (#15344)
- chore(DB): import pending files
- fix(Scripts/Ulduar): Yogg-Saron hardcode & some adustments. (#15146)
- fix(Scripts/Creatures): Fixed some profession trainers. (#15349)
- fix(Core/Spells): Casting Basaic Campfire should give cooking skill. (#15194)
- fix(Core/Players): Charmed players should not attack critters. (#15358)
- fix(Core/Movement): Updated creature pet's follow movement. (#15360)

## 2023-03-12
- feat(Core/BasicEvents): Add the possibility to group BasicEvents (#15369)
- fix(Core/Session): Let movement flags update on their own when disabl… (#15366)
- chore(DB): import pending files
- fix(Scripts/Achievement): Fixed Flirt With Disaster achievement. Sourc… (#15352)
- feat(Core/Player): Implement helper to send system messages to players (#15364)
- fix(Scripts/BlackMorass): Don't pick the same rift spot in succession (#15359)
- fix(Core/Session): Inform the client when we can no longer fly (flyin… (#15363)
- fix(Scripts/Creature): Add 5 second timer for Raliq the Drunk to animate drinking (#15203)
- fix(Scripts/BlackMorass): Fixed rift mobs texts on summon. (#15339)
- fix(Scripts/BlackMorass): Fix Aeonus not spawning, mobs spawning duri… (#15346)

## 2023-03-11
- fix (Core/Spells) Correct Life Tap mana gain and cleanup (#15278)
- fix(Scripts/Spells): Fixed Rogue T10 4P bonus. (#15336)
- fix(Core): Crashfix. (#15338)
- chore(DB): import pending files
- fix(DB/Creature): Starving Helboar aggro radius. (#15321)
- fix(DB/Creature): Set Temporus Level 72 (#15335)
- fix(DB/SAI): Steam Pump Overseer toughen not stacking. (#15319)
- fix(Scripts/Creature): Fel Guard Hound not despawning. (#15300)
- chore(DB): import pending files
- fix(DB/Loot): Fix Aeonus Normal Loot Drops (#15333)
- chore(DB): import pending files
- fix(Scripts/BlackMorass): Fixed mob waves sequence. (#14863)
- chore(DB): import pending files
- fix(DB/Conditions) Correct Class conditions for Satchel of Helpful Goods (65-70) (#15281)
- fix(DB/Quest): Add missing rewards to Ally of the Netherwing (#15314)
- chore(DB): import pending files

## 2023-03-10
- chore(DB/Text): Fix missing apostrophes in Coilfang Slavemaster and Slavehandler texts and add Broadcast IDs (#15280)

## 2023-03-11
- chore(DB): import pending files
- fix(DB/SAI): Daggerfen Assassin missing stealth. (#15311)

## 2023-03-10
- fix(DB/SAI): Rework Naturalist Bite in SAI (#15323)
- refactor(Scripts/BlackMorass): Move the Rift handling to the creature… (#15316)
- Merge branch 'azerothcore:master' into Playerbot

## 2023-03-09
- chore(DB): import pending files
- fix(DB/Creature): Pool Ethereum Jailor (#15289)
- fix(DB/Locale): deDE fixes for request items 3/3 (#15308)
- fix(DB/Locale): deDE fixes for request items 2/3 (#15307)
- fix(DB/Locale): deDE fixes for request items 1/3 (#15306)

## 2023-03-10
- fix(Core/Warden): Fix buffer not being handled during interrupt. (#15258)

## 2023-03-09
- chore(DB): import pending files
- fix(DB/Creature): Remove reputation gains from Seedlings in The Botanica (#15317)

## 2023-03-07
- chore(DB): Rerrunnable SQLs (#15305)
- chore(DB): import pending files
- fix(DB/Movement): Unpopulated rows from previous PRs. (#15292)
- fix(DB/Event): Shadowfang Keep's Valentine decoration. (#15283)
- fix(DB/SAI): Chimaerok casting on aggro. (#15286)
- fix(DB/Creature): Remove creature 138 (#15291)
- fix(DB/Creature): Wild turkey spawns having gossip flags. (#15297)
- fix(DB/Creature): Lord Azrethoc pathing without a melee weapon. (#15260)
- fix(DB/Quest): Against the Legion requirements (#15242)
- fix(DB/Creature): Avatar of Sathal missing text. (#15298)
- fix(DB/Conditions): Sha'ni Proudtusk infinite spawning.  (#15094)
- fix(DB/SAI): Serpentbloom Snakes movement. (#15151)
- refactor(Scripts/Northrend): conversion to std::chrono (#15269)
- fix(Scripts/Blackmorass): Clean unnecessary repetitions (#15299)
- feat(Core/AI): Implement DoForAllSummons() function to summon lists (#15262)

## 2023-03-06
- Merge branch 'azerothcore:master' into Playerbot
- chore(DB): import pending files
- fix(DB/Loot): Correct Gorefiend Truncheon drop rate (#15287)
- chore(Core/Database): Improve error wording (#15270)
- refactor(Scripts/Blackmorass): Rewrite Blackmorass (#15290)

## 2023-03-05
- chore(DB): import pending files
- fix(DB/Creature): Add missing spell to Infected Kodo Beast & disable gravity for Column Ornament (#15087)
- fix(DB/SAI): Add Emberstrife's missing SAI. (#15149)
- fix(DB/SAI): Deathstalker Vincent being killable. (#15282)
- chore(Core/Scripts): Use serverside spell instead of SummonCreature for Nether-wraith Beacon (#15285)
- chore(DB): import pending files
- fix(Core/Spells): Un-hack Spellcloth trigger spell (#15284)
- feat(CI): add cppcheck (#15211)
- fix(Scripts/TheBotanica): Rework Laj (#15279)
- chore(DB): import pending files
- refactor(Scripts/TheBotanica): Modernize Thorngrin the Tender's script (#15277)

## 2023-03-04
- feat(Core/AI): Implement ScheduleHealthCheckEvent() for events that fire … (#15275)
- chore: fix cherry-pick (MariaDB) (#15274)
- chore(DB): import pending files
- fix(DB/SAI): Rift Spawn no emote/flags (#15150)
- feat(Core/Character): Implement profanity_name (#15156)
- fix(Script/PitOfSaron): Pit of Saron - Remove hardcode and duplicated texts in DB (#15160)
- fix(DB/SAI): Scarlet Enchanter & Scarlet Cleric - OOC attack (#15180)
- Scripts/OldHisbradFoothills): Improved Escape from Durnholde Keep event. (#15189)
- fix(Core/Spells): Fixed sending category cooldowns. (#15192)
- fix(Core/Pet): Fixed set hunter pet's speed on load. (#15206)
- fix(DB/Spells): Dirge's Kickin' Chimaerok Chops should not stack with… (#15209)
- fix(Core/Spells): Seal of Command, Seal of Vengeance and Seal of Corr… (#15193)
- fix(Scripts/HallsOfReflection): Halls of Reflection - Fix Alliance side, text broadcasts and hardcodes. (#15227)
- fix(Core/Spells): Goblin Rocket Helmet should not cause auto-attack. (#15207)
- fix(DB/Quest): Zandalari Tribe missing rogue quest and race restrictions. (#15229)
- fix(DB/Spells): Blazing Speed should proc off from absorbed damage. (#15210)
- fix(DB/creature): Remove 1.X-era mobs from Mirror Lake Orchid (#15234)
- fix(DB/Creature): Add NO_PLAYER_DAMAGE_REQ flag to Socrethar (#15243)
- fix(Scripts/WorldNPCs): npcs_special hardcode removal and fixes. (#15240)
- fix(DB/Creature): Correct Flags for Raging Souls (#15245)
- fix(DB/Gossips): Wrong gossip text for Franclorn Forgewright. (#15253)
- fix(DB/Loot): Spirit Shards (#15244)
- fix(DB/Loot): Fix Talon King Ikiss Normal Mode loot table (#15246)
- chore(DB): import pending files
- fix(Scripts/TheBotanica): Rework Commander Sarannis (#15264)
- chore(Core/DB): Display the SQL client version found when throwing th… (#15266)
- refactor(Scripts/Steamvault): Modernize boss/instance scripts (#15224)
- fix: Crash on unit charm (#15256)
- chore(DB): import pending files
- fix(Core/Scripts): Zort's Protective Elixir (#14365)

## 2023-03-03
- fix(Core/Warden): FMT (#15254)
- chore(DB): import pending files
- fix(DB/Conditions): Show correct Zorbin Fandazzle gossip on quests rewarded. (#15216)

## 2023-03-02
- Merge branch 'azerothcore:master' into Playerbot
- chore(DB): import pending files

## 2023-03-01
- fix(DB/SAI): Rewrite Ring of Blood (#15205)
- chore(DB): import pending files
- fix(DB/Gameobject): Rotten Arakkoa Eggs (#15199)
- fix(DB/Quest): The Flesh Lies... (#15195)
- fix(DB/Quest): Dissension Amongst the Ranks... (#15191)
- fix(DB/SAI): Rewrite Deathblow to the Legion and Turning Point in SmartAI (#15182)
- refactor(DB/SAI): Re-organize Teron Gorefiend, I am... script and add time limit properly (#15164)
- fix(DB/Gameobject): Ever-burning Ash (#15055)
- chore(DB): import pending files
- fix(Core/Gameobject): Fix lootable chests related to quests but not having quest loot (#15197)
- fix(Scripts/IcecrownCitadel): fix Lord Marrowgar bone spikes (#15238)
- chore(DB): import pending files
- fix(Scripts/BlackTemple): Combat status (#15222)
- fix(DB/SAI): Fix WP_START parameter mistakes (#15214)
- Merge branch 'Playerbot' of https://github.com/ZhengPeiRu21/azerothcore-wotlk into Playerbot
- Merge branch 'master' into Playerbot

## 2023-02-28
- feat(Core/Channel): add GetChannelDBId() (#15232)
- chore(DB): import pending files
- fix(DB/Creature): Give Enraged Soul triggers the trigger flag (#15223)

## 2023-02-27
- fix(Core/Quests): Fix exploit in icc reputation rings (#15092)
- chore(DB): import pending files
- fix(DB/Quest): Port Escape from Coilskar Cistern to SAI and improve it. (#15137)
- chore(DB): import pending files
- fix(Scripts/Karazhan): Rework Prince Malchezaar (#14877)
- chore(DB): import pending files
- fix(DB/Conditions): Baron Revilgaz - correct gossip for Pirates' Day (#15188)
- fix(DB/ShatteredHalls): Sharpshooter Guard use Viper Sting in Normal mode (#15080)

## 2023-02-26
- fix(DB/Creature) Scout Jyoba should be dead (#14799)
- fix(DB/Loot): Tamed Sporebats have drops and Giant Plains Creeper spider should not be skinnable (#14797)

## 2023-02-27
- fix(DB/SAI): Theradrim Guardian (#13384)
- chore(DB): import pending files

## 2023-02-26
- fix(DB/Conditions): Koren requires at least honored with Violet Eye (#14795)
- chore(Scripts/Ulduar): fix typo/misc when loading instance data (#15215)

## 2023-02-27
- fix(Core/Hook): Call OnUnitDeath for all unit types. (#15213)

## 2023-02-25
- chore(DB): import pending files
- fix(DB/SAI): Defias Gunpowder - add no repeat flag. (#15184)
- chore(DB): import pending files
- fix(DB/Spell): Crusader Strike now stacks from multiple sources (#15181)

## 2023-02-23
- chore(DB): import pending files

## 2023-02-22
- fix(DB/Quest): Fix quest You're Fired! from being unable to be completed by more than one player. (#15141)
- fix(Core/Cooldown): Implement spell cooldown overrides to address cha… (#15143)

## 2023-02-21
- chore(Core/Misc): For Azeroth! (#15155)
- refactor(Core/Autobroadcast): Move autobroadcast to it's own file (#15147)
- Merge branch 'azerothcore:master' into Playerbot
- fix(Core/PacketIO): Reintroduce requeueing packets that are sent during login but need you to be logged in (#15145)

## 2023-02-20
- chore(DB): import pending files
- refactor(Core/Motd): Move motd from conf to db (#15111)

## 2023-02-19
- chore(DB): import pending files
- fix(DB/Conditions): Increase range check for Lakka gossip (#15139)
- feat(Core/Disables): Implement DISABLE_TYPE_LOOT (#15136)
- chore(DB): import pending files
- fix(Scripts/Scholomance): Kirtonos the Herald event now starts correctly again (#15131)
- fix(Core/PacketIO): Remove wrong QueuePacket() (#15124)
- chore(DB): import pending files
- fix(DB/Loot) Droprate of Doctor's Key from Doctor Gutrick (#15106)
- chore(DB): import pending files
- fix(DB/Creature): Port Zangarmarsh rares from Mangos (#15091)
- fix(DB/Quest): The Stone Watcher (#15102)
- fix(Scripts/BlackMorass): Improved Opening the Dark portal encounter. (#14861)
- chore(DB): import pending files

## 2023-02-18
- fix(DB/Creature): Andormu should not sell ammunition (#15090)

## 2023-02-19
- fix(DB/SAI): Increase range of Set Data for Fenrus the Devourer. (#15107)
- fix(Scripts/OldHilsbradFoothills): Corrected spawn position and waypo… (#15099)
- fix(DB/Creatures): Fixed reputation gained on Ethereal Wraith/Arcane … (#15100)
- fix(DB/SAI): Ethereal Crypt Raider's Charge should be casted on rando… (#15101)
- chore(DB): import pending files
- fix(DB/Creature): Rebuild the Coilskar Cistern (#15114)

## 2023-02-18
- feat(Core/Instance): Implement helpers to easily save/retrieve persist… (#15113)

## 2023-02-19
- chore(DB): import pending files

## 2023-02-18
- fix(DB/Creature): Remove custom-placed Shadowmoon Retainers in Eclipse Point (#15112)
- chore(Scripts/SethekkHalls): Move Anzu script to its own file (#15109)
- chore(DB): import pending files
- fix(Scripts/SethekkHalls): Update Talon King Ikiss script (#15098)
- chore(DB): import pending files
- fix(DB/Creature): Stonegazer spawn and waypoints (#15030)
- chore(DB): import pending files
- fix(DB/Creature): Port Vorakem Doomspeaker from Mangos (#15071)
- chore(DB): import pending files
- fix(DB/Quest): Remove Reply-Code Alpha previous quest requirements (10 & 25) (#15086)
- fix(DB/SAI): Wetlands Dragonmaw Bonewarder missing Skeleton Minion (#15082)
- chore(DB): import pending files
- fix(DB/Creature): Add sniffed waypoints to Fenissa the Assassin (#15077)
- fix(DB/Creature): Port Netherstorm rares from Mangos (#15083)
- fix(DB/Creature): Port Terokkar Forest rares from Mangos (#15089)
- chore(DB): import pending files
- fix(DB/SAI): Lakka escort event. (#15097)
- fix(Scripts/BlackMorass): Implemented wipe event. (#14860)

## 2023-02-17
- Merge branch 'azerothcore:master' into Playerbot
- Update to be compatible with latest AC
- chore(DB): import pending files
- fix(DB/Creature): Port Shadowmoon Valley rares from Mangos (#15084)
- Merge branch 'master' into Playerbot
- fix(DB): Fix 2023_02_17_05.sql (#15081)
- chore(DB): import pending files
- fix(DB/QuestTemplate): esES and esMX translation (#15049)
- chore(DB): import pending files
- fix(DB/Creature): Port Collidus the Warp-Watcher from TBCMangos (#15064)
- fix(DB/SAI): Fix Teron Gorefiend, I am... being uncompletable (#15065)
- fix(DB/Creature): Port Speaker Mar'grom from Mangos (#15066)
- fix(DB/Creature): Port Morcrush from Mangos (#15067)
- fix(DB/Creature): Port Eldinarcus spawns from Mangos (#15068)
- fix(DB/Creature): Port Dr. Whitherlimb spawns from Mangos (#15069)
- fix(DB/Creature): Port Mekthorg the Wild from Mangos (#15070)
- chore(DB): import pending files
- fix(DB/Creature): Port Goretooth from Mangos (#15072)
- fix(DB/Creature): Delete extra Chess Square, OUTSIDE BLACK (DND) found in Nagrand (#15073)
- fix(DB/Quest): Kill'em With Sleep Deprivation/Look At the Size of It  (#15074)
- fix(DB/Creature): Port Voidhunter Yar from Mangos (#15076)
- feat(Core/PacketIO): Implement STATUS_LOGGEDIN_OR_RECENTLY_LOGGOUT (#15059)

## 2023-02-16
- fix(DB): Fix 2023_02_16_03.sql (#15063)
- chore(DB): import pending files

## 2023-02-15
- fix(Scripts/GruulsLair): Kiggler the Crazed should cast lightning bol… (#15061)
- fix(DB/Creature): Add another Ghostrider of Karabor group (#15062)

## 2023-02-16
- chore(DB): import pending files

## 2023-02-15
- fix(DB/Loot): Darkwater Crocolisk skinning loot (#15027)
- fix(DB/Creature): Re-Construct The Deathforge spawns (#15037)
- fix(DB/Creature): Improve Shadowmoon Harbingers and Zealots for Teron Gorefiend questline (#15057)
- fix(DB/Creature): Cleric of Karabor (#15060)
- fix(Scripts/GruulsLair): Only players should deal aoe shatter damage (#15056)
- chore(DB): import pending files
- fix(DB/SAI): Fix Escape from Durnholde Barrel exploit (#15047)
- fix(Scripts/Naxxramas): Remove Sapphiron encounter boss requirements (#15048)

## 2023-02-14
- Merge branch 'Playerbot' of https://github.com/ZhengPeiRu21/azerothcore-wotlk into Playerbot
- fix(Scripts/Ulduar): Don't load encounter states as IN_PROGRESS (#15041)

## 2023-02-13
- refactor(Core/AI): Some more refactoring prep for Comat Threat system… (#15026)
- Merge branch 'master' into Playerbot
- fix(Scripts/MoltenCore): revert ragnaros submerge event to 180s (#15001)
- Revert "fix(Core/Unit): Fix creatures not being able to cast spells d… (#14987)

## 2023-02-12
- refactor(Scripts/BloodFurnace): Modernize Broggok script (#14982)

## 2023-02-13
- chore(DB): import pending files

## 2023-02-12
- fix(Scripts/Karazhan): Rework Attumen & Midnight (#14756)
- fix(Scripts/HellfireRamparts): Omor the Unscarred shouldn't move (#14751)
- fix(Scripts/Spells): Prevent Omen of Clarity from procing from crafti… (#14910)

## 2023-02-13
- fix(DB/Quest): Report to Goldshire RP. (#14813)

## 2023-02-12
- fix(Scripts/Ulduar): Fix Stormcaller Brundir flying under texture (#14940)
- refactor(Scripts/TempleOfAhnQiraj): Clean up unused variables (#14979)
- feat(Core/SAI): Implement SMART_TARGET_INSTANCE_STORAGE (#14981)
- chore(DB): import pending files
- fix(DB/Creature): Rakoria RP event (#14796)
- fix(CORE/Spell): Book of the Dead unequip fix (#14839)

## 2023-02-13
- feat(Core/Warden): Allow sending of custom lua payloads through Warden. (#14723)

## 2023-02-12
- chore(DB): import pending files
- fix(Scripts/Arcatraz): Fix Zereketh Seed of Corruption damage and mod… (#14980)
- refactor(Scripts/Arcatraz): Modernize Dalliah the Doomsayer script (#14978)
- chore(DB): import pending files
- chore(DB): Add default values to columns in creature_formations table (#14936)
- fix(DB/SAI): Fixed Private Hendel SAI script. (#14866)
- fix(DB/Creature): Implement & Script Wildhammer Gryphon Rider (#14924)
- fix(DB/ShatteredHalls): Spawned Hellfire Training Dummies in Shattere… (#14964)
- fix(DB/SAI): Fixed "Trapping the Light Fantastic" quest. (#14963)
- refactor(Core/InstanceScript): refactored load and save methods (#14977)
- chore(DB): import pending files
- fix(DB/SAI): Shattered Hand Assassin. (#14965)
- fix(DB/SAI): Shattered Hand Sharpshooter uses Viper Sting … (#14976)
- chore(DB): import pending files
- fix(Scripts/GruulsLair): Fixed Ground Slam. (#14780)
- chore(DB): import pending files
- fix(DB/SAI): Add OOC lines to Tempest-Forge Peacekeeper (#14975)
- chore(Core/Misc): Change all TODO to doxygen comment (#14966)
- refactor(Core/GameObject): Split GameObject for Dynamic Crea/Go (#14889)
- chore(DB): import pending files
- fix(DB/SAI): "Someone Else's Hard Work Pays Off" - fixed ending scene. (#14962)
- fix(Core/SAI): Set minions in combat with their master's victim (#14959)
- fix(Scripts/BlackMorass): Adds should walk towards Medivh. (#14945)
- chore(DB): import pending files
- feat(Core/DBC): Implement NamesProfanity and NamesReserved DBC (#14956)
- chore(DB): import pending files
- fix(DB/SAI): Script Sunseeker Netherbinder (#14958)
- fix(Core/Unit): Fix creatures not being able to cast spells during Ju… (#14957)

## 2023-02-11
- refactor(Scripts/TheBotanica): Modernize High Botanist Freywinn script (#14954)
- chore(DB/SQL): Correct file to comply with standards (#14953)
- refactor(Scripts/TheBotanica): Modernize the Warp Splinter script (#14951)
- feat(Core/AI): Update the BossAI scheduler in the parent class (#14952)
- chore(DB): import pending files
- feat(Core/Pet): DK Petname generation locale (#14059)
- chore(DB): import pending files
- fix(DB/Creature): Spawn Ancient Draenei Spirit (#14925)
- fix(Scripts/BlackMorass): Fixed portal positions. (#14946)
- fix(Scripts/BlackMorass): Fixed amount of Medivh's Integrity shield t… (#14948)
- feat(Core/AI): Implement delay option to the Talk() function (#14950)
- chore(DB): import pending files
- fix(DB/SAI): Fix Phantom Guardsmen timers and remove rep from their s… (#14943)
- refactor(Scripts/Karazhan): Move Barnes/Medivh/Arcanagos texts to the DB (#14949)
- fix(DB/TheBotanica): Re-Construct The Botanica (#14932)
- fix(Core/AI): Fixed mobs attacking in defensive state. (#14947)
- chore(DB): import pending files
- fix(DB/Locale): deDE fix offer reward texts #01 (#14614)
- fix(DB/SAI) Sundered Rumblers wrong use of Summon Sundered Shard (#14831)
- fix(Scripts/Karazhan): Fixed Wizard of Oz encounter. (#14942)
- fix(Scripts/AzjolNerub): Fixed Hadronox being killed by mobs. (#14123)
- fix(Core/Vehicles): Crashfix. (#14941)
- chore(DB): import pending files
- fix(Core/Config): Added new config to make pet's health be modified b… (#14051)

## 2023-02-10
- fix(DB/SAI) Warp Aberration should keep up Arcane Shield out of combat (#14832)

## 2023-02-11
- fix(DB): Separate INSERTs from base sql into smaller sections part 2 (#14938)
- chore(DB): import pending files

## 2023-02-10
- fix(DB/Creature): Add missing Thrash aura to Aeonus in Black Morass (#14884)

## 2023-02-11
- chore(DB): import pending files
- fix(Scripts/Underbog): Underbog Shambler's Allergies should periodica… (#14563)

## 2023-02-10
- Merge branch 'azerothcore:master' into Playerbot
- chore(DB): import pending files
- fix(DB/SAI): Script Wyrmcaller Vile (#14922)
- chore(DB): import pending files
- fix(DB/Creature): Remove bleed immunity from Escape from Durnholde bosses. (#14937)
- fix(Scripts/Netherstorm): Crash in Netherstorm (#14934)
- chore(DB): import pending files
- fix(DB/Creature): Spawn Warsong Hold Mount (#14930)
- fix(DB/Creature): Spawn Floating Skull (#14931)
- chore(DB): import pending files
- fix(DB/SAI): Script Magister Savarin (#14921)
- chore(DB): import pending files
- fix(DB/Creature): Knight-Lieutenant T'Maire Sydes (#14928)
- fix(DB/SAI): Misc SAI updates (#14927)
- fix(DB/Creature): Script Sawemba (#14920)

## 2023-02-09
- Merge branch 'Playerbot' of https://github.com/ZhengPeiRu21/azerothcore-wotlk into Playerbot
- Merge branch 'master' into Playerbot
- chore(DB): import pending files

## 2023-02-08
- improve(DB/npc_vendor): Address vendor exploit (#14909)
- fix(DB): Separate INSERTs from base sql into smaller sections (#14881)
- fix(Scripts/BlackwingLair): Fix Flamegor frenzy timer (#14908)
- fix: Crash on Flamegor (#14906)
- fix(Scripts/ShadowfangKeep): Fix Apothecary Trio events not reseting … (#14898)

## 2023-02-07
- chore(DB): import pending files
- fix(DB/Creature): Use sniffed values for Black Morass creatures and spawn positions (#14886)
- feat(Core/Scripting): Implement OnBeforeSetBossState (#14891)

## 2023-02-06
- chore(DB): import pending files

## 2023-02-05
- fix(DB/Creature): Fix some unit flags for Black Morass (#14878)
- feat(Core/Unit): Combat pulse (#14792)
- chore(DB): import pending files
- refactor(Core/Scripts): Simplify speeches for Special Surprise quests. (#14630)

## 2023-02-06
- fix(Script/Nexus/EOE/Oculus) The Scion of Eternity(EOE) target wrong and player can not ride the dragon in Oculus (#14830)

## 2023-02-05
- refactor(Scripts): Update vanilla scripts to std::chrono (#14876)
- chore(DB): import pending files
- fix(DB/SAI): Laughing Skull Legionnaire casts Sweeping Strikes. (#14858)
- refactor(Scripts/GruulsLair): Modernize High King Maulgar script (#14870)
- refactor(Core/ObjectMgr): Load Creatures.CustomIDs into stores (#14835)
- chore(Core/Object): Rename GetGOData() to GetGameObjectData() (#14875)
- fix(Core/Socket): `CMSG_WARDEN_DATA` should not reset idle connections. (#14865)

## 2023-02-04
- refactor(Core/Instance): make SetBossState void (#13412)
- chore(DB): import pending files
- fix(Scripts/HellfireRamparts): Removed invalid spells from Omor the U… (#14538)
- feat(Core/Scripting): Added new hook: OnInstanceIdRemoved. (#14670)
- fix(Scripts/GruulsLair): Improvements to High King Maulgar (#14732)
- fix(DB/Event): Elemental Invasions (#14803)
- chore(DB): import pending files
- fix(DB/Creature): Fix Elder Runetotem & Elder Darkhorn gossip (#14777)
- chore(DB): import pending files
- fix(DB/SAI): Fix Spectral Chargers not casting fear (#14867)
- refactor(Scripts/Karazhan): Use std::chrono for Maiden, Servant Quart… (#14864)
- fix(Core/Creature): Fix bosses with hard reset flag not respawning an… (#14862)
- fix(Scripts/TempleOfAhnQiraj): Fix C'thun not using abilities after e… (#14859)

## 2023-02-01
- fix(DB): MariaDB Imports (#14841)
- fix(Core/Calendar): Correct calculation of reset time (#14834)
- refactor(Scripts/Karazhan): Maiden of Virtue script update (#14836)

## 2023-01-31
- feat(DB): release ACDB 8.0.0 (#14833)
- chore(DB): import pending files
- fix(DB/Creature): Update sniffed walk/run values (#14495)
- chore(DB): import pending files
- fix(DB/Creature) Heartswood drop (#14810)
- chore(DB): import pending files
- fix(Scripts/Spells): Nether Portal - Perseverence should not increase… (#13951)
- fix(Scripts/BloodFurnace): The Maker should cast Domination instead o… (#13892)
- fix(DB/Quest): Rework support for 'Someone Else's Hard Work Pays Off' (#14258)
- refactor(Core/AuctionHouse): Remove Hungarian notation (#14097)
- refactor(Core/DBCEnums): Reword NYI comment. (#14752)
- fix(DB/Creature): Adding missing BroadcastTextId in Pit of Saron (#14793)
- feat(Core/SmartAI): Implement SMART_EVENT_SUMMONED_UNIT and SMART_EVE… (#14811)
- fix(DB/SAI): Nether Ray (18880) (#14815)
- fix(DB/SAI): Port Coilskar Siren AI from Cmangos (#14826)
- fix(DB/Gossip): Add missing Undercity Guardian gossip options (#14827)
- fix(Core/Spells): Cleasing, Healing Stream Mana Tide totems should ig… (#14679)
- fix(Core/SmartAI) Fix null reference when summoning (#14812)
- feat(Core/ObjectAccessor): Helper to access creature/object by DB GUID (#14802)

## 2023-01-30
- chore(DB): import pending files
- fix(DB/Quest): Change QuestType in quest 13070 (#14798)

## 2023-01-29
- chore(DB): import pending files
- fix(Core/Spells): Remove all hardcoded restrictions for pick pocket sp… (#14788)
- chore(Valgrind): Move Valgrind from data folder to apps folder (#14778)
- chore(DB): import pending files
- fix(DB/Reputation): Fix reputation awarded for Murkblood Healers (#14783)
- feat(Core/GameObject): Expand IsSummonedBy() to GameObjects (#14789)
- chore(DB): import pending files
- fix(DB/Reputation): Remove reputation from Fiendish Imp (#14787)

## 2023-01-28
- feat(Core/Creature): Actually despawn creatures on evade with Despawn… (#14786)
- feat(Core/Unit): Add KillSelf overload (#14785)
- fix(Scripts/GruulsLair): Fixed assigning loot mode to High King Maulgar. (#14781)
- feat(Core/Deps): add macOS ARM support (#14761)
- chore(DB): import pending files
- fix(Scripts/MagtheridonsLair): Fixed Blast Nova timers. (#14776)
- refactor(Core/MySQL): MySQL PreparedStatement Affected Row Count (#12002)
- fix(DB/gameobject): Correct Scarab Gong Type ID (#12879)
- fix(DB/reference_loot_template): Adjusted raptor drops (#13204)
- fix(DB/Script): Violet Hold Door not opening (#13958)
- fix(Core/Players): Fixed sending power regen update to nearby players. (#14043)
- fix(Scripts/Command): Command `gm visible on` should not mark you wit… (#14057)
- fix(DB/item_template_locale): Add Chinese translation for 'Wand of Allistarj' (#14079)
- refactor(Core/World): Remove Hungarian notation (#14095)
- fix(DB/quest_template_locale): Add ruRU ObjectiveText1/2 to The Tower of Althalaxx. (#14129)
- fix(DB/npc_text_locale): Add esES/esMX text to Talin Keeneye. (#14131)
- fix(Core/Auth): Cleanup PrepareStatements (#14220)
- fix(Core/Creatures): Critters should start fleeing upon entering comb… (#14253)
- fix(Core/Maps): Increased visibility distance inside Ahn'Qiraj Temple… (#14271)
- fix(DB/Item): Missing Dungeons\quests esES
- fix(Scripts/HP PvP): Hellfire PvP Objective Flag and Progress bar not in sync (#14304)
- fix(Core/PlayerQuest): Get base skill value for quest prereqs. (#14393)
- fix(Core/GameObject): Make fishing bobber finish a channeled spell rather than interrupt in all cases. (#14422)
- fix(CMake/Module): module related cmake error (#14569)
- fix(Core/Spells): Fixed Master of Elements not refunding mana. (#14665)
- fix(DB/Spells): Improved Stormstrike should proc only once per cast. (#14666)
- fix(Core): Crashfix. (#14667)
- fix(Core/Battlegrounds): When team loses the base in EotS, dead playe… (#14668)
- fix(Core): Crashfix. (#14680)
- fix(Core/Combat): Pets should put their owners in combat only on init… (#14682)
- fix(Core/Spells): Update crit chance on shapeshifting to/from feral f… (#14683)
- fix(DB/Creature): Add some immunities to C'thun adds (#14750)
- fix(DB) Zorbo the Advisor gives no rep (#14767)

## 2023-01-26
- fix(Core/Unit): Petrified Lichen Guard effect (#14436)
- feat(Core/AI): Move TaskScheduler to BossAI class (#14757)
- chore(Core/ObjectMgr): Adjust a few comments/logs to reflect recent changes with stat handling. (#14759)
- fix(Core/Creatures): Spells casted by player should tap the creature … (#14725)

## 2023-01-25
- chore(DB): import pending files
- fix(DB/SAI): Caretaker Smither. (#14445)
- chore(DB): import pending files
- fix(DB/Creature): Rebuild Old Hillsbrad critters (#14656)
- fix(Docker): config loading for ac-dev-server container (#14755)
- chore(DB): import pending files
- feat(Core/ObjectMgr): Add handling specific to heroic player level stats (DKs). (#14378)
- chore(DB): import pending files
- fix(DB/Creature): Rework Old Tarren Mill in Old Hillsbrad Foothills (#14659)

## 2023-01-24
- fix(docker): missing config file in dev image (#14753)
- chore(DB): import pending files
- fix(DB/Locale): deDE fix request items texts #03 (#14619)
- fix(DB/Locale): deDE fix request items texts #02 (#14615)

## 2023-01-23
- fix(DB/gameobject): Improve Draenei Vessel (#14339)
- chore(DB): import pending files
- fix(DB/Locale): Chinese (#14740)
- Fix configs in docker builds (#14747)
- fix (core): macos12 depreciation workflow error / security CWE-120 (#14746)

## 2023-01-22
- feat(Core/Mail): call CanSendMail() even if no items are sent (#14435)
- chore(DB): import pending files

## 2023-01-21
- fix(DB/Creature): Minor fixes for Sethekk Halls (#14741)
- chore(DB): import pending files
- fix(DB/Creature): Remove extra spawns of Sally Whitemane and Renault Mograine in Old Southshore (#14700)
- fix(DB/Creature): Looking to the Leadership quest mob respawn times (#14710)
- fix(DB/Gameobject): Fixed overlapping Milk Barrel / Food Crates in St… (#14730)
- fix(DB/Creature): Bloodaxe Veteran equipment (#14733)
- refactor(Core/Conf): Removal of unnecessary .dist file loading (#14707)

## 2023-01-19
- chore(DB): import pending files
- fix(Core/Formations): Implemented new creature formation flag: GROUP_… (#14537)
- Merge branch 'azerothcore:master' into Playerbot
- chore: Update issue template (#14703)

## 2023-01-16
- chore(DB): import pending files
- fix(DB/Gameobject): Add Winter Veil objects to Old Hillsbrad (#14658)
- fix(DB/Creature): Correct road and tower patrols in Old Hillsbrad (#14657)
- fix(DB/Creature): Fix IDs and path Hillsbrad Peasant farmers in Old Hillsbrad Foothills (#14655)
- chore(DB): import pending files
- fix(DB/Locales): Wintersbite (#14278)
- fix(DB/Creature): Ashenvale Rare spawn times and locations  (#13792)
- chore(DB): import pending files
- fix(DB/SAI): Underbog Shambler's Fungal Regrowth should be casted on … (#14560)
- fix(DB/Locale): deDE locales fixed for quests 6381 and 6391 (#14607)

## 2023-01-15
- fix(DB/creature): Correct Mok'rash respawn timer (#14647)

## 2023-01-16
- fix(DB/SAI): Shadowmoon Summoner should not interrupt its spells. (#14567)
- DB/SAI: Bog Giant and Underbog Lord uses Growth only in Heroic mode. (#14542)
- fix(DB/SAI): Underbog Shambler's Itchy Spores should be casted on ran… (#14561)

## 2023-01-15
- fix(DB/SAI): Grimclaw (#14629)

## 2023-01-16
- fix(DB/SAI): Bleeding Hollow Archers should only use ranged abilities. (#14669)
- fix(DB/SAI): Sunfury Geologist. (#14681)

## 2023-01-15
- fix(DB/SethekkHalls): Re-construct Sethekk Halls gameobjects and creatures (#14265)
- feat(Core/Database): move MySQL handle and HandleMySQLErrno to protected (#14673)
- feat: getter for the used instance IDs (#14677)
- fix(Core/Characters): Correctly update char count on realm selection (#14685)
- chore(DB): import pending files
- fix(DB/Locale): Missing Offer_Request reward Locale esES/esMX (#14045)
- fix(core/packets): reduce sending unnecessary packets (#13198)
- fix(Cmake/Build): correct build single app (#12202)
- chore(Core/Docs): Remvoe old comment (#14684)

## 2023-01-14
- fix(Core): Crashfix. (#14660)
- chore(DB): import pending files
- fix(DB/Loot): Strong Junkbox (#14611)
- chore(DB): import pending files

## 2023-01-13
- fix(DB): Implement more Old Southshore events and other misc fixes (#14502)
- chore(DB): import pending files
- fix(DB/skinning_loot_template): new skinning entries for different mobs in TBC (#14506)

## 2023-01-12
- Merge branch 'azerothcore:master' into Playerbot

## 2023-01-11
- fix(Core): Crashfix. (#14536)

## 2023-01-07
- chore(DB): import pending files
- fix(Script/Item): Elixir of Shadows for pets (#14514)
- fix(Core/Creature): Check model increase only for Exotic creatures (#14526)
- chore(DB): import pending files
- fix(DB/Creature): Cho'war the Pillager (#13896)
- fix(DB/Texts): Added texts to Halazzi. (#14124)
- fix(Core/Spells): Fixed applying some proc ex flags to melee attacks. (#14254)
- fix(Scripts/Underbog): Fixed Fungal Decay spells. (#14543)
- fix(Scripts/The Underbog): Rewritten The Black Stalker's Levitate mec… (#14541)
- fix(Core/Packets): Fix a crash in MSG_RANDOM_ROLL. (#14545)

## 2023-01-08
- fix(Core/Gossip): quest_greeting_locale doesn't work #10913 (#14532)

## 2023-01-07
- chore(DB): import pending files
- fix(Scripts/Hellfire Ramparts): Nazan should walk on the surface afte… (#14539)
- chore(DB): import pending files
- fix(DB/Creature): Infested Root-Walker (#14515)
- fix(Core/Spell): Roll 'dem Bones (#14522)
- fix(Core/Loot): Fix too many quest items visible by master looter (#14510)

## 2023-01-06
- fix(Apps): Update client data version (#14527)
- chore(DB): import pending files
- fix(DB/SAI): Add a few item restoration gossips/conditions/smart_scripts for Betina Bigglezink. (#14476)
- fix(DB/creature_loot): fix two quest rates in EK (#14520)
- fix(Core/Pets): Correct Pet size for bigger pets (#14511)

## 2023-01-05
- Revert "fix(Core/Spells): Ignite and Revitalize should not prelong co… (#14513)

## 2023-01-06
- fix(DB/Quest): Make query rerunnable (#14512)

## 2023-01-05
- chore(DB): import pending files
- fix(DB/quest_greeting_locale): Add esES/esMX quest greeting to Apothecary Helbrim. (#14482)

## 2023-01-06
- fix(Core/Spells): Aura with `SPELL_AURA_MOD_FEAR` effect are always c… (#14450)
- fix(Core/Spells): Regen auras should not be removed by Rapid Recupera… (#14269)
- fix(Scripts/OnyxiaLair): All Onyxia's adds should attack player on su… (#14108)
- fix(Core/Items): Players should dismount upon using Brazier of Dancin… (#14055)
- fix(Core/Creatures): Implemented `SUMMON_PROP_FLAG_ONLY_VISIBLE_TO_SU… (#14054)
- fix(Core/Spells): Every spell casted by player should tap the creature. (#14037)
- fix(Scripts/Karazhan): Barnes should respawn on wipe. (#13953)
- fix(Core/Spells): Ignite and Revitalize should not prelong combat. (#13812)

## 2023-01-05
- chore(DB): import pending files
- fix(DB/SAI): Implement Captain Sanders and Edward Hanes RP event in Old Hillsbrad Foothills (#14396)
- fix(DB/SAI): Implement Kel'Thuzad and Helcular RP event in Old Hillsbrad Foothills (#14385)
- feat(Core/Config): Allow disable points of interest for quests (#14501)

## 2023-01-04
- Merge branch 'azerothcore:master' into Playerbot
- chore(DB): import pending files
- fix(DB/SmartAI): Implement Hal McAllister and Nat Pagle event in Old Southshore (#14493)
- fix(DB/gameobject): Rebuild gameobjects for the remaining Auchindoun instances (#14491)
- chore(DB): import pending files
- revert "fix(Core/Formations): Implemented new creature formation flag: GROUP_AI_FLAG_ACQUIRE_NEW_TARGET_ON_EVADE." (#14494)

## 2023-01-03
- chore(DB): import pending files
- fix (db): EOTS BG StartMaxDist (#14489)
- chore(DB): import pending files
- fix(DB/gameobject): Duskwood gameobject pool (#14200)
- chore(DB): import pending files
- fix(DB/SAI): Fixed Fallen Hero's Spirits not giving kill credit. (#14443)
- chore(DB): import pending files

## 2023-01-02
- fix(DB/creature_template): Remove Bleed Immunity from Elementals (#13734)

## 2023-01-03
- fix(Core/Loot) Fix master looter invisible quest items (#14103)

## 2023-01-02
- chore(DB): import pending files

## 2023-01-03
- fix(DB/Creature): Fel Cannon should be stationary and shoot (#14460)

## 2023-01-02
- fix(Core/Scripts): Rewrite Hungarfen (#14426)
- fix(Core/Auras): SPELL_AURA_MOD_SCALE should scale additively instead… (#14425)
- Revert "fix(Core/Config): Set default corpse decay for normal creatures to 5 …" (#14474)
- fix(MMAP/core/PathGenerator): Try to fix more water creatures (#13705)
- chore(DB): import pending files
- fix(Core/Gameobjects): Fixed LoS for traps summoned by creatures. (#13873)
- refactor(Core/player_levelstats): Split player_levelstats into class and race specific tables. (#14383)
- fix(Scripts/Spells): Omen of Clarity should not proc from Revitalize. (#13867)
- fix(Core/Spells): Spellmods should not drop charges if not consumed b… (#13498)
- chore(DB): import pending files
- fix(DB/Creature): Force the correct modelid on spawn of Enchanted Tiki Warriors (#12318)
- chore(DB): import pending files
- fix(DB/SAI): Nexus Terror's Death Coil should be casted only on Hero… (#14449)
- fix(DB/npc_vendor): Improve a few TBC Vendor Recipe Rates (#14472)
- chore(DB): import pending files
- fix(DB/smart_scripts): Fix Crypt Guard's Acid Spit (#14132)

## 2023-01-01
- chore(DB): import pending files
- fix(DB/SAI): Fen Ray should cast Psychic Horror on random target. (#14464)
- chore(DB): import pending files
- fix(DB/Loot): Auchenai Death-Speaker/Doomsayer money drop (#14461)
- fix(DB/loot): Nagrand gold drop fixes (#14462)
- fix(DB/SAI): Murkblood Spearman's Viper Sting should be casted only o… (#14465)
- chore(DB): import pending files
- fix(DB/SAI): Swamplord Musel'ek prefers ranged attacks than melee. (#14463)
- chore(DB): import pending files
- fix(DB/Loot): Prospecting Adamantite adjustment (#14456)
- chore(Docs): New Year (#14459)
- chore(DB): import pending files
- fix(DB/SAI): Swamplord Musel'ek should yell when Claw is enraged. (#14454)
- fix(DB/SAI): Swamplord Musel'ek's Aimed Shot should not be interrupte… (#14455)
- fix(Core/Spells): Fixed Hunter's Mark not being casted by Swamplord M… (#14457)

## 2022-12-31
- refactor(Core/Object): getLevel() -> GetLevel() (#14122)
- chore(DB): import pending files
- fix(DB/creature): Port some Boulderfist Ogre spawns from Mangos (#14414)
- fix(DB/creature): Auchenai Monk speed (#14416)
- fix(DB/creature): Hellfire Channelers shouldn't be pulled by distance (#14417)

## 2022-12-30
- chore(DB): import pending files
- fix(DB/loot): Deathknell unique drops rate improvements (#14088)
- chore(DB): import pending files
- fix(DB/Loot): Fixed Koralon the Flame Watcher loot for alliance players. (#14109)
- chore(DB): import pending files
- fix(DB/HallsOfStone): Triggers in Tribunal of Ages (#14130)
- fix(DB/Gossip): Remove empty data from Archmage Leryda gossip (#14327)
- fix(DB/Loot): Naga claws should drop 100% (#14405)
- fix(DB/creature): Remove Bonelashers inside of a wall. (#14379)
- feat(Core/scripts): expose Halaa slider value and owner setter
- chore(DB): import pending files
- fix(DB/Creature): Remove Neophyte Guardian spawn (#14409)
- chore(DB): import pending files
- fix(DB/Loot): Improve Kil'sorrow gold drops (#14418)

## 2022-12-29
- Merge branch 'azerothcore:master' into Playerbot
- chore(DB): import pending files
- fix(DB/Loot): Fen Strider Tentacle should only drop when on quest (#14404)
- fix(DB/Creature): Remove Tamed ravager spawns (#14408)
- chore(DB): import pending files
- fix(DB/Quest): 'He Will Walk The Earth' Should have quest rewards (#14406)
- fix(DB/SmartScript): Fey Drake should blink behind target (#14410)
- fix(DB/SmartScript): Boulderfirst Mage / Warrior smartscript (#14413)
- chore(DB): import pending files
- fix(DB): Correct missing file extension (#14412)
- feat(Core/Group): add GetGroupType() (#14411)
- feat(Core): move achievement manager and criteria progress getters to public (#14387)
- chore(DB): import pending files
- fix(DB/Loot): Make Qiraji Scarab not skinnable (#14376)
- fix(DB/Loot): Remove `Primed Mold Key` from `Coilfang Emissary` (#14370)
- fix(DB/smart_scripts): Fix Tapoke "Slim" Jahn's event_flags (#14362)
- fix(DB/Creature): Change bad id1 from Veil Skith (#14337)
- fix(DB/SAI): Corporal Ironridge (#14240)
- fix(DB/Gossip): Add gossip text, sub-menu, and correct condition for Raene Wolfrunner. (#14106)
- fix(Core/Config): Set default corpse decay for normal creatures to 5 … (#14039)
- fix(DB/Creature): Remove Mathrengyl Bearwalker's Left Right Claw. (#13846)

## 2022-12-28
- feat(Core/Player): delete character cache in Player::DeleteFromDB() (#14388)
- Add (core): SendTeleportPacket helper (#14389)
- fix(Core/Handlers): Crash (#14390)
- chore(DB): import pending files
- fix(DB/quest): quest 456 translation (#13674)
- chore(DB): import pending files

## 2022-12-27
- fix(DB/Creature): Properly handle Sunspring Villager death state (#14356)

## 2022-12-28
- chore(DB): import pending files

## 2022-12-27
- fix(DB/GameObject): Add rope lines in Scryer's Tier library (#14248)

## 2022-12-28
- fix(Core/Loot): Disenchanted, milled or prospected items should be se… (#14273)

## 2022-12-27
- fix(Core/Totem): Implement casting delay for the Fire Totem used by c… (#14276)
- fix(Core/AI): Fix target selectors logic when accounting for tanks (#14368)
- Merge branch 'azerothcore:master' into Playerbot
- chore(DB): import pending files
- fix(Core/Formations): Implemented new creature formation flag: GROUP_AI_FLAG_ACQUIRE_NEW_TARGET_ON_EVADE. (#13509)
- chore(DB): import pending files
- fix(DB/Scripts): Npc Tonk Control Console (#13342)
- fix(Scripts/GO): Druid‘s fly quest (#14085)

## 2022-12-26
- fix(CI/mac): python issue workaround (#14369)
- chore(DB): import pending files
- fix(DB/Loot): Blackwind Sabercat (#14328)
- fix(Scripts/Zangarmarsh): Naturalist Bite shouldn't desummon after casting Mark of Bite (#14354)

## 2022-12-25
- chore(DB): import pending files
- fix(DB/Creature): Port some Outland Elementals from Mangos (#14267)
- fix(DB/Creature): Rebuild Bonechewer Ruins (#14335)
- fix(DB/Loot): Correct Primal Nether drop chance from normal dungeons (#14329)
- fix(Core/Transports): Added Arrival bell sound for boats. (#14272)
- chore(DB): import pending files
- fix(DB/SAI): Aggonis In Combat spells (#14336)
- fix(Core/LFG): Fixed showing dungeon access requirements only for lea… (#14116)
- fix(DB/Creatures): Fixed Frozen Spheres not floating in the air in he… (#14251)
- fix(Core/Pets): Taunt should work on pets. (#14255)
- chore(DB): import pending files
- fix(DB/Creature): Attach auras to Winter Revelers to correct models. (#14366)

## 2022-12-24
- feat(Core/Scripting): Pass SpellInfo through the ModifyPeriodicDamage… (#14360)
- chore(DB): import pending files
- feat(Scripts/Commands): Output SpellCastResult if the spell fails to … (#14359)

## 2022-12-22
- chore(DB): import pending files
- fix(DB/Gameobject): Remove Chests from TBC dungeons (#14320)
- fix(Core/Spells): Cursed Cauldron gobs despawn after 5 seconds. (#14252)
- fix(DB/Creature): Add trigger flag to Credit Marker: Water (#14287)
- fix(DB/Creature): Fix Dreadfang Widow bad Z coord (#14286)
- fix(DB/Gameobject): Delete bad Nightmare Vine node (#14285)
- fix(Core/Misc): Consider `/dance` as an emote state. (#14275)
- chore(DB): import pending files
- fix(DB/Reputation): Fiendish Hound (#14245)
- fix(DB/Loot): Jaggal Clam (#14243)
- fix(DB/SAI): Correct Vagrant 19283 target_type (#14242)
- fix(DB/SAI): Morph Honor Hold Scout Archery Target into correct modelid on respawn (#14239)
- fix(DB/Loot): Hellfire quest loot improvements (#14236)
- fix(DB/Gameobject): Add more Ravenous Flayer Eggs (#14238)
- chore(DB): import pending files
- fix(DB/Vendor): Improve Xerintha Ravenoak vendor timers (#14319)
- fix(DB/Vendor): Reduce Super Mana Pot and Frost Power Potion Recipe timer (#14321)
- chore(DB): import pending files
- fix(DB/CreatureOnKillReputation): Lykul Stinger rep should stop at friendly (#14283)
- fix(DB/smartscript): Hellfire Watcher should cast Renew and Heal on t… (#14281)
- fix(DB/FactionChangeQuests): Return to Thrallmar and Go To The Front … (#14303)

## 2022-12-21
- chore(DB): import pending files
- fix(DB/QuestTemplateAddon): Membership Benefits should not have quest… (#14305)

## 2022-12-20
- chore(DB): import pending files
- fix(DB/creature): Port rare spawns from Mangos (#14288)
- chore(DB): import pending files
- fix(DB/loot): Arvuu's Orb quest start item drop rate fix (#14235)
- chore(DB): import pending files
- fix(DB/gameobject): Correct state for 5 herbalism nodes (#14221)
- fix(DB/loot): Improve Mulgore zone unique items (#14195)
- chore(DB): import pending files
- fix(DB/creature/gameobject): Add more objects and creatures for 'Cipher of Damnation' questline (#14082)
- chore(DB): import pending files
- fix(DB/SAI): Workaround bad model for Void Spawner L (#14289)
- chore(DB): import pending files
- fix(DB/Creature): Corrected Spawn Time Terrorclaw (#14302)
- chore(DB): import pending files
- fix(DB/loot): Improve Mazthoril recipe drop rates (#14010)
- fix(Core): Correct Quest Details Display at Max Level (#13046)

## 2022-12-18
- chore(DB): import pending files
- fix(DB/Loot): Remove Fel Spirit (22454) loot (#14268)

## 2022-12-17
- chore(Core/SAI): Align SAI headers with TrinityCore (#14261)

## 2022-12-16
- chore(DB): import pending files
- fix(DB/Creature): Add AQ40 missing onkill reputation gains (#14246)
- chore(DB): import pending files

## 2022-12-15
- fix(DB/Quest): Add some ruRU localization to multiple quests. (#14202)

## 2022-12-16
- chore(DB): import pending files

## 2022-12-15
- fix(DB/Loot): Burning Legion Gate Key rate fix (Doorway to the Abyss) (#14232)

## 2022-12-16
- chore(DB): import pending files
- fix(DB/SAI): Worms should not despawn instantly (#14233)
- chore(DB): import pending files

## 2022-12-15
- fix(DB/Loot): Separate Normal and Heroic loot from early TBC dungeons (#14234)

## 2022-12-14
- chore(DB): import pending files
- fix(DB/Creature): Incorrect jewelcrafting trainer (#14213)

## 2022-12-13
- chore(DB): import pending files
- fix(DB/Loot): Improve Tirisfal Glade unique drops (#14197)
- chore(DB): import pending files
- fix(DB/GameObject): Add Mailbox in Nighthaven. (#14126)
- update (core): Continue Taxi Flight support helper (#14211)

## 2022-12-12
- Merge branch 'azerothcore:master' into Playerbot
- chore(DB): import pending files
- fix(Scripts/Spells): Fixed level requirements for Blade Ward and Bloo… (#14107)
- fix(Core/Spells): Fixed auras with `AURA_STATE_HEALTH_ABOVE_75_PERCEN… (#14110)
- chore(DB): import pending files
- fix(DB): Add some scourge invasion gobjects/creatures. (#14150)

## 2022-12-11
- fix(Core/Unit): properly reset displayIds when having a shapeshift au… (#14134)
- chore(DB): import pending files
- fix(Core/SmartScripts): Added new parameter `onlyInCombat` to `SMART_… (#13947)
- fix(Core/Scripts): Bloodscale Enchantress/Rajis Fyashe freezing circle (#13963)
- chore(DB): import pending files
- fix(DB/SAI): Quest - Cleansing the Waters missing RP (#13703)
- fix(Core/Auras): Implement Roc form (#13959)
- chore(DB): import pending files
- fix(Scripts/Instances): Fixed text during "Opening the Dark Portal" i… (#13872)
- fix(Core/Dungeons): Fixed displaying custom requirement texts from `d… (#14125)
- fix(build): build-db (#14121)

## 2022-12-10
- feat(Core): EnableLowLevelRegenBoost config option (#13035)

## 2022-12-11
- chore(DB): import pending files
- fix(Scripts/Underbog): Moved Gha'zan script to C++ file. (#13887)
- fix(DB/Creatures): Added waypoint script to Black Stalker. (#13888)
- fix(DB/QuestGreeting): Krelding Ungor missing locale (#13935)
- fix(DB/creature):  pr13832 delete the wrong table (#13982)
- fix(Core/Movement): Falling/Jumping/Knockback effects should not make… (#14044)

## 2022-12-10
- fix(DB/loot): `Black Pearl Ring` wrongly drops (#14065)
- Revert "refactor(Core/Movement): Naming convention" (#14100)
- fix(DB/SAI): Stormwind Marshal (#14119)
- chore(DB): import pending files
- fix(DB/SAI): Script all of the Dark Portal opening event creatures (#14118)

## 2022-12-09
- Merge branch 'azerothcore:master' into Playerbot
- chore(DB): import pending files
- fix(DB/Player): Update playercreateinfo_action to line up with Wrath Classic. (#12563)

## 2022-12-07
- Merge branch 'Playerbot' of https://github.com/ZhengPeiRu21/azerothcore-wotlk into Playerbot
- Merge branch 'master' into Playerbot
- chore(DB): import pending files
- fix(DB/Quest): Into the Breach Quest start/end (#14092)

## 2022-12-06
- chore(DB): import pending files
- fix(DB/GameEvent): Add Arena Seasons 1 and 2 to game_event (#13999)
- chore(DB): import pending files
- fix(Scripts/Karazhan): Added Opera Event decorations. (#13952)
- chore(DB): import pending files
- fix(DB/loot): Adjust AQ40 Idols and coffers (#13998)
- chore(DB): import pending files
- chore(DB/DungeonAccess): Add comments part 2 (#14087)
- chore(DB): import pending files
- fix(DB/Quest): Supplying the Front quest reward (#13933)
- chore(DB): import pending files
- fix(DB/GameEvents): Move Brewfest start dates. (#13136)
- chore(DB): import pending files
- chore(DB/DungeonAccess): Add comments (#14022)
- chore(DB): import pending files
- fix(Core/Players): Fixed awarding kill credit while being on vehicles. (#13944)
- fix(Scripts/BloodFurnace): Fixed Broggok not casting Poison Cloud. (#13894)
- fix(DB/Conditions): Pint-Sized Pink Pachyderm and Wolpertinger should… (#13946)
- fix(Core/GameObject): Implement restock mechanic for non-consumable gameob… (#13950)
- fix(Core/Loot): Fix quest items looting system (#13720)
- chore(DB): import pending files
- fix(DB/Quests): 'one commendation signet' & 'ten commendation signets' quest descriptions (#13779)
- fix(DB/SmartAI): Convert smartai stealth detection buff to Aura (#13828)
- chore(DB): import pending files
- fix(DB/SAI): Baristolth of the Shifting Sands Agent of Nozdormu restoration. (#13956)
- chore(DB): import pending files
- fix(Scripts/BlackwingLair): Razorgore the Untamed should not reset enco… (#13782)
- fix(DB/Dungeons): Caverns of Time: Old Hilsbrad should be available u… (#13895)
- fix (DB/Conditions): Drain Schematics (#13960)
- fix(DB/Creature): Auchenai Crypts pathing, formations and minor fixes (#13865)
- fix(Scripts/Spells): Apple Trap should not activate without the playe… (#13868)
- fix(DB/SAI): Fixed spam chat made by Coilfang Slavemaster and Coilfan… (#13871)
- fix(Core/SmartScripts): Implemented new target type: SMART_TARGET_SUM… (#13880)
- fix(Scripts/HellfireRamparts): Nazan should descend when Vazruden rea… (#13876)
- fix(Scripts/HellfireRamparts): Hellfire Sentry should aggro on each o… (#13878)
- fix(DB/SAI): Hellfire Imp SAI. Source: TrinityCore. (#13891)
- fix(DB/SAI): Feralfen Hunter should cast Net (#13961)
- fix(DB/SAI): Crypto Raider should cast Enrage at <20% hp. (#13885)
- fix(DB/Quest): Our Boy Wants To Be A Skyguard Ranger prerequisite (#13968)
- fix(DB/SAI): Bladewing Bloodletter (#13967)
- fix(DB/Loot): Fenclaw Hide (#13964)
- fix(DB/SAI): Unliving adds summoned by Auchenai Soulpriest/Monk/Vindi… (#13890)
- fix(DB/Creature): Add missing Warmaul creatures in Warmaul Hill (#14026)
- fix(DB/Quest): A Visit With the Greatmother shouldn't be available without completing all prerequisites (#14027)
- fix(DB/SAI): Marshfang Slicer (18131) (#14028)
- fix(DB/Quest): Remove rewards from quest There Is No Hope (10172) (#14029)
- fix(DB/Creature): Increase detection_range of Underbog Lord (#14030)
- fix(DB/GameObject): Add more Raven Stones (#14064)
- fix(DB/Creature): Remove redundant Tamed Sporebat (18201) spawns (#14032)
- fix(Scripts/TempleOfAhnQiraj): Corrected timer for Cthun's Dark Gla… (#13799)
- refactor(Core/UnitAI): Update target selector (#13169)
- fix(Scripts/Karazhan): Mark optional boss as completed when it dies (#13175)
- fix(Scripts/TempleOfAhnQiraj): Anubisath Sentinels should emote af… (#13797)
- chore(DB): import pending files
- fix(DB/SAI): Prevent text spam in Hellfire Ramparts (#14036)
- chore(DB): import pending files
- fix(DB/SmartAI): Laughing Skull Warden stealth detection buff (#13826)
- fix(DB/Creature): TBC Gas Clouds shouldn't be selectable (#14072)
- fix(Core/Session): Fixed loading global account data and tutorials. S… (#14038)
- fix(DB/Creature): Correct reputation gains in Blood Furnace Normal Mode (#14035)
- fix(DB/Creature): Prevent Underground Well Credit Marker from attacking the player (#14071)
- chore(DB): import pending files
- fix(DB/SAI): Correct target type for Guardian of the Eagle SAI (#14060)
- fix(DB/Creature): Fix missing Aldor/Scryer trainer gossip and prevent bookshelves from facing the player (#14040)
- fix(DB/Gossips): Show the correct gossip for Ysuria. (#14056)
- fix(DB/Creature): Add Emote state work to Rogg (37072) (#14041)
- fix(DB/Text): Highlord Kruul's text (#14061)
- fix(DB/Quests): Fixed quest chaining of "Trial of the Naaru: Magtheri… (#13954)
- fix(DB/pool): Pool herbs in Alterac Mountains (#13390)
- chore(DB): import pending files
- fix(DB/GameObject): Add 3 more Box of Surveying Equipment spawns (#14073)

## 2022-12-02
- chore(DB): import pending files
- fix(DB/Locale): esES/esMX reward text for Reagents for Reclaimers Inc. (#13969)
- chore(DB): import pending files
- fix(DB/SAI): Bloodthirsty Marshfang (#13962)
- fix(DB/gameobject): Port Netherwing objects from Mangos (#13970)
- refactor(Core/Achievement): Remove Hungarian notation (#13991)
- refactor(Core/Movement): Naming convention (#13989)
- fix(DB/CTM): Fix Vanquished Tentacle of  C'thun moving (#14018)
- fix(DB/SAI): Underbog Lord should cast Knock Away (#14020)
- chore(DB): import pending files

## 2022-12-01
- fix(DB/SAI): Marshfang Ripper AI (#13955)
- Merge branch 'azerothcore:master' into Playerbot

## 2022-11-27
- chore(DB): import pending files
- fix(DB/Trainers): Bookshelves in Seer's Library should skill up profe… (#13945)

## 2022-11-24
- Revert "fix(Scripts/Temple of AhnQiraj): Cthun's Eye should always focus on b…" (#13938)

## 2022-11-23
- feat(Core/Crypto): add support `OpenSSL 3.0` (#13354)
- Merge branch 'azerothcore:master' into Playerbot

## 2022-11-21
- chore(DB): import pending files

## 2022-11-22
- fix(DB/Creatures): Phantasmal Possessor are immune to any kind of Cro… (#13883)

## 2022-11-21
- chore(DB): import pending files
- fix(DB): Re-construct the Underbog (#13769)
- fix(DB/SmartAI): Improve Hellfire SmartAI part 1 (#13611)
- chore(DB): import pending files
- fix(DB/Spells): Drums of War/Battle/Speed/Restorarion should apply Ti… (#13866)
- chore(DB): import pending files
- fix(DB/SAI): Uncontrolled Voidwalker (#13853)
- fix(DB/SAI): Raging Colossus (#13852)
- fix(DB/SAI): Kaliri Nest should despawn on use (#13850)
- fix(DB/Loot): Coilfang Water Elemental loot (#13832)
- fix(Scripts/Spells): Hallow's End Candy punpkin treat should turn pla… (#13808)
- chore(DB): import pending files
- fix(DB/Conditions): Grub should sell its items only to players who co… (#13803)
- fix(Core/Items): Item sell prices are affected by durability loss. So… (#13801)
- fix(DB): Pathaleon the Calculator's Image duplicate spawn/ Warped Peon (Missing animation) (#13641)
- fix(Scripts/Spells): Phantasmal Possessor's Posses spell should be ca… (#13884)
- chore(DB): import pending files
- fix(DB/SAI): Bleeding Hollow Scryer should cast Fear on random non-ta… (#13879)
- chore(DB): import pending files
- fix(DB/creature_template_locale): Ilkrud Magthrull name (#13861)
- fix(DB/Locale): Missing Locales Dragonblight esES/esMX (#13807)
- fix(DB/Locales): Add Missing esES/esMX locales to WG and GrizzlyHills (#13893)
- chore(DB): import pending files
- Fix(DB/Locale) Missing Borean Tundra esES/esMX Locales quests (#13768)
- chore(DB): import pending files
- Fix(DB/Locale): Missing howling fjord esES/esMX locale (#13806)
- chore(DB): import pending files
- fix(DB): Fix Slave Pens pathing, formations and improve gathering nodes (#13816)
- chore(DB): import pending files
- fix(DB): Improve Mana-Tombs waypoints, formations and gathering nodes. (#13833)
- fix(Core/Scripts): Master of elements odd crash (#13849)
- chore(DB): import pending files
- fix(Core/Units): Do not stun players during taxi flight. (#13798)
- fix(DB/SAI): Corrected despawn type for Tabulks summoned by Shado 'Fi… (#13778)

## 2022-11-20
- fix(Scripts/Temple of AhnQiraj): Cthun's Eye should always focus on b… (#13796)
- fix(Scripts/TempleOfAhnQiraj): Fix Digestive Acid not being applied t… (#13870)

## 2022-11-19
- fix(Core): Crash on random movement SAI (#13862)
- fix(Core/Build): correct build for `GCC 12` (#13583)
- chore(Scripts/Commands): increase default removal duration to 30m from 15m (#13869)
- fix(Scripts/TempleOfAhnQiraj): Prevent tentacles from spawning inside… (#13864)

## 2022-11-18
- Merge branch 'Playerbot' of https://github.com/ZhengPeiRu21/azerothcore-wotlk into Playerbot
- Merge branch 'master' into Playerbot

## 2022-11-17
- chore(DB): import pending files
- fix(DB): Correct mistake (#13848)

## 2022-11-16
- chore(DB): import pending files
- fix(DB/onkill_reputation) Venture Co. mobs in stv (#13644)
- fix(DB/SmartAI): Unliving Stalker Viper Sting heroic only (#13815)
- fix(DB/Services): Brown Kodo should be replaced with Unpainted Mechan… (#13813)
- fix(DB/Creature): Garrick Padfoot Rage generation (#13830)
- fix(Core/Pets): Save all spell cooldowns to db. (#13809)
- fix(Core/Spells): Fixed Glyph of Kilrogg. (#13802)
- fix(Scripts/Items): Green Whelp Armor affects only enemies level 50 a… (#13800)
- fix(Scripts/Commands): Fix assertion error on mmaps path command (#13704)

## 2022-11-15
- fix(Scripts/TempleOfAhnQiraj): Twins Emperors - First Teleport (#13652)

## 2022-11-16
- fix(Scripts/TempleOfAhnQiraj): Increase Vek'lor Blizzard timer (#13791)
- fix(Core/Spells): FIxed calculating LoS for dynamic objects. (#13795)
- chore(DB): import pending files
- fix(DB/Spell): Serendipity should proc off on cast rather than on hit. (#13805)

## 2022-11-15
- chore(DB): import pending files
- fix(DB/SAI): Missing Fire Brigade Locale esES/esMX (#13718)

## 2022-11-13
- fix(Core/Scripts): Renataki crash (#13811)
- chore(DB): import pending files
- fix(DB/Loot): Syndicate emblems in junkboxes (#13750)

## 2022-11-12
- chore(Scripts/ToC): Correct variable naming according to standarrds (#13786)
- chore(DB): import pending files
- fix(Scripts/ToC): Fix Trial of the Champion and Trial of the Crusader on … (#13772)
- fix(DB/gameobject): Cleanup previous TBC revamps and set better spawn timers (#13599)
- fix(DB/Creature): Update Blood Furnace pathing, formations and add missing spawns (#13757)
- fix(Docs): ReadMe (#13773)
- chore(DB): import pending files
- fix(DB/gameobject): Improve Escape From Durnholde incendiary barrels (#13627)
- fix(Core/Loot): Fixed processing duplicated loot item within different groups. (#13038)
- refactor(Core/ScriptedAI): few improvements with threat methods (#13146)
- chore(DB): import pending files
- fix(DB/Creature): Awbee RP close gossip (#13775)
- fix(Core/Creature): Prevent flying creatures from falling on respawn. (#13774)
- fix(DB/Creature): Gelkis Rumbler & Gelkis Earthcaller (#13760)
- chore(DB): import pending files
- fix(DB/creature) Remove bleed immunity from Twilight Elementalist (#13749)
- chore(DB): import pending files
- fix(DB/Creature): Remove incorrect gossip from Roetten Stonehammer (#13767)
- chore(DB): import pending files
- fix(DB/SAI): Dreamscythe and Jammal'an the Prophet (#13756)
- chore(DB): import pending files
- fix(DB/creature_template): Disable Shattered Hand Warhound assistance function (#13753)
- chore(DB): import pending files
- fix(DB/SAI): Missing esES/esMX locales (#13716)
- chore(DB): import pending files
- fix(DB/gameobject): Venom bottle queststarter (#13713)
- chore(DB): import pending files
- fix(DB/creature_template_locale): Fix Vikki Lonsav title (#13699)
- chore(DB): import pending files
- fix(DB/Gameobject): instant spawn on Eyes of Skettis and remove Duplicate (#13721)
- fix(DB/Quest): Zangarmarsh quest rep requirements (#13726)
- fix(DB/SAI): Bonechewer Ravener (#13739)
- fix(DB/SAI): Hellfire Imp animation on combat (#13729)

## 2022-11-11
- fix(Core): Correct Rest Bonus Formula (#13173)
- fix(Core): Fix guild bank update broadcasts (#13520)

## 2022-11-09
- feat(Docs): Add Doxygen link to ReadMe (#13755)
- chore(DB): import pending files
- fix(DB/SAI) Dreghood Brute dont become friendly after the death of the taskmaster (#13696)
- fix(Spells/TempleOfAhnQiraj): Attempt to partly fix Digestive Acid not being applied (#13751)

## 2022-11-08
- fix(Core/Unit): Prevent CTM rooted flag from being removed on aura ex… (#13732)
- chore(DB): import pending files

## 2022-11-07
- fix(DB/Creature): Remove Disorient immunity from rank 0 (Normal) undead and elemental creatures (#13724)

## 2022-11-08
- chore(DB): import pending files

## 2022-11-07
- fix(DB/gameobject): Durotar Copper Vein overhaul (#13573)

## 2022-11-08
- chore(CI): restore old configuration
- chore(CI): removed cache_from client-data
- chore(CI/docker): disable BUILDKIT_INLINE_CACHE
- fix(CI/docker): increase build space

## 2022-11-07
- fix(CI/docker): checkout the entire history
- fix(CI/docker): removed buildx and speedup checkout
- fix(CI/docker): try to fix the missing space issue
- fix(CI): clean before checkout
- fix(CI/docker): optimize runtime space
- Merge branch 'azerothcore:master' into Playerbot
- feat(CORE/docker): try to leverage inline cache
- fix(CI): missing --profile dev
- fix(CORE/docker): restore old client-data image creation
- fix(CORE/docker): client data image deployment
- feat(CORE/docker): cachebust for the client data
- fix(CI/docker_build): missing step
- fix(CORE/docker): image tag creation
- feat(CORE): docker permissions and rework (#13454)
- feat(Core/Scripting): Create OnStoreNewItem() hook (#13725)

## 2022-11-06
- chore(DB): import pending files
- fix(DB/creature): High Admiral "Shelly" Jorrik Rep and spawn (#13714)

## 2022-11-05
- chore(DB): import pending files
- fix(DB/Creature) Slain Auchenai Warrior & Slain Sha'tar Vindicator (#13695)
- fix(DB/GameObject): instant spawn on 61-64 quest interactables (#13712)
- fix(DB/SAI): Change Qiraji Mindslayer Mana Burn cast to ON_DEATH instead of UPDATE_IC (#13715)
- fix(Core/Unit): Exclude Sword Specialization and Hack and Slash from … (#13706)
- feat(Core/Scripting): Expand ModifySpellDamageTaken() to include the … (#13707)
- chore(DB): import pending files

## 2022-11-04
- fix(DB/Creature): Remove wrong MECHANIC_SLOW_ATTACK immunity from cre… (#13700)
- chore(DB): import pending files
- fix(Scripts/TempleOfAhnQiraj): Huhuran/BugTrio - EnterCombat (#13653)
- fix(DB/Creature) Lisaile Fireweaver (#13679)
- chore(DB): import pending files
- fix(DB/areatrigger_tavern) Fix neutral rest area in Booty Bay (#13656)
- fix(DB/quest_template_addon): Add repeatable flag to Imperial Qiraji quests (#13688)
- fix(Core/Unit): Check if the unit is within melee range before proces… (#13697)
- fix(Scripts/TempleOfAhnQiraj): Don't store object references in scripts (#13694)
- fix(Scripts/TempleOfAhnQiraj): Fix crash caused by permanently spawni… (#13698)
- fix(Scripts/TempleOfAhnQiraj): Fix Ouro not using abilities if there's only one player and he's out of his melee range (#13692)
- fix(Scripts/TempleOfAhnQiraj): Replace Sartura's Gaze mechanic with a threat wipe (#13691)
- Merge branch 'azerothcore:master' into Playerbot
- fix(CORE): file permissions for the devcontainer (#13686)

## 2022-11-03
- fix(Core/Scripting): Also call the OnLootItem() hook on master looted… (#13683)
- chore(DB): import pending files
- fix(DB/gameobject): Improve Netherstorm gathering nodes and pooling (#13582)
- fix(DB/gameobject): Improve Outlands Fishing Pools (#13570)
- fix(DB/gameobject): Improve Blade's Edge Mountains gathering nodes and pooling (#13560)
- chore(DB): import pending files
- fix(DB/gameobject): Improve Shadowmoon Valley gathering nodes and pooling (#13596)
- fix(DB/gameobject): Improve Terokkar Forest gathering nodes (#13466)
- fix(DB/gameobject): Improve Zangarmarsh gathering nodes and pooling (#13442)
- chore(DB): import pending files
- fix(DB/gameobject): Improve Hellfire Peninsula gathering nodes and pooling (#13398)
- chore(DB): import pending files
- fix(DB/gameobject): Add more Shredder Parts (#13605)
- fix(Scripts/TempleOfAhnQiraj): Improve Veklor pathing (#13682)
- chore(DB): import pending files
- fix(DB/gameobject): Adjust respawn timers for Hellfire Peninsula quest objects 184466 and 185302 (#13681)

## 2022-11-02
- feat(Core/Scripting): Implement OnAuraApply() hook for unitscripts (#13658)
- feat(Core/Scripting): Expand ModifyHealReceived() to also include hea… (#13655)
- chore(DB): import pending files
- fix(DB/Creature): Improve Outlands Gas Clouds (#13562)
- fix(DB/GameObject): Improve Isle of Quel'Danas gathering nodes and pooling (#13597)

## 2022-11-01
- chore(DB): import pending files

## 2022-11-02
- fix(DB/creature): Reduced Firewing Courier's spawntime, text added (#13629)

## 2022-11-01
- chore(DB): import pending files
- fix(DB/Quest): The Grateful Dead (Draenei) (#13640)
- Add (core\logging): Log sync db queries in mapupdater (#13638)
- chore(DB): import pending files
- fix(DB/Formations): Link packs in the Blood Furnace (#13628)
- fix(DB/Creature): Improve Azuregos' mechanic (#13616)
- feat(Core): Config to disable all Wintergrasp processing (#13086)
- fix(Core): Crashfix. (#13484)
- chore(DB): import pending files
- fix(DB/GameObject): Improve Nagrand gathering nodes and pooling (#13545)
- fix(DB/Formations): Update Hellfire Ramparts GroupAI and link stationary packs (#13600)
- fix(Scripts/Commands): Fix group list command output (#13614)

## 2022-10-31
- Merge branch 'azerothcore:master' into Playerbot

## 2022-10-30
- chore(DB): import pending files
- feat(DB): Change VerifiedBuild datatype to MEDIUMINT (#12960)
- fix(Scripts/TempleOfAhnQiraj): Fix Sartura not enraging if stunned (#13615)
- chore(DB): import pending files
- fix(DB/Loot): Fix Burning Legion Missive drop chance (#13607)

## 2022-10-29
- fix(Core/Spells): Spells requires cast from behind victim bypass Dete… (#13499)
- chore(DB): import pending files
- fix(Core/Units): Fixed uninitialized `m_cleanDamage` variable after e390087 (#13485)
- fix(Core/Players): Fixed obtaining extra (custom) talent points only … (#13526)
- fix(Core/Players): Players should nt able to rest in unfriendly taver… (#13493)
- fix(DB/Spells): Bloodsurge vs Slam. (#13507)
- fix(Scripts/MoltenCore): Lava Spawn. (#13508)
- fix(Core/Pets): Tamed hunter pets should deal physical damage. (#13522)
- fix(DB/WorldEvents): Added missing spawn of Katrina Shimmerstar. (#13516)
- fix(Core/Spells): Implemented SPELL_HIT_TYPE_SPLIT hit type. Source: … (#13518)
- fix(Core/Spells): Maelstrom Weapon should not reset attack timers. (#13504)
- fix(Core/Spells): Fixed calculating LoS for dynamic objects. (#13521)
- fix(Scripts/Commands): Fixed command `learn all my talents` for chars… (#13529)
- fix(Core/Quest): Fixed implementation of `CONFIG_QUEST_IGNORE_AUTO_ACCEPT` and `CONFIG_QUEST_IGNORE_AUTO_COMPLETE` configs. (#13525)
- fix(Core/Movement): Removed some leftover after c8f43d85849. (#13524)
- chore(DB): import pending files

## 2022-10-28
- fix(DB/Creature): Add interrupt immunity to Emperor Vek'lor (#13483)
- fix(Scripts/TempleOfAhnQiraj): Ouro Sand Blast should hit top threat … (#13578)
- chore(DB): import pending files
- fix(DB/Creature): AQ40 taunt immunity (#13576)
- fix(Scripts/TempleOfAhnQiraj): Properly prevent Uppercut from triggering Double Attack (#13581)
- fix(Scripts/TempleOfAhnQiraj): Sand Blast threat-wipe mechanic (#13577)
- feat(CI): auto-assign to all projects
- fix(CI): improve previous commit
- fix(CI): correct auto-assign-projects
- feat(CI): try assign-to-one-project
- fix(CI): use add-to-projects v0.0.5
- feat(CI): first experiment with add-to-project

## 2022-10-27
- fix(Scripts/TempleofAhnQiraj): Cthun Grasps should despawn on Cthun… (#13503)
- fix(Core/Creatures): Fixed loading transform auras from DB. (#13489)
- fix(Core/Movement): Fixed mobs evading attacks in case of incompleted… (#13519)

## 2022-10-26
- fix: Crash (#13559)
- chore(DB): import pending files
- fix(DB/Spells): Fiery Payback should have 1min internal cooldown. (#13496)
- fix(Scripts/TempleOfAhnQiraj): Don't let Giant Claw Tentacles autoatt… (#13550)
- Merge branch 'azerothcore:master' into Playerbot
- chore(DB): import pending files

## 2022-10-25
- fix(Scripts/TempleOfAhnQiraj): Huhuran's Wyvern Sting should hit the … (#13468)
- chore(DB): import pending files
- fix(DB/Spells): Spell Axe Flurry should target only one player. (#13208)
- fix(Scripts/Temple of AhnQiraj): Slime Toxin clouds should despawn 10… (#13492)
- fix(Scripts/TempleOfAhnQiraj): Fix Veklor hitbox (#13543)
- chore(DB): import pending files
- fix(DB/Movement): Root the Eye of C'thun (#13528)
- chore(DB): import pending files

## 2022-10-24
- fix(Scripts/TempleOfAhnQiraj): Make sure Sartura adds respawn on evade (#13541)
- feat(Scripts/Commands): Implement character changeaccount command (#13532)
- Merge branch 'azerothcore:master' into Playerbot
- fix(Core/ObjectAcessor): Fix crash caused by forced character renames (#13527)
- Merge branch 'azerothcore:master' into Playerbot
- fix(Core/Event): STV Riggle Bassbait broadcast text ids (#13517)

## 2022-10-23
- fix(Scripts/TempleOfAhnQiraj): Prevent Sartura from casting Whirlwind while stunned (#13481)
- fix(Core/Spells): Deep Wounds can proc off from non-physical spells. (#13494)
- fix(Scripts/TempleOfAhnQiraj): Prevent Uppercut from triggering Double Attack (#13482)
- chore(DB): import pending files
- fix(DB/Creatures): Timothy Cunningham should be civilian. (#13495)
- fix(Scripts/TempleOfAhnQiraj): Correct Anubisath Defender Explode spell ID (#13500)
- chore(DB): import pending files
- fix(DB/HallowsEnd): Fixed quest chaining of Fire Brigade Practice and… (#13486)
- fix(Scripts/HallowsEnd): Fixed starting "Let the fires come" event. (#13487)
- Add (core): Effect Transmit Anticheat Helper (#13447)

## 2022-10-22
- Merge branch 'azerothcore:master' into Playerbot
- fix(CORE/docker): path on conf generation
- chore(DB): import pending files
- fix(DB/HallowsEnd): Fixed "Trick or Treat" gossip option for Innkeepe… (#13488)
- feat(CORE/bash): implemented acore dashboard for Windows (#13476)
- fix(Scripts/TempleOfAhnQiraj): Fix Cthun 3-beam focus mechanic resett… (#13479)
- fix(CORE): another attempt to fix the dbimport command line warning (#13449)

## 2022-10-21
- fix(CORE): crash when AC_DISABLE_INTERACTIVE is not defined
- chore(DB): import pending files
- Fix (db): Graveyard Frostmane Hold Alliance (#13448)
- chore(DB): import pending files

## 2022-10-20
- fix(DB/SAI): Script Colossus of Zora, Ashi and Regal (AQ War Event npcs) (#13461)
- chore(DB): import pending files
- fix(Core/Event): Rework STV Fishing Extravaganza (#12506)
- chore(DB): import pending files
- fix(DB/gameobject, pool): overhaul Durotar chests (#13430)
- Revert feat(core): Start Process and  DBUpdater (#13465)

## 2022-10-19
- Merge branch 'azerothcore:master' into Playerbot
- chore(DB): import pending files
- fix(DB): Fix variable in 2022_10_07_06.sql (#13451)
- feat(CORE): implemented AC_DISABLE_INTERACTIVE for DBUpdater (#13450)

## 2022-10-18
- chore(DB): import pending files
- fix(DB/item_template): Blue sack of gems should not multidrop (#13429)
- Fix (core): SMSG_BINDPOINTUPDATE packet fix (#13452)

## 2022-10-17
- fix: codestyle CI (#13453)
- feat(CORE/docker): switch to `docker compose` and check the version (#13444)
- Merge branch 'azerothcore:master' into Playerbot
- fix(CORE): revert to mysql -p argument.
- fix(CORE): gcc compilation errors with gtest (#13445)
- fix(CORE/dbupdate)): allow to pass MySQL password via env (#13404)
- chore(DB): import pending files
- fix(Scripts/TempleOfAhnQiraj): Skeram copies shouldn't save raid cd (#13422)
- fix(Scripts/TempleOfAhnQiraj): Anubisath Sentinel Mortal Strike and M… (#13435)
- chore(DB): import pending files

## 2022-10-16
- fix(Scripts/TempleOfAhnQiraj): Correct post-teleport threat values for Twin Emperors (#13437)

## 2022-10-17
- fix(DB/SAI): vekniss warrior should not use impale (#13428)

## 2022-10-16
- fix(Scripts/TempleOfAhnQiraj): C'Thun pull range (#13438)
- fix(Scripts/TempleOfAhnQiraj): Use correct Ids for Drain Mana (#13436)
- fix(Scripts/Temple of AhnQiraj): Fixed Sartura's aggro reset mechanic. (#13185)

## 2022-10-15
- fix(Core): Build (#13425)
- fix(Core/Spells): Overflow damage (#13424)
- fix(Core/Battleground): Correct Alterac Valley mine announcement (#13411)
- chore(DB): import pending files

## 2022-10-16
- fix(DB/gameobject): Dutotar Food and Water Gameobject Overhaul (#13416)

## 2022-10-15
- Merge branch 'azerothcore:master' into Playerbot
- chore(DB): import pending files
- fix(DB/creature_template): Remove gold from Giant Eye Tentacle (#13414)
- fix(Scripts/TempleOfAhnQiraj): Fix double spawns during Cthun phase 2 and several other fixes (#13413)
- chore(DB): import pending files
- fix(DB): Remove Skinning loot from Giant Buzzard (#13392)
- fix(core): Horde Warsong Gulch gates dont despawn (#13381)
- fix(DB/creature): Adjust Shatterspear respawn timer (#13349)
- fix(DB/loot): Remove skinning loot from creatures that shouldn't be skinnable (#13348)
- fix(Core): Fix PlayerSettingVectors (#13338)
- Fix(core/scripts): issue 13325 - reset talents command (#13326)
- fix(DB/pools): Update herb pooling in TBC starter zones (#13319)
- fix (core): Header consistency (#13303)
- fix(Scripts/NPC): Arcanite Dragonling (#13233)
- fix(DB/creature_template): Import Vmangos values for Dragons of Nightmare and Azuregos (#13199)
- fix(DB): Add sharks (#13162)

## 2022-10-14
- chore(DB): import pending files
- fix(Scripts/TempleOfAhnQiraj): Ouro double spawn in 3rd phase, interrupt immunity (#13405)
- fix(Scripts/TempleOfAhnQiraj): Huhuran and Viscidus combat range (#13407)
- fix(Scripts/TempleOfAhnQiraj): Change spawn mode for Spawn of Fankriss (#13408)
- fix(Scripts/TempleOfAhnQiraj): Make Nullify consume mana (#13403)
- fix(DB/creature_template): Add IGNORE_ASSISTANCE_CALL to Anubisath Sentinel (#13406)
- chore(bash/db_assembler): show deprecation warning (#13410)
- chore(DB): import pending files
- fix(Scripts/ICC): gossip in boss Deathbringer Saurfang (#12381)

## 2022-10-13
- chore(DB): import pending files
- fix (updates\sql): Move orientation to pending (#13399)
- chore(DB): import pending files
- refactor: rename spell_proc fields (#13334)

## 2022-10-12
- Add (core\db): Support for Homebind Orientation (#13389)
- fix(Core/Creature): Fix LinkedRespawn not working with id2, etc. (#13367)
- fix(Scripts/TempleOfAhnQiraj): Fix Twin Emperor's critters aggroing p… (#13365)

## 2022-10-11
- chore(DB): import pending files
- fix(DB/creature_addon): Add missing auras to creature_addon (#13352)
- chore(DB): import pending files
- fix(DB/Creature): Add Horizon crew (#13165)
- fix(DB/creature_loot):  Corrects all incorrect quest rates in Ammen Vale (#13167)
- chore(DB): import pending files
- fix(DB/Creature): Springpaw pelt should drop less (#13383)
- chore(DB): import pending files
- fix(DB/pool): Pool Spawn of Hakkar to avoid double spawns (#13344)
- fix(Scripts/TempleOfAhnQiraj): Don't submerge Ouro if it's already en… (#13363)
- fix(DB/Creature): Set STATE_MELEE to Twin Emperors (#13366)
- chore(DB): import pending files
- fix(Scripts/TempleOfAhnQiraj): Allow Anubisath Sentinels to all pull together (#13362)
- fix(Scripts/TempleOfAnhQiraj): Fix Digestive Acid not stacking (#13361)
- fix(DB/loot): Remove AQ20 Idols from AQ40 mobs (#13359)
- fix(DB/creature_addon): Add Frenzy Aura to Vekniss Soldier (#13346)
- fix(Scripts/TempleofAhnQiraj): Obsidian Eradicator Shock Blast now consume mana (#13356)

## 2022-10-09
- feat(Core/DB): add support range loop for mysql result (#13355)
- chore(Gitignore): add ignore all folders `cmake-build-*` for Clion (#13353)
- chore(DB): import pending files

## 2022-10-08
- fix(Scripts/TempleOfAhnQiraj): Correct Dark Glare's radius (#13350)
- feat(Core/Items): Implemented elemental weapon damage. Source: Trinit… (#13050)
- chore(DB): import pending files
- fix(DB/Quest): Morganth (#13206)
- fix(Scripts/MoltenCore): Added loot recipient to Cache of the Firelord. (#13209)
- fix(Scripts/TempleOfAhnQiraj): Despawn Eye of Cthun once encounter is… (#13336)

## 2022-10-07
- chore(DB): import pending files
- fix(DB/creature): Grimscale Murloc improvements in Eversong Woods (#13315)
- fix(DB/gameobject): improve Captain Kelisendra's Cargo spawnpoints (#13317)
- chore(DB): import pending files
- fix(db/creature_loot_template): Item 21757 and 21771 rate corrections (#13328)
- fix(DB/spell_bonus_data): Add Missing Spell Bonus Data (#13333)
- fix(DB/creature_template): Update AQ40 detection ranges (#13339)
- fix(DB/creature): Add id2 to Qiraji Scarabs/Scorpions (#13337)
- fix(DB/loot): Adjust AQ40 loot (#13327)
- Remove outdated Git submodule
- Merge branch 'azerothcore:master' into Playerbot

## 2022-10-06
- chore(DB): import pending files
- fix(Core/Creatures): Renamed `CREATURE_FLAG_EXTRA_DONT_CALL_ASSISTANCE` to `CREATURE_FLAG_EXTRA_IGNORE_ASSISTANCE_CALL` (#13130)
- fix(Scripts/Temple of AhnQiraj): Adjusted Sartura's event timers. (#13187)
- chore(DB): import pending files
- fix(DB/QuestPOI): Trial of the Sea Lion (#13302)
- chore(DB): import pending files

## 2022-10-05
- fix(Scripts/TempleOfAhnQiraj): C'thun (#13153)

## 2022-10-06
- chore(DB): import pending files
- fix(DB/Spells): Using Ossirian Crystal should not prevent from castin… (#13211)
- chore(DB): import pending files
- fix(DB/Disables): Ossirian Crystals should not block LoS. (#13210)
- fix(Core/Spells): Rental Racing Ram will not be removed upon entering… (#13192)
- chore(DB): import pending files
- fix(Scripts/Temple of AhnQiraj): Sartura's Sundering Cleave should be… (#13184)

## 2022-10-05
- fix(Core/Vehicle): Crash (#13180)
- chore(DB): import pending files
- fix: Qaston revert (#13320)
- feat(docker): implemented dbimport (#13308)

## 2022-10-04
- fix(Core/TempleOfAhnQiraj): Huhuran timers + EventMap::Repeat (#13182)
- fix(Core/QAston): fixed shields oneshotting (#13271)
- fix(Core): Crash (#13292)

## 2022-10-03
- fix: Crash (#13241)

## 2022-10-02
- fix: Crash (#13230)
- chore(DB): import pending files
- refactor(Core/Spells): Implement QAston Proc System (#11079)
- Merge branch 'azerothcore:master' into Playerbot
- chore(DB): import pending files
- fix(DB/Quest): The Alliance Needs Silk Bandages completion text (#13202)

## 2022-10-01
- chore(DB): import pending files
- fix(DB/creature_loot_template): Branch of Cenarius should not drop from Prince Raze (#13174)

## 2022-10-02
- Update LFGMgr.cpp (#13197)

## 2022-10-01
- chore(DB): import pending files
- fix(DB/creature_loot_template): Sunstrider Isle Quest Rate Fixes (#13170)

## 2022-10-02
- fix(Tools/vmaps): Fix extractor crash when some .mpq files does not exist (#11976)

## 2022-10-01
- chore(DB): import pending files
- fix(DB/creature_template): Fix Ossirian's resistances accidentally removed. (#13191)
- fix(DB/Temple of AhnQiraj): Added `GROUP_AI_FLAG_RESPAWN_ON_EVADE` to… (#13188)
- fix(CORE/Spells): Fix Scaling of some Guardians (#12625)
- update (core): Startup console capitalizations (#13195)
- refactor(Scripts/Anubarak): Convert spellscripts to new system (#13194)
- chore(DB): import pending files
- fix(Scripts/Spells): Remove some magic numbers (#13193)
- fix(DB/Creature): Blix Fixwidget (#13190)
- chore(DB): import pending files
- fix (core): Log correction (#13181)
- fix(db/multi): Quest improvements for Ruins of Silvermoon area (#13183)

## 2022-09-29
- fix(Core/TempleOfAhnQiraj): Bug trio (#13141)

## 2022-09-28
- Merge branch 'azerothcore:master' into Playerbot
- fix (Core/Spell): Shadowform Dispel (#13155)
- chore(DB): import pending files
- fix(Scripts/Temple of AhnQiraj): Qiraji Champion. (#12965)
- chore(DB): import pending files

## 2022-09-27
- fix(DB/creature_loot_template): Broken Tears should not drop from NPCs (#13097)

## 2022-09-28
- chore(DB): import pending files
- fix(Scripts/TempleOfAhnQiraj): AhnQiraj critters should enter comba… (#12998)
- chore(DB): import pending files
- fix(DB/SAI): Update AQ40 Trash SmartAI. (#12931)
- chore(DB): import pending files
- fix(DB/BlackwingLair): Supression Room trash mobs should not respawn … (#13129)
- chore(DB): import pending files
- fix(DB/creature_template): Modify elementals dmgschool to deal elemental damage on melee attacks. (#13027)
- fix(Core/Item): Renataki's Charm of Beasts (#13124)
- chore(DB): import pending files
- fix(DB/SAI): Jademir Boughguard (#13125)
- chore(DB): import pending files
- fix(DB/item_loot): Ahn'Qiraj War Effort Supplies loot (#13135)
- chore(DB): import pending files
- fix(DB/creature_template): Update AQ20 detection ranges (#13150)

## 2022-09-27
- Update PLAYERBOTS_SEL_TEXT query

## 2022-09-26
- Merge branch 'azerothcore:master' into Playerbot
- fix(Scripts/MoltenCore): Players should not be able to summon Ragnaro… (#13128)
- chore(DB): import pending files
- fix(DB/waypoint): Update Sartura waypoints (#13142)
- fix(Core/TempleOfAhnQiraj): Fankriss pull range (#13143)
- fix(Scripts/Brewfest): Fixed race for tokens dailies. (#13109)

## 2022-09-25
- refactor(Core/Combat): Code style and improvement of ThreatMgr (#12992)
- fix(Scripts/Brewfest): Added inebriate effect to Complimentary Brewfe… (#13112)
- chore(DB): import pending files
- fix(core/quest): improved egg collection (#12640)
- feat(Core): Allow negative resistance values (#12958)
- fix(Scripts/Spells): Prevent from stacking basic campfires on each ot… (#13037)
- fix(Scripts/TempleOfAhnQiraj): Reduce player damage req for Ouro (#13065)
- fix(DB/Conditions): Added conditions to Neill Ramstein & Ram Master Ray gossip options. Source: TrinityCore. (#13108)
- fix(DB/Conditions): "Brewfest - apple trap - friendly DND" aura targe… (#13110)
- fix(Scripts/MoltenCore): Boss' runes should not respawn after 5 min o… (#13127)
- fix(Core): Crashfix. (#13113)
- fix(Core): Crashfix. (#13126)
- chore(DB): import pending files
- chore(DB/Quests): Correct wrong mark quest being added in 8fc055e44ec… (#13118)

## 2022-09-24
- chore(DB): import pending files
- fix(DB/Creature): Set Battered Brewer's gossip (#13123)
- fix(Core): Crash (#13106)
- chore(DB): import pending files
- fix(DB): Override Spell Bonus Coefficients (Workaround) (#13104)

## 2022-09-23
- chore(DB): import pending files
- fix(DB/skilllineability_dbc): Correct structure of skilllineability_dbc (#13088)
- Merge branch 'azerothcore:master' into Playerbot

## 2022-09-22
- fix(DB): typo in DB file (#13095)
- Merge branch 'azerothcore:master' into Playerbot
- chore(DB): import pending files
- fix(DB/gameobject): Import Vmangos herbs for Old World starter zones. (#13031)
- chore(DB): import pending files

## 2022-09-21
- fix(DB/Spawning) Shadowpine NPCs Ghostlands (#13093)
- chore(DB): import pending files
- fix(DB/creature_template): Vanilla gold drop values (credit Vmangos) (#11927)
- chore(DB): import pending files
- fix(Core/TempleOfAhnQiraj): Viscidus (#12956)
- chore(DB): import pending files
- fix(DB/creature_template): Vanilla Creature Speed corrections (Credit VMangos) (#11924)
- chore(DB): import pending files
- fix(Scripts/UpperBlackrockSpire): Missing Seal of Ascension event (#12891)
- fix(Core/Battlegrounds): `MinLevel` and `MaxLevel` from `battelground… (#12880)
- chore(DB): import pending files
- fix(CORE/Naxxramas): Portals and Teleports (#12696)
- chore(DB): import pending files
- fix(DB/Creatures): Arathi Basin Rare Critters: (#12882)
- chore(DB): import pending files
- fix(DB/gossip_menu_option_locale): Populate missing locale entries from broadcast_text (zhCN) (#11943)
- Merge branch 'azerothcore:master' into Playerbot
- chore(DB): import pending files
- fix(Scripts/Quest): improved egg freezing (#12575)
- fix(Core): Small improvements for weapon/defence skill handling (#12253)
- feat(core): OnFfaPvpStateUpdate Event (#13023)
- feat(Core): Hide Game Object Quest Markers Config Option (#13013)
- feat(Core): OnBeforeLootMoney hook (#13030)
- chore(DB): import pending files
- fix(DB/quest_offer_reward): Correct incorrect newline for Kranal Fiss (#13052)
- chore(DB): import pending files
- fix(Core): CanAccountCreateCharacter hook parameters (#13060)
- fix(DB/TempleOfAhnQiraj): Sartura formation groupAI (#13066)
- fix(DB/creature_formations): Prevent Jin'do from being pulled with trash (#13042)
- fix(Core/Player): Give Death Knight's twenty silver on character creation (#12974)

## 2022-09-20
- fix(Core): Hunter Readiness crash fix (#12987)
- fix(Core): SMART_EVENT_RANGE (#13064)
- fix(Core): Crashfix on vehicle uninstall. (#13036)

## 2022-09-19
- fix(Core/DBCLoader): Add handler for possibly unused DBC format data type (#13045)
- Feature(Smart Scripts/SMART_EVENT_RANGE): Proper fix to prevent Initial timer (#13059)
- Merge branch 'azerothcore:master' into Playerbot

## 2022-09-18
- feat(Core): CanAccountCreateCharacter hook (#13020)

## 2022-09-19
- fix(Core/Spells): Fingers of Frost should always proc alongside with … (#13008)
- chore(DB): import pending files
- fix(DB/Spells): Frost of Fingers vs AoE spells. (#13007)
- chore(DB): import pending files
- fix(Scripts/Spells): Finger of Frost Shatter Combo. (#13006)
- chore(DB): import pending files
- fix(DB/creature_formations): Update Fozruk GroupAI to pull together (#13032)
- chore(DB): import pending files
- fix(DB/Creatures): Blackwing Technicians should not chain-pull Death … (#13041)
- fix(Core/TempleOfAhnQiraj): Door handling (#13053)
- chore(DB): import pending files

## 2022-09-18
- fix(DB/gameobject): Adds missing static gameobjects in Ammen Vale (#13016)

## 2022-09-19
- chore(DB): import pending files

## 2022-09-18
- fix(DB): quest_greetings corrections (#12997)
- fix(Core): Creatures should finish casting any current spells before fleeing (#12964)

## 2022-09-19
- chore(DB): import pending files
- fix(Scripts/BlackrockSpire): Scarshield Infiltrator (#12920)

## 2022-09-18
- chore(Core): Debloat Mail.cpp (#12881)
- fix(Core): Correct Post 3.1 Fishing Skill Leveling (#12996)

## 2022-09-19
- fix(Scripts/Quest): A-Me 01 aggro text (#12953)
- chore(DB): import pending files
- fix(DB/Loot): Rot Hide Mongrel loot table (#12917)
- chore(DB): import pending files
- fix(Scripts/TempleofAhnQiraj): Moved Obsidian Nullifier script from… (#12949)

## 2022-09-18
- fix(Scripts/RuinsOfAhnQiraj): Fix Ayamiss not landing if someone take… (#13048)
- Merge branch 'azerothcore:master' into Playerbot
- fix(Core/Smart Scripts): Add param5 flag for range event (#13049)
- fix(Core/Spell): Mixology duration Gift of Arthas (#12982)

## 2022-09-17
- chore(Core/Player): Small optimization in the IsInWhisperWhiteList() … (#13026)
- chore(DB): import pending files
- fix(Scripts/TempleOfAhnQiraj): C'thun rewrite (#12993)
- chore(DB): import pending files
- feat(Core): Implement SP Bonus Coefficients from DBC (#12562)

## 2022-09-15
- Merge branch 'azerothcore:master' into Playerbot
- chore(DB): import pending files
- fix(DB/Pathing): Replace Simone path (#13029)
- Merge branch 'azerothcore:master' into Playerbot
- chore(DB): import pending files
- fix(DB/Pathing): Add missing path to Razorspine (#13025)

## 2022-09-14
- chore(DB): import pending files
- fix(Scripts/TempleOfAhnQiraj): Vekniss Stinger. (#12963)
- chore(DB): import pending files
- fix(Scripts/Temple of AhnQiraj): Moved Anubisath Warder script from D… (#12951)
- fix(Core/Spells): Improved Blink in WSG near NE huts. (#13012)
- fix(Core/Spells): Fixed ground destination of Blink. (#13009)
- fix(Scripts/Temple of AhnQiraj): Fixes Skeram's Summoning Images mech… (#12966)
- chore(DB): import pending files

## 2022-09-13
- fix(DB/Quests): One Commendation of Undercity quest (war effort) (#13022)

## 2022-09-14
- chore(DB): import pending files
- fix(Scripts/TempleOfAhnQiraj): Obsidian Eradicator. (#12733)
- chore(DB): import pending files
- fix(DB/SmartAI): Missing SmartAI to Mark of Detonation (#12967)
- chore(DB): import pending files
- fix(DB/Spells): Added 500ms cooldown to Flurry proc. (#13002)

## 2022-09-13
- Merge branch 'azerothcore:master' into Playerbot
- feat(Core): Hide Quest Sparkle Config Option (#13005)

## 2022-09-14
- fix(Core/Spells): Fixed applying `Command` aura to shaman Feral Spirits. (#13000)

## 2022-09-13
- chore(DB): import pending files

## 2022-09-14
- fix(DB/Spells): Fixed Shaman's T2 3Pbonus. (#13001)
- fix(Core/Spells): Fixed Paladin's T2 8P bonus. (#12999)

## 2022-09-13
- chore(DB): import pending files
- fix(DB/conditions): Glyph Chasing Conditions (#12986)
- chore(DB): import pending files
- fix(DB): Missing Ironforge Guard on Mountain (#12985)
- chore(DB): import pending files
- fix(DB): Missing Stratholme Linking and Pathing (#12979)
- Merge branch 'azerothcore:master' into Playerbot

## 2022-09-12
- fix(Core/Spells): Revive Pet cannot be cast if there is not pet to resurrect (#12818)

## 2022-09-08
- Merge branch 'azerothcore:master' into Playerbot
- chore(DB): import pending files
- fix(DB/loot): Add missing Warlock grimoires to AQ20 loot (#12991)
- chore(DB): import pending files

## 2022-09-07
- fix(DB/creature_template): Import AQ20 values from Vmangos. (#12845)

## 2022-09-08
- chore(DB): import pending files

## 2022-09-07
- fix(DB/loot): Remove AQ40 Idols from AQ20 (#12977)
- Merge branch 'azerothcore:master' into Playerbot
- chore(DB): import pending files
- fix(Scripts/Item): Winter Veil Disguise Kit cannot be used during pre… (#12883)

## 2022-09-06
- fix(DB/creature): Rework AQ40 Qiraji Champion packs after Twin Emperors. (#12862)

## 2022-09-07
- chore(DB): import pending files

## 2022-09-06
- fix(Core/TempleOfAhnQiraj): Twin emperors rewrite (#12855)

## 2022-09-07
- chore(DB): import pending files

## 2022-09-06
- fix(DB/Quests): Proof of Demise (374) available without prequest (#12875)

## 2022-09-07
- chore(DB): import pending files

## 2022-09-06
- fix(DB/creature_template): Import AQ40 values from Vmangos missing in previous PR (#12984)

## 2022-09-07
- fix(Core/BGQueue): correct start match logic (#12823)
- fix(Scripts/TempleOfAhnQiraj): Increased aggro range of Sartura. (#12961)
- chore(DB): import pending files
- fix(DB/EversongWoods): Repair Flag wrongly set (#12936)
- chore(DB): import pending files
-  fix(DB/EversongWoods): Ranger Sareyn RP (#12934)
- chore(DB): import pending files
- fix(DB/Quest): "Unraveling the Mystery" has wrong quest marker (#12932)
- chore(DB): import pending files

## 2022-09-06
- fix(DB/creature): Correct Newman's Landing NPC positions and vendor items. (#12914)

## 2022-09-07
- chore(DB): import pending files
- fix(Core/Unit): DualWield Off-hand hit penalty (#12906)
- fix(DB/Item): Dark Rune puts Demonic Rune 2min CD (#12921)

## 2022-09-06
- chore(DB): import pending files
- fix(DB/creature): Araga (14222) add spawn points and pooling (#12888)
- chore(DB): import pending files
- fix(DB/creature): AQ40 Qiraji Scarab & Scorpion movement (#12937)

## 2022-09-07
- feat(Scripting/Hooks): Add OnBeforeOpenItem Hook (#12576)

## 2022-09-06
- Attempt to fix Evade issue
- chore(DB): import pending files
- fix(DB/linked_respawn): Link AQ20 trash spawn (#12908)
- fix(Scripts/AqhQiraj): Increased aggro range for Moam. (#12947)
- feat(Core): OnBeforeChooseGraveyard Hook (#12860)
- chore(DB): import pending files
- fix(DB/Creature): Brambleblade Ravine revamp in Mulgore (#12854)
- fix(Core/Player): Dismount on Transport Teleport (#12848)
- fix(Core/Maps): Fixed getting liquid data near depths. (#12814)
- fix(Core): Entering BG whilst in combat (#12770)
- chore(DB): import pending files
- fix(DB/LookingForGroup): Leaving dungeon does not give deserter (#12763)
- chore(DB): import pending files

## 2022-09-07
- fix(DB/Quest): BlackKnight‘Order npc required credit count  (#12717)

## 2022-09-06
- chore(DB): import pending files
- Merge branch 'azerothcore:master' into Playerbot
- fix(DB/EversongWoods): Remove sprint action from tigers (#12704)
- chore(DB): import pending files
- fix(DB/Movement): Blackrock Drake path waypoints and movement template. (#12556)
- chore(DB): import pending files
- fix(DB/Quests): Repeatable flag for The Alliance Needs More Iron Bars! (#12981)
- chore(DB): import pending files
- fix(DB/Gossips): Corrected gossips shown for Arygos, Caele… (#12962)
- fix(DB/Quests): Repeatable flags for The Horde Needs More Mithril & T… (#12968)

## 2022-09-03
- chore(DB): import pending files
- fix(DB/Creatures): General Rajaxx Andorov and Kaldorei Elites should … (#12948)
- Merge branch 'azerothcore:master' into Playerbot
- fix(Core/Spells): Resistance auras should affect creatures. (#12946)
- chore(DB): import pending files
- fix(Scripts/Spells): Fix Itch (26078) not applying Vekniss Catalyst (#12930)
- chore(Core/Script): Correct spelling of Strength of Ossirian from Strenght (#12945)
- fix(DB/linked_respawn): General Angerforge shouldn't respawn adds when dead. (#12887)
- chore(DB): import pending files

## 2022-09-02
- fix(DB/creature): Update Vekniss Guardian (15233) movement (#12940)

## 2022-09-03
- chore(DB): import pending files

## 2022-09-02
- fix(DB/Loot): Update AQ Scarab item drops (#12935)
- chore(DB): import pending files
- fix(DB/SAI): Fix Andorgos teleports in AQ40 (#12939)
- Merge branch 'azerothcore:master' into Playerbot
- chore(DB): import pending files
- fix(DB/creature_template): Import Vmangos values for ZG (#12907)
- chore(DB): import pending files
- fix(DB/Spells): Fixed applying Brutal Assault. (#12886)
- fix(Core/Spells): Fixed spell error when players tries to disarm rang… (#12885)
- fix(DB/creature_template): Import Vmangos values for AQ40. (#12902)
- chore(DB/Commands): Add missing command to the database (#12924)
- fix(Core): Correct Quest XP Display when modified by OnQuestCompleteXP Hook (#12919)
- fix(DB/SAI): Improve ZG Voodoo Spirit (15009) (#12926)

## 2022-09-01
- fix(Core): Fix Missing OnBeforeQuestComplete Hook (#12892)
- Merge branch 'azerothcore:master' into Playerbot
- chore(DB): import pending files
- fix(Core/SmartAI): Mind-controlled creatures can auto-attack its vict… (#12863)

## 2022-08-31
- fix(DB/creature_formation): Link AQ40 trash packs near Princess Huhuran. (#12872)
- fix(Core/Battlegrounds): Fixed setting proper winner team at the end … (#12868)
- fix(Core/Scripts): Rajaxx should drop aggro after Thundercrash (#12900)

## 2022-08-30
- Merge branch 'azerothcore:master' into Playerbot
- chore(DB): import pending files
- fix(DB/linked_respawn): AQ40 trash respawn (#12877)
- chore(DB): import pending files
- fix(DB/SAI): Script Maw's pathing (#12904)

## 2022-08-29
- Merge branch 'azerothcore:master' into Playerbot
- chore(DB): import pending files
- fix(DB/Quest): Import several missing texts and creature links for th… (#12890)

## 2022-08-28
- fix(Core/Spells): Wyvern Sting DoT (ranks 1-3) should considered as n… (#12803)
- chore(DB): import pending files
- fix(Scripts/Spells): Moonkin Form passive aura should not proc off fr… (#12815)

## 2022-08-27
- chore(DB): import pending files

## 2022-08-28
- fix(DB/Spells): Glyph of Blocking should proc on Shield Slam use rath… (#12865)
- fix(Core/TotemAI): Active totems should interrupt its spell casting i… (#12864)
- fix(Core/Spells): Nature's Swiftness should not be consumed by instan… (#12816)
- fix(Core/Spells): Fixed Rejuvenation healing amount increased by Idol… (#12812)

## 2022-08-27
- chore(DB): import pending files
- fix(DB/Loot): Remove all Punctured Voodoo Dolls from mobs (#12768)
- chore(DB): import pending files
- fix(DB/Creature): Remove incorrect drops for Idol of Brutality (#12769)
- fix(Scripts/RuinsOfAhnQiraj): Restructure Ayamiss task scheduling during landing (#12870)
- chore(DB): import pending files
- fix(DB/TempleOfAhnQiraj): Added missing spawns of Cthun Graps. (#12806)
- fix(Core/Battelgrounds): Fixed registering newly created battleground… (#12869)
- fix(Core/Spells): Feed Pet should not interrupt eating/drinking. (#12817)
- chore(DB): import pending files
- fix(DB/Creature): ZG Snake Area Unpooled Fixes (#12540)
- fix(Core/Quest): improved flight of the wintergarde defender (#12437)
- chore(DB): import pending files
- fix(Scripts/TempleOfAhnQiraj): Added missing doors. (#12734)
- fix(Scripts/TempleOfAhnQiraj): Princess Huhuran's Poison Bolts should… (#12861)
- fix(Scripts/TempleOfAhnQiraj): Skeram should cast True Fulfillment on closest non-tank player.
- fix(Core/Spells): Death's Respite should not generate threat. (#12807)
- fix(Scripts/TempleOfAhnQiraj): Aggro Drones. (#12737)

## 2022-08-26
- fix(Scripts/RuinsOfAhnQiraj): Implement bonus reputation gains if you… (#12856)
- fix: Buru crash (#12858)
- fix(Scripts/RuinsOfAhnQiraj): Increase Andorov's bash intervals and r… (#12853)
- feat(Core/DBUpdater): Apply each sql update file in a separate transa… (#12842)
- chore(DB): import pending files

## 2022-08-25
- fix(DB/Loot): Update Scarab Coffer (180690 & 180691) loot (#12850)
- feat(CMake): Minor CMake Update to Modules Cmake File to Allow Custom Modules to make changes without changing Core. (#12846)
- chore(DB): import pending files
- fix(DB/Creature): Ayamiss larva should be knockback immune (#12847)
- Merge branch 'master' into Playerbot
- fix(Core/Weather): Wrong change type algorithm (#12729)
- chore(DB): import pending files

## 2022-08-24
- fix(Scripts/RuinsOfAhnQiraj): Anubisath Defender's shadow storm shoul… (#12844)
- fix(DB/Creature): Improve Nefarian's Corrupted Infernal (14668) (#12841)
- fix(DB/linked_respawn): Link Rajaxx's waves respawns to Rajaxx (#12843)

## 2022-08-25
- chore(DB): import pending files

## 2022-08-24
- fix(Scripts/RuinsOfAhnQiraj): Fix Ossirian's starting crystal and san… (#12839)

## 2022-08-25
- chore(DB): import pending files

## 2022-08-24
- fix(DB/Creature): Fix AQ20 respawn timers (#12840)

## 2022-08-23
- fix(sql): Squash fix for mariadb (#12830)
- chore(DB): import pending files
- fix(DB/Loot): AQ20 enchanting recipes (#12810)
- fix(Scripts/TempleOfAhnQiraj): Fixed Skeram's Earth Shock. (#12740)
- fix(DB/Creature): Remove gold drops from Swarmguard Needler and Hive'Zara Larva. (#12827)
- fix(DB/Formations): AQ40 Stationary pack linking (#12799)
- chore(DB): import pending files
- refactor(Scripts/RuinsOfAhnQiraj): Buru eggs (#12822)

## 2022-08-21
- feat(Core/GameObject): Add an overload to SummonGameObject() to accep… (#12821)
- fix(Scripts/RuinsOfAhnQiraj): Lower player damage req when Buru is da… (#12820)
- fix(Scripts/RuinsOfAhnQiraj): Enable Ayamiss gravity when landing (#12819)
- chore(DB): import pending files
- fix(Scripts/TempleOfAhnQiraj): Improve Princess Huhuran (#12747)
- chore(DB): import pending files
- fix(DB/Creature): Improve AQ40 Bug Tunnel (#12809)
- chore(DB): import pending files
- fix(Scripts/AhnQiraj): Anubisath Defender. (#12725)
- refactor(Scripts/Duskwood): Twilight Corrupter (#12797)
- fix(Scripts/TempleofAhnQiraj): Skeram's Arcane Explosion and Tru Fu… (#12736)
- refactor(Scripts/TempleOfAhnQiraj): Temple of Ahn Qiraj header (#12749)
- fix(Scripts/ZulGurub): Mandokir engage combat after Speaker's death (#12771)
- fix(Scripts/ZulGurub): Set timer for Ohgan's Thrash (#12772)
- fix(Core/RuinsOfAhnQiraj): Lash should not disarm (#12788)
- fix(Core/Event): Hourly bell: Dwarf horn sound should only play once (#12795)
- chore(DB): import pending files
- fix(Scripts/AhnQiraj): Spawn 3 crystals at start. (#12804)
- fix(Core/Creatures): Implemented `CREATURE_FLAG_EXTRA_DONT_CALL_ASSISTANCE` extra flag. (#12802)
- fix(Misc/Log): Info to debug learn spell (#12774)
- feat(DB): release ACDB 7.0.0 (#12811)
- chore(DB): import pending files
- fix(DB/creature_template): Remove Incorrect Loot (#12560)
- fix(DB/creature): Entry 2961 Mountain Cougar Maintenance (#12751)
- fix(DB/creature): Entry 2966 (Battleboar) Maintenance (#12765)
- fix(DB/gameobject): Update Z pos for gob guid 45150 (#12775)
- fix(DB/waypoint): Correct typo in Fingat (Guid 134237) waypoints (#12801)
- fix(DB/gossip_menu_option_locale): Populate missing entries from broadcast text (zhTW) (#12488)
- fix(DB/gossip_menu_option_locale): Populate missing entries from broadcast text (esMX) (#12483)
- fix(DB/gossip_menu_option_locale): Populate missing entries from broadcast text (frFR) (#12484)
- fix(DB/gossip_menu_option_locale): Populate missing entries from broadcast text (esES) (#12482)
- fix(DB/gossip_menu_option_locale): Populate missing entries from broadcast text (ruRU) (#12487)
- fix(DB/gossip_menu_option_locale): Populate missing entries from broadcast text (deDE) (#12481)
- fix(DB/gossip_menu_option_locale): Populate missing entries from broadcast text (koKR) (#12486)
- chore(DB): import pending files
- fix(Scripts/AhnQiraj): Obsidian Destroyer - Drain Mana. (#12723)
- fix(Core/RuinsOfAhnQiraj): Ossirian movement speed (#12706)
- chore(DB): import pending files
- fix(Scripts/AhnQiraj): Implemented General Andorov event. (#12645)
- chore(DB): import pending files
- fix(DB/SAI): [AQ20] Shrieker/Spitting Scarab improvement (#12793)

## 2022-08-19
- fix(Scripts/RuinsOfAhnQiraj): Buru full speed and gathering speed (#12796)
- ResetChatTimer no longer needed with upstream chat flood handling changes
- chore(DB): import pending files
- fix(DB/Conditions): Gordok Shackle Key should not be seen if you already… (#12792)

## 2022-08-18
- Merge branch 'azerothcore:master' into Playerbot
- Fix Evading issue
- fix(Scripts/RuinsOfAhnQiraj): re-enter the instance after Buru died (#12761)
- fix(DOCKER): remove docker db import using bash (#12773)
- fix(Scripts/RuinsOfAhnQiraj): Apply movement on Ayamiss' death (#12779)

## 2022-08-17
- feat(Core/ChatHandler/Conf): Flood Control Addon Messages (#12603)

## 2022-08-16
- Merge branch 'master' into Playerbot
- fix(Scripts/BlackwingLair): Chromaggus lever should stay open (#12758)
- chore(DB): import pending files
- fix(DB/Loot): Correct Tactical/Logistical assignment loots (#12760)
- fix(Core/Loot): Unique items shouldn't be hidden indiscriminately (#12759)
- feat(Core/BattlegroundQueue): remove queue in all group if player leave (#12731)

## 2022-08-15
- chore(DB): import pending files
- fix(Core/TempleOfAhnQiraj): Ouro rewrite (#12683)
- chore(DB): import pending files
- fix(DB/Quest): Add Aqual Quintessence questline steps. (#12707)
- chore(DB): import pending files
- fix(Scripts/RuinsOfAhnQiraj): Ossirian the Unscarred - Ossirian Crystals imp… (#12654)
- feat(Core/Debug): GetDebugInfo implementation (#12705)
- chore(DB): import pending files
- fix(DB/SAI): Zanzil zombie should not cast triggered abilities
- chore(DB): import pending files
- fix(Scripts/RuinsOfAhnQiraj): Rework Ayamiss (#12738)
- fix(Scripts/World): Emerald Dragon's Dream Fog should chase switch ta… (#12728)
- fix(Core/Mage) Water Elemental wrongly ressurected at Spirit Healer (#12684)
- chore(DB): import pending files
- fix(DB/EversongWoods): Add Jero'me weapons (#12710)
- chore(DB): import pending files
- fix(DB/EversongWoods): Fix Angershade noise spam (#12703)
- chore(DB): import pending files
- fix(DB/Creature): Corrects spawn values for creature 2955 (#12702)
- chore(DB): import pending files
- fix(DB/Gossip): Fix gossip for anachronos (#12681)

## 2022-08-14
- chore(DB): import pending files
- fix(DB/Loot): Drop condition for Silithid Carapace (#12682)
- chore(DB): import pending files
- fix(Scripts/AhnQiraj): Hive'Zara Stinger. (#12659)
- fix(DB/SAI): Qiraji Gladiator. Base on TC work. (#12719)
- fix(DB/SAI): Hive'Zara Sandstalker. (#12722)
- fix(Scripts/AhnQiraj): Anubisath Sentinel - added missing spells. (#12726)
- fix(Core/Scripting): OnAuctionSuccessful on buyout (#12732)
- chore(DB): import pending files

## 2022-08-13
- fix(Scripts/TempleOfAhnQiraj): Improve Sartura (#12577)
- fix(CI): pin boost version (#12730)
- fix(Scripts/Misc): Lower Artorius damage treshold when he damages him… (#12695)
- fix (core): Cast sub-expression to wider-type (#12430)

## 2022-08-12
- chore(DB): import pending files

## 2022-08-13
- fix(DB/EversongWoods): Add Eldinarcus Patrol (#12709)

## 2022-08-12
- chore(scripts/RuinsOfAhnQiraj): cleanup ruins_of_ahnqiraj.h (#12622)
- chore(Scripts/BlackwingLair): Another temporary solution to Chromaggu… (#12664)
- chore(DB): import pending files
- fix(DB/Quest): The Sun Gate (#12685)

## 2022-08-11
- chore(DB): import pending files
- fix(DB/Quest): fix Silithus Armament of War class condition (#12698)

## 2022-08-10
- chore(DB): import pending files

## 2022-08-09
- fix(Core/TempleOfAhnQiraj): Rewrite Fankriss (#12652)

## 2022-08-10
- fix(DB/SAI):Anubisath Defender should spawn Large Obsidian Chunk… (#12657)

## 2022-08-09
- fix(Core/RuinsOfAhnQiraj): Kurinnaxx thrash (#12680)

## 2022-08-10
- fix(Scripts/AhnQiraj): Anubisath Sentinel and Anubisath Guardian shou… (#12656)

## 2022-08-09
- chore(DB): import pending files
- fix(Scripts/RuinsOfAhnQiraj): Use proper spells to spawn Ayamiss larv… (#12665)
- update (core): Additional anticheat helper (#12692)
- chore(Core/GameObject): Clear an error that often doesn't mean anything (#12689)
- fix(Core/Commands): Achievement checkall (#12649)

## 2022-08-08
- chore(DB): import pending files
- fix(Scripts/RuinsOfAhnQiraj): Sand Vortexes should move (#12655)
- fix(Scripts/Zul'Gurub): Prevent multiple spawns of Gazhranka (#12663)

## 2022-08-07
- chore(DB): import pending files
- fix(Core): Crashfix. (#12643)
- chore(DB): import pending files
- fix(DB/Creature): remove skinning loot from several creatures (#12627)
- fix(DB): Remove scriptname wrongly assigned (#12660)
- chore(DB): import pending files
- fix(Core/BlackwingLair): add missing Nefarian Gate (#12608)
- chore(DB): import pending files
- fix(DB/Translations): City guard gossips (#12436)
- chore(Core/DBCEnums): Define SummonPropGroup/Flags enums (#12648)
- fix(Core/SmartScripts): Fixed `SMART_TARGET_OWNER_OR_SUMMONER` target. (#12644)
- fix(Scripts/RuinsOfAhnQiraj): Increased aggro range for Kurinnaxx. (#12646)
- chore(DB): import pending files
- fix(DB/SAI): Colonel Zerran (15385) Enlarge spell mechanics (#12636)
- chore(DB): import pending files
- fix(DB/formations): Add formations to AQ20 zone The Hatchery (#12635)
- chore(DB): import pending files
- fix(DB/SAI): Spell timers for Hive'Zara Tail Lasher and Hive'Zara Collectors (#12631)
- chore(DB): import pending files
- fix(Scripts/RuinsOfAhnQiraj): Fixed crystal activation animation. (#12647)
- chore(CI): remove ubuntu-18.04 (#12650)

## 2022-08-06
- chore(DB): import pending files
- fix(Scripts/RuinsOfAhnQiraj): Implement Rajaxx waves gear check (#12552)

## 2022-08-05
- chore(CI): remove macos-10.15 (#12642)

## 2022-08-06
- fix(Core/Spells): Fixed Druid T3 8P bonus. (#12598)

## 2022-08-05
- update (core): Knock Back Helpers (#12639)

## 2022-08-06
- chore(DB): import pending files
- fix(DB/Spells): Fixed Hunter T3 4P bonus. (#12597)
- fix(Core/Spells): Volley should suspend auto-shot. (#12596)
- fix(Scripts/Spells): Readiness should remove all spell category coold… (#12595)

## 2022-08-05
- refactor(Core/Scripts): Move AQ scripts to new scripting system (#12623)
- chore(DB): import pending files
- fix(Core/SAI): Unused parameters warnings (#12620)
- fix(Core/TempleOfAhnQiraj): Bug Trio (#12599)

## 2022-08-06
- fix(Core/AI): correct Permit level for trigger flagged creatures (#12614)

## 2022-08-05
- feat(Core/Utilities): add event emitter class (#12632)

## 2022-08-03
- update (source): Establish chapter 3 dk script (#12549)
- fix(Core): Freeze on Lord Jaraxxus (#12616)
- fix(Core/Scripts): Ayamiss crashfix (#12610)
- fix(Core): Crash on Mandokir gaze (#12611)
- fix(Core/Spells): Crashfix (#12609)

## 2022-08-02
- chore(DB): import pending files
- fix(Core/Movement): Improvements to taxi flight movement generator: (#12347)

## 2022-08-01
- chore(DB): import pending files
- fix(Core/RuinsOfAhnQiraj): Ossirian Crystals: Weakness spells (#12547)
- chore(DB): import pending files
- fix(DB/RuinsOfAhnQiraj): add missing SAI for some creatures (#12602)
- fix(Scripts/Spells): Fixed T3 6P Frostfire Regalia bonus not proccing. (#12585)
- chore(DB): import pending files
- fix(DB/Creature): ZG Formations: Before Bats cont. Troll 3-pack (#12511)
- chore(DB): import pending files
- fix(DB/Spells): Hive'Zara Tail Lasher's Tail Lash (#12601)
- fix(Scripts/Spells): Fixed T3 4P Frostfire Regalia bonus not proccing. (#12583)
- fix(Core/SmartScripts): Fixed `SMART_ACTION_START_FOLLOW` not complet… (#12580)
- chore(DB): import pending files
- fix(DB/Creature): Make Nefarian's Troops invisible (#12572)
- chore(DB): import pending files
- fix(DB/Creature): Add Black Bear Pack northwest of the Ironforge Airfield. (#12564)
- chore(DB): import pending files
- fix(DB/ZulGurub): Hakkari Witchdoctor SAI (#12529)
- chore(DB): import pending files
- fix(DB/Formations): ZG: Creature formations before bat area (#12523)
- chore(DB): import pending files
- fix(DB/Creature): Npc 1568 spawn position (#12519)
- chore(DB): import pending files
- fix(DB/Creature): Set wander_distance for creatures 21773, 21774, 21775 (#12514)
- fix(Scripts/Spells): Properly handle spellclick flag for Lightwell. (#12505)
- chore(DB): import pending files
- fix(DB/Creature): ZG Formations: Aggro on pack (#12494)
- chore(DB): import pending files
- fix(DB/Creature): Continued ZG Before Bats work (Pools - Formations) (#12493)
- chore(DB): import pending files
- fix(DB): Restore Goodsteel Ledger (#12492)
- chore(DB): import pending files
- fix(DB): Sprinkle's Secret Ingredient Outro Event (#12491)
- chore(DB): import pending files
- fix(DB/gossip_menu_option): Correct Marin Noggenfogger text (#12490)
- chore(DB): import pending files
- fix(DB/Gameobject): Ghost Mushroom Position (#12382)
- chore(DB): import pending files

## 2022-08-02
- fix(DB/creature): Felannia, Zebig and Brumman should have a gossip (#12360)

## 2022-08-01
- chore(DB): import pending files
- fix(DB/Creature): Deliana and other npcs spawn time (#12600)
- chore(DB): import pending files
- fix(DB/Creature): Update Z position for Ghostpaw Runner (GUID: 34977) (#12555)
- fix(Core/Services): Re-check all achievement criterias on faction cha… (#12582)
- fix(Core): Crashfix on loot roll (#12605)

## 2022-07-31
- chore(DB): import pending files
- fix(DB): Script To Serve Kum'isha End Event (#12480)
- chore(DB): import pending files
- fix(DB/creature): correct movement type on a couple snakes (ZG Entrance 3) (#12441)
- chore(DB): import pending files
- fix(DB/quest_greeting): Fix Chief Hawkwind quest_greeting (#12377)
- fix(Scripts/RuinsOfAhnQiraj): Despawn Ayamiss summons on death/reset (#12550)
- fix(Core): Crashfix. (#12594)
- fix(Scripts/Mail) Fix faction server mail rewards. (#12593)

## 2022-07-30
- fix(Core): Crashfix. (#12581)

## 2022-07-29
- chore(DB): import pending files
- fix(DB/Loot): emerald dragons should skin dreamscale (#12569)
- fix(Scripts/EmeraldDragons): fix summon player spam (#12573)

## 2022-07-28
- fix(Scripts/RuinsOfAhnQiraj): Limit Moan's mana drain to 6 targets (#12551)

## 2022-07-27
- Update to work with latest AzerothCore master
- Merge branch 'Playerbot' of https://github.com/ZhengPeiRu21/azerothcore-wotlk into Playerbot
- Merge branch 'master' into Playerbot
- chore(DB): import pending files
- fix(DB/Formations): ZG Trash Formations (#12533)
- chore(DB): import pending files
- fix(DB/Spells): Greater Heal spell from 8P T2 Priest set should scale… (#12504)
- fix(DB/SAI): Hive Wasp should target 3 people every cast (#12557)
- fix(DB/SAI): Destroyer should have 0 mana on repull (#12558)
- chore(DB): import pending files
- fix(Scripts/RuinsOfAhnQiraj): Ossirian reset (#12548)

## 2022-07-26
- fix(DB/Update): Fix update 2022_07_26_04.sql (#12553)

## 2022-07-27
- feat(Core): Add OnGroupRollRewardItem hook. (#12538)

## 2022-07-26
- chore(DB): import pending files

## 2022-07-27
- fix(DB/SAI): Shadowfang Keep: improve Arugal intro script (#12405)

## 2022-07-26
- chore(DB): import pending files
- fix(DB/Pathing): Missing Durotar Pathing (#12373)
- fix(Scripts/TempleOfAhnQiraj): Clear Eye of C'thun scheduler during p… (#12545)
- chore(DB): import pending files
- fix(Scripts/RuinsOfAhnQiraj): Improve Ayamiss (#12143)
- chore(DB): import pending files
- fix(Core/RuinsOfAhnQiraj): Buru (#12524)
- chore(DB): import pending files
- fix(Scripts/RuinsOfAhnQiraj): Rewrite Moam (#12539)
- refactor(Core/RuinsOfAhnQiraj): Ossirian (#12541)
- chore(DB): import pending files
- fix(DB/Creature): Deadwood Shaman, Avengers, Den Watchers, should not… (#12456)
- chore(DB): import pending files

## 2022-07-25
- fix(Scripts/RuinsOfAhnQiraj): Improve Moam (#12142)
- chore(DB): import pending files
- fix(Scripts/RuinsOfAhnQiraj): Script Anubisath Guardians (#12537)
- chore(DB): import pending files
- fix(Scripts/RuinsOfAhnQiraj): Improve Ossirian (#12138)
- fix(Core/Spells): Make sure that attacker is always in combat with it… (#12516)
- fix(Core/Spells): Lightning Shield should not proc off from self-cast… (#12501)
- fix(Scripts/RuinsOfAhnQiraj): Moam should spawn a Large Obsidian Chun… (#12536)
- chore(DB): import pending files
- fix(DB/SAI): AQ20 Trash improvements (#12528)
- chore(DB): import pending files
- fix(Scripts/Spells): Script spell Itch (AQ20) and improve Consume (AQ20) (#12502)
- refactor(Scripts/TempleOfAhnQiraj): Remove Giant Flesh Claw script as… (#12526)
- feat(Core/Creature): Implement SetRegeneratingPower() to disable powe… (#12535)
- fix(Scripts/RuinsOfAhnQiraj): Implement Rajaxx waves (#12513)
- chore(DB): import pending files
- fix(DB/Formations): Scarab formations AQ20 (#12530)
- chore(DB): import pending files
- fix(DB/Formations): Qiraji Gladiator should be linked together (#12531)
- chore(DB): import pending files
- fix(DB/SAI): Fixed completing quest "Into The Realm of Shadows" (#12515)
- chore(Scripts): remove double method calling for ZG script (#12517)

## 2022-07-24
- chore(DB): import pending files
- fix(Core/RuinsOfAhnQiraj): Kurinnaxx (#12522)
- chore(DB): import pending files
- fix(scripts/RuinsOfAhnQiraj): Improve Buru (#12141)
- chore(DB): import pending files
- fix(DB/SAI): Zulian Crocolisk has scripted movement (#12460)
- fix(Core): Instance Reset Exploit Fix (#12459)
- chore(DB): import pending files
- fix(Core/Spells): Elemental Mastery should only affect Lightning Bolt… (#12499)
- chore(Cleanup): Merge redundant `if` in Totem::Update() (#12423)
- chore(DB): import pending files
- fix(Scripts/Spells): Glyph of Felguard. (#12497)
- chore(DB): import pending files
- fix(DB/SAI): Script Warmaul Chef Bufferlo (#12378)
- fix(Core/Pets): Warlock should not be refunded with Soul Shard on log… (#12409)
- chore(DB): import pending files
- fix(DB/Loot): Cannon Master Willey (10997) (#12476)
- fix(Core/Creatures): Added new AI function `OnTeleportUnreacheablePlayer` to teleport all unreachable players. (#12193)
- chore(DB): import pending files
- fix(Core): Crash on smart event: near players (#12479)
- fix(Core/AI): validate stored targets (#12489)
- fix(Scripts/Spells): Replenishment should trigger only from Mind Blast. (#12503)
- fix(DB/Creature): Moontouched Owlbeast (7453) (#12344)

## 2022-07-23
- chore(DB): import pending files
- feat(Core/Entities): Enabled loading basic stats for players, pets an… (#12394)
- chore(DB): import pending files
- fix(DB/SAI): Sunhawk Reclaimer should not cast Frost Ar… (#12450)

## 2022-07-22
- fix(Core): SMART_ACTION_SET_HOME_POS should accept a parameter (#12468)
- chore(DB): import pending files
- fix(DB/Loot): Abyssal Crest (20513) (#12477)

## 2022-07-21
- Merge pull request #5 from KobaltBlu/Playerbot
- Merge branch 'azerothcore:master' into Playerbot

## 2022-07-20
- chore(DB): import pending files
- fix(DB/SAI): AQ20 Trash scripts (#12444)
- chore(DB): import pending files
- fix(Scripts/RuinsOfAhnQiraj): Improve Kurinnaxx (#12136)
- chore(DB): import pending files

## 2022-07-21
- fix(DB/Quest): Slim Pickings (#12359)

## 2022-07-20
- chore(DB): import pending files
- fix(Scripts\TempleOfAhnQiraj): C'thun should aggro as soon as you eit… (#12429)
- fix(Scripts\TempleOfAnhQiraj): Fix Huhuran`s Wyvern Sting dealing no … (#12445)
- fix(Scripts/TempleOfAhnQiraj): Correct Fankriss Mortal Wound spell ID (#12443)
- chore(DB): import pending files
- fix(Scripts\Spells): Consume (AQ) (#12448)
- chore(DB): import pending files
- fix(DB/Creature): ZG Before Bats Area Improvements (#12442)
- fix(DB/SAI): Flamewaker Protector should not cast domi… (#12454)
- fix(Scripts\TempleOfAhnQiraj): Fix Skeram images not spawning if he's… (#12428)
- fix(Scripts/ZulGurub): Adjust Arlokk timers (#12458)
- chore(DB): import pending files
- fix(DB/SAI): Skeletal Horror should cast Terrify at top threat target (#12452)
- chore(DB): import pending files
- fix(DB/Creature): Remorseful Highborne (#12374)
- fix(DB/Quest): Boiling Point. (#12407)
- chore(DB): import pending files
- fix(DB/SAI): Skeletal terror should not cast Altered C… (#12451)
- fix(DB/SAI): Cauldron Lord Razarch smartscripts (#12453)
- fix: illegal instruction error in Creature.cpp:3470
- chore(DB): import pending files

## 2022-07-19
- feat(Core/Commands): Introduce .npc guid (#12440)

## 2022-07-20
- chore(DB): import pending files

## 2022-07-19
- fix(DB/Creature): Rocklance waypoints and formation. (#12322)

## 2022-07-20
- chore(DB): import pending files
- fix(DB/Event): Shadowfang Keep: link objects and npcs to event (#12404)
- chore(DB): import pending files

## 2022-07-19
- fix(DB/Pathing): Add missing waypoints to Somnus (12900) (#12321)
- chore(DB): import pending files
- fix(db/creature): ZG entrance creature improvement, part 2 (#12371)
- chore(DB): import pending files
- fix(DB/Spells): Zandalarian Hero Charm trinket should drop off stacks… (#12406)
- fix(Core/Spells): Upon using charge warrior should start auto attacki… (#12408)
- chore(DB): import pending files
- fix(Core/AI): more AI factory checks (#12402)
- chore(DB): import pending files
- fix(Scripts/ZulGurub): Improvements to Jindo the Hexxer (#12395)
- fix(Scripts/ZulGurub): Threat caused by `SPELL_AURA_DAMAGE_SHIELD` au… (#12398)
- chore(DB): import pending files
- Merge pull request #4 from KobaltBlu/Playerbot
- fix(Scripts/ZulGurub): Corrected timers on Arlokk. (#12397)

## 2022-07-18
- chore(DB): import pending files
- fix(DB/Loot): Cuergo's Hidden Treasure (9265) (#12283)
- fix(DB/Creature): Rookery Whelps should not give XP. (#12426)
- refactor(Core/SmartScripts): GetTargets returns ObjectList instead of ObjectList* (#11950)

## 2022-07-16
- fix: remove WorldFloatConfigs[CONFIG_WATER_BREATH_TIMER]

## 2022-07-15
- refactor(Core/AI): factory functions cleanup  (#11779)

## 2022-07-13
- chore(DB): import pending files
- fix(DB/creature template): Adjust Whitewhisker/Irondeep NPCs in Alterac Valley (#12309)
- fix(Core): Fix indexing in UpdatePlayerSetting (#12375)
- Merge branch 'Playerbot' of https://github.com/ZhengPeiRu21/azerothcore-wotlk into Playerbot
- Merge branch 'master' into Playerbot

## 2022-07-12
- chore(DB): import pending files
- fix(DB/Creature): Zul'Gurub entrance creature improvements (#12367)
- fix(Scripts/World): Ysondre - Spawn adds should scale with raid size v2 (Source: VMangos) (#12368)
- chore(DB): import pending files
- fix(DB/Creature): Emeriss should not give reputation on kill (#12357)

## 2022-07-11
- feat(Core/Scripting): Add several UnitHooks (#12365)
- chore(DB): import pending files
- fix(DB/SAI): Fixes starting waypoint movement during "I Sense a Distu… (#12350)
- feat(Core): add OnDisplayId hook (#12320)

## 2022-07-10
- update (core): Clean Up SendGMText (#12317)
- fix(Scripts/ZulGurub): fix Thekal not dying in phase 2  (#12353)
- chore(DB): import pending files
- fix(DB/SAI): Fixed summoning friendly NPCs during quest "The Air Stan… (#12349)
- chore(DB): import pending files
- fix(DB/Pathing): Missing Elwynn Forest Pathing (#12313)
- chore(DB): import pending files
- fix(Scripts/World): Prevent Taerar to be untargetable on death (#12351)
- refactor(Core): Improve struct alignment and codestyle (#12335)
- fix(Core/Spells): Fixed LoS problems with hunter traps. (#12348)
- fix(DB/Pathing): Missing Westfall Pathing (#12312)
- fix(DB/Creature): Removed permanent root from Nergeld. (#12291)
- chore(DB): import pending files
- feat(Core/Config): Configurable Water Breath Timer (#11945)
- fix(DB/Locale): Creature: Nayura (#11355)

## 2022-07-09
- chore(DB): import pending files
- fix(Core/ZulGurub): Jin'do the Hexxer rewrite (#12233)
- chore(DB): import pending files
- fix(DB/creature): More ZulGurub pathing (#12334)
- chore(DB): import pending files
- fix(Core/ZulGurub): Hakkar hardmode (#12333)
- chore(DB): import pending files
- fix(Scripts/ZulGurub): Added more missing areatrigger whispers (#12326)
- fix(Scripts/ZulGurub): Prevent from summoning multiple Edge of Madnes… (#12331)
- chore(DB): import pending files
- fix(DB/GameObject): Dark Iron deposit respawn time (#12319)
- chore(DB): import pending files
- fix(DB/GameObjects): Improve ZG Mining Spawns (#12314)
- chore(DB): import pending files
- fix(Scripts/ZulGurub): Added missing yell on Hakkar's evade. (#12329)
- fix(Scripts/ZulGurub): Added Sweeping Strikes to Gri'lek encounter (#12328)
- fix(Scripts/Zulgurub): Hakkar should cast Insanity only if there are … (#12325)
- chore(DB): import pending files
- fix(DB/Creature): Zul'Gurub Patrols part 2 (#12304)
- chore(DB): import pending files
- fix(DB/GameObjects): Improve ZG Herbalism spawns (#12307)
- chore(DB): import pending files
- fix(DB/ZulGurub): Hoodoo Piles should not melee atack their targets. (#12269)
- chore(DB): import pending files
- fix(Scripts/ZulGurub): Hakkar's Blood Siphon (#12196)
- feat(Core/Scripting): Implement OnAllowedForPlayerLootCheck() hook (#12316)

## 2022-07-07
- chore(DB): import pending files
- fix(Core): Implement ACHIEVEMENT_CRITERIA_DATA_TYPE_S_ITEM_QUALITY (#12246)
- fix(Core): Fix Achievement Packets (#12255)

## 2022-07-06
- Merge branch 'azerothcore:master' into Playerbot
- fix(Core/Gossips): Properly send packet with questgiver query handler. (#12290)
- chore(DB): import pending files
- feat(Core/Commands): Debug Spell Visuals Command (#12216)

## 2022-07-05
- chore(DB): import pending files
- fix(DB/Achievements): Critters Killed statistic (#12306)
- fix(DB): Remove `acore.world` from 2022_07_05_00.sql (#12305)
- Merge branch 'azerothcore:master' into Playerbot
- chore(DB): import pending files
- fix(DB/waypoint): Alshirr Banebreath (14340) (#12256)
- fix(DB/Quest): Fixed Tatjana's Horse not moving to final destination. (#12251)

## 2022-07-03
- chore(DB): import pending files
- fix(DB/Creature): Silithid Swarm remove gold drop (#12262)
- chore(DB): import pending files
- fix(DB/SAI): Heb'Jin should not evade on attack. Source: TrinityCore. (#12270)
- fix(Core/Combat): Removed `UNIT_FLAG_IMMUNE_TO_PC` when entering comb… (#12288)
- fix (db): Graveyard Horde Teldrassil (#12278)
- fix(DB/SAI): Fixed completing quest "What Book? I Don't See Any Book" (#12289)
- chore(DB): import pending files
- fix(Core/SmartScripts): Added option to override current running time… (#12298)
- fix(Core/Spells): Smash Mammoth Trap should open Mammoth Calf's trap. (#12295)
- chore(DB): import pending files
- fix(DB/SAI): Fixed Blight Geist not collecting crystal while being ch… (#12292)
- chore(DB): import pending files
- fix(DB/SAI): Plague Cauldron Target should remove all auras on event … (#12294)
- fix(Core): Crashfix. (#12296)
- fix(Core/Spells): Place Fake Fur should activate Caribou Trap. (#12297)
- chore(DB): import pending files
- fix(DB/SAI): Fixed completing "Iron Rune Constructs and You: The Bluf… (#12299)

## 2022-07-02
- chore(DB): import pending files
- Script/Spell: fix Midsummer's Juggling Torch (#12198)
- chore(DB): import pending files
- fix(DB/Quest): Fixed getting kill credit for quest "A Delicate Touch" (#12272)
- chore(DB): import pending files
- fix(Scripts/ZulGurub): Thekal improvements (#12238)
- feat(Core/Scripts): Added Boundary in Azjol nerub (#12159)

## 2022-07-01
- chore(DB): import pending files
- fix(DB/Creature) Add CTM to 4 flying creatures (#12182)
- fix(Scripts): Midsummer Music Range (#12248)
- chore(DB): import pending files
- fix(Core/ZulGurub): Hazza'rah improvements (#12236)
- Merge branch 'azerothcore:master' into Playerbot
- chore(DB): import pending files
- fix(DB/Scripts): Greater Windstone Bosses (#12247)
- chore(DB): import pending files
- fix(DB/ZulGurub): Remove taunt immunity from Mar'li (#12234)
- Fix command .skirmish (#12149)
- feat(Core/Command): Deserter Command send feedback (#11958)

## 2022-06-30
- chore(DB): import pending files
- fix(scripts/Ragnaros): Move root handling from DB to Core (#12245)
- Merge branch 'azerothcore:master' into Playerbot

## 2022-06-29
- chore(DB): import pending files
- fix(DB/creature): Add missing rare The Behemoth (#12232)
- fix(DB): Daggerspine Marauder loot (#12231)
- fix(DB/quest_offer_reward): Food for Baby and Becoming a Parent gender text (#12230)
- fix(DB/creature_template): Cenarion Emissary Jademoon Cata Gossip (#12229)
- fix(DB/Scripts): Furlbrow RP Text (#12228)

## 2022-06-30
- fix(DB/Quest): Fixed Ducal's Horse not moving to final destination. (#12223)

## 2022-06-29
- fix(Core): Crashfix. (#12184)

## 2022-06-28
- chore(DB): import pending files
- fix(DB/Creature): Make Skullsplitter Hunter and Panther more in line with other creatures with summoned pets (#12199)
- fix(DB/Creature): Dawnblade Hawkrider SmartAI fix (#12192)
- fix(DB/Creature): The Ancient Hero SmartAI fix (#12191)
- chore(DB): import pending files
- fix(Core/Spells): Removed any triggered auras on glyph removal. (#12168)
- fix(DB/waypoint): ZG pathing and formations (#12146)
- fix(Scripts): Brazier of Dancing Flames should dance when spawned (#12156)
- chore(DB): import pending files

## 2022-06-29
- fix(DB/creature) first aid trainer (#11980)

## 2022-06-28
- fix(DB/Quest): Quest An Undead's best friend (#11933)

## 2022-06-27
- Merge branch 'azerothcore:master' into Playerbot
- chore(DB): import pending files
- fix(Scripts/ZulGurub): Corrected Hakkar speeches at the very start of… (#12200)
- fix(DB/Quest): Strengthen the Ancients (#12125)

## 2022-06-26
- fix(Scripts/ZulGurub): Gri'lek should pursuit random targets. (#12194)
- fix(Scripts/ZulGurub): Arlokk's Panthers should attack players. (#12185)
- chore(DB): import pending files
- fix(Scripts/ZulGurub): Mandokir's Threatening Gaze. (#12095)
- fix(Core): Crashfix. (#11903)
- fix(DB/Creature): Disable Ragnaros movement (#12022)
- fix(Scripts/ZulGurub): Fixed never-ending Thousand Blades during Rena… (#12105)
- fix(Scripts/ZulGurub): Priestess Jeklik intro (#12109)
- fix(Core/ZulGurub): Hakkar improvements (#12134)
- fix(Core/Spells): Fixed cooldowns on shaman totems. (#12166)
- feat(Core/Scripts): Added Boundary in Obsidian sanctum (#12158)
- fix(Core/ZulGurub): Arlokk reset behaviour (#12154)
- fix(Scripts/BlackwingLair): Correct Bone Constructs abilities (#12180)
- fix(DB/quest_offer_reward): Balance of Light and Shadow Reward Text (#12155)
- fix(Core/LFG): Fixed joining seasonal bosses if only `LFG_OPTION_ENAB… (#12163)
- fix(Core/Units): Fixed problems with charming non-demon creatures by … (#12164)
- fix(Core/Spells): Shaman T10 4Set bonus should properly extend Flame … (#12167)

## 2022-06-24
- Merge branch 'azerothcore:master' into Playerbot
- fix(core): Npc gossip error logging (#11999)
- feat(Core/Scripts): Added Boundary in Forge of Souls (#11798)

## 2022-06-23
- fix(Scripts/BlackwingLair): Nefarian class calls should not repeat (#12148)

## 2022-06-22
- chore(DB): import pending files
- feat(Core/Command): Deserter rm all time parameter (#11963)
- chore(DB): import pending files
- fix(Scripts/ZulGurub): Venoxis - Holy wrath and Holy nova event (#12089)
- fix(DB/Creature): Son of Hakkar Improvements (#12119)
- fix(Core/Spells): Sleep aura from Magic Dust should be removed if tar… (#12020)
- chore(DB): import pending files
- fix(DB/gameobject): move three objects Half-Buried Bottle (2560) abov… (#12103)
- chore(DB): import pending files
- fix(DB/SmartScript): Gurubashi Blood Drinker should cast Blood Leech … (#12121)

## 2022-06-21
- chore(DB): import pending files

## 2022-06-22
- fix(DB/Spells): Intercept should not bypass Deterrence. (#12113)

## 2022-06-21
- chore(DB): import pending files
- fix(DB/Events): Midsummer festival cataclysm spawn (#12129)

## 2022-06-22
- chore(Dashboard/functions.sh): update data version (#12140)

## 2022-06-21
- update (app) Extractor.bat update (#12139)
- Fix merge conflicts
- Merge branch 'master' of https://github.com/ZhengPeiRu21/azerothcore-wotlk into Playerbot
- fix(Core/Tools): Revert "Handle different slopes in  mmaps and Add so… (#12111)
- fix(Core/Groups): Level restriction on allowing raid groups (#12110)
- Merge branch 'master' of https://github.com/ZhengPeiRu21/azerothcore-wotlk into Playerbot
- chore(DB): import pending files
- feat(Core/Formations): Implement GROUP_AI_FLAG_DONT_RESPAWN_LEADER_ON… (#12128)

## 2022-06-20
- fix(Core/Movement): Water-bound creatures should not evade if their t… (#12112)
- chore(cleanup): Excessive line breaks removal. (#12126)
- fix(Scripts/UtgardePinnacle): Svala Sorrowgrave's sacrifice should o… (#12069)

## 2022-06-19
- chore(DB): import pending files
- fix(Core/ZulGurub): Mandokir charge and chained spirits (#12072)
- fix(Core/Professions): Players should be able to update gathering ski… (#12033)
- fix(Core/Pets): Mob "soloed" by pet should not grant exp/loot to its … (#11969)

## 2022-06-18
- fix(Scripts/ZulGurub): Improvements to Madonkir's melee spells. (#12096)
- feat(Core/Players): Enabled resurrecting players from opposite factio… (#12012)
- fix (core): value of the MAX_ARENA_SLOT const
- fix(Core/Items): Special bags cannot be stored inside other special b… (#12032)
- fix(Core/Spells): Fixed calculating LoS for dynamic objects. (#12090)
- fix(Core/Spells): Fixed calculating LoS checks for spells casted by g… (#12091)
- fix(Core): Crashfix. (#12093)
- chore(DB): import pending files
- fix(DB/Creature): Nightmare Illusion should be aoe immune (#12087)
- fix(DB/gameobject): Overhaul of Gameobject 106318 in Mulgore (#12071)
- fix(DB/Smartscripts): Gazban smartAI (#12062)
- (DB/loot): Addressed drop style to be proper for Fire Hardened Mail (#12060)
- chore(DB): import pending files
- fix(DB/quest_template): Update (#11394)
- fix(Core): Crashfix. (#12092)
- fix(DB/smartscripts): Gurubashi Axe Thrower should cast Axe Flurry (#12085)
- fix:(DB/Creature): Molten Core elementals should bleed. (#12074)
- chore(DB): import pending files
- fix(Scripts/TempleofAhnQiraj): improve C'thun's script a bit and repl… (#12067)
- fix(DB/creature_template): Fix Domesticated Felboar (#12057)
- chore(DB): import pending files
- fix(DB): Brontus spawn and pathing behaviors corrected (#12052)
- Fix(DB/Smartscripts): Rot Hide Plague Weavers incorrectly stay at range (#12027)
- Fix(DB/Loot): Tobacco should not be in chest (#12026)
- chore(DB): import pending files
- Fix(DB/smartscripts): Call of Water(5/6)(draenei) improvements (#12025)
- Fix(DB/Quest): "Burning Blood", "Iron Coal" and "Sunscorched Shells" … (#12024)
- Fix:(DB/Creature): Threshwackonator missing gossip (#12023)
- fix(DB/SAI): Removed one invalid action for Scarlet Warder. (#12014)
- refactor(Core/Unit): PC&NPC Immunity (#11986)

## 2022-06-16
- Merge branch 'Playerbot' of https://github.com/ZhengPeiRu21/azerothcore-wotlk into Playerbot
- Merge branch 'breathTimerConfig' into Playerbot
- Merge branch 'azerothcore:master' into Playerbot
- chore(DB): import pending files
- fix(DB/SAI): Son of Hakkar - Poison cloud (#12036)
- chore(DB): import pending files
- Fix(DB/Creature): Spirit Shade should be immune to AOE (#12044)
- chore(DB): import pending files
- fix(Scripts/ZulGurub): Fixed spawning Edge of Madness bosses. (#11957)
- chore(DB): import pending files
- Fix(DB/Creature): Zul'Gurub boss damage (#11977)
- fix(Scripts/ZulGurub): Renataki - improvements: (#11967)
- chore(DB): import pending files
- Fix(DB/Creature): Kroshius should be targetable. (#12043)
- fix(Core/Units): Fixed restoring running movement flag after charm. Source: TrinityCore (#12019)
- fix(DB/creature_template): Hide 'Flame of Ragnaros' (#12040)
- fix(DB/QuestTemplate): Mission Accomplished! sent correct mail to player (#12055)
- fix(DB/Smartscripts): Darnassian hunter should melee when closed range (#12056)

## 2022-06-15
- chore(DB): import pending files
- fix(Scripts/EmeraldDragons): Lethon should use shadow bolt whirl (#12045)
- chore(DB): import pending files
- fix(DB/Loot): Increase the drop rate of Ritual Salve (#11906)
- chore(DB): import pending files
- fix(Core/Item): Fix TrinketUpdate (#11571)

## 2022-06-14
- chore(DB): import pending files

## 2022-06-15
- fix(DB/SAI): Private Hendel should despawn on player dead/reset (#12051)

## 2022-06-14
- chore(DB): import pending files

## 2022-06-15
- fix(Scripts/Spells): Shadowburn should give Sould Shard only if targe… (#12030)

## 2022-06-14
- fix(Scripts/Azuregos): mark of frost should be removed on reset (#12053)
- chore(DB): import pending files
- fix(DB/Spells): Added Earth Shock/Icy Chill enchantment to spell stac… (#12031)
- chore(DB): import pending files
- fix(DB/Creature): ZulGurub - Mad Servant (15111) (#12034)
- fix(Scripts/TempleOfAhnQiraj): Rewrite C'thun tentacles (#12047)
- chore(DB): import pending files
- Fix(Creature/AI): Mirveda's summoned creatures should despawn out of … (#11951)
- chore(DB): import pending files
- fix(DB/Creature) Tarindrella movement type (#11802)
- chore(DB): import pending files
- fix(Scripts/ZulGurub): Improvements to Gah'zranka: (#11908)
- chore(DB): import pending files

## 2022-06-13
- fix(Core/Spells): Implement SPELL_EFFECT_ACTIVATE_OBJECT (#11648)

## 2022-06-14
- chore(DB): import pending files
- fix(Scripts/ZulGurub): Fixed Jindo's Brain Wash Totem. (#11839)
- fix(Scripts/ZulGurub): Improvements to Hazzarah encounter (#11964)

## 2022-06-13
- chore(DB): import pending files
- fix(Core/ZG): Multiple improvements to High Priestess Mar'li (#11647)

## 2022-06-14
- refactor(Core/Unit): minor changes for the combat system (#11904)

## 2022-06-13
- Merge branch 'azerothcore:master' into Playerbot
- chore(DB): import pending files
- fix(DB/factionchange_items): Adding missing 58 pvp faction change items (#12049)
- chore(DB): import pending files
- feat(Core/Command): Use timestring with all commands (#12050)
- fix(Scripts/ZulGurub): Wushoolay - improvements: (#11968)
- fix(Scripts/BRD): Emperor should not yell when dead. (#12046)
- fix(Core): Deserter overrides from BG and Command (#11961)
- chore: restore googletest main repo reference (#12011)
- fix(Core/Misc): Fixed radius of areatriggers in battlegrounds. (#12017)
- chore(DB): import pending files
- fix(scripts/ZulGurub): Rewrite Broodlord Mandokir and Ohgan (#11854)
- chore(DB): import pending files
- fix(Scripts/World): Fix Emeriss putrid mushrooms not doing anything (#12035)
- chore(DB): import pending files
- fix(Core/Objects): Include combat reach instead of object size in LoS… (#12013)

## 2022-06-12
- fix(Scripts/EmeraldDragons): Emerald dragons should 'enrage' at health per… (#12029)

## 2022-06-11
- chore(DB): import pending files

## 2022-06-12
- fix(db/translation): Chinese translation of road signs (#11981)

## 2022-06-10
- Merge branch 'azerothcore:master' into Playerbot

## 2022-06-09
- chore(DB): import pending files

## 2022-06-10
- fix(Scripts/ZulGurub): Fixed Edge of Madness tablets. (#11959)
- fix(Scripts/ZulGurub): Gah'zranka's Slam should reset threat. (#11910)

## 2022-06-09
- feat(Tools/DbImport): implement separated app for importing DB (#11614)

## 2022-06-08
- Merge branch 'azerothcore:master' into Playerbot
- chore(DB): import pending files
- fix(Script/Quest): Mystery of the Infinite minor adjustments & zone_dragonblight move to db from hardcode (#11810)
- fix(Conf): Modules should compile (#11983)
- chore(DB): import pending files
- Fix(DB/Loot): Evergreen Herb Casing should not drop random herbs (#11952)
- fix(Core/Spell): Fixed Divine Shield not granting immunity to spell s… (#11954)
- chore(DB): import pending files

## 2022-06-07
- fix(DB/pathing): Dun Morogh Missing Pathing (#11923)

## 2022-06-08
- fix(Core): Crashfix. (#11956)

## 2022-06-06
- fix(Scripts/ZulGurub): Update Gahzranka's abilities (#11849)
- refactor: remove useless ternary operator (#11907)
- chore(DB): import pending files
- fix(Scripts/ZulGurub): Shade of Jin'do's invisibility aura should not… (#11838)
- fix(Script/Instance): Ulduar - Fix Keeper's missing gossips and remove hardcode (#11831)
- fix(Scripts/ZulGurub): Fixed Jindo's Healing Ward Totem. (#11841)
- chore(DB): import pending files
- fix(Scripts/ZulGurub): Rewrite High Priest Thekal (#11784)
- fix(Core/Movement): Improved fleeing movement generator. (#11896)
- chore(DB): import pending files
- fix(Script/Instance): Ulduar - Flame Leviathan Hardcore to DB (#11879)
- fix(DB/Loot): Abyssal Lord should only drop 1 rare/epic (#11953)
- fix(Core/Spells): Hunter traps should not be activated by targets not… (#11971)
- fix(Script/Creature): Scarlet Commander Mograine - Pull entire cathedral and fix mob fleeing into him (#11766)
- fix(DB/SAI): Do not summon King Jokkum vehicle if player is mounted. (#11895)
- fix(Core/Spells): Properly handle SPELL_MOD_THREAT flat spell mods. (#11911)
- chore(DB): import pending files
- fix(Scripts/ZulGurub): Improvements to Gri'lek encounter: (#11960)

## 2022-06-04
- fix(Scripts/Paladin): infusion of light proc (#11935)
- chore(DB): import pending files

## 2022-06-03
- fix(DB/pathing): Badlands Missing Pathing (#11324)
- feat(Core/Config): Configurable Water Breath Timer
- Merge branch 'azerothcore:master' into Playerbot
- chore(DB): import pending files
- fix(Core/ZulGurub): more improvements to High Priestess Jeklik (#11604)
- fix(DB/Item): Fix ProcChance of Charred Twillight Scale Trinket (#11487)

## 2022-06-02
- chore(DB): import pending files
- fix (Conditions): Loh'atu gossip (#11922)
- chore(DB): import pending files
- feat(Core/Commands): deserter command offline & using targets & console support (#11921)

## 2022-05-31
- Merge branch 'master' into Playerbot
- refactor(Cmake): add support build selected applications and tools (#11836)
- refactor(Core/Instances): Update CHAR_DELETE_INSTANCE_SAVED_DATA (#11866)

## 2022-05-30
- chore(DB): import pending files
- fix(DB/Loot): Zul'Gurub boss loot (#11844)
- fix(Core): Crashfix. (#11898)
- fix(Scripts/ZulGurub): Jindo cannot attack targets affected by Hex. (#11837)
- chore(DB): import pending files
- fix(DB/Creature): Leviathan Mk II's Plasma Blast BroadcastTextId (#11874)
- fix(Script/Core): Move hardcoded text to DB (#11829)
- chore(DB): import pending files
- fix(Scripts/ZulGurub): Re-implemented Hakkar's Insanity. (#11840)
- fix(Core/Units): Clear any movement on charm - vol. 2. (#11897)
- fix(Scripts/ZulGurub): Massive Geyser should not attack players. (#11909)

## 2022-05-29
- Merge branch 'azerothcore:master' into Playerbot
- chore(DB): import pending files
- fix(Quest/SAI/Equip) Quest 8891 "Abandoned Investigations" (#11912)
- chore(DB): import pending files
- fix(DB): Crashfix. (#11900)

## 2022-05-28
- fix: temporary workaround for the googletest issue (#11902)

## 2022-05-27
- fix(Scripts/Commands): fix baninfo command issues (#11871)

## 2022-05-26
- chore(DB): import pending files
- fix(DB/CreatureText): Jin'do the Hexxer's RP - GRATS! (#11855)
- chore(DB): import pending files
- fix(DB/SAI): Updated text for Rune-Inscribed Parchment (#11639)

## 2022-05-25
- chore(DB): import pending files
- fix(DB/Spell): Set Lock and Load procPhase to 0, allowing Black Arrow to proc it. (#11862)
- Merge branch 'master' into Playerbot
- chore(DB): import pending files
- fix(DB/Translation): Chinese translation of two quests (#11867)
- fix(Core/Spells): Shadow Weaving should not proc off from DoTs. (#11825)
- chore(DB): import pending files
- fix(Core/Spells): Fixed players being able to mount with all transfor… (#11767)
- chore(DB): import pending files
- fix(DB/SAI): Commander Felstrom Infinite Loot Farm (#11744)
- chore(DB): import pending files
- fix(DB/Loot): Bear Flank drop rates (#11530)

## 2022-05-24
- chore(DB): import pending files
- feat(Core/GameObjects): Instance gameobject save data implementation (#11113)

## 2022-05-23
- Merge branch 'azerothcore:master' into Playerbot
- chore(DB): import pending files
- fix(DB/SAI): Skeletal Guardian should melee when no mana / follow around corners. (#11808)
- fix(DB/BlackwingLair): Trash Formation (#11807)
- fix(Core/Units): Clear any movement on charm. (#11826)
- chore(DB): import pending files
- refactor(Core/Combat): DeleteThreatLists() become ClearAllThreat() (#11824)
- fix(DB/Creature): Flamebringer spawning indefinitely  (#11737)
- fix(Scripts/Spells): Sweeping Strikes - improvements. (#11666)
- fix(Script/ZulGurub): Skeletons should appear in pit (#11561)
- chore(DB): import pending files
- fix(Scripts/Spells): Replenishment should proc off from Vampiric Touc… (#11772)
- fix(DB/gameobject): Darnassus Moonwell spell focus objects (#11428)
- chore(DB): import pending files
- fix(Core/Items): Properly transfer enchantment durations from old to … (#11828)
- fix(Core/Spells): Improvements to Far Sight spell: (#11683)
- fix(Core): Crashfix. (#11821)
- fix(DB/Quest): Fixed Captive Crocolisk not moving to final destination. (#11823)
- feat(Cmake/FindMySQL): add support MariaDB 10.9 (#11835)
- fix(Tools/Vmap): correct build (#11834)

## 2022-05-22
- Merge branch 'azerothcore:master' into Playerbot

## 2022-05-21
- chore(DB): import pending files
- feat(Core/Movement): Allow waypoints to use 0 as valid facing value (#11681)
- chore(DB): import pending files

## 2022-05-22
- fix(Script/Quest): A Suitable Disguise - Move zone_dalaran to DB from hardcode (#11813)
- fix(Script/Quest): Conversing With the Depths adjustments & zone_dragonblight move to db from hardcode (#11795)
- fix(DB/Creature): BRD Detention Block - Link mobs in group pack (#11790)
- fix(DB/Creature): Horde Scout - console SmartScript::ProcessAction errors (#11783)

## 2022-05-21
- chore(DB): import pending files

## 2022-05-22
- fix(Script/Ulduar): Mimiron - remove hardcode text and fix Computer broadcast. (#11725)
- fix(Script/Ulduar): Thorim - misc fixes & hardcode removal (#11711)

## 2022-05-20
- feat(Common/Collision): missing fclose (#11753)

## 2022-05-19
- Merge branch 'azerothcore:master' into Playerbot
- fix(Script/Ulduar): Freya spawning multiple chests (#11794)
- fix (core/logging/conf): Fix Logging for Modules (#11601)

## 2022-05-18
- Core/Combat: rename getThreatMgr() to GetThreatMgr() (#11758)
- fix(Core/Spells): Windfury, Flametongue, Healing Stream, Cleansing … (#11761)
- fix(Core/Spell): Enslaved Demon does not auto-attack/auto-cast (#11677)
- chore(DB): import pending files
- fix(DB/Quest): Quest "Relic of the Earthen Ring" should be reset on … (#11755)
- fix(Core/Spells): The Earthshatterer 8/9 set bonus should be removed … (#11757)
- chore(DB): import pending files
- fix(DB/Spells): Fixed Shaman's Clearcasting proc. (#11754)

## 2022-05-17
- chore(DB): import pending files
- fix(DB/Gossips): Earthcaller gossips (#11792)
- Merge branch 'azerothcore:master' into Playerbot
- chore(DB): import pending files
- fix(DB/Quest): Coward Delivery... Under 30 Minutes or it's Free (#11734)
- fix(DB/Creature): Goblin Land Mine playing Hakkar voiceline  (#11756)
- fix(Core/Scripts): Black Template Area Boundary (#11705)
- fix(DB/SAI): Fixed crystal fang to spawn 4 spiders on death (#11732)
- refactor(Core/Combat): implement compatiblity layer for ResetAllThreat() (#11778)
- fix(DB/Creature): Hakkar should be taunt immune.  (#11777)
- fix(Core/Spells): Priest with Spirit of Redemption should be immediat… (#11771)
- fix(Core): Crashfix. (#11740)
- fix(Core): Crashfix. (#11741)
- chore(DB): import pending files

## 2022-05-16
- Fix(Script/SAI/Misc) Eversong Partygoers (#11786)
- Add missing override annotation to GetPlayerbotsDBRevision
- Merge branch 'azerothcore:master' into Playerbot
- chore(DB): import pending files
- fix(DB/Quest): Fixed quest "Krolmir, Hammer of Storms". (#11742)
- chore(DB): import pending files
- fix(DB/quest): Forging an Alliance require A Spark of Hope + Mending Fences

## 2022-05-15
- fix(Scripts/World): fix nullptr crash (#11770)

## 2022-05-14
- feat(tools/mmaps): isContinentMap (#11727)

## 2022-05-13
- add (core): Additional Helper (#11731)
- fix (core): Prevent Forced UpdateObjectVisibility Before in World (#11730)
- fix (core\crash): fix client crash dk starter (#11726)

## 2022-05-12
- Merge branch 'azerothcore:master' into Playerbot
- fix (core): Build Fix (#11723)
- chore(DB): import pending files
- fix(DB/Quest): Exodar version of "Yorus Barleybrew" quest should open "The Rethban Gauntlet". (#11664)

## 2022-05-11
- feat(Core/Map): Allow disabling the blizzlike PvP line of sight checks (#11692)
- chore(DB): import pending files
- fix(DB/translation): some Chinese translation (#11696)
- chore(DB): import pending files
- fix(DB/SAI): Rallying Cry of the Dragonslayer should happen… (#11593)
- fix(Core/Spells): Everlasting Affliction should be considered as shad… (#11678)
- chore(DB): import pending files
- fix(Scripts/BlackwingLair): Warrior Class Call should  not restore to default stance on removal. (#11671)

## 2022-05-10
- chore: update AC data version (#11709)

## 2022-05-11
- fix(Scripts/Outland): boss_kaelthas (#11701)

## 2022-05-10
- fix(Core/Spells): Blink. (#11663)
- fix(Core/PacketIO): Stop WorldSession packet processing loop immediat… (#11680)
- fix(Core/Spells): Fixed rank 6 of Flametongue Weapon. (#11689)
- Merge pull request #3 from qudzy/upstream/refactor-instance-suggestions
- Merge branch 'azerothcore:master' into Playerbot
- fix(Scripts/Spells) charge Auto attack (#11693)

## 2022-05-09
- chore: update AC data version (#11703)
- fix(Script/Ulduar): Change the way Elders are despawned
- fix(Core/MMAPs): Fix small steps being considered as NAV_AREA_GROUND_STEEP  (#11591)
- chore(DB): import pending files
- fix(Scripts/Auriaya): Move hardcoded text/gossips to DB (#11658)
- feat(Core/MMAPs): Reduce chances of breaking tile connections  (#11605)
- feat(Tools/Mapextractor): Implemented liquid object detection  (#11402)

## 2022-05-08
- chore(DB): import pending files
- fix(DB/Quests): Quest "JoJ" should be available only to Draenei plaladins. (#11581)
- refactor(Core/Movement): Rewritten fleeing movement generator. Source: TrinityCore. (#11586)
- chore(DB): import pending files
- fix(DB/SAI): Zul'Gurub trash monsters should cast their abilities (#11598)
- chore(DB): import pending files
- fix(Scripts/Quest): improved You'll Need a Gryphon (#11651)

## 2022-05-09
- fix(Core/Spells): Allow spells with SPELL_ATTR0_CU_REQ_CASTER_BEHIND_TARGET attribute to go through deterrence. (#11644)
- fix(Scripts/Ignis): Move hardcoded text/gossips to DB (#11655)
- fix(Scripts/XT002): Move hardcoded text/gossips to DB (#11652)

## 2022-05-08
- fix(Core/Auras): INVISIBILITY_UNK10 also applies the flag PLAYER_FIELD_BYTE… (#11588)

## 2022-05-09
- fix(Scripts/Freya): misc improvements (#11665)

## 2022-05-08
- fix(Scripts/RazorScale): Move hardcoded text/gossips to DB and minor fixes  (#11694)
- chore(DB): import pending files
- fix(DB/Spells): 54476 triggerspell (#11688)
- chore(DB): import pending files
- fix(DB/Item): Wrynn's Decree page text (#11686)
- chore(DB): import pending files
- fix(DB/Creature): Korfax missing gossip (#11676)
- chore(DB): import pending files
- feat(Tools/MMAPs): Output the time spent in a human readable format  (#11574)
- fix(Scripts/AQ): Rewrite bug trio fight (#11565)
- chore(DB): import pending files
- fix(Scripts/MC): Set exit teleport location to in front of Lothos Riftwalker (#11635)
- fix(Core/ItemHandler): fix selling items over gold limit (#11673)
- fix(Core/Spells): Paladin's Judgements can be applied on different targets at the same time (#11672)
- chore(DB): import pending files
- fix(Scripts/Ahune): Removed hardcoded emotes (#11674)
- fix(DB/Quest): Krolmir, Hammer of Storms. (#11661)

## 2022-05-07
- chore(DB): import pending files
- fix(DB/Spells): Fixed phasing after quest "A Spark of Hope". (#11662)

## 2022-05-08
- fix(DB/Creature): Remove Orphan Matron Aria duplicate (#11669)

## 2022-05-07
- fix(Script/Skadi): Emotes (#11625)
- fix(Core/Guardian): Crashfix. (#11659)

## 2022-05-06
- chore(DB): import pending files
- Fix (DB/SAI) Valkyrion Harpoon Gun (#11657)
- Merge branch 'azerothcore:master' into Playerbot
- chore(DB): import pending files
- Fix(DB/SAI) Rhapsody's Kalimdor Kocktail quest script (#11654)
- chore(DB): import pending files
- fix(DB/Loot): Removed Cache of Zanzil from Grand Foreman Puzik Gallywix (#11640)

## 2022-04-28
- Add prepared dungeon suggestion statement
- Declare strToLower method in utilities

## 2022-04-04
- Ignore Visual Studio folders

## 2022-05-06
- chore(DB): import pending files
- fix(DB/SAI): Regression with Gravis Slipknot (#11638)
- refactor(Core/Creature): Move hardcoded text/gossips to DB - boss_general_vezax  (#11649)
- refactor(Core/Spells): make DoCast functions use SpellCastResult (#11546)
- feat(Core/DB): Add Hooks On creature/game object save to db (#11246)
- fix(Core/Commands): Fix removing item from player account (#11041)

## 2022-05-05
- chore(DB): import pending files
- Fix (DB/Gossip/Conditions) Captured Arko'narin (#11622)
- fix(Script/Quest): A Pawn on the Eternal Board freezing world (#11616)
- chore(DB): import pending files

## 2022-05-04
- Fix(DB/Quest_Greeting) gender check (#11628)
- chore(DB): import pending files
- Fix(DB/SAI): Falconwing Square scripted NPCs (#11619)
- Merge branch 'azerothcore:master' into Playerbot
- chore(DB): import pending files
- Fix(DB/Creature): Set correct faction flag for Aggi Rumplestomp. (#11511)

## 2022-05-03
- chore(DB): import pending files
- fix(Scripts/TempleOfAhnQiraj): Battleground Sartura should not be ski… (#11596)
- fix(Scripts/BlackwingLair): Prevent Chromaggus from hostilizing playe… (#11595)
- chore(DB): import pending files
- fix(Scripts/BlackwingLair): Prevent Chromaggus cage from looking (#11603)
- fix(Core/Duel): Player during duel countdown is not a valid attack target. (#11509)
- chore(DB): import pending files
- fix(Script/ZulGurub): High Priestess Jeklik improvements (#11458)
- fix(Scripts/BWL): Razorgore's Orb of Domination should not be usable during 2nd phase of the encounter. (#11580)

## 2022-05-02
- Merge branch 'master' into Playerbot
- fix(Scripts/TempleOfAhnQiraj): Correct Battleguard Sartura spell ids (#11597)

## 2022-05-01
- chore(DB): import pending files
- fix(DB/Creatures): Added `CREATURE_FLAG_EXTRA_IGNORE_PATHFINDING` flag to Muck Frenzy. (#11589)
- Fix (core) water level and ground level correction (#11552)
- fix(Core/Minions): Crashfix. (#11592)
- chore(DB): import pending files
- Fix(DB/SAI): Prince Thunderaan corpse should despawn after 1 hour. (#11575)
- fix(Core/Movement): Improved pet's follow movement. (#11585)

## 2022-04-30
- chore(CI): add macos-12 (#11242)
- fix(Scripts/IcecrownCitadel): Increases radius of Sindragosa's boundary. (#11579)

## 2022-05-01
- feat(Tools/MMapsGenerator): Improve multithreading of mmaps_generator (#10963)

## 2022-04-29
- chore(Scripts/Spells): Remove a few aura types being passed as spells in the validator (#11576)
- chore(CI): Remove version check (#11572)
- refactor(Tools/MeshExtractor): remove meshextractor (#11569)

## 2022-04-28
- fix(Scripts/Spells): Validate some spells in spell_generic (#11549)
- chore(DB): import pending files
- refactor(DB): Handle SQL files in a new way (#11494)
- fix(Core/Spell): Improvements to path generation for Charge mechanic (#11534)
- feat(Tools): Automatically create directories for tools  (#11540)

## 2022-04-27
- fix(Core/Players): Updates visibility of nearby entities around player's viewpoint in case of immediate changing farsight object. (#11520)
- fix(Core/Battlegrounds): Remove all DoTs when exiting battleground. (#11517)

## 2022-04-26
- Merge branch 'azerothcore:master' into Playerbot

## 2022-04-25
- chore(DB): import pending files

## 2022-04-26
- Fix(DB/Item) Bonereaver's Edge proc should be 2 ppm. (#11508)

## 2022-04-25
- chore(DB): import pending files
- fix(Core/Wintergrasp): Reimplement Wintergrasp quests and fix vendors (#11533)
- chore: update AC data version (#11535)
- Merge branch 'azerothcore:master' into Playerbot
- feat(Core/Player): Allow stay in group when logged out (#10887)
- chore(DB): import pending files
- fix(Core): Restored code about shared visions removed in d504a62. (#11493)
- fix(Core): Crashfix. (#11495)
- fix(DB/Conditions): Unfired Plate Gauntlets should only require blacksmithing 225 to loot. (#11510)
- fix(Core/Formations): Implemented GROUP_AI_FLAG_RESPAWN_ON_EVADE flag. (#11512)
- fix(Core/Spells): Rapture should ignore line of sight. (#11519)

## 2022-04-24
- feat(Core/Creature): Implement ModifyThreatPercentTemp() function (#11521)
- fix(Core/Battlegrounds): Fixed battleground queue announcer. (#11348)

## 2022-04-25
- feat(Core/Mmaps): Handle different slopes in  mmaps and Add some more input parameters to improve (#10974)

## 2022-04-24
- fix(Tools/Mapextractor): Fix water height redundancy algorithm ignoring "no water" (#10947)
- chore(DB): import pending files
- fix(DB/Item): Formula: Enchant Cloak - Titanweave and Shadow locales (#11354)
- fix(Scripts/BlackiwingLair): Rogues should be teleported in front of Nefarian during Class Call event. (#11513)
-  feat(Tools/MMaps): Allow to specify different Recast settings for different maps (#10922)
- fix(DB): Weird leftover (#11518)
- chore(DB): import pending files
- fix (core): Water Calculation Corrections (#11516)
- feat(DB): release ACDB 6.0.0 (#11515)
- chore(DB): import pending files
- refactor(Scripts/BlackwingLair): Refactor Chromaggus (#11501)
- chore(DB): import pending files
- fix(Scripts/Spells): Improvements to Brood Power: Bronze: (#11499)
- fix(Scripts/BlackwingLair): Three drake bosses should be optional (#11506)
- fix(Scripts/BlackwingLair): Bone Constructs should persist after Nefarian's death (#11504)
- fix(Core/Spells): Fixed some damage overflows during resilience calculations. (#11497)

## 2022-04-23
- chore(Core/Misc): Improve wiki link in database error (#11496)
- chore(DB): import pending files
- fix(Core/Spells): Custom attributes belong in the DB (#11405)
- chore(DB): import pending files
- fix(Core/Player): null crash in RemovePet() (#11464)
- fix(DB/Creature): Risen Ghoul (DK) locales (#11210)
- fix(Core/Pets): Handle health-aurastates on pet loading. (#11491)
- fix(DB/Creature): Some locales frFR ruRU (#11220)
- fix(Core): Crashfix. (#11490)
- fix(DB/Creature): Zul'jin locales (#11207)
- chore(DB): import pending files
- fix(DB/Creature) Scarlet Warrior position (#11483)
- fix(DB/Creature): Behsten gossip for XP freeze (#11478)
- fix(DB/Item): Wand of Allistarj locale esES esMX (#11412)
- feat(Core/SmartScripts): SMART_EVENT_FLAG_WHILE_CHARMED (#10286)
- fix(DB/Creature): Totem locales esEs esMx (#11372)
- fix(DB/GameObject): Western Zeppelin Tower - Northrend & Mulgore deDE locale (#11217)
- fix(DB/Creature): Correct gossip display for Master Smith (#11420)
- feat(Core/Creature): CREATURE_FLAG_EXTRA_MODULE (#11445)
- fix(DB/Item): Shaft of Tsol drop rate (#11444)
- fix(DB/Quest): Redemption Text and Animation Missing (#11400)
- fix(Clang/CMake): -Wdeprecated-copy warning in G3D (#11471)
- chore(Core/CreatureAI): improve log (#11468)
- chore(DB): import pending files
- fix(DB/Quest): Corruption of Earth and Seed faction exclusive (#11403)
- add (core): additional helper for jump destination (#11489)
- chore(DB): import pending files
- fix(DB/Gameobject): Zul'Gurub - Fix Entrance Gate (#11441)

## 2022-04-22
- Merge branch 'azerothcore:master' into Playerbot
- fix (core): inhabit CanSwim revert (#11475)
- fix(core): Null check the helpers (#11476)

## 2022-04-21
- fix(Core/Spells): Prevent shadow spells from triggering Nefarian's corrupted healing (#11470)

## 2022-04-22
- feat(Core/DryRun): add support db autoupdate for DryRun (#9572)

## 2022-04-21
- chore(Core/Misc): nullptr cleanup (#11467)
- feat (core): another helper implemented (#11469)
- chore(DB): import pending files
- fix(Scripts/ICC): Change trigger flag for Battle Experience spell (#11466)
- fix(Core/Spell): Move SelectTrajTarget log to Debug (#11465)
- Feat: (core) Additional Helper (#11457)

## 2022-04-20
- Merge branch 'azerothcore:master' into Playerbot
- fix(Script/BWL): Fix initial shadowflame timers (#11443)

## 2022-04-19
- chore(DB): import pending files
- feat(Core/Mail): Server mail (#10628)
- Merge branch 'azerothcore:master' into Playerbot
- fix(Core/SmartScripts): null crash in SMART_TARGET_PLAYER_DISTANCE (#11442
- fix(Scripts/BlackwingLair): Chromaggus shimmer timer adjustment, fre… (#11437)

## 2022-04-18
- chore(DB): import pending files
- fix(Script/Instance): Azuregos' Mark of Frost debuff should persist through wipe and reset (#11345)
- fix(DB/Gossip): wrong TextId for NPC's (#11342)
- fix(Scripts/Ulduar): Fixed console errors of uninstalling vehicles. (#11334)
- fix(DB/Locale): quest 12718 "frFR" (#11218)
- fix(DB/Locale) Horde of the Borean Tundra Quests (#11202)
- feat(Core/SmartScripts): Improvements to SMART_EVENT_FRIENDLY_HEALTH_PCT: (#11171)
- feat(Spell/Scripts): Move Spell gen remove impairing auras to spell scripts (#11104)
- fix(DB/Creature): Renn McGill Gossip Option (#10627)
- feat(Core/Conditions): CONDITION_STAND_STATE (#10287)

## 2022-04-17
- Merge branch 'azerothcore:master' into Playerbot
- fix (core) Remove not need operator 
- fix(Scripts/BlackwingLair): Prevent Nefarian's adds corpse from decaying (#11424)

## 2022-04-16
- Merge branch 'azerothcore:master' into Playerbot

## 2022-04-17
- chore(DB): import pending files
- fix(DB/Spells): Prince Taldaram's Conjure Flame should proc off from absorbed damage. (#11174)
- chore(DB): import pending files
- fix(DB/Spells): Skullflame Shield's Drain Life should scale with spell power. (#11352)
- chore(DB): import pending files
- fix(DB/Spells): Warrior's Execute can be dodged/parried/blocked. (#11351)
- feat(Tools/MMapsGenerator): percentage progress (#10948)
- feat(Core/SmartScripts): Add an action_param3 to "summon gob" to control when the object will despawn (#10254)
- fix(Core/SmartScripts): don't allow to start a new SAI actionlist while the entity is already running one (#10230)
- feat(Core/SmartScripts): SMART_EVENT_EVENT_PHASE_CHANGE (#10054)

## 2022-04-16
- fix(Core/Auth): Fix uninitialized variable, fixes changing realms aFter logging in to world (#11415)
- fix (core): Shallow Water Calulation Correction (#11419)
- chore(DB): import pending files
- fix(DB/item_template_locale): 'Viewing Room Key' translations (#11370)
- fix(CI/Docker): Redacted Eluna (#11418)
- chore(DB): import pending files
- Fix (Core\DB) Hostil to Hostile spelling fix (#11399)
- fix(Scripts/BlackwingLair): Improve Nefarian's add animations (#11414)
- fix(Core/Spells): Implemented spell priorities. (#11278)
- fix(Core/Units): Stop melee attacking victim if being charmed by non-friendly target. (#11353)

## 2022-04-15
- fix(CI): Redacted eluna (#11406)
- chore(Core\Dep): Zlib 1.2.7 to 1.2.12 (#11401)
- fix(Core/Spells): Send proper caster's guid in SMSG_SPELL_START/SMSG_SPELL_GO packets in case of spells casted originally by gameobjects. (#11337)
- fix(Core/Quests): Fixed displaying correct quest marks for autocomplete/repeatable/daily completed quests. (#11349)
- chore(DB): import pending files
- fix(Spell/Scripts): MOVE Drinking to spell scripts (#11105)
- feat(Core/Maps): AreaBoundary (#10525)
- chore(DB): import pending files
- fix(DB/SAI/Creature): Kyle's Gone Missing! Quest credit (#10034)
- chore(DB): import pending files
- fix(Core/Unit): Remove some hardcoded texts (#5816)

## 2022-04-14
- fix(Scripts/BlackwingLair): Solve the issue with Nefarian occasionall… (#11398)
- chore(DB): import pending files
- fix (db) Harpy Z Axis fix (#11284)
- Merge branch 'azerothcore:master' into Playerbot

## 2022-04-13
- chore(DB): import pending files
- fix(Core/BWL): Orb of Command areatrigger (#11385)
- fix(Scripts/Spell): Gargoyle's damage (#11389)

## 2022-04-12
- fix(Core/BWL): Nefarian class call spells (#11384)

## 2022-04-11
- chore(DB): import pending files
- fix(DB): Many Missing and Fixed zhCN Translations (#11323)
- fix(Spell/SpellCorrection): Brood Power Bronze should only affect a single target (#11367)
- fix(Scripts/BlackwingLair): Do not spawn more than 52 Razorgore's add… (#11274)
- Merge branch 'azerothcore:master' into Playerbot
- fix(Core): Crashfix. (#11346)
- chore(DB): import pending files
- fix(Core/BWL): Nefarian spawns (#11326)
- chore(DB): import pending files
- fix(Core/Player): corrected HasUnitFlag usage (#11321)
- fix(DB/quest_template_locale): Correct zhCN Quest Text (#10791)
- chore(DB): import pending files
- fix(DB/Creature): Broodlord Lashlayer should not be disarmable (#11359)
- fix(DB/Creature): Vaelastrasz should be immune to interrupts (#11358)

## 2022-04-10
- fix(Core/Vmaps): Stop M2s from occluding for spellcast LoS. Original autho… (#11341)

## 2022-04-09
- chore(DB): import pending files
- fix(Scripts/Items): Fix Goblin Bomb Dispenser (#10612)
- fix(Scripts/BlackwingLair): Prevent Razorgores' eggs from respawning … (#11336)

## 2022-04-07
- chore(DB): import pending files
- fix(Scripts/UtgardPinnacle): Implement Beast's Mark (#11298)
- chore(DB): import pending files
- fix(Core/BWL): Razorgore spawns timer (#11320)
- Scripts/Spells: Suppression Aura should not hit stealthed units. (#11270)
- chore(DB): import pending files
- fix(DB/BWL): Chromaggus should be taunt immune (#11290)
- chore(DB): import pending files
- fix(Core/BattlegroundQueue): disable double queue in one bg (#11165)
- Fix(DB/Loot): Nefarian should drop T2 Helm (#11264)
- chore(DB): import pending files
- fix(DB/Creature): Frostwolf run and walk speed (#11259)
- chore(DB): import pending files
- fix(DB): Gorbold Steelhand incorrectly has Cataclysm Gossip Text (#10520)
- fix(DB/BWL): Blackwing Warlocks (#11291)
- chore(DB): import pending files
- fix(DB): Stitches Event Fix (#11213)
- chore(DB): import pending files
- fix(DB/Creature) More Dense Grinding Stones... (#11300)
- Merge branch 'azerothcore:master' into Playerbot
- chore(DB): import pending files
- fix(DB/creature_template_locale): npc Title ruRU (#11265)
- chore: Rename rev_1649325436095486698 to rev_1649325436095486698.sql (#11318)
- fix(DB/Creature): Razorgore should not be interruptable

## 2022-04-06
- fix(Scripts/Raids): Fixed setting `UNIT_FLAG_NON_ATTACKABLE` flag to … (#10759)

## 2022-04-05
- feat(Core/Players): PlayerFlag helpers (#11294)
- fix(Core/Gossip): Leatherworking specialization
- fix(Scripts/Ulduar): Sara's buffs should be casted randomly among the players. (#11255)
- feat(Core/GameObject): Gob flag helpers (#11287)
- feat(Core/Unit): NPCFlags helpers (#11286)
- chore(DB): import pending files
- fix(Core/Spells): Razorgore's Explosion ignores LoS. (#11253)
- fix(Scripts/BlackwingLair): Razorgore should not attack units with Conflagrate. (#11272)

## 2022-04-04
- Merge branch 'azerothcore:master' into Playerbot

## 2022-04-03
- Add (core): Additional Teleport Helpers (#11277)
- chore(DB): import pending files
- fix(Core/BWL): Blackwing Lair improvements (#11244)
- fix(Scripts/BlackwingLair): Chromaggus should not attack units afflic… (#11254)

## 2022-04-02
- chore(DB): import pending files
- fix (DB/creature_text): add missed BroadcastTextID (#11141)
- chore(DB): import pending files
-  feat(Core/Command): Split respawn command (#11245)
- feat(Config): Max gold on change faction (#11147)
- fix(Core/Creatures): Properly reset encounter if boss despawns on evade. (#11251)
- chore(DB): import pending files
- fix(Scripts/BWL): Chromaggus Affliction debuff should target… (#11161)
- fix(DB/Loot): Blackwing Lair (#11081)
- chore(DB): import pending files
- feat(DB/Locale): Add missing ruRU quest_request_items_locale (#11185)
- feat(DB/Locale): Add missing esES & esMX quest texts (#11187)
- feat (DB/Locale): Add missing ruRU quest_request_items_locale (#11184)
- feat(DB/Locale): Add missing ruRU offer rewards for quest 11001-12000 (#11192)
- chore(DB): import pending files
- feat(DB/Locale): Add missing ruRU offer rewards 1501-3500 (#11196)
- feat(DB/Locale): Add some missing ruRU quest texts (#11223)
- chore(DB): import pending files
- feat(DB/Locale): Add missing ruRU offer rewards 5501-7500 (#11197)
- chore(DB): import pending files
- feat(DB/Locale): Add missing ruRU offer rewards 3501-5500 (#11198)
- feat(DB/Locale): Add missing ruRU offer rewards for quest id 12001 - 13000 (#11191)
- feat(DB): assign BroadcastText to Creature_text (Night Elf Commoner) (#11188)
- feat(DB/Locale): Add missing ruRU offer rewards 7501-8500 (#11199)
- feat(DB/Locale): Add missing esES & esMX quest locales (#11205)
- fix(Scripts/BlackwingLair): Suppression Trap casts its aura 5 sec afer re-activate. (#11252)
- fix(Core/Spells): Fixed displaying runes cooldowns. (#11250)
- fix(Core/Object): Fix WorldObject::SetZoneScript unsafe cast to InstanceMap (#11226)

## 2022-04-01
- chore(DB): import pending files

## 2022-04-02
- feat(DB/Locale): Add missing ruRU offer rewards 8500-10000 (#11200)
- feat(DB/Locale): Add missing ruRU quest_request_items_locale duplicated texts (#11189)
- chore(Tools/Mapextractor): clean up an unnecessary function

## 2022-04-01
- fix(Tool/MMAP): Fixed invalid check causing certain tiles not to build (#10841)
- Merge branch 'azerothcore:master' into Playerbot
- chore(DB): import pending files
- fix(DB/conditions): Missing conditions for trainer gossip (#11110)
- fix(DB/SAI): Multiple barrel spawns (#11120)
- feat(Core/Unit): New helpers for DynamicFlags (#11230)
- feat(DB/Locale): Add missing ruRU offer rewards 10001-11000 (#11201)
- feat(DB/Locale): Add missing ruRU offer rewards 0-1500 (#11195)
- feat(DB/Locale): Add some missing ruRU quest offer rewards (#11222)
- fix(Core/Spells): Do not reset periodic timers for auras with multiple stacks. (#11167)
- feat(DB/Locale): Add missing creature locale names (#11194)
- fix(Scripts/Ulduar): Yogg-Saron portals should be interactable. (#11150)
- fix (DB/creature_template): fix interraction with Light and Dark Essences (#11117)
- fix(Scripts/Ulduar): Do not spawn Hodir chests if already defeated. (#11149)
- feat(DB/Locale): Add missing ruRU offer rewards (#11190)
- feat(Scripts/Spell): Teleporting to Script
- feat(Scripts/Spells): Move to spell scripts - Brittle Armor & Mercurial Shield (#11116)
- fix(Core/Spells): Ghost Wolf Speed from PvP 58 vl set. (#11096)
- feat(Scripts/Spells): Move to spell scripts Deathbolt (#11100)
- fix(DB/Creatures): Snow Mound stalker should be invisible. (#11084)
- fix(Core/Players): Fixed setting player's zone id to unknown value. (#10996)
- fix(Scripts/AlteracValley): Crashfix. (#10976)
- feat(Scripts/Commands): debug objectcount
- feat(Core/Vmaps): Changed error message when loading outdated vmaps (#10490)

## 2022-03-30
- Merge branch 'azerothcore:master' into Playerbot
- chore(DB): import pending files
- fix(Scripts/Icecrown): Lich King should not evade attacks on last phase (#11146)
- feat(Core/Unit): New helpers for UnitFlag and UnitFlag2 (#11227)
- fix(Core/Misc): Update some log errors to debug (#11225)
- docs: update README.md with latest Eluna changes (#11216)

## 2022-03-28
- Merge branch 'azerothcore:master' into Playerbot
- chore(Core/Player): clarify a gossip error about invalid OptionType (#11173)
- chore(DB): import pending files
- fix(DB/SAI): Haleh & Rokaro Drakefire Amulet retrieval gossips (#11175)
- fix(modules/CMakeLists): new Eluna module name (#11164)

## 2022-03-27
- chore(DB): import pending files
- fix(DB): Evening/Nighttime Game Events Update (#11166)
- Merge branch 'azerothcore:master' into Playerbot
- fix (Core/SmartScripts): allow to start waypoint movement for a creature that is in combat
- fix(Core/Combat): Improved extra attacks handling. Author: @trickerer (#11169)
- chore(DB): import pending files
- fix(DB/SpellProcEvent) Hand of Justice Fix (#11172)
- chore(DB): import pending files
- fix(SAI): Fix Stormwind citizens to be more Blizzlike in their behavior (#11121)
- fix(Core/Objects): Fixed typo in `m_visibilityDistanceOverride` initialization (#11170)
- chore(DB): import pending files
- feat(Core/SmartScripts): SMART_EVENT_ACCEPTED_QUEST, SMART_EVENT_REWARD_QUEST (#10210)
- chore(DB): import pending files
- fix(DB/Spawns): Some improvements to Death Talon Hatcher spawns: (#11157)
- chore(DB): import pending files
- fix(DB/Loot): Remove wrongly added ring from Ragnaros loot (#11144)
- chore(DB): import pending files
- fix(DB/Core/Misc): More adjustments to BWL (#11154)
- fix(Core/BWL): Victor Nefarius encounter not resetting properly (#11145)
- chore(DB): import pending files
- feat(Core/Spells): Move Spell q1846 bending shinbone to spell scripts (#11106)
- chore(DB): import pending files
- feat(Core/Spells): Move Spell death knight initiate visual to spell scripts (#11103)
- chore(DB): import pending files
- feat(Core/Spells): Move Spell item dimensional ripper area52 to spell scripts (#11099)
- chore(DB): import pending files
- feat(Core/Spells): Move Spell pri lightwell to spell scripts (#11089)
- chore(DB): import pending files
- feat(Core/Spells): Move spell_item_runic_healing_injector to spell scripts (#11088)
- fix(Core/Spells): Fixed an issue with Premeditation removing itself. (#11093)
- chore(DB): import pending files
- fix(DB/Locale/ruRU): Add missing gameobject_template_locale (#11115)
- chore(DB): import pending files
- fix(DB/Locale/ruRU): Add missing item_template_locale (#11114)
- feat(Core/Wintergrasp): Save win/loss totals for faction (#11056)
- chore(DB): import pending files
- fix(DB/npc_text): The Stone Watcher (#11077)
- fix(Scripts/Ulduar): Open the chamber door on Kologarn's death. (#11085)
- fix(Scripts/Ulduar): The Flame Leviathan's main gate should be closed during the fight. (#11083)
- chore(DB): import pending files
- fix(DB/Spells): Rogue Armor Energize proc (#11048)
- feat(Core/Packets): SMSG_WORLD_STATE_UI_TIMER_UPDATE (#11047)
- feat(Core/Scripts): Spirit towers reset to neutral 6 hours after capture and save WorldState (#11030)
- chore(DB): import pending files
- fix(DB/SAI): Raze Direhorn Post! (#10985)
- fix(Core/Spells): Fixed implementation of CAST_FLAG_POWER_LEFT_SELF flag. (#10908)
- Core/Packet: MIRROR_TIMER (#10885)
- chore(DB): import pending files
- fix(Scripts/Vehicles): The next player entering Salvaged Siege Engine… (#10987)
- chore(DB): import pending files

## 2022-03-26
- fix(DB/pathing): Duskwood and Deadwind Missing Pathing (#11054)

## 2022-03-27
- fix(DB/Creatures): Corrupted Blue Whelp should stop respawning if Bro… (#11153)
- chore(DB): import pending files
- fix(DB/SAI): Despawn all nearest Demon Portals on Blackwing Warlock d… (#11092)
- chore(DB): import pending files

## 2022-03-26
- fix(DB/Formations): Death Talon Wyrmguard should be linked (#11068)

## 2022-03-27
- chore(DB): import pending files
- fix (DB/Creature): BWL trash boe drop adjustment (#11156)
- fix(Scripts/Blackwing Lair): Supression traps should not be disarmed... (#11082)

## 2022-03-26
- fix(Core/BWL): Victor Nefarius Shadow Bolt (#11078)

## 2022-03-25
- Merge branch 'azerothcore:master' into Playerbot
- Fix (core) Death Comes from high Client Crash Fix (#11136)
- chore(DB): import pending files
- fix(Scripts/Quest): improved Overwhelmed! (#10387)
- fix(Core/Handlers): Faction Change service properly reset and give ne… (#9729)

## 2022-03-24
- Merge branch 'azerothcore:master' into Playerbot

## 2022-03-25
- fix(Core/BattlegroundQueue): remove second queue if player enter bg (#11067)

## 2022-03-24
- Merge branch 'azerothcore:master' into Playerbot
- chore(DB): import pending files
- feat(Scripting/Hooks): implement OnQuestComputeXP() hook (#10934)

## 2022-03-23
- chore(DB): import pending files
- fix(Scripts/BlackwingLair): Razorgore improvements (#10971)
- Merge branch 'master' of https://github.com/ZhengPeiRu21/azerothcore-wotlk into Playerbot
- Add missing ifdef for PLAYERBOTS
- feat(Core/Packet): SMSG_DURABILITY_DAMAGE_DEATH (#10894)
- chore(DB): import pending files
- fix(DB/Loot): Molten Core (#11080)
- chore(DB): import pending files

## 2022-03-22
- fix (db) smartscript error fix Acherus Necromancer (#11109)
- fix(Core/Command): Fix issue with waypoint show off (#11111)

## 2022-03-23
- chore(DB): import pending files

## 2022-03-22
- fix(DB/Creature): Update equipment for Burning Blade NPCs (#11112)
- Merge branch 'master' into Playerbot
- Fix corrupt item cache crashes, bot whispers, trade crashes
- fix (core) Script Names not loaded with manual add (#11102)

## 2022-03-21
- Merge branch 'questXPHook' into Playerbot
- Merge branch 'master' into Playerbot
- chore(DB): import pending files
- fix(DB/Quest): Kim'jael Indeed! GO loot (#10350)
- fix(Scripts/Spells): Earthliving Weapon should no proc from Earth Shield. (#11094)
- chore(DB): import pending files
- fix(DB/Creatures): Control Onyxia's movement flags via script. (#11095)
- Core/Packet: SMSG_LEVELUP_INFO (#10884)

## 2022-03-18
- chore(DB): import pending files
- fix(DB/creature_template): Love is in the Air Creatures Level (#11009)
- chore(DB): import pending files
- fix(DB): Blood Elf Mage Trainers Incorrect Dialog (#10524)
- docs(LICENSE): remove old GPLv2 license (#11076)
- chore(DB): import pending files
- fix(DB/SAI/Quest): Stranglethorn Fever (#11010)
- fix(Core): Crash related to reset instances (#11003)
- chore(DB): import pending files
- fix(DB/Creatures): Adjusted ground position for some mobs in Swamp of Sorrows. (#11004)
- chore(DB): import pending files
- fix(DB/SAI): The Touch of Zanzil (#11046)
- chore(DB): import pending files

## 2022-03-19
- feat (DB/locale): zhTW CompletedText locale text (#11007)

## 2022-03-18
- chore(DB): import pending files

## 2022-03-19
- fix(DB/Locale): esES & esMX quest texts (#11044)

## 2022-03-18
- chore(DB): import pending files

## 2022-03-19
- fix(DB/Locale): Add missing esES & esMX quest texts (#11042)

## 2022-03-18
- chore(DB): import pending files
- fix(DB/SAI): The Stone Watcher (#11045)
- chore(DB): import pending files
- fix(DB/pathing): Stranglethorn Missing Pathing (#11012)
- chore(DB): import pending files
- fix(DB/quest_template): Rat Catching (#11008)
- fix(Core/Events): Corrections to Apothecary Hummel (#10674)
- fix(Core/Loot): Fixed some chests inside dungeons not being bound only to participants. (#10995)
- chore(DB): import pending files
- fix(DB/Quest): The Tome of Divinity (#10990)
- chore(DB): import pending files
- fix(DB/smart_scripts): The Restless Souls (#10989)
- fix(Core/Spells): Heal from Bloodthirst should be affected by healing mods. (#10915)
- fix(Core/Spells): Nature's Swiftness should not be consumed by instant spells. (#10909)
- chore(DB): import pending files
- fix(Core/Mails): Do not load expired mails from database. (#10917)
- fix(DB/pathing): Blasted Lands Missing Pathing (#11028)
- chore(DB): import pending files

## 2022-03-19
- fix(DB/Locale): zhTW locale texts for quests 13068-13090 (#11036)

## 2022-03-18
- chore(DB): import pending files

## 2022-03-19
- fix (DB/Locale): Fix zhTW locale texts for death knight quests 12593-13189 (#11035)

## 2022-03-18
- chore(DB): import pending files

## 2022-03-19
- fix(DB/Locale): wrong zhTW locale texts for quests 11560-11631 (#11034)

## 2022-03-18
- chore(DB): import pending files

## 2022-03-19
- fix(DB/Locale): fix missing zhTW CompletedText locale text and locale Item names (#11033)

## 2022-03-18
- chore(DB): import pending files

## 2022-03-19
- fix(DB/Locale): Add missing zhTW CompletedText, (#11032)

## 2022-03-18
- chore(DB): import pending files

## 2022-03-19
- fix(DB/Locale): Add missing zhTW CompletedText for Zul'Drak, Howling Fjord, Grizzly Hills, Storm Peaks quests (#11031)

## 2022-03-18
- chore(DB): import pending files
- feat(DB/locales): missing zhTW CompletedText locale (#10968)
- fix(Core/Spells): Seed of Corruption detonation should obey LoS (#10916)
- feat(CI): add more modules to CI (#11065)

## 2022-03-17
- feat(Core/Chat): Fixed feature to prevent horde and alliance players to chat with each other via custom emotes. (#11000)

## 2022-03-16
- Merge branch 'master' into questXPHook
- fix(Core/Spells): Ruthlessness/Seal Fate selecting wrong proc target (#10982)
- fix(Bash/Dashboard): fix macOS configurations (#11002)
- chore(DB): import pending files
- fix(DB/SAI): Fixed setting faction to Agnetta Tyrsdottar. (#10988)
- chore(DB): import pending files
- fix(Scripts/Spells): Icewing Marshal should affect not affect players. (#11001)
- chore(Core/DataStores): correct logging fmt in `M2Stores.cpp`  (#11018)

## 2022-03-15
- fix(Core/Spells): Periodic ticks number should not exceed the max one. (#10999)
- chore(DB): import pending files

## 2022-03-16
- feat(Core/Battleground): rework bg queue system (#10817)

## 2022-03-15
- fix(Core/Spells): Kill credits given via spells should always be awarded to players
- feat(Core/Characters): Replace DELETE + INSERT with REPLACE (#10862)
- fix(Core/SAI): allow scripts to target the summoner of a TempSummon (#10819)

## 2022-03-14
- fix(Scripts/ZulGurub): Prevent Arlokk from being summoned twice (#10932)
- fix(Scripts/Zul'Gurub): Don't allow players to enter while encounters are in progress (#10933)
- fix(Scripts/MoltenCore): Ragnaros should change its main target to so… (#10758)
- chore(DB): import pending files
- feat(DB/locales): fix missing zhTW CompletedText locale (#10954)
- fix(Core/Spells): Beacon of Light should not proc off from Glyph of Holy Light and Judgement of Light. (#10564)
- chore(DB): import pending files
- fix(Core/Professions): Leatherworking specialization (#10415)

## 2022-03-13
- Merge branch 'master' into questXPHook
- chore(DB): import pending files
- fix(Core/BWL): Nefarian weekly adds spawn mechanics (#10981)

## 2022-03-12
- Added changelog
- Big update.
- chore(DB): import pending files
- fix(DB): Gossip Option to Restore Missing Totem (#10868)
- fix and bringing to a unified style warnings of server loading logs to be more visible at server startup (#10970)
- chore(DB): import pending files
- feat(db/locales): ruRU - translation of the objectives field for quest 5624 (#10956)
- chore(DB): import pending files
- feat(db/locales): ruRU - Add missing quest_request_items_locale for quest  (#10953)
- fix(Scripts/Sunken Temple): Fix Shade of Eranikus (#10891)
- fix(Scripts/Ulduar): "I Could Say That This Cache Was Rare" achievement. (#10912)

## 2022-03-11
- fix(Core/BWL): Nefarian reset behaviour (#10957)

## 2022-03-12
- chore(DB): import pending files

## 2022-03-11
- fix(DB/BWL): Blackwing Taskmaster path error (#10959)
- chore(DB): import pending files
- fix(Scripts/ZulGurub): implement mising Hakkar speech that fires when reaching his temple
- feat(Core/Packet): CMSG_SET_SHEATHED
- Revert "fix(Scripts/AlteracValley): Mini bosses should evade with boss (#10544)" (#10975)
- fix(Core/BWL): Remove warlocks and taskmasters as Razorgore's summons (#10961)
- feat(Core/Maps): Improvements to Cinematic function  (#10765)
- chore(DB): import pending files

## 2022-03-10
- fix(DB/quest_template_addon): Fix The Battle for Arathi Basin (#10930)
- Merge branch 'master' into questXPHook
- chore(DB): import pending files
- fix(DB/Events): Apothecary Hummel should be linked to event (#10786)
- fix(Scripts/AlteracValley): Mini bosses should evade with boss (#10544)
- feat(Core/Gossips): override BoxMoney from DB (#10414)
- fix(Scripts/BlackwingLair): Vaelastrasz (#10962)
- fix(Core/Creature): correctly load creature equipments (#10966)
- chore(DB): import pending files
- fix(DB/BWL): Blackwing Technicians (#10958)
- chore(DB): import pending files
- fix(DB/BWL): Trash formations (#10960)
- fix(Scripts/BlackwingLair): Improved Ebonroc's movement. (#10905)

## 2022-03-09
- fix (core): Load Order Adjustment GAME_EVENT_START hook (#10939)
- chore(DB): import pending files
- fix(Scripts/BlackwingLair): Nefarian (#10536)
- chore(DB): import pending files
- fix(DB/quest_template_locale): Correct zhTW Text (#10940)
- fix (Console): count of Broadcast Text Locales shown by logger on server start (#10942)
- fix(Scripts/Ulduar): Fixed spawning Hodir chests. (#10844)
- fix(Scripts/Ulduar): Fixed launching Leviathan's hard mode. (#10911)

## 2022-03-08
- feat(Core/Conf): Miss Chance Multiplier (#10873)
- Merge branch 'master' into questXPHook
- chore(DB): import pending files
- (DB/Translations) Neutral quests in Grizzly Hills (#10937)
- chore(DB): import pending files
- fix(DB/quest_request_items_locale): Add some ruRU Texts (#10936)
- chore(DB): import pending files
- fix(DB/BWL): Blackwing Technicians should not auto attack (#10897)
- chore(DB): import pending files
- fix (DB): Grimclaw NPC Mini RP event (#10926)
- fix(Core/Spells): Fixed damage of Burning Adrenaline. (#10901)

## 2022-03-07
- feat(Scripting/Hooks): Implement OnQuestComputeXP() hook
- chore(DB): import pending files
- fix(DB/Scripts): Fix Thrash Console Error (#10929)
- chore(DB): import pending files
- fix(DB/quest_greeting): Populate quest_greeting table (#10928)
- chore(DB): import pending files
- (DB/Translations) Alliance quests in Grizzly Hills (#10927)
- chore(DB): import pending files
- fix(Scripts/OnyxiasLair): Force Onyxia to enter evade mode if pulled out of her room (#10890)
- chore(DB): import pending files

## 2022-03-06
- fix (db): Thrash (#10869)
- fix(Core/Spells): Fixed getting max spell range for friendly targets. (#10906)
- chore(DB): import pending files

## 2022-03-07
- feat(Core/Packet): SMSG_CROSSED_INEBRIATION_THRESHOLD (#10893)

## 2022-03-06
- fix(DB/Scripts): Fix Ring of Blood Quest Credit (#10889)
- chore(DB): import pending files

## 2022-03-07
- feat(Core/Players): do not update position data on character creation

## 2022-03-06
- fix(DB): Fix Orgrimmar Grunt creature_addon data (#10872)
- chore(DB): import pending files
- fix(DB/Pathing): Add Missing Bloodscalp Mystic patrol path (#10870)
- chore(DB): import pending files
- fix (DB): Howling Fjord missions translated into Spanish (#10867)
- chore(DB): import pending files
- fix(DB): Missing Skullsplitter Troll Pathing and Formation (#10860)
- chore(DB): import pending files
- fix(DB/Pathing): Add Missing Mosh'Ogg Warmonger Pathing (#10859)
- chore(DB): import pending files
- fix(DB/Pathing): Add Missing Murkgill Hunter pathing (#10858)
- fix(DB/Pathing): Add Missing Hakkari Oracle Pathing (#10857)
- fix(DB/Pathing): Booty Bay Bruisers pathing fixes (#10856)
- fix(DB/Pathing): Add missing pathing and fix position for Booty Bay Bruiser (#10855)
- fix(DB/Pathing): Add missing pathing to Mosh'Ogg Spellcrafter (#10853)
- fix(DB/Pathing): Add missing pathing to Ironforge Mountaineer (#10852)
- fix(Core/Movement): Send proper movement animation visuals. (#10843)
- fix(Scripts/Raids): Phase 3 of Razorgore encounter should start when all eggs are destroyed. (#10837)
- fix(DB): Add missing pathing to Mother Fang (#10836)
- fix(Scripts/Raids): Debuff Mind Exhaustion on Razorgore should be apply on start of mind control. (#10835)
- fix(Core/Spells): Implemented SPELL_ATTR0_CU_IGNORE_EVADE. (#10832)
- chore(DB): import pending files
- fix(Core/Maps): Dead players should not be allowed to enter dungeon if exceeded max number of instances. Thx to @DepTypes (#10831)
- feat(Core/Creature): Implement quest_greetings table (#10526)
- fix(DB): Odesyus' Landing Gossip Conditions (#10803)
- chore(DB): import pending files
- fix(DB/conditions): Fix Keristrasza Gossip (#10531)
- fix(DB): Blackwing Technician spawn and addon (#10470)
- fix(DB/Quest): The Amphitheater of Anguish: Yggdras! (#10412)
- Core/Packet: LFG (#9420)
- chore(Core/Creature): clean up an unnecessary function (#10904)

## 2022-03-05
- chore(DB): import pending files
- fix(DB): Horde Feralas Quest Emotes (#10748)
- fix(Core/Player): fix pet not appearing after dismount for warlock (#10899)

## 2022-03-04
- chore(DB): import pending files
- BREAKING CHANGE(Core/Config): Individual XP rate per bg (#10793)

## 2022-03-03
- chore(DB): import pending files
- fix(DB/page_text): correct Text for Laird's Response (#10530)
- chore(DB): import pending files
- fix(DB/quest_request_items): typo in Salve via Hunting (#10833)
- fix(Scripts/Raids): some corrections to Broodlord Supression Room: (#10834)
- chore(DB): import pending files
- fix(DB/Pathing) Banthar and Clefthoof formations (#10842)
- chore(DB): import pending files

## 2022-03-02
- fix(DB/creature): Fix Weaver MovementType (#10861)

## 2022-03-03
- chore(DB): import pending files

## 2022-03-02
- fix(DB/creature): Fix Death Howl Spawns (#10871)
- chore(DB): import pending files

## 2022-03-03
- fix(Scripts/BWL): Vaelastrasz improvement (#10845)

## 2022-03-02
- chore(DB): import pending files
- fix(DB/Loot): Only drop Draconic for Dummies if the player has the quest (#10818)
- feat(DB/Account): Delete auto increment in account table (#10879)
- chore(DB): import pending files
- fix(DB): add missing pathing to Delmanis the Hated (#10804)
- fix(Scripts/Commands): solve crash in .npc move (#10825)
- chore(DB): import pending files
- fix(DB/Spells): add internal proc cooldown to Nature's Grasp (#10757)
- chore(DB): import pending files
- fix(DB): Horde and Neutral Quest Emotes - Desolace, Thousand Needles, Stranglethorn (#10747)
- chore(DB): import pending files
- fix(DB): Stonetalon and Ashenvale Horde Quest Emotes (#10745)

## 2022-03-01
- chore(DB): import pending files
- fix(DB): Fineous Darkvire Pathing (#10707)

## 2022-03-02
- fix(Scripts/Ulduar): Flame Leviathan first time engage (#10809)

## 2022-03-01
- chore(DB): import pending files
- fix(DB/gossip_menu_option): Theramore Guards gossip (#10706)
- chore(DB): import pending files
- fix(DB/creature_loot_template): do Not Allow Stonemaul Banner to drop NPCs (#10704)
- feat(bash): bumped inst_download_client_data to v13 (#10755)
- chore(DB): import pending files
- fix(DB): Azuremyst Isle Quest Emotes (#10700)
- chore(DB): import pending files
- fix(DB/creature_queststarter): The Hunter's Charm Questgivers (#10697)
- chore(DB): import pending files
- fix(DB): startup error (#10865)
- chore(DB): import pending files
- fix(DB/BlackwingLair): add missing spawns in Halls of Strife (#10454)
- chore(DB): import pending files
- fix(DB): Emotes for quest Easy Strider Living (#10696)
- fix(Core/Mail): do not show expired mails in packets (#10560)
- chore(DB): import pending files
- fix(DB): Exodar Camera Shake While Mounted (#10694)
- refactor(Core/Packet): Pet (#9473)
- chore(DB): import pending files
- fix(DB): Dolanar First Aid Trainer Dialogues (#10499)

## 2022-02-27
- fix(Core/Database): use char guid if character order is null (#10243)

## 2022-02-26
- chore(DB): import pending files

## 2022-02-27
- fix(DB): Add gossip flag to Expedition Commander (Ulduar) (#10800)

## 2022-02-26
- chore(DB): import pending files
- fix(DB/Pathing): Nagrand Dust Howlers, Storm Ragers, and Living Cyclones (#10824)
- fix(Scripts/Kalimdor): fix Azuregos respawn timer not persisting after restarts (#10823)
- fix/feat: (Core/PacketIO): updated sound and creature addon (#10813)

## 2022-02-25
- chore(DB): import pending files
- fix(DB/creature): Tharnariun Treetender Orientation (#10693)
- chore(DB): import pending files
- fix(DB/SAI): Jesthenis Sunstriker and Matron Arena (#10692)
- chore(DB): import pending files
- fix(DB/SAI): add Missing Imp to Yasmine Teli'Larien (#10691)
- chore(DB): import pending files
- fix(DB/Spells): Amplify/Dampen Magic buff should not block each other from casting (#10563)

## 2022-02-24
- chore(DB): import pending files
- fix(DB/Spawning/Pathing): Wild Elekk, Nagrand (#10815)
- chore(DB): import pending files
- fix(DB/creature_text): add missing line to General Krakork (#10690)
- fix(Core/Creatures): correct applying swimming moveflag to creatures in water (#10756)
- chore(DB): import pending files
- fix(DB/quest_template_locale): add missing zhTW quest text for quests 8249 to 8474 (#10688)
- fix(Core/Spells): auto attack only selected target when charge is over (#10541)

## 2022-02-23
- chore(DB): import pending files
- fix(DB/Loot): add loot to Training Dummy (#10648)

## 2022-02-22
- fix (core): server.log dump (#10742)
- fix(SQL) (#10790)
- chore(DB): import pending files
- fix(DB): Many Quest Emote Fixes from TrinityCore (#10751)
- fix(Core): Crashfix. (#10744)
- chore(DB): import pending files
- fix(DB/Creature) Fix an error in a previous PR (#10789)
- fix(Core/Battlegrounds): Fixed Alterac Valley quests. (#10754)
- fix(Core/Spells): Don't allow to purge Azuregos' Reflect (#10723)
- fix(Core/Spells): Azuregos teleport should only drop threat for hit units (#10722)
- fix(Core/Spells): Azuregos' Mana Storm should not be interruptable (#10721)
- chore(DB): import pending files

## 2022-02-21
- fix (db): Smolderthorn Berserker not attacking (#10785)
- feat(Core/Battlegrounds): Min level of selected random bg must be lower than pvp bracket level. (#10752)
- feat(CI): add mod-low-level-rbg module (#10764)

## 2022-02-20
- feat(Scripting/Hooks): Implement OnGameEventCheck() hook (#10761)
- fix(Core/Battlegrounds: Fixed doubled score in Alterac Valley battleground. (#10743)
- chore(DB): import pending files
- fix(DB/Factionchange): add quests for T0.5 chain (#10646)
- fix(Core/Misc): Remove from LFG/batleground queues when teleported to battleground/LFG dungeon. (#10740)
- fix(Scripts/Scholomance): Darkmaster Gandling crash (#10546)

## 2022-02-19
- fix(Core/GameObjects): move activation code of traps to GO_ACTIVATED (#10537)
- chore(DB): import pending files
- fix(DB/gossip_menu): add missing text to Ragged John gossip menu (#10623)
- fix(Core/Spells): Deep Freeze should damage only permanent stun-immuned targets (#10452)
- chore(DB): import pending files

## 2022-02-18
- fix(DB/creature): Ghostpaw Runner position (#10617)

## 2022-02-19
- chore(DB): import pending files

## 2022-02-18
- fix(DB): Sian'dur and Xor'juul Gossip Fix (#10614)

## 2022-02-19
- chore(DB): import pending files

## 2022-02-18
- Add (DB\Gameobject): Missing Bon Fires VOS (#10738)

## 2022-02-19
- chore(DB): import pending files

## 2022-02-18
- fix(DB/Pathing) Hellfire Peninsula (#10739)
- chore(DB): import pending files
- fix(DB/Spawning/Pathings/SAI) Hellfire Mines (#10737)
- chore(DB): import pending files
- fix(DB/npc_text): Fix Kraz Gossip Text (#10720)
- chore(DB): import pending files
- fix(DB/Spawning/Pathing/SAI) Telaar, Nagrand (#10736)
- chore(DB): import pending files
- Add (DB/SAI): Raider Jhash and Raider Kerr Durotar TC Cherry pick (#10716)
- fix(Core/Creature): Allow Multi id in areas with zone script (#10735)
- fix (core): Final Override to Final (#10731)
- chore(DB): import pending files
- fix(DB/Creature): Fix equipment on older PRs (#10732)
- fix(Core/Creature): Allow setting no equipment. (#10730)
- fix (core): BG Final Override to Final (#10729)
- chore(DB): import pending files
- fix(DB/Creatures): correct spawn of Arcanist Janeda (#10669)
- chore(DB): import pending files
- fix(DB/Loot): Corrected skinning loot for Scorpid Workers. (#10667)

## 2022-02-17
- fix(Core/Guild): Guild bank handling issues (#10724)
- chore(DB): import pending files
- fix(DB/npc_text): Journal of Jandice Barov (#10719)
- chore(DB): import pending files

## 2022-02-18
- feat(Core/Battleground): split Arena and Battleground score (#10616)

## 2022-02-17
- chore(DB): import pending files
- fix(DB/creature_template): Alanndarian Nightsong Gossip Menu (#10689)
- chore(DB): import pending files
- fix(DB/Gameobjects): Basic Campfire should always give Cozy Fire  (#10665)
- chore(DB): import pending files
- fix(DB/Creatures): Nat Pagle should display vendor icon if player completed Nat's Measuring Tap quest. (#10657)

## 2022-02-16
- chore(DB): import pending files
- fix(Core/Battleground/PvPstats): correct bracket_id for AV (#10677)
- Fix (Conf): Add Gossip exemption for AZ Catelogue (#10705)
- chore(DB): import pending files
- fix(Core/Spells): Nefarius Corruption should only affect Vaelastrasz (#10701)

## 2022-02-15
- chore(DB): import pending files
- fix (core\db): SAI Error Reporting (#10698)
- chore(DB): import pending files
- feat(Core/SmartScripts): Warn when an unused parameter is set in the database (#10124)
- fix(Core/Spells): Base spell resistances from auras should apply to pets. (#10562)
- chore(DB): import pending files
- fix(DB/Creature) Highperch Soarer (#10253)
- chore(DB): import pending files
- fix(DB): Seer Skaltesh Elemental Sapta (#10637)
- fix(Core/Spells): Crown Parcel Service Uniform should dismount players (#10654)
- chore(DB): import pending files
- fix(DB/gameobject): Truesilver Node Underground (#10605)
- fix(Scripts/Spells): revive pets always with full health during battlegrounds (#10647)
- chore(DB): import pending files
- fix(DB/Raids): Razorgore the Untamed should pull together with Gorthek the Controller. (#10640)
- fix(Scripts/BlackwingLair): Chromaggus should cast the same affliction spell among players. (#10644)

## 2022-02-14
- chore(DB): import pending files
- fix(DB/creature_questitem): some Missing Quest Markers (#10636)

## 2022-02-15
- fix(Scripts/BlackwingLair): Razorgore adds should spawn 45 seconds after Razorgore's combat engagement (#10641)

## 2022-02-14
- chore(DB): import pending files
- fix(DB/quest_template_addon): The Brokering of Peace Quest Order (#10634)
- fix(Core/Scripts/BWL): Vaelastrasz Burning Adrenaline (#10626)
- chore(DB): import pending files
- fix(DB): Hidden Farm (#10624)
- fix(Scripts/BWL): Blast Wave timer (#10622)
- chore(DB): import pending files
- fix(DB): Script Kwee Q. Peddlefeet (#10621)
- refactor(Core/DB/playercreateinfo_spell_custom): Load empty (#10595)
- chore(DB): import pending files
- fix(DB/creature): Wildthorn Stalker under ground (#10619)
- refactor(Core/Misc): rename some variables that can be confusing (#10592)
- fix(Core/Misc): Change const to be after type name (#10591)
- chore(DB): import pending files
- fix(DB/Gameobject): Preserved Threshadon Carcass should be despawned before the event. (#10543)

## 2022-02-13
- chore(DB): import pending files
- fix(DB/GameObject): despawn traps of Warpwood Pod after being activated (#10539)
- feat(Core/Conf): Rate.MissChanceMultiplier (#10639)

## 2022-02-12
- fix(Scripts/Kalimdor): Azuregos should respawn within 2 and 3 days (#10645)
- chore(DB): import pending files
- fix(DB/Creatures): Death Talon Wyrmguard should gain extra auras. (#10456)
- fix(Core/Spells): Flasks should not be overridden by elixirs. (#10301)
- chore(DB): import pending files
- fix(Scripts/BlackwingLair): Razorgore The Untamed misc improvements (#10205)

## 2022-02-11
- fix(Core/SmartScripts): SMART_ACTION_SET_CORPSE_DELAY, SMART_ACTION_DISABLE_EVADE and SMART_ACTION_GO_SET_GO_STATE are valid actions. (#10538)
- fix(Scripts/Commands): Improve server debug command (#10528)
- chore(DB): import pending files
- fix(DB/item_template): Adjust Deathbringer Proc Rate (#10620)
- fix(Scripts/UBRS): fix crash with Solakar minions (#10638)
- chore(DB): import pending files
- feat(DB/spell): rename fields according to their DBC equivalent (#10633)
- fix(Core/Misc): Remove invalid comment (#10523)
- fix(Scripts/ThousandNeedles): Add final waypoint dialog for quest 4904 "Free at Last" (#10517)
- chore(DB): import pending files
- fix(DB/Creature): Grimbooze Thunderbrew Missing Gossip (#10501)
- Fix(Core/Instance): Chromaggus reset (#10473)
- feat(Core): Enable C++20 support (#10440)
- fix(Core/Spells): Shadowflame should not be interruptable (#10437)
- chore(DB): import pending files
- fix(DB/Formations): Death Talon Captain chain pull (#10436)
- refactor(Core/Packets): Rewrite MSG_RANDOM_ROLL to new packet class (#10590)
- chore(DB): import pending files
- fix(Core/Events): Apothecary Hummel (#10615)
- fix(Core/Misc): Remove Clang 7 workaround (#10521)

## 2022-02-10
- chore(DB): import pending files
- fix(Core/Quest): For The Horde!  (#10330)
- refactor(Core/Creature): More functions capitalized (#10012)
- fix(Core/Spells): Added some exceptions to `SPELL_AURA_PREVENT_REGENE… (#9844)
- fix(Core/GameObjects): Do not allow players to interact with gobs that use "Point" icon (#9800)
- chore(DB): import pending files
- fix(Scripts/Spell): Don't use invalid spells for the Magic Rooster mount (#9797)
- chore(DB): import pending files
- fix(Core/WorldBoss): Azuregos rewrite (#10369)
- fix(Chat): session null check for isavailable (#10613)
- refactor(Script/Event): convert midsummer into new system (#9607)

## 2022-02-09
- feat (core): Add Teleport Helpers (#10611)

## 2022-02-10
- feat(Core/Grids): Allow arbitrary containers in grid searchers that support push_back

## 2022-02-09
- feat(Core/Player): Implement option to convert excess honor points int… (#10565)
- chore(DB): import pending files
- Fix (Core/Scripts): Warrior T3 8P Bonus Fix (#10561)
- chore(Scripts/Events): fix typo (#10604)
- refactor(Core/Misc): sqrt/log/exp() to std::sqrt/log/exp() (#9792)
- fix(Core/BG): store correct faction id (#10576)
- Fix(Core/Crash): possible crash due uninitialized value (#10602)
- fix(Scripts/Events): Fix not being able to start the Apothecary Trio … (#10596)

## 2022-02-08
- chore(DB): import pending files

## 2022-02-09
- fix(DB/Creatures): Razormaw should move on waypoints (#10455)
- docs(SECURITY): macOS 11 support (#10481)

## 2022-02-08
- fix(Core/Spells): Revert an oopsie (#10598)
- chore(DB): import pending files
- fix(DB/Spawn): Death Talon Overseer (#10434)
- refactor(Core/Spells): Move SpellInfoCorrections to its own file (#10587)
- refactor(Core/Spell): Use ApplySpellFix with SpellInfo (#9938)
- fix(Core): macOS build (part 2) (#10586)
- fix(Core/Build): macOS build (part 1) (#10549)
- feat(Core/Position): own file (#10505)

## 2022-02-07
- fix: (core) Game Hook Correction (#10572)
- fix(Scripts/MoltenCore): Ragnaros dying while submerging (#10535)
- chore(DB): import pending files
- fix(DB/SAI): Blackwing Technician (#10433)

## 2022-02-06
- chore(DB): import pending files
- fix(DB/Creature): Shen'Dralar wisp movement (#10405)

## 2022-02-05
- fix (conf): Added additional Cateloge NPC IDS (#10547)
- fix(Scripts/Commands): cs_list crash (#10480)
- fix(Core/Reputations): Faction rep gained by killing mobs is now prop… (#9737)

## 2022-02-04
- chore(DB): import pending files

## 2022-02-05
- feat(Core/DBLayer): replace `char const*` to `std::string_view` (#10211)

## 2022-02-04
- chore(DB): import pending files
- fix(DB/Loot): Un'Goro Dirt Pile (#10404)
- chore(DB): import pending files
- fix(DB/Item): Bonereaver's Edge proc (#10393)
- chore(DB): import pending files
- fix(DB/Gossip): show correct gossips for Shadow Priestess Vandis and High Priestess MacDonnell (#10392)
- chore(DB): import pending files
- fix(DB/Gossip): Angela Dosantos (#10389)
- fix(Core/Spells): Wolverine Bite (#10312)
- chore(DB): import pending files
- fix(DB): add missing dialogue page text for Old Orok (#10431)
- fix(Core/BWL): do not open Nefarian door until Chromaggus is defeated (#10472)
- chore(DB): import pending files
- fix(DB/Creatures): Ebonroc should move on waypoints (#10457)
- fix(Core/Misc): Remove c++ check for c++11 (#10439)
- chore(DB): import pending files
- fix(DB/spell_proc_event): Lawbringer's T1 8 Set Bonus Fix (#10402)
- feat(Core/Map): add DoForAllPlayers method (#10371)
- chore(DB): import pending files
- fix(DB/Vendor): Zorbin Fandazzle's gossip (#10361)
- feat(Core/Player): Stats limitation (#10403)
- chore(DB): import pending files
- fix(DB/Quest): move Lost In Battle to DB (#10378)
- refactor(Core/GuildHandler): remove unused function (#10375)
- feat(Core/Conf): handle custom creatures IDs and exclude them from checks (#10367)
- chore(DB): import pending files
- fix(DB/Skills): Thrown on create troll warrior (#10351)
- feat(Core/Conditions): CONDITION_DIFFICULTY_ID (#10332)
- chore(DB): import pending files
- fix(DB/Gameobjects): Thwarting Kolkar Aggression objects should not be interactable without quest (#10326)
- fix(Core/Spells): delete creatures threat list after taming them for t… (#10224)
- feat(Core/Common): move EventMap to separated files, add support chrono (#10209)
- chore(DB): import pending files
- fix(DB/Quest): Matis the Cruel (#10380)
- fix(Scripts/MoltenCore): Separate teleport timers for Majordomo Executus (#10348)
- chore(DB): import pending files
- fix(DB/SAI): Removing Thrash from Creatures (#9746)

## 2022-02-03
- chore(DB): import pending files
- fix(DB): Draenei Start Area Class Training Quests Fixes (#10488)
- chore(DB): import pending files
- fix (DB): Blacksmithing Plans Loot and Conditions (#10391)
- chore(DB): import pending files
- fix(DB/creature_template): Trial of the Champions Gossip Menu (#10487)
- chore(DB): import pending files
- fix(DB/creature): Double critter spawns in Dire Maul East (#10484)
- chore(DB): import pending files
- fix(DB/item_template): Fix Deathbringer Proc Rate (#10492)
- chore(DB): import pending files
- fix(DB/creature): Ram inside Thelgen Rock (#10486)
- chore(DB): import pending files
- fix(DB): Underground Wildkin Feather for Quest 3661 (#10482)
- chore(DB): import pending files
- fix(DB): Tallonkai Swiftroot has incorrect dialogue texts (#10479)
- chore(DB): import pending files
- feat(Guild/Commands): guild rename (#10323)

## 2022-02-02
- fix(Core/Player): Align SaveSeasonQuestStatus() with TrinityCore (#10503)

## 2022-02-03
- feat(Deps/Fmt): update to 8.1.1. Fix build with c++20 (#10489)

## 2022-02-02
- Revert "fix (core): Smart Script Clean up\Code Reduction (#10491)" (#10494)
- fix (core): Smart Script Clean up\Code Reduction (#10491)
- refactor(Core/Hook): OnPlayerReputationChange (#10471)

## 2022-02-01
- Revert "fix(Core/Spells): Fix spellclick (#8232)" (#10483)
- chore(DB): import pending files
- fix(DB/CTM): Fix Onyxia float on ground at P2 (#10191)
- chore(DB): import pending files
- fix(DB/Quest): completing quest "Freedom to Ruul" (#10325)
- fix(Scripts/Pets): Increased Shadowfiend hp. (#10304)
- fix(CMake/MSVC): Cleanup and enable some warnings (#10295)
- fix(CI/Misc): Make CodeFactor happy (#10468)

## 2022-01-31
- feat(Core/Scripting): Implement OnLoadSpellCustomAttr global hook (#10469)
- chore(DB): import pending files
- feat(Scripts/Commands): Implement go quest starter/ender command (#10442)
- chore(DB): import pending files
- fix(DB/Loot): Sarkoth's quest item drop chance (#10320)
- chore(Core/Texts): Rename parameter for creature texts (#10317)
- fix(Core/Scripting): Fix healing reduction abilities not applying cor… (#10435)
- chore(DB): import pending files
- fix(Core/Spells): Implemented SPELL_GROUP_SPECIAL_FLAG_SKIP_STRONGER_SAME_SPELL. (#10307)

## 2022-01-30
- fix(Core/Spells): Removed MECHANIC_POLYMORPH from PX-238 Winter Wondervolt spells. (#10302)
- chore(DB): import pending files
- fix(DB/Spawning/Pathing): Zeth'Gor, Hellfire Peninsula (#10453)
- fix(Core/DungeonFinder): Fixed joining to LFG dungeon if there is alr… (#10062)
- fix(C++20): Windows build (#10438)
- chore(DB): import pending files
- fix(DB/Creatures): Fixed spawn points of some quest starting NPCs. (#10306)
- chore(DB): import pending files
- fix(DB/Spells): Restored old values for Flurry. (#10305)
- feat(Core/Conditions): CONDITION_PET_TYPE (#10299)

## 2022-01-29
- chore(DB): import pending files
- fix(DB/Pathing): Winterspring Rares (#10432)
- chore(DB): import pending files
- fix(DB/Gossips): Show the correct gossip for portal trainers (#10291)
- fix (core) : TransportMgr Load up time (#10388)
- feat(Core/SmartScripts): Add distance option for SMART_ACTION_SOUND & SMART_ACTION_RANDOM_SOUND (#10255)
- chore(DB): import pending files
- feat(DB): release ACDB 5.0.0 (#10292)
- feat(Core/Conditions): CONDITION_TAXI
- feat(Core/Conditions): CONDITION_CHARMED (#10298)
- fix(Core/Pathfinding): Remove unnecesary LiquidData Z check (#10251)
- chore(DB): import pending files

## 2022-01-28
- fix(DB/Gossip): Myranda the Hag (#10411)
- chore(DB): import pending files
- fix(DB/Spells): Added food spells to stack rules (#10277)

## 2022-01-29
- feat(Core/SmartScripts): SMART_ACTION_PLAY_CINEMATIC (#10231)

## 2022-01-28
- fix(Core/Misc): Revert commits causing massive delays (#10408)
- chore(DB): import pending files
- fix(DB/Loot)Fixed wrong drop loot from creatures (#10226)
- fix(Core/Spells): Removed Focused/Brutal on map change. (#10105)
- fix(Core/Spells): Reset melee swing timer on  cast rather than on finish. (#10101)
- fix (core): Delay added so spell animation plays on unit death (#10394)
- fix (core): EffectInstaKill Prevents spell animation fix (#10379)
- chore(DB): import pending files
- fix(DB/Creature): Omen does not reset HP (#10359)
- chore(DB): import pending files

## 2022-01-27
- fix(DB/Loot) Level 1 - 5 fixes (#10390)

## 2022-01-28
- fix(Core/Spell): Summon Arcane Disruptor

## 2022-01-27
- chore(DB): import pending files
- fix(DB/Creature): Add Deathclasp and his scorpions to formations (#10240)
- chore(DB): import pending files
- fix(DB/Quest): Add missing objective marker quest 9454 (#10281)
- refactor(Core/Logging): switch to fmt style for LOG_ (#10366)
- chore(DB): import pending files
- fix(DB/Loot): Frostwhisper's Embalming fluid can be looted without the quest (#10238)
- chore(DB): import pending files
- fix(DB/Creatures): Creature Placements Northeast of Dolanaar (#10285)
- chore(DB): import pending files
- fix(DB/Creature): Creature Placements Southeast of Dolanaar (#10282)
- feat(Core/Logs): Improve logs for linked_respawn (#10202)
- chore(DB): import pending files
- fix(DB/Formations): Lord Vyletongue is now linked to his adds (#10275)
- feat(Core/Chat): delete delay for channels (#10365)

## 2022-01-26
- fix(Core/MC): Core Hounds should despawn after death (#10219)
- chore(DB): import pending files
- fix (DB): fix Ravager Spicimens overpopulation (#10377)
- chore(DB): import pending files
- fix(DB/Creature): adjust Whip Lasher damage (#10273)
- feat(Core/Common): add support fmt style for ASSERT and ABORT (#10355)

## 2022-01-25
- chore(DB): import pending files

## 2022-01-26
- fix(Core/Logs): improve log money (#10297)

## 2022-01-25
- chore(DB): import pending files
- fix(DB/Creature): Add Flame Imp formations (#10234)
- feat(Core/Player): allow to queue both RDF & BGs together (#10102)
- fix(Core/Spells): Remove vanish immunity aura on stealth removal. (#10106)
- fix(Core/Spells): Ensures that Moonkin Aura is always casted with Moonkin Form. (#10195)

## 2022-01-24
- fix (core/pdump): Fix Pdump write and load thru TC Cherry picks (#10349)

## 2022-01-25
- chore(DB): import pending files
- fix(Scripts/Spell): properly script collapsing cave aura (#10092)
- chore(Core/Logging): add default logger for modules (#10341)

## 2022-01-24
- chore(DB): import pending files
- fix(Core/Spells): Implemented spell proc phases. (#9725)
- fix(Core/Logs): fixed wrong decription of error during server startup
- fix(Core/MC): Randomize shields for Majordomo Executus (#10270)
- chore(DB): import pending files
- feat(Core/Time): Implement saparated manager for game time (#8630)
- chore(DB): import pending files
- fix(DB/GO): Pools of Arlithrien moonwell should be invisible (#10203)
- fix(Core/Spells): correct teleport distance for Shadowstep/Killing Spree/Warp (#10081)
- fix(Scripts/Commands): quest complate kill reward (#9926)
- chore(DB): import pending files
- fix(Scripts/Hunter): Bestial Wrath shoul not be castable on dead pets. (#9896)
- chore(DB): import pending files

## 2022-01-23
- fix(Spawning/Pathing): Tunnelers, Hellfire Peninsula (#10329)

## 2022-01-24
- fix(Core/Spells): Fixed Revive Pet. (#10324)

## 2022-01-23
- feat(Core/Scripting): Implement OnSpellHealingBonusTakenNegativeModifiers hook (#10318)
- chore(DB): import pending files
- fix(DB/GO): correct ground position for Cluster Launchers (#10197)
- feat(Core/Cmake): add support MariaDb 10.7 and 10.8 (#10322)
- chore(DB): import pending files
- fix(DB/Quests): The Shadow Guard and The Ice Guard should be repeatable (#10222)
- fix(Core/Spells): Passive auras with SPELL_ATTR0_ONLY_INDOORS/SPELL_A… (#9837)
- fix(Scripts/Omen): Giant Spotlight NPC should be not selectable. (#10198)

## 2022-01-22
- chore(DB): import pending files
- fix(DB/Pathing/SAI): The Abyssal Shelf, Hellfire Peninsula (#10310)
- chore(DB): import pending files
- fix(Core/Stratholme): Some adjustments to Jarien and Sothos fight (#10269)
- chore(DB): import pending files
- fix(DB/Creature): Shatterspear Trolls respawn time (#10283)
- chore(DB): import pending files
- fix(DB/Pathing): Razorfang Ravager, Hellfire Peninsula (#10303)
- chore(DB): import pending files
- fix(DB): UBRS Creature formations (#10233)
- refactor(Core): remove unused imports (#10296)
- chore(DB): import pending files

## 2022-01-21
- fix(DB/NPC): WP for stormwind guard guid 79875 (#10294)
- fix(Core/BWL): Vaelastrasz reset after wipe (#10176)
- fix(Core/Spells): Restored special Rolling DoTs mechanic for Corruption and SW:Pain (#10206)
- chore(DB): import pending files
- fix(DB/Loot): Remove invalid loot from Flamewaker Healer (#10280)
- chore(DB): import pending files
- fix(DB/Creature): Shadowforge Surveyor movement (#10284)
- feat(Core/ScriptMgr): add new hook `OnAfterUnloadAllMaps` (#10279)
- chore(DB): import pending files
- feat(Core/Common): delete old Tokenizer (#10121)
- chore(DB): import pending files
- fix(DB/Quest): Conditions for Replacement Vial (#9908)
- feat(Core/Database): add support set arguments for PrepareStatment (#10066)

## 2022-01-20
- fix(Scripts/Stratholme): Cancel Baron's Ultimatum event after Baron dies (#10242)
- fix(Core/Spells): Properly handle client-side orientation on stun. (#10107)
- fix(Core/Quest): A Rogue's Deal should be completed if pet lands the killing blow (#9917)
- chore(DB): import pending files
- feat(Core/DB/Creature): Throw error if npcflag and gossip_menu_id is not c… (#9665)
- fix(Core/PetAI): Combat spells should be casted when pet starts attack. (#9845)

## 2022-01-19
- chore(DB): import pending files
- fix(Scripts/DB): Terenthis quest chain (#9714)
- chore(DB): import pending files
- Fix(DB/BWL): Vaelastrasz trash (#10184)
- chore(DB): import pending files
- fix(DB/Pathing): Marauding Crust Bursters, Hellfire (#10246)
- fix(DB/Pathing): Crust Bursters, Hellfire (#10245)
- chore(DB): import pending files
- fix(DB/Pathing): Fel Reavers, Hellfire (#10244)
- chore(DB): import pending files
- fix(DB): Befouled Water Elemental CTM (#10145)
- feat(Core/Common): add new helpers for time utility (#10207)

## 2022-01-18
- chore(DB): import pending files
- fix(db): Shadowglen creatures with missing ids added. (#10196)
- chore(DB): import pending files
- fix(DB/Pathing): Pterrordax & Fledgling Pterrordax (#10189)
- chore(DB): import pending files

## 2022-01-17
- fix (DB/Misc): Rename tele OldIronForge (#10225)

## 2022-01-18
- chore(DB): import pending files

## 2022-01-17
- fix(DB/Spawning/Pathing) Jadefire Run, Felwood (#10188)
- chore(DB): import pending files
- Add (DB/Misc): Add OldScarletMonastery (#10216)
- chore(DB): import pending files
- fix(DB/CreatureLoot) Felhunter (417) (#10215)
- refactor(Core): apply clang-tidy modernize-* (#9975)
- feat(Core/Conditions): Implement CONDITION_SOURCE_CREATURE_VISIBILITY (#10208)
- fix(Core/Events): Prevent seasonal quests from resetting at server re… (#9708)
- fix(Core/Spells): Drop combat on Mind Control cancel. (#10201)
- fix(Scripts/Instances): Fixed some problems with getting proper unit'… (#10193)

## 2022-01-16
- fix(Core/Pets): Manual using pet spell should not reset attack command. (#9635)
- fix(Core/Spells): Charging unit should always reach its target even if stunned/rooted. (#10192)
- chore(DB): import pending files
- fix(DB/Formations): Molten Core Giants creature_formation (#10116)
- fix(Core/Packets): Display item suffixes in guild bank packet. (#10200)
- fix(Core/Handlers): Correctly updating faction and race change on packet. (#10199)
- fix(Scripts/BRD): Arena Spoils shouldn't despawn whem High Justice Grimstone is removed from world (#10140)
- chore(DB): import pending files
- fix(Scritpts/MoltenCore): Add immune to pc & npc flags to Ragnaros (#10179)
- chore(DB): import pending files

## 2022-01-15
- chore(DB/Creature): LBRS guid conflict resolve (#10194)
- fix(Scripts/Spells): fix a crash with Scent of Blood talent (#10078)

## 2022-01-16
- fix(Core/Pets): fix crash at pet resurrect (#10120)

## 2022-01-15
- chore(DB): import pending files
- fix(DB): Teldrassil herbalism gameobject re-construction (#10170)
- fix(Core/Spells): Added `SPELL_AURA_MOD_ABILITY_IGNORE_TARGET_RESIST`… (#9764)
- chore(DB): import pending files

## 2022-01-14
- fix(DB/Spawning/Pathing): Felpaw Village, Felwood (#10187)

## 2022-01-15
- chore(DB): import pending files

## 2022-01-14
- fix(DB/Spawning/Pooling/Pathing) Devilsaurs, Un'goro (#10171)
- chore(DB): import pending files
- feat(Core/Creature): Allow 3 ids per spawn point. TESTING (#10169)
- chore(DB): import pending files
- fix(DB): Lower Blackrock Spire creature import (#10079)
- chore(DB): import pending files
- fix(DB/Quests): some corrections for Winter Veil quests (#10103)
- fix(Core/Mail): Include 100g in the mail for The Wrath of Neptulon (#10093)
- refactor(Core/Misc): isEmpty to IsEmpty (#10011)
- chore(DB): import pending files
- fix(DB/Gameobjects): Removed invalid spawn of Gromsblood in Azuremyst… (#10087)
- chore(DB): import pending files
- fix(DB/GameEvents): Some gameobjects outside Exodar should spawn only during specificgame events. (#10084)
- chore(DB): import pending files
- fix(DB/Loot): Corrected some loot tables. (#10074)

## 2022-01-13
- fix (core\script) Double to Float Fix (#10161)

## 2022-01-14
- fix(Core/Build): Fallthrough (#10165)

## 2022-01-13
- chore(DB): import pending files
- fix(Core/GM Commands): Update NPC Info command (#10157)
- fix(Core/Quests): Do not remove inventory items/non-empty bags on quest reward. (#10073)
- fix(Core/BWL): Suppression traps can be disarmed (#10163)
- fix (Core/CodeReduction) TC_ removal (#10162)
- chore(DB): import pending files
- fix(DB/Pathing): Stone Guardians, Un'Goro Crater (#10160)
- chore(DB): import pending files
- fix(DB/broadcast_text): align some column names (#10090)
- fix(Scrips/BlackrockSpires): add missing `_JustDied()` to Halycon script (#10065)
- chore(DB): import pending files
- feat(Scripts/SmartAI): SMART_TARGET_INVOKER (#9802)

## 2022-01-12
- fix(Core/Waypoint Show): Fixed error with waypoint show. (#10148)
- fix (Core/CTM) Water Evade Fix (#10147)
- chore(DB): import pending files
- fix(DB/Loot): Goblin Rocket Fuel and Discombobulator Ray should always drop off Mux's Quality Goods (#10141)
- chore(DB): import pending files
- fix(DB/GameEvents): Updates start dates of all yearly game events. (#10068)
- chore(DB): import pending files
- fix (DB\CTM): Redridge Mulocs CTM added (#10118)
- chore(DB): import pending files
- fix(DB\CTM): Hydroflask CTM
- chore(DB): import pending files
- fix(DB\Creature\Instance): Maraudon CTM fix (#10122)
- chore(DB): import pending files
- fix(DB\CTM): Wailing Caverns CTM (#10132)

## 2022-01-11
- chore(DB): import pending files
- fix(DB/Spawning/Pathing/SAI) Winterfall Furbog (#10134)
- chore(DB): import pending files
- fix(DB/Creature): Dual Spawning Creature Update (#10127)
- fix(Core/Dual Spawning) Change rand to roll_chance_f (#10130)
- chore(DB): import pending files
- fix(DB/Conditions): Core Hounds and Firesword respawn (#10112)
- chore(DB): import pending files

## 2022-01-10
- feat(Core/Creature): Dual id Spawning WIP (#10115)

## 2022-01-11
- chore(DB): import pending files
- fix(DB\Creature): Flamewaker bleed immunity removal (#10117)
- chore(DB): import pending files
- fix(DB/GameEvents): Great-Father Winter's Helper NPCs should be present only during Winter Veil: Gifts event. (#10064)
- Fix (Core): add missing default,break. (#10114)

## 2022-01-10
- chore(DB): import pending files
- BREAKING CHANGE:(DB/Creature) Remove modelId field in creature table (#10071)
- chore(DB): import pending files
- fix(DB): Add missing creatures and gameobject pools in Fel Rock (#10052)
- chore(DB): import pending files
- fix(DB/Pathing) Everlook, Winterspring (#10089)
- chore(DB): import pending files
- feat(Core/SmartScripts): Add a warning when a boolean value is outside of [0,1] range (#10038)
- fix (Core/Creature): Random Gender on respawn if Gender exsist for Entry (#10108)
- fix(Core/Pets): fixed crash happening when current pet is forcibly removed (#10025)

## 2022-01-09
- chore(DB): import pending files
- fix (DB/NPC): Dalaran Visitor CTM fix (#10058)
- fix(Scripts/MoltenCore): Solve edge case that caused Majordomo to spawn double adds (#10076)
- refactor(Core/Unit): Split spell things into SpellDefines.h (#10009)
- refactor(Core/Packet): Combat log (#9673)
- chore(DB): import pending files
- feat(DB/Creature): Allow to set swim and flight speeds (#10067)

## 2022-01-08
- chore(DB): import pending files
- fix(DB/Pathing) Timbermaw Hold (#10072)
- fix(Scripts/Icecrown Citadel): Ensure Deathbringer Saurfang casts Frenzy (#10048)
- fix(Scripts/MoltenCore): Ensure Majordomo minions that completely despawned respawn on wipes (#10061)
- refactor(Core/Packet): Chat (#9509)

## 2022-01-07
- chore(DB): import pending files
- fix(DB/GameEvents): Added missing spawn of Melnan Darkstone. Source: TrinityCore. (#9657)
- chore(DB): import pending files
- fix(DB/GameEvents): new game event Darkmoon Faire Building (Terokkar Forest)(#9654)
- fix(Core/Entities): extend combo point system to all Units (#9816)
-  feat(Core/SmartScripts): SMART_ACTION_ATTACK_STOP #10053
- fix(Core/Handlers): remove the uint8 cap from guild bank max stacks per day
- chore(DB): import pending files

## 2022-01-06
- fix(DB/Pathing) Swamp of Sorrow (#10042)
- fix(Scripts/Creature): Convert npc_ranger_lilatha script to RegisterCreatureAI (#10043)

## 2022-01-07
- chore(DB): import pending files

## 2022-01-06
- fix(DB/Pathing): Westfall (#10046)
- fix(DB/Pathing): Darkshire (#10044)
- chore(DB): import pending files
- fix(Core/Creature): Fire Elemental Invasion changes (#9372)
- refactor(Core/Misc): sin() to std::sin() (#9795)
- fix(MMAP): Build ADT floor just like WMO floor below liquid (#9990)
- chore(DB): import pending files
- fix(DB/Script): Eastvale Logging Camp, Elywnn Forest (#10036)
- chore(DB): import pending files
- fix(DB/Pathing) Elywnn Forest Guards (#10035)
- chore(DB): import pending files
- refactor(Core/Creature): Remove Inhabit Type (#9272)
- fix(Core\OpCode): HandleFarSightOpcode (#9965)
- refactor(Core/Packet): Character packets (#9546)
- chore(DB): import pending files
- fix(DB\Texts): Goblin pit crew's gossip probability (#9905)
- chore(DB): import pending files
- feat(Core/SmartScripts): Add support to friendly+hostile to SMART_EVENT_OOC_LOS and SMART_EVENT_IC_LOS (#10037)
- chore(DB): import pending files
- Fix (DB\Reputiation): Western Plaguelands monster reputation (#10020)
- Fix (DB\MOB): Mob Timberstrider Position (#10015)
- fix(DB): Nathanos quest requirements (#10014)
- chore(DB): import pending files
- Fix (DB/Creature): Azuremys Murloc Spawn Correction (#10033)
- chore(DB): import pending files
- Fix (DB\Quest\SmartScript): Quest 9540 Totem of Tiki (#10032)

## 2022-01-05
- chore(DB): import pending files

## 2022-01-06
- Fix (Core\Script) Grammar Correction (#10031)

## 2022-01-05
- chore(DB): import pending files
- fix(DB/Spawning/Pathing) Darrow Hill full respawn with new paths (#10027)
- chore(DB): import pending files
- Feat (Core\DB\Event) Children of Goldshire (WIP) (#10022)
- feat(Core/SmartScripts): SMART_ACTION_SET_MOVEMENT_SPEED (#10018)
- chore(DB): import pending files
- fix(DB/Creature): Centipaar Tunneler attack on summon (#9989)
- feat(Core/Pathing): Add path_id to PathEndReached (#10021)
- feat(Core/SmartScripts): SMART_ACTION_SET_HEALTH_PCT
- NewFunction(Core/Pathing) Path End Reached (#10017)
- chore(DB): import pending files
- Fix (DB\Creature) Adjust Shadowforge Surveyor z-position (#9973)
- chore(AUTHORS): Now it is 2022 (#10013)

## 2022-01-04
- chore(DB): import pending files
- fix(DB): Fixed pathing and creature spawns directly around Dolanaar (#9943)
- fix(DB): Significant Creature improvements in Shadowglen, Teldrassil (#9912)
- Core\Packet\Misc: Weather (#9648)
- chore(DB): import pending files
- fix(DB/Gameobject): Delete unused hack objects (#9999)
- chore(DB): import pending files
- Fix (DB\Loot) Zora Loot fix (#10002)
- Fix (DB\Loot) Copper Bolt Loot fix (#10006)
- chore(DB): import pending files
- Fix (DB\Loot) Frigid Ring Reference Loot Fix (#10004)
- fix(Core/Spells): Add Target Processing (SMSG_SPELLLOGEXECUTE) to LAUNCH_TARGET phase. (#9765)
- feat(Core/SmartScripts): ACTION_GO_SET_GO_STATE
- feat(Core/SmartScripts): SMART_ACTION_SET_CORPSE_DELAY
- fix(DB): fix world imports again (#9991)
- chore(.clang-format): Delete (#9934)

## 2022-01-03
- chore(DB): import pending files
- Fix (DB\Loot) Ez-Thro Dynamite II (#9977)
- chore(DB): import pending files
- Fix (DB\SmartScript\Quest) Catch and Release  (#9987)
- Fix (DB\Loot) Gordok Mastiff's loot table Audit (#9958)
- chore(DB): import pending files
- Fix(Core/Quest): Pet issues with They're Alive! Maybe... (#9918)
- Fix (Core/Movement): During escort movement, do not stop moving if unit is casting channeled spells. (#9815)
- Fix(Core/Item): Wraith Scythe scales with spell power (#9901)
- chore(DB): import pending files
- fix(DB/Creature): Removed duplicated creatures from Midsummer event. (#9710)
- chore(DB): import pending files
- fix(DB): Improved Lord Kragaru and gameobjects (#9904)
- Fix(DB/Quest): Wrong pre-requisite for quest 9706 (#9923)
- chore(DB): import pending files
- fix(Core/Spells): Judgement spells should always set combat event spe… (#9709)
- Fix(DB/Quests): Pre-quest requirement for Lorekeeper Lydros quests (#9900)
- chore(DB): import pending files
- fix(Core/CullingOfStratholme): Chromie start (#9898)
- fix(Scripts/Commands): Look item (#9892)
- fix(Core/Spells): Multi-Shot should not be affected by Glyph of Aimed… (#9897)
- fix(DB/Loot): Remove Bolt of Silk Cloth from creature loot
- chore(DB): import pending files
- Add files via upload (#9877)
- Fix(Core/Creature): Disable shredder should not attack creatures nearby (#9920)
- fix(SQL): Remove wrong comment (#9928)
- chore(DB): import pending files
- fix(DB/SAI): BWL Grethok arcane missiles & immunity flags (#9985)
- chore(DB): import pending files
- fix(DB/Misc): Set default value to `visibilityDistanceType` in `*_addon` tables. (#9658)
- Core/Packet: WorldState (#9435)
- chore(DB): import pending files
- fix(DB/Loot): remove Bolt of Runecloth from creatures
- refactor(Core/Misc): atan2() to std::atan2() (#9793)
- fix(DB/Pathing) Lordamere Internment Camp, Alterac Mountains (#9921)
- fix(DB/Pathing)  Elemental Slaves, Dalaran Crater, Alterac Mountains (#9919)
- fix(DB/Spawns/Pathing) Southshore, Hillsbrad Foothills (#9929)
- fix(DB/Pathing/Equipment) Hammerfall npc movement fixup (#9952)
- fix(DB/Pathing) Solanin, Eversong Woods (#9950)
- fix(Scripting/Spawning/Pathing) An'owyn, Ghostlands (#9935)
- chore(DB): import pending files
- fix(DB/Pathing) Fix some bad paths at Taren Mill (#9910)
- refactor(Core/Misc): ceil() to std::ceil() (#9791)
- fix(Scripts/Spells): fix logic mistake in spell_generic (#9799)
- chore(DB): import pending files
- fix(DB/Pathing/Auras) Forsaken Raiders, Hillsbrad Foothills (#9907)
- feat(Core/SmartScripts): SMART_EVENT_SUMMONED_UNIT_DIES (#9979)
- chore(DB): import pending files

## 2022-01-02
- Fix(DB/Path) Zixil, Hillsbrad Foothills (#9906)

## 2022-01-03
- chore(DB): import pending files

## 2022-01-02
- fix(DB/Walk/Run Speed) Creature speed update for Eversong woods and Ghostlands (#9868)

## 2022-01-03
- chore(DB): import pending files

## 2022-01-02
- fix(DB/Spawns/Pathing) Pathing Ghostlands (#9839)

## 2022-01-03
- feat(Core/SmartScripts): SMART_TARGET_LOOT_RECIPIENTS (#9967)

## 2022-01-02
- chore(DB): import pending files
- fix(Core/DB): adjust commands sec level to follow wiki (#9978)
- chore(DB): import pending files

## 2022-01-03
- fix(DB/Loot): Bolt of Mageweave (#9850)

## 2022-01-02
- refactor(Core): remove unused imports (#9969)
- chore(DB): import pending files
- fix(DB\Gameobject): Missing gameobjects causing world errors (#9964)
- fix(Core/Scripting): Solve issue with client crashes on login (#9971)
- chore(DB): import pending files
- fix(DB/Waypoints): Curator Thorius & Gorlorn Frostbeard waypoints (#9963)
- fix(Core/Object): macOS build (#9968)
- fix(Core): Suppress status opcode after gossip (#9962)

## 2022-01-01
- feat(Core/Scripting): OnBuildValuesUpdate hook (#9961)

## 2022-01-02
- chore(DB): import pending files

## 2022-01-01
- fix(DB/Waypoints): Pathing corrections for 2 NPCs in Shadowglen (#9758)
- chore(DB): import pending files
- feat(Core/Conditions): Implement CONDITION_TYPE_CREATURE_RESPAWN (#9927)
- fix(Core/Players): fix trailing whitespaces being added as settings (#9960)
- fix(Core/Achievement): Don't count bought back items as a new item for ACHIEVEMENT_CRITERIA_TYPE_RECIEVE_EPIC_ITEM (#9798)
- fix(Core/Spells): Dungeon and world bosses are always subject to spell school lockouts. (#9638)
- refactor(Core/Misc): fabs() to std::fabs() (#9790)

## 2021-12-31
- refactor(Core/Misc): abs() to std::abs() (#9789)
- chore(DB): import pending files

## 2022-01-01
- Add files via upload (#9847)

## 2021-12-31
- chore(DB): import pending files

## 2022-01-01
- Add files via upload (#9848)

## 2021-12-31
- chore(DB): import pending files
- Abyssal Crest Loot % correction (#9951)
- chore(DB): import pending files
- Fix (DB\Loot) Remove Tree Frog Loot (#9949)
- fix(Core/Scripting): fix a loop in the affected mod spell hook (#9948)
- chore(Scripts/Misc): Cleanup some more JustDied hooks (#9768)
- refactor(Core/Packets): Totem (#9451)
- chore(DB): import pending files
- fix(DB): Onu quest conditions (#9817)
- chore(DB): import pending files
- fix(DB\Quest): A Visit to the Doctor (#9925)
- chore(DB): import pending files

## 2021-12-30
- fix(DB/Pathing) Brooms, Silvermoon City (#9944)

## 2021-12-31
- chore(DB): import pending files
- fix(DB/Conditions) Spirit of the Vale (#9942)
- chore(DB): import pending files
- fix(DB/Gameobject): Move chairs to AV (#9931)
- feat(Core/Pets): Management refactoring (#9712)

## 2021-12-30
- feat(Core/Scripting): Implement OnIsAffectedBySpellModCheck hook (#9903)
- refactor(Core/Packets): Bank packets (#9627)
- chore(DB): import pending files
- fix(DB/Pathing): Ghostlands Guardians (#9838)
- chore(DB): import pending files
- fix(DB/Quest): Quest "In Dreams" (#9924)
- fix(Core/TemporarySummon): Implement TEMPSUMMON_TIMED_DESPAWN_OOC_ALIVE (#9915)
- feat(Apps/CI): Add check for broadcast_text (#9771)

## 2021-12-29
- chore(DB): import pending files
- fix(DB/Misc): Reimport all broadcast_text entries (#9769)
- fix(Scripts/Silithus): Solve issues with bosses despawing too fast (#9914)
- chore(DB): import pending files
- fix(DB/Loot): Remove Jingling Bell from creature loot (#9909)
- fix(SQL): fix SQL (#9911)
- feat(Core/AI): convert `SelectAggroTarget` to enum class (#9893)

## 2021-12-28
- chore(DB): import pending files
- fix(DB/Spawning) Respawn Stonewing Trackers, Ghostlands (#9829)
- chore(DB): import pending files
- fix(DB/SAI/Creature text) Dar'Khan Drathir, Deatholme, Ghostlands (#9828)
- chore(DB): import pending files
- fix(Scripts/Silithus): Wind Stone summons roleplay & despawn (#9899)
- fix(Core/Players): Removed old and invalid `Player::SetInWater` funct… (#9739)
- fix(Core/Player): Arena AFK (#9733)
- chore(DB): import pending files
- fix(DB/Pathing): Brooms, Sunstrider Isle (#9827)

## 2021-12-27
- chore(DB): import pending files
- Fix (DB\Loot Objective) Remove Bad Loot Objective (#9873)
- chore(DB): import pending files
- fix(DB): startup error (#9894)
- chore(DB): import pending files
- fix(DB/Spawning/Movement): Gangled Flesheaters. Ghostlands (#9786)
- feat(CI): process pending SQL file in PRs (#9887)
- chore(DB): import pending files
- fix(DB/Pathing): Ruins of Silvermoon, Eversong Woods (#9826)
- chore(DB): import pending files
- fix(DB/Creature): Deatholme, Ghostlands (#9818)

## 2021-12-26
- fix(DB/SQL): fix character database versioning (#9891)
- chore(DB): import pending files
- chore(DB/SQL): fix SQL imports #9886
- chore(DB): import pending files
- feat(Core/Player): Implement player specific settings (#9483)

## 2021-12-25
- chore(DB): import pending files
- fix(DB): Jorn Skyseer gossip option removal (#9735)
- chore(DB): import pending files
- refactor(Scripts/Pets): Move Mojo to SAI (#9662)
- chore(DB): import pending files
- fix(DB/Creature): Lich King Audio and Text during Chapter 3 of DK Questline (#9503)
- chore(DB): import pending files
- fix(Script) Quest "Deactivating the Spire" (#9874)

## 2021-12-24
- chore(DB): import pending files
- fix(DB/Gameobject): Shadowglen, Teldrassil Gameobject Improvements (#9852)
- chore(DB): import pending files
- Fix (DB\Skin Loot) Remove Skinning loot  from none skinnable npc (#9864)
- feat(Core/SavingSystem): remove old player saving system (#9779)
- fix(Core/Loot): Proeprly handle `UNIT_DYNFLAG_LOOTABLE` flag. (#9761)
- fix(Core/Movement): Always stop moving on new chase movement generator init. (#9622)

## 2021-12-23
- chore(DB): import pending files
- fix(DB/Spawning/Pathing): Windrunner Spire, Ghostlands (#9784)
- chore(DB): import pending files
- fix(Scripts/Silithus): Wind stone summons (#9859)
- fix(Core/Player): Solve the issue with creature not offering low level quests (#9862)
- chore(DB): import pending files
- fix(DB/Creature): Amani Catacombs, Ghostlands (#9770)
- chore(DB): import pending files
- fix(DB/Loot): Abyssal Crest drop chance (#9857)
- chore(DB): import pending files
- feat(Scripts/Commands): additem (#9759)
- fix(Scripts/MoltenCore): Ragnaros targetting dead player
- chore(DB): import pending files
- fix(DB/Quest): Updated Durotar shaman quests (#9691)
- chore(DB): import pending files
- fix(DB/Graveyards): Added missing graveyard in Undercity for Alliance. (#9762)
- chore(DB): import pending files

## 2021-12-22
- Fix (DB) issue mob guid 55176 pathing correction (#9275)
- chore(DB): import pending files

## 2021-12-23
- fix(DB/Loot): Flamewalker Elite/Priest loot table (#9846)

## 2021-12-22
- chore(DB): import pending files
- fix(Scripts/Spell): Removed doubled damage from Deep Freeze. (#9810)
- fix(Scripts/Commands): fix additem (#9843)
- fix(Core/Movement): Fixed adding wrong flag on root. (#9803)
- fix(Core/Player): Quest Question marks (#9683)

## 2021-12-21
- chore(DB): import pending files

## 2021-12-22
- fix(DB/Creature): Add immunity to MECHANIC_ROOT to Baron Geddon (#9840)

## 2021-12-21
- fix(Core/Load): Comment continue (#9836)
- chore(DB): import pending files
- refactor(Core/Scripts): Spell To Scripts (#9718)
- refactor(Scripts/Commands): convert cs_misc to new system (#8939)
- refactor(Core/Misc): fmod() to std::fmod() (#9796)
- chore(DB): import pending files

## 2021-12-20
- fix(DB/Scripts): changed event param to Bodley' script (#9813)
- chore(DB): import pending files
- feat(Scripts/Commands): Implement item refund command (#9811)
- chore(Scripts/Silithus): fix warning (#9812)

## 2021-12-19
- fix(Scripts/Silithus): Prevent summoning multiple windstone creatures (#9801)
- feat(Core/Player): Split Dungeon Finder quest rates (#9788)

## 2021-12-20
- feat(Core/SmartScripts): SMART_ACTION_DISABLE_EVADE (#9772)

## 2021-12-19
- chore(DB): import pending files
- fix(DB/Spawning/Pathing): Underlight Mines, Ghostlands (#9753)
- chore(DB): import pending files
- fix(DB/Spawning/Pathing): Windrunner Village, Ghostlands (#9752)
- refactor(Core): remove unused imports (#9767)
- chore(DB): import pending files
- fix(DB/Spawning/Pathing): Zeb'Tela, Ghostlands (#9751)
- fix(Core/Creature): Remove empty spell ids from CreatureAddon.auras vector (#9783)
- fix(Core/Spells): Only check GO state for doors when using SPELL_EFFECT_OPEN_LOCK (#9778)
- chore(DB): import pending files
- fix(DB/Spawning/Pathing): Zeb'Nowa, Ghostlands (#9750)
- chore(DB): import pending files
- fix(DB/Creature/SAI/Conditions): Twin Ziggurats Deatholme Darkmage (#9747)
- chore(DB): import pending files
- fix(Core/GridNotifiers): fix tempsummons not finding nearby creatures (#9749)

## 2021-12-18
- chore(DB): import pending files
- fix(DB/Path): Luzran (#9744)
- fix(CI/Docker): free up additional space (#9754)
- chore(Script/Misc): Cleanup some JustDied hooks (#9669)
- chore(DB): import pending files

## 2021-12-17
- fix(DB/Gossip): Added Bodley gossips (#9756)

## 2021-12-18
- chore(DB): import pending files
- fix(DB/Gossips): add missing gossip texts to Niby the Almighty (#9692)
- chore(DB): import pending files
- fix(DB/Loot): drop rate of Frost Lotus from herbs in Northrend. (#9671)

## 2021-12-17
- chore(DB): import pending files
- fix(DB/Loot): Fel cone loot incorrect (#9713)
- chore(DB): import pending files
- fix(DB): remove immunity to bleed effects on Boss (#9711)
- chore(DB): import pending files
- fix(DB/Creatures): add `CREATURE_TYPE_FLAG_FORCE_GOSSIP` to some creatures (#9706)
- chore(DB): import pending files
- fix(DB/Loot): Remove incorrect blacksmith recipe drops (#9698)
- chore(DB): import pending files
- fix(Spawning/Pathing): An'daroth, Ghostlands (#9696)
- chore(DB): import pending files
- fix(Pathing): Knucklerot (#9694)
- fix(Spawning/Pathing): Goldenmist Village,Ghostlands (#9693)
- chore(DB): import pending files
- fix(DB/Gameobjects): Spirit Candle should properly give buff to nearby players (#9690)
- chore(DB): import pending files
- fix(DB/Quest): correct Queststarter & Questender for "The Key to Scholomance" (#9682)
- chore(DB): import pending files
- fix(Spawning/Pathing/SAI): Shalandis Isle, Ghostlands (#9678)
- chore(DB): import pending files
- fix(Spawning/Waypoints): Arcane Reavers at Dawnstar Spire (#9677)
- chore(DB): import pending files
- fix(DB/SAI): Eskhandar Combat Script (#9672)
- chore(DB): import pending files
- fix(DB/Scripts): Unworthy Initiate Chains (#9668)
- refactor(Scripts/Zone): move crystalsong_forest to new system (#9700)
- feat(Core/Creature): Log temporary auras on creatures (#9670)
- fix(Core/Object): Add infinite gob check (#9667)
- fix(Core/Guilds): Implement guild bank gold limit matching client (#9666)
- fix(Core/Quests): implement QUEST_SPECIAL_FLAGS_NO_REP_SPILLOVER (#9661)
- chore(Core/Misc): use fallthrough attribute instead of comment (#9660)
- fix(Core/Movement): despawn mini pets on flight take (#9624)
- chore(DB): import pending files
- fix(DB/Spells): Add missing spells for Ulduar heroic mode (#9655)
- chore(DB): import pending files
- fix(DB/Quest): An Unholy Alliance (#9585)
- chore(Core/Cache): Remove an assert breaking 1v1 arena module (#9651)
- chore(DB): import pending files

## 2021-12-16
- fix(DB/SAI): Tomb of the Lightbringer Quest Completion Trigger (#9645)

## 2021-12-17
- fix(Core/Units): Modify health dependent aura states on update rather than immediately on death. (#9641)
- fix(Core/Spells): Implement SPELL_AURA_PERIODIC_TRIGGER_SPELL_FROM_CL… (#9615)

## 2021-12-16
- chore(DB): import pending files
- Fix (DB) Loot Correction (#9728)
- fix(Scripts/Silithus): Stop banning people for using windstones (#9734)
- chore(DB): import pending files
- fix(DB/Creature): Ghostlands Respawn and path three areas (#9614)
- chore(DB): import pending files
- (Core\DB) Create Logging Game Event Creatures\Gameobjects (#9731)
- chore(DB): import pending files
- fix(DB/Gossips): Fix Commoner's gossip texts for all game events. Source: TrinityCore. (#9540)
- fix(Core/Player): Interrupt flag capturing even if damage is absorbed. (#9445)
- chore(DB): import pending files
- fix(Scripts/BRD): Magmus, Emperor, Priestess, Arena improvements (#8102)
- chore(DB): import pending files
- fix(Core/Trainers): add new column `ReqSpell` to `npc_trainer` table (#9490)
- chore(DB): import pending files
- fix(Script/Quest): Plagued Lands [2118] (#9541)
- fix(Core/Spells): Implement SPELL_EFFECT_FORCE_CAST_2 (#9613)

## 2021-12-15
- fix(Core/Unit): fix quest items not dropping if they are the only thi… (#9723)
- chore(DB): import pending files
- fix(DB/Quests): Armor Scraps and Enemy Booty should not be repeatable (#9628)
- fix(CI): set openssl to use openssl1.1 (#9715)
- fix(Core/Pets): Improved Revive Pet should affect dead despawned pet. (#9625)
- fix(Core/Spells): Mind Control can be dispelled from friendly target. (#9689)
- fix(Core/Scripts): Fix QuestRewarded hook (#9717)
- refactor(Scripts/Events): convert childrens_week to new system (#9611)
- fix(Core/Spell): Core not handling AURA_INTERRUPT_FLAG_TELEPORTED (#9543)

## 2021-12-14
- fix(Core/Character): Fix OnFirstLogin script hook (#9686)
- fix(Core/Scripts): Fix bool script hooks not executing code (#9699)
- fix(Core/DatabseWorkerPool): Maria stuff (#9705)
- refactor(Scripts/Events): convert hallows_end to new system (#9610)
- fix(Core/Spells): Do not apply diminishing return on spells casted by mobs. (#9536)
- fix(Core/Pet): Standardize pet run speed at 115% rate. (#9478)
- refactor(Core/DB): Deprecate MariaDB 10.4 and below (#9675)
- fix(CI): Ubuntu build (#9697)

## 2021-12-13
- fix(Core/Instances): always put boss minions in combat with zone (#9649)
- refactor(Scripts/Events): convert brewfest to new system (#9612)
- refactor(Scripts/Event): convert pilgrims_bounty into new system (#9608)
- refactor(Scripts/Events): convert love_in_air to new system (#9609)
- chore(DB): import pending files
- fix(DB/SAI): Add missing path for Solanin (#9601)
- refactor(Script/Spells): convert winter_veil into new system (#9606)
- fix(Core/Guild): Properly updates guild leader using command `guild rank`. (#9596)
- chore(DB): import pending files

## 2021-12-12
- fix(DB/Spawning/Pathing): Eversong Woods cleanup and pathing #1 (#9597)
- chore(DB): import pending files
- fix(DB/Quest): Update WorldMapAreaId to match respective quests (#9584)
- chore(DB): import pending files
- fix(DB/quest_offer_reward): Add Completion Text for quest "Tome of Nobility" (#9583)
- chore(DB): import pending files
- fix(DB/Quest): Fix Incorrect 'On Complete' Text (#9582)
- chore(DB): import pending files
- fix(DB/Creature): Add mining type_flag for NPC Tavarok (#9579)
- chore(DB): import pending files
- fix(DB/Loot): Remove Items Incorrectly Placed on Loot Tables (#9581)
- chore(DB): import pending files
- fix(DB/SAI): Battle Chicken Combat SAI Improvements #9578
- feat(Core/Config): loading modules configs before loading scripts (#9653)
- fix(Core/Spells): Properly handle pet spell auras with infinity cooldown. (#9576)
- fix(Core/Loot):  Set skinnable flag only after all loot was taken. Source: TrinityCore. (#9573)
- fix(Core/Pets): Properly cast spells on friendly target if not in LoS… (#9570)
- chore(DB): import pending files
- fix(DB/Vendor): Restock time for Undermine Clam Chowder (#9544)
- fix(Core/ScriptMgr): Correct whisper hook parameters (#9674)
- fix(Core/Pets): Add cooldown on spell cast if pet initially was out of range or not in LoS. (#9539)
- chore(DB): import pending files
- fix(Core/Spells): Added some new spells to spell_group rules. (#9537)

## 2021-12-11
- chore(DB): import pending files

## 2021-12-12
- fix(DB/gameobject): Remove respawn timer from The Holy Spring (#9534)

## 2021-12-11
- fix(Core/Command): cfg check on item restore list (#9659)
- chore(DB): import pending files

## 2021-12-12
- fix(DB/creature): Remove money drops from Imp Minion (#9533)

## 2021-12-11
- refactor(Scripts/Command): Simplify command go set state (#9527)
- fix(Core/Commands): Item duplication exploit (#9650)
- chore(DB): import pending files
- fix(DB/SAI): Quest 9678 "The First Trial" (#9528)
- chore(DB): import pending files
- fix(DB/Gob): Move D.I.S.C.O script to spell_scripts (#9524)
- chore(DB): import pending files
- fix(DB/Creature): Greatfather Winter (#9522)
- chore(DB): import pending files
- fix(DB/Creature): set proper faction for Deepmoss Hatlings (#9523)
- chore(DB): import pending files
- fix(DB/Pathing): Reworked Sunsail Anchorage in Eversong Woods with pathing (#9517)
- chore(DB): import pending files
- fix(Scripts/MoltenCore): Properly spawn Ragnaros' Sons of Flame (#9642)
- chore(DB): import pending files
- fix(DB/SAI): Correct target for some Dalaran vendor welcome texts (#9516)
- refactor(Core/Packet): Guild (#9411)
- feat(Core/ScriptMgr): replace macro and cleanup (#9598)

## 2021-12-10
- chore(DB): import pending files
- fix(DB/SAI): Nathanos Blightcaller Combat Script (#9507)
- Revert "fix(Core/Spells): Forward core changes (#8841)" (#9631)
- fix(Scripts/Spells): Fixed logic in Glyph of Prayer of Healing script. (#9502)
- feat(Core/Config): implement loading files optional (#8198)
- fix(Core/Spells): Melee spells are not affected by cast haste modifiers. Source: TrinityCore. (#9501)
- fix(Core/Spells): Channeled destination spells should not interrupt flag capturing. (#9472)
- fix(Core/Players): Update the player's zone and area only after update the player's position server-side (#9419)

## 2021-12-09
- fix(Core/Spells): Forward core changes (#8841)
- fix(Core/Auras): Always process hover/waterwalking movement flags on aura removal. (#9416)
- chore(DB): import pending files
- fix(DB/Creature): apply 'Permanent Feign Death' to Citizen of New Avalon (#9499)
- feat(CI/Modules): disable build mod-azerothshard (#9605)
- feat(Core/ScriptMgr): correct execute bool hooks (#9574)
- chore(DB): import pending files
- fix(DB/Gossip): Mux manascrambler's conditions (#9442)
- fix(Core/Spells): Damage spell modifiers do not affect wands. (#9418)
- chore(DB): import pending files
- fix(DB/Loot): all starting area loot to work like Official (#9379)
- chore(DB): import pending files
- feat(Scripts/Commands): Item restoration command (#9538)

## 2021-12-08
- fix(Scripts/MoltenCore): Solve an issue causing Ragnaros melee checks to be skipped (#9599)

## 2021-12-09
- chore(DB): import pending files
-  fix(DB/GameObject): ZAM hostage chest unlootble
- chore(DB): import pending files
- fix(DB/Instances): Dark Keeper Portrait should summon only one boss. (#9346)

## 2021-12-08
- feat(Core/Build): Patched to be buildable on FreeBSD 13.0-RELEASE (#9568)
- fix(Core/Battlegrounds): Delay a little bit relocation of dead players. (#9302)
- fix(Scripts/Brewfest): Set proper npc entry to `NPC_NORMAL_VOODOO` (#9262)
- fix(Core/Spell) Green Beam spells should only hit one target (#9593)
- chore(DB): import pending files
- fix(Scripts/MoltenCore): Implement Ragnaros' Lava Bursts (#9526)
- chore(DB): import pending files
- Fix(DB/Creature): Add InhabitType Water to various Gogger's NPC (#9520)
- fix(Core/Player): Fix potential freeze on login after skipping cinematics (#9577)
- chore(DB): import pending files
- fix(DB/Creature): Greatmother Hawkwind faction (#9580)
- chore(DB): import pending files
- fix(DB): Work Work Audio Broadcast (#9525)
- Core/ScriptMgr: Duplicate include (#9511)

## 2021-12-07
- fix(Scripts/MoltenCore): Majordomo's spawn line should be said instantly (#9515)
- chore(DB): import pending files
- fix(Scripts/Spells): Hunter's Initimidation should not stun pet. (#9493)
- chore(DB): import pending files
- fix(DB/Creature): remove duplicated Goblin Commoners (#9487)
- asd
- chore(DB): import pending files
- fix(DB/SAI): Add Gnomish Battle Chicken combat SAI (#9485)
- chore(DB): import pending files
- fix(DB/Gossip): Adding Mor'ogal's gossip (#9462)
- chore(conf): change default option & add description for setting Instance.SharedNormalHeroicId (#9484)
- chore(DB): import pending files
- fix(DB/Creature): Dark Iron Kidnapper (#9461)
- fix(Script/Spell): Winter Wondervolt Trap (#9464)
- chore(DB): import pending files
- fix(DB/SAI): Warlord Krom'zar wrong spell (#9459)
- chore(DB): import pending files
- fix(DB/SAI): Jorn Skyseer's gossip chance (#9457)
- chore(DB): import pending files
- fix(DB/SAI): Theramore Preserver SAI (#9456)
- chore(DB): import pending files
- fix(DB/SAI): Bristleback NPCs SmartAI improvements (#9455)
- chore(DB): import pending files
- fix(DB/Loot): Cats eye emerald drop correction (#9453)
- chore(DB): import pending files
- fix(DB/Quest): Noth the Plaguebringer ends quest 'Noth's special brew' (#9482)
- chore(DB): import pending files
- fix(DB/Spells): Elemental Focus should proc off only from damage spells. (#9498)
-  fix(Core/Loot): Send Retrieval Mail for lost disenchant mats
- fix(Core/Spells): Steady Shot now deals the correct damage when using Heirloom Weapons.

## 2021-12-06
- fix(Core\Logging): Capitalization
- chore(DB): import pending files
- fix(DB/Item): Fix Super Reaper Droprate to 30% (#9436)
- fix(Core/Movement): Unroot should remove MOVEMENTFLAG_FALLING if not really falling (#9428)
- chore(DB): import pending files
- fix(DB/SAI): Removing Venture Co. Drudger's Thrash (#9452)
- fix(Core/Corpses): Reset corpse location data if player already resurrected in different dungeon map. (#9429)
- chore(DB): import pending files
- fix(DB/GameObjects): Reverting past node changes (#9476)
- fix(Core/Chat): correct logic for using guild officer chat (#9535)
- chore(DB): import pending files
- fix(DB/Creature): Metzen the Reindeer (#9460)
- fix(Script/Spells): Prevent passive spells to proc Omen of Clarity (#9518)
- chore(DB): import pending files
- fix(DB/Creatures): Eye of Kilrogg should be able to attack. (#9427)
- 1st commit
- chore(DB): import pending files
- fix(SAI/Script): Move Lady Jaina Proudmoore to SAI. (#9426)

## 2021-12-05
- fix(Scripts/Spells): Drain Soul generates Soul Shard only from targets that yields experience or honor on death. (#9417)
- chore(DB): import pending files
- fix(DB/Creature): Spawn at Winter Veil (#9521)
- chore(DB): import pending files
- fix(DB/SAI): Clean up event_type in Timed Actionlists (#9405)
- chore(DB): import pending files
- fix(DB/SAI): Deathstalker Vincent has SAI in DB but not linked (#9404)
- chore(DB): import pending files
- fix(DB/Creature) Add missing SAI and gossip to Elder Torntusk (#9403)
- chore(DB): import pending files
- fix(DB/SAI) Script Lords spawned from Greater Windstones (#9402)
- chore(DB): import pending files
- fix(DB/SAI): Make generically spawned traps invisible (#9506)
- chore(DB): import pending files
- fix(DB/Loot): arcanite reaper recipe drop rare fix (#9397)
- chore(DB): import pending files
- fix(DB/Quest): Great-father Winter is Here! (#9465)
- fix(Core/Scripts) Add respawn timer to wind stones (#9392)
- feat(Script/Misc): Implement missing FactoryGameObjectScript (#9388)
- chore(DB): import pending files
- fix(DB/SAI): Dr Weavil Abilities (#9505)
- fix(Core/ScriptMgr): Cleanup few scripts (#9497)

## 2021-12-04
- chore(DB): import pending files

## 2021-12-05
- fix(DB/formations): Adds formations to two groups in UBRS (#9494)

## 2021-12-04
- refactor(Scripts/Commands): convert cs_modify to new system (#9474)
- fix(Core/ScriptMgr): correct condition for AreaTrigger (#9491)
- chore(DB): import pending files
- fix(DB/Creature): Add missing random movement to Sarkoth (#9389)
- chore(DB): import pending files
- fix(DB/Loot): Remove Frigid Ring from RLT (#9358)
- chore(DB): import pending files
- feat(Core/Commands): command to teleport character to npc  (#8887)

## 2021-12-03
- chore(DB): import pending files
- feat(Core\Player): Added createplayerinfo_cast_spell support cast spell for some class spells (#9448)
- chore(DB): import pending files
- fix(DB/SAI): Script Dukes spawned from Windstones (#9401)
- chore(DB): import pending files
- fix(Scripts/DireMaul): Rewrite Isalien fight (#9377)
- chore(DB): import pending files
- fix(Scripts/BlackrockSpire): Improved Kormok encounter. (#9394)
- chore(DB): import pending files
- fix(Scripts/Stratholme): Rewrite Jarien and Sothos fight (#9391)
- fix(Script/Commands): cs_modify crash fix (#9471)
- fix(Core/Quest): Daphne Stillwater respawn for quest Tome of Valor (#9469)
- chore(DB): import pending files
- fix(Scripts/BlackrockSpire): rewrite Mor Grayhoof fight (#9374)
- chore(DB): import pending files
- fix(DB/Pathing) Add missing Springpaw pathing in Sunstrider Isle (#9375)

## 2021-12-02
- chore(DB): import pending files
- fix(DB/SAI): Script Templars spawned from Lesser Windstones (#9399)
- chore(Core/Warden): comment auto ban from TIMING_CHECK_FAIL (#9470)
- chore(DB): import pending files

## 2021-12-03
- fix(DB/creature_loot): Remove underlevel RLT from Blackhand Veteran (#9398)

## 2021-12-02
- chore(DB): import pending files
- fix(Scripts/BlackrockSpire): Improved Lord Valthalak encounter. (#9373)
- chore(DB): import pending files
- fix(DB/Quest) Class Training quest for Sunstrider Isle (#9355)
- fix(Scripts/Brewfest): Reload faction auras for revelers after respawn. (#9264)
- fix(Core/LFG): Prevent leaving LFG if in combat (#9466)
- fix(Scripts/BFD): Fix problem with Aku'mai event being skippable after crash (#9463)
- feat(Core/Modules): add separated lib for modules (#9281)

## 2021-12-01
- fix(Core/DungeonFinder): Dead players should be able to get XP reward from random dungeon. (#9319)
- fix(Core/Quests): Do not save queststatus for autocomplete quests . S… (#9425)

## 2021-11-30
- chore(DB): import pending files
- chore(Core/Auras): Clean up Aura::CanBeSaved() (#9343)
- chore(DB): import pending files
- fix(Scripts/Spells): Omen of Clarity should proc off from more spells. (#9344)
- chore(DB): import pending files
- fix(DB/Gameobjects): Duskwood mineral spawns and pooling (#9413)
- fix(Core/Pets): Master Demonologist should not be removed on pet resummon. (#9317)

## 2021-11-29
- chore(DB): import pending files

## 2021-11-30
- fix(Core/Auras): Set proper displayId for mounts that changes dependi… (#9342)
- fix(Core/Spells): Fixed calculating damage/healing pct auras on aura refresh. (#9316)

## 2021-11-29
- fix(DB/Misc): Correct imported file (#9415)
- fix(Core/Spells) T9 2p Hunter bonus vs Mortal Shots. (#9246)
- chore(DB): import pending files
- fix(DB/Gameobject): Improved Copper Vein spawns and pooling (#9284)
- fix(Core/Entities): add missing nul pointer checks in HandleProcTrigger Spell  (#9303)
- chore(DB): import pending files
- fix(Scripts/Spells): Mind Control should put both caster and target in combat. (#9301)
- chore(DB): import pending files

## 2021-11-30
- fix(DB/loot): Correct Treant's Bane drop rate (#9280)

## 2021-11-29
- fix(Scripts/UBRS): Drakkisath's conflagrate should drop threat temporarily (#9299)
- chore(DB): import pending files
- fix(Raid/AQ40): Ouro not spawning (#9285)
- chore(DB): import pending files
- fix(DB/Spells): Thera/Stonard Portals Level Req (#9277)
- chore(DB): import pending files
- fix(DB/Loot): battered chest loot in starting areas (#9265)
- fix(Core/CharacterHandler): Reputation + Map Explore AT_FIRST_LOGIN (#9252)

## 2021-11-28
- chore(DB): import pending files
- fix(DB/Spells): Moonkin Form - remove TBC leftover from mana restore passive aura. (#9247)
- chore(DB): import pending files
- fix(DB/locales): Adds spanish names for auctioneers in orgrimmar (#9245)
- fix(Core/Player): prevent crash exploit spam duel starting (#9226)
- chore(DB): import pending files
- fix(DB/Creature): Add Fellicent path and spawntime (#9224)
- fix(Scripts/MoltenCore): Ragnaros target selector and remove submerge… (#9335)
- chore(DB): import pending files
- fix(DB/Quest): Alterac Valley trinkets quests (#9222)
- chore(DB): import pending files
- fix(Core/Spells): Increased Arcane Bolt effect radius to 40 yards. (#9217)
- refactor(Scripts/AhnKahet): new script system (#9040)
- refactor(Core): Clean-up after FD (#8586)

## 2021-11-27
- chore(DB): import pending files
- fix(DB/Item): Demon's Blood trinket (#9223)
- chore(DB): import pending files
- refactor(Scripts/Onyxia): Update Onyxia's script (#9371)
- chore(Core/Instances): Move the objectdata loading log from error to debug level (#9382)

## 2021-11-26
- fix(Core/MC): adds should aggro with Golemagg (#9370)
- chore(Scripts/OnyxiasLair): Fix broken code style (#9367)
- chore(DB): import pending files
- fix(DB): Mass Update deprecated and monster items (#5473)
- fix(Core/DBUpdater): MySQL 8.0 + SSL support (#9340)
- chore(DB): import pending files
- fix(DB/SAI): Lava Surger should target the farthest player (#9338)
- fix(Scripts/MoltenCore): Majordomo shouldn't cast Blast Wave (#9352)
- chore(DB): import pending files
- fix(Core/Formations): fixed possible finite loop related to GROUP_AI_FLAG_EVADE_TOGETHER (#9279)
- fix(Core/Loot): Always interrupt any spell casting while looting corpse. (#9160)

## 2021-11-25
- fix(Core/Loot) remove stealth/feign death on loot (#8982)
- refactor(Core/BattlegroundSA): Convert to std::chrono (#8499)
- chore(DB): import pending files
- fix(Script/Spell): Gryphon/Wyvern Pet - Mounting Check Aura (#8481)
- chore(DB): import pending files
- fix(DB/Quest): The Left Piece of Lord Valthalak's Amulet (#9315)
- chore(Core): Remove unnecessary slang Cosmetic (#9325)

## 2021-11-24
- chore(DB): import pending files
- fix(DB/Quest): add pre-quest for Flash Bomb Recipe quest (#9221)
- fix(Core): Fixed dead loop. (#9312)
- fix(Core/Creature): prevent useless grid searches (#9307)
- fix(Core/Shutdown): add checks to see if MapUpdater threads are joineable (#7450)
- fix(Core/Creature): crash on creature evade (#9305)
- chore(DB): import pending files
- refactor(Scripts/Commands): Update cs_quest to the new model (#9267)
- chore(DB): import pending files
- feat(DB): skilltiers_dbc (#6756)

## 2021-11-23
- fix(Core/Spells): Autoshot should not interrupt Volley (#9202)
- fix(Scripts/Scholomance): Fix nullptr crash (#9298)
- fix(Core/Spells): properly handle item cooldowns (#9176)
- chore(DB): import pending files
- fix(DB/Loot): dropchance of [A Letter to Yvette] (#9219)
- chore(DB): import pending files

## 2021-11-22
- fix(DB/Spells): Add mana burn to Son of Flame (#9229)
- chore(DB): import pending files

## 2021-11-23
- fix(Core/DB): add exceptions for shield and badge. Update db for positions (#9169)

## 2021-11-22
- fix(Core/MC): Golemagg (#9233)
- chore(DB): import pending files
- fix(Scripts/MoltenCore): Majordomus improvements: (#9232)
- chore(DB): import pending files
- fix(Scripts/MoltenCore): Ragnaros rewrite (#8935)
- fix(Core/GameObjects): Lockpicking timer on gameobjects should reset … (#9203)
- fix(Core/MC): Sulfuron Harbinger (#9235)
- refactor(Core/Misc): headers cleanup (#9259)
- chore(DB): import pending files
- fix(DB/Quest): remove Nipsy Handin location (#9145)
- chore(DB): import pending files

## 2021-11-21
- fix(DB/Crash): remove wrong groupAI flag causing stack overflow (#9273)
- chore(DB): import pending files
- fix(DB/SAI): Defias Traitor now addresses player on say (#9170)
- chore(DB): import pending files
- fix(DB/BlackrockSpire): Spirestone Lord Magus should cast Enlarge and… (#9216)
- fix(Core/Spells): possible crashes within class spells (#9168)
- fix(Core/Spells): Item Fresh Brewfest Hops (#8010)
- fix(Core/Spells): Fix spellclick (#8232)
- chore(DB): import pending files
- fix(DB/Quest): Remove exclusivegroup from Tome of Divinity quests (#9260)
- Revert "fix(Core/Spells): Lowered Magmadar Panic's effect radius to 30 yards. (#9227)" (#9266)
- fix(Core/Spell): Add Dual Wield skill dependency to Dual Wield effect, sho… (#9162)
- chore(DB): import pending files
- fix(DB/Fishing): Implemented day/night fishing events. (#8176)

## 2021-11-20
- feat(Core/Misc): Added lambda support to EventProcessor. (#9263)
- feat(Scripts/Commands): Implement restart/shutdown reasons (#9242)
- chore(DB): import pending files

## 2021-11-21
- fix(DB/creature): Correct Emberstrife's respawn time (#9258)

## 2021-11-20
- chore(DB): import pending files
- fix(Script/Item): Deviate Fish effects (#9163)
- fix(Core/SmartScripts): SMART_ACTION_ACTIVATE_GOBJECT should not rese… (#9178)
- refactor(Core/BattlegroundRV): Convert to std::chrono (#8498)
- chore(DB): import pending files
- fix(Scripts/Misc): Replace some AddItem/CreateItem with spells (#9006)
- fix(Core/CreatureAI): enemy stealth alert ignoring LOS (#9161)

## 2021-11-19
- feat(Core/SmartScripts): `SMART_ACTION_CALL_FOR_HELP` should properly call assistance in case of polymorphed creature. (#9231)
- fix(Core/Scripts): add support using whitespace for cs_lookup (#9243)
- chore(DB): import pending files
- fix(DB/Loot): BRD Dark Coffer arcanum items (#8914)
- chore(DB): import pending files
- fix(Scripts/Scholomance): improvements for Kirtonos (#8401)
- fix(Core/Spells): Lowered Magmadar Panic's effect radius to 30 yards. (#9227)
- fix(Core/Spells): Flamewaker's Sunder Armor should be single stack. (#9228)
- chore(DB): import pending files
- fix(DB/Creature):  restore deleted spawns (#9250)

## 2021-11-18
- chore(Core/AH): update auction house files after cache update (#9244)
- chore(DB): import pending files
- refactor(Core/Cache): move the GlobalPlayerCache to its own class (#9166)
- fix(Scripts/UBRS): The Beast should deaggro when walking over the fir… (#9201)
- chore(DB): import pending files
- fix(DB/Script): Add bat mini event to hourly bell event in Brill (#9200)
- fix(DB/Misc): Remove quotes from ints (#9237)
- chore(DB): import pending files

## 2021-11-17
- refactor(DB/SAI): Move Chromatic Elite Guard script to SAI (#9194)
- chore(DB): import pending files
- fix(Core/Objects): increase sight range of objects & correct general defau… (#9180)
- fix(Script/Spells): validate all rogue spells (#9164)
- feat(Core/CharacterHandler): (#9147)
- chore(DB): import pending files
- feat(Core/Loot): Implement player_loot_template (#9198)
- chore(DB): import pending files
- fix(DB/Formations): Add the new "evade together" formation flag for Drakkisath adds (#9220)

## 2021-11-16
- fix(Scripts/MoltenCore): Shazzrah should teleport to players (#9212)
- chore(DB): import pending files
- fix(Scripts/BlackrockSpire): Urok's summoned mobs should move towards the pile. (#9215)
- feat(Core/Formations): implemented a new formation groupAI flag "GROUP_AI_FLAG_EVADE_TOGETHER" (#8758)
- fix(Core/AuctionHouse): Implemented sorting. Based on @r00ty-tc work. (#9011)
- chore(DB): import pending files
- fix(Scripts/DB): Jiklik's bats from phase 2 now won't engage players… (#8142)
- chore(DB): import pending files
- fix(DB/Gossip) Malyfous missing gossip (#9156)

## 2021-11-15
- chore(DB): import pending files
- fix(DB/Creature): add pre-cata equipment to 2 creatures (#9142)
- chore(DB): import pending files
- fix(Scripts/Commands): cs_character - Restore character rename reserved_name functionality (#9195)
- fix(Core/Movement): creatures should not cast while moving (#9141)
- chore(Core): remove duplicate comment (#9140)
- chore(DB): import pending files
- fix(DB/Waypoints): Script Quartermaster Zigris waypoints (#9190)
- chore(DB): import pending files
- fix(DB/Loot): Remove Fifth Mosharu Tablet from Smolderthorn Shadow Priest (#9192)
- chore(DB): import pending files
- feat(Scripts/Commands): implement new command: `.inventory count` (#9139)

## 2021-11-14
- fix(Core/DungeonFinder): premade LFG groups are considered as single-person groups (#9135)
- fix(Core/Spells): health-dependent reactive states should reset on death (#9134)
- feat(CI/Modules): add mod-progression-system (#9188)
- chore(DB): import pending files
- fix(Core/Script): add hourly bell event (#9151)
- fix(Scripts/UBRS): Set Gyth's encounter state on death (#9189)
- fix(Core/Scripts): corrrect cs_lookup (#9184)
- fix(Script/Spells): Validate Warlock spells (#9181)
- fix(Script/Spells): Validate Warrior spells (#9182)
- chore(DB): import pending files

## 2021-11-13
- fix(DB/Gossip) Missing gossip text for Finkle Einhorn (#9154)

## 2021-11-14
- refactor(Scripts/Commands): convert cs_lookup to new system (#9100)

## 2021-11-13
- fix(Core/Spells): Steady Shoot should not suspend ranged attack timer. (#9125)
- chore(DB): import pending files
- fix(DB/SAI): Blackhand Dreadwaver should cast Curse of Thorns
- chore(DB): import pending files
- fix(DB/SAI): Blackhand Dragon Handler should cast Mend Dragon (#9173)
- chore(DB): import pending files
- refactor(Scripts/Spells): convert spell_item into new system (#9057)
- fix(Core/Disables): Remove validation checks from DISABLE_TYPE_GAME_EVENT (#9167)
- chore(DB): import pending files
- fix(DB/creature_loot): drop chance of items that start a quest at Elwyn Forest (#8969)
- fix(Scripts/Spell): don't allow to tame an already owned creature (#9005)
- refactor(Scripts/Spells): convert spell_generic into new system (#9044)

## 2021-11-12
- fix(Core): Crashfix. (#9157)
- chore(DB): import pending files
- fix(DB/Event): remove Bountiful Barrels from wrong zones (#9097)
- fix(Core/Achievement): Throw food (#9098)
- chore(DB): import pending files
- feat(Script/Commands): .debug dummy (#9070)
- chore(DB): import pending files
- fix(Scripts/Spells): Holiday food items should give their buff after 10 seconds, not when the eating aura expires (#9132)
- chore(DB): import pending files
- fix(Scripts/BlackrockSpire): Urok Doomhowl - improvements: (#9067)
- refactor(Scripts/Commands): convert cs_learn & cs_player to new system (#9050)
- chore(DB): import pending files
- fix(Scripts/UBRS): Pyroguard Emberseer adds improvements (#9136)
- fix(Scripts/UBRS): Drakkisath's Conflagration should be cast on the main target (#9138)
- fix(Scripts/DireMaul): immolthar and adds are now immune to combat until the pylons are activated (#9007)

## 2021-11-11
- chore(DB): import pending files
- fix(DB/Spells): Glyph of Backstab should proc off only from Backstab (#8985)
- feat(Apps): Imrpove crashlogs on Linux. (#9131)

## 2021-11-10
- feat(Core/Misc): change how Position struct is retrieved (#9017)
- fix(CI): do not always run mac/windows/docker for C++ changes (#9126)
- feat(Core/Disables): Implement DISABLE_TYPE_GAME_EVENT (#9099)
- fix(CI): re-run builds if label is present (#9114)
- refactor(Scripts/Commands): convert cs_server to new system (#9078)
- fix(CI/C++20): attempt to fix labelled builds
- refactor(Scripts/Commands): Convert cs_reload to new system (#9052)
- fix(CI): revert sleep + fix shadowing variable issue (#9106)
- chore(CI): rename workflow
- fix(CI): trigger builds on C++ changes (#9103)
- chore(DB): import pending files
- fix(DB/Creature): Ilkrud Magthrull (#9073)
- chore(DB): import pending files
- fix(DB/Formations): Linked some creatures in Drakkisath Room into one formation. (#9092)
- chore(DB): import pending files
- fix(DB/Loot): Green Winter Hat should drop only if Winter Veil is active (#9096)

## 2021-11-09
- chore(DB): import pending files

## 2021-11-10
- fix(Script/Spell): Dark Reckoning (#9024)

## 2021-11-09
- chore(DB): import pending files
- fix(DB/Creatures): Added missing spawns of Spire Scarab and Spire Scorpids. Source: TrinityCore. (#9093)
- chore(DB): import pending files
- fix(Scripts/LBRS): Quartermaster Zigris (#9077)
- refactor(Core): move complex functions from Object.h to Object.cpp (#9016)
- fix(core/Creature): initialize AI before calling OnCreatureCreate
- fix(Scripts/Misc): AhnKahet instance script typo (#9055)
- refactor(Scripts/Commands): Convert cs_mmap to new system (#9020)
- fix(CI/Labeller): correct config key name
- chore(DB): import pending files
- fix(DB/Quest): remove deprecated breadcrumb quests as prerequisites fo… (#9019)
- chore(DB): import pending files
- refactor(Scripts/Spells): convert spell_warrior into new system (#9068)
- refactor(Scripts/Spells): convert spell_warlock into new system (#9066)
- refactor(Scripts/Spells): convert spell_shaman into new system (#9065)
- refactor(Scripts/Spells): convert spell_quest into new system (#9064)
- refactor(Scripts/Spells): convert spell_priest into new system (#9063)
- refactor(Scripts/Spells): convert spell_paladin into new system #9058 (#9061)
- refactor(Scripts/Spells): convert spell_mage into new system (#9058)
- refactor(Scripts/Spells): convert spell_hunter into new system (#9047)
- refactor(Scripts/Creature): convert pets into new system (#9046)
- refactor(Scripts/Spells): convert spell_hunter into new system (#9045)
- refactor(Scripts/Spells): convert spell_druid into new system (#9043)
- refactor(Scripts/Spells): convert spell_dk into new system (#9042)
- feat(Scripts/Commands): convert cs_disable to new system (#9021)
- chore(Misc/Conf): Rearrange World.RealmAvailability (#9002)
- fix(CI): labeller token (#9081)
- fix(Core/Spells): Potential crashes in spell_generic and spell_item (#8810)
- chore(DB): import pending files
- fix(DB/SAI): Goraluk Anvilcrack should always spawn (#9075)
- chore(DB): import pending files
- fix(DB/Conditions): Collect Rookery Egg should require nearby Rookery Egg (#9076)
- chore(DB): import pending files
- fix(Scripts/LBRS): Wyrmthalak, adds no longer despawn after death (#9036)

## 2021-11-08
- fix(Scripts/UBRS): Handle Rend and Drakkisath doors (#9072)
- fix(Scripts/UBRS): Rend's summon spell should be a triggered cast (#9074)

## 2021-11-09
- refactor(Core/Combat): Cleanup DoZoneInCombat function. (#8789)

## 2021-11-08
- chore(Scripts/UBRS) - incorrect unannotated fallthroughs (#9035)
- refactor(GameObjectAI): Change self-accessor to "me" (#9041)
- chore(DB): import pending files
- fix(Core/Build): Delete spell_dbc data with wrong values (#9012)
- chore(DB): import pending files
- fix(DB/Quests): Set Hallow's End Treats quests as repeatable. (#8954)
- fix(Scripts/MoltenCore) Fixed golemagg minions evade due range behavior (#8940)
- fix(Scripts/MoltenCore): Fixed shazzrah "23138 - Gate of Shazzrah" (#8942)
- chore(Script/ApplySpellFix): Correct some comments (#9001)
- chore(DB): import pending files
- fix(Scripts/MoltenCore): Fixed some Geddon encounter issues (#8941)
- fix(docker): Solve the issue with SQL connection strings in env.ac (#9015)
- chore(DB): import pending files
- fix(DB/Creature): Populate Wetlands Farm (#9013)
- refactor(Scripts/Commands): Convert cs_cast to new system (#8997)
- chore(DB): import pending files
- fix(DB/Loot): remove Wintersbite from invalid loot tables. (#8933)
- chore(DB): import pending files

## 2021-11-07
- fix(Scripts/UBRS): General Drakkisath adds (#8988)
- chore(DB): import pending files

## 2021-11-08
- feat(Scripts/Commands): new command to debug play music (#8967)

## 2021-11-07
- chore(DB): import pending files

## 2021-11-08
- fix(DB/Quest): add missing POI for Masked Orphan Matron/Costumed Orphan Matron quests (#8950)

## 2021-11-07
- chore(DB): import pending files
- fix(DB/Creature): Corrects spawn times of various Westfall rare mobs (#8949)
- Core/Spells: Triggered spells should not cause players to stand up (#8986)
- fix(Core/Spells): Troll Roof Stalker's Stealth and Ashenvale Outrunne… (#8984)
- fix(Core/Spells): Slam should suspend attack timers (#8981)
- fix(Core/Players): charge should not delay player's auto attacks (#8978)
- fix(Core/DungeonFinder): enable requeueing inside random dungeon (#8948)
- fix(CI): labelled builds (#9037)
- fix(Labeler): file-cpp (#9025)
- chore(DB): import pending files
- fix(DB/creature_loot): Removes Sayge's Fortunes from all NPCs (#8944)
- chore(DB): import pending files
- feat(CI): skip matrix builds for non-C++ changes (#9008)
- fix(Scripts/DB): UBRS Solakar / father flame  (#8236)
- feat(Core/Packets): rework HandleWhoOpcode (#8863)
- feat(Scripts): Implement generic script loader and registry macros (#8976)
- fix(Scripts/UBRS): Warmaster Voone stances (#8972)

## 2021-11-06
- fix(Core/Spells): Exploit with silithyst aura (#9014)
- chore(DB): import pending files
- fix(Core/DB/SAI): [Quest] - Weapons of Spirit / Allows Value 3 for react SAI WP Start Consolidated PR (#8926)

## 2021-11-07
- fix(Core/DB-Updater): correct world DB update (#9009)

## 2021-11-06
- chore(DB): import pending files
- chore(DB): Fix SQL imports/database revision (#8999)
- chore(DB): import pending files
- feat(Core/Modules): Preparation to implement progression-system module. (#8837)
- feat(Core/SAI): Wp table add in orientation and delay collumn  (#8927)
- chore(DB): import pending files
- fix(DB/Equipment) Add missing weapons to Gordunni npcs (#8924)
- chore(DB): import pending files
- fix(DB/creatures): UBRS stealthed mobs issues (#8858)
- chore(DB): import pending files

## 2021-11-05
- fix(DB/Gossip): go_wind_stone to use db gossip and conditions (#8953)

## 2021-11-06
- chore(DB): import pending files

## 2021-11-05
- fix(DB/Creature): Southsea Swashbuckler equipment (#8913)
- feat(Core/World): Don't prevent players from logging characters by default (#8993)
- chore(DB): import pending files

## 2021-11-06
- fix(Core/Items): properly show quest items count deposited/withdrew from bank (#8956)
- fix(Core/Item): showing errors when cannot equip some item (#8932)
- feat(Scripts/Commands): convert cs_list to new system (#8920)
- featScripts/Commands): convert cs_lfg to new system (#8919)

## 2021-11-05
- chore(DB): import pending files
- fix(DB/SAI) Myranda the Hag (#8911)
- chore(DB): import pending files
- fix(DB/Equipment): Burning Blade NPCs (#8916)
- chore(DB): import pending files
- fix(DB/Gossip): Broadcast text for Jero'me (#8907)
- chore(DB): import pending files
- fix(Script/SAI/Conditions): move npcs_dithers_and_arbington script to SAI (#8909)
- fix(Scripts/Player): some refactor related to PlayerCommand functions (#8975)
- chore(DB): import pending files
- fix(DB/Gossip): Witch Doctor Uzer'i missing text (#8906)
- feat(Core/Spells): implement two new custom attributes to handle aura saving rule (#8377)
- chore(DB): import pending files
- fix(DB/Quest): Added missing poi points for "Hallow's End Treats for Jesper!" (#8905)
- feat(Core/Unit): Implement DoCastRandomTarget() helper (#8876)
- chore(DB): import pending files
- fix(script/LBRS):  Urok Doomhowl improvements (#7960)
- fix(CI): do not skip windows/mac/docker on master branch (#8968)
- fix(CI): run-build label (#8966)
- feat(CI): C++20 build (#8952)
- fix(Core/PlayerUpdates): one more C++20 compile warning (#8959)
- fix(Scripts/UBRS): Correct Drakkisath's guard abilities not being cast (#8957)
- chore(DB): import pending files
- fix(DB/Creature): lowers max level of Fen Dweller (#8002)
- chore(DB): import pending files
- fix(Script/Gossip) Mathredis Firestar (#8895)
- chore(DB): import pending files
- fix(DB/SAI):Twilight Discipline and Twilight Thug scripts(talks an… (#8023)
- chore(DB): import pending files
- fix(Scripts/BlackrockSpire): implement pre-fight The Beast event. Source: TC (#8903)

## 2021-11-04
- fix(Core/Quest): Refresh SMSG_QUESTGIVER_STATUS_MULTIPLE after a quest change (#8902)
- fix(Core/Pets): controllable guardians (including pets) should not set the combat with its target when commanded to attack it. (#8877)

## 2021-11-05
- fix(Core/Commands): correct header `PlayerCommand.h` file structure (#8947)
- feat(Core/Socket): make world OnSocketAccept like auth (#8946)

## 2021-11-04
- fix(Spell/Core): Prayer of Mending Heal not smart Healing [TC Cherry Pick] (#8753)
- chore(DB): import pending files
- refactor(Scripts/Commands): Convert cs_go to new system (#8874)
- fix(Core/Unit): Reduce mobs speed when low on health (#7932)
- chore(DB): import pending files
- feat(Scripts/Command): implement new command: bags clear (#8549)
- chore(DB): import pending files
- fix(DB/Waypoints): Strider Clutchmother (#8044)
- fix(Core/SmartAI): improve SMART_EVENT_GOSSIP_HELLO (#8849)

## 2021-11-03
- chore(DB): import pending files
- feat(Core/Scripting): implement OnlyOnceAreaTrigger & Zul'Gurub's in… (#8850)
- feat(Scripts/Commands): convert cs_instance to new system (#8831)
- fix(Scripts/UBRS): General Drakkisath improvements (#8875)
- chore(DB): import pending files
- fix(DB/creature_loot): Defias Rapier drops (#8836)
- chore(DB): import pending files
- fix(Scripts\ZulGurub): Razzashi Cobra's will act as Venoxis minions (#8141)
- feat(Core/EnumUtils): add more enum for support chat command (#8828)
- chore(DB): import pending files
- fix(DB/SAI): Remove some bad SAI from turtles (#8808)

## 2021-11-02
- chore(DB): import pending files

## 2021-11-03
- fix(DB/item_loot): remove various incorrect items from Mithril Lockbox (#8834)

## 2021-11-02
- fix(Core/Player): clear current title if the player loses it (#8827)
- chore(DB): import pending files

## 2021-11-03
- fix(DB\Broadcast Text): remove double string on emote text (#8791)

## 2021-11-02
- chore(DB): import pending files
- fix(DB/Quest): wrong quest on beached sea turtles (#8809)
- chore(DB): import pending files
- fix(Scripts/BlackrockSpire): Rend Blackhand improvements (#8826)
- feat(Core/Scripts): implemented a guid map in InstanceScript, this wa… (#8781)
- fix(DatabaseWorkerPool): state correct MYSQL version in message (#8782)
- chore(DB): import pending files
- fix(Core\Scripts):Venomhide Hatchling multiple fixes (#8792)
- fix(Core/Map): encounters list for heroic difficulties (#8224)
- fix(Core/Creatures): `AttackStart` in `MoveInLineOfSight` is called only for aggressive mobs. (#8878)
- feat(CI/CheckPending): add check version db line (#8653)
- chore(DB): import pending files
- fix(Scripts/MoltenCore): rewrite (#8741)

## 2021-11-01
- feat(Scripts/Commands): convert cs_object to new system (#8855)
- refactor(Core): update getFaction to GetFaction and setFaction to SetFaction (#8708)
- chore(DB): import pending files
- fix(DB/Locale): improve Draenei translations (#8613)
- fix(Scripts/Spells): Blessing of Ancient Kings crash (#8871)
- feat(Bash/Installer): configure remote and pull branch in conf/config.sh (#8488)
- chore(CI/Ubuntu): remove unused code (#8703)
- chore(DB): import pending files
- fix(Scripts/Scholomance): Grandmaster Gandling correctly drops threat if teleports the tank (#8455)

## 2021-10-31
- chore(DB): import pending files

## 2021-11-01
- fix(DB\Quest): Argent Dawn reward recalculated (#8370)

## 2021-10-31
- chore(DB): import pending files
- fix(Scripts/Northrend): Last Rites [Quest 12019] (#8691)
- chore(DB): import pending files
- fix(DB/Creature): NPC Darcy location (#8804)
- chore(DB): import pending files
- fix(DB\smart_scripts):Kregg Keelhaul spells (#8743)
- feat(Scripts/Commands): convert cs_debug to new system (#8786)
- fix(Scripts/SpellHunter): prevent crash in spell_hun_readiness (#8847)
- chore(DB): import pending files
- fix(DB\SAI):Mottled Screechers calls for help properly now at low health (#8579)
- refactor(Scripts/Commands): Convert cs_event to new system (#8832)
- chore(DB): import pending files

## 2021-10-30
- fix(DB/SAI) Add cosmetic script to Rousch (#8803)
- chore(DB): import pending files

## 2021-10-31
- fix(Core\Scripts): Veridian Broodlings SAI moved into C++ and fixed movement issue after casting (#8638)

## 2021-10-30
- chore(DB): import pending files
- refactor(Scripts/Commands): Convert cs_npc to new system (#8814)
- chore(DB): import pending files
- fix(DB\Creature):Mindless Undead should not give reputation at all (#8793)
- chore(DB): import pending files
- fix(DB\smart_scripts):fixed NPC Greymist Coastrunner Fleeing at low h… (#7990)
- chore(DB): import pending files
- fix(DB/Quest): allows both factions to do Past Endeavors (#8785)
- chore(DB): import pending files
- fix(DB/SAI): Innkeeper Shaussiy missing gossip option
- refactor(Scripts/Commands): Convert cs_character to new system (#8768)
- chore(DB): import pending files
- fix(DB/Quest): The Grateful Dead exclusive groups (#8830)
- chore(DB): import pending files
- fix(DB\Quest):The Greatful Dead can be seen twice (#8774)
- chore(DB): import pending files

## 2021-10-29
- fix(DB/Quest) Tome of Divinity Quest line (#8757)

## 2021-10-30
- refactor(Scripts/Commands): Convert cs_spectator to new system (#8811)

## 2021-10-29
- chore(DB): import pending files

## 2021-10-30
- fix(DB/creature_loot): remove invalid Fadeleaf drops from NPCs (#8748)

## 2021-10-29
- fix(Core/GameObject): Segment fault error fix (#8824)
- refactor(Scripts/Commands): Convert commands to new system Part 1 (#8704)

## 2021-10-30
- fix(Core/Chat): add missing Eluna chat api (#8821)

## 2021-10-29
- chore(DB): import pending files
- fix(DB\Quest): A Crew Under Fire should be repeatable and not counting towards Loremaster (#8742)
- fix(Core/Unit): remove wrong CombatStop() when charming (#8733)
- feat(Scripts/Commands): convert  cs_bf to new system (#8763)
- feat(Core): implement world availability option (#8755)
- chore(Script/Code): remove Not Needed Logging. (#8747)
- feat(Scripts/Commands): convert cs_cheat to new system (#8740)
- feat(Scripts/Commands): Convert cs_achievement to new system (#8736)
- feat(CI/Modules): add more modules (#8816)
- fix(Core) Quest Relations (#8777)

## 2021-10-28
- chore(DB): import pending files
- fix(DB/Procs): Shaman's Elemental Focus should also proc off healing spells (Healing Wave, Lesser Healing Wave, etc.) (#8695)
- chore(DB): import pending files
- fix(Core/QuestNpc): Rework/fix the Stave of Ancients script (#7929)
- feat(Core/Metrics): implement real time statistic visualization (#8663)
- fix(Core/Crashfix): Add nullptr checks for Blood Draining enchant (#8778)
- chore(DB): import pending files
- fix(DB\Creature):Ranger Lord Hawkspear faction (#8371)
- chore(Core/Conf): add missing configuration options (#8761)
- feat(CMake): support version 3.22 (#8773)

## 2021-10-27
- fix(Core/Spell): Implement SPELL_ATTR7_BYPASS_NO_RESURECTION_AURA (#7859)
- fix(Scripts/Commands): Fill the missing argument for the GPS command so it displays its message correctly (#8734)
- feat(Core/SAI): Allow forcing creatures/gameobjects's respawn timers when using SMART_ACTION_FORCE_DESPAWN (#8714)
- chore(DB): import pending files

## 2021-10-26
- fix(Core/GameObject): Spawn linked traps when gameobjects are created (#8572)

## 2021-10-27
- chore(DB): import pending files

## 2021-10-26
- fix(DB/Gameobject): Reinsert several missing gameobject templates (#8722)
- chore(DB): import pending files
- fix(SAI/Script) Quest 8304 Dearest Natalia (#8717)
- chore(Core/DBCEnums): define few SummonPropFlags enums (#8749)
- chore(Core/Arena): LANG_AREAN_ERROR_NAME_NOT_FOUND > LANG_ARENA_ERROR_NAME_NOT_FOUND (#8737)
- chore(DB): import pending files
- fix(DB\smart_scripts):Marin Noggenfogger RP after accepting the elixir quest (#8578)
- chore(DB): import pending files
- fix(Core/DB) Quest 925 Cairne's Hoofprint (#8721)
- fix(Scripts/Hunter): Fixed freeze while using Readiness. (#8709)
- chore(DB): import pending files
- fix(DB/Creature): Removed invalidunit flag from guards in Kharanos and Brill. (#8707)
- chore(DB): import pending files
- fix(DB/Gameobject): Moved Book "Old Hatreds - The Colonization of Kalimdor" to correct location. (#8706)

## 2021-10-25
- fix(Core): enable .freeze and .unfreeze gm cmd for NPCS (#8688)
- fix(Core): ScriptName not readable in creature and gameobject table fix (#8715)
- chore(DB): import pending files
- fix(DB/SAI): Correct Primal Ooze's invisibility target, so they no longer turn players invisible (#8696)
- feat(Core/LFG): move the LFG max kick count & kick prevention timers … (#8683)
- feat(Core): CreatureUnitRelocationWorker reworked (#8672)
- fix(Core/Spells): Devastate vs Glyph of Sunder Armor. (#8705)

## 2021-10-24
- chore(Core): Code Reduction dealing with Logging, (Cosmetic only). (#8686)

## 2021-10-25
- chore(DB): import pending files
- fix(DB/Quest): Fixed Let the Fires Come! quest availability to horde … (#8719)

## 2021-10-24
- feat(Core/Spells): Implemented SPELLVALUE_AURA_DURATION. (#8690)
- fix(Core/DB): Unrestrict the amount of mails loaded (#8687)
- chore(Core/AI): Change a FollowerAI log from error to debug (#8685)
- chore(DB): import pending files
- fix(Core/Spell): Recall destination for Insignia trinkets using CFBG (#8679)
- chore(Config): Update example text of DataDir (#8684)
- fix(Core/Spells): Spirit of Kirith spell summon duration adjusted (#8680)
- fix(Core/Spells): SPELL_AURA_PROC_TRIGGER_DAMAGE auras should not proc if target is immuned (#8675)
- fix(Core/Spells): Polymorphed targets should call assistance. (#8674)
- fix(Core/Spells): Auras triggered by talents/glyphs should be removed on respec. (#8671)
- chore(DB): import pending files
- fix(Core/Script) Quest 11590: Abduction (#8668)
- chore(DB): import pending files
- fix(DB/Waypoint): DB Error from Creature (#8666)
- chore(DB): import pending files
- fix(Core/Script) Quest 11794: "The Hunt is on" (#8650)
- chore(DB): import pending files
- fix(DB\smart_scripts):Gnarlpine Shaman healing timers adjusted (#8639)
- chore(DB): import pending files
- fix(DB/loot): Fixed chicken egg loot (#8636)
- chore(DB): import pending files
- fix(Scripts/Quests): "Let the fires come" and "Stop the fires" should… (#8565)

## 2021-10-23
- fix(Core/DungeonFinder): Random Dungeon Finder always removes no perm… (#8561)
- fix(Core/Professions): Fixes some profession specs available without … (#8385)
- chore(DB): import pending files
- fix(DB\Creature):Raging Owlbeast relocation (#8495)
- chore(DB): import pending files
- feat(Core/Chat): new argument parsing and unify chat hyperlink parsing (#6243)

## 2021-10-22
- chore(DB): import pending files
- refactor(Scripts/Stratholme): move Baroness Anastari script to CPP (#8562)
- chore(DB): import pending files
- fix(DB\GameObject):Small Throium Vein location adjusted (#8661)
- chore(DB): import pending files
- fix(DB/Loot): Rotting worm doesn't drop money (#8657)
- chore(DB): import pending files
- fix(Core/Spells): Silithyst (#8656)
- chore(DB): import pending files
- fix(DB/Loot): Blackrock Champion (#8634)
- fix(Core/AI): possible "self interrupts" in BossAI::ExecuteEvent calls (#8654)
- fix(Core/Spells): passive auras should not stak with itself (#8652)
- chore(DB): import pending files
- fix(DB/creature_loot): removes invalid Goldthorn drops from NPCs (#8649)

## 2021-10-21
- fix(Core/BattlegroundAV) Irondeep/Coldtooth Supplies never despawning (#8612)
- chore(DB): import pending files
- fix(Core/Script): Tomb of 7 in brd (#7991)
- chore(DB): import pending files
- fix(Core/Conditions): Conditions not working for area auras (#8648)
- fix(Core/Combat): Removed some invalid code about auto-acquiring a nearby target if primary target is not detectable by creature. (#8624)
- chore(DB): import pending files
- fix(DB/creature_loot): Crimson Hammersmith (#8547)
- fix(DB/npc_trainer): Req mining skill for "Smelt Thorium" (#8544)
- fix(DB\Loot):Minor Magic Resistance should not drop (#8533)
- fix(DB/Loot) Gargoyle's Fragment drop chance (#8459)
- fix(Scripts/Spells): Fixed Enrage armor reduce part. Source: TrinityCore. (#8625)
- chore(DB): import pending files
- fix(DB): add emotes to guards part 7 (#8450)
- chore(DB): import pending files
- fix(DB): add emotes to guards part 6 (#8449)
- chore(DB): import pending files
- fix(DB/SAI): Innkeeper Allison's Trick or Treat cast (#8599)
- chore(DB): import pending files
- fix(DB): add script to Mountaineer Pebblebitty (#8271)

## 2021-10-20
- chore(DB): import pending files
- chore(DB/SAI): remove missing SAI link for Risen Aberrations (#8587)
- chore(DB): import pending files
- fix(DB/Quest): "Chicken Clucking for a Mint" not being completable and add missing emotes (#8567)
- chore(DB): import pending files

## 2021-10-21
- fix(DB/Gossip) Fix Tirion's gossip order for to the Redemption quest (#8568)

## 2021-10-20
- chore(DB): import pending files
- fix(DB/SAI): Remove SMARTCAST_COMBAT_MOVE from Jadenir Oracles/Tree Wardens spell cast SAI (#8584)
- chore(DB): import pending files
- fix(DB): correct db_world updates (#8646)
- chore(DB): import pending files
- fix(DB/Quests): Corrected required faction requiements for PvP Care P… (#8379)
- feat(Core/Quests): Implemented quest_money_rewards (for quest with Qu… (#8610)
- chore(DB): import pending files
- fix(DB/quest): Sets Apothecary Dithers as quest start/end for "The Key to Scholomance" (#8552)
- fix(DB/quest): Make 5 Craftsman's Writ quests repeatable (#8555)
- fix(DB/Quest): "Fire Brigade Practice" and "Fire Training" are now pr… (#8569)
- fix(DB/quest_template): quest completion text "The Art of the Armorsmith" (#8597)
- feat(Core/Battlegrounds): Added extra parameter to `SetQueueAnnouncementTimer`. (#8607)
- fix(Core/Spells): Dismount from flying mount if teleported to Nothrend without Cold Weather Flying spell. (#8524)
- fix(Core/DungeonFinder): Premade groups should be treated as normal groups. (#8520)
- fix(DB\Loot):Magic Resistance Potion should not drop at all (#8518)
- fix(DB\Loot):Catseye Elixir should not drop at all (#8517)
- fix(DB\Loot):Decoded Twilight Texts should not drop from creatures (#8493)
- feat(Core/CLI): Flash WorldServer at start (Windows only) (#8477)
- chore(DB): import pending files

## 2021-10-19
- fix(DB/Quest): The Sun Gate (#8593)

## 2021-10-20
- feat(DB): release ACDB 4.0.0 (#8494)

## 2021-10-19
- chore(DB): import pending files
- refactor(Script/SAI): Move Corastrasza script to SAI (#8616)
- chore(DB): import pending files
- fix(DB/Creature): The Black Brewmaiden (#8514)
- chore(DB): import pending files
- fix(DB/Creature): remove mount visual from Forsaken Thugs (#8560)
- fix(Core/Player): restore the removal of pending sale mails (it was accidentally removed in https://github.com/azerothcore/azerothcore-wotlk/pull/8065) (#8550)
- fix(Scripts/Spells): fix a crash with resto shaman's t10 chain heal procs (#8614)

## 2021-10-18
- chore(DB): import pending files
- feat(Scripts/SAI): Ported Riding the Red Rocket Quest script from TCO (#3704)
- chore(DB): import pending files
- fix(DB/Quest): Fallen Hero of the Horde should offer a Fel Salve replacement if the player has destroyed the required quest items (#8501)

## 2021-10-17
- chore(DB): import pending files

## 2021-10-18
- fix(DB/creature): Delete Duplicated Squirrel in DM East (#8582)
- fix(DB/GMO_locale): DM East GMO deDE Option Text (#8583)

## 2021-10-17
- chore(DB): import pending files

## 2021-10-18
- fix(DB\smart_scripts):Sara Balloo missing RP (#8580)

## 2021-10-17
- chore(DB): import pending files

## 2021-10-18
- fix(DB\Loot):Cuergo's Hidden Treasure synced drop rate to an item and added additional item (#8490)

## 2021-10-17
- fix(DB/locale): Some translations of quests in the Draenei starting area (#8525)
- chore(DB): import pending files
- fix(DB/creature_loot): Removes Black Metal War Axe from RLT (#8447)
- fix(Core/Gossip): Fix gossip menu for locale clients (#8396)
- chore(DB): import pending files
- fix(DB/GO): flying Arthas' Tears (#8443)
- chore(DB): import pending files
- fix(DB\Creature): Longsnout spawns (#8211)
- fix(Core/Battlegrounds): Fixed timed announcement system for CrossfactionBG module. (#8521)
- fix(Core/Entities): fix contested flag timer when logging out and in (#8558)

## 2021-10-16
- chore(DB): import pending files

## 2021-10-17
- fix(DB\Quest): Fragments of the Past POI relocated (#8489)

## 2021-10-16
- fix(Core/Globals): Check if creatures got any valid `InhabitType` dur… (#8464)
- fix(Core/Script): Valithria Dreamwalker event reset over 75% heal. (#8286)
- chore(DB): import pending files
- fix(Core/Event): improve "Let the fires come" event (#8199)
- chore(DB): import pending files
- fix(DB/Quest): Defenders of Darrowshire (#8467)
- docs: update CONTRIBUTING.md (#8435)
- chore(DB): import pending files
- fix(DB\Quest): make 2 Hallow's End quests not repeatable (#8516)
- chore(DB): import pending files
- fix(DB/creature_loot): Remove Dark Iron Ore from various NPCs (#8512)

## 2021-10-15
- fix(DB/Auras): add AuraInterruptFlag for Gordok Ogre Suit (22736) (#8492)

## 2021-10-16
- chore(DB): import pending files
- fix(DB/creature_loot): Removes invalid Firebloom drops from various NPCs (#8446)

## 2021-10-15
- chore(DB): import pending files
- fix(DB/SAI): Risen Aberration being immune to holy damage (#8438)
- chore(DB): import pending files
- fix(DB/Gossip): correct Lorax's gossip action menu ID (#8436)
- chore(DB): import pending files
- refactor(Core/Unit): clean MonsterText methods (#6957)

## 2021-10-14
- chore(DB): import pending files

## 2021-10-15
- fix(DB/Quest): fix Supplies for the Crossroads pre-requisite (#8456)

## 2021-10-14
- chore(DB): import pending files

## 2021-10-15
- refactor(Core/Creature): Rename some TypeFlags (#8483)
- fix(DB/creature_loot): Remove Plans: Corruption from various NPCs (#8482)
- fix(DB/disenchant_loot): DE loot for Dusty Mail Boots (#8451)
- fix(Core/Spells): Revive pet cannot be used on alive pets. (#8434)

## 2021-10-14
- chore(DB): import pending files
- chore(Conf): move BG QueueAnnouncer conf to the right section (#8515)
- fix(DB/Conditions): Fix conditions for Larion's Bloodpetal Zapper rep… (#8432)
- fix(DB/Misc): Fix gossip conditions for 'Altar of Suntara' and add ac… (#8429)
- fix(Core/Spells): Fix all cases of client crash when pressing ESC after a spell being cast (#8497)
- fix(Scripts/Spells): Fix Lock and Load proc from Frost Trap (#8441)
- fix(DB/Creature): Scarshield Portal (#7426)
- fix(Core/EventScripts): Credit nearby group members when using the SCRIPT_COMMAND_QUEST_EXPLORED event_scripts command (#8378)
- fix(CORE/Unit): Fix controllable guardians evading when not posed to be (#7959)
- fix(Core/Units): clear emote state on attack rather than on combat st… (#8170)
- chore(DB): import pending files
- fix(DB/SmartScripts): Removed casting Dazed from smart scripts. (#8430)
- fix(DB/Quest): Pawn Captures Queen (#8422)
- feat(Core/SAI): implemented a new SAI action type SMART_ACTION_DO_ACTION (#8375)
- chore(DB): import pending files
- feat(DB): add support squash db for archive dir (#8496)
- chore(DB): import pending files
- fix(Scripts/Spells): Linken's boomerang (#8179)
- fix(Core/SAI): Update SMART_ACTION_FORCE_DESPAWN to allow temporarily despawning gameobjects (#8340)
- fix(DB/Creature): Young Wetlands Crocolisk (#8353)
- fix(Core/DungeonFinder): Seasonal bosses are available only via Dunge… (#8056)
- fix(DB/Loot): changed sum RLT fo Blackrom Champion (#8055)
- fix(Core/Entities): contested guards attacking after bg/recent pvp (#7518)
- chore(DB): import pending files
- refactor(Core/Achievement): Achivement earned message will use broadc… (#8485)
- feat(Core/Player): add helper for send large count mail items (#8460)
- fix(CI/Docker): Run build on label (#8487)

## 2021-10-13
- chore(DB): import pending files

## 2021-10-14
- fix(DB/Creatures): fix various motionless rare spawns - 40-49 bracket (#6653)

## 2021-10-13
- chore(DB): import pending files
- fix(Core/Graveyards): rework the graveyard selection logic to allow l… (#8022)
- Revert "feat(APPS/installer): configure remote and pull branch in conf/config.sh (#8364)" (#8486)
- feat(Core): GetDeadCreatureListInGrid helper added, for aoe loot (#8445)
- feat(Core/SAI): implemented boss state handling in SMART_ACTION_SET_INST_DATA + added additional data checks (#8369)
- chore(DB): import pending files
- fix(DB): golorn frostbeard and curator thorius (#8269)
- chore(DB): import pending files
- fix(DB/Quest): Very tasty! (#8362)
- chore(DB): import pending files
- fix(DB/Spells): fix the spell proc from Haunted, incorrectly phasing p… (#8402)

## 2021-10-12
- fix(Scripts/Spells): Fix pets not being resurrected by BG Spirit Healers (#8421)
- feat(APPS/installer): configure remote and pull branch in conf/config.sh (#8364)
- fix(Core/Spells): Always stand up on spell cast. (#8337)
- fix:(Core\Scripts):Krikthir the Gatewatcher minions position (#8120)
- fix(Core/Player): fix Eluna hook in Player::CanUseItem (#7117)
- chore(DB): import pending files
- fix(DB): add Emote Reactions to Guards part 5 (#8317)
- chore(DB): import pending files
- fix(DB\Quest): Argent Dawn Commission faction-locked (#8267)
- chore(DB): import pending files
- refactor(Core/CreatureAI): Turn hardcoded entries into flagsExtra (#8189)
- fix(Core/Unit): perform melee attack when unit has not enough power for melee spell (#7996)
- chore(DB): import pending files
- fix(DB/creature_template_addon): add missing passive threat reset auras for some creatures (#7222)

## 2021-10-11
- fix(Core/Pets): Disable /petfollow command while using vehicle. (#8304)
- chore(DB): import pending files
- feat(Core/Hooks): Added new hook for pvp flag state (#8336)
- fix(Core/Spells): Fixed absorb auras not working with spell damage. (#8427)
- chore(Core): add Prefix to Command menu
- fix(Core/Spells): typo 89f0c42c0 (#8398)

## 2021-10-10
- chore(DB): import pending files

## 2021-10-11
- fix(DB/Quest): Make Armaments of Battle repeatable (#8400)
- fix(DB/Loot): Remove Commander Eligor Dawnbringer's loot table (#8393)

## 2021-10-10
- fix(Script/Spells): Summon Shy-Rotam (#8382)

## 2021-10-11
- fix(DB/creature_loot): Remove invalid Purple Lotus drops from NPCs (#8373)
- fix(DB/Creature): Remove invalid Wildvine drops from various NPCs (#8368)
- fix(DB/Quest): Craftsman's writ (#8363)

## 2021-10-10
- fix(DB/Creature): Correct GroupAI for Tendris Warpwood's formation (#8357)

## 2021-10-11
- fix(DB/Object): Bruiseweed spawn (#8356)

## 2021-10-10
- fix(DB/Quest): When Smokey sings, I get violent (#8338)

## 2021-10-11
- fix(DB/Gameobjects): Fixed respawn time of some footlockers. (#8335)
- fix(DB/quest): Fix Defiling Uther's Tomb visuals & quest objective (#8334)
- fix(DB/Gameobjects): Corrected position of one bonfire in Orgrimmar during Midsummer event. (#8333)
- fix(DB/Creature): Delete Tactical Task Briefing IX from Rex Ashil (#8332)
- fix(DB/Quest): Mission Accomplished! (#8328)

## 2021-10-10
- fix(DB/GameObject): Correct Karazhan's entrance hall door's spawn data (#8320)

## 2021-10-11
- fix(DB/Creature): Add Emote Reactions to Guards Part 4 (#8316)
- fix(DB/Creautre): Add Emote reactions to Guards Part 3 (#8314)
- fix(DB/Loot): Remove Mageroyal from invalid loot tables. (#8311)
- fix(DB/Loot): Remove Mountain Silversage from invalid loot tables. (#8310)
- fix(DB/Loot): Remove Dreamfoil from invalid loot tables. (#8309)
- fix(DB/Loot): Remove Golden Sansam from invalid loot tables. (#8308)
- fix(DB/Loot): Remove Gromsblood from invalid loot tables. (#8307)
- fix(DB/Loot): Remove Ghost Mushrooms from invalid loot tables. (#8305)
- fix(DB/Loot): Remove Sungrass from invalid loot tables. (#8303)
- fix(DB/Loot): Remove Blindweed from invalid loot tables. (#8302)
- fix(DB/Creature): Fixed Gravis Slipknot (#8300)
- fix(DB/Creature): Populate Ironforge Airfield Part 1/2 (#8272)
- fix(DB/Quest): Add outro for "Prospect of Faith" quest (#8270)
- fix(DB/Events): Added missing signposts to Warsong Gulch CTA banners. (#8258)
- Fix(DB/reputation) Strat/scholo change reputations for spawned mobs (#8238)
- fix(DB\GameObject):Peacebloom unaccesible removed (#8212)
- fix(DB/Creature): Add Emote Reactions to Guards Part 2 (#8200)
- fix(DB\Creature): Cornish Rex Cat removed incorrect spawn (#8197)
- fix(DB/Object): Repositioning a Copper Vein (#8188)
- fix(DB/Creature): Fixed gossip for Innkeeper Pala. (#8181)
- fix(DB/Creature): Added missing Traveling Orphans (#8180)
- fix(DB/Creature): Add Emote Reactions to Guards Part 1 (#8178)
- fix(DB/Gameobject): Moves a Goldthorn herb to the ground (#8104)

## 2021-10-10
- fix(Core/Mail): load mails on login instead of when requested (#8065)
- fix(Core/Spells): add several missing null checks for the DamageInfo struct to fix a crash (#8322)
- fix(Core/Spells): add several missing null checks for the DamageInfo struct to fix a crash - Part II. (#8376)
- chore(DB): import pending files
- fix:(DB/GObject): remove double spawns for Bonfire and Mighty Blaze in Orgrimmar (#8088)

## 2021-10-09
- chore(DB): import pending files

## 2021-10-10
- fix(Scripts/Instances): fix some bosses flying animations (#7851)

## 2021-10-09
- feat(Core/LFG): Implemented LFG_OPTION_ENABLE_SEASONAL_BOSSES. (#8219)
- fix(Core/Spells): Restore dafef5bd78 (#8380)
- chore(DB): import pending files
- fix(DB/gossip_menu): add vendor option to Innkeeper Shaussiy (#8078)
- fix(Core/Quest): Update all quests when item is optained/removed (#7862)
- fix(Core/Item): Dropped loot containers acting soul bound after looking inside them. (#7826)
- chore(DB): import pending files
- fix(DB/SAI): Baron doors now close and open properly. (#8263)
- chore(DB): import pending files
- fix(DB/Loot): Remove some invalid reference loot. Fixes #8248 (#8284)
- chore(DB): import pending files
- fix(DB/Event): Fixed some doubled gameobject spawns during Harvest Festival. (#8203)
- chore(DB): import pending files
- fix(DB/Quest): Fixed Quest Stone Circle POIs (#8348)

## 2021-10-08
- chore(DB): import pending files

## 2021-10-09
- fix(DB/Brewfest): Removed invalid decoration. (#8256)

## 2021-10-08
- chore(DB): import pending files

## 2021-10-09
- fix(DB/SAI): Added self healing to Stonesplinter Shamans (#8298)

## 2021-10-08
- chore(DB): import pending files

## 2021-10-09
- fix(Gameobject/Loot): Fixed loot chance of Giant Clams (#8279)

## 2021-10-08
- chore(DB): import pending files
- fix(DB/gameobject): Add Rich Thorium Vein spawns inside Dire Maul East (#8288)
- chore(DB): import pending files

## 2021-10-09
- fix(DB/creature): Remove Civilian flag from Emeral Dragon Whelp (#8245)

## 2021-10-08
- chore(DB): import pending files

## 2021-10-09
- fix(DB/creature_loot): Reduce Alanna's Embrace drop rate (#8215)

## 2021-10-08
- chore(DB): import pending files
- fix(Scripts/Brewfest): Rewritten Coren Direbrew's fight(#8040)
- chore(DB): import pending files
- fix(DB/Events): Added missing Brewfest spawns outside Exodar and Shat… (#8283)
- chore(DB): import pending files
- fix(DB/Quest): A Taste of Flame (#8282)
- chore(DB): import pending files
- fix(DB/Loot): Remove Arthas' Tears from loot tables. (#8285)
- chore(DB): import pending files
- fix(Quest): Fixed Bone Collector Quest Missing Kodo Apparition Spawns (#8278)
- feat(Core/Eluna): Added new OnPetAddedToWorld() hook for Eluna. (#8084)
- chore(DB): import pending files
- fix(DB/Spell): Arcane Concentration should proc only from damaging spells. (#8218)
- fix(Core/Movement): Improved player's pet follow movement. (#8217)
- chore(DB): import pending files
- fix(DB): adds location information to game objects 2/17 (#7731)
- chore(DB): import pending files
- fix(DB/creature): add 8 spawns for Giant Webwood Spider (#8137)
- chore(DB): import pending files
- fix(DB/GameObject): Remove Sabotage Plans (#8185)
- chore(DB): import pending files
- fix(DB/Gameobject): Make Giant Softshell Clam lootable (#8096)
- chore(DB): import pending files
- fix(DB/Creature): Laughing Sister spawned inside a tree (#8086)
- chore(DB): import pending files
- fix(DB/creature): Move Zhevra Runner spawn from inside tree (#8076)

## 2021-10-07
- chore(DB): import pending files
- fix(DB/Quest): Properly despawn Slim's friend if the player dies (#8274)
- chore(DB): import pending files
- fix(Scripts/BRD): Rework Shadowforge Braziers (#8233)
- chore(DB): import pending files
- fix(DB/Spells): Malown's Slam should proc Surge of Strenght (#8268)
- fix(Core/Spells): Premeditations should not break enemy's stealth. (#8220)
- fix(Core/Pets): Eye of Kilrogg should not put its owner in combat wit… (#7193)
- chore(DB): import pending files
- fix(DB/GameObject): Copper Ore corrected spawn (#8213)
- chore(DB): import pending files
- fix(DB\Creature): Moonstalker Runt maxlevel (#8210)
- chore(DB): import pending files
- fix(Core/Spells): Improved Drain Soul triggering from every target … (#8144)
- chore(DB): import pending files
- fix(DB/Fishing): add seasonal fish, Raw Summer Bass/Winter Squid. Source: TrinityCore (#8175)
- chore(DB): import pending files
- fix(DB/acore_string): Spanish translation of entry 5030 (#8164)
- chore(DB): import pending files
- fix(DB/SAI): oozes not despawning after using Empty Tainted Ooze Jar for the quest A Little Slime Goes A Long Way (#8124)
- chore(DB): import pending files
- fix(DB/Creature): add spawn point and movement to Sister Riven (#8103)
- chore(DB): import pending files
- fix(DB): Burning Steppes drake paths (#8068)
- chore(DB): import pending files
- fix(DB/creature): Adds spawn and movement to Lady Sathrah (#8117)
- chore(DB): import pending files
- fix(DB/Spell): Glodrak Huntsniper should not spaw with his mug throwing spell if player does not have Portable Brewfest Keg. (#8062)
- fix(Core/LFG): implement ERR_PARTY_LFG_BOOT_NOT_ELIGIBLE_S and lower … (#8243)
- fix(Core/GameObject): credit nearby group members on object activation if they're in reward range (#8240)
- fix(Core/SAI): Fix SMART_ACTION_CALL_AREAEXPLOREDOREVENTHAPPENS not working with gameobject sources if the player is in group (#8234)
- fix(CI/Docker): don't build images in forks (#8225)
- fix(Core/Graveyard): prevent non-death knights from getting ported to… (#8206)
- fix(Core/Formations): mistake in radians calculation (#8205)
- fix(Scripts/Event): Always the nearest baker should throw Complimentary Brewfest Sampler back. (#8204)
- chore(DB): import pending files
- fix(DB): update newly spawned instance rares (#6513)
- chore(DB): import pending files
- fix(DB): adjust Raene Wolfrunner gossip behaviour (#6057)

## 2021-10-06
- chore(DB): import pending files
- fix(DB/Creature): Deepstrider Searcher resets when attacked underwater (#7038)
- chore(DB): import pending files
- fix(DB/Creature): Fix Incendosaur Respawn Timer (#8296)
- fix(Core/Crash): Evade after cleaning threat references. (#8160)
- Fix(Core/Crash): Fixed a typo on Pet::_SaveSpellCooldowns. (#8277)

## 2021-10-05
- fix(CI): Don't run builds when PRs are labeled (#8290)
- feat(Core/Spells): add helper to get clean and unmitigated damage for pro… (#7244)

## 2021-10-04
- chore(DB): import pending files
- fix(DB/Creature): Bael'dun Digsite mob flags fixed (#8069)
- chore(DB): import pending files
- fix(Core/Spells): correct hunter's Lock and Load procs (#8177)
- fix(Core/LFG): Properly teleport players to new instance if queued within the same dungeon. (#8174)
- fix(Core/Spells): improve displaying spell category cooldowns in client UI. (#8172)
- fix(Core/Spells): properly handle SPELLMOD_COOLDOWN for spell category cooldowns. (#8161)
- fix(Core/Players): solve issue with hunters never being able to roll need on polearms and properly check conditions to roll on relics (#8148)
- fix(Core/Player): check for existing corpse on respawn (#8112)
- fix(Core/Mails): mails containing items not being returned if they were read and ensure mails sent by GMs are not returned (#8095)
- fix(Core/Spells): Implemented SPELL_ATTR0_CU_NO_PVP_FLAG. (#8092)
- fix(Core/Spells): basepoints of spell 'Pick Lock' being wrongly added to player's lockpicking skill when evaluating if a lock can be opened (#8072)
- fix(Core/Items): toggle temporary items enchantments during items swap. (#8067)
- fix(Core/Chat): properly log zone name when logging GM commands, as some areas don't have parent zone set (#8066)
- fix(Core/Commands): partially fix an issue with mails sent from console never showing up the 'Customer Support' sender in-game (#8064)
- chore(DB): import pending files
- fix(DB): Twilight Lord Everun Waypoint (#8039)
- chore(DB): import pending files
- fix(DB/creature_template): Enable swimming for Tooga (#8116)
- fix(Core/Movement): disable invalid code about getting area info from GOs (#7898)
- chore(DB): import pending files
- fix(DB/quest_template): Quest Book Of Ur (#8136)
- chore(DB): import pending files
- fix(DB/smart_script): Add 'Clone' spell to Devouring Ectoplasm (#8079)
- refactor(Core/Map): Use std::chrono for SetZoneOverrideLight (#6489)

## 2021-10-03
- chore(DB): import pending files
- fix(DB/SAI): Uniting the Shattered Amulet (#8123)
- chore(DB): import pending files

## 2021-10-04
- fix(DB/loot): Remove high-level consumeables from Scorpid Reaver (#8075)

## 2021-10-03
- fix(Core/Achievements): Fixed showing achievement statistics of inspected player. (#8093)
- chore(DB): import pending files

## 2021-10-04
- fix(DB/quest): Add 2 day time delay to Gubber Blump's letter (#8074)

## 2021-10-03
- chore(DB): import pending files
- fix(DB/creature): Colonel Kurzen's respawn time (#8060)

## 2021-10-02
- chore(DB): import pending files

## 2021-10-03
-  fix(DB/Reputation): change Rep Cenarion (#8046)

## 2021-10-02
- fix(Core/Loot): players can roll on unique items they already own (#8003)
- fix(CI/MacOS) openssl sym link (#8201)
- feat(Core: new hook OnPlayerQueueRandomDungeon() and revert (now unnecessary) PR (#8196)
- fix(Core/Instances): Fixed displaying warning about entering instance in progress. (#8171)

## 2021-10-01
- chore(DB): import pending files
- fix(DB/Loot): removes under-leveled loot from Anvilrage Guardsman (#8036)
- fix(DB): Codestyle (#8190)
- Fix(Core/Uldaman): Door behind Archaedas can close after event. (#8024)
- fix(Core/Players): Fixed getting resting exp in cities/inns. (#8020)
- fix(Core/Movement): Properly handled root movement acks. (#8019)
- Fix start scripts (#8005)
- fix(Core/Spells): Ensure gameobjects are still locked/closed when loc… (#8012)
- fix(Core:Battlegrounds): fixes some Arathi Basin achievements. (#8009)
- chore(DB): import pending files
- fix(DB/Quest): Freedom for All Creatures (#7995)
- fix(Core/Spells): Added 3y radius to Feral Charge. (#7901)
- chore(DB): import pending files
- fix(DB/Quest): Suntara Stones escort quest (#7994)
- fix(Core/Spells): Do not send doubled learning packet if spell is lea… (#8140)

## 2021-09-30
- Translation and modifications in extractor.bat (#7992)
- chore(DB): import pending files
- fix(DB/Creature): Elixir of Giants removed (#7973)
- feat(License): add new headers information about license (#7941)

## 2021-09-29
- refactor(Core/SpellEffects): Rework some of the null checks (#6987)
- chore(DB): import pending files
- fix(DB/Creature): arcane elixir drops removed (#7972)
- fix(CI/MacOS): pinto openssl@1.1 (#8150)

## 2021-09-28
- feat(Core/Battlegrounds): Implemented new timed config for queue anno… (#8053)

## 2021-09-27
- chore(DB): import pending files

## 2021-09-28
- fix(DB/creature):Change model for Captain Halyndor (#8037)

## 2021-09-27
- fix(DB/Spells): Contagion of rot (#8021)
- chore(DB): import pending files
- fix(DB/Loot): Removes incorrect drops from Highland Razormaw (#8017)
- chore(DB): import pending files
- fix(DB/Loot): corrects the drop rate of Winterfall Firewater (#8016)
- chore(DB): import pending files
- fix(DB/Areatriggers): Remove wrong areatrigger teleport entries for Orbs of Translocation in Eversong Woods (players should use the gobs instead) (#8015)

## 2021-09-25
- chore(DB): import pending files
- fix(Core/Players): Properly save resting state to DB. (#8014)
- fix(Core/Script): 'Battle at Valhalas' quests done automatically (#7036)

## 2021-09-24
- fix(Core/Calendar): Solve the issue with calendar event invite response time never updating (#8006)
- chore(DB): import pending files
- fix(Core/Creature): Fixed GroupAI flags usage in creature_formations (#7544)
- chore(DB): import pending files
- Fix NPC Lord Lakmaeran (#8013)
- chore(DB): import pending files
- fix(Scripts/Brewfest): Some tweaks to Dark Iron Attack event. (#8026)

## 2021-09-23
- chore(DB): import pending files

## 2021-09-24
- fix(DB/creature): Adjust creature spawn location at Badlands (#5719)

## 2021-09-23
- chore(DB): import pending files
- fix(DB/Creature): removes Elixir of Dream Vision from creature loot (#8004)
- chore(DB): import pending files
- fix(Script/Quest): move Shay Leafrunner's script from DB to C++ (#7801)

## 2021-09-22
- chore(DB): import pending files
- fix(DB/Quest): testing the Tonic (#7935)
- chore(Bash/installer): update client-data version (#8000)

## 2021-09-21
- chore(DB): import pending files
- fix(Core/Spells): Implemented PROC_EX_ONLY_FIRST_TICK (#7933)
- chore(DB): import pending files
- fix(DB/Quest_template): Location for Twisted Hatred (#7953)
- chore(DB): import pending files
- fix(DB/reference_loot): Remove Hide of Lupos from RLT 24062 (#7951)
- chore(DB): import pending files
- fix(Scripts/ZulFarrak): Moved Sergeant Bly's script from DB to C++ (#7855)
- chore(DB): import pending files
- fix(DB/creature_loot_template): Elixir of Demonslaying should not drop (#7988)
- chore(DB): import pending files
- fix(DB/creature_loot): Remove Icecap drops from NPCs (#7949)
- chore(DB): import pending files
- fix(DB/creature_loot): Remove Plaguebloom drops from NPCs (#7950)
- feat(CI/Labeler): Add Batch label (#7993)

## 2021-09-20
- chore(DB): import pending files

## 2021-09-21
- fix(DB/GO): Makes two mining Nodes wholly visible (#7958)
- fix(Core/Combat): Creatures should evade if its only victim is teleporting to other map (#7975)
- fix(Core/Player): Remove mount aura on a flight (#7976)

## 2021-09-20
- fix(Core/BRD): Timer for tomb of seven (#7952)
- chore(DB): import pending files

## 2021-09-21
- fix(DB/creature_loot): Remove Black Lotus drops from NPCs (#7948)

## 2021-09-20
- fix(Core/Spells): Properly remove item dependent passive auras on item unequip (#7944)
- chore(DB): import pending files
- fix(DB/Quest): The Corrupter Pt. 3 (#7942)
- chore(DB): import pending files
- fix(DB/Quest): Bloody Imp-ossible! (#7936)
- chore(DB): import pending files
- fix(DB/Quest): Jin'Zil's Forest Magic (#7927)
- chore(DB): import pending files
- fix(DB/GO): Despawn chests for "Grimtotem Spying" (#7916)
- chore(DB): import pending files
- fix(DB/creature): Geltharis movement (#7915)
- chore(DB): import pending files
- fix(DB/loot_template): Drop rate of Atal'ai items (#7910)
- chore(DB): import pending files
- fix(DB/creature_loot_template): Remove Elixir of Greater Agility (#7909)
- chore(DB): import pending files
- fix(DB/Quest): The Stones That Bind Us  (#7906)
- chore(DB): import pending files
- fix(DB/reference_loot_template): Drop rate for Princess Theradras (#7900)
- chore(DB): import pending files
- fix(DB/dungeon_access_requirements): Key required by the horde (#7893)
- chore(DB): import pending files
- fix(DB/creature): add movement to Spindleweb Lurkers (#7894)
- fix(Core/Map): remove ABORT() to prevent crash (#7904)
- chore(DB): import pending files
- fix(DB/creature): Adds movement for Stonewing Slayer & Phantasmal Seeker (#7891)
- chore(DB): import pending files
- fix(DB/gameobject): Add location information to game objects 5/17 (#7888)
- fix(CORE/Reputation): +Rep aura modify quest with override faction (#7887)
- chore(DB): import pending files
- fix(DB/Creature): Fel'zerul RP on The Temple of Atal'Hakkar quest (#7885)
- chore(DB): import pending files
- fix(DB/Creature): Added auras to some creatures (#7883)
- chore(DB): import pending files
- fix(DB/gameobject): Rotations of plaques in Royal Gallery (#7882)
- fix(Core/Spells): Applying category spell cooldown instead of spell cooldown (#7878)
- fix(Core/Spell): Add additional check to LoadSpellScripts() (#7860)
- fix(scripts/Thaddius): Update initial unit_state (#7886)
- chore(DB): import pending files
- fix(DB/broadcast_text_locale): Typo on Lore Keeper of Norgannon's Greetings (#7903)

## 2021-09-19
- chore(DB): import pending files

## 2021-09-20
- fix(DB/Creature): Eversong Woodsm(Dead Scar) multiple mobs not wandering when idle (#7873)
- refactor(Core/Misc): Use .empty() instead of == "" (#7870)
- refactor(Core/Maps): Change map file version from FourCC to uint32 (#7866)

## 2021-09-19
- fix(Core/Unit): Improve check for players to automatically stand if a… (#7869)
- chore(DB): import pending files
- Fix(DB): Gelkis/Magram reputations (#7880)
- fix(Core/Misc): SendAuthWaitQueue typo (#7868)
- fix(Core/Spell): Remove SPELL_ATTR4_NO_CAST_LOG from being applied to some spells (#7867)
- chore(DB): import pending files
- fix(DB/Quest): Fix undead starting quests allowed races (#7876)
- chore(DB): import pending files
- fix(DB/game_tele): Duplicate teleport name (#7864)
- fix(Scripts/Spells): Fixed never-ending Victorious state proc off from Victory Rush. (#7856)
- chore(DB): import pending files
- fix(DB/Creature): Move Ashenvale Elder Bear spawn (#7747)

## 2021-09-18
- chore(DB): import pending files
- fix(Scripts/Items): Powerful Anti-venom (#7854)
- chore(DB): import pending files
- fix(DB/Creatures): Removed interrupt mechanic immune mask for Befouled Water Elemental. (#7751)
- chore(DB): import pending files
- fix(DB/Zone):improved Nagrand (#4919)
- chore(DB): import pending files
- fix(DB/smart_scripts): Improved Terokkar Forest (#4918)
- chore(DB): import pending files
- fix(DB/Zone): improved Blades Edge (#4917)
- fix(Core/Spell): PLAYER_FIELD_BYTE2_INVISIBILITY_GLOW applies only with invisibility type INVISIBILITY_GENERAL (0) (#7863)

## 2021-09-17
- chore(DB): import pending files
- fix(DB/Gameobject): adds location information to game objects 4/17 (#7852)
- feat(Core/Misc): improve enum flags with type safe operators (#7865)
- chore(DB): import pending files
- fix(DB/Quest): Deliver the Plans to An'telas (#7848)
- fix(Core/Creature): remove combo points on evade (#7861)
- chore(DB): import pending files
- fix(DB/smart_scripts): add Voidwalker summons to Apothecary Falthis (#7847)
- fix(Scripts/BlackwingLair): starting Razorgore the Untamed fight (#7783)

## 2021-09-16
- fix(CI): update mysql path for windows build (#7934)
- chore(DB): import pending files
- fix(DB/smart_scripts): Improve Ironaya & prevent external pull (#7902)
- chore(DB): import pending files
- fix(DB/quest_template): correct text (#7835)
- fix(Core/Spell): Warlock Banish (#7832)
- chore(DB): import pending files
- fix(DB/Creature): remove the cast of Thrash for Tamra Stormpike (#7846)
- chore(DB): import pending files
- fix(Scripts/ToC): remove completely invalid code about removing loot (#7814)
- fix(Creature/Core): Boss phased reset (#7828)
- fix(Scripts/BRD): movement of Burning Spirits during Ambassador Flamelash encounter (#7810)
- chore(DB): import pending files
- fix(DB/Creature): add missing gossip option to obtain Yeh'kinya's Scr… (#7799)
- refactor(Core/Misc): remove duplicate line (#7808)
- fix(Core/Unit): Improve pets behavior (#7836)

## 2021-09-15
- chore(DB): import pending files

## 2021-09-16
- fix(DB/Trainer): correct levelReq for Portal spells Darnassus and Thunder Bluff (#7758)

## 2021-09-15
- refactor(Core): Rename ...Manager to ...Mgr (#6910)

## 2021-09-14
- chore(DB): import pending files

## 2021-09-15
- fix(Core/Spell): Remove ErrorCube visual (#5713)

## 2021-09-14
- chore(DB): import pending files
- feat(Core/debug): Add commad to debug lfg (#6638)
- fix(Core/Misc): bunch of crashfixes (#7307)

## 2021-09-13
- chore(DB): import pending files
- fix(Core/Spells): several improvements to cooldowns (#7559)
- chore(DB): import pending files
- fix(DB/Gameobject): remove Shipment of Iron respawn timer (#7833)
- fix(DB/Gameobject): moves stranglekelps to the shore (#7825)
- fix(DB/gameobject): respawn timers for "Refugee's Quandry" items (#7818)
- fix(DB/Gameobject): adds location information to game objects 3/17 (#7815)
- fix(DB/Creatures): Removed invalid script for Warder Stilgiss. (#7811)
- fix(DB/Quest): Shadoweaver (#7800)
- fix(DB/Spells): define Dust Field as a positive spell (#7798)
- fix(Scripts/BRD): Mobs in Manufactory should attack on Golem Lord Arg… (#7794)
- chore(DB): import pending files
- fix(Scripts/DB): Quest OOX 09 - 17 - 2FE (#7792)
- fix(DB/Creature): remove skinning from rock worm, rock borer and vile larva (#7791)
- fix(DB/creature_template): Befouled Water Elemental (#7777)
- chore(DB): import pending files

## 2021-09-12
- chore(DB): Correct update file (#7841)
- fix(Scripts/Ulduar): Hodir boss fight issue (#5897)
- fix(Core/Item): Luffa removing more than one bleed (#7752)
- chore(DB): import pending files
- feat(Core/Commands): Gear (#7717)

## 2021-09-11
- chore(DB): import pending files
- fix(DB/creature_formations): [BRD] The Throneroom will now aid Thaurissan & Moira (#7770)
- chore(DB): import pending files
- fix(Core/Achievements): new achievement criteria type ACHIEVEMENT_CRITERIA_DATA_TYPE_BG_TEAMS_SCORES (#7756)

## 2021-09-10
- chore(DB): import pending files
- fix(DB/Spell): Dalaran Sewers knockback (#7739)
- chore(Core/Spells): redefine & Define some castFlags (#7724)

## 2021-09-09
- chore(DB): import pending files

## 2021-09-10
- fix(Core/Quests): properly handle quests with QuestType=0. (#7718)

## 2021-09-09
- chore(DB): import pending files
- fix(DB/creature_loot_template): add Azure Whelpling on Blue Dragonspawn (#7772)
- chore(DB): import pending files
- fix(DB/Creature): Mist Howler (#7757)
- fix(Core/Guild): prevent join multiple guilds exploit (#7631)
- fix(Core/Loot): properly handle referenced group loot templates (#7539)
- Revert "fix(Core/Unit): NPC enters into EvadeMode, he loses all his Auras (#6379)" (#7793)

## 2021-09-08
- fix(DB/MySQL): Drop script table name (#7788)
- chore(DB): import pending files
- fix(DB/Gameobjects): add missing posts to Alterac Valley banners in cities (#7755)

## 2021-09-07
- chore(DB): import pending files

## 2021-09-08
- fix(DB/creature_loot): remove Frost Oil drops from 3 NPCs (#7745)

## 2021-09-07
- chore(DB): import pending files
- fix(DB/Reputation): Cenarion Circle (#7732)
- chore(DB): import pending files
- fix(DB/Gameobject): Removes green armor and non-armor drops from armor crate  (#7735)
- chore(Core/Condition): replace assertion with logs preventing server crash (#7730)
- chore(DB): import pending files
- fix(DB/Loot): remove Arena Spoils items from NPC drop tables (#7728)
- fix(Core/Items): properly display item spell charges (#7722)
- chore(DB): import pending files
- fix(DB/GameEvent): correct wrong emissary NPCs spawned during CTA: Warsong Gulch game event (#7719)
- fix(DB/smart_script): increase Rift Spawn health check frequency (#7716)
- fix(DB/quest_template): correct objective tracker (#7711)
- fix(DB/SmartAI): Screecher Spirit despawn target (#7710)
- fix(Core/Spells): implement SPELL_GROUP_SPECIAL_FLAG_SAME_SPELL_CHECK group stack flag (#7709)
-  fix(DB/Quests): Exclamation mark - Elegant Letter (#7707)
- fix(DB/Gameobject): remove duplicate spawn from Razormaw Matriach's Nest (#7706)
- fix(DB/Quests): correct gold reward for some Midsummer quests. (#7703)
- fix(DB/Gameobject): overlapping Water Barrels/Food Crates in Stormwind City (#7705)
- refactor(DBC/Misc): Redefine & Define FactionTemplateFlags (#7697)
- fix(DB): missing special dialogue for High Chief Stillpine during 'The Kessel Run' (#6940)

## 2021-09-06
- chore(DB): import pending files
- fix(DB/Quest): Nessa Shadowsong quest chain (#7694)
- feat(Core/Loot): add configurable option to specify ilv restriction for items below player class in NeedBeforeGreed loot mode in DF (#7701)
- fix(Core/Loot): Quest items should not be lootable/visible if quest objective already fulfilled (#7700)
- chore(DB): import pending files
- fix(DB/Creature): add auras to Jadefire Shadowstalker (#7691)
- fix(Core/Loot): Only Paladins, Warriors and Shamans should be able to roll Need on shields (#7696)
- chore(DB): import pending files
- fix(DB/Creature): add patrolling to Shadowclaw (#7681)

## 2021-09-05
- chore(DB): import pending files

## 2021-09-06
- fix(DB/Pathing): correct path for Isle of Conquest Envoys in Thunder Bluff (#7674)

## 2021-09-05
- chore(DB): import pending files
- fix(DB/Creature): Spawntimer fix GUID 36519 (#7669)
- fix(Core/pathing): incorrect pathing of caster mobs when their casts fail due to LOS (#7472)
- fix(Core/Creatures): Creatures' guardian should not despawn on summon… (#7607)

## 2021-09-04
- chore(DB): import pending files

## 2021-09-05
- fix(DB/Creature): Gordunni/Forest Walker movement (#7527)

## 2021-09-04
- chore(DB): import pending files
- fix(DB/creature_template): adjust movement speed of all vanilla creatures from sniffs up until Naxxramas (#7175)
- chore(DB): import pending files
- fix(DB/translation): add missing Chinese translations (#7670)

## 2021-09-03
- chore(DB): import pending files

## 2021-09-04
- fix(DB/Reputation): Hydraxian Waterlords Reputation (#7668)

## 2021-09-03
- chore(DB): import pending files
- fix(DB_Creature) remove unnecessary NPC Griz Gutshank (#7678)
- chore(DB): import pending files
- fix(DB/updates): Fix merge of PR 7707 (#7708)
- chore(DB): import pending files
-  fix(DB/Creature): add roaming Quel'dorei (#7663)
- fix(Core/Pets): Spells casted by pets and delayed due to LoS or not in range cause should have cast time (#7667)
- chore(DB): import pending files
-  fix(DB/Quest): Fix missing quest Return to Krog (#7626)
- chore(DB): import pending files
- fix(DB/Creature): Gordunni Shamans casting too much healing (#7665)
-  fix (DB/Creature): add roaming Stonewind Trackers (#7661)

## 2021-09-02
- chore(DB): import pending files
- fix(DB/Quest): The Rethban Gauntlet (#7662)
- chore(DB): import pending files
- fix(DB/Creature): fumblub gearwind loot (#7658)
- chore(DB): import pending files
- fix(Core/Movement): properly send movement *ack packets to controlling players. (#7635)
- fix(Core/Items): armor type requirement for needing items in LFG grou… (#7523)

## 2021-09-01
- fix(Core): Possible DF crashfix (#7684)
- chore(DB): import pending files

## 2021-09-02
- fix(DB/Reputation):Brood of Nozdormu reputation (#7622)

## 2021-09-01
- fix(Core): possible crashfix (#7683)
- chore(DB): import pending files
- fix(DB/creature_template): Southshore Guards faction (#7655)
- fix(DB/creature): Cavindra position inside the pool (#7657)
- fix(DB/Loot): Bloated Slippery Eel should be lootable only with quest (#7653)
- fix(Scripts/Spells): Unlit Torches cannot be used too far away from the bonfire (#7644)
- fix(DB/Gameobject): adjust Tin Vein position in Westfall (#7660)
- fix(DB/Quest): decrease respawn items Bloodsail (#7608)
- fix(DB/Gameobject_loot): remove Rethban/Underlight ores from non-zone ores (#7641)
- fix(DB/Creature): Celebras the Redeemed gossip (#7645)
- fix(DB/Creature): add new spawn to Masophet the Black and more (#7640)
- fix(DB/Creature): make Webwood spiders and Githyiss the Vile neutral (#7633)
-  fix(DB/Loot): change blood red key drop rate (#7591)
- fix(DB/GameEvents): add missing pavilion at Tarren Mill (#7646)
- fix(DB/Creature): corrected model of Earthen Ring Guide (#7611)
- fix(DB/Creature): add movements for Spindleweb (#7632)
- fix(DB/Quest): Bitter Rivals (#7625)
- fix(DB/Creature): Lord Xiz (#7620)
- fix(DB/Creature): Zul'arek Hatefowler (#7619)
-  fix(DB/quest_template): correct objective for the Blackfathom Villainy (#7604)
- chore(DB): import pending files
- fix(DB/gameobject_loot): correct Rich Thorium Vein drops (#7603)
- fix(DB/GO): repositioning of a Small Thorium Vein (#7601)
- fix(DB/gameobject_loot): delete incorrect items from Alterac Granite loot (#7597)
- fix(DB/Creature): change respawn timer and add movement to The Husk (#7605)
- fix(DB/gameobject): respawn time for 2 Dark Iron deposits (#7600)
- fix(DB/Creature): Death Speaker Jargba's MC (#7595)
- fix(DB/Creature): decrease respawn time of Garrick Padfoot (#7593)
- fix(DB/quest_template_addon): set honored requirement for "Favor Amongst the Brotherhood" quests (#7582)
- fix(DB/Creatures): Xan'tish Snakes pathing (#7576)
- fix(DB/Loot): correct Darkmoon Faire Prizes loot (#7575)
- fix(DB/creature_formation): Link Den Mother and cubs (#7568)
- chore(DB): import pending files
- fix(DB/Creature): GhostLands Added movement to multiple mobs (#7567)
- chore(DB): import pending files
- fix(DB/Quest): change allowed races for Fire Hardened Mail (#7566)
- chore(DB): import pending files
- fix(DB/Quest): "Gaining Acceptance" Reputation limit (#7563)
- chore(DB): import pending files
- fix(DB/creature): Gish the Unmoving pathing (#7557)
- fix(Core/Movement): set proper flying animations for creatures with INHABIT_GROUND (#7589)
- chore(DB): import pending files
- fix(DB/Quest): starting Blood Elf quests are now only belf (#7556)
- fix(Core/DungeonFinder): misc improvements (#7488)

## 2021-08-31
- chore(DB): import pending files
- fix(DB/Quest): add script to Wait for Sirra to Finish (#7555)
- fix(Core/DungeonFinder): re-queueing being inside dungeon and member leaving DF (#7570)
- fix(Core/Creature): Disable periodic call for assistance on minions from instances (#7650)
- chore(DB): import pending files
- fix(Script/BD): fix skill needed and more for Quest The Spectral Chalice (#7519)
- fix(Core/Cooldowns): SPELLMOD_COOLDOWN should not affect category coo… (#7164)
- chore(DB): import pending files
- fix(DB/loot): remove shadowcat hide from skinning loot (#7441)
- feat(Core/Gameobject): add a range check for gameobjects (#7521)

## 2021-08-30
- feat(Core/Config): add option for LFG expansion (#7256)
- chore(DB): import pending files
- fix(DB/Item): Deleted Manual: Heavy Silk Bandage and Manual: Mageweav… (#7538)
- chore(DB): import pending files
- fix(DB/Quest): restrict multiple quests to blood elves (#7536)
- fix(Core/Maps): fix getting wrong area/zone on spawn (#7590)
- chore(DB): import pending files
- fix(DB/Gameobject): add new spawns to Slagtree's Lost Tools (#7533)
- chore(DB): import pending files
- fix(DB/Creature): add patrol to Swiftmane (#7531)
- fix(Core/Players): healing pet should not reset PvP timer (#7541)
- chore(DB): import pending files
- fix(DB/spell_target_position): Fix teleport locations for Ulduar Teleporter (#7530)

## 2021-08-29
- chore(DB): import pending files
- fix(DB/Creature): Added movement to Arcane Devourer and Mana Shifter (#7526)
- chore(DB): import pending files
- refactor(Script/Command): modify mount & dismount (#7413)

## 2021-08-27
- chore(DB): import pending files
- fix(DB/Creature): Ro'bark Missing Patrol and spawn (#7522)

## 2021-08-26
- chore(DB): import pending files

## 2021-08-27
- fix(DB/Creature): add movement to a few Mummified Headhunters (#7517)

## 2021-08-26
- chore(DB): import pending files
- fix(DB/Creature): Marez Cowl (#7516)
- refactor(Core/Common): code cleanup (part 12) (#7520)
- fix(Core/Spell]: interrupt invisibility auras on cast (#7508)
- chore(DB): import pending files
- fix(DB/quest_template_locale): Quest 6324 Wrong deDE Text (#7506)
- chore(DB): import pending files
- fix(DB/Creature): add movement to the static Vengeful/Ravening Apparitions (#7481)
- fix(Core/Vendors): incorrect check which allowed/disabled alliance players (#7507)
- chore(DB): import pending files
- fix(DB/creature): add movement to static Withered Green Keepers (#7464)
- fix(Core/Chat): print zoneId on GM command used (#7503)
- chore(DB): import pending files
- fix(DB/creature): add movement to static Elder Springpaws (#7460)
- fix(Core/Spells): show Execute/Slam misses/dodges/parries in combat log (#7494)
- chore(DB): import pending files
- fix(DB/creature): add movement to static Tenders/Feral Tenders (#7458)
- fix(Core/Entities): mobs called for help should check if can see and detect the enemy (#7493)
- chore(DB): import pending files

## 2021-08-25
- fix(DB/Creature): prevent scarlet friar floor fall (#7455)

## 2021-08-26
- fix(Core/Movement): properly initialized combat distance for creatures with SAI script (#7437)

## 2021-08-25
- chore(DB): import pending files

## 2021-08-26
- fix(DB/Creature): Duggan Wildhammer (#7449)
- docs(README): clarify the role of Jetbrains in AzerothCore (#7504)

## 2021-08-25
- chore(DB): import pending files
- fix(DB/GO): changes the respawn time of Ammo Crate (#7447)
- fix(Core/Spec): changing spec now removes auras of spells with rank > 1 (#7482)
- chore(DB): import pending files
- fix(DB/Skinning_loot): remove Thick Wolfhide, adjust other drops (#7443)
- fix(Core/Movement): (#7008)
- chore(DB): import pending files
- fix(DB): ore wrong spawn BFD (#7440)
- fix(Core/Maps): display instance warning when entering bound dungeon (#7448)
- chore(DB): import pending files
- fix(Script/Creature): move Shadow Hunter Vosh'gajin script to SAI (#7421)
- chore(DB): import pending files
- fix(Core/Misc): restore playercreateinfo_item item deletion functionality (#7470)

## 2021-08-24
- chore(DB): import pending files

## 2021-08-25
- fix(DB/Creature): add patrol to Murgurgula (#7442)
- fix(Core/Spells): do not remove stances when teleported from Instance/BG (#7469)

## 2021-08-24
- chore(DB): import pending files

## 2021-08-25
- fix(DB/Creature): misc murloc spawns (#7436)
- fix(Scripts/Spell): Volley should trigger pet attack in defensive mode (#7453)

## 2021-08-24
- chore(DB): import pending files
- fix(DB/Creature): add patrol moves to Fingat (#7435)
- fix(Core/Loot): (#7452)
- chore(DB): import pending files
- fix(DB): Removes multiple occurances of double ore spawn (#7430)
- fix(CMake/Build): set default build type to RelWithDebInfo (#7445)
- chore(DB): import pending files
- fix(DB/Object): Reduce dark iron pillow respawn time (#7427)
- fix(Core/Spells): Sacred Cleansing range (#7439)
- chore(DB): import pending files
- fix(DB/Creature): remove skinloot from Spirestone Mystic (#7425)
- fix(Script/Spells): Anti-Magic Zone amount calc (#7438)
- chore(DB): import pending files
- fix(DB/Skinning_loot): remove Chimaera Leather (#7424)
- fix(Core/Movement): Rewritten follow movement generator for pets (#7324)

## 2021-08-23
- chore(DB): import pending files
- fix(DB/creature): respawn timer for Timmy the Cruel (#7419)
- fix(Core/Arenas): correct BG status on Arena leave (#7323)
- chore(DB): import pending files
- fix(DB/Creature): Private Hendel - The Missing Diplomat (#7391)

## 2021-08-22
- fix(Core/Crash): reload page GetSession check to avoid crash (#7451)
- chore(DB): import pending files
- fix(DB/Creature): Gizrul the Slavener (#7414)
- chore(DB): import pending files
- feat(Core/Scripts): new OnBeforeFinalizePlayerWorldSession() hook (#7136)
- chore(DB): import pending files
- fix(DB/Gameobjects): remove classic Naxxramas portal (#7408)
- fix(Core/Unit): adds in formation not attacking when leader killed (#7412)

## 2021-08-21
- chore(DB): import pending files

## 2021-08-22
- fix(DB/Creature): Chillwind Chimaera falling through the floor (#7407)

## 2021-08-21
- fix(Core/Scrips): Kologarn focused eyebeam should target only 1 target (#7405)
- chore(DB): import pending files
- fix(DB/Creature): Fix Void Critters spawn time (#7392)

## 2021-08-20
- chore(DB): import pending files

## 2021-08-21
- fix(DB/Creature): correct script for Quartermaster Zigris (#7404)

## 2021-08-20
- chore(DB): import pending files
- fix(DB/Creature): Fix Quartermaster Zigris loot table (#7403)
- feat(Core/Item): remove item auras after unequipping an item. (#7398)
- [Core/Spells]: Fixed stormstrike and lava lash consuing flurry. (#7397)
- chore(DB): import pending files
- [Core/Spells]: Fix glyph of arcane shot not refunding mana. (#7395)
- fix(Core/Spells): Druid's Enrage not reducing armor (#7394)
- chore(DB): import pending files
- fix(DB/Creature): Mottled Razormaws tweak (#7396)
- chore(DB): import pending files
- fix(DB/Item): Wolfshead Helm not giving Energy when going into cat form (#7393)
- fix(Core/Maps): prevet a crash occurring when shutting the server down. (#7387)

## 2021-08-19
- chore(DB): import pending files
- Create rev_1629122909167793000.sql (#7378)
- chore(DB): import pending files
- fix(DB/Creature): Groomsblood's spawn rate (#7376)
- fix(Core/Spells): add SPELL_ATTR0_CU_NO_INITIAL_THREAT to some spells (#7291)
- fix(Core/Chat): muteTime for players that were muted when offline (#7375)
- feat(Core/Network): Add conf to allow/disallow storing IP address (#7168)

## 2021-08-18
- chore(DB): import pending files
- Fix Tears of the Moon (#7373)
- fix(Core/Movement): Properly updates MOVE_WALK in case of slowing auras. (#7371)
- chore(DB): import pending files
- fix(DB/creature): Remove Gossip from NPC Winkey (7770) (#7367)
- chore(DB): import pending files
- fix(DB/creature): Fix Primitive Owlbeast spawn location, movement (#7348)

## 2021-08-17
- chore(DB): import pending files

## 2021-08-18
- fix(DB/creature): Shift Silvermane Stalker spawn slightly (#7343)

## 2021-08-17
- chore(DB): import pending files

## 2021-08-18
- fix(DB/creature): Add movement to 2 NPC spawns in Azshara (#7336)

## 2021-08-17
- chore(DB): import pending files

## 2021-08-18
- fix(DB/quest): Remove incorrect prereq, premature drop for Gurf's Dignity (#7334)
- fix(Core/Spells): Beacon of Light should not cause combat. (#7321)

## 2021-08-17
- fix(Core/Spells): Always melee attack target when charge is over. (#7316)
- chore(DB): import pending files
- fix(DB/Quest): completable flag of "Gaining Acceptance"  (#7322)

## 2021-08-16
- chore(DB): import pending files

## 2021-08-17
- fix(DB/smart_scripts): Aku'mai Servant spell targeting (#7314)

## 2021-08-16
- fix(Core/Pets): controllable guardians (including pets) should not set the combat with its target when commanded to attack it (#7315)
- chore(DB): import pending files
- fix(DB/Quest): "Sturdy Rope" Quest Item Despawns Any Low Health NPC, Including Dungeon/Raid Bosses (#7304)
- fix(Scripts/BWL): drakes in Blackwing Lair can't attack (#7303)

## 2021-08-15
- fix(Core/Players): remove shapeshift auras on taxi restore (#7292)

## 2021-08-14
- fix(Core/Spells): Master's Call used on rooted pet (#7294)
- fix(Core): do not start combat with pet's current victim on spell hit if it's not in combat (#7293)

## 2021-08-13
- chore(DB): import pending files

## 2021-08-14
- fix(DB/Creature): add movement to various Dunemaul Ogres (#7289)

## 2021-08-13
- fix(Core/Professions): properly unlearn skill dependent spells (#7290)
- fix(Core/DBPlayer): correct support MariaDB 10.6 (#7288)
- chore(DB): import pending files
- fix(DB/creature_template): make various critters/pets unskinnable (#7302)
- fix(Core/Pets): do not summon pet if owner is being teleported (#7275)
- fix(Core/WorldSocket): add missing hook OnLastIpUpdate (#7272)

## 2021-08-12
- chore(DB): import pending files

## 2021-08-13
- fix(DB/Creature): delete skinning table from lvl 1 Serpentbloom Snake (#7271)

## 2021-08-12
- fix(Core/Visibility): notify AI of nearby creatures immediately if forced update object visibility is called (#7274)
- chore(DB): import pending files
- fix(DB/SAI): add missing spells for Wrath Hammer Construct (#7261)
- fix(Core/Auction): server returning wrong items (#7260)

## 2021-08-11
- chore(DB): import pending files
- fix(DB/Creature): reorient Dorin Songblade (#7259)
- fix(Core/Spells): Levitate cannot be casted on mounted targets (#7258)
- chore(DB): import pending files
- fix(DB/Loot): new skinning table for various 10-15 NPCs (#7254)
- fix(Core/Players): don't reset contested PvP timer if teleported between two maps (#7257)

## 2021-08-10
- chore(DB): import pending files

## 2021-08-11
- fix(DB/Creature): remove Fedfennel wandering (#7250)

## 2021-08-10
- fix(Core/Spells): remove hack-fix for sword specialization proc (#7245)
- chore(DB): import pending files
- fix(DB/Loot): make Ranger Jaela and Vile'rel Unskinnable (#7243)
- chore(DB): import pending files
- fix(DB/quest): remove quest Sartheril's Haven from quest chain (#7234)

## 2021-08-09
- fix(CI): docker workflow update (#7262)
- chore(DB): import pending files
- fix(DB/Creatures): Do not check race requirement for mount trainers. (#7233)
- chore(DB): import pending files
- fix(DB/Creature): remove spell Trash from Mosh'Ogg Brute (#7231)
- chore(DB): import pending files
- fix(DB/creature): add patrolling to Anathemus (#7229)
- chore(DB): import pending files
- fix(DB/Loot): remove two lvl 75 plans from Galak Windchaser drops (#7228)
- chore(DB): import pending files
- fix(DB/Loot): delete Pure Un'goro Sample from Firegut Brute drops (#7227)

## 2021-08-08
- chore(DB): import pending files
- fix(DB/creature): change spell Chill to Chilled for Chillwind Ravager (#7225)
- chore(DB): import pending files
- fix(DB/Spells): Shadow Weaving can proc from periodic spells (#7221)
- fix(Core/Spells): Glyph of Freezing Trap Applying Slow Incorrectly (#7184)
- fix(Tools): error when execute vmap4assembler.exe in extractor.bat (#7166)
- fix(Core/Collision): typo in VMap BIH generation. (#7066)
- chore(DB): import pending files
- fix(DB/Reputation): correct Caliph/Wastewander Gadgetzan reps (#7220)
- chore(DB): import pending files
- fix(DB/Creature): Wildthorn Stalker's spawn point (#7210)

## 2021-08-07
- chore(DB): import pending files
- fix(DB/Creature): rare NPC Mongress spawn movement (#7203)
- refactor(Scripts/Northrend): code cleanup (part 11) (#7103)
- chore(DB): import pending files
- fix(Scripts/DB): Ahn'kahet rewrite (#3449)
- fix(Core/Maps): Enabled dead players to be resurrected at the dungeon entrance if cannot enter it due to some reasons (#7236)
- chore(DB): import pending files
- fix(DB/object): skull piles despawning on quest Speaking with Nezzliok (#7202)
- fix(Core/Spells): always select correct item on weapon skill update (#7135)
- chore(DB): import pending files
- fix(DB/Quest): Egg of Onyxia disappears after attacking for Brood of Onyxia (#7200)
- fix(Core/Spells): do not attack focus target while charging (#7235)

## 2021-08-06
- chore(DB): import pending files

## 2021-08-07
- fix(DB/creature): Fix Arei on Ancient Spirit quest (#7198)

## 2021-08-06
- chore(DB): import pending files

## 2021-08-07
- fix(Scripts/Spells): Windfury Weapon should not consume Flurry stacks. (#7151)

## 2021-08-06
- chore(DB): import pending files
- fix(DB/creature): Added movement to Mok'rash (1493) (#7197)
- chore(DB): import pending files
- fix(DB): corrupted and cleansed plants of Felwood (#7196)
- fix(Core/Spells): pets should not dispel beneficials bufs from neutral units not being at war with pet's owner (#7230)
- chore(DB): import pending files

## 2021-08-07
- fix(DB/Loot): delete 'Recipe: Savory Deviate Delight' from RLT 24701 (#7195)

## 2021-08-06
- fix(Core/Quests): SMSG_QUESTUPDATE_COMPLETE on quest completion (#7213)
- chore(DB): import pending files
- fix(Scripts/Items): Goblin Bomb Dispenser (#7190)
- fix(Core/Items): destroy invalid own guild/arena charters (#7211)
- refactor(Scripts/Kalimdor): code cleanup (part 10) (#7065)
- chore(DB): import pending files
- fix(DB/Creature): Added spawn and movement to Lord Maldazzar (#7187)
- chore(DB): import pending files
- fix(DB/Creature): Fixed the spawns of two Heavy War Golem (5854) (#7188)
- chore(DB): import pending files
- Fixes issue #7029 (#7186)
- chore(DB): import pending files
- fix(DB/Creature): spawns of Death Howl (#7170)
- fix(Core/Spells):SPELL_ATTR5_AURA_AFFECTS_NOT_JUST_REQ_EQUIPED_ITEM (#7205)
- chore(DB): import pending files
- fix(DB/Creature): add patrolling to Azurous (10202) (#7189)
- fix(Core/Spells): Killing Spree should not affect invisible units (#7191)
- chore(DB): import pending files
- fix(Scripts/Spell): combustion will now properly go on cooldown when the buff is manually cancelled (#7185)
- chore(DB): import pending files
- fix(DB/Creature): Olm The Wise multiple spawns (#7169)
- fix(Core/SOAP): mem leak and new/free mismatch (#7181)
- fix(Core/Spells): Next melee swing spells are supposed to be queued up even when out of range. (#7180)
- fix(Core/Totems): Totems should not fall to the depth in water. (#7179)

## 2021-08-05
- fix(Core/Spells): Implemented SPELL_ATTR3_NO_PROC_EQUIP_REQUIREMENT. (#7178)
- fix(Core/Spells): Disarmed creatures should no cast spells that requi… (#7171)
- fix(Core/Spells): Forbid using charge if already charging to someone. (#7172)
- fix(Core/Cooldowns): Fixed replacing longer cooldowns by equip cooldown. (#7163)
- fix(Core/Spells): Fixed displaying "That Glyph is already inscribed in your spellbook" when activating the same glyph in different spec. (#7162)
- fix(Core/Items): Removed tradeable flag from items with temp enchants. (#7160)
- chore(DB): import pending files
- fix(DB/Spell): Set proc cooldown of Taste of Blood to 5.5 sec. (#7177)
- fix(DB): Moved Briarthorn node outside of terrain (#7174)
- fix(Core/Spells): Glyphs should send SMSG_LEARNED_SPELL/SMSG_REMOVED_… (#7161)
- fix(Core/Totems): Searing Totem will properly attack neutral targets. (#7157)
- fix(Core/Movement): properly handle UNIT_STATE_CHARGING (#7152)
- chore(DB): import pending files
- fix(DB): add the deleted spawns and fix so they cant be seen (#7173)
- chore(DB): import pending files
- fix(DB/Creature): Add movement to various Ghostclaws/Mistbats (#7150)
- chore(DB): import pending files
- fix(DB/Creature): Added patrolling and fixes to Spiteflayer (#7115)

## 2021-08-04
- chore(DB): import pending files

## 2021-08-05
- fix(DB/Quest): Made Mortality Wanes alliance only so it cant be shared with hordes (#7147)

## 2021-08-04
- chore(DB): import pending files

## 2021-08-05
- fix(DB/Creature): Upgraded Gath'Ilzogg (334) armor to 1.5X value (#7232)

## 2021-08-04
- Core/Spells: Regenerating POWER_HAPPINESS should not generate additional threat. (#7146)
- chore(DB): import pending files
- fix(DB/Spells): Corrected attributes for Intercept. (#7134)
- chore(DB): import pending files
- fix(DB/Creature): Added patrolling to Foulmane (#7141)
- chore(DB): import pending files
- fix(DB/Creature): Fixed spawn point of Scarlet High Clerist (#7140)
- fix(DB/Creature): Added patrolling and new spawns to Omgorn the Lost (#7133)
- fix(Core/Pets): Corrected pet speed catchup system. (#7131)

## 2021-08-03
- chore(DB): import pending files

## 2021-08-04
- fix(DB/creature): Fixed Anvilrage Taskmaster spawns inside Anvilrage Enforcer (#7129)

## 2021-08-03
- chore(DB): import pending files

## 2021-08-04
- fix(DB/Creature): Added patrolling to Dart(14232) (#7132)

## 2021-08-03
- chore(DB): import pending files
- fix(DB/Creature): Fixed speed walking of Grunter (#7128)

## 2021-08-01
- chore(DB): import pending files

## 2021-08-02
- fix(Core/Spells): Master of Elements (#7102)

## 2021-08-01
- fix(Core/Spell): Impelement SPELL_ATTR7_NO_ATTACK_DODGE & SPELL_ATTR7_NO_ATTACK_PARRY & SPELL_ATTR7_NO_ATTACK_MISS (#7099)
- fix(Core): Impelement CREATURE_FLAG_EXTRA_NO_PLAYER_DAMAGE_REQ (#7101)
- feat(Core/Logging): add support fmt::format logging (#6893)

## 2021-07-31
- fix(Core/Spell): Make use of SPELL_ATTR2_NO_SCHOOL_IMMUNITIES (#5880)
- fix(Script/Mandorik): enrage on reset and on subsequent pulls. (#7176)

## 2021-07-30
- fix(Docs/Doxygen): improve some comments (#7118)
- chore(DB): import pending files
- fix(DB/Creature): Added patrolling to Alshirr Banebreath (14340) (#7120)
- chore(DB): import pending files
- fix(DB/Creature): Fixed some coords on the patrolling of Scalding Drake (#7119)
- chore(DB): import pending files
- fix(DB/Creature): Changed skinning loot and movement speed of Deatheye (#7116)
- chore(DB): import pending files
- feat(Core/DB): Add Creature ExperienceModifier  (#7095)

## 2021-07-29
- chore(DB): import pending files

## 2021-07-30
- fix(DB/smart_scripts): Add call for help to Deadwood Den Watcher (#7109)
- fix(DB/GO): Relocate Peacebloom in Elwynn Forest to avoid collision with Darkmoon Faire (#7096)

## 2021-07-29
- chore(DB): import pending files
- fix(DB/Gameobject): Normalise respawn times for Bingles' items (#7098)
- chore(DB): import pending files
- fix(DB/Script): Adds NPC event for The Test of Righteousness 3/3 (#7097)
- chore(DB): import pending files
- fix(DB/Creature): Correct respawn timers for various rare NPCs (#7094)
- fix(DB/Creature: speed_walk of some Blasted Lands creatures (#7088)
- chore(DB): import pending files
- fix(DB): Fixed Southsea Freebooter shoots while running away in fear and while polymorphed (#7019)

## 2021-07-28
- chore(CI): enable macos-11 (#7127)
- chore(DB): import pending files
- fix(DB/gameobject): Peacebloom spawn location (#5837)
- chore(DB): import pending files
- fix(DB/Quest): Add emotes to some silithus quests (#5560)

## 2021-07-27
- fix(Core/Spells): melee spells on sitting targets guaranteed critical strikes (#7085)
- fix(Core): player's fall position on elevators (#7076)
- feat(Cmake/MySQL): add support MariaDB 10.6 (#7113)

## 2021-07-26
- fix(Core/Spells): Far Sight auras are supposed to extend view distance and allows seeing objects from further distance (#7068)

## 2021-07-25
- fix(Core/Spells): Divine Shield should prevent from environmental damage (#7071)
- chore(DB): import pending files
- fix(DB/Waypoints): rare Shadowforge Commander patrolling (#7070)
- fix(Core/Items): items with charges should not remove on item unequip its … (#7064)
- chore(DB): import pending files
- fix(DB/Creature): slowed the movement speed of Deadwind Mauler (#7055)
- feat(CMake): enable optional C++20 support (#7075)

## 2021-07-24
- chore(DB): import pending files

## 2021-07-25
- fix(DB/creature): spawn point of Vale Screecher (#7059)

## 2021-07-24
- chore(Script/Misc): add comments to some scripts (#7011)
- fix(Core/Movement): correct weird pathing by clearing old path (#7034)
- chore(DB): import pending files
- fix(DB/Quest) : Venomhide Eggs quest not bound to prerequisites (#6968)
- chore(DB): import pending files
- fix(DB/Spell): Syndicate Conjuror continues casting "Bright Campfire" when attacked (#7045)

## 2021-07-23
- chore(DB): import pending files

## 2021-07-24
- fix(DB/Creature): Spellmaw not wandering/patrolling (#7040)

## 2021-07-23
- chore(DB): import pending files

## 2021-07-24
- fix(Core/Spell): handle 5,000 Gold with SpellScript (#6996)

## 2021-07-23
- chore(DB): import pending files
- fix(DB/Creature): Remove Fire Immunity from Warlock's Infernal (Inferno Spell)
- chore(DB): import pending files
- fix(DB/Creature): slow down movement speed of Dragonmaw Battlemaster (#7063)
- fix(DB/Creature): add movement to some spawns of Burning Blade Fanatic and Burning Blade Apprentice (#7060)
- fix(DB/GO): respawn timer for Waterlogged Letter (#7057)
- fix(DB/GO): chest pooling to solid chests in Duskwood (#7054)
- fix(DB/GO): chest pooling to battered chests in Jangolade Mine (#7053)
- fix(DB/GO): chest pooling to battered chests in Elwynn Forest (#7052)
- fix(DB/Graveyards): correct ally graveyard in Shadowfang Keep (#7047)
- fix(DB/GameObject): spawn of some nodes so they spawn on ground (#7044)
- fix(DB/Creature): Olm the Wise (rare) missing movement pattern (#7039)
- chore(DB): import pending files
- fix(DB/Creature): skills/movement to Razorbeak Gryphon and Razorbeak Skylord (#7026)
- chore(DB): import pending files
- fix(DB/Creature): increased armor of Pyrewood leatherworker and armorer and their worgen transformation (#7025)
- chore(DB): import pending files
- fix(DB/NPC-Quest): Protecting the Shipment (#7024)
- fix(Core/LootItemStorage): missing write of 'conditionLootId' (#6950)
- chore(DB): import pending files
- fix(Scripts/Item): Gnomish Death Ray. (#7062)
- chore(DB): import pending files
- fix(DB/item): box of supplies not containing coin reward (#7020)
- fix(Core/Pets): spells disappearing while pet being offline (#7046)
- chore(DB): import pending files
- fix(DB/gameObject): book "Old Hatreds - The Colonization of Kalimdor" spawn (#7041)
- fix(Core/Units): charmed creatures do not need to check hostility to attacked creature (#7043)
- chore(DB): import pending files
- fix(DB/Gossip): Fixed "Plundering the Plunderers" has incorrect quest completion text (#7009)

## 2021-07-22
- fix(Scripts/Naxxramas): properly handle Thaddius' polarity stacks (#7030)
- chore(DB): import pending files
- fix(DB/Loot): correct 'Design: Ruby Serpent' loot table (#7006)
- chore(DB): import pending files
- fix(DB/GO): moves herbs outside of buildings (#7001)
- chore(DB): import pending files
- fix(DB/GO): move termite mound to the ground (#7000)
- chore(DB): import pending files
- fix(DB/GO): prevents four objects from spawning in the Stormwind Moon… (#6998)
- chore(DB): import pending files
- fix(DB/GO): prevent herb from spawning in the ground (#6993)
- chore(DB): import pending files
- Fix [Burning Steppes] Thauris Balgarr (rare) has no "Shoot" ability (#6989)
- chore(DB): import pending files
- fix(DB/Gossip): Champion Cyssa Dawnrose gossip in Undercity (#7007)

## 2021-07-21
- chore(DB): import pending files

## 2021-07-22
- fix(DB/SAI): "Attack on the Tower" Quest - Incorrect NPC Spawn Behaviour (#6986)
- refactor(Scripts/Spells): code cleanup (part 9) (#6946)

## 2021-07-21
- chore(Core/Misc): remove toxic language (#6988)
- chore(DB): import pending files
- fix(DB/Locale): better chinese translations by @mpfans (#6969)
- refactor(Scripts/Pet): code cleanup (part 8) (#6928)
- chore(DB): import pending files
- fix(DB/Loot): 'Deadwood Headdress Feather' drop rates (#6951)
- refactor(Scripts/OutdoorPvP): code cleanup (part 7) (#6927)
- chore(DB): import pending files
- fix(Core/Item): prevent possible items dupe (#6943)

## 2021-07-20
- chore(DB): import pending files
- fix(DB/Gameobject): add node pools to solid chests in Winterspring (#6936)
- refactor(Scripts/Events): code cleanup (part 6) (#6924)

## 2021-07-19
- chore(DB): import pending files
- fix(DB/Gameobject): prevent Goldthorn herb from spawning in the air (#6925)
- refactor(Scripts/EasternKingdoms): code cleanup (part 5) - also fix potential crash (#6923)

## 2021-07-18
- refactor(Scripts/Commands): code cleanup (part 4) (#6921)
- chore(DB): import pending files
- fix(DB/Condition): NPC Cowlen Offers Dialogue With Non-Draenei Races (#6920)

## 2021-07-17
- refactor(Core/Player): created update player category (#6872)
- fix(format/clang-format): Acessmodifieroffset & line breaks (#7005)
- fix(Deps/G3DLite): char to LPTSTR (#6997)
- fix(CMake): find std::filesystem across platforms (#6914)
- feat(Deps/g3dlite): replace deprecated is_pod with is_standard_layout (#6894)

## 2021-07-16
- chore(DB): import pending files

## 2021-07-17
- fix(DB/GO): move inaccessible Steelbloom herbs (#6908)

## 2021-07-16
- feat(Deps/ACE): remove ACE library (part 2/2) (#5679)
- feat(Deps/ACE): remove ACE library (part 1/2) (#6980)
- chore(DB): import pending files
- fix(DB/GO): moved Groomsblood down to the ground (#6905)
- fix(Core/SpellAuras): prevent crash in Aura::GetType() (#6922)
- feat(Core): replace ACE network with Boost.Asio (#6574)
- fix(Core): revert Boost minimum version change (#6975)
- chore(DB): import pending files
- fix(DB): ore node now spawns above ground (#6876)

## 2021-07-15
- chore(DB): import pending files

## 2021-07-16
- BREAKING CHANGE(Deps/Boost): Set 1.74 as minimum version (#6874)

## 2021-07-15
- chore(DB): import pending files
- fix(DB/Creature): various static Vilebranch Trolls (#6904)
- chore(DB): import pending files
- fix(DB/Quest): Quest "Devourer of Souls" Has Incorrect Qu… (#6911)
- feat(CMake): delete EXTRA_LOGS (#6897)

## 2021-07-14
- chore(DB): import pending files
- fix(DB/Creature): static Ironjaw Basilisks (#6903)
- feat(Core): added clang-format (#6848)
- fix(Core): -Wambiguous-reversed-operator warning (#6864)

## 2021-07-13
- chore(Core/Database): add info about errors (#6895)
- chore(DB): import pending files

## 2021-07-14
- fix(DB/Loot): remove Arathi PVP food/bandages from open world NPCs (#6891)

## 2021-07-13
- chore(DB): import pending files
- fix(DB/Creature): correct Wrathscale Siren spawn location (#6871)
- fix(Core/Unit): -Wdeprecated-enum-enum-conversion warning (#6868)
- fix(Scripts/Ulduar): Mimiron Summon Mine (#6833)

## 2021-07-12
- chore(DB): import pending files
- fix(DB/Loot): remove underlevel RLT 24074 from Rocs/Hyenas (#6866)
- chore(DB): import pending files

## 2021-07-11
- fix(Scripts/DB/Quest): improved No Fly Zone (#6850)

## 2021-07-12
- fix(Core/WheatyExceptionReport): for c++20 (#6875)

## 2021-07-11
- fix(Core/Common): -Wdeprecated-enum-float-conversion warning (#6870)
- chore(DB): import pending files
- fix(DB/Creature): various static NPCs in Darkshore/Tanaris (#6869)
- feat(Deps/Fmt): update to 8.0.1 (#6859)

## 2021-07-10
- feat(CI): show warnings in macOS run (#6861)
- chore(DB): import pending files
- fix(DB): rewrite Supplies to Auberdine quest (#6846)
- fix(Core/World): -Wrange-loop-analysis warning (#6853)
- fix(Core/ObjectGuid): prevent creating copies when looping objects (#6852)
- chore(DB): import pending files
- fix(DB): minor issues with Spellshock Leggings (#6834)
- refactor(Core/Player): extract methods based on existing categories (#6838)
- chore(DB): import pending files
- fix(DB/creature_template): correct faction and speed_run for Masat T'andr and Broken Exiles (#6809)
- fix(CI): docker workflow update (#6860)

## 2021-07-09
- fix(CI): docker workflow update (#6851)

## 2021-07-10
- fix(Core/PetHandler): prevent crash (#6805)

## 2021-07-09
- fix(Core/Loot): allow master looter to see and distribute all quest items (#6417)
- chore(DB): import pending files

## 2021-07-10
- fix(DB/quest_template): correct objective for The Sacred Flame 1/3 (#6796)

## 2021-07-09
- chore(Core/Player): add error log when previously ASSERT (#6802)
- chore(DB): import pending files

## 2021-07-10
- fix(DB/GO): raise group of ore nodes to stop underground spawning (#6795)

## 2021-07-09
- refactor(Core): replace boost::filesystem with std::filesystem (#6800)
- chore(DB): import pending files
- fix(DB/Creature): correct Mezzir the Howler movement (#6794)
- chore(DB): import pending files
- fix(DB/Loot): correct Venom Web Fang drops (#6793)
- chore(DB): import pending files
- feat(Scripts/Commands): show SpellSchoolImmuneMask in .npc info (#6788)
- chore(DB): import pending files
- fix(DB/Spell): Deep Freeze (#6787)
- chore(DB): import pending files
- fix(DB/pool): remove redundant Meshlok creature pool (#6779)

## 2021-07-08
- fix: forgot to push addition to previous commit (#6836)
- refactor(Core/Player): extract KillRewarder, TradeData and PlayerTaxi (#6804)
- fix(Core/Instance): Grauf is spawned in the floor (#6776)
- chore(DB): import pending files
- feat(Core): port aggro distance from vMaNGOS (#6214)
- chore(DB): import pending files
- fix(DB/character_skills): Fix Riding Skill messed up by PR #6015 (#6768)
- chore(DB): import pending files
- fix(DB/Gossip): Arcanist Ithanas gossip (#6757)
- fix(Core/Player): Paladin's Seal of Righteousness (#6727)
- chore(DB): import pending files
- fix(DB/Spell): Giant Softshell drops (#6684)
- chore(DB): import pending files
- fix(DB/smart_scripts): rewrite Lard Lost His Lunch quest (#6801)

## 2021-07-07
- chore(DB): import pending files
- fix(DB/Creature): InhabitType of ICC flying Creatures (#6661)
- feat(Core/Battleground): Added new config variables to battleground b… (#6432)
- fix(Core): prevent crash (#6677)
- chore(DB): import pending files
- fix(DB/smart_scripts): rewrite Stranglethorn Fever quest (#6777)

## 2021-07-08
- fix(DB/Creature): stop two NPCs spawning inside trees (#6772)
- fix(DB/Creature): correct Glasshide Gazer position and movement (#6771)
- fix(DB/Loot): correct various bag item lists (#6770)

## 2021-07-07
- chore(Core/Misc): add LOG_ERROR where there was commented ASSERT (#6761)
- fix(DB/SmartAI): prevent Vylestem Vine to be used multiple times (#6760)
- fix(DB/creaure_template): Wretched Captive orientation (#6759)

## 2021-07-08
- fix(DB/Loot): remove Dark Iron Ale Mug from Whit Wantmal (#6750)
- fix(DB/Creature): add gossip to Maggran Earthbinder (#6748)
- fix(DB/Creature): correct Dread Swoop spawn point (#6747)

## 2021-07-07
- fix(DB/smart_scripts): add roleplay for the quest Set Them blaze! (#6730)

## 2021-07-08
- fix(DB/Quest): Remove respawn timers from "Broken Alliances" pillars (#6726)

## 2021-07-07
- fix(DB/Quests): Report to Helgrum prerequisite (#6725)

## 2021-07-08
- fix(DB/Quest): add Alchemy requirement to "Badlands Reagent Run II" (H) (#6724)

## 2021-07-07
- fix(DB/creature_template_locale): Tannaria deDE Title (#6717)
- fix(DB/smart_scripts): Add roleplay for the quest The Divination (#6714)
- chore(DB): import pending files

## 2021-07-08
- fix(DB/Creature): add correct buff to Amani Berserkers (#6713)

## 2021-07-07
- chore(DB): import pending files
- fix(DB/gameobject): reposition underground ore nodes in EPL (#6712)
- chore(DB): import pending files
- fix(DB/Loot): correct Stonemason's Cloak drops (#6711)
- chore(DB): import pending files
- fix(DB/Loot): correct Blackwater Cutlass drops (#6709)
- chore(DB): import pending files
- fix(DB/Creatures) Fix more static rare spawns, 40-49 bracket (#6693)
- fix(CI): docker workflow update step if (#6716)
- fix(Core/Conf): worldserver.conf.dist duplicate entry (#6705)
- chore(DB): import pending files
- fix(DB/Loot): Limit maximum Darkclaw Lobster catches (#6687)
- chore(DB): import pending files
- fix(DB/Loot): Revenge of Gann (Part 1) Quest Drop Rate (#6665)
- chore(DB): import pending files
- fix(DB/Loot): Green Carapace Shield Incorrectly Dropping From Various Mobs (#6682)
- docs(bug_report): Clean up (#6758)

## 2021-07-06
- chore(DB): import pending files
- fix(DB): Improve quest Kroshius' Infernal Core (#6683)
- chore(DB): import pending files
- fix(DB/Quest): Rigglefuzz in Badlands bugged question mark for engineers (#6680)
- chore(DB): import pending files
- fix(DB/Creature): correct Siege Golem speed (#6667)
- fix(Scripts/Spell): Victory Rush spammable ability (#6662)
- chore(DB): import pending files
- fix(DB/Creature): motionless Silithid Harvester (#6668)
- fix(Core/Player): learnSkillRewardedSpells AFERT ALL skills have been loaded (#6676)
- chore(DB): import pending files
- fix(Script/Spell): update character_skill to have riding max 300 (#6671)
- chore(DB): import pending files
- fix(DB/Creature): motionless Azzere the Skyblade (#6655)

## 2021-07-05
- chore(DB): import pending files
- fix(DB/SAI): Sironas despawn time increased (#6632)
- chore(DB): import pending files
- fix(DB/Creature): Bellygrub not wandering (#6619)
- chore(DB): import pending files

## 2021-07-06
- fix(DB/Loot): remove underlevelled RLT 24078 from various NPCs (#6610)

## 2021-07-05
- docs(ISSUE_TEMPLATE): allow blank reports
- chore(DB): import pending files

## 2021-07-06
- fix(DB:Creature) Removes Spider Meat from Deviate Creepers/Lurkers (#6608)

## 2021-07-05
- chore(DB): import pending files
- fix(DB/Graveyard): move Ally GY when dying in Thunder Bluff (#6595)
- docs(issue_template): migrate from .md to .yml format (#6621)
- chore(DB): import pending files
- fix(DB/Quest): Remove deprecated Arathi Basin quests (#6594)
- chore(DB): import pending files
- docs(Changelog): SkillLineAbility changes (#6613)
- chore(DB): import pending files
- fix(DB/Creature): remove Civilian flag from Nazzivus Summoners (#6590)
- chore(DB): import pending files
- fix(DB/Loot): Belamoore's Rearch Journal drop requirement (#6589)

## 2021-07-04
- chore(DB): import pending files

## 2021-07-05
- fix(Core/Script): Molten Core: Gehennas (#5680)

## 2021-07-04
- chore(DB): import pending files
- fix(DB/Quest): Ending the Bloodcurse (#6477)
- chore(DB): import pending files

## 2021-07-05
- fix(DB/Creature): Fix various motionless rare spawns - 30-39 bracket (#6628)

## 2021-07-04
- fix(Core/Script): Molten Core: Lucifron (#5655)
- chore(DB): import pending files
- fix(DB/Creature): Corrects Gnarl Leafbrother movement speed (#6586)

## 2021-07-03
- chore(DB): import pending files
- fix(DB/creature_summon_groups): Adjust creature despawn in BFD / Fire Of Aku'Mai (#6583)
- chore(DB): import pending files
- fix(DB): pending locales for Gems esES/esMX (#6581)
- chore(DB): import pending files

## 2021-07-02
- fix(DB): missing translations for The Battle for Undercity (#6582)
- chore(DB): import pending files
- fix(DB/item_template): Flag all "Shredder Operating Manual" pages for HORDE_ONLY (#6579)
- chore(DB): import pending files
- fix(DB/gameobject_loot_template): Indurium Mineral Vein should contain always ores (#6569)
- chore(DB): import pending files
- fix(DB/creature): rotate Desert Agitator to face the guard when talking (#6577)
- chore(DB): import pending files
- fix(DB/creature): Gray Bear no longer spawned underground  (#6571)
- chore(DB): import pending files
- fix(DB/Quest): prerequisites for Convert Ops quests (#6556)

## 2021-07-01
- chore(DB): import pending files
- fix(SAI): Disciple of Naralex (#6656)
- chore(DB): import pending files
- fix(DB): esMX entries for item_set_names_locale (#6530)

## 2021-06-30
- chore(DB): import pending files

## 2021-07-01
- fix(DB/creature): Cranky Benj pathing (#6536)

## 2021-06-30
- chore(DB): import pending files
- feat: reorder character selection screen (#6555)
- chore(DB): import pending files
- fix(DB/creature): Fix Sunscale Lashtails movement (#5963)
- chore(DB): import pending files

## 2021-06-29
- feat(DB/acore_string) Spanish translations of acore_string (#6529)
- chore(DB): import pending files

## 2021-06-30
- docs(Changelog): add changelog for new features (#6518)

## 2021-06-29
- chore(DB): import pending files
- fix(DB/Locale): Chinese translations (#6473)
- chore(DB): import pending files
- fix(DB/loot): Adjust Nightbane Dark Runner loot (#5966)
- fix(Core/DBC): hackfix to prevent skills fuckup (#6631)
- fix(Core/CharacterDatabase): bad query in prepared statement (#6630)

## 2021-06-28
- refactor(GameObject): Update some methods to UpperCamelCase (#6487)
- feat(CI): add mod-azerothshard to the CI (#6629)
- fix(Core): fix ip bans (#6519)
- chore(DB): import pending files
- fix(Core/ScriptsMgr): correct hooks name (#6434)
- chore(DB): import pending files
- docs(changelog): add methods rename to the changelog (#6615)
- chore(DB): import pending files
- fix(DB/Creature): Gordunni Warlock SmartAI (#6515)
- fix(Core/Movement): Fixed never ending spline movement if fallen under map. (#6485)

## 2021-06-27
- chore(DB): import pending files
- fix(SmartAI): Blacksilt Seer missing SmartAI (#6482)
- feat(Core/DBUpdater): implement db auto update (#6576)
- fix(Core/Player): Learn runeforging & lockpicking skills (#6612)
- refactor(Collision): update some methods to UpperCamelCase (#6486)
- chore(DB): import pending files
- fix(DB): The Demon seed conditions (#6483)
- chore(DB): import pending files
- fix(DB/Spell): Correct proc for Deep Freeze Immunity State (71761) (#6598)
- chore(DB): import pending files
- fix(DB): Webbed Creature missing flags (#6481)
- chore(DB): import pending files
- fix(DB/loot): remove Green Linen Shirt from Skeletal Warrior (#6444)

## 2021-06-26
- chore(DB): import pending files

## 2021-06-27
- fix(Scripts/Quest): reward money amount of `Apprentice Angler` (#6431)

## 2021-06-26
- chore(DB): import pending files

## 2021-06-27
- fix(SmartAI): Axxarien Hellcaller SmartAI (#6480)

## 2021-06-26
- chore(DB): import pending files
- fix(DB/quest_poi): Waters of Xavian (1944) and Laughing Sisters (1945) (#6459)
- docs: replacing Bountysource with PayPal donation (#6592)
- fix(Core): Undefined symbols ArenaSpectator::HandleSpectatorSpectateC… (#6580)
- feat(Core/Arena): support cross-faction teams (#6448)
- chore(DB): import pending files
- fix(DB/Creature): relocate stuck Wild Gryphon (#6447)
- feat(CI): add modules (#6584)
- fix(Scripts/Naxxramas): crashfix. (#6445)
- chore(DB): import pending files
- fix(DB/creature): corrected Magister Duskwither position (#6433)
- chore(DB): import pending files
- fix(DB/creature_template): add Fire immunity to Brimgore (#6430)

## 2021-06-25
- chore(DB): import pending files

## 2021-06-26
- fix(DB/spell): Adjust Intercept and Charge attrs (#6421)

## 2021-06-25
- chore(DB): import pending files
- fix(DB/gameobject): various overlapping Water Barrels/Food Crates (#6415)
- chore(DB): import pending files
- fix(DB/Vendor): remove Perfume & Cologne (#6397)
- chore(DB): import pending files
- fix(DB/Creature): Correct Baron Charr's speed (#6413)
- chore(DB): import pending files
- fix(DB/SAI): Remove Claw (cat ability and sound) from Non-Cat creatures (#6407)
- chore(DB): import pending files
- fix(DB/Creature): Wretched Captive SAI (#6395)
- chore(Core/Spell): SpellId's should always be uint32 (#6466)
- feat(build): Set correct year in VER_LEGALCOPYRIGHT_STR (#6488)
- fix(Core/Player): Correct SPEC_MASK for addSpell() (#6561)

## 2021-06-24
- chore(DB): import pending files
- fix(DB): Outrunner Alarion gossip menu (#6390)

## 2021-06-25
- refactor(Core/Misc): add braces and impove codestyle (#6402)

## 2021-06-24
- chore: Minor typo fix in worldserver.conf.dist (#6508)
- chore(DB): import pending files
- fix:(DB/Quest): QuestType in NPC Chronos (#6387)
- chore(DB): import pending files
- fix(DB/Quest): QuestType in Spawn of Jubjub (#6386)

## 2021-06-23
- chore(DB): import pending files

## 2021-06-24
- fix(DB): Arcanist Helion missing gossip menu text (#6381)

## 2021-06-23
- chore(DB): import pending files
- feature(Core/Spells): Allow to learn all spells for characters on cre… (#6464)
- feat(Core/Misc): Add .Size() to TypeUnorderedMapContainer for stats/debugging (#6080)
- fix(CMake/Bash): -DSCRIPTS cmake param (#6522)
- fix(Core/Unit): NPC enters into EvadeMode, he loses all his Auras (#6379)
- chore(DB): import pending files
- fix(DB/loot): Reduce Plans: Copper Chain Vest drop rates in Siltfins+Mistbats (#6376)
- fix(Core/Mail): cleanup pending auction sale mail (#6022)

## 2021-06-22
- chore(DB): import pending files

## 2021-06-23
- fix(DB): Improve NPC Malyfous Darkhammer behaviour (#6308)
- refactor(Core/Common): alphabetical sorting inlcudes (#6282)
- fix(DB/Quest): The Deathstalkers (#5854)
- feat(Core/Scripts): split the huge scriptloader into smaller pieces (#5346)

## 2021-06-22
- fix(Core/Build): correct macos build (#6492)
- feat(Core/Database): port TrinityCore database API (#5611)
- chore(DB): import pending files
- fix(Core/BattlegroundAB): add missing Victory near sound (#5556)

## 2021-06-21
- fix(DB/ItemLoot): Killed MYSQL error introduced in 289f140ab. (#6446)
- fix(DB/Auth): Collation error (#6465)
- chore(DB): import pending files
- fix(Core/Player): Use SkillLineAbility.dbc to determine player initia… (#6015)
- fix(Core): macOS build (#6479)
- chore(Common/Misc): Replace old macros with modern C++ attributes (#6462)
- chore(Core/Logging): replace most server loggers (#5726)

## 2021-06-20
- chore(DB): import pending files

## 2021-06-21
- fix(Scripts): Neeru Fireblade conditions (#6372)

## 2021-06-20
- fix(Core): check spell info and prevent crash (#6454)
- chore(DB): import pending files
- fix(DB): gossip locale for every city guard esES/esMX (#6377)
- chore(DB): import pending files
- fix(DB/loot): normalise Tunnel Rat Ear drop rates (#6375)
- feat(Core): improve check of set variables (#6336)
- chore(DB): import pending files
- fix(CI): workflow updates (#6439)
- fix(Scripts): Witch Doctor Mau'ari conditions (#6371)
- chore(Core/SmartScript): Fix typo (#6355)

## 2021-06-19
- fix(Scripts/ToC): solved issue twin valkyr's ball (#6352)
- chore(DB): import pending files
- fix(DB/Creature): Emblem Quartermaster locales (#6340)
- chore(DB): import pending files

## 2021-06-20
- fix(DB/loot): delete overlevelled items from NPC RLTs (#6335)

## 2021-06-19
- chore(DB): import pending files
- fix(DB/loot): remove Empty Tainted/Cursed Jars from various NPCs (#6334)
- fix(CI): limit concurrency group to PR's (#6419)
- chore(DB): import pending files
- fix(DB/creature): Beaten Corpse faction and flags (#6319)
- chore(Core/Gossip): delete old gossips api (#5414)
- refactor(Build/CMake): Only complain when BOOST_ROOT was not found (#6418)
- refactor(Core): code cleanup (part 3) (#6380)

## 2021-06-18
- chore(DB): import pending files
- fix(DB): chinese translations (#6373)
- fix(DB/spell_dbc): Imp's Phase Shift (#6408)
- feat(Core/Commands): GM command to display strings (#6268)
- feat(Core): add argument to .character rename to add name to reserved_name (#6163)
- fix(CI): typo in docker_build (#6364)
- fix(DB/gameobject): fix overlapping gameobjects (#6363)

## 2021-06-19
- fix(DB/Creature): Pacifies Theramore Combat Dummies (#6351)

## 2021-06-18
- fix(Scripts): Victory rush killing blow (#6349)
- fix(Core/Loot): Fixed loading conditioned item loot. (#6337)
- chore(DB): import pending files
- fix(CORE/Quests): Quest dialog fails to close with follow-up quest (#6309)
- fix(DB/Quest): Disabled regen health for Sorlof. (#6307)
- fix(DB/quest): recover the cargo! objects not despawning (#6304)
- fix(Core/DB): Brewspewer hardcoded conditions (#6301)
- fix(DB/creature_template): Adjust Hematos speed walk (#6300)
- fix(DB/creature_model_info): prevent NPC George Candarte incorrect display (#6299)
- fix(DB/creature_template): Uruson speed walk (#6290) (#6291)
- fix(Core/SmartScripts):SMART_TARGET_CREATURE/GAMEOBJECT_GUID (#6298)
- chore(DB): import pending files
- fix(DB/creature_loot_template,conditions): Cracked Silithid Carapace (5877) (#6284)
- chore(DB): import pending files
- fix(DB): Scholomance Hall of secrets issues (#5238)
- chore(DB): import pending files
- fix(DB/loot): Adjust Spellshock Leggings drops (#6288)
- chore(DB): import pending files
- fix(DB/loot): Prospecting Thorium doesn't always yield a gem (#6198)
- chore(DB): import pending files
- fix(DB/creature_template): mass update vanilla creatures damages (#4927)

## 2021-06-17
- chore(DB): import pending files
- feat(CI): move modules build into separate workflow (#6277)

## 2021-06-18
- feat(Common/IPLocation): replace ip2nation by ip2location (#5653)

## 2021-06-17
- chore(DB): import pending files
- fix(DB/gameobject): Unreachable Copper vein (#6274)
- feat(Core): deprecate clang-9 and older (#6406)
- chore(DB): import pending files
- fix(DB/loot): Remove Mana Agate drop from Vultros (#6273)
- feat(Core/Logging): Changed format of packet log file from .bin to .pkt (#5949)
- chore(DB): import pending files
- fix(DB/Creature): Great Goretusk spawned inside a tree in Redridge Mountains (#6271)
- chore(DB): import pending files
- fix(DB): revert bad sql imports (#6394)

## 2021-06-16
- fix(bash): restored import sql script

## 2021-06-17
- chore(DB): import pending files
- fix(DB/creature_loot_template): Increase drop chance for Diabolical Plans (#6297)

## 2021-06-16
- refactor(Core): code cleanup (part 2) (#6374)
- chore(DB): import pending files
- fix(DB/SAI): Remove despawn event from Lorgus Jett (#6289)
- docs(SECURITY): add support for clang-12
- refactor(Core): code cleanup (part 1) (#6361)
- chore(DB): import pending files
- fix(DB/waypoint_data): add waypoint_data, update creature and creature_addon (#6262)
- chore(Core): typo fixes (#6272)

## 2021-06-15
- chore(DB): import pending files
- feat(Core/BGQueue): rework queue announce (#6114)
- fix(Core/Packets): sending item's random property in a few packets (#6193)
- fix(Script/URBS): Potential crash in Dragonspire Room (#6330)
- chore(deno/changelog): fix commit link
- chore(DB): import pending files
- fix(bash): pending sql script path
- feat(doc): changelog system (#6350)

## 2021-06-14
- chore(DB): import pending SQL update file
- fix(DB/Creature): Firemane Flamecaller Spawning Inside Wall (#6260)
- feat(CI): limit workflow concurrency (#6332)
- chore(DB): import pending SQL update file
- fix(DB/loot): delete more overlevelled items from world NPCs (#6245)

## 2021-06-13
- fix(Core/Player): Players are allowed to continue melee attacking on … (#6267)
- chore(DB): import pending SQL update file
- fix(DB/Skinning): Firemane mobs not consistently dropping leather (#6261)
-  fix(Core/Config): typo in worldserver.conf.dist (#6258)
- chore(DB): import pending SQL update file
- fix(DB/Creature): Silverpine Forest - Moonrage Bloodhowler Bad Spawn Placement/Missing Movement (#6233)
- chore(DB): import pending SQL update file
- fix(DB/Creature): Emeraldon Mobs Missing Patrol Patterns (#6231)
- chore(DB): import pending SQL update file
- fix(DB/graveyard): Fix Hearthglen Spirit Healer (#6206)
- feat(Core): improved some hooks (#6302)
- chore(DB): import pending SQL update file
- fix(DB/loot): Unholy Alliance available without prerequisites (#6202)

## 2021-06-12
- fix(Core/Unit): dodges, parries and critters not increasing weapon skills (#5895)
- chore(DB): import pending SQL update file
- fix(DB/spell): Feral Spells are not gated at trainers (#6183)
- fix(Core/Spells): category cooldowns (#6191)
- chore(DB): import pending SQL update file
- fix(DB/Creature): Some Nethergarde Foremans missing patrol pattern (#6225)
- chore(DB): import pending SQL update file
- fix(DB/smart_scripts): The Plains Vision speed (#6213)

## 2021-06-11
- chore(DB): import pending SQL update file
- fix(DB/creature): Fix some raptors not moving (#6212)
- chore(DB): import pending SQL update file
- fix(DB/gameobject): Add missing Azshara fish nodes (#6210)
- chore(DB): import pending SQL update file
- fix(DB/events): Fishing Extravaganza wrong start time (#6201)
- fix(Core/Spells): Updates autoshoot spell target in case of clientside target change. (#6257)
- chore(DB): import pending SQL update file
- fix(DB): Add missing script for The Binding quest (#6200)
- chore(DB): import pending SQL update file
- fix(DB/loot): Remove Webbed Creature drops (#6199)

## 2021-06-10
- chore(DB): import pending SQL update file
- fix(DB/gameobject): Adjust Barrel location (#6197)
- chore(DB): import pending SQL update file
- fix(DB/spell): Fix Hex of Ravenclaw Removal spell (#6196)
- fix(Core/Spells): Spells and auras activated by item use should not be removed on unequip. (#6255)
- chore(DB): import pending SQL update file
- fix(DB/creature): Greymist murlocs movement (#6192)

## 2021-06-09
- feat(CI): add clang12 to core_build matrix (#5681)
- chore(DB): import pending SQL update file
- fix(DB/waypoint_data): Aku'mai pathing (#6185)
- fix(Scripts/Spells): Seal of Command cannot be casted on dead targets (#6186)
- fix(Core/Pets): Pets should update speed out of combat only if are following their owner. (#6207)
- chore(DB): import pending SQL update file
- fix(DB/creature): Son of Arugal movement (#6184)
- chore(DB): import pending SQL update file
-  fix(DB/loot): Dinosaur Bones (#6182)

## 2021-06-08
- feat(CI): run pr builds on label (#6241)
- chore(DB): import pending SQL update file
- fix(DB/loot): Highland Fleshstalker drops (#6180)
- chore(DB): import pending SQL update file
- fix(Core/Loot): properly save and load from DB loot from items (#6151)
- chore(DB): import pending SQL update file
- fix(DB/loot): Removes Scarlet Set items from rand_loot_temp tables (#6102)

## 2021-06-06
- chore(DB): import pending SQL update file

## 2021-06-07
- fix(DB/loot): Dalaran Miner and Brewmaster drops (#6178)

## 2021-06-06
- chore(DB): import pending SQL update file
- fix(DB/loot): Slimy, Oozing, Scum Covered Bag loot (#6173)

## 2021-06-05
- chore(DB): import pending SQL update file

## 2021-06-06
- fix(DB/creature): Kurdros and Granistad movement (#6177)

## 2021-06-05
- fix(Core/Spells): disable fishing if not in LOS within boober destination. (#6138)
- chore(DB): import pending SQL update file
- fix(DB): Adjust Advisor Sorrelon gossip conditions (#6160)
- fix(Core/Spells): Shadowmeld targets only players. (#6136)
- chore(DB): import pending SQL update file
- fix(DB): chinese translations (#6148)
- fix(Core/Spells): Changing druid forms should not remove items auras triggered on use. (#6135)
- fix(CI): update semicolon check (#6228)

## 2021-06-04
- chore(DB): import pending SQL update file

## 2021-06-05
- fix(Scripts/DB): Improve Demon Portals and convert to SAI (#6140)

## 2021-06-04
- feat(Modules): load modules configs before Log initialization (#6104)
- chore(DB): import pending SQL update file

## 2021-06-05
- fix(DB/loot): Removes various overlevelled gear drops (#6103)

## 2021-06-04
- feat(Core/RASession): switch to boost api (#6172)
- chore(Core/MIsc): added few helpers for chat commands (#6175)

## 2021-06-03
- fix(Core/Spells): On autoshot interrupt send proper packet to cancel autoshot clientside. (#6169)
- chore(DB): import pending SQL update file
- fix(DB/spawn) Remove Earthroot node from Menethil Harbor (#6125)
- fix(Core/Spell): Remove delay from Flare activation (#5933)
- feat(Core/Spell): AssertSpellInfo (#6115)
- refactor(Core/Grids): Ported cmangos/mangos-wotlk@ea99457 (#6113)

## 2021-06-02
- chore(DB): import pending SQL update file
- fix(DB/loot): Fix drops related to Root Samples Q (#6088)

## 2021-06-03
- feat(Core/Thread): move Processpriority to separated files (#5638)

## 2021-06-02
- chore(DB): import pending SQL update file
- fix(DB/creature_template): set Gatekeeper Rageroar to faction Timbermaw Hold (#6086)
- chore(DB): import pending SQL update file

## 2021-06-03
- fix(DB/loot): Remove overlevelled items (#6076)

## 2021-06-02
- chore(DB): import pending SQL update file
- fix(DB/loot): Noblegarden loot (#6074)
- chore(DB): import pending SQL update file
- fix(DB/loot): Clean up refs to ref table 24060 (#6072)
- chore(DB): import pending SQL update file
- fix(DB/SAI): Swap scripts called on gossip for NPC Krasus (#6071)
- chore(DB): import pending SQL update file
- fix(DB/SAI): Improve Lunaclaw/Moonkin Stone behaviour (#6061)
- chore(DB): import pending SQL update file
- fix(DB/Creature/SAI): Disciple of Naralex (#6059)
- chore(DB): import pending SQL update file
- refactor(SmartAI): move C++ script to DB (SAI) (#6067)
- chore(DB): import pending SQL update file
- fix(DB/creature_loot_template): Rotting Slime (#6050)
- fix(Scripts/HoL): adjust IsEncounterInProgress() (#6108)
- fix(Scripts/VoA): Toravon Orbs bug (#6082)
- chore(DB): import pending SQL update file
- fix(DB/gameobject): Fathom Stone GO respawn (#6049)
- chore(DB): import pending SQL update file
- fix(DB/Spell): Furious Howl & Call of the Wild (#6047)
- chore(DB): import pending SQL update file
- fix(DB/SAI/Quest): Curing the Sick (#6041)

## 2021-06-01
- chore(Core/AchievementMgr): add GetAchievement helper (#6121)
- feat(Core/Apps): add support dynamic lib for EnumUtils (#6120)
- chore(Core/Common): delete macro UNUSED (#6119)
- chore(DB): import pending SQL update file
- fix(DB/Quest POI): Going, Going, Guano! (#6039)
- fix(Core/Shared/DB): recommit transactions on dead-lock error (#6069)
- fix(Core/Spell): Apply AURA_STATE_FAERIE_FIRE to Faerie Fire (#6105)
- chore(DB): import pending SQL update file
- fix(DB/smart_scripts): play small event on noble brew part 2 completion (#6038)
- feat(Core/Script): Allow spell script ValidateSpellInfo to work with any container type (#6078)
- chore(DB): import pending SQL update file
- fix(DB/gossip_menu_option): Remove Chromie duplicate gossip options (#6025)
- fix(Scripts/ScarletMonastery): Whitemane spell cast (#6073)
- chore(DB): import pending SQL update file
- fix(DB/Zone):improved Zangamarsh (#4920)

## 2021-05-31
- chore(DB): import pending SQL update file
- fix(DB/Creature): Spiteful Apparition (#6014)
- fix(Bash/Ubuntu): allow Boost install on minimal ubuntu 20.04 installs (#6037)
- chore(DB): import pending SQL update file
- fix(DB/Spell): Adjust Tree Disguise spell effect (#6004)
- fix(Script/Command): Build (#6159)
- refactor(Core/Misc): acore to Acore (#6043)
- chore(DB): import pending SQL update file
- fix(DB): Adjust NPC Inquisitor Salrand's behaviour (#6003)
- feat(CI/Codestyle): add check core logs (#6012)
- chore(DB): import pending SQL update file
- fix(DB/Spells): Remove scaling from spell ID 36500 (#6002)
- fix(Core/Unit): Prevent Unit emote when entering combat (#6030)
- chore(deps/acelite): Remove VERSION (#6143)
- chore(import-sql): fix update (#6139)
- feat(Cmake/Modules): support add config all modules without AC_ADD_CONFIG_FILE (#5994)

## 2021-05-30
- fix(BASH/Compiler): error in if condition (#5983)
- chore(DB): import pending SQL update file
- feat(Core/Command): server debug (#6007)
- chore(DB): import pending SQL update file

## 2021-05-31
- fix(DB/loot): Staff of Horrors drops (#5999)

## 2021-05-30
- fix(CI): sql build (#6134)
- chore(DB): import pending SQL update file
- feat(DB/Version): Add date on update (#6006)
- chore(DB): import pending SQL update file
- feat(Core/Soap): delete ACE inherited (#4951)
- fix(DB/Resistances): Incorrect Holy resistances (#5496)
- fix(Core/Spells): triggering potion cooldowns (from TC) (#6016)
- feat(Core/Containers): MapGetValuePtr (#6111)
- feat(Core/Util): AsUnderlyingType (#6117)

## 2021-05-29
- chore(DB): import pending SQL update file
- fix(DB): Stormwind City Guard Pathing Into Lamppost (#5954)
- fix(Core): fix instance portal not resurrecting when corpse is not spawned (#6106)
- refactor(Core/Spell): Change "Attribute &" to HasAttribute() (#5991)
- fix(CI/Docker): free up additional space (#5993)

## 2021-05-28
- chore(DB): import pending SQL update file
- fix(Core/Player): Weapon skill gain (#5961)
- feat(Core/PacketIO): correct parsing some opcodes (#6051)

## 2021-05-27
- feat(Core/Common): add Asio network threading (#6063)
- fix(Core/Creature): Creatures will periodically call for assistance. (#5065)

## 2021-05-26
- chore(DB): import pending SQL update file

## 2021-05-27
- feat(Core/RealmList): port TrinityCore realm api (#5626)

## 2021-05-26
- feat(Core/Misc): includes cleanup (#5953)

## 2021-05-25
- chore(DB): import pending SQL update file
- fix(DB/Item): special characters for translation esES/esMX (#5948)
- chore(DB): import pending SQL update file
- fix(DB/Item) Special characters for translation esES/esMX (#5924)
- fix(Core/Spell): packet build in spell_pvp_trinket_wotf_shared_cd (#6048)
- fix(Core/WorldSession): prevent crash in SendPacket (#6045)
- chore(DB): import pending SQL update file
- fix(DB): Adjust Quest 7944 POI (#5918)
- refactor(Core/Creature): Split creature.h (#5974)
- fix(DB/gameobject): Andorhal sign location (#5962)
- fix(DB/loot): Adjust SM mobs' loot tables (#5947)
- fix(DB/loot): Shiver Blade drop (#5944)
- fix(DB): Adjust Blackhoof Cage behaviour (#5916)
- fix(DB/waypoint_data): Valdred Moray pathing (#5905)
- chore(DB): import pending SQL update file
- Adjust Scholomance Instructor Malicia abilities (#5239)

## 2021-05-24
- chore(DB): import pending SQL update file
- fix(DB/gameobject): Adjust Position For Some Copper Veins (#5701)

## 2021-05-23
- feat(Core/Main): Show Boost Version (#6019)
- feat(Deps/Boost): add boost support (#5676)
- chore(DB): import pending SQL update file
- fix(DBCreature): NPC 23859 gossip_menu_option_locale error (#5903)
- chore(DB): import pending SQL update file
- fix(DB/Quest): Fixed zhCN translate of Blood Is Thicker. (#5898)
- chore(DB): import pending SQL update file
- fix(DB/Creature): Remove Mistbat spawn in Eversong Woods (#5894)
- chore(DB): import pending SQL update file
- fix(Script/Creature): Script warlock imp (#5960)
- style(DB/Updates): Style 2021_03_19_02 (#5876)

## 2021-05-22
- chore(DB): import pending SQL update file
- fix(Scripts/Quest): A Cry For Help (#5720)
- fix(Core): CFBG achievements (#5900)
- refactor(Core/CliRunnable): Make AC> a static (#5621)
- fix(Core): GUID of GameObject (#6001)
- chore(DB): import pending SQL update file
- fix(DB/Creature): Add script to some Howling Fjord creatures (#5559)
- Update docker-cmd.ts (#5973)
- feat(Core/Packets): Port packet handling from TrinityCore (#5617)

## 2021-05-21
- chore(DB): import pending SQL update file
- fix(DB/creature,SAI): Silvermane Stalkers: grey -> black, no fade (#5875)
- fix(Core/Unit): criticals not working against sitting players. (#5872)
- chore(DB): import pending SQL update file
- fix(DB/Quest): Get the Scoop (1950) (#5858)
- feat(TOTP): use feature toggle via authserver.conf (#5978)
- fix(Core/Database): fix wrong Field::IsNull() return value on null binary fields (#5975)

## 2021-05-20
- Revert "feat(Core/Auth): add AccountInfo helper (#5640)" (#5971)
- chore(DB): import pending SQL update file
- fix(DB/spell_dbc): Rename Life Tap's Ranks (#5843)
- feat(Deps/FmtLib): update fmtlib to 7.1.3 (#5950)
- chore(DB): import pending SQL update file
- fix(DB/waypoint_data): Lizzarik and Jorb pathing (#5890)
- fix(Core/Banner): Add missing space (#5881)
- feat(Core/Auth): add AccountInfo helper (#5640)

## 2021-05-19
- chore(DB): import pending SQL update file
- fix(DB/command): delete command togglequerylog (#5846)
- fix(Scripts/Event): Removing hardcore texts in Love is in the Air (#5831)

## 2021-05-18
- fix(MySQL8): Add Drop script (#5828)
- chore(DB): import pending SQL update file
- fix(DB/Loot): Vampiric Duskbat (#5830)
- fix(DB/Quest): Lessons Anew (#5824)
- fix(DB/Quest): A Necessary Distraction (#5818)
- fix(DB/creature_loot_template): Remove the Scarlet Key from creature loot tables (#5814)
- fix(DB/Creature): Stonemaul spirit (#5812)
- fix(DB/Quest): Smolderwing (#5810)
- chore(DB): import pending SQL update file
- fix(DB/Quest): You Have Served Us Well (#5784)
- fix(Scripts): Crashfix. (#5913)

## 2021-05-17
- chore(DB): import pending SQL update file
- fix(DB/creature_loot_template): Remove Crumpled, Ripped and Torn Note from Highland Thrasher loot table (#5484)
- feat(Cmake/Compiler): deprecated clang6 and gcc 7 (#5671)
- feat(Core/Logging): improve DB logging (#5437)
- fix(Core/Loot): make Loot::AddItem() honor LootItem::AllowedForPlayer() (#5774)
- feat(Core/Random): port random system from TrinityCore (#5454)

## 2021-05-16
- fix(Core/Gameobjects):bloading addon table. (#5885)
- fix(CI): replace clang-9 with clang-8 (#5877)

## 2021-05-15
- chore(DB): import pending SQL update file
- fix(DB/Creature): improved Netherstom (#4916)
- feat(Core/BG): revamp Battleground.QueueAnnouncer.Limit (#5267)

## 2021-05-14
- fix(Scripts/Innkeeper): remove hard-coded texts (#5811)
- fix(Core): Memleaks fixes - Part II. (#5760)
- chore(DB): import pending SQL update file
- fix(Core/Maps): GetCollisionHeight and Z_OFFSET_FIND_HEIGHT (#5778)
- fix(DB/creature_addon): Remove path info from Blackwater Deckhand (#5758)
- fix(DB/smart_scripts): Remove spawn event for Scorn (#5754)
- fix(DB/creature_template): NPCs: 416, 417, 1860, 1863 (#5749)
- fix(DB/smart_scripts): Mirefin Coastrunner (#5723)
- fix(DB/crature_loot_template): Remove loot from Witherbark Bloodlings (#5711)
- fix(DB/creature_loot_template): Revelosh items drop (#5706)
- fix(DB/creature_formations): Adjust Boss Tho'grun's group (#5700)

## 2021-05-13
- chore(DB): import pending SQL update file
- fix(DB/gameobject): Adjust state for Rich Thorium Vein with GUID 120186 (#5756)
- chore(DB): import pending SQL update file
- fix(DB/gameobject): Adjust spawn time for Waterlogged Wreckage (#5755)
- chore(DB): import pending SQL update file

## 2021-05-12
- fix(DB/smart_scripts): Script "The End of the deserters" (#5708)

## 2021-05-13
- chore(DB): import pending SQL update file

## 2021-05-12
- fix(Scripts/DB/SAI): Return to Vahlarriel (#5712)

## 2021-05-13
- feat(Deps/Gperftools): make gperftools lib to interface (#5797)

## 2021-05-12
- fix(Core/Spell): Apply AURA_STATE_FAERIE_FIRE (#5703)

## 2021-05-13
- chore(DB): import pending SQL update file
- feat(Core/Authserver): TOTP rewrite (#5620)
- feat(Core/Config): added info about bad lines in config file (#5813)

## 2021-05-12
- chore(DB): import pending SQL update file
- fix(DB/item_template): Add coin loot to fishing trunks (#5772)

## 2021-05-11
- chore(DB): import pending SQL update file
- fix(DB/Smart_scripts): Add event on quest completion for last part of Elixir of Agony (#5359)
- fix(Core/Creature): Fix kill credit for some mobs after UpdateEntry (#5746)
- feat(apps): Config Merger (#5779)
- chore(DB): import pending SQL update file
- fix(DB/waypoint_data): Protector Dorana's waypoints (#5688)

## 2021-05-10
- fix(CORE/CREATURE) Polymorphed erratic mob behavior (#5699)
- feat(bash): Improved support for gperftools (#5769)
- feat(Core/DB): reconnect seconds and attempts configurable (#5673)
- Revert "feat(Core/Config): add abort message if config incorrect (#5438)" (#5761)
- fix(Core): Lower MIN_WANDER_DISTANCE_GROUND (#5693)
- chore(DB): import pending SQL update file
- fix(DB/creature): Adjust spawn time for Mosh'Ogg Ogres (#5738)
- chore(DB): import pending SQL update file
- fix(DB/gameobject): Respawn time of several ores (#5717)
- chore(DB): import pending SQL update file
- fix(DB): STV mobs dropping TBC items (#5727)
- chore(DB): import pending SQL update file
- fix(DB/quest_template_addon): Prevent Homeward Bound quest from autocompleting (#5694)
- chore(DB): import pending SQL update file
- fix(DB/smart_scripts): Supplies to Auberdine quest NPC behaviour (#5687)
- chore(DB): import pending SQL update file
- Fix: Chest Respawn time (#5695)

## 2021-05-09
- fix(Bash): process priority class Permission denied (#5686)
- chore(DB): import pending SQL update file

## 2021-05-10
- fix(DB): Remove Ashenvale quest mutual exclusivity (#5684)

## 2021-05-09
- feat(CI): trigger build on pr review (#5645)
- chore(DB): import pending SQL update file
- fix(Core/Scripts): Convert Galen's Escape to SAI (#5683)

## 2021-05-10
- chore(Core/Logging): enable logger sql and set level info (#5677)

## 2021-05-09
- chore(DB): import pending SQL update file
- fix(DB/creature_model_info): Adjust CombatReach for Sarathstra's creature_model(#5672)
- chore(DB): import pending SQL update file
- fix(DB/gameobject): Adjust position for Bruiseweed node with GUID 3440 (#5670)
- chore(DB): import pending SQL update file
- fix(Core/DB): Adjust Kodo Roundup quest mob behavior (#5665)
- fix(Core/LoadSmartAIFromDB): Prevent loading if entryorguid = 0 (#5663)

## 2021-05-08
- fix(Core/Misc): BuildAuctionMailBody guid (#5743)

## 2021-05-09
- fix(Scripts/HoS): Adjust IsEncounterInProgress() (#5642)
- chore(DB): import pending SQL update file
- fix(DB/gameobject_loot_template): Correct drop chances for all classic ores (#5628)
- chore(Core/Authserver): set default root logger to level info (#5613)

## 2021-05-08
- fix(Core): Reputation gain rate when nearby party members are dead (#5605)
- fix(Core/Pooling): Fixed less and less objects from pools being spawned the longer the server is running (#5572)
- chore(DB): import pending SQL update file
- fix(DB/Conditions): Add some missing comments (#5564)
- fix(Core/Movement): Fix strange teleport when rooting a fleeing NPC (#5555)

## 2021-05-07
- chore(DB): import pending SQL update file

## 2021-05-08
- fix(DB): Add additional Incendia Agave spawns (#5426)

## 2021-05-07
- fix(Core/Movement): MSG_MOVE_SET_* opcodes - GUID missing (#5554)
- feat(Core/Anticheat): Preparation to implement new passive anticheat … (#5516)
- fix(Core/Groups): fix group enchanting level not resetting properly (#5501)
- chore(DB): import pending SQL update file
- fix(Core/Spells): Berserk now removes the Tiger Fury buff. (#5481)
- chore(DB): import pending SQL update file

## 2021-05-06
- fix(DB/creature_addon): Adjust movement for Juvenile Snow Leopard (#5675)

## 2021-05-07
- chore(DB): import pending SQL update file
- fix(DB/Creature): Remove Skeletal Executioner from Silverpine Forest (#5251)
- feat(Core/Common): delete lib game-interface inherited (#5333)

## 2021-05-06
- chore(DB): import pending SQL update file
- fix(DB/go_loot_template): Silver Piffeny Band should not be lootable from chests (#5608)
- fix(DB/pool_creature): NPC: Or'Kalar (#5601)
- fix(DB/Creature): Apprentice Mirveda (#5596)
- fix(DB/Graveyard): add ghostZone for zone 1537 (#5581)
- fix(Creature/Gossip): Adjust some guard direction text (#5562)
- fix(DB/Creature): Son of Hakkar (#5561)
- fix(DB/Creature): Twilight Idolater (#5558)
- fix(DB/locale): Import esES/esMX translations (Part 2) (#5547)
- fix(DB/Creature): Verify & update Ashen Verdict reputation values (#5539)
- fix(DB): remove undesired DELETE statement
- chore(docker): pre-install deno within the images (#5644)
- feat(DB/Locales): missing esES & esMX quest locales [PART 3] (#5511)
- chore(DB): import pending SQL update file
- fix(DB/Spells): Arcane Missiles: They should not cause aggro when launched, but when hit with the first beam. (#5489)

## 2021-05-05
- chore(DB): import pending SQL update file
- feat(DB/Locales): missing esES & esMX quest locales [PART 2] (#5510)
- Revert "feat(CI): trigger windows build on comment (#5643)" (#5647)
- feat(CI): trigger windows build on comment (#5643)
- chore(DB): import pending SQL update file
- fix(DB/smart_scripts): Event quest "The Missing Diplomat" / Old Town Thugs (#5618)
- chore(DB): import pending SQL update file
- fix(DB/creature): Adjust spawn time for Saltscale murlocs (#5614)

## 2021-05-04
- chore(DB): import pending SQL update file
- fix(DB/broadcast_text): fix Stormwind guard Shaman trainer text (#5537)

## 2021-05-05
- chore(Core/SharedDefines): move SharedDefines.h to shared lib (#5518)

## 2021-05-04
- fix(docker): reduced client-data image of 200%
- docs(template): fix comment (#5634)
- chore(template): Make them less intimidating (#5569)
- chore(DB): import pending SQL update file
- hotfix(docker): login before push
- fix(DB/creature_formations): hezrul bodyguards path and formations (#5528)
- feat(docker): production images, integrated ccache and many other improvements (#5551)
- chore(DB): import pending SQL update file
- fix(DB/game_event_gameobject): link to brewfest 2 gameobjects (#5487)
- chore(DB): import pending SQL update file
- feat(DB/Locales):missing esES & esMX quest locales (#5483)
- chore(DB): import pending SQL update file

## 2021-05-03
- fix(DB/gameobject): Adjust XYZ pos for multiple mining nodes in STV (#5616)

## 2021-05-04
- chore(DB): import pending SQL update file
- fix(DB/Gameobject): duplicate or wrong spawns (#5258)

## 2021-05-03
- chore(DB): import pending SQL update file
- fix(DB/creature): move location, add path (#5486)
- chore(DB): import pending SQL update file
- fix(DB/creature_loot_template): Fix loot tables for a few rare npcs 2 (#5452)
- fix(Core/Battlegrounds): fix Warsong Gulch flags not capping when standing on capture area (#5482)
- chore(DB): import pending SQL update file

## 2021-05-02
- fix(DB/gameobject): Adjust position for Bruiseweed with GUID 3799 (#5567)

## 2021-05-03
- chore(DB): import pending SQL update file

## 2021-05-02
- fix(DB/creature): Adjust position for Syndicate Thief (#5566)

## 2021-05-03
- fix(Core/GameObjects): Gameobject rotation and moving actions not updating to client (#5223)

## 2021-05-02
- chore(DB): import pending SQL update file
- fix(DB/smart_scripts): SetInCombatWithZone at spawn for Haunting Spirit (#5568)
- chore(DB): import pending SQL update file
- fix(DB/gameobject): Adjust gob position for some Copper Vein nodes (#5602)
- chore(DB): import pending SQL update file
- fix(DB/creature): Adjust z position of creature in Wailing Caverns (#5465)
- fix(CI): change on: push to only run on master branch (#5591)
- chore(DB): import pending SQL update file

## 2021-05-01
- fix(DB/creature_loot_template): a few rare npcs (#5449)

## 2021-05-02
- feat(Core/Config): add abort message if config incorrect (#5438)

## 2021-05-01
- chore(DB): import pending SQL update file
- fix(DB/spell_dbc): Fix Eye of Eternity exit portal (#5468)
- fix(Core/TotemAI): Totems should not attack neutral unless owner is in combat (#5434)
- fix(Script/Command): HandleAddItemCommand (#5412)
- fix(Core/Unit): potential crash + extract duplicated code (#5303)
- fix(Core): fix chests not despawning when opened in group (2) (#5387)
- chore(DB): import pending SQL update file

## 2021-04-30
- feat(DB/smart_scripts): Add SAI for Icecrown's creatures (#5385)
- chore(DB): import pending SQL update file

## 2021-05-01
- Fix(DB/Smart_scripts) Ambassador Sunsorrow (#5364)

## 2021-04-30
- chore(DB): import pending SQL update file
- fix(DB/GameObj-Spawn/CreaturesSAI): EPL chest in Tyr's hand (#5187)
- chore(CI): move docker build to separate workflow (#5548)
- fix(Core/Misc): Memleaks fixes. Part I. (#5546)
- chore(DB): import pending SQL update file
- fix(Core/Guild): disable invite if players diff factions (#5519)
- feat(Core/Creature): Create & use CREATURE_FLAG_EXTRA_IGNORE_FEIGN_DEATH (#5360)
- chore(DB): import pending SQL update file
- fix(DB): Chest Pooling in Dustwallow Marsh (#5527)
- chore(DB): import pending SQL update file
- fix(DB): Alterac Mountains Chest Pooling (#5522)
- chore(DB): import pending SQL update file
- fix(Script/Instance) [Deadmines] Smite Slam (#5373)

## 2021-04-29
- chore(DB): import pending SQL update file

## 2021-04-30
- fix(DB): Chest Pooling in Tanaris (#5530)
- feat(CI): Issue Labeler (#5543)

## 2021-04-29
- chore(DB): import pending SQL update file
- fix(DB): Add Pooling to the Herbs in Burning Steppes (#5505)
- fix(DB): Chest Pooling in Desolace (#5500)
- fix(DB): Chest Pooling in Arathi Highlands (#5499)
- fix(DB): Stranglethorn Vale Chest Pooling 2 (#5509)
- chore(DB): import pending SQL update file
- fix(DB/Pets): Added `casterGuid` as a primary key to `pet_aura` table. (#5423)
- fix(Core/Loot): Fixed looting personal items while being in master loot group. (#5389)
- fix(Core/Spells): SPELL_AURA_DAMAGE_SHIELD auras should be modified by absorbs and resistance. (#5418)
- fix(Core/Player): correct add guid for packet SMSG_CLIENT_CONTROL_UPDATE (#5540)
- chore(DB): import pending SQL update file
- fix(DB/Creature): Add some immunities to ToC (#5436)
- fix(BASH): cp docker configs (#5536)
- chore(DB): import pending SQL update file
- chore(DB): import pending SQL update file
- chore(DB): import pending SQL update file
- chore(DB): import pending SQL update file
- fix(doc): cleanup outdated documentation in ScriptMgr.h (#5488)

## 2021-04-28
- chore(DB): import pending SQL update file
- fix(Docker): windows improvements and permissions fix (#5444)
- refactor(Core/Misc): Define & Rename Attributes (#5311)

## 2021-04-27
- chore(DB): import pending SQL update file
- Fix Chest Pooling in Stranglethorn Vale (#5498)
- fix(Core/Spells): Do not allow the use of the master's call while the pet is controlled [port from TC] (#5273)
- chore(DB): import pending SQL update file
- fix(Core/Ticket): close & resolve by console -1 (#5326)
- chore(DB): import pending SQL update file
- fix(DB/Gameobject) Mining nodes inside of eachother (#5345)
- fix(Core/Movement) : Improved confused movement generator. (#5491)

## 2021-04-26
- fix(CI/macOS): change build type to release (#5466)
- chore(DB): import pending SQL update file
- fix(DB/Gameobject): Add (more) Tailasher Eggs (#5344)
- fix(CI): filter extra spaces (#5441)
- fix(Core/Spell): Apply AURA_STATE_FAERIE_FIRE to Faerie Fire (#5319)

## 2021-04-25
- chore(DB): import pending SQL update file
- feat(Core/Misc): implement ObjectGuid class (port from TC) (#4885)
- chore(DB): import pending SQL update file
- chore(DB/gameobject): move gameobject cookpot (#5404)
- fix(DB/Creature): Brote (#5381)
- fix(DB) A Lost Master missing prerequisite (#5375)
- fix(DB/Smart_scripts) Razorfen Stalker (#5358)
- fix(DB/npc_trainer): set req skill to 225 for 9954 (#5350)
- fix(DB/creature_loot_template): Fix Broken Tooth loot table (#5337)
- fix(DB/Quest): Add Horde restriction to some quests (#5330)
- feat(DB/Spawns): add vulture spawns (#5322)
- fix(DB/gameobject): Adjust Position For Fishing Schools (#5318)
- refactor(DB/spell_dbc): Update AttributesEx names (#5317)
- fix(DB): Scholomance Occultists behavior (#5314)
- fix(DB/Spells): several spells (#5298)
- fix(DB/quest_poi_points): location tracker of Quell the Uprising (#5296)
- chore(DB): import pending SQL update file
- fix(DB/SAI): acore_string missing locale_zhCN (#5288)

## 2021-04-24
- fix(Core/Spells): cyclone shouldn't be casted on totems (#5306)

## 2021-04-25
- Adjust Scholomance Kirtonos boss fight (#5313)
- chore(DB): import pending SQL update file
- Adjust wander distance and movement type on Splintered Skeleton (#5244)
- fix(CI): disable mac PCH to allow more caching (#5427)

## 2021-04-24
- chore(DB): import pending SQL update file
- fix(DB/Creature): The Ebon Watcher (#5380)
- feat(Core/Achievements): Send guild's name instead of the player's one when achieved realm first kill. (#5409)
- fix(Core/Spells): Cloak of Shadows: Spell [Pounce Bleed] should not be (#5305)
- fix(docker): env variable settings (#5432)
- chore(DB): import pending SQL update file
- fix(DB/SAI): Quest Fel Spirits (#4988)
- chore(DB): import pending SQL update file
- fix(DB/creature_template): Update BaseAttackTime for various creatures (#4826)

## 2021-04-23
- chore(CI): move windows build to separate workflow (#5405)
- chore(CI): move macos build to separate workflow (#5416)
- feat(Core/Movement): time synchronisation to better interpret client timestamps (#5300)
- fix(bash): bash errors on windows (#5406)
- fix(Core/Script): Shadowmeld (#4857)

## 2021-04-22
- chore(DB): import pending SQL update file
- fix(DB/npc_text): Add gossip for Jangdor Swiftstrider (#5402)
- chore(deno): upgraded v1.9.1 (#5401)
- Feat(Docker/bash): docker-compose system rework (#4488)
- chore(DB): import pending SQL update file

## 2021-04-21
- fix(DB/smart_scripts): Landslide - Adjust Knock Back spell & despawn minions on death (#5395)
- fix(Core/Player): Enable water walking when dead on instances (#5393)

## 2021-04-22
- feat(Core/Build): add the possibility to link libraries dynamically (#5348)

## 2021-04-21
- Revert "fix(Core): fix chests not despawning when opened in group (#5371)" (#5386)
- chore(DB): import pending SQL update file

## 2021-04-20
- fix(DB/gameobject): Adjust position for Bruiseweed node - GUID 3538 (#5363)
- fix(Core): fix chests not despawning when opened in group (#5371)
- feat(Cmake/Database): separate database lib from common (#5334)

## 2021-04-19
- chore(DB): import pending SQL update file
- fix(DB/GameEvent): darkmoon faire carnie spawn on event (#5293)
- fix(Scripts/RubySanctum): Xerestrasza Incorrect Usage of GOSSIP_OPTIONQUESTGIVER (#5286)
- Scripts/RazorfenDowns: Fix Belnistrasz Incorrect Usage of GOSSIP_OPTION_QUESTGIVER (#5285)
- fix(Core/Tools): extracting custom maps (#5138)
- chore(DB): import pending SQL update file
- fix(DB/Zone):improved Shadowmoon Valley (#4915)
- chore(DB): import pending SQL update file
- fix(DB/gameobject): Adjust position for Wild Steelbloom node - GUID 4997 (#5331)
- chore(DB): import pending SQL update file

## 2021-04-18
- fix(DB/gameobject): Adjust position for Bruiseweed - GUID 3716 (#5332)

## 2021-04-19
- chore(DB): import pending SQL update file
- fix(DB/SAI): Quest of Bodley without AllowableClasses Setting (#5283)

## 2021-04-18
- fix(DB/Spell): flurry talent shaman rework (#5262)

## 2021-04-19
- fix(DB): Drop for Humbert's Helm (#5260)
- fix(DB/creature_template): Add missing gossip to Terenthis in Auberdine, Darkshore (#5259)
- fix(DB/Creature): add missing spirit healer (#5257)
- fix(DB/Spawns): duplicate nodes (#5255)
- fix(DB/Creature): thrown animations (#5254)
- fix(DB/Creature): move creature spawn (#5256)

## 2021-04-18
- chore(DB): import pending SQL update file
- fix(DB/Waypoints): Sethir the Ancient path (#5247)
- chore(DB): import pending SQL update file
- fix(DB): spawn missing vanilla rares (#4639)
- chore(DB): import pending SQL update file
- fix(DB/creature_template): Adjust InhabitType and SAI - Deviate creatures (#5335)
- chore(DB): import pending SQL update file
- Fix Scholomance Gandling encounter (#5245)
- feat(Core/Debugging): Allow to show a message when aborting (#5228)
- feat(apps): Add a tool to remove trailing whitespaces (#4074)
- fix(Core/Warden): typo 81301c67d. (#5284)
- refactor(Core/Server): Move Banner into separate file (#5207)

## 2021-04-17
- chore(DB): import pending SQL update file
- fix(DB/GameObject-Spawn): Copper veins spawns in Mulgore (#5240)
- feat(Core/Logging): rework logging (#4692)
- feat(Core/Threading): replace ace threading (#4821)

## 2021-04-16
- fix(Core/BGQueue): correct return BattlegroundQueueTypeId (#5304)
- fix(Core/Movement): Make sure pet always follows its master. (#5103)
- chore(DB): import pending SQL update file
- fix(DB/quest) Leave no one behind (#3674)

## 2021-04-15
- refactor(Core/Misc): Define & Rename Attributes and flags (#5193)
- fix(DB/Account): Remove default accounts (#5292)

## 2021-04-14
- chore(DB): import pending SQL update file
- fix(DB/page_text): Fix typo in page text of Hallowed Scroll (#5282)
- chore(DB): import pending SQL update file
- fix(DB/creature_loot_template): Remove 'Wastewander Water Pouch' from Andre Firebeard (#5281)
- chore(DB): import pending SQL update file
- fix(DB/smart_scripts): Deviate Guardian - Call for help (#5280)

## 2021-04-13
- chore(DB): import pending SQL update file
- fix(Core/GameObjects): Creating gameobject's model requires set go state. (#5188)
- feat(Core/Player): detect Spanish clients (#5186)
- chore(DB): import pending SQL update file
- fix(DB/GameObjects) Incorrect and Duplicate Chairs. (#5236)
- feat(Core/Hooks): added collection of hooks to extends AC (#3047)
- chore(DB): import pending SQL update file
- fix(DB/DBC): correct gtoctclasscombatratingscalar_dbc (#4072)
- chore(DB): import pending SQL update file
- fix(DB/Quest): Noblegarden RewardMoney (#5268)

## 2021-04-12
- feat(Core/Database): implement db loader (#4431)

## 2021-04-11
- feat(CI): add extra_logs to build matrix and update warden ByteArrayToHexStr (#5102)
- chore(DB): import pending SQL update file
- fix(DB/GameObject): Bubbling Fissure (#5150)
- fix(Core/Unit): decrease swim speed (#5149)
- chore(Core/SpellMgr): Indentation (#5145)
- fix(DB/Quest): required race (faction) of quest (#5143)
- fix(DB/Spawn): move spawn over the ground (#5141)
- fix(DB/Quest): The Principal Source (#5134)
- fix(DB/Spawn): move spawn because it was under the earth (#5122)
- fix(DB): The Missing Diplomat Part 11 Fix (#5070)
- fix(DB/Creature): Skinning loot (#5219)
- fix(DB/GameObject-Spawn): Solid Chest respawn time for gameobject 100068,16946 (#5212)
- fix(DB/GameObject-Spawn): Solid Chest respawn time for gameobject 100067 (#5210)
- fix(DB): Demetria is alone (#5205)
- fix(DB/gameobject): Change position of copper/other veins (#5204)
- fix(DB/Creature): Timberstrider Fledgling undermap (#5201)
- fix(DB/GameObject) Mining veins spawn (#5198)
- fix(DB/Spell): Demoralizing Roar (#5197)
- fix(DB): Flesh piercer drop rate (#5195)
- fix(DB/CreatureSAI): Ranged mobs shooting (#5192)
- fix(DB/CreatureSkinning): Skinning boars (#5190)
- fix(DB/Items-Drop-Chance): Battered Junkboxes (#5176)
- fix(DB/Creatures): Npc Minions not Engaging (#5166)
- fix(DB/Creatures): Raptor Ridge Cave (#5155)
- fix(DB/GameObjects-Spawn): The Shade of Elura (#5182)
- fix(DB/Creature): Ruul Snowhoof (#5174)
- fix(DB/CreatureSpawn): Nerubis Guard (#5172)
- fix(DB/CreatureSAI): Razormane Wolf (#5171)
- fix(DB/Spells): All PvP Bandages (#5168)
- fix(DB/Spell): Brutal Assault debuff remaining (#5165)
- fix(DB/Creature): set movementType to 2 for Rageclaw (#5154)

## 2021-04-09
- chore(DB): import pending SQL update file
- feat(Core/Spell): Define SPELL_AURA_PREVENT_DURABILITY_LOSS (#5148)
- fix(Core/Movement):  fix multiple creature movement issues (#5097)

## 2021-04-10
- feat(Core/BattlegroundQueue): add limited Battleground.QueueAnnouncer (#5093)

## 2021-04-09
- fix(Bash): client data files version 10 (#5146)
- fix(Core): Warning C4018 (#5091)
- fix(Core/Spells): Spells learned from skills should be visibile immediately in the spellbook and chat. (#5106)

## 2021-04-08
- fix(Core/Player): Allow sharing completed in log quests. Send push to party on failed reason seasonal (#4880)
- refactor(DB/SQL): Update 2021_03_29_01.sql to MYSQL standards (#5144)
- feat(Core/PvP): Set 30 sec timer before turn off FFA PvP flag. (#5090)
- fix(Core/Unit): Set AI notification when setting/removing contested PvP flags. (#5076)
- chore(DB): import pending SQL update file
- fix(DB/Spell): Execute Warrior (#5125)

## 2021-04-07
- fix(Core/Spell): make use of SPELL_ATTR3_IGNORE_PROC_SUBCLASS_MASK (#5005)
- fix(Core/Spell): Make use of SPELL_ATTR6_DONT_CONSUME_PROC_CHARGES (#5004)
- chore(DB): import pending SQL update file
- fix(Core/Script): Rename Pinnacle & Ramparts scripts (#5175)
- fix(Core/Objects): LoS calculation (#5084)
- feat(Apps): Automatic extractor for windows (#5177)
- chore(DB): import pending SQL update file
- fix(Core/Spell): Handle ClearAllDebuffs (#5006)
- fix(Core/Loot): Items below group threshold should not be blocked by master looter. (#5041)

## 2021-04-06
- chore(DB): import pending SQL update file
- fix(DB/smart_scripts): Adjust SAI for Elder Timberling (#5170)
- chore(DB): import pending SQL update file
- fix(DB/creature): Adjust xyz position for multiple creatures in Wailing Caverns (#5163)
- chore(DB): import pending SQL update file
- fix(DB/smart_scripts): Adjust SAI for Dabyrie Laborer (#5162)
- chore(DB): import pending SQL update file
- fix(DB/smart_scripts): Remove 'Prowl' on 'Flatland Prowler' (#5161)
- chore(DB): import pending SQL update file
- fix(DB/gameobject): Adjust position for Copper Vein 5242 (#5159)
- chore(DB): import pending SQL update file
- fix(DB/creature_template): Remove cataclysm gossip on Argos Nightwhisper (#5158)
- fix(Core/Spells): Ensures that procs triggered by another aura are proccessed in the first place. (#5075)
- fix(Core/Movement): Removed wrong code that blocked updating movement generators in case of root/stun. (#5061)
- refactor(Core/Common): generalise platform specific includes in common/Platform (#5058)
- fix(Core/PetAI): Fixed logic in PetAI to determine if pet can cast co… (#5038)
- fix(Core/FriendStatus): Alerted when friends log in/out (#4995)
- fix(Core/Spell): Make use of SPELL_ATTR4_DONT_REMOVE_IN_ARENA (#4990)
- fix(Core): Boss encounter disengage improvement (#4954)
- chore(DB): import pending SQL update file

## 2021-04-05
- fix(DB/locale): Import esES/esMX translations (#5160)
- chore(DB): import pending SQL update file
- fix(DB/creature_loot_template): Adjust Okra drop rate (#5139)
- chore(DB): import pending SQL update file
- feat(Core/Creatures): extend mob leash mechanic assist in-combat creatures (#4897)
- feat(Core/Instance): Add instance validation for creature scripts (#4596)
- fix(DB/Spell): explosive sheep duration time (#5119)
- chore(DB): import pending SQL update file
- fix(DB/Spell): Flurry Shaman Talent (#5117)
- fix(Core): Remove RDF cooldown after completion (#5034)
- fix(Core): Ghost property fix (#5033)
- feat(Tools/Vmapextractor): Improved vmap detail level by extracting w… (#4922)
- chore(DB): import pending SQL update file

## 2021-04-04
- fix(DB/gameobject): Adjust position for Cooper Vein 18679 (#5132)

## 2021-04-05
- chore(DB): import pending SQL update file

## 2021-04-04
- fix(DB/loot): Adjust loot chance of Captain's Key (#5133)

## 2021-04-05
- fix(Core/Log): GMLogFile -> GmLogFile (#5130)

## 2021-04-04
- chore(DB): import pending SQL update file
- fix(DB/Quest): make quest "a new plague" for Horde (#5110)
- fix(DB) Spawn placement of mineral veins - Redridge Mountains (#5100)
- fix(DB/gameobject): Align respawn time of fish schools / wreckage (#4884)
- fix(Core/Movement): Corrected calculating ground level in shallow water. (#5114)
- chore(DB): import pending SQL update file

## 2021-04-03
- fix(DB/creature): Add Missing Marauding Geist in Naxxramas (#5123)

## 2021-04-04
- chore(DB): import pending SQL update file
- fix(DB/Spell): Hunter bug with melee weapons (#5121)

## 2021-04-03
- feat(Core/SmartScripts) Implement SMART_TARGET_VEHICLE_PASSENGER (#3510)
- chore(DB): import pending SQL update file

## 2021-04-02
- fix(scripts/Naxx): The art of Naxxramas (2/2) (#5057)
- chore(DB): import pending SQL update file
- fix(DB/Zone):improved Hellfire Peninsula (#4921)
- feat(Cmake/PCH): use target_precompile_headers instead of cotire (#5082)

## 2021-04-01
- chore(DB): import pending SQL update file
- fix(DB/Gameobject): Adjusted autoclose time to properly handle Archmage Arugal door lever. (#5060)
- fix(DB/Creature): Removed UNIT_FLAG_SWIMMING from mobs in The Master's Glaive area. (#5059)
- fix(DB/creature_template): aet RangeAttackTime to default value (#4767)
- fix(DB/SAI): NPC Nancy Vishas (#5089)
- fix(DB/Spells): spell "57874 Twilight Shift" should be negative + target only players (#5087)
- fix(DB): The Ancient Statuette questline missing smart scripts and waypoints (#5080)
- fix(DB/gameobject): Remove duplicate herbs (#5079)
- fix(DB/gameobject): Remove duplicate mineral nodes (#5078)
- fix(DB/creature_template): Disciple of Naralax walking speed (#5073)
- fix(DB/CreaturesSAI): Quest Unexpected Results (#5072)
- fix(DB/pool_template): Fix Black Lotus in Burning Steppes (#5071)
- fix(DB/CreaturesSAI): Silithid Invader and Silithid Hive Drone (#5069)
- fix(DB/Creatures/GameObjectSAI): Quest Helcular's Revenge (#5067)
- fix(DB/CreaturesSAI): Quest Matis the Cruel (#5062)
- fix(DB): Deviate Hides not available for Alliance (#5051)
- fix(DB): NPCs don't attack the player if he is in water (#5049)
- fix(DB): Wrong Dialog for 1st Aid trainers (#5032)
- fix(DB): wrong position or multiple placements of herbs (#5023)
- fix(DB/quest_template): Travel to Darkshire (#5010)
- fix(DB/quest_template): A New Plague is not just for undeads (#5009)
- fix(DB/Creatures/GameObject/SAI): Quest-Ending-Their-World (#4998)
- fix(DB): herb spawn position (#4985)
- fix(Core/Config): Removed unsued config. (#4957)
- fix(BASH/INSTALLER): add missing deps for debian 10 (#5019)

## 2021-03-31
- chore(DB): import pending SQL update file

## 2021-03-30
- fix(DB/Quest): Spanish translation (hellfire and varied) Part 1 (#4968)
- Revert "feat(Core/Spells): improve SpellCheckRange(), spell cast when dismounting, falling or levitating spells (#3384)" (#5052)
- fix(Scripts/Commands): correct reloading creature_template table (#5020)

## 2021-03-29
- chore(DB): import pending SQL update file
- feat(CORE/Instance): access_requirement db refactor and improved output (#3696)
- fix(Scripts): Pilfering Perfume (#5043)
- chore(DB): import pending SQL update file
- fix(scripts/DB): Implement "Marked immortal guardian" (#5046)

## 2021-03-28
- chore(DB): import pending SQL update file

## 2021-03-29
- fix(DB/gameobject): Add treasures in Eastern Plaguelands to a pool (#4947)

## 2021-03-28
- fix(scripts/UtgardeKeep): Improve Dalronn & Skarvald (#5044)
- fix(Core/Creatures): Fixed unitialized varibale implemented in 728d018. (#5042)
- chore(DB): import pending SQL update file
- fix(DB/mechanic_immune_mask): Bosses from Deadmines  (#4977)
- chore(DB): import pending SQL update file
- Added missing gossip_menus (#5035)
- fix(Core): Implement retail-like fishing skill-up functionality (#4809)
- chore(DB): import pending SQL update file
- fix(Core/Warden): Fixed random kicks caused by warden. (#5027)
- chore(DB): import pending SQL update file
- fix(DB/Spell): Paladin talent Heart of the Crusader (#4585)
- fix(Core/Spell): Restricted Flight Area (#5016)
- fix(Core/Gameobject): Spell spawned chests should not despawn on loot (#4413)

## 2021-03-27
- chore(DB): import pending SQL update file
- fix(DB/SAI): Edwin VanCleef encounter (#5007)
- fix(scripts/Gruul): Boss script fine tuning (#4126)

## 2021-03-26
- docs: update PR template (#5015)
- feat(Core/Spells): improve SpellCheckRange(), spell cast when dismounting, falling or levitating spells (#3384)
- fix(Core/AI): improve npc_escortAI (#4980)

## 2021-03-25
- fix(PullRequestTemplate): Adjustment and fix typo (#5002)
- chore(DB): import pending SQL update file
- fix(DB/creature_loot_template): Lower drops from Mottled Scytheclaw and Raptors (#4948)
- feat(Core/Sockets): replace ACE_ASSERT to default core ASSERT (#4950)
- fix(Core/Spell): Make use of SPELL_ATTR7_IGNORE_COLD_WEATHER_FLYING (#4933)

## 2021-03-24
- fix(Core/Spell): Make use of SPELL_ATTR6_NOT_RESET_SWING_IF_INSTANT (#4931)
- feat(Core/Game): Add option to disable trading BoP items among raid members (#4895)
- feat(IssueTemplate/BugReport): Improve templates and add "source" field (#4959)
- feat(Core/SignalHandler): Replace ACE signal handling with std (#4877)
- refactor(DB/SQL): Update integer & utf to MySQL's new standards (#4929)
- chore(DB): import pending SQL update file
- fix(DB): Update some VoA scripts SAI, add waypoints (#3489)

## 2021-03-23
- chore(DB): import pending SQL update file
- fix(DB/Account): fixed CHARSET in account_muted (#4215)
- feat(Core/Movement): MotionMaster "Land" and "Take off" velocity speed is optional now (#3446)
- chore(DB): import pending SQL update file
- fix(scripts/Naxx): The art of Naxxramas (1/2) (#4076)
- fix(Core/GUARD_RETURN): correct typo (#3743)

## 2021-03-22
- chore(DB): import pending SQL update file
- Fix for wrong spawn mining veins (#4938)
- chore(DB): import pending SQL update file
- (DB/Gameobject_addon) Fixed position for Ironforge Library plaques (#4924)
- chore(DB): import pending SQL update file
- fix(Core/Spell): Val'anyr periodic healings proc and move to new proc system (#4216)

## 2021-03-21
- chore(DB): import pending SQL update file
- fix(Build/Windows): For OS locales like CJK (#4912)
- feat(Build): allow using MySQL/MariaDB/OpenSSL from vcpkg (#4914)
- feat(Core/Maps): Use a fixed offset instead of full collision height when retrieving floor Z. (#4909)
- fix(Core/AI): add condition to force casters into melee combat (#4894)
- fix(Core/Creature): Respawning mobs missing aggro "grace period" (#4893)
- fix(Core/Command): crash on set model to npc if not valid (#4874)
- fix(Core/Maps): Include collision height in underwater status calculations. (#4855)
- feat(Core/Spells): Implemented SPELL_AURA_DETECT_AMORE. (#4850)
- fix(Core/Creatures): Fixed displaying trainer npcflags that are not valid to player. (#4848)
- feat(Core/DB/Authserver): remove `sha_pass_hash` (#4827)
- chore(DB): import pending SQL update file
- feat(Core/Creature): Implement c_t_r & c_t_s (#4359)
- fix(Core/Commands): .cheat god lowering hp to 1 and .cheat power not refilling power (#3299)
- feat(Core/Utilities): Introduce a task scheduler which schedules task (#4932)

## 2021-03-20
- feat(Core/Hooks): OnLastIpUpdate(accountId, ip) (#4913)
- fix(DB): sql chain (#4925)
- chore(DB): import pending SQL update file
- fix(Core/Movement): Fixed collision calculation returning wrong position. (#4879)
- fix(DB/quest_poi): Wrong map marker position - The Princial Source (A) (#4870)
- fix(DB):Stranglethorn Fever Fixes - Perry Gatner Event (#4864)
- fix(DB/CreatureSAI/GameObjectSAI): Quest Call of Water 5/6 (#4892)
- fix(DB/pool_template): Treasures in Teldrassil (#4887)
- fix(DB/CreatureSAI): Quest: One Shot One Kill (#4869)
- fix(DB/item): Remove Horde-only from Pattern: Raptor Hide Harness (#4861)
- fix(Core/Loot): Gold should always be lootable, even if it's the only loot (#4842)
- chore(DB): import pending SQL update file
- fix(scripts/Ulduar): Improve Hodir (#4703)
- fix(Core/SpellEffect): Increase speed of cat charge (#4795)

## 2021-03-19
- chore(DB): import pending SQL update file

## 2021-03-20
- fix(DB/Core) Fix the CLS damage system and update creature_classlevelstats (#4749)

## 2021-03-19
- chore(DB): import pending SQL update file
- fix(DB/Fix Faction): Quest: Freedom to Ruul (#4866)
- chore(DB): import pending SQL update file
- fix(DB/creature_template): Correct speed_run and speed_walk (#4644)
- fix(Core): prevent potential crash (#4875)
- fix(Core/MailHandler): Fix display of item enchantments in mailbox (#4872)

## 2021-03-18
- chore(DB): import pending SQL update file
- fix(DB/GameObject-Spawn): Solid Chests respawn time in Azshara (#4838)
- chore(DB): import pending SQL update file
- fix(DB/gameobject): Archbishop Alonsus Faol misplaced plaque in Stormwind (#4846)
- chore(DB): import pending SQL update file
- fix(DB/creature): King Bangalash (#4825)
- chore(DB): import pending SQL update file
- fix(DB/Creature): Remove loot from Enslaved Druid of the Talon (#4840)
- chore(DB): import pending SQL update file
- fix(DB/SAI): Lunaclaw (#4859)
- fix(Core): Removing auras from spells that trigger taxi (#4820)

## 2021-03-17
- feat(CI): clang-11 in ubuntu 20.04 (#4891)
- chore(DB): import pending SQL update file
- fix(Core/DB): Susurrus hardcoded to SmartAI (#4819)
- chore(DB): import pending SQL update file
- fix(DB/creature): Dreadmaw Crocolisk's position (#4889)
- fix(Core/License): issue with old files license (#4762)
- fix(scripts/VoA): Vault of Archavon (#4853)
- fix(scripts/Ulduar): Two fixes to Algalon encounter (#4852)
- fix(scripts/Ulduar): Spinning UP during 4th phase (#4876)
- chore(DB): import pending SQL update file
- fix(DB/Warden): Export 6 warden checks from TC that were corrupted on AC (#4856)
- chore(DB): import pending SQL update file
- fix(DB/creature_template): Resistances for level 1-20 creatures (#4753)
- chore(DB): import pending SQL update file
- fix(DB/pool_template): Allow more mineral veins in Duskwood (#4724)
- chore(DB): import pending SQL update file
- fix(DB/Creature): Remove Vyrin Swiftwind's Innkeeper title (#4721)

## 2021-03-16
- chore(DB): import pending SQL update file

## 2021-03-17
- fix(DB/gameobjects): Add more herbs to Bloodmyst Isle (#4696)

## 2021-03-16
- fix(Core): Rogue - Premeditation fix (#4695)
- chore(DB): import pending SQL update file
- fix(DB/creatures): Update CC immunities for multiple creatures (#4630)
- chore(DB): import pending SQL update file
- fix(DB/gameobject): Add treasures to Bloodmyst Isle (#4690)
- chore(DB): import pending SQL update file
- fix(DB/gameobjects): Mineral veins on Bloodmyst Isle (#4689)

## 2021-03-14
- chore(DB): import pending SQL update file
- fix(DB/Quest): Spanish translation for Silithus (#4648)
- chore(DB): import pending SQL update file
- fix(DB/GameObject-SpawnEvent): Brewfest banners in Darnassus (#4835)
- fix(DB/GameObject-SAI): Bubbling Fissures in Moonglade (#4834)
- fix(DB/GameObject-Spawn): Copper Veins above Jangolode Mine (#4833)
- fix(DB/Creature-Spawn): Gnolls Underground in Wetlands (#4832)
- fix(DB/Creature) bugged Pridewing Soarer (#4824)
- fix(DB/Creature): Make Lady Moongazer move around (#4818)
- fix(DB/quest): The Tear of the Moons (#4817)
- fix(DB/quest): Bounty on Murlocs has no prerequisite (#4815)
- fix(DB/Spell): suicide saboteur on sapper explode (#4799)
- fix(DB/Gameobject): spawn position (#4797)
- fix(DB/CreatureSAI): Various mobs in Tirisfal (#4794)
- fix(DB/CreatureSAI): Bael'dun Foreman and Digger Flameforge (#4759)
- fix(DB/SAI): ashenvale outrunner stealthed (#4710)

## 2021-03-13
- feat(Core/Hook): OnSendInitialPacketBeforeAddToMap (#4645)

## 2021-03-12
- fix(Core/Spells): Warlock Death Coil shouldn't be able to crit (#4629)

## 2021-03-11
- chore(DB): import pending SQL update file
- fix(DB/CreatureSAI): Ruul-Snowhoof (#4786)
- chore(DB): import pending SQL update file
- fix(DB/Creature): Add spirit healer to Eastern graveyard in Arathi Highlands (#4789)
- fix(DB/object): Increase respawn timer of Booty Bay fishing pool (#4780)
- fix(DB/quest): Gathering Leather requires skinning (#4771)
- fix(Core): [Spell][Night Elf] Shadowmeld is not working properly (#4765)
- fix(DB/GameObjectSpawn): Floating Giant Clam in Ghostlands (#4761)
- fix(DB/CreatureSAI): Gnarlpine Mystic (#4760)
- fix(DB/CreatureSAI): Quest Denalans Earth (#4758)
- fix(DB): some vanilla instance rare creatures and add missing ones (#4625)

## 2021-03-10
- chore(DB): import pending SQL update file
- fix(DB/Spell+CreatureSAI): Leprous Machinesmith (#4757)
- chore(DB): import pending SQL update file

## 2021-03-09
- fix(DB/creature_addon): Add "Double Attack" back on Anub'Rekhan and Gluth (#4779)
- chore(DB): import pending SQL update file

## 2021-03-10
- fix(DB/creature): Kolkar Drudge and Kolkar Outrunner resistances (#4746)

## 2021-03-09
- fix(DB/GameEvent/CreatureSpawns): Hallow's-End-NPCs (#4750)
- chore(DB): import pending SQL update file
- fix(DB/creature_addon): Remove extra attacks from Naxxramas NPCs (#4773)
- fix(Core/Utilites): improve acore::String::Trim (#4704)

## 2021-03-08
- chore(DB): import pending SQL update file
- fix(DB/creatures): correct BaseAttackTime and RangeAttackTime (#4637)

## 2021-03-07
- fix(bash): Handle different Debian versions (#4607)
- chore(DB): import pending SQL update file
- fix(Core/DB): Missing Diplomat Quests Part 11,14,16 and Minor Guard Tower Fixes (#4719)
- chore(DB): import pending SQL update file
- fix(DB/gameobject): Improve quest Fields of Grief (part2) (#4722)
- fix(Code/Fishing): improve timing of fishing (#4733)
- fix(DB/Quest): prevQuest (#4727)
- fix(DB/GameObject/SAI): Bubbling Fissure (#4717)
- fix(DB/Text): chicken text for CLUCK special quest (#4714)
- fix(Core/Spell): Anti-Venom (#4711)
- fix(DB/Quest): prevquest for quest 872 (#4687)
- fix(DB/Quest): make quest 75 not repeatable (#4685)
- fix(DB/Page): update legacy aspects (#4684)
- fix(DB/SAI): remove SAI for talk line 0 (#4682)
- fix(DB/Spell): quest very tasty (#4677)
- fix(DB/Loot): remove blackened gloves loot (#4672)
- chore(DB): import pending SQL update file

## 2021-03-06
- fix(DB/creature_loot_template): Remove Long Crawler Limb from Ghostclaw Lynx (#4741)

## 2021-03-07
- chore(DB): import pending SQL update file

## 2021-03-06
- fix(DB/creature): Adjust position for Cursed Darkhound (#4745)
- chore(DB): import pending SQL update file
- fix(DB/smart_scripts): Pyrewood Elder - Healing SAI (#4737)

## 2021-03-05
- chore(DB): import pending SQL update file
- fix(DB/creature_loot_template): Remove loot on creatures that shouldn't have loot (#4718)
- fix(DOCKER): add dos2unix conversion when generating config files (#4697)

## 2021-03-04
- fix(Core): Compilation with EXTRA_LOGS in Windows (#4605)
- chore(DB): import pending SQL update file
- fix(DB/smart_scripts): Nagrand Kristen Dipswitch event (#4604)
- chore(DB): import pending SQL update file
- fix(DB/gameobject): 'Chemical Wagon' zhCN translation (#4601)
- fix(Core/player): Fix localized gossip_menu_option (#4584)

## 2021-03-03
- chore(Core/worldserver.conf): Enable warden by default (#4533)
- chore(DB): import pending SQL update file

## 2021-03-02
- fix(DB/creature_template): Fix 'Riding Horse' faction (#4679)

## 2021-03-03
- chore(DB): import pending SQL update file

## 2021-03-02
- fix(DB/gameobject): Underground Herbs in Mulgore (#4678)
- refactor(Core): replace NULL with nullptr (#4593)

## 2021-02-28
- feat(Core/Config): rework config and delete ACE inherited (#4608)
- chore(DB): import pending SQL update file
- fix(DB/Core/Creatures/SAI): Pyrewood Ambush Quest (#4649)
- fix(DB/CreaturesSAI): Mobs Casting Daze (#4641)
- fix(DB/Creature/SAI): Quest Mist Disappearing cat (#4655)

## 2021-02-27
- chore(DB): import pending SQL update file
- fix(DB/creature): Young Moonkin shouldn't have Moonfire (#4651)

## 2021-02-26
- chore(Misc): correct double includes (#4647)

## 2021-02-25
- chore(DB): import pending SQL update file

## 2021-02-24
- fix(DB): Gnomeregan - Viscous Fallout and Minions Update (#4643)

## 2021-02-25
- fix(DB/object): Pool copper veins on Bloodmyst Isle (#4636)
- fix(DB/object): Pool copper veins in Eversong Forest (#4634)
- fix(DB/object): Pool copper veins on Azuremyst Isle (#4633)
- fix(DB/Creature): Patroling-Deathguards-chain-aggro-range (#4632)
- fix(DB/Creature): Burning Blade Apprentice Summon Voidwalker (#4626)

## 2021-02-24
- fix(DB): Fix Some Gnomeregan Issues - Missing Animations, Spells and Texts (#4617)
- refactor(Core): sort #includes alphabetically (#4579)

## 2021-02-23
- chore(git): Add a co-author suggestion to the commit template (#4538)

## 2021-02-21
- feat(Core/Hooks): OnBattlegroundDesertion (#4619)
- fix(Core/Spell): Divine Protection reduces fall damage (#4618)
- chore(DB): import pending SQL update file
- fix(DB/SAI): Captured Scarlet Zealot should die (#4616)
- chore(DB): import pending SQL update file
- fix(DB/Creature): Gubber-Blump-missing-gossip (#4615)
- chore(DB): import pending SQL update file
- fix(DB/Creature): Westfall Woodworker position (#4614)
- chore(DB): import pending SQL update file
- fix(DB/Quest): Plagued Lands (#4612)
- chore(DB): import pending SQL update file
- fix(DB/GameObject): Firework Launcher (#4597)
- chore(DB): import pending SQL update file
- fix(DB/Creature): Amani Berserker (#4594)
- chore(DB): import pending SQL update file
- fix(DB/Creature): Position NPC Rocklance (#4589)

## 2021-02-19
- fix(Scripts/MoltenCore): Garr abilities timers (#4568)
- fix(DB/MySQL): Support MySQL 8 in create_mysql.sql (#4492)

## 2021-02-18
- chore(DB): import pending SQL update file
- fix(DB/creature/quests): Remove Tormek Stoneriver and his quests (#4578)
- chore(DB): import pending SQL update file
- fix(DB/spell_dbc): column sizes & Life Tap descr. (#4545)

## 2021-02-17
- chore(DB): import pending SQL update file

## 2021-02-16
- fix(db/Creature): Darkshire NPC updates (#4588)

## 2021-02-17
- chore(DB): import pending SQL update file

## 2021-02-16
- fix(db): Translation to Ello Quest - Add Stitches Completion Event (#4523)
- chore(DB): import pending SQL update file
- fix(DB/creature_loot_template) Increase droprate for item Healthy Dragon Scale (#4516)
- chore(DB): import pending SQL update file
- fix(core/Scripts): 'The Attack!' Quest Improvements/NPC Spawn Adjust (#4577)

## 2021-02-15
- chore(DB): import pending SQL update file
- fix(db/smart_script): Fix Worldserver spam of smart_script errors (#4575)
- chore(DB): import pending SQL update file
- chore(DB/quest_offer_reward): Update capitalization of name/class (#4421)
- chore(DB): import pending SQL update file
- fix(db/GameObject): Adjust XYZ of Copper Vein (#4576)

## 2021-02-14
- chore(DB): import pending SQL update file
- Fix: pipeline error after 8 pending sql
- fix(DB/Spell): Make Amplify Magic Ranks 4-7 as Positive (#4567)
- chore(DB): import pending SQL update file
- Fix(DB/Trainer): Correct Polearm MinLvl Req (#4566)
- chore(DB): import pending SQL update file
- fix(DB/creature): Ham from Reese Langston position (#4564)
- chore(DB): import pending SQL update file
- Ras Frostwhisper movement (#4517)
- chore(DB): import pending SQL update file
- fix(DB/quest_details): Add missing emotes for Maybell Maclure when offering quest Young Lovers (#4558)
- chore(DB): import pending SQL update file

## 2021-02-13
- fix(DB/Creature): Script Master Wood Emotes and Responses (#4560)

## 2021-02-14
- chore(DB): import pending SQL update file
- fix(DB/gameobject): Improve quest Fields of Grief (#4529)
- chore(DB): import pending SQL update file

## 2021-02-13
- fix(db/creature): Add missing npc text for William Pestle (#4559)

## 2021-02-14
- chore(DB): import pending SQL update file
- Improve quest Of Love and Family (#4501)
- chore(DB): import pending SQL update file

## 2021-02-13
- fix(DB/creature): Update Old Blanchy Faction & Add Missing Text for Verna Furlbrow
- chore(DB): import pending SQL update file
- fix(DB/npc_text): Various Missing NPC Gossip
- chore(DB): import pending SQL update file
- fix(DB/gameobject): Improve quest Barov Family Fortune (#4500)
- chore(DB): import pending SQL update file
- Improve raid quest Keanna's Log (#4502)
- fix(Core/SAI): Do not reset HP with SMART_ACTION_UPDATE_ENTRY (#4486)
- chore(DB): import pending SQL update file
- fix(DB/Item): Chinese locale (#4473)

## 2021-02-12
- chore(DB): import pending SQL update file
- feat(Core/Conf): Rate.RewMoneyMaxLevel (#4546)
- fix(DB/quest): Rogue quest Encrypted Scroll (#4553)
- fix(DB/gameobject) Strange lockbox position and add Bubbly Fissure (#4460)
- chore(DB): import pending SQL update file
- fix(DB/gameobject): pooling for Battered Chests in starting zones (#4552)
- chore(DB): import pending SQL update file
- fix(DB/creature): Move Undertaker Mordo (#4548)
- chore(DB): import pending SQL update file
- fix(DB/creature): Move Megelon (#4539)
- chore(DB): import pending SQL update file
- fix(DB/waypoint): Thomas Miller text (#4534)
- fix(Core): loot party (#4409)
- chore(DB): import pending SQL update file
- fix(Core): creature movement bugs (#4544)

## 2021-02-11
- Revert "feat(CI): use acore-core-build-action (#4326)" (#4543)
- fix(DB/updates): faulty SQL update
- chore(DB): import pending SQL update file
- fix(Core/Spell): solve issue with Life Tap All Ranks (#4408)
- chore(DB): import pending SQL update file

## 2021-02-10
- fix(DB/Creature): Set MovementType of Scourged Flamespitter to 'Idle' (#4525)
- fix(Core/Script): Startup error in spell_bwl_shadowflame (#4474)
- chore(DB): import pending SQL update file
- fix(DB/Spell): remove NPC curse (#4477)
- chore(DB): import pending SQL update file
- Improve quest The Active Agent (#4454)
- chore(DB): import pending SQL update file
- fix(DB/gameobject): Improve quests Find the Gems and Power Source & Find the Gems (#4450)
- chore(DB): import pending SQL update file
- fix(DB/command): remove bank command (#4515)
- fix(Core/Pathfinding): Creatures regen health, spells LOD (#4509)

## 2021-02-09
- chore(DB): import pending SQL update file
- Improve quest Rig Wars (#4453)
- feat(Hooks/PlayerScript): ShouldBeRewardedWithMoneyInsteadOfExp  (#4445)
- chore(DB): import pending SQL update file
- ValianceKeepUpdates (#4511)
- chore(DB): import pending SQL update file
- Improve quest Rituals of Power (#4449)
- chore(DB): import pending SQL update file
- Improve paladin quest The Test of Righteousness (#4443)
- chore(DB): import pending SQL update file
- Improve quest Knowledge in the Deeps (#4438)
- refactor(Core/Spell): Pascal Case some SpellEntry types (#4432)

## 2021-02-08
- chore(DB): import pending SQL update file

## 2021-02-09
- Improve quest Test of Lore (#4442)

## 2021-02-08
- chore(DB): import pending SQL update file
- fix(DB/Commands): align core and DB (#4479)
- refactor(Core/Player): add helper method for PLAYER_FLAGS_DEVELOPER (#4395)
- chore(DB): import pending SQL update file
- fix (DB/Commands): Add Syntax to Command .achievement checkall (#4506)
- chore(DB): import pending SQL update file
- fix(DB/Quest): Incorrect requirements for quest: 'A Spark of Hope' (#4434)
- chore(DB): import pending SQL update file
- refactor(DB/Creature): Move some Lunar auras from SAI to c_t_a (#4393)
- chore(DB): import pending SQL update file
- fix(DB/Spawn): move outside a tree a rabid bear (#4480)
- chore(DB): import pending SQL update file
- fix(DB/Event): Attempt to resolve STV Fishing Extravagnaza spawns and start (#4482)

## 2021-02-07
- chore(DB): import pending SQL update file
- Deserter Propaganda should respawn much faster (#4414)
- fix(Core/Spell): Restore Stealth remove check (#4491)
- Fix Bug(cpp): SmartScriptMgr.cpp - Event Start and Stop not working (#4392)
- chore(DB): import pending SQL update file
- fix(DB/Gamobject): Remove deprecated signs (#4390)
- chore(DB): import pending SQL update file
- fix(DB/Creature): Remove skinning from non-skinnable creatures (#4475)
- chore(DB): import pending SQL update file
- fix(Core/Spell): Restore SPELL_ATTR0_CU_AURA_CC (#4472)
- fix(Core/Spell): Clearcasting duration (#4422)
- fix(Core/Pathfinding): pets chase & transport (#4451)

## 2021-02-06
- chore(DB): import pending SQL update file
- Improve quest The Lost Tablets of Will (#4452)
- chore(DB): import pending SQL update file
- Fix quest Secondhand Diving Gear respawn rates (#4419)
- chore(DB): import pending SQL update file
- fix(DB/quest_request_items): Remove text that is set as null (#4385)
- chore(DB): import pending SQL update file
- Improve quest Mythology of the Titans (#4439)
- chore(DB): import pending SQL update file
- fix(DB/gameobject): Double stacked veins in Stranglethorn Vale (#4433)
- chore(DB): import pending SQL update file
- fix(DB/Item): Foreboding Plans text (#4386)
- chore(DB): import pending SQL update file
- Lower respawn for New Avalon Registry (#4428)

## 2021-02-05
- chore(DB): import pending SQL update file

## 2021-02-06
- refactor(Core/Spell): Move some SpellImmune from script to db (#4381)

## 2021-02-05
- chore(DB): import pending SQL update file
- Lower respawn for Empty Cauldron and Iron Chain (#4427)
- chore(DB): import pending SQL update file
- Lower respawn for New Avalon Patrol Schedule (#4426)
- chore(DB): import pending SQL update file
- fix(DB/Creature): Add missing auras for some Icecrown creatures (#4394)
- fix(Core/Commands): remove character creation flag from .save command
- fix(Bash/DB-Exporter): typo (#4376)
- fix(Core/Player): Prevent looting already looted items (#4420)
- chore(DB): import pending SQL update file
- fix(DB/Creature): Remove clam loot from non-sea creatures (#4384)

## 2021-02-04
- chore(DB): import pending SQL update file
- fix(DB/Item): Venture Co. Documents text (#4387)
- chore(DB): import pending SQL update file
- fix(DB/Creature): Update Mutaded Professor Putricide hitbox (#4382)
- fix(Docker): add cache to dockerignore to speed up local build  (#4366)
- chore(DB): import pending SQL update file
- fix(DB/Item) Flamewrought Key zhCN translation (#4365)
- chore(DB): import pending SQL update file
- fix(DB/Quest): Journey to Undercity outro (#4389)

## 2021-02-03
- chore(DB): import pending SQL update file

## 2021-02-04
- fix(DB/gameobject): Book of Ur should be lootable by all (#4362)

## 2021-02-03
- chore(DB): import pending SQL update file
- fix(DB/gameobject): Compendium of the Fallen should be lootable by all (#4360)
- fix(Core/Spell): SPELL_EFFECT_TELEPORT_UNITS_FACE_CASTER to face caster (#4351)
- fix(DB): bad sql syntax
- chore(DB): import pending SQL update file
- fix(DB/Creature): Tender Strider Meat chance increase /  icon for Refurbished Steam Tank (#4250)
- chore(DB): import pending SQL update file
- feat(DB/Waypoint): improve Princess and companions movements (#4397)
- chore(DB): import pending SQL update file
- feat(DB/SAI): murloc fear when Mmmrrrggglll die (#4391)
- chore(DB): import pending SQL update file
- feat(Core/Creature): implement c_t->spell_school_immune_mask (#4358)
- chore(DB): import pending SQL update file
- fix(DB/Creature): Add spirit healer to gy 1318 (#4371)
- chore(DB): import pending SQL update file
- fix(DB/Creature): Lunar Festival Harbinger gossip (#4383)
- refactor(Core/Config):  Change PlayerStart.AllSpells to .CustomSpells (#4345)

## 2021-02-02
- chore(DB): import pending SQL update file
- fix(DB/Quest): wrong quest chain order (#4320)
- chore(DB): import pending SQL update file
- fix(Core/Spell): Instant Statue (#4319)
- feat(Core/Conf): toggle XP price (#4388)

## 2021-02-01
- feat(CI): use acore-core-build-action (#4326)
- chore(DB): import pending SQL update file

## 2021-02-02
- fix(DB/Creature): Convert npc_anchorite_truuen to sai (#4324)

## 2021-02-01
- chore(DB): import pending SQL update file
- fix(DB/gameobject): The Damaged Chest quest Tome of the Cabal should respawn right away (#4321)
- chore(DB): import pending SQL update file
- fix(DB/gameobject): The Scarlet Key should be lootable by all (#4317)
- chore(DB): import pending SQL update file
- fix(DB/gameobject): Move location of Chest of The Seven in BRD (#4315)
- feat(Core/Spell): Implement ValidateSpellInfo (#4323)
- chore(DB): import pending SQL update file
- fix(DB): missing Lunar Festival GOs and creatures (#4367)
- chore(DB): import pending SQL update file
- feat(DB/SAI): lunar festival invitation teleport (#4354)
- chore(DB): import pending SQL update file
- fix(DB/gameobject): Core Fragment should not despawn (#4311)
- fix(Core/Spell): Detect Undead (#4310)
- feat(Core/Movement): Improved pathfinding, collisions and movements (#4220)

## 2021-01-31
- refactor(Core/Spell): Define some unknown spell attributes (#4305)
- chore(DB): import pending SQL update file
- fix(Core/SpellMgr): Add cooldown to some vehicle spells (#4300)
- fix(Core/Spell): improve check in SPELL_EFFECT_CREATE_ITEM(_2) (#4296)
- chore(DB): import pending SQL update file
- fix(Core/Scripts): Blackwing Lair overhaul (#3673)

## 2021-01-30
- refactor(Core/LoginDatabase): LOGIN_DEL_ACCOUNT_MUTEDEL -> LOGIN_DEL_ACCOUNT_MUTED (#4281)
- fix(CI/macOS): solve ccache issue (#4378)

## 2021-01-29
- chore(DB): import pending SQL update file

## 2021-01-30
- fix(Core/Item): Implement mount speed mod items (#4258)

## 2021-01-29
- fix(Core/Quest): A Tangled Skein (#4237)
- fix(Core/Tets): Removed duplicated mock method (#4219)

## 2021-01-28
- chore(DB): import pending SQL update file
- fix(DB/Quest): location for quest 9589 & 9590 (#4204)
- fix(Bash): db-export on macOS (#4342)
- fix(Bash): Improve db_export script (#4350)

## 2021-01-27
- chore(DB): import pending SQL update file
- feat(DB/locales): Import deDE locales (Part 16) (#4194)
- fix(Core/Spell): do not create new items when inventory is full (#4298)
- feat(Core/PvPstats): top players of the month (#4353)
- chore(DB): import pending SQL update file
- fix(DB/Quest): Missing Event on questId (1020, 1033, 1034, 1035) (#4201)

## 2021-01-26
- fix(Core/Spell): Glyph apply bonus (#4206)
- docs(SECURITY.md): rebrand supported dependencies (#4334)
- chore(DB): import pending SQL update file
- fix(Core/Creature): Implement CREATURE_FLAG_EXTRA_NO_SELL_VENDOR (#4233)
- fix(DB/updates): fix chain (2) (#4349)

## 2021-01-25
- chore(DB): import pending SQL update file

## 2021-01-26
- fix(DB/updates): fix chain (#4347)

## 2021-01-25
- fix(Core/Creature): Move CREATURE_FLAG_EXTRA_IMMUNITY_KNOCKBACK (#4232)
- chore(Core/Global): Fix grouping of Worldserver initialization (#4130)
- release: DB squash & begin AC 4.0.0 development (#4341)
- chore(DB): import pending SQL update file
- release: AzerothCore 3.0.0 (#4339)
- chore(Core/PathGenerator.h): Kill Malformed whitespace (#4289)

## 2021-01-24
- chore(DB): import pending SQL update file
- fix(DB/Creature): King Magni Bronzebeard combat script (#4292)
- chore(DB): import pending SQL update file
- fix(DB/Graveyard): Add Horde graveyards in Darkshore (#4322)
- chore(DB): import pending SQL update file
- fix(DB/Creature): faction of ravenoak (#4229)
- feat(CI): deprecate gcc 7 (#4333)

## 2021-01-23
- fix(gcc): type warning [1/2] (#4332)
- chore(DB): import pending SQL update file
- fix(Core/Spell): Paralytic Poison (#4128)

## 2021-01-22
- fix(CI): temp restore ci-install.sh (#4325)
- chore(DB): import pending SQL update file
- fix(Core): Activate creatures and objects during opening cinematics (#4045)

## 2021-01-21
- chore(DB): import pending SQL update file

## 2021-01-22
- fix(DB/Quest): improve quest poi for some quests (#4120)

## 2021-01-21
- chore(DB): import pending SQL update file
- fix(DB/spell_area): remove spell 57940 on area 480 (#4119)
- chore(CI): Improve error message of check_pending_sql (#4081)

## 2021-01-20
- feat(Core/Config): allow initial (free) amount of Guild Bank tabs (#4290)
- chore(DB): import pending SQL update file
- fix(DB/Waypoint): Hezrul Bloodmark (#4245)
- chore(DB): import pending SQL update file
- feat(DB/locales): Import deDE locales (Part 15) (#4064)
- chore(DB): import pending SQL update file
- feat(DB/locales): Import deDE locales (Part 14) (#3986)
- fix(Core/QuestTracker): do not store quest if quest_id is null (#4027)

## 2021-01-19
- chore(DB): import pending SQL update file
- fix(DB/Creature): Gyromasts Revenge (#4115)
- chore(DB): import pending SQL update file
- fix(DB/locale): Spanish translation quests in elwynn forest (#3870)
- chore(DB): import pending SQL update file
- fix(DB/locale): Spanish translation for Death Knight quests (#3563)

## 2021-01-18
- chore(DB): import pending SQL update file

## 2021-01-19
- refactor(Core/cs_reload): Improve page_text(_locale) output (#3115)

## 2021-01-18
- feat(Core/Opcodes): Implement CMSG_CHANNEL_MODERATE (#4021)
- chore(DB): import pending SQL update file
- fix(Core/Creature): Implement INHABIT_ROOT (#4141)
- chore(DB): import pending SQL update file
- feat(DB/Translations): import translation text from @mpfans (#4088)
- chore(DB): import pending SQL update file
- feat(DB/locales): import locales from TC (#4125)

## 2021-01-17
- fix(Core/SpellMgr): Essence of Wintergrasp only applies if config is enabled (#4110)
- chore(DB): import pending SQL update file
- feat(Core/Warden): optimization + PQR detection (#3875)
- chore(DB): import pending SQL update file
- feat(DB/game_tele): Hidden Places (#3878)
- chore(DB): import pending SQL update file
- fix(DB/creature): Remove WotLK recipe drops from Vanilla NPC Sorrow Wing (#4285)
- chore(DB): import pending SQL update file

## 2021-01-16
- airmanskyhomie (#4251)

## 2021-01-17
- fix(Scripts/boss_freya): adds apply SPELL_CONSERVATOR_GRIP 6s after spawn (#4082)
- fix(Core/Spell): Killing Spree range (#4097)

## 2021-01-16
- fix(Core/SpellMgr): Death Plague stacks (#4299)
- feat(Core/Player): implement GetFreeInventorySpace() (#4297)
- chore(DB): import pending SQL update file
- fix(DB/Quest): Taken by the Scourge (#4079)
- feat(Core/Conf): allow to change the cost of the guild bank tabs (#4240)
- chore(DB): import pending SQL update file
- feat(DB/game_tele): Improve GM Teleports (#3873)

## 2021-01-15
- fix(Docker): binary update on rebuild (#4279)
- chore(DB): import pending SQL update file

## 2021-01-16
- fix(DB/Creature): Ethereal Priest Power-Shield Spam (#4073)

## 2021-01-15
- fix(CI): disable macos-11.0 (#4283)
- chore(2021_01_14_01.sql): int not string (#4280)

## 2021-01-14
- chore(DB): import pending SQL update file

## 2021-01-15
- feat(DB/locales): Import deDE locales (Part 13) (#3858)

## 2021-01-14
- fix(Core/CreatureAI): revert NPC repositioning and path system (temporarily) (#4274)
- chore(DB): import pending SQL update file
- fix(Scripts/DB/Creature): Set PvP flag for some creatures (#4270)
- chore(DB): import pending SQL update file
- fix(DB/Quest): Shadow Vault Decree (#4075)

## 2021-01-13
- chore(DB): import pending SQL update file
- fix(DB/Creature): Civilian Recruit Valiance Keep (#4071)
- chore(IssueTemplate/BugReport): Fix typo (#4199)
- chore(DB): import pending SQL update file
- fix(DB/loot_template): Fill in comment fields (#4063)

## 2021-01-12
- chore(DB): import pending SQL update file
- feat(DB/locales): Import deDE locales (Part 12) (#3853)
- refactor(Core): fix some warnings from VS (#4049)
- chore(DB): import pending SQL update file
- fix(Core/The Oculus) Drakos dragon keepers (#3531)
- chore(ReadME): Add codefactor (#4260)

## 2021-01-11
- fix(Build/Cmake): CMake now uses the Windows env vars (#3419)
- refactor(db_assembler): Allow connecting to non default mysql ports (#3123)
- chore(Core/SpellAuraEffects): Comment out empty if (#4246)

## 2021-01-10
- chore(DB): import pending SQL update file
- fix(DB/Creature): Fix Borean Tundra Footmans (#4069)
- chore(core): Remove malformed whitespace (#4248)
- chore(core): remove malformed whitespaces (#4244)
- fix(Core/Opcodes): Implement CMSG_GROUP_SWAP_SUB_GROUP (#4020)

## 2021-01-09
- chore(DB): import pending SQL update file
- fix(DB/gossip_menu_option): Give me a bomber! (#3830)
- feat(CI/Ubuntu): use acore.sh to install deps (#4042)
- chore(CI/codestyle): fix build (#4241)
- chore(DB): import pending SQL update file
- fix(DB/Script): Quest Re-Cursive (#3220)
- feat(CI/Codestyle): added codestyle check (#3668)
- chore(DB): import pending SQL update file
- fix(DB/Graveyard): add ghostZone for zone 3479 (#4224)

## 2021-01-08
- fix(Core/Spell): [Potion] Elixir of Minor Fortitude effect disappear (#4217)
- chore(DB): import pending SQL update file
- fix(Core/Spell): Earthliving weapon proc (#4015)
- fix(Core/Crash): safe calculation in GetMeleeAttackPoint (#4235)
- chore(DB): import pending SQL update file
- fix(scripts/instance): Force correct gossip/text updates (#3838)
- fix(CI/MacOS) workaround for configure os failing (#4234)

## 2021-01-07
- fix(Core/ArenaTeam): Arena team queue protections (#3803)
- fix(DB/Update): fix missing delete (#4231)
- chore(DB): import pending SQL update file
- fix(DB/SmartAI): Demolitionist Legoso weird behavior (#4211)
- chore(DB): import pending SQL update file
- fix(DB/Creature): Laris Geardawdle (9616) missing text (#4134)

## 2021-01-06
- chore(DB): import pending SQL update file
- fix(DB/Creature): Guvan (npc 17482) incorrect NPC flags (can't train priests past lvl 6) (#4138)
- chore(DB): import pending SQL update file
- fix(DB/Creature): position of guid 17952 (#4117)

## 2021-01-05
- chore(DB): import pending SQL update file
- fix(DB/Creature): Ranger Lilatha walk speed correction  (#4114)

## 2021-01-04
- chore(DB): import pending SQL update file
- fix(DB/Quest): "Botanist Taerix" and "Urgent Delivery!" (#4111)
- chore(DB): import pending SQL update file
- fix(Core/Creature): Implement CREATURE_FLAG_EXTRA_GHOST_VISIBILITY (#4129)
- feat(Core/CreatureAI): improve npc position during the combat (#3369)
- chore(DB): import pending SQL update file
- fix(DB/Creature): Shadowglen Webwood Spiders Population (#4135)
- chore(DB): import pending SQL update file
- fix(DB/smart_scripts): Add abilities to Arcanist Torseldori and Bloodmage (#4052)

## 2021-01-03
- chore(DB): import pending SQL update file
- fix(DB/Visual): The Sun Gate (#4100)
- chore(DB): import pending SQL update file
- fix(DB/creature): Add female models to Chosen Zealots (#4054)
- chore(MySQL): Deprecate 5.6 (#4070)

## 2021-01-02
- chore(DB): import pending SQL update file
- fix(DB/Creature): Engineer "Spark" and Geezle (#4089)
- chore(DB): import pending SQL update file
- fix(DB/Quest): Galaen's Fate (#4080)

## 2021-01-01
- chore(DB): import pending SQL update file
- fix(DB/gameobject): adjust spawntimesecs of multiple GOs (#4062)
- fix(Core/Quest): They're Alive! Maybe... (#4035)

## 2020-12-31
- chore(DB): import pending SQL update file
- fix(DB/Quest) add missing quest to brewfest npc's (#3511)
- chore(DB): import pending SQL update file
- feat(DB/translations): import quest_template, quest_request_items and quest_offer_reward from TC (#4068)

## 2020-12-30
- fix(CI): Only run macos build if ubuntu build is successful (#4044)
- refactor(Core/sWorld): improve singleton management (#3862)
- chore(DB): import pending SQL update file

## 2020-12-29
- fix(DB/quest): Thalorien Dawnseeker - Quest texts (#3852)
- chore(DB): import pending SQL update file
- fix(DB/Creature): add/fix spawns in Ghostlands & Eversong Woods (#4067)
- fix(DB/Loot): drop chances for white items in starter zone (#4047)

## 2020-12-28
- chore(Core/Conf): Change default of RecordUpdateTimeDiffInterval (#4033)
- chore(DB): import pending SQL update file
- fix(DB/acore_string): Adjust characters for pinfo (#4032)
- fix(dashboard): check if acore user already exists (#4034)
- fix(Core/GO): failed attempt (#4036)
- chore(DB): import pending SQL update file
- fix(DB/gameobject): Quest 'Soaked Pages' GO respawn time (#4061)

## 2020-12-27
- chore(DB): import pending SQL update file
- fix(DB/acore_string): Remove weird spaces in npc info (#4031)
- chore(DB): import pending SQL update file
- fix(DB/creature_template): Add mechanic_immune_mask for Hyjal bosses (#4029)
- chore(DB): import pending SQL update file
- fix(DB/smart_scripts): Script "Crowleg" Dan (#4030)
- chore(Core/SpellMgr): Indentation (#4028)

## 2020-12-26
- chore(DB): import pending SQL update file
- fix(DB/game_event_gameobject): Brewfest gameobject in Winter Veil (#4026)
- fix(scripts/Felmyst): Adjust beam target (#4055)
- fix(Core/Object): Fix small error in Position::IsWithinBox (#4050)

## 2020-12-25
- fix(scripts/Ulduar): Kologarn - Focused Eyebeam (#3529)
- chore(DB): import pending SQL update file
- fix(scripts/Ulduar): Expedition Base Camp (#3558)
- fix(CI): update procedure/function check (#4046)

## 2020-12-24
- fix(Core/Guild): Implement gender in guild (#4017)
- refactor(scripts/BlackrockMountain): Remove commented NPC scripts (#3229)
- chore(DB): import pending SQL update file
- fix(DB/broadcast_text_locale): Guard gossip for hunter class [esES/esMX] (#3572)
- chore(DB): import pending SQL update file
- fix(DB/Spell): Clearcast proc (#4014)
- chore(config): Improve dist files (#3989)

## 2020-12-23
- fix(apps/scripts): Add quotes for directory paths containing empty spaces (#3716)
- refactor(Core): Remove player title defines (#2781)

## 2020-12-22
- fix(Core/Spell): Clicking lock portal cost mana (#4013)
- feat(CI/MacOS): use acore.sh to install deps (#4003)
- fix(Bash/simple-restarter): always show the correct command name (#3996)
- Core/Utils: Create std::optional helper class (#3994)

## 2020-12-21
- fix(README): catalogue link (#4023)
- docs: add sponsor link (#3987)
- refactor(Core): removed unused ace includes (#3874)
- docs(PR-template): normalized captions #3867
-  docs(README.md): normalized captions #3863
- feat(Core): Another way to get talent points (#3773)

## 2020-12-19
- fix(scripts/CullingOfStratholme): Remove "Corrupting Blight" at Infinite Corruptor's death (#4011)
- fix(scripts/Oculus): Reset Mage-Lord Urom's position at death (#4012)
- chore(DB): import pending SQL update file

## 2020-12-18
- fix(DB/creature): Improve starting NPCs (#4010)
- chore(DB): import pending SQL update file
- fix(DB/npc_vendor): Argent Tournament (#3847)
- chore(DB): import pending SQL update file
- fix(DB/Quest): Make 6962 not repeatable (#4004)
- chore(DB): import pending SQL update file
- fix(DB/item_template_locale): Item Description deDE (#3845)
- refactor(Core): apply clang-tidy modernize-raw-string-literal (#3824)

## 2020-12-17
- feat(CI/macOS): add macos-11.0 Big Sur to CI build (#4001)
- fix(CI/macOS): remove old openssl removal (#3998)

## 2020-12-16
- chore(DB): import pending SQL update file
- fix(DB/quest_poi_points): Fix The Battered Hilt Questline (#3844)

## 2020-12-15
- chore(DB): import pending SQL update file
- fix(DB/smart_scripts): Quest "Enlistment Day" (#3725)
- feat(Bash/restarter): add restarter to the available bin/ collection (#3991)
- fix(Bash/installer): client data version (#3992)

## 2020-12-14
- refactor(Core/Social): Cleanup (#3843)
- chore(DB): import pending SQL update file
- fix(DB/spell_custom_attr):  Debuffs incorrectly applied as buffs (#3798)

## 2020-12-13
- chore(DB): import pending SQL update file
- feat(DB/locales): Import deDE locales (Part 11) (#3842)
- chore(DB): import pending SQL update file
- fix(DB/Quest): Text for quest "When the Cows Come Home" (#3840)
- chore(DB): import pending SQL update file
- fix(DB/waypoint_data): Great Hexer Ohodo pathing (#3839)
- fix(Core/conf): Battleground kill XP rate description (#3833)
- chore(DB): import pending SQL update file
- feat(DB/locales): Import deDE locales (Part 10) (#3829)
- chore(DB): import pending SQL update file
- fix(DB/creature_template): Improve The Nexus (#3542)
- refactor(Core): apply clang-tidy modernize-pass-by-value (#3823)

## 2020-12-12
- fix(Core): a typo introduced in the Rest & Inn Improvements (#3985)
- chore(ReadMe): Add Discussions (Forum) to important links (#3980)
- refactor(Core): apply clang-tidy modernize-deprecated-headers (#3821)
- feat(Core/Config): Arena points - Games required (#3811)

## 2020-12-11
- chore(DB): import pending SQL update file
- fix(DB/item_template_locale): Twisted Reflection item description (#3808)
- chore(DB): import pending SQL update file
- feat(DB/locales): Import deDE locales (Part 09) (#3807)
- chore(DB): import pending SQL update file
- fix(DB/creature_template_addon): Add 'Shadowform' aura to Saronite Animus (#3805)
- chore(DB): import pending SQL update file
- fix(DB/access_requirement): Add missing quest_failed_text #3804
- fix(Core/Game): Rest & Inn Improvements (#3780)

## 2020-12-10
- chore(DB): import pending SQL update file
- fix(DB/smart_scripts): Ulduar- Iron Mender casting Fuse Metal out of combat #3802
- chore(DB): import pending SQL update file
- fix(DB/creature): Ulduar 25 Antechamber trash pack #3800
- chore(DB): import pending SQL update file
- fix(DB/creature_loot_template): Quest item drop chance - 'Guardian of the Monument' #3796
- chore(DB): import pending SQL update file
- fix(DB/creature_template): Improve damage (#3561)
- chore(DB): import pending SQL update file
- fix(DB/creature_template): Improve Ulduar (#3555)
- chore(DB): import pending SQL update file
- fix(DB/creature_template): Improve Utgarde Keep (#3540)

## 2020-12-09
- chore(DB): import pending SQL update file
- fix(DB/creature_template): Improve The Oculus (#3541)
- chore(DB): import pending SQL update file
- fix(DB/creature_template): Improve Utgarde Pinnacle (#3539)

## 2020-12-08
- chore(Core): forgot to add copyright in new files + small correction (#3861)
- refactor(Core): apply clang-tidy modernize-use-bool-literals (#3826)

## 2020-12-07
- fix(CMake): Deprecation warning #3814
- refactor(Core): apply clang-tidy modernize-use-default-member-init (#3827)
- refactor(Core): apply clang-tidy modernize-use-equals-default (#3834)
- refactor(Core): apply clang-tidy modernize-loop-convert (#3822)
- refactor(Core): apply clang-tidy modernize-use-emplace (#3828)
- chore(DB): import pending SQL update file
- fix(DB/creature_template): Improve Onyxia Lair (#3537)
- chore(DB): import pending SQL update file
- fix(DB/creature_template): Improve Vault of Archavon (#3536)
- refactor(Core/PetAI): remove useless code (#3836)

## 2020-12-06
- refactor(Core): apply clang-tidy modernize-use-noexcept (#3837)
- refactor(Core): apply clang-tidy modernize-redundant-void-arg (#3825)
- refactor(Core): apply clang-tidy modernize-use-nullptr (#3819)
- refactor(Core): apply clang-tidy modernize-use-nodiscard (#3835)
- refactor(Core): apply clang-tidy modernize-use-override (#3817)
- refactor(Core/sLog): improve singleton management (#3801)
- chore(DB): import pending SQL update file
- fix(DB/Raid): improved Eye of Eternity (#3538)

## 2020-12-05
- chore(DB): import pending SQL update file
- fix(DB/creature_template): Improved Obsidian Sanctum (#3535)
- chore(DB): import pending SQL update file
- fix(DB/creature_formations): Elite patrolling positions (#3795)
- chore(DB): import pending SQL update file
- fix(DB/creature): Respawn time secs (#3794)

## 2020-12-04
- fix(Scripts/Ulduar): Yogg-Saron's portals (#3810)
- chore(DB): import pending SQL update file
- fix(DB/smart_scripts): Improve - Stitched Giant (#3812)
- chore(DB): import pending SQL update file
- fix(DB/creature): Improve - The Battle For The Ebon Hold (#3797)
- chore(DB): import pending SQL update file
- feat(DB/locales): Import deDE locales (Part 08) (#3792)
- fix(Core/Social): cleanup + fix crash in friend system (#3832)

## 2020-12-03
- chore(DB): import pending SQL update file
- fix(DB/creature_template): Adjust levels for Snobold Vassal and Saronite Animus (#3787)
- chore(DB): import pending SQL update file
- fix(DB/smart_scripts): Open door on Sneed's death (#3786)
- chore(DB): import pending SQL update file
- feat(DB/locales): Import deDE locales (Part 07) (#3775)
- chore(DB): import pending SQL update file
- fix(DB/Instance): Fix equip issue and text errors (#3771)

## 2020-12-02
- fix(bin/scripts): Allow script work with git bash (#3841)
- chore(DB): import pending SQL update file
- feat(DB/locales): Import deDE locales (Part 06) (#3766)
- chore(DB): import pending SQL update file
- feat(DB/locales): Import deDE locales (Part 05) (#3761)

## 2020-12-01
- chore(DB): import pending SQL update file
- feat(DB/locales): Import deDE locales (Part 04) (#3751)
- fix(Core/Pathfinding): Improve - Point movement (#3658)
- fix(Deps/Acelite): add missing Windows dependency (#3816)

## 2020-11-30
- chore(DB): import pending SQL update file
- fix(DB/creature_template): Remove skull level on dungeon bosses (#3750)
- chore(DB): import pending SQL update file
- feat(DB/locales): Import deDE locales (Part 03) (#3742)
- chore(DB): import pending SQL update file
- feat(DB/locales): Import deDE locales (Part 02) (#3738)
- feat(CMake): show version when running cmake (#3813)
- chore(DB): import pending SQL update file
- feat(DB/locales): Import deDE locales (Part 01) (#3732)

## 2020-11-29
- feat(Core/Script): Hooks for custom arena teams/types (#3508)
- test(Formulas.h): GetGrayLevel, GetColorCode, GetZeroDifference (#3734)
- chore(CMake/Tests): use conventional CMake flag to enable tests (#3809)
- chore(DB): import pending SQL update file
- fix(DB/Quest): Import "In Service of the Lich King" audio correct (#3748)

## 2020-11-28
- fix(ci): update semicolon check #3799
- chore(DB): import pending SQL update file
- fix(Scripts/ObsidianSanctum): Code revamp [1/2] (#3634)
- chore(DB): import pending SQL update file
- fix(DB/gossip): remove cataclysm gossip/gossip flag from Anduin Wrynn (#3717)
- chore(DB): import pending SQL update file
- fix(Scripts/ICC): Intro Event Timers and Text

## 2020-11-27
- fix(Scripts/VOA): code-style improvements + bandwidth consumptio (#3632)
- chore(DB): import pending SQL update file
- fix(Scripts/DB): Mimiron Computer NPC text (#3722)

## 2020-11-26
- fix(scripts/Ulduar): Assembly of Iron - interrupt immune effect (#3765)
- fix(scripts/Commands): Avoid get gm phase when summoning (#3764)

## 2020-11-25
- fix(ci): update semicolon check (#3767)
- chore(DB): import pending SQL update file
- fix(DB/creature): Starting zones (#3763)
- chore(DB): import pending SQL update file

## 2020-11-26
- fix(DB/creature): Delete duplicate Big Roy (#3755)

## 2020-11-25
- feat(CI): Add check for semicolon at end of pending sql update file #3749
- Revert "fix(Core/Player): Improve rested removal (#3715)" (#3762)

## 2020-11-24
- chore(DB): import pending SQL update file
- fix(DB/creature): Ulduar 25 extra trash packs (#3736)
- chore(DB): import pending SQL update file
- fix(DB/conditions): Fix quest Kibler's Exotic Pets (#3710)
- feat(Core/Config): Added pet experience rate (#3703)

## 2020-11-23
- chore(DB): import pending SQL update file
- fix(DB/spell_proc_event): The Black Heart (#3694)
- chore(DB): import pending SQL update file
- fix(DB/conditions): Frenzyheart Champion & Hand of the Oracles (#3691)
- refactor(Core): remove ACE types (#3745)
- feat(Core/Misc): remove ACE Auto_Ptr (#3454)

## 2020-11-22
- fix(DB): failure due to missing semicolumn (#3746)
- chore(DB): import pending SQL update file
- fix(DB/scripts): Freya - Sun beam (#3730)
- chore(DB): import pending SQL update file
- refactor(DB/player_factionchange_titles): Add comment section (#3138)

## 2020-11-21
- fix(Scripts): Ignis the Furnace Master - Iron construct buff stacks #3731
- fix(CI): make labeler work with UnitTests (#3735)
- refactor(Core/SpellMgr): simplify dbc data corrections (#3709)
- chore(DB): import pending SQL update file
- fix(DB/locales): Restore deleted quest locales (#3729)

## 2020-11-20
- feat(ci): Add apps directory to bash label (#3721)

## 2020-11-19
- refactor(Apps/Defines): Codefactor warning (#3714)
- fix(Core/Player): Improve rested removal (#3715)

## 2020-11-18
- fix(Core/bin): Add quotes to pwd in docker build scripts (#3701)
- fix(Core/SpellMgr): Thorns should not miss (#3695)
- chore(DB): import pending SQL update file
- feat(DB/locales): Import deDE quest locales (#3692)
- refactor(Tools): restyle tools with astyle (#3705)

## 2020-11-17
- chore(DB): import pending SQL update file
- fix(DB/creature_loot_template): Emblem of Triumph #3689
- feat(Core/Config): configurable BG Respawn Timers (#3569)
- refactor(Core/Common): restyle tools with astyle (#3706)

## 2020-11-16
- chore(DB): import pending SQL update file
- fix(DB/creature): Maker's Overlook (#3686)
- chore(DB): import pending SQL update file
- fix(DB/gameobject): Dalaran Forge Spell Focus range (#3681)

## 2020-11-15
- chore(DB): import pending SQL update file
- fix(DB/creature): Rabid Brown Bear Position (#3667)
- chore(DB): import pending SQL update file
- fix(DB/quest_poi_points): Seeds of the Blacksouled Keepers Quest POI (#3663)
- chore(DB): import pending SQL update file
- fix(DB/quest_poi_points): The Fallen Sisters Quest POI (#3662)

## 2020-11-14
- chore(DB): import pending SQL update file
- fix(DB/creature) Frosthorn Ram Position (#3661)
- fix(Core/Command): additem - doesn't work when name contains apostrophe (#3647)
- fix(Core/Condition): Implement CONDITION_QUESTSTATE (#3049)
- fix(Core/Conditions): Implement CONDITION_DAILY_QUEST_DONE (#3050)
- feat(Core/MapUpdate): switch from ACE_Method_Request to PCQ (#3459)

## 2020-11-13
- fix(Core/Item): Meta gems sometimes ignore added sockets (#3643)
- feat(Core/Spells): Functions will return cast result (#3635)
- chore(DB): import pending SQL update file
- fix(DB/smart_scripts): Improved Classic Rares II (#3629)
- chore(DB): import pending SQL update file
- fix(DB/smart_scripts): Improved Hinterlands II (#3628)
- chore(DB): import pending SQL update file
- fix(DB/smart_scripts): Improved Hilsbrad Foothills (#3627)
- chore(DB): import pending SQL update file
- fix(DB/smart_scripts): Improved Silverpine Forest (#3626)
- chore(DB): import pending SQL update file
- fix(DB/smart_scripts): Improved Alterac Mountains (#3625)

## 2020-11-12
- chore(DB): import pending SQL update file

## 2020-11-13
- fix(DB/smart_scripts): Improved Arathi Highlands (#3624)

## 2020-11-12
- chore(DB): import pending SQL update file
- fix(DB/smart_scripts): Improved Dun Morogh (#3623)
- chore(DB): import pending SQL update file
- fix(DB/smart_scripts): Improved Wetlands (#3622)
- chore(DB): import pending SQL update file
- fix(DB/smart_scripts): Improved Badlands (#3621)
- fix(Labeler): revert CORE changes(#3683)
- chore(DB): import pending SQL update file
- fix(DB/smart_scripts): Improved Searing Gorge (#3620)
- chore(DB): import pending SQL update file
- fix(DB/smart_scripts): Improved Strangethorn Vale II (#3618)

## 2020-11-11
- chore(DB): import pending SQL update file
- fix(DB/smart_scripts): Improved Elwynn Forest (#3616)

## 2020-11-12
- feat(Core/Config): Improve config (#3453)

## 2020-11-11
- chore(Labeler): Workaround for CORE label (#3649)
- chore(Deps/Acelite): Update to 6.5.10 (#3450)
- fix(Docker): fix log files not being generated in Docker setups (#3680)
- chore(DB): import pending SQL update file
- feat(DB/locales) Import deDE quest locales from TrinityCore (#3666)
- chore(DB): import pending SQL update file
- fix(DB/smart_scripts): Improved Blasted Lands (#3617)

## 2020-11-10
- chore(DB): import pending SQL update file
- fix(DB/smart_scripts): Improved Westfall (#3615)
- chore(DB): import pending SQL update file
- fix(DB/quest_poi): A Portabale Power Source (#3576)
- feat(MMAPS/mapbuilder): restore ability to work with custom MapIDs >= 1000 (#3671)
- chore(DB): import pending SQL update file
- fix(DB/gameobject): The Codex of Blood (#3546)

## 2020-11-09
- chore(DB): import pending SQL update file
- fix(DB/smart_scripts): Improved Duskwood (#3614)
- chore(DB): import pending SQL update file
- fix(DB/creature_template) flags_extra for brewfest barker bunny's (#3505)
- fix(Core/Logs): Fix arguments in function call (#3672)
- chore(DB): import pending SQL update file
- fix(DB/gameobject_loot): Gordok Tribute (#3413)
- chore(DB): import pending SQL update file
- fix(DB/smart_scripts) Rachelle Gothena Position (#3651)
- chore(DB): import pending SQL update file
- fix(DB/creature/gameobject): Brother against brother (#3547)

## 2020-11-08
- chore(DB): import pending SQL update file
- fix(DB/smart_scripts): Improved redrige mountains (#3613)
- fix: broken link
- chore(DB): import pending SQL update file
- fix(DB/smart_scripts): Improved swamp of sorrows (#3612)

## 2020-11-07
- chore(DB): import pending SQL update file
- fix(DB/creature_template): Void Zone from Lady Blaumeux (#3637)
- fix(Core/Unit): ranged auto-attack sound issue if a player attacks target not in LOS (#3610)
- chore(DB): import pending SQL update file
- fix(DB/spelldifficulty_dbc): Fix Disrupting shout [10/25] (#3639)
- chore(DB): import pending SQL update file
- fix(DB/creature_template):  Fix Twilight Fissure (#3638)

## 2020-11-06
- chore(DB): import pending SQL update file
- fix(DB/smart_scripts): Improved loch modan (#3619)
- chore(DB): import pending SQL update file
- fix(DB/Zone):improved Burning Steppes (#3611)
- chore(DB): import pending SQL update file
- fix(DB/creature) Coilskar-Assasin Position (#3608)
- chore(DB): import pending SQL update file
- fix(DB/waypoint_data): Ulduar Colossus path fix (#3601)

## 2020-11-05
- chore(DB): import pending SQL update file
- fix(DB/creature) Light's Hope Muradin/Saurfang Wrong Models (#3600)
- fix(Core/CS): Fixed learn command using null session when send over SOAP (#3595)
- feat(CI): check if pending sql has procedure or function  (#3596)

## 2020-11-04
- chore(DB): import pending SQL update file
- fix(Script/ICC): Spirit Alarm and Deathbound Ward (#3592)
- chore(DB): import pending SQL update file
- fix(DB/creature_template): Ulduar - Overload (#3590)
- fix(Scripts/Ulduar): Supercharge stack issue fix (#3586)

## 2020-11-03
- fix(Core/Ulduar): Stone Nova stacks [25 mode]
- fix(Scripts/Ulduar): Boss XT-002 enrage sound
- chore(DB): import pending SQL update file
- fix(DB/Creature): Shandy Glossgleam (#3577)

## 2020-11-02
- chore(DB): import pending SQL update file
- fix(DB/Quest): The Black Box (#3575)
- fix(CI): do not run core_build on forks
- fix(Scripts/Ulduar): Hodir flash freeze safe spots
- chore(DB): import pending SQL update file
- fix(DB/Dungeon/Quest): Entry into Karazhan (#3545)

## 2020-11-01
- chore(DB): import pending SQL update file
- fix(DB/Quest): Rifle the Bodies (#3574)
- chore(DB): import pending SQL update file
- fix(DB/Zones):improved Tirisfal Glades (#3543)

## 2020-10-31
- chore(DB): import pending SQL update file
- fix(DB/Creature):improved Defender of Timbermaw (#3523)
- chore(DB): import pending SQL update file
- fix(DB/smart_scripts): Gordok Ogre-Mage (#3578)
- fix(Spell): Expose weakness (#3588)

## 2020-10-30
- chore(DB): import pending SQL update file
- fix(DB/Zones): improved missing & skipped some NPCs (#3518)
- chore(DB): import pending SQL update file

## 2020-10-29
- fix(DB/creature_template): Adjust Anub'arak minions level (#3525)

## 2020-10-28
- chore(DB): import pending SQL update file
- fix(DB/creature_template): Nerubian Burrower's immunity (#3513)
- chore(DB): import pending SQL update file
- fix(DB/Zone):improved Hinterlands (#3517)

## 2020-10-27
- chore(DB): import pending SQL update file
- fix(DB/Zone): improved Strangethorn Vale (#3516)
- chore(DB): import pending SQL update file
- fix(DB/creature_loot_template): Pattern: Fur Lining - Arcane Resist (#3522)

## 2020-10-26
- chore(DB): import pending SQL update file
- fix(DB/Zone): improved Western Plaguelands (#3515)
- chore(DB): import pending SQL update file
- fix(DB/Zone):improved Eastern Plaguelands (#3514)

## 2020-10-25
- chore(DB): import pending SQL update file
- fix(DB/SAI): Speaker Mar'grom (#3509)

## 2020-10-24
- fix(Core): fixed crash happening when clearing old mail (#3604)

## 2020-10-23
- feat(Core/Unit): don't allow additions threat in evade mode and implement AURA_INTERRUPT_FLAG_LEAVE_COMBAT (#3381)

## 2020-10-22
- chore(DB): import pending SQL update file
- fix(DB/Loot): Naxxramas 25 (#3512)

## 2020-10-21
- refactor(Core/Mail): avoid big mail loading/saving time, only load 50 mails at a time (#3420)
- fix(CI): add workaround for configure os (macos-10.15) (#3597)

## 2020-10-20
- fix: update labeler.yml (#3593)
- fix(Actions): Labeler (#3591)

## 2020-10-19
- fix(Action): Labeler (#3579)
- chore(DB): import pending SQL update file
- fix(DB/Creature): remove mobs from brewfest camp (#3497)
- chore(CI): fix Trailing spaces (#3481)

## 2020-10-17
- fix(Core/Util): EventMap::RepeatEvent when eventId is retrieved by ExecuteEvent() call (#3426)
- fix(Scripts/Ulduar): cast electrical charge only if player dies (#3480)

## 2020-10-15
- feat(Actions): Automatically add labels on PRs (#3571)
- chore(DB): import pending SQL update file
- fix(DB/Spell): make 38318 positive (#3474)

## 2020-10-14
- chore(DB): import pending SQL update file
- chore(DB/VerifiedBuild): Creatures 3.1.x(#3409)

## 2020-10-13
- fix(Core/Unit): Eating anim (#3472)

## 2020-10-12
- refactor(Core/Game): restyle game lib with astyle (#3466)

## 2020-10-11
- chore(DB): import pending SQL update file
- fix(DB/Event):  Brewfest - Synthebrew Goggles and Ram Racing Reins (#3502)
- refactor(Core/Scripts): restyle scripts lib with astyle (#3467)

## 2020-10-09
- fix(Core/Creature): dead creatures spawn position on respawn (#3382)

## 2020-10-08
- chore(DB): import pending SQL update file
- fix(DB/Creature): npc positions (#3376)

## 2020-10-07
- chore(DB): import pending SQL update file
- fix(Core/Boss): Toravon Script Mechanics (#2868)
- chore(DB): import pending SQL update file
- fix(DB): Resupplying the Excavation (#3471)

## 2020-10-06
- refactor(Tools): restyle tools with astyle (#3465)

## 2020-10-05
- feat(Core/Movement): added orientation input for Point movement (#3456)

## 2020-10-04
- fix(Core/Misc): fixed NOPCH build (#3448)

## 2020-10-03
- fix(Core/Script) npc Tom Hegger target player for aggro text (#3444)

## 2020-10-02
- fix(Issue/Config): correct links (#3423)

## 2020-10-01
- chore(DB): import pending SQL update file
- fix(DB): ICC Intro Event - Saurfang/Muradin MODELID (#3432)

## 2020-09-30
- chore(DB): import pending SQL update file
- fix(DB/Dungeon): Dire Maul West (#3412)

## 2020-09-29
- chore(DB): import pending SQL update file
- fix(DB/Dungeon): improved Upper Blackrock (#3414)

## 2020-09-28
- chore(DB): import pending SQL update file
- fix(DB/Dungeon): improved Dire Maul East (#3410)

## 2020-09-27
- fix(Core/Spells): prevent client crash on use spell Neural Needle + ESC (#3383)

## 2020-09-26
- chore(Core/Player): remove useless SendQuestComplete (#3380)

## 2020-09-25
- chore(DB): import pending SQL update file
- fix(DB/Quest): Post-partum Aggression (#3417)

## 2020-09-24
- chore(DB): import pending SQL update file
- fix(DB/Dungeon): improved Dire Maul North (#3411)

## 2020-09-23
- chore(DB): import pending SQL update file
-  fix(DB/Waypoint): npc guid 1021 path (#3366)

## 2020-09-22
- feat(Docker): add timezone settings to dockerfile (#3292)

## 2020-09-21
- fix(Core/PacketsIO): Send correct messages about server first achievements depending on faction. (#3379)

## 2020-09-20
- feat(Core/Events): update holiday code and remove misleading log (event date is the one from game_event) (#3365)
- feat(InstanceScripts): new scriptable function DoAction() (#3445)

## 2020-09-19
- feat(CI/macOS): improve caching level (#3493)
- chore(DB): import pending SQL update file
- chore(DB/VerifiedBuild): Items 3.1.x (#3408)
- chore(DB): import pending SQL update file
- fix(DB/Creature): faction of several creatures (#3339)

## 2020-09-18
- docs: Move README.md to .github folder (#3235)
- chore(DB): import pending SQL update file
- chore(DB/VerifiedBuild): Gameobjects 3.1.x (#3407)

## 2020-09-17
- feat(CI): add support for GCC (#3314)
- chore(DB): import pending SQL update file
- chore(DB/VerifiedBuild): Quests 3.1.x (#3406)

## 2020-09-16
- chore(DB): import pending SQL update file
- fix(DB/Event): Brewfest starttime (#3487)
- refactor(Travis): Remove unused travis files (#3364)
- chore(DB): import pending SQL update file
- fix(DB/Creature): Remove Noblegarden item from Redridge Mongrel (#3362)
- chore(DB): import pending SQL update file
- chore(DB/VerifiedBuild): Creatures 3.2.0 (#3405)

## 2020-09-15
- fix(Core/AuraScript): Soul Feast should apply on some Valithria mobs (#3355)
- chore(DB): import pending SQL update file
- fix(DB/Quest): gluttonous lurkers: improve the current SmartAI (#3341)
- chore(DB): import pending SQL update file
- chore(DB/VerifiedBuild): Quests 3.2.0 (#3403)

## 2020-09-14
- fix(Core/Misc): all GCC warnings (#3457)
- chore(DB): import pending SQL update file
- chore(DB/VerifiedBuild): Creatures 3.2.2 (#3402)

## 2020-09-13
- chore(DB): import pending SQL update file
- fix(DB/Quest): gameobject loot and related responsible spell script (#3340)
- chore(Core/Scripting): cleanup unused code (#3473)

## 2020-09-12
- fix(Scripts/Ulduar): Hodir Door (#3346)
- chore(DB): import pending SQL update file
- chore(DB/VerifiedBuild): Items 3.2.0 (#3404)
- fix(CI): do not run import-pending-sql on forks (#3441)
- chore(DB): import pending SQL update file
- fix(DB/Creature): Prince Sandoval is not attackable (#3333)
- docs(Readme): Minor improvements (#3214)
- refactor(Core/Common): restyle common lib with astyle (#3461)

## 2020-09-11
- feat(Core/Time): remove inherited ACE Time (#3455)
- chore(Core/Shared): restyle shared lib with astyle (#3462)
- chore(Core/Worldserver): restyle worldserver lib with astyle (#3463)
- feat(Deps/MySQL): add support MariaDB 10.5 (#3452)
- chore(Core/Authserver): restyle authserver library with astyle (#3464)

## 2020-09-10
- chore(DB): import pending SQL update file
- fix(DB/SAI): remove links pointing to non-existing ID (#3139)
- chore(DB): import pending SQL update file
- chore(DB/VerifiedBuild): Items 3.2.2 (#3401)
- refactor(Core/Misc): remove the ternary operator when used improperly (#3327)
- chore(DB): import pending SQL update file
- fix(DB/Creature): Remove wrong Steam Burst (#3072)

## 2020-09-09
- docs(issue_template): add template for feature requests (#3207)
- fix(Scripts/Wintergrasp): fix disabled always false (#3437)
- chore(DB): import pending SQL update file
- chore(DB/VerifiedBuild): Creatures 3.3.0 (#3400)

## 2020-09-08
- fix(Core/Spline): -Wcast-function-type warning (#3442)
- fix(Core/player): do not show zone at first login (#3358)
- docs(SECURITY): Move SECURITY.md to .github folder (#3234)
- refactor(Core): replace ACE atomic types with standard C++ (#3421)

## 2020-09-07
- chore(DB): import pending SQL update file
- fix(DB/spell_custom_attr): Remove spell that doesn't exist (#3353)
- fix(Scripts/AzjolNerub): Amanitar not casting “Mini” and mushroom not cleansing the player on death (#3348)
- refactor(Core/Tools): remove ACE from tools (#3351)
- chore(DB): import pending SQL update file
- chore(DB/VerifiedBuild): Items 3.3.0 (#3399)
- fix(Scripts/ICC): visual of the Blood Council Bosses

## 2020-09-06
- chore(DB): import pending SQL update file
- chore(DB/VerifiedBuild): Gameobject 3.3.0 (#3398)
- Revert "feat(pull_request_template): Introduce the new github way (#3209)" (#3435)
- refactor(Scripts/Stratholme): fix warnings and made code more readable (#3433)
- chore(DB): import pending SQL update file
- chore(DB/VerifiedBuild):] Quests 3.3.0 (#3397)

## 2020-09-05
- chore(DB): import pending SQL update file

## 2020-09-06
- fix(DB/pool_template): improve spawn quantity of herbs in northrend (#3338)

## 2020-09-05
- refactor(Core/ICC): Move hardcoded spells to enum (#3337)
- chore(DB): import pending SQL update file
- chore(DB/VerifiedBuild): Creatures 3.3.5
- fix(Scripts/ICC): Don't show Heroic Attempts on Normal difficulty (#3336)
- chore(DB): import pending SQL update file
- chore(DB/VerifiedBuild): Items 3.3.5
- fix(Core/Tools): fix GCC warnings in extractors (#3430)

## 2020-09-04
- chore(DB): import pending SQL update file
- chore(DB/VerifiedBuild): Quests 3.3.5 (#3394)
- fix(Core/Misc): GCC warnings (#3428)
- feat(code_of_conduct): add code of conduct to the project (#3210)
- chore(DB): import pending SQL update file
- fix(DB/Dungeon): improved Lower Blackrock Spire (#3328)
- refactor(lfg): refactor code and style (#3326)
- chore(DB): import pending SQL update file
- fix(Core/Script): Anomalus (#3325)
- fix(CI/macos): reduce cache size (#3427)

## 2020-09-03
- chore(DB): import pending SQL update file
- chore(DB/Zone): enable allowMount in Emerald Dream (#3392)
- fix(CORE/Dungeon): Mage-Lord Urom now cats empowered arcane explosion when he teleports to the center (#3323)
- chore(CI): solve (#3322)
- chore: add ./apps/joiner/ to .gitignore (#3318)
- fix(Core/Spells): Implement SPELL_ATTR7_INTERRUPT_ONLY_NONPLAYER. (#3313)
- feat(pull_request_template): Introduce the new github way (#3209)

## 2020-09-02
- feat(CI/Linux): use compression in ccache (#3425)
- chore(deps): update gsoap to version 2.8.105 (#3316)
- chore(DB): import pending SQL update file
- feat(Core/Script): Playing music from GameObjects and added holiday zones music script (#3307)
- chore(DB): import pending SQL update file
- [Dungeon] Scholomance (#3306)
- fix(Docker): fix Priority class denied (#3295)
- docs(issue_template): add links to issue create window (#3208)

## 2020-09-01
- chore(DB): import pending SQL update file
- fix(Core/Quest): Death Comes From On High (#2939)
- chore(DB): import pending SQL update file
- Core/Scripts: fix Nightfall proc chance and reduce it for victims with level above 60. (#3304)
- chore(DB): import pending SQL update file
- fix(CORE/Commands): Renamed .character deleted old to .character deleted purge (#3300)
- feat(contributing) Add guidelines for new contributors (#3211)
- chore(DB): import pending SQL update file
- feat(DB/SmartAI): [Raid] Ulduar (#3264)

## 2020-08-31
- chore(DB): import pending SQL update file
- fix(DB/Creature): Atal'ai Priest unattackable (#3043)
- feat(CI): actions/cache@v2 (#3416)
- chore(CI/Docker): skip Scripts for shorter build times (#3415)
- fix(CI/macOS): ccache issue (#3389)
- fix(CORE/Raid): Muradin/Saurfang not de-spawning after finishing movement (#3294)
- fix(CORE/Raid): Lich King “Pain and Suffering” snapping and “Shadow Trap” not targeting tanks (#3293)
- refactor(Core): NULL -> nullptr (#3275)
- docs(README): fix url (#3385)

## 2020-08-30
- fix(Core/SpellEffects): Make Shadowmeld drop combat (#3272)
- fix (Core/Quest) Correct link quest and fix command lookup quest for multilanguage dbc (#3271)
- chore(DB): import pending SQL update file
- Core/DB fix Icecrown Citadel Raid - Saurfang Intro Roleplay (#3261)

## 2020-08-29
- chore(DB): import pending SQL update file
- feat(DB/SAI): [Azeroth] Classic Rares - Part I (#3256)
- chore(DB): import pending SQL update file
- feat(DB/Creature): [Zone] Thousand Needles (#3255)
- chore(DB): import pending SQL update file
- feat(DB/SAI): [Azeroth] Missed & Skipped Creatures (#3254)

## 2020-08-28
- chore(DB): import pending SQL update file
- [Zone] Isle of Quel'Danas (#3253)
- chore(DB): import pending SQL update file
- [Zone] Tanaris (#3252)
- chore(DB): import pending SQL update file
- fix(DB/Creature): Eversong Woods (#3251)

## 2020-08-27
- chore(CI): change bot's commit message format (#3361)
- Import pending SQL update file...
- fix(DB/Creature): Ungoro Crater (#3250)

## 2020-08-26
- Import pending SQL update file...
- fix(DB/Creature): Silithus (#3249)
- Import pending SQL update file...
- fix(DB/Creature): Yulda the Stormspeaker (#3233)
- Allow mages to refresh Living Bomb (#3228)
- Import pending SQL update file...
- fix(DB/Creature): Stratholme (#3226)

## 2020-08-25
- refactor(Core): remove ace_autoptr, cleanup (#3276)
- Import pending SQL update file...
- fix(DB/SAI): improve Feralas NPCs

## 2020-08-24
- Import pending SQL update file...
- fix(Core/Gossip): Remove hard-coded texts from the: The forge of souls C++ (#3219)
- fix(DB/SmartScriptMgr): Move CWZ valid check (#3206)
- fix(build): remove warning (#3205)

## 2020-08-23
- fix(quest): improve quest force of neltharaku (#3203)
- Import pending SQL update file...
- refactor(creature-loot): improve chance % of Bohan NPC (#3202)

## 2020-08-22
- fix(Core/DBCStores): prevent crash worldserver
- Import pending SQL update file...
- fix(DB/GO): improve gameobject instances respawn timesecs (#3201)
- fix(Core/SpellAuras): Show auras to client limit (#3193)

## 2020-08-21
- fix(Scripts/UtgardePinnacle): Svala Sorrowgrave's loot disappearing too quickly (#3188)
- feat(CI): add Windows to the CI (#3324)
- fix(Core/Spells): Winter's Chill now stacks from multiple sources
- feat(CI): add macOS to our CI (#3321)
- fix(Core/Command): Can comment closed tickets (#3176)

## 2020-08-20
- feat(Core/Command): Reenable .teleport name on offline player (#3175)
- feat(Core/Config): CONFIG_INTERVAL_SAVE (#3171)
- feat(Core/SendListInventory): Add multivendor function (#3172)

## 2020-08-19
- fix(CI): Made test run in relative path (#3319)
- fix(CI/Core/ArenaSpectator): clang warnings + prevent new warnings (#3317)
- Import pending SQL update file...
- refactor(CORE/Instance): Move Pandemonius script from SAI to Core script (#3165)
- Import pending SQL update file...
- feat(Core/Commands): Character check bag && work (#3164)
- Import pending SQL update file...
- fix(Scripts/DB): Add Prison to spawn Yor, move Yor AI from SAI (#3163)

## 2020-08-18
- feat(CI): add Ubuntu 18.04 to the CI (#3311)
- test: add code coverage report (#3312)
- fix(Core/Unit): melee attack through LoS (#3265)
- fix(#2147): enrage and some false-negative spells (#3153)

## 2020-08-17
- fix(deps): update gsoap to fix vulnerability issue (#3310)
- test: fix some cmake params (#3308)
- test: fix unit test linking problem in ubuntu 18.04
- chore(unit-object-accessor): add findConnectedPlayer to object accessor (#3155)

## 2020-08-16
- Import pending SQL update file...

## 2020-08-17
- Create rev_1592783105272652900.sql (#3150)

## 2020-08-16
- Import pending SQL update file...
- refactor(Core/SpellInfo): Positive/Negative spells from SpellFamilyName into DB (#3149)

## 2020-08-15
- feat(CI/Docker): build all containers in CI (#3289)
- feature(testing-automation): unit tests with Google Framework (#3273)
- Import pending SQL update file...
- fix(DB/Creature): Desolace (#3145)

## 2020-08-13
- fix(Core/ObjectMgr): solve Global Storage issue
- Import pending SQL update file...
- fix(DB/SAI): improve Mulgore zone (#3144)
- feat(Docker): update to Ubuntu 20.04 + more improvements (#3277)

## 2020-08-12
- Import pending SQL update file...
- fix(DB): improvements to Magister's Terrace (#3143)

## 2020-08-11
- fix(Core/Spell): rogue's poisons logic check (#3278)

## 2020-08-10
- Import pending SQL update file...
- refactor(Scripts/SAI): move Gryphoneer Windbellow to SAI (#3137)

## 2020-08-09
- Import pending SQL update file...
- fix(DB/Creature): Opening the Dark Portal (#3142)
- Import pending SQL update file...
- fix(DB/GameTables): correct links to data from gt* DB tables (#3216)

## 2020-08-08
- Import pending SQL update file...
- fix(DB/Creature): Escape from Durnholde (#3141)

## 2020-08-06
- chore: Removed unwanted submodule
- feat(bash): support for derivated distro + refactor conf (#3259)

## 2020-08-05
- chore(worldserver.conf): Update GM.StartLevel to core default (#3136)

## 2020-08-04
- feature(World/Config): Implement MaxWhoListReturns (#3127)
- Import pending SQL update file...
- fix(DB/item_template): Savange and Hateful Gladiator's range (#3126)

## 2020-08-03
- Import pending SQL update file...
- fix(Core/playercreateinfo_item): Alter amount of allowed items (#3122)

## 2020-08-02
- Import pending SQL update file...
- fix(Core/Script): Remove hardcoded Loch Modan texts (#3111)

## 2020-07-30
- Import pending SQL update file...
- fix(Core/Creature): Lady Katrana hardcoded text (#3110)
- Core/Misc: update g3dlite lib (#2904)

## 2020-07-28
- feat(SUPPORT): Show contributors how to get help (#3212)
- fix(Core/MailHandler): Prevent client crash while receiving a malformed mail (#3223)

## 2020-07-27
- fix(Core/Vendors): Load npc_vendor items in the right order (#3099)

## 2020-07-26
- Import pending SQL update file...
- fix(DB/Creature): The Botanica (#3098)

## 2020-07-25
- Import pending SQL update file...
- fix(DB/Creature): The Mechanar (#3096)

## 2020-07-24
- Import pending SQL update file...
- fix(DB/Creature): The Arcatraz (#3097)

## 2020-07-23
- Import pending SQL update file...
- fix(DB/Creature): Dustwallow Marsh (#3095)

## 2020-07-22
- Import pending SQL update file...
- feat(Core/DBC): rework load DBC (#3002)

## 2020-07-21
- Import pending SQL update file...

## 2020-07-22
- fix(DB/Creature): Barrens (#3094)

## 2020-07-21
- Import pending SQL update file...
- fix(DB/Creature): Durotar (#3093)

## 2020-07-20
- Fix db_assembler on macOS (#1700)

## 2020-07-19
- fix(Core/SmartScripts): Disallow Gob to use Combat with Zone (#3199)

## 2020-07-18
- Import pending SQL update file...
- fix(DB/Gameobject): Maraudon portal clickable (#3088)

## 2020-07-17
- Import pending SQL update file...
- fix(DB/Sai): Remove Gameobject from being in combat with zone (#3195)

## 2020-07-16
- Import pending SQL update file...
- fix(DB/Creature): Captain Greenskin formation (#3086)
- Import pending SQL update file...
- fix(DB/Spell): Savory Deviate Delight auras should not stack (#3073)
- doc(readme): Fixed catalogue link

## 2020-07-15
- Import pending SQL update file...
- fix(DB/Creature): Vereth the Cunning stand state (#3069)

## 2020-07-14
- fix(Core/Player): Display random properties in inspect (#3067)
- refactor(Core/World): Make the file a bit more pretty (#3058)
- Import pending SQL update file...
- fix(DB/Creature): Stonetalon Mountains (#3046)

## 2020-07-13
- Import pending SQL update file...
- fix(DB/Creature): Ashenvale (#3045)

## 2020-07-12
- feat(Core/Config): rework configs load system (#2566)
- Import pending SQL update file...
- fix(DB/Creature): Azshara

## 2020-07-10
- refactore(core/config): Move BG Report AFK To Conf (#2813)

## 2020-07-07
- Import pending SQL update file...
- fix(DB/Creature): Darkshore (#3039)
- wiki(Security): Fix link (#3170)

## 2020-07-06
- wiki(Security): Add a security policy (#3085)
- chore(CMake)!: Drop support for MariaDB 10.1

## 2020-07-05
- feat(Core/Loot): Increase the max loot possible by 2 (#3025)

## 2020-07-03
- Import pending SQL update file...
- fix(DB/Creature): Auchenai Crypts (#3022)

## 2020-07-02
- Import pending SQL update file...
- fix(DB/Creature): Underbog (#3020)

## 2020-07-01
- Import pending SQL update file...
- fix(DB/Creature): Steamvault (#3019)

## 2020-06-30
- Import pending SQL update file...

## 2020-07-01
- fix(DB/Creature): Light's Hope Chapel dialogue script (#2850)

## 2020-06-29
- Import pending SQL update file...
- fix(DB/Creature): Slave Pens (#3018)

## 2020-06-28
- Import pending SQL update file...
- fix(Core/SpellScript): Script item Egg Nog (#2943)

## 2020-06-27
- Import pending SQL update file...

## 2020-06-28
- fix(DB/Creature): Shadow Labyrinth (#3017)

## 2020-06-27
- Import pending SQL update file...
- fix(DB/Fix): Sethekk Halls (#3016)

## 2020-06-25
- Import pending SQL update file...
- fix(DB/Creature): Mana Tombs (#3015)

## 2020-06-24
- Import pending SQL update file...
- fix(DB/Creature): Felwood (#3014)

## 2020-06-23
- Import pending SQL update file...
- fix(DB/Creature): Winterspring (#3013)

## 2020-06-22
- refactor(issue_template): Move it to Githubs "new" place (#3074)

## 2020-06-21
- Import pending SQL update file...
- feat(Core/Config): Enable/Disable Debug BG/Arena (#3001)

## 2020-06-19
- Import pending SQL update file...

## 2020-06-20
- fix(DB/Creature): Remove loot from totems (#2995)

## 2020-06-19
- Import pending SQL update file...
- fix(Core/Spell): Implement SPELL_ATTR0_CU_DONT_BREAK_STEALTH (#3056)

## 2020-06-18
- refactor(Core/BG): improvements to the queue system (#3091)
- fix(Core/BG): fix BG_QUEUE_INVITATION_TYPE_NO_BALANCE (#3134)

## 2020-06-17
- Import pending SQL update file...
- fix(DB/Creature): Dragonmaw Bonewarder (#2992)

## 2020-06-16
- Import pending SQL update file...
- fix(DB/Creature): Outland Rares (#2991)

## 2020-06-15
- fix(Core): C++ 11 rule of 3 compiant constructors (#3023)

## 2020-06-14
- fix(Core/Battleground): fix queue issue (#3116)
- Import pending SQL update file...
- fix(DB/SmartScripts): Swamp of Sorrows (#2990)

## 2020-06-13
- Import pending SQL update file...
- fix(DB/Locale): Add several entries for frFR (#1302)
- fix(Core/WorldSocket): All control paths will return a value (#3117)

## 2020-06-12
- Import pending SQL update file...

## 2020-06-13
- fix(DB/Creature): Desolace (#2989)

## 2020-06-12
- Import pending SQL update file...
- fix(DB/Quest): Mastery of the Crystals (#2988)
- Import pending SQL update file...
- fix(DB/Creature): Blackfathom Deeps (#2987)

## 2020-06-11
- Import pending SQL update file...
- fix(DB/Creature): Shattered Halls (#2986)

## 2020-06-10
- Import pending SQL update file...
- fix(DB/Creature); Blood Furnace (#2985)

## 2020-06-09
- Import pending SQL update file...
- fix(DB/Creature): Hellfire Ramparts (#2984)

## 2020-06-08
- Import pending SQL update file...
- fix(DB/Creature): Sunken Temple (#2983)

## 2020-06-07
- Import pending SQL update file...
- fix(DB/Creature): Zul'farrak (#2982)
- Import pending SQL update file...
- [Dungeon] Maraudon (#2981)

## 2020-06-06
- Import pending SQL update file...

## 2020-06-07
- fix(DB/Creature): Uldaman (#2980)

## 2020-06-06
- Import pending SQL update file...
- fix(DB/Creature): Razorfen Downs (#2979)

## 2020-06-05
- fix(Core/BG): do not start new BGs if there are BGs with free slots (#3082)
- Import pending SQL update file...
- fix(DB/Creature): Scarlet Monastery (#2978)

## 2020-06-04
- Import pending SQL update file...
- fix(DB/Creature): Gnomeregan (#2977)
- Import pending SQL update file...
- fix(DB/Creature): Razorfen Kraul (#2976)

## 2020-06-03
- Import pending SQL update file...

## 2020-06-04
- fix(DB/Creature): The Stockade (#2975)

## 2020-06-03
- feat(CI): update clang-7 to clang-9, add clang-10 build (#3107)
- fix(Core/MailHandler): Security check (#2889)

## 2020-06-02
- fix(Core/Spell): Allow to cast and aura all spells (#3089)
- feat(CI): upgrade to Ubuntu 20.04 (#3106)
- fix(Core/Clang): make it work with clang 10 (#3104)
- Import pending SQL update file...
- fix(DB/Quest): A Dire Situation (#2974)

## 2020-06-01
- fix(build): eluna (#3103)
- feat(CI): refine cache usage in gh-actions (#3101)
- Import pending SQL update file...
- fix(DB/Creature): Shadowfang Keep (#2972)

## 2020-05-31
- fix(CMake/FindMySQL): Allow MySQL 8.0 in Windows (#3087)
- Import pending SQL update file...
- fix(DB/Creature): Wailing Caverns (#2971)

## 2020-05-30
- fix(Core/Query): Update GroupMgr query to support MySQL 8.0 (#3068)
- Import pending SQL update file...
- fix(Core/Script): Felmyst (#2965)

## 2020-05-29
- fix(Core): solve issue with MariaDB (#3084)
- Import pending SQL update file...
- fix(DB/Creature): Deadmines (#2970)

## 2020-05-28
- Import pending SQL update file...
- refactor(Core/Command): tele to teleport (#2956)

## 2020-05-27
- fix(Core/Script): Trial of the Crusader (#2888)
- fix(Core/ChatHandler): Prevent messages > 255 characters (#3063)

## 2020-05-26
- fix(Core/Mysql): my_bool type conflict (#3060)
- fix(Docker): Mysql Password (#3061)

## 2020-05-25
- Import pending SQL update file...
- fix(DB/Creature): Ragefire Chasm (#2969)
- feat(Core/Docker): Enable SOAP for external usage (#3003)

## 2020-05-24
- feat(Docker): Container healthchecks (#2951)
- fix(Docker): Persistent volumes for ac-database (#2947)

## 2020-05-23
- fix(Core/Pet): Risen Ghoul random name & pet detail (#2945)
- Import pending SQL update file...

## 2020-05-22
- fix(DB/Quest): Take No Chances (#2944)
- Import pending SQL update file...
- feat(Core/Battleground): Config to allow/disallow ability to Share Quest & Ready Check (#2924)

## 2020-05-21
- Import pending SQL update file...

## 2020-05-22
- fix(DB/ImportSQL): Missed import SQL f2892764cd (#3054)
- fix(Core/Query): Escape MySQL 8.0 Keyword (#3052)

## 2020-05-21
- Import pending SQL update file...
- fix(DB/Quest): The Deathstalkers (#2935)

## 2020-05-20
- Import pending SQL update file...
- refactor(DB/acore_string): Rename locale columns (#2929)

## 2020-05-19
- fix(DB/Quest): Repurposed Technology (#2938)
- Import pending SQL update file...
- fix(DB/Gameobject): Reagent Pouch (#2908)
- Import pending SQL update file...
- fix(DB/Quest): Skybreaker Questchain (#2903)

## 2020-05-18
- Import pending SQL update file...
- fix(Core/Command): additem checks (#2898)
- Import pending SQL update file...

## 2020-05-17
- fix(DB/Locale): Locale fix for quest 919 (#2894)
- Import pending SQL update file...
- fix(DB/Gameobject): Dalaran Forges (#2886)
- refactor(Core/Query): escape some MySQL 8.0 keywords (#3027)

## 2020-05-16
- fix(bash): joiner tool has been moved (#3038)
- Import pending SQL update file...
- fix(DB/Quest): Secrets of the Flamebinders quest chain (#2873)

## 2020-05-15
-  feat(DB/Account): Delete account_muted when deleting an account
- fix(Core/Script): Grand Magus Telestra talk (#2871)

## 2020-05-14
- Import pending SQL update file...

## 2020-05-15
- fix(Core/Command): cheat explore (#2862)

## 2020-05-14
- Import pending SQL update file...
- fix(DB/Quest): Deprecated quests (#2861)

## 2020-05-13
- fix quotes on 74e0f00 (#3029)
- Import pending SQL update file...
- fix(Core/Conditions): Add CONDITION_SOURCE_TYPE_QUEST_AVAILABLE (#2859)

## 2020-05-12
- style(Core/Achievement): Improve error msg for achievement_reward (#2852)
- Import pending SQL update file...
- fix(DB/Quest): Image of Commander Ameer Quests Start/End (#2845)

## 2020-05-11
- chore(DB): fix syntax in sql update (#2841)

## 2020-05-10
- Import pending SQL update file...

## 2020-05-11
- fix(DB/Creature): Julianne Death Sound (#2836)

## 2020-05-10
- Import pending SQL update file...
- fix(DB/Creature): Dreadsaber & Shardhorn Rhino positioning (#2835)

## 2020-05-09
- Import pending SQL update file...
- fix(DB/Creature_text): ToC Lich King (#2824)

## 2020-05-08
- Import pending SQL update file...
- fix(DB/Creature): Bloodmaul Skirmisher Spawn Point (#2812)

## 2020-05-07
- fix(Core/Account): GM Level 1 will not be hostile to players (#2807)
- fix(CI): core_build on coverity_scan is not needed
- feat(Core/Conf): Move BG rewards to config  (#2798)

## 2020-05-06
- Import pending SQL update file...
- fix(DB/lang): TBC Heroic Dungeon Keys German Description (#2805)

## 2020-05-05
- Import pending SQL update file...
- fix(DB/lang): Totem Item Description (#2795)

## 2020-05-04
- Import pending SQL update file...
- fix(DB/Creature): Naxxramas Cultistl (#2814)
- feat(Core/conf): Move arena charters cost to config (#2790)

## 2020-05-03
- Import pending SQL update file...
- fix(DB/Quest) Deprecated quests (#2770)

## 2020-05-02
- Import pending SQL update file...

## 2020-05-03
- fix(DB/Quest): Brothers in Death event (#2788)

## 2020-05-02
- Import pending SQL update file...
- feat(DB): Import german quest_request_items texts from GTDB (Part 4/4) (#2787)
- feat(Core/commands): Display reason for muting player (#2780)

## 2020-05-01
- feat(CORE/command): .account onlinelist orders accounts by IP (#2934)

## 2020-04-30
- Import pending SQL update file...
- fix(DB/reputation): Kurenai and Mag'har reputation amount rewarded (#2783)
- Import pending SQL update file...
- fix(DB/Creature): Stinky aura (#2860)

## 2020-04-29
- Import pending SQL update file...
- fix(DB/Quest): Shoot 'Em Down (#2915)

## 2020-04-28
- Import pending SQL update file...
- fix(DB/Item): Chest of Spoils loot (#2769)

## 2020-04-27
- feat(Core/Config): Configurable buy/sell rates (#2763)
- Import pending SQL update file...
- fix(DB/Item): Tome of Tranquilizing Shot Deprecated (#2768)

## 2020-04-26
- Import pending SQL update file...
- fix(DB/SAI): Grizzly Hills transport (#2765)

## 2020-04-25
- Import pending SQL update file...

## 2020-04-26
- Fix(DB/Dungeon): The Nexus (#2914)

## 2020-04-25
- Import pending SQL update file...
- fix(DB/Quest): More locations to complete Patching Up (#2853)

## 2020-04-24
- Import pending SQL update file...
- fix(Core/DB/Events): Game Event on Calendar (#2890)

## 2020-04-23
- Import pending SQL update file...
- fix(DB/NPC): Eridan Bluewindl now award Flute of the Ancients (#2759)
- chore(CI): update import_pending_sql.yml (#2928)
- fix(Core/Raid): Eyes activate when endboss dead in Naxxramas (#2819)

## 2020-04-22
- Import pending SQL update file...

## 2020-04-23
- fix(CI): sql import

## 2020-04-22
- fix(DB/Spell): Clam drops (#2757)
- Import pending SQL update file...
- fix(CI):updated token for import_pending_sql
- feat(CORE/command): .kick will now display the kick reason (#2779)

## 2020-04-21
- fix(DB/Creature): Ragefire Shaman will now cast heal (#2772)
- fix(core/packet): prevent client crash from malformed packet/message (#2910)

## 2020-04-20
- fix(DB/item): Missing loot for Heart-Shaped Box (#792)

## 2020-04-19
- feat(CI): migrate from Travis to GitHub Actions (#2887)

## 2020-04-18
- feat(Core/AI): CU_SAI - Custom Target Options (#2879)

## 2020-04-17
- Import pending SQL update file...
- fix(DB/Quest): Old Whitebark's Pendant (#2771)
- Import pending SQL update file...
- Fix reward text for Quest: Shaodw's Edge (#2752)
- fix:(DB/Item) Mechanical Greench / Wand of Holiday Cheer (#2751)
- feat(Core/AI): CU_SAI - set creature in combat outside of dungeon (#2878)
- feat(Core/AI): CU_SAI - Custom Event Options (#2881)

## 2020-04-16
- feat(Core/SAI): new Actions + Polar Coords System Offset Relocating (#2880)

## 2020-04-15
- fix(Core/Mail): Mailhandler cleanup (#2802)

## 2020-04-13
- Import pending SQL update file...

## 2020-04-14
- fix(DB/Quest): Teron Gorefiend chaining (#2746)

## 2020-04-12
- Import pending SQL update file...
- fix(DB): The Green Hills of Stranglethorn German quest texts (#2736)

## 2020-04-11
- Import pending SQL update file...
- fix(Core/Creature): Use proper name for wander distance (#2858)

## 2020-04-10
- fix(CORE/locale): achievement_reward_locale should now work (#2811)

## 2020-04-08
- Import pending SQL update file...

## 2020-04-09
- fix(DB): Fix quest minor text errors (#2727)

## 2020-04-08
- Import pending SQL update file...
- fix error loot altac valley (#2726)

## 2020-04-07
- Import pending SQL update file...
- feat(DB/lang): import German quest_request_items Texts from GTDB (Part 3/4) (#2725)

## 2020-04-05
- Import pending SQL update file...
- fix(DB/Gossip): Corrupted Cat gossip #2762

## 2020-04-04
- Import pending SQL update file...
- fix(DB/creature): Add waypoint for Morin Cloudstalker (#2837)
- fix(core): "Silenced - You can only chat with GMs" spell (#2716)

## 2020-04-02
- Import pending SQL update file...
- style(DB): battelground_template entries now commented by type (arena or bg) (#2722)

## 2020-04-01
- fix(Core/Hook): OnFirstLogin can now make persistent changes (#2793)

## 2020-03-31
- fix(app/db_assembler): Allow recursion with bash (#2731)
- feat(Core/Config): make stop time for creatures with WP movement configurable #2715 (#2829)

## 2020-03-30
- Import pending SQL update file...
- fix(DB/creature_formations): Thal'trak Proudtusk pathing (#2724)

## 2020-03-29
- Import pending SQL update file...
- fix(DB/creature_formations): Moon Priestess Amara pathing (#2711)
- Import pending SQL update file...
- feat(DB/Creature): Add missing Little Adeline NPC #2747

## 2020-03-28
- fix(Calendar/Packets): add additional validation when creating events (#2799)
- Import pending SQL update file...
- fix(DB/reputation): Sporeggar repeatable quest reputation rate (#2698)

## 2020-03-26
- Fix(Core/Packets/AntiDOS): Remove from default some repetitive movement packets (#2809)
- Import pending SQL update file...
- fix(DB): Marsh Lurker spawn position (#2697)

## 2020-03-25
- chore(Core/AH): Restore little comment (#2702)
- fix(Core/Pet): Pet chase range check for melee ranged spells (#2694)
- fix(DB): error on default MySQL install (#2776)

## 2020-03-24
- Import pending SQL update file...
- feat(DB/lang): Import german quest_request_items texts from GTDB (Part 2/4) (#2692)
- Revert "Fix(Core/Gameobjects): non-consumable goobers no longer despawn on use (#2750)" (#2797)

## 2020-03-23
- feat(Core/Packet): Implement AntiDOS protection from Trinity (#2789)
- fix(Core/Gossip): fix titles in quest reward being able to show in gossip (#2791)

## 2020-03-22
- Import pending SQL update file...
- fix(DB/creature): Remove duplicates Cenarion Stormcrow (#2708)

## 2020-03-21
- Fix(Core/Gameobjects): non-consumable goobers no longer despawn on use (#2750)

## 2020-03-20
- fix(Core/Spell): Melee ranged spells (#2686)

## 2020-03-19
- Import pending SQL update file...
- fix(DB/creature_template): PvP flagged creatures in Talon Den (#2681)

## 2020-03-18
- Core/Misc: Remove dependency on undefined behaviour (#2678)

## 2020-03-17
- Fix(Core/Packet): Calendar events exploits (#2753)

## 2020-03-16
- Import pending SQL update file...
- fix(DB/Gameobject): Secret Safe loot (#2738)

## 2020-03-15
- Import pending SQL update file...
- fix(GameObject/Quest): GameObject quest / gossip window (#2676)

## 2020-03-14
- fix(Core/SAI): SMARTCAST_COMBAT_MOVE (#2672)

## 2020-03-12
- Import pending SQL update file...
- fix(DB/Quest): Shaman quest "Earth Sapta" (#2663)

## 2020-03-11
- Import pending SQL update file...
- feat(DB/lang): Import german quest_offer_reward texts from GTDB (Part 1/4) (#2670)

## 2020-03-09
- Import pending SQL update file...
- fix: Zul'Aman raid improvements (#2654)

## 2020-03-08
- fix(apps): Script for default git commit template returns output (#2642)

## 2020-03-07
- fix(core/packet): check malformed guild packet to prevent client crash (#2739)

## 2020-03-06
- fix: TC link and fix spacing (#2737)

## 2020-03-05
- chore(README): Add linkedin link (#2723)

## 2020-03-04
- Import pending SQL update file...
- fix(DB/quests): Added german locale for "Ashenvale Hunt" (#2730)

## 2020-03-03
- fix(Core/Dungeon): Halls of stone doors (#2646)

## 2020-03-02
- Import pending SQL update file...
- fix(DB/Creature): Argent Guard Thaelrid (#2674)

## 2020-03-01
- Import pending SQL update file...
- Morph command update (#2641)

## 2020-02-28
- fix(Core/Pet): only show pet details for hunter pets and demons (#2637)

## 2020-02-27
- feat(Core/Hook): A few new hooks (#2671)
- fix(Core): build with ENABLE_EXTRA_LOGS (#2709)

## 2020-02-26
- feat(Core/Hook): New GlobalScript hook (#2665)
- fix(Core/Crash): remove unneeded hook OnPlayerChat (#2707)

## 2020-02-25
- fix(Core/commands): Realign columns for command ".pdump" (#2699)

## 2020-02-24
- refactor(HandleAuctionListOwnerItems): prevent crash (#2684)

## 2020-02-23
- feat(Core/Config): Parameter to set all creatures with WP movement active (#2615)

## 2020-02-22
-  fix(Core/Packet): fix crash happening when someone sends small packets that is processed directly to WorldSocket (#2669)

## 2020-02-20
- Core/Misc: Remove redundant null pointer checks before delete (#2679)
- refactor(Core/Spells): Improved logic and DX Spell::EffectSummonPet (#2634)

## 2020-02-19
- feat(Core/Spell): Header include optimization for files: SpellAura.h SpellAuraEffects.h (#2632)

## 2020-02-18
- fix(Core/Misc): fix some exploits (#2630)

## 2020-02-17
- Import pending SQL update file...
- fix(DB/gossip): Fix several gossip options for NPCs in Un'Goro Crater (#2606)

## 2020-02-16
- fix(Core/CreatureGroups): Fix "MoveSplineInitArgs::Validate" errors (#2604)

## 2020-02-15
- Import pending SQL update file...
- fix(DB/npc_trainer): remove some wrong spells from trainer tables (#2598)

## 2020-02-14
- fix(Core/CreatureAI): Skip creatures in evade mode for DoZoneInCombat (#2599)

## 2020-02-13
- fix(Core/Unit): Fix Guardian Pets clearing combat state (#2619)

## 2020-02-12
- fix(Core/Eluna): Fix issues with spell procs with Eluna (#2636)

## 2020-02-11
- Import pending SQL update file...
- fix(DB/SAI): Duskwing (#2596)

## 2020-02-10
- Import pending SQL update file...
- fix(DB/SAI): Quest "Anatoly Will Talk" (#2595)

## 2020-02-08
- fix(DB): sql import (#2655)

## 2020-02-07
- Import pending SQL update file...
- feat(DB): Test accounts using various GM levels (#2587)

## 2020-02-05
- fix(Core/TempSummon): Fix crash concerning PlayerScript hook (#2650)
- docs(REPO): removed unused submodule
- Import pending SQL update file...
- fix(DB/SAI): Grizzly Bear (#2585)

## 2020-02-04
- feat(Core/Hook): New PlayerScript hooks (#2639)

## 2020-02-03
- fix(Core): potential crashes/bugs reported by static analysis #2 (#2622)

## 2020-02-01
- Fix (Core/DB): Remove hardcoded text from Malygos (#2618)
- fix(Core/Hook): Make OnPlayerLeaveMap actually trigger (#2628)

## 2020-01-31
- Import pending SQL update file...
- fix(DB/SAI): Innocuous Scarab (#2580)

## 2020-01-30
- Import pending SQL update file...
- fix(DB/SAI): Devilsaurs (#2577)

## 2020-01-29
- fix(Core/Player): Fix removal of quest items (#2626)
- refactor(CORE/scripts): Clearer error when script unassigned or alrea… (#2576)

## 2020-01-28
- Import pending SQL update file...
- fix(DB/creature): Imperial Eagle (#2572)

## 2020-01-26
- fix(Core/DK): Don't allow starter dk to queue bg (#2584)

## 2020-01-25
- fix(Core): Fixed a few crashes/bugs that were found via static code analysis (#2617)

## 2020-01-24
- fix(Core): Improve logging msg when missing .conf file (#2560)

## 2020-01-23
- fix(Core) : Enable randomProperties or suffix up to 5 (#2340)

## 2020-01-21
- fix(CORE): Missing override on various functions (#2602)
- fix(Core/Battleground): must fix IC scoreboard (#2597)

## 2020-01-19
- feat(Core/Battlegrounds) Reworked enhanced bg system for modules (#2521)

## 2020-01-18
- fix(Core/Player): Only save player's glyphs when needed (#2583)

## 2020-01-16
- fix(Core/CreatureScript): Fix dk quest 12701 #2557 (#2559)

## 2020-01-15
- fix(core): Improve output for 2 small errors (#2549)

## 2020-01-14
- feat(Core/Hook): New PlayerScript hook "OnPetInitStatsForLevel" (#2556)

## 2020-01-13
- fix(Core/Battlegrounds): Fix compile error (#2574)
- refactor(Core/BG/AB): code cleanup (#1903)

## 2020-01-11
- Import pending SQL update file...
- fix(DB/SAI): Loramus Thalipedes quests/gossip (#2535)

## 2020-01-10
- refactor(Core/BG/AV): code cleanup (#1695)

## 2020-01-09
- Import pending SQL update file...
- fix(DB): Various database cleanups (#2515)

## 2020-01-07
- Fix(Core/Battleground): Fixed Nagrand Arena door position (#2523)

## 2020-01-05
- chore(github): Clean up pull_request_template.md (#2547)

## 2020-01-04
- Import pending SQL update file...
- feat(DB/Worldstates): added worldstates entry 20004 in characters DB (#2402)

## 2020-01-02
- Import pending SQL update file...
- fix(DB/creature): Great Wavethrasher position (#2537)

## 2019-12-31
- Import pending SQL update file...
- fix(DB/SAI): Kanati Greycloud (#2522)

## 2019-12-30
- Import pending SQL update file...
- fix(DB/SAI): Snufflenose Gopher (#2519)

## 2019-12-28
- fix(Core/Tools): fix build (#2529)
- fix(Core/Battlegrounds) Rewrite RandomBG and enabling bg/arenas weights (#2516)

## 2019-12-27
- chore(Core/Soap): Renamed TCSoap to ACSoap (#2509)

## 2019-12-26
- Import pending SQL update file...
- fix(Core/Spell): Glyph of Eternal Water (#2508)

## 2019-12-25
- Import pending SQL update file...
- fix(Core/CreatureScript): Grand Warlock Nethekurse (#2507)

## 2019-12-24
- Import pending SQL update file...
- fix(DB/SAI): Wastewalker Captive (#2502)

## 2019-12-23
- fix(Core/Intance): Fixed group spawn UBRS Rend (#2499)

## 2019-12-22
- fix(Core/Spell) Add an intervene trigger condition to avoid stealth removal (#2492)

## 2019-12-21
- feat(Core/Misc): remove and replace ACE_Singleton (#2418)

## 2019-12-20
- Import pending SQL update file...
- feat(Core/CommandScript): New GM command "player learn" (#2487)

## 2019-12-19
- fix(Core/ItemHandler): crash buy back item (#2511)

## 2019-12-18
- Import pending SQL update file...
- fix(DB/Locales): Various names & title fixes in locales (#2482)

## 2019-12-17
- fix(Core/Guild): Crash during money deposit / withdrawal (#2506)

## 2019-12-16
- Import pending SQL update file...
- fix(DB/SAI): Citizen of New Avalon (#2474)

## 2019-12-15
- Import pending SQL update file...
- fix(DB/GameEvent): Stranglethorn Fishing Extravaganca Event NPC's & Gameobject  (#2463)

## 2019-12-14
- fix(Core/Raid): Save correct data to DB after killing Ragnaros (issue #2464) (#2476)

## 2019-12-13
- Import pending SQL update file...
- fix(DB/SAI): Fix SAI error during quest "The Seer's Relic" (#2470)

## 2019-12-12
- fix(Core/BG) Moved AddObject AV doors after their spawn, closes #2453 (#2456)

## 2019-12-11
- feat(docs): Revamp the README (#2478)

## 2019-12-10
- Import pending SQL update file...
- fix(DB/SAI): Enraged Feral Scar (#2452)

## 2019-12-09
- Import pending SQL update file...
- feat(Core/ItemHandler): Optional item recovery (#2442)

## 2019-12-08
- Import pending SQL update file...
- fix(DB/SAI): Re-added Snowblind Follower interaction for quest 14090 (#2468)

## 2019-12-07
- Import pending SQL update file...
- fix(Core/GameObjectScript): Environmental damage of burning game objects (#2432)

## 2019-12-06
- fix(Core): Rand shuffle seed (RandomBattlegroundSystem,ICC-Marrowgar & Deathwhisper) (#2431)

## 2019-12-05
- fix(Core/SpellScript): Remove hard-coded texts from the "Pit of Saron" c++ script (#2405)

## 2019-12-04
- Import pending SQL update file...
- fix(DB): Command reload acore_string (#2484)

## 2019-12-03
- fix(CI): Enable Travis modules check (#2483)

## 2019-12-02
- fix(Core/Misc): few improvements to ut8 handling (#2455)

## 2019-12-01
- Import pending SQL update file...
- refactor(Core): rename namespaces and macros to acore (#2454)
- Import pending SQL update file...
- fix(DB/SAI): Freed Crusader (#2403)

## 2019-11-30
- Import pending SQL update file...
- fix(DB/GameObject): Quest event "The Bones of Nozronn"; quest sparkle for GO type "GAMEOBJECT_TYPE_SPELL_FOCUS" (#2398)

## 2019-11-29
- fix(Core/CreatureScript): Fix Ragnaros magma blast (#2394)

## 2019-11-28
- Import pending SQL update file...
- fix(DB/waypoint_data): Wyrmrest Guardian (#2389)

## 2019-11-27
- Import pending SQL update file...
- fix(DB/Quest): "Hot and Cold" quest item (#2388)

## 2019-11-26
- fix(Core): Missing updates for creatures; disable Travis modules check (#2457)

## 2019-11-25
- fix(docker): garbled cjk characters in docker (#2393)

## 2019-11-24
- Import pending SQL update file...
- fix(Core/Raid):Putricide mutated abomination being energized by players (#2386)

## 2019-11-22
- feat(Core/Misc): replace ACE based typedefs (#2460)
- Import pending SQL update file...
- feat(DB/characters): added comments to worldstates (#2384)

## 2019-11-21
- fix(DB/game_event): use another default minimum date to avoid import errors (#2462)

## 2019-11-20
- Import pending SQL update file...
- feat(DB/Translations) Imported german translations from GTDB (#2381)

## 2019-11-18
- fix(Core/PetAI): aggro and movement of Warlock's IMP (#2379)

## 2019-11-17
- fix(Core/Deps): fix build for Windows (#2451)
- fix(Core/GridNotifiers): Fix crash (#2443)

## 2019-11-16
- fix(Core): uint32 assignment, prevent crash, closes #2433 (#2435)

## 2019-11-15
- feat(Core/Misc): replace all prefix preprocessor defines from CompilerDefs with AC_ (#2419)
- feat(Core/Shared): added new library - shared (#2416)
- feat(Core/PacketIO): restrict CMSG_EMOTE/CMSG_STANDSTATECHANGE to only allow emotes/stand states that client can send by itself (#2412)
- fix(Core): prevent movement exploit (#2410)

## 2019-11-14
- feat(Deps/Jemalloc): update Jemalloc to 5.2.1 (#2413)
- fix(Core/GridNotifiers): increased visibility for large creatures, part 2 (#2378)

## 2019-11-13
- fix(Core/MovementHandler): fix crash at null guid in mover (#2426)

## 2019-11-12
- fix(Core/Gossip): Enable gossip translations from database(#2427)
- feat(Core/DBLayer): move DatabaseWorkerPool into it's own translation unit (#2417)

## 2019-11-11
- Import pending SQL update file...
- fix(Core/Quest): The Lich, Ras Frostwhisper (#2373)

## 2019-11-10
- feat(Core/Debugging): improve crash reports (#2365)

## 2019-11-09
- Import pending SQL update file...
- feat(Core/GameEvent): Allow unspecified end_time for game events (#2368)

## 2019-11-08
- feat(Core/Opcode): simple opcode filter to log non-existing opcode (#2281)

## 2019-11-07
- Import pending SQL update file...
- fix(Core/Dungeon): Elder Nadox hardcore texts + Ahn'kahar Spell Flinger spells. (#2244)

## 2019-11-06
- fix(Core/Crash): Improved Utf8toWStr() function to prevent crashes (#2407)

## 2019-11-05
- Import pending SQL update file...
- fix(Core/Spell): Eye of Gruul healing discount spell (#1913)

## 2019-11-04
- fix(Core/Spell): Glyph of Shadow Word: Death (#1900)

## 2019-11-03
- Import pending SQL update file...
- fix(DB/SAI): Garm area (#2367)

## 2019-11-02
- Import pending SQL update file...
- fix(DB/SAI): Quest "Canyon Chase" (Horde/Alliance) (#2362)

## 2019-11-01
- Import pending SQL update file...

## 2019-10-31
- fix(DB/creature_template): Make Sunreaver Dragonhawk not attackable in Argent Tournament Grounds (#2360)
- feat(Docker): Enable warnings during build (#2395)

## 2019-10-30
- fix(Core/AuthSocket): Added check for AuthFlooder (#2387)

## 2019-10-29
- Import pending SQL update file...
- fix(DB/SAI): Waypoint pause errors (#2359)

## 2019-10-28
- fix(Core/Item): Random item properties generation (#2331)

## 2019-10-27
- Import pending SQL update file...
- fix(DB/waypoint_scripts): Chilltusk (#2357)

## 2019-10-26
- Import pending SQL update file...
- fix(DB/gossip_menu_option): Quest "The Exorcism of Colonel Jules" (#2355)

## 2019-10-25
- Import pending SQL update file...
- fix(DB/SAI): Garm's Bane (#2354)

## 2019-10-24
- Import pending SQL update file...
- fix(DB/creature_loot_template): Fix Baron Rivendale loot, close #2349 (#2350)

## 2019-10-23
- Import pending SQL update file...
- feat(DB/points_of_interest): Improved points_of_interest table, close #1193 (#2348)

## 2019-10-22
- Import pending SQL update file...
- fix(Core/Commands): debug send opcode (#2344)

## 2019-10-21
- Import pending SQL update file...
- fix(DB/Core): Quest "The Great Hunter's Challenge"; add new condition CONDITION_QUEST_OBJECTIVE_PROGRESS (#2342)

## 2019-10-20
- Import pending SQL update file...
- fix(DB/Quest): Fix quest Hotter than Hell requirement of Fel Reaver corpse (#2336)

## 2019-10-19
- Import pending SQL update file...
- feat(DB/game_tele): Added Emerald Dream teleports (#2333)

## 2019-10-18
- Import pending SQL update file...
- fix(DB/SAI): Fulgorge (#2326)

## 2019-10-17
- feat(Core/Tools): mmaps working with mapID >= 1000 (#2321)

## 2019-10-16
- Import pending SQL update file...
- feat(Core/SpellMgr): Worldserver option for ICC buff (#2320)

## 2019-10-15
- Import pending SQL update file...
- fix(DB/SAI): Quest event "The Reckoning" (#2318)

## 2019-10-14
- feat(CI): add docker to travis build (#2347)

## 2019-10-13
- Import pending SQL update file...
- fix(DB/SAI): Fel Reaver (#2309)

## 2019-10-12
- Import pending SQL update file...
- fix(DB/SAI): Sen'Jin Fetish (#2297)

## 2019-10-11
- Import pending SQL update file...
- fix(DB/SAI): Battle beneath the Dark Portal, part 2 (#2291)

## 2019-10-10
- Import pending SQL update file...
- fix(DB/gossip_menu_option): Gossip Dalaran NPCs (#2290)

## 2019-10-09
- feat(docker): allow script-less build (#2337)

## 2019-10-08
- Import pending SQL update file...
- fix(Core/spell_item): Fix a few items with spell effects (#2296)

## 2019-10-07
- feat(cmake/macro): Allow scripts to lower prioritize other scripts (#2329)

## 2019-10-06
- fix(Core/Battleground): Improving the Anti-Spam BG Queue Announcer (#2299)

## 2019-10-05
- fix(Core/Chat): Channel exploit (#2298)

## 2019-10-04
- Import pending SQL update file...
- feat(Core/CreatureAddon): increased visibility for large creatures (#2304)

## 2019-10-03
- Import pending SQL update file...
- fix(DB/SAI): Wind Trader Marid (#2285)

## 2019-10-02
- Import pending SQL update file...
- fix(DB/gameobject): Tallonkai's Dresser (#2288)

## 2019-10-01
- Import pending SQL update file...
- fix(Core/Chat): Prevent Horde / Alliance chat via custom emotes (#2292)

## 2019-09-30
- feat(Core/Config): Add parameter to load all grids of all non-instanced maps on server start (#2283)

## 2019-09-29
- Import pending SQL update file...
- fix(DB/SAI): Ruul the Darkener (#2279)

## 2019-09-28
- Import pending SQL update file...
- fix(DB/SAI): Quest "What Is Going On?" (#2275)

## 2019-09-27
- Import pending SQL update file...
- fix(DB/SAI): Venomspite quests / area (#2274)

## 2019-09-26
- feat(Core): Added ABORT() macro to prevent the usage of ASSERT(false) as a quick hack to crash the core misusing assert (#2273)

## 2019-09-25
- fix(Core/Hunter): Stable Master, exotics pets management, tame validations. (#2100)

## 2019-09-24
- fix(CMake): Use cmake-generator-expressions for escaping quotes (#2307)

## 2019-09-22
- feat(Cmake): set policy CMP005 to NEW (#2294)

## 2019-09-21
- feat(Cmake): set minimal support version 3.8 and added interface libs for world and auth (#2295)
- fix(Core/CreatureScript): Quest "Kindness" (#2272)

## 2019-09-20
- Import pending SQL update file...
- fix(DB/SAI): Sarathstra (#2264)

## 2019-09-18
- feat(Cmake/Build): Use interface targets for inheriting flags and definitions (#2255)

## 2019-09-17
- Import pending SQL update file...
- fix(DB/Quest): Lumber Hack (#2261)

## 2019-09-16
- Import pending SQL update file...
- fix(Core/Dungeon): Small corrections to Boss Novos encounter and some npcs wrong behavior (#2266)

## 2019-09-15
- Import pending SQL update file...

## 2019-09-16
- fix(DB/Quest): "The Hunter's Path" (#2257)

## 2019-09-14
- Import pending SQL update file...
- fix(DB/gameobject_template): Quest "Thwarting Kolkar Aggression" (#2249)
- Import pending SQL update file...
- fix(DB/SAI): Bath'rah the Windwatcher (#2253)

## 2019-09-12
- fix(Core/CreatureScript): Ormorok log errors (#2241)

## 2019-09-11
- fix(Core/GameObjectScript): Load ICC Scourge Teleport gossip from DB (#2192)

## 2019-09-10
- Import pending SQL update file...
- fix(DB/Creature): Gimorak's Den (#2226)

## 2019-09-09
- fix(Core/Worldsession): add option to prevent logout when AFK in a sanctuary zone (#2205)

## 2019-09-08
- fix(Core/Spell): "Taming the Beast" hunter quests, part 2 (#2271)
- Import pending SQL update file...
- fix(DB/SAI): Quest "Territorial Trespass" (#2217)

## 2019-09-06
- Import pending SQL update file...
- fix(DB/creature): Add random movement to critters in "Pit of Saron" (#2196)
- fix(Core): Build error concerning debug log message (#2265)

## 2019-09-05
- Import pending SQL update file...
- fix(Core/Spell): "Taming the Beast" hunter quests (#2243)

## 2019-09-04
- Import pending SQL update file...
- fix(DB/Core): "Sons of Hodir" quests / areas (#2231)

## 2019-09-03
- Import pending SQL update file...

## 2019-09-04
- feat(Core/Player): Additional option for worldserver config parameter "InstantFlightPaths" (#2246)

## 2019-09-03
- chore(Core/Player): Fix all apply item mods for scale (#2248)
- chore(PRTemplate): Update style pull_request_template.md (#2251)
- Import pending SQL update file...
- fix(SQL): rework dir for sql update (#2250)

## 2019-09-02
- feat(Core): enable C++17 (#2234)

## 2019-09-01
- fix (Core/Vehicle): delay position update in Vehicles, this may be deleted (#2247)
- chore(Core/AI): Convert the hardcoded variadic RAND functions into one C++11 variadic template version. (#2239)

## 2019-08-31
- Import pending SQL update file...
- fix(DB/SAI): Thrym (#2183)

## 2019-08-30
- fix(Core/CreatureScript): Sindragosa - Ice Tomb and Frost Imbued Blade buff (#2210)

## 2019-08-29
- fix(Core/Dungeon): Scourgelord Tyrannus died mid-air. Body got stuck mid-air and can't be looted (#2209)

## 2019-08-27
- Import pending SQL update file...

## 2019-08-28
- fix(DB/creature): Thrall position (Orgrimmar) (#2181)

## 2019-08-26
- refactor(Core/Misc): Rewrite name handling functions that use raw buffers  (#2230)
-  refactor(ItemTemplate): add missing enums + other minor improvements (#2236)
- Import pending SQL update file...
- fix(DB/creature): Random movement "Stoic Mammoth" & "Roaming Jormungar" (#2178)

## 2019-08-25
- fix(bash): update the data files version (#2235)
- feat(CI/Travis): use Ubuntu 18.04 + update min clang version (#2232)

## 2019-08-24
- Import pending SQL update file...
- fix(DB/SAI): Quest "Keeping Pace" (Zamek's Distraction) (#2171)

## 2019-08-23
- chore(authserver): improve startup console logs (#2227)
- fix(db-assembler): error 'cant find any matching row in the user table' (#2202)

## 2019-08-21
- Import pending SQL update file...

## 2019-08-22
- fix(DB/SAI): Stoneskin Gargoyle (Naxxramas) (#2169)

## 2019-08-21
- feat(Core/BG): rewrite invite in bg (#2137)

## 2019-08-18
- fix: revert unwanted Spell changes (#2222)

## 2019-08-17
- chore(CI): disable staging branch (#2221)
- fix(Core/Dungeon): Remove Goblin Rocket Pack from inventory in ICC Gunship Battle (#2191)

## 2019-08-16
- Creature type flags (#2195)

## 2019-08-15
- Import pending SQL update file...
- fix(DB/SAI): The Drakkensryd (#2164)

## 2019-08-14
- fix(Core/Deps): fix build (#2203)

## 2019-08-13
- fix(Core/Deps): Update recastnavigation to last version  (#2189)
- feat(Core/Deps): Added fmt lib (#2190)
- fix(Core/Boss Script): Obsidian Sanctum Bugs Fixed (Cant enter instance while boss in combat , fix HardMode problem with damage drakes before starting boss) (#2130)

## 2019-08-12
- fix(Core): Fix build - C3848 compile error (#2194)

## 2019-08-11
- Import pending SQL update file...
- fix(DB/creature): Thorim position (Temple of Storms) (#2160)

## 2019-08-10
- fix(Core/SpellInfo): Magmadar's Enrage dispel fix (#2146)

## 2019-08-09
- Import pending SQL update file...
- fix(DB/creature): Random movement for "Icemaw Bear" and "Ravenous Jormungar" (#2149)

## 2019-08-08
- fix(Core/Commands): Support morph uint32 ids (#1753)

## 2019-08-07
- fix(Scripts/Karazhan): Cleanup in opera event (#2163)
- Import pending SQL update file...
- fix(DB/SAI): Mirage Raceway - goblin / gnome racing (#2119)

## 2019-08-06
- fix(Core/Instance): Fix instance resetting exploit (#2172)
- feat(Core/CFBG): Added support module mod-cfbg (#2064)

## 2019-08-05
- Updated client data downloader url with vmaps 4.3
- feat(core/AI): implement DoCastSelf helper (#2179)

## 2019-08-04
- Import pending SQL update file...
- fix(DB/Core): Throwing spells for Instructor Razuvious and Drakkari Battle Riders (#2109)

## 2019-08-03
- chore(README.md): add Discord badge (#2162)
- chore: improved pull_request_template.md (#2166)

## 2019-08-02
- Import pending SQL update file...
- fix(DB/SAI): Revamp Crystalweb Cavern (#2105)

## 2019-08-01
- fix(Core/Raid/Boss Script): Naxxramas boss loatheb kill event (#2098)

## 2019-07-31
- fix (Core/Dungeon/Boss Script): Remove Goblin Rocket Pack from inventory. (#2095)

## 2019-07-30
- Import pending SQL update file...
- fix(Core/DB/Quest): Let Them Eat Crow (#1680)

## 2019-07-29
- Import pending SQL update file...

## 2019-07-30
- fix(DB/Waypoint): Saedelin Whitedawn waypoint (#2112)

## 2019-07-29
- Import pending SQL update file...
- fix(DB/Creature): Enslaved Netherwing Drake flying animation (#2093)

## 2019-07-28
- Import pending SQL update file...
- fix(Core/SAI): fix parameters for action type "SMART_ACTION_UPDATE_TEMPLATE" (#2131)

## 2019-07-27
- fix(Core/Achievements): Skill achievements (#2114)
- fix(Core/Quest): Scratches (#2090)

## 2019-07-26
- Fix client game crash with invite player to invalid name for Channel. (#2087)

## 2019-07-25
- Import pending SQL update file...
- fix(DB/Quest): Ending their world (#2102)
- fix(Core/Dungeon/Boss Script):  Halls of Stone - Brann Respawn - Naxxaramus Noth Teleport phase Bug - Ulduar StormcCaller Brundir inFly Die Bug (#2063)

## 2019-07-24
- Import pending SQL update file...

## 2019-07-25
- fix(DB/gameobject): Band-aid fix for Malygos platform (#2085)

## 2019-07-24
- Import pending SQL update file...
- fix(DB/CreatureScript): The Lurker Below (#2083)

## 2019-07-23
- Import pending SQL update file...
- fix(Core/Spell): Flame Breath (Catapult) (#2115)

## 2019-07-22
- Import pending SQL update file...

## 2019-07-23
- fix(DB/CreatureScript): Deathblow to the Legion (#2080)

## 2019-07-22
- chore(PR template): automatically add instructions for testing (#2066)

## 2019-07-21
- Import pending SQL update file...
- DB/SAI: actually execute Technician Zhanaa's script on quest turn-in (#2078)

## 2019-07-20
- Import pending SQL update file...

## 2019-07-21
- fix Emalon Loot (#2068)

## 2019-07-20
- fix(Core/Boss): Boss Urom (#2110)
- fix(Core/Battleground): Warsong flags can be picked up while mounted (#2067)

## 2019-07-19
- Import pending SQL update file...
- fix(DB/Core): Dragonflayer Strategist spell "Hurl Dagger" (#2060)

## 2019-07-18
- fix(Core/Boss Scripts): Update boss_hodir.cpp - Fix ice shards cast speed in 10 man (#2050)
- Import pending SQL update file...
- fix(DB/SAI): Overthane Balargarde (#2058)

## 2019-07-17
- Import pending SQL update file...
- fix(DB/Gameobject): Pumpkin wrong placement (#2057)
- refactor(Naxxramas): code cleaning (#2015)

## 2019-07-16
- fix(Core/CreatureScript): fix Skadi / Grauf text error (#2052)

## 2019-07-15
- Import pending SQL update file...
- fix(DB/SAI): fix a few issues for Jotunheim (#2047)

## 2019-07-14
- Import pending SQL update file...
- fix(DB/SAI): fix movement / SAI errors (#2041)

## 2019-07-13
- fix(Core): Online status of accounts (#2037)
- Import pending SQL update file...
- fix(DB/Creature): Razorscale Harpoon Fire State (#2036)

## 2019-07-12
- Import pending SQL update file...
- fix(DB/Creature): High Overlord Saurfang (#2034)

## 2019-07-11
- Import pending SQL update file...
- fix(DB/Quests): For Great Honor & Concerted Efforts (#2033)

## 2019-07-10
- Import pending SQL update file...

## 2019-07-11
- fix(DB/gameobject): Faction+flags ID 184632 (#2031)

## 2019-07-10
- Import pending SQL update file...
- fix(DB/creature_text): "Scarlet Medic" / "Scarlet Infantryman" (#2029)
- Import pending SQL update file...
- feat(Core/Pool): improve pool manager (#2027)

## 2019-07-09
- Import pending SQL update file...
- fix(DB/Creature): Fixing reports related to DB, SAI, Text (#2022)

## 2019-07-08
- Import pending SQL update file...

## 2019-07-09
- fix(DB/Creature): Flatland Prowler SAI (#2021)

## 2019-07-08
- feat(Core): GUID recycler (#1820)

## 2019-07-07
- Import pending SQL update file...
- fix(DB/SAI): quest "When All Else Fails" (#2017)

## 2019-07-06
- Import pending SQL update file...

## 2019-07-07
- fix(DB/Creature): Kargath Grunt equipment (#2016)

## 2019-07-06
- Import pending SQL update file...
- fix(DB/Creature): Warsong Marksman's corpses (#2013)

## 2019-07-05
- Import pending SQL update file...
- fix(DB/Quest): Fix Fire At Will! (#1699)
- [CFBG module part 3] Core/BG: Rework functions, delete ASSERT's. (#2010)
- Import pending SQL update file...
- fix(DB/Creature): Ribbon Pole Dance NPC's (#2059)

## 2019-07-04
- fix(Core/Wintergrasp): Leaving Wintergrasp with the minimap button (#2018)

## 2019-07-03
- fix(Core/Wintergrasp): Spam msg's (#2040)

## 2019-07-02
- Import pending SQL update file...

## 2019-07-03
- fix(DB/Spell): Argent Dawn trinkets (#2007)

## 2019-07-02
- Import pending SQL update file...
- fix(DB/SAI): Mini Diablo, Panda Cub, Sleepy Willy (#2011)

## 2019-07-01
- Import pending SQL update file...
- fix(DB/Creatures): Living & Mature lasher (#2006)

## 2019-06-30
- Import pending SQL update file...

## 2019-07-01
- fix(DB/Creature/Event): Arena Vendors & Creatures (#2002)

## 2019-06-30
- Import pending SQL update file...
- fix(DB/Creature): Ulathek aggro text (#2000)

## 2019-06-29
- feat(Core/SAI): improve SAI logging for missing creature text (#2023)
- Import pending SQL update file...
- fix(DB/SAI): Zergling vs Grunty (#1998)

## 2019-06-28
- Import pending SQL update file...
- Fix(Core/DB): Naxxramas overhaul (#1657)
- Let's make it clear. (#1991)

## 2019-06-26
- Import pending SQL update file...
- fix(Core/Spell): Haunted Memento (#1992)
- fix(Core/Creature): Mature Netherwing Drake (#1987)

## 2019-06-25
- Import pending SQL update file...
- fix(DB/Core): "Battle for the Undercity" buffs (#1986)
- feat(Core/Player): Added new functions for `BGData` (#2009)
- feat(Core/Hooks): Added new BG hooks (#2008)

## 2019-06-24
- fix(Core/Spell): Holy Priest Tier 5 Greater Heal Refund proc (#1985)
- chore(core): fix indentation (#1983)

## 2019-06-23
- Import pending SQL update file...
- fix(DB/SAI): Orbaz Bloodbane - Ominous Cloud (#1977)
- Import pending SQL update file...
- fix(DB/Creature): Quintis Jonespyre gossip menu (#1970)

## 2019-06-22
- Sartharion Boundary (#1967)
- fix(Core/npc_professions): Swordsmith specialization (#1966)

## 2019-06-21
- Import pending SQL update file...
- fix(DB/SAI): Death Knight Adept mass spawn (#1962)

## 2019-06-20
- Import pending SQL update file...
- fix(DB/Creature): Venture Co. Strip Miners now move/attack/cast (#1973)
- Import pending SQL update file...
- fix(DB/npc_vendor): Empty vendors honor/arena S6 horde side (#1960)

## 2019-06-19
- Import pending SQL update file...
- fix(DB): King Krush (#1958)
- Import pending SQL update file...
- fix(DB/Creature): FixCreature Sporebat+Greater Sporebat+Young Sporebat+Sporewing (#1953)

## 2019-06-18
- fix(Core/Spell): Target "TARGET_DEST_CHANNEL_TARGET" (#1979)
- Import pending SQL update file...
- fix(DB/SAI): Chicken Escapee (#1954)

## 2019-06-17
- Import pending SQL update file...
- fix(Core/Spells): Spell ID Shadow Ward (Warlock) (#1971)
- fix(Core/BG): prevent potential crash in BG (#1931)

## 2019-06-16
- Import pending SQL update file...
- fix(DB/SAI): Thalgran (#1952)
- Import pending SQL update file...
- fix(DB/SAI): Serfex the Reaver (#1951)

## 2019-06-15
- Import pending SQL update file...
- fix(DB/Quest): Tormented By the Past (#1972)
- fix(Core): check quest conditions on item equip (#1936)

## 2019-06-14
- Import pending SQL update file...
- fix(DB/Core): Play "Lament of the Highborne" as music instead of sound (#1926)

## 2019-06-13
- Import pending SQL update file...
- fix(DB): Dismiss Frenzyheart companion (#1945)

## 2019-06-12
- Import pending SQL update file...
- fix(DB/Spell): Judgement of wisdom/light procs (#1943)

## 2019-06-11
- Import pending SQL update file...
- fix(DB/Quest): Horn Fragment (#1933)

## 2019-06-10
- Import pending SQL update file...
- fix(Core/Quest): Memories of Stormhoof (#1930)

## 2019-06-09
- feat(Core/Player): PartyLevelReq invite settings (#1919)

## 2019-06-08
- Import pending SQL update file...
- fix(DB/SAI): Various fixes for Mogor (Ring of Blood) (#1912)
- feat(Core/Eluna): PLAYER_EVENT_ON_SPELL_CAST (#1624)

## 2019-06-06
- Import pending SQL update file...
- fix(DB/Creature): Hide various dungeon creature triggers (#1924)
- Import pending SQL update file...
- fix(DB/Gameobject): Empty Cauldron (#1911)

## 2019-06-05
- Import pending SQL update file...
- fix(DB/Core): Fix some issues concerning "Thorim's Charm of Earth" (Mending Fences) (#1910)

## 2019-06-04
- fix(Core/Spell): Big Blizzard Bear (#1905)

## 2019-06-03
- Import pending SQL update file...
- fix(DB/Quest): The Key of Warlord Zol'Maz (#1904)
- Import pending SQL update file...
- fix(DB/SAI): Ring of Blood creature despawn (#1901)

## 2019-06-02
- Import pending SQL update file...
- fix(DB/Quest): "Defeat the Gearmaster" / "The Gearmaster" (#1894)

## 2019-06-01
- Import pending SQL update file...
- fix(DB/Core): Mother Smolderweb (#1886)
- fix(SQL): solve critical issue #1921 (#1922)
- Import pending SQL update file...

## 2019-05-31
- fix(DB/Creatures/Objects): Revamp Wintergarde mine to include more mobs and mineral nodes (#1880)
- fix(DB/Creature): Hide creature trigger on Shirrak the Dead Watcher  (#1909)
- Import pending SQL update file...
- fix(DB/SAI): Wastewalker Slave&Wastewalker Worker (#1881)

## 2019-05-30
- fix(Core): Bag/Fishing pole equip (#1860)

## 2019-05-29
- refactor(Docker): fix codacy warnings (#1902)
- Import pending SQL update file...
- fix(DB/SAI): Quest "Jack Likes His Drink" (#1875)

## 2019-05-28
- fix(Core/Spells): Shaman Reincarnation (#1844)

## 2019-05-27
- Import pending SQL update file...
- fix(DB/Gameobject): Spire Spider Egg Trap (#1873)

## 2019-05-26
- Import pending SQL update file...
- fix(DB/SAI): Fix some db errrors (#1865)
- fix(DB/Quest): Dark Iron Legacy (#1861)
- Core/Spells: Fix wintergrasp spells yards (#1842)
- Improved check (#1831)
- fix(DB/Quest): Going Bearback SAI (#1864)
- fix(DB/SAI): Defias Taskmaster on loot (#1866)
- fix(Core/Raid): Vault of Archavon stomp (#1871)

## 2019-05-25
- Import pending SQL update file...
- fix(DB/Gossip): Stormpike Quartermaster (#1827)

## 2019-05-24
- fix(CORE): Low-level quests blue "!" instead of yellow w/ tracker (#1867)
- Import pending SQL update file...
- fix(DB/Quest): The Assassination of Harold Lane (#1859)

## 2019-05-23
- Import pending SQL update file...
- fix(DB/SAI): Watchman Doomgrip / Warbringer Construct (#1872)
- Import pending SQL update file...
- fix(Core/Raid): Reworked Archimonde fight (#1691)
- Import pending SQL update file...
- fix(Core/Waypoint): Drakkari Gutripper (#1848)

## 2019-05-22
- Import pending SQL update file...
- fix(DB/Waypoints): Guardian Lasher & Winter Revenant (#1847)

## 2019-05-21
- feat(Core/Icons): New look (#1840)
- fix(Core/Combat): Casters combat (#1839)

## 2019-05-20
- Import pending SQL update file...
- fix(DB/SAI): Fizzcrank Bomber (#1838)
- Import pending SQL update file...
- fix(DB/Quest): A Spirit Ally QuestId 9847 (#1837)

## 2019-05-19
- Import pending SQL update file...
- fix(DB/SAI): Overseer Deathgaze (#1832)

## 2019-05-18
- Import pending SQL update file...
- fix(DB/Core): Emotes / reaction during quest "The Taste Test" (#1795)
- Import pending SQL update file...
- fix(DB/Creature); Kelgruk Bloodaxe (#1830)

## 2019-05-17
- Import pending SQL update file...

## 2019-05-18
- fix(DB/Fishing): Fix db errors (#1828)

## 2019-05-17
- Import pending SQL update file...
- fix(DB/Gameobject): Missing in DB (Giving conflicts on quest) (#1829)
- Import pending SQL update file...
- fix(DB): Defendo-tank 66D - fix target of "say" action (#1819)

## 2019-05-16
- fix(Core/SAI) Add missing parameters for SMART_ACTION_MOVE_TO_POS (#1813)

## 2019-05-15
- Import pending SQL update file...
- fix(DB) TC Alignment - Characters arena stats (#1810)
- Import pending SQL update file...
- fix(DB/Creature): Deadmines Pathing for 23 creatures (#1808)

## 2019-05-14
- Import pending SQL update file...
- fix(Core/Dungeon) Blackrock Depths - Ambassador Flamelash (#1803)
- Import pending SQL update file...
- fix(DB/Quest): Healthy Dragon Scale (#1807)

## 2019-05-13
- Import pending SQL update file...
- fix(DB/Creature): Delete creature, wrong spawn (#1804)
- Import pending SQL update file...
- feat(Core/Commands): Arena command (#1798)

## 2019-05-12
- Import pending SQL update file...
- feat: Add creation_date column to characters table (#1825)
- Import pending SQL update file...
- fix(DB/Quest): Returning the Favor (#1797)

## 2019-05-11
- Import pending SQL update file...
- Import pending SQL update file...
- fix(DB/Creature): Delete some creatures in Dragonblight (#1816)
- fix(DB/SAI): Bleeding Hollow Riding Worg despawn (#1799)
- Import pending SQL update file...
- fix(DB/SAI): Void Spawner - Quest - Warp Rifts (#1796)

## 2019-05-10
- fix(Core): Auth/World conf.dist corrections (#1801)
- Import pending SQL update file...
- fix(DB): Raised Mud Despawn (quest "An Embarassing Incident") (#1794)
- fix(Core/Dungeon) BRD - The seven minibosses re-order (#1792)

## 2019-05-09
- Import pending SQL update file...
- fix(DB/SAI): Blackrock Depths creatures (#1791)
- Import pending SQL update file...
- fix(DB): Sturdy Vine Despawn (quest "Some Make Lemonade, Some Make Liquor") (#1790)

## 2019-05-08
- Import pending SQL update file...
- feat(Core/Commands): Deserter command (BG/Instance) (#1786)
- fix(Core): increase visibility distance of large game objects (#1788)

## 2019-05-07
- Import pending SQL update file...
- fix(DB/Quest): Gaining Acceptance (#1777)
- Import pending SQL update file...
- fix(DB/SAI): Skorn (#1780)

## 2019-05-06
- Import pending SQL update file...
- fix(DB/SAI): Darkspear Spear Thrower (#1763)

## 2019-05-05
- Import pending SQL update file...

## 2019-05-06
- fix(DB/SAI): Alterac Valley mobs movement (#1761)

## 2019-05-05
- fix(CORE/Quest): Death's Challenge gossip menu (#1755)

## 2019-05-04
- Import pending SQL update file...
- fix(DB/SAI): Teldrassil missing SAI (#1750)
- Import pending SQL update file...
- fix(DB/SAI): Bloodmyst Isle missing SAI (#1749)

## 2019-05-03
- Import pending SQL update file...
- fix(DB/Creature): NPC Ethereum guardian (#1742)

## 2019-05-02
- Import pending SQL update file...

## 2019-05-03
- fix(DB/SAI): phasing after reward for "Return To Angrathar" (#1747)

## 2019-05-02
- fix(Core/Raid): Ulduar - Kologarn (#1785)

## 2019-05-01
- Import pending SQL update file...
- fix(DB/Creature): Dalaran creatures speech (#1752)
- fix(CORE/Commands): .Pinfo - Show guild informations (#1775)

## 2019-04-30
- Import pending SQL update file...
- fix(sql): Eversong Woods missing SAI (#1751)
- Import pending SQL update file...
- fix(DB/SAI): Trident of Naz'jan to SAI (#1736)

## 2019-04-29
- fix(Core/Spells): Change to the way the spell effect SPELL_EFFECT_JUMP work.  (#1696)

## 2019-04-28
- Import pending SQL update file...
- fix(DB/Quests): Blood Elfs starting zone quests for classes (#1739)

## 2019-04-27
- fix(CORE/Battleground): Captain Galvangar position (#1762)
- Import pending SQL update file...
- fix(DB/Creature): Coilskar defender (#1743)

## 2019-04-26
- Import pending SQL update file...
- fix(DB/SAI): fix mini-event for quest "All Hail Roanauk!" (#1735)

## 2019-04-25
- fix(CORE): Increase C'Thun Dark Glare spell timer (#1754)
- feat(Core/Quest): Quest item reward (#1733)

## 2019-04-24
- fix(CORE/Spells): Druid forms (#1732)

## 2019-04-23
- fix(CORE/Spells): Shadowmourne spell effect (#1731)
- fix(CORE/Raid): Obsidian Sancturn - Tenebron (#1726)

## 2019-04-22
- fix(CORE/Raid): Molten Core - Ragnaros hammer orientation (#1683)
- Import pending SQL update file...
- fix(DB/SAI): Head of Nefarian (A&H) (#1729)

## 2019-04-21
- fix(Core): implement "SCRIPT_COMMAND_MOVEMENT" (35) to fix Defias Thug waypoint errors (#1721)

## 2019-04-20
- Import pending SQL update file...
- Fix(DB/Core): UBRS - General Drakissath (#1703)

## 2019-04-19
- Import pending SQL update file...
- fix(Core/DB): Hardcoded text - Eastern Kingdoms (#1640)

## 2019-04-18
- Import pending SQL update file...
- Fix(DB/Core): Dragonmaw Peon AI (#1722)
- Import pending SQL update file...
- Fix(DB/Gameobject): Neferian head spawntime updated to 2 hours (#1711)
- fix(DB/SAI): battle beneath the dark portal (#1719)
- Fix(DB/SAI): Creature text for "Battle for the Undercity" (#1720)

## 2019-04-17
- feat(Cmake/MYSQL): Correct support MariaDB for windows (#1674)

## 2019-04-16
- Import pending SQL update file...
- changes to loot from Trinitycore (#1715)

## 2019-04-15
- Import pending SQL update file...
- DB/Creature: Grom'tor, Son of Oronok (#1716)

## 2019-04-14
- Import pending SQL update file...
- fix(DB): Training the Beast quest reward text (#1714)

## 2019-04-13
- Import pending SQL update file...
- feat(core): Increased limit of realms (#1664)

## 2019-04-11
- Import pending SQL update file...

## 2019-04-12
- fix(DB/SAI): Shadowlord Deathwail (#1705)

## 2019-04-10
- chore(git): Add a commit template & introduce new guidelines (#1044)

## 2019-04-09
- Fix(Core/Spells): Fix parry aura spells (#1694)
- Import pending SQL update file...
- Fix(DB/SAI): Desolace AI for centaurs (#1682)

## 2019-04-08
- fix(Docker): allow to use modules (#1558)
- fix(CI): fix paths for dry-run check (#1697)

## 2019-04-07
- Import pending SQL update file...
- DB/Quest: Head of Nefarian (A) (#1662)
- fix(Core/Battlegrounds): log errors about creatures not found (#1587)

## 2019-04-06
- feat(CI): Travis check modules (#1663)
- Import pending SQL update file...
- Fix(Core/BG): Queue Announcer FIX (#1643)
- Import pending SQL update file...
- Core/ICC: Lady Deathwhisper (#1630)

## 2019-04-05
- Import pending SQL update file...
- feat(Core/Commands): Quest Add (#1673)
- Fix(DB/Misc): Borean Tundra SAI (#1681)
- Import pending SQL update file...
- Fix(DB/Quest/Gameobject): Despawn time for The Lord of Blackrock (#1686)
- Import pending SQL update file...
- Fall From Grace (#1665)
- fix(Core/Eluna): fix compiler warning concerning Eluna (#1671)

## 2019-04-04
- feat(Core/Library): Rename shared library to common (#1675)
- fix(Cmake/Eluna): Add Eluna files in game lib (#1668)

## 2019-04-02
- Import pending SQL update file...
- Fix(DB/Creature): Spirit of Olum and Spirit of Udalo (#1650)
- Import pending SQL update file...
- Fix(DB/SAI): Rough Stone & Dragonmaw Bonewarder (#1656)
- fix(Core): fix a few issues with "Battle for the Undercity" (#1648)
- feat(Cmake): Add new hook AFTER_LOAD_CMAKE_MODULES (#1670)
- Import pending SQL update file...
- DB: Shattered sun marksman SAI (#1038)
- feat(Cmake): Rewrite build and use inherited dependencies (#1652)

## 2019-03-30
- Import pending SQL update file...
- Fix(Core/Player: On first login cinematics (#1617)
- DB/Core: Heroes of old Blizzlike and Fix (#1646)
- fix(Core/Commands): Learn spell for GM lvl 3 (#1651)

## 2019-03-28
- Import pending SQL update file...
- chore(Docker): add comments to explain the building steps (#1638)
- Fix(DB/Quest): Data Rescue (#1645)

## 2019-03-27
- Fix(Core/Scripts): NPC Iruk gossip from DB (#1632)
- Feat(Core/Item): Proper way to add item signature (#1623)
- Import pending SQL update file...
- fix(DB/SAI): despawn Jenny when quest "Load'er Up!" is complete (#1641)
- Import pending SQL update file...
- fix(DB): Fezzix "jumping" through the air (#1634)

## 2019-03-26
- Import pending SQL update file...

## 2019-03-27
- fix(DB/Core): quest chain leading to "Battle for the Undercity" (#1629)

## 2019-03-26
- Import pending SQL update file...
- feat(Core): Changing max pass size (#1626)
- Fix(DB/Quest): Blueleaf Tubers (#1633)
- Core/Misc: Replace ACE_UINT* to uint* (#1628)
- fix(CI): prevent failing Travis runs (#1631)

## 2019-03-25
- feat(DB): Keeping database names consistent troughout the system (#1603)

## 2019-03-26
- Refactor(Core/Misc): Remove remaining COMPILER_HAS_CPP11_SUPPORT related macros (#1627)

## 2019-03-25
- Import pending SQL update file...
- Fix(DB/Quest): Assassin's Contract & Baron's Demise (#1616)
- Refactor(Core/Gossip): Replacing old macros with new (#1338)
- Import pending SQL update file...
- Rewrite(Core/BanManager): Rewrite Ban system (#1576)

## 2019-03-24
- Import pending SQL update file...
- Fix(DB/Quest): Heroes of Old (#1607)
- Feat: Add Codacy badge (#1622)
- Fix(Core/Quest): Correct add locale in quest (#1614)
- Import pending SQL update file...
- Fix(Core/DB/Ulduar): Assembly of Iron (#1615)

## 2019-03-23
- Import pending SQL update file...
- Fix(DB/NPC): Librarian Garren (#1610)
- Import pending SQL update file...
- Fix(DB/Quest): Ogre Head On A Stick (#1608)
- Fix(Core/Player): fix periodic eating and drinking emotes (#1602)

## 2019-03-22
- Import pending SQL update file...
- refactor(DB/world): graveyard_zone (#1599)
- Import pending SQL update file...
- Fix(DB): Fixing several Npc issues (#1596)
- Import pending SQL update file...
- DB restructuring - world - achievement_reward (#1598)
- Import pending SQL update file...
- fix(DB/Quest): WANTED: Boss Grog'ak (#1589)

## 2019-03-21
- Import pending SQL update file...
- Skill perfect item template (#1564)
- Switch to C++14 to solve compilation issues (#1595)
- Feat:Update README.md (#1594)
- Fix(Core/Common): Added header <unordered_map> in file DBCStore.h (#1592)

## 2019-03-20
- Fix(Core/Ticket System): Ticket comment visual output bug  (#1567)
- feat(Core/Chat): Add config option to allow use LFG anywhere not only in city (#1586)

## 2019-03-19
- Import pending SQL update file...
- fix(DB): Fjord Hawk, Fjord Turkey (#1584)
- Import pending SQL update file...
- fix(DB/Core): play event after quest "Hero of the Mag'har"; extend SAI to play music (#1570)

## 2019-03-18
- Import pending SQL update file...
- fix(DB): a few improvements to the giant wandering outdoor creatures (#1579)
- Import pending SQL update file...
- fix(DB): zeppelin master - remove gossip option "Where is the zeppelin now?" (#1578)
- Fix(Core): GM command not working while GM mode is on (#1581)

## 2019-03-16
- feat(CI): improve Travis build time (#1573)

## 2019-03-14
- Import pending SQL update file...
- Fix(Scripts/Instances/Oculus): improvements (#1498)
- Import pending SQL update file...
- fix(DB): Malmortis creature text (#1572)
- fix(Core/WorldSession): change how to storing data in account_tutorial (#1563)
- Fix(Scripts/Spells): Check range to fire totem when casting Fire Nova. (#1566)

## 2019-03-11
- fix(Core/Player): close all character tickets when delete (#1565)

## 2019-03-09
- fix(Core/Commands): fix reload creature_template and creature movment
- fix(Modules): solve breaking change (#1561)

## 2019-03-07
- Import pending SQL update file...
- fix(core): prevent unsupported-by-client passwords (#1547)

## 2019-03-05
- feat(core): allow to debug KickPlayer() (#1549)
- feat(cpp): enable C++17 support (#1553)

## 2019-03-03
- fix(Docker/macOS): solve disconnection issues (#1552)
- feat(core): allow to disable auto-kick for idle players (#1550)
- Import pending SQL update file...
- Fix(Core/Ulduar): Multiple fixes to Flame Leviathan (#1487)
- feat(Core/Movement): Implement move time skipped handler  (#1433)
- Eluna: load the configuration file using the new method. (#1546)
- fix(Docker): no need to duplicate *.dist files (#1551)

## 2019-03-02
- feat(modules): Allow modules to extend Battlegrounds (#1444)

## 2019-02-28
- Import pending SQL update file...
- fix(DB/creature): correct phaseMask of NPC Ravenous jormungar (#1523)

## 2019-02-27
- Import pending SQL update file...
- fix(Core/DB/Quest): Battle for the Undercity (#1479)

## 2019-02-26
- Core/ChatHandler: Update Addon message read fix (#811)

## 2019-02-25
- Import pending SQL update file...
- fix(DB): Pit of Saron intro (#1517)
- feat(CI): add commit hashes to the automatic SQL import (#1516)

## 2019-02-24
- chore(readme): fix stackoverflow default view
- Import pending SQL update file
- feat(Commands): Added cheat commands (#1412)

## 2019-02-23
- feat(docker): add cache for faster rebuild (#1507)
- Import pending SQL update file
- fix(DB/Item): Hateful Gladiator's Longbow No Range (#1492)

## 2019-02-22
- feat(CI): dynamically calculate thread count for build process (#1510)
- Core/Skills: Add FishingBaseSkillLevel dynamic change method (#1511)

## 2019-02-21
- Import pending SQL update file
- fix(DB/Quest): Morrowgrain to darnassus (#1490)

## 2019-02-20
- style(cpp): DBC AchievementCriteriaTypes indentation
- fix(CI): break on errors in CI scripts (#1504)

## 2019-02-19
- Core/Eluna: Hotfix call sEluna->OnGameEventStart method arg register (#1500)
- feat(CI): improve Travis configuration (#1486)
- Core/Hooks: Adds hooks for start and stop game events (#1472)

## 2019-02-18
- Core/Hooks: Add new Player hooks (#1481)

## 2019-02-17
- chore(docs): use new wiki
- fix(CI): Travis triggers the AC bot only once (#1484)
- Import pending SQL update file
- fix(DB): sql update chain for all DBs
- DB: Fixing some issues (#1474)
- fix(DB): update chain after release
- DB squash & begin AC 3.0.0 development
- Import pending SQL update file
- AzerothCore 2.0.0
- fix(Bash/Exporter): fix path + add prompt to prevent wrong usage (#1477)

## 2019-02-16
- Import pending SQL update file
- fix(DB): added missing SQL part of #1371 (#1478)
- Import pending SQL update file
- fix(DB/Quest): solved three Quest issues (#1443)
- fix(instance): Ruby Sanctum - Resistances ignored (#1371)
- fix(setup): MySQL 5.7 (#1445)
- fix(sql): correct mistake in update file (#1473)

## 2019-02-15
- Import pending SQL update file
- DB/Creature: Strange Winged Goblin (#1468)
- Revert "feat(core): Ensure that all actions are compared to fixed point in time (#1236) (#1458)" (#1471)

## 2019-02-14
- Import pending SQL update file
- fix(DB/Quest): Fall From Grace (#1466)
- fix(DB/Creature): NPC Rabine Saturna missing text (#1460)
- fix(Core/Instances): instance reset (#1416)
- refactor(DB/Quest): move 4866 and 4224 from cpp to DB (#1415)
- fix(DB): correct mistake in sql update file
- Import pending SQL update file
- chore(DB): set main DB version
- feat(core): Ensure that all actions are compared to fixed point in time (#1236) (#1458)
- fix(Core/Player): achievements activation (#1463)
- feat(Core/LOS): restruct LOS functions and add LineOfSight check (#1459)

## 2019-02-12
- fix: windows build (#1455)
- Import pending SQL update file
- feat(Command): Remove spy command from AC and make it a module (#1401)
- refactor(Scripts/SpellGeneric): use modern C++ array instead of C array (#1436)

## 2019-02-11
- Import pending SQL update file
- fix(DB/Quest): Hunting for Ectoplasm (#1441)
- feat(Travis): speed up and stabilize build process (#1410)

## 2019-02-10
- Import pending SQL update file
- fix(DB/Quest): The Shimmering Frond (#1440)
- chore(PCH): remove "ScriptPCH.h" from cpp scripts (#1423)

## 2019-02-09
- fix(clang): fix build on version 7 (#1391)
- feat(Core/Misc): compatibility with 10.2+ versions of MariaDB library (#1284) (#1437)

## 2019-02-08
- Import pending SQL update file
- feat: Added logs_ip_action + more (#1157)

## 2019-02-07
- [Core /Script] Added On player complete quest hook (#1427)
- Import pending SQL update file
- fix(DB): prevquest for "Rejold's New Brew" (#1409)

## 2019-02-06
- feat(CI): prevent PRs that cause DB errors to get on master (#1407)
- Import pending SQL update file
- fix: remove data for unsupported criteria type (#1405)
- Import pending SQL update file
- feat(DB/Creature): Add Troll Roof Stalkers (#1414)

## 2019-02-05
- fix(DB): mail_loot_template startup errors (#1404)

## 2019-02-04
- Import pending SQL update file
- Fix(DB): Backbiter movement + missing texts in Dalaran (#1384)
- Update README.md
- Import pending SQL update file
- fix: spell_scripts DB startup errors (#1406)

## 2019-02-03
- Import pending SQL update file
- fix(DB): positioning of the control console on the zeppelin "Cloudkisser" (#1400)

## 2019-02-02
- fix(gobject): elevator bug + prevent bugs related to faction and flags (#1402)
- Core/Spells: Mage permafrost talent (#1389)

## 2019-02-01
- Import pending SQL update file
- fix(DB/SAI): Rift Spawns (Mage quests) (#1383)
- Import pending SQL update file
- [Core/ Spell] Val'anyr Hammer of Ancient Kings Fix (#1388)

## 2019-01-31
- Import pending SQL update file
- fix(DB): solved several issues (#1375)

## 2019-01-30
- style: Reorder DBs in config.sh.dist (#1353)
- [Core / Spell] Fixed Amplify Damage (#1387)

## 2019-01-29
- Import pending SQL update file
- feat(conditions): prevent adding bad contitions + align enums with TC (#1381)
- Import pending SQL update file
- refactor: Quest 5742 moved from core to DB (#1354)
- fix(docker): align generate-database.sh to db-asm script output renames

## 2019-01-28
- Import pending SQL update file
- feat(gameobject): allow gameobjects to loot money + align table with TC (#1368)
- fix(quest): fix some quest chains + align NextQuestID with TC (#1351)
- feat(SmartAI): display error on unsupported targets + align TC enums (#1349)

## 2019-01-27
- fix(Core/Command): fix startup error
- fix(travis): prevent failures in forks

## 2019-01-26
- fix(travis): remove command duplication that was causing failure
- chore(readme): added Docker reference in README.md
- feat(SmartAI): Implement action type 115 "SMART_ACTION_RANDOM_SOUND"
- fix(travis): attempt to fix staging branch auto-update
- Import pending SQL update file
- fix(DB/Quest): Mage Summoner (#1341)

## 2019-01-25
- Import pending SQL update file
- fix(DB/SAI): Lazy Peons quest (#1348)
- feat(travis): keep staging branch up to date

## 2019-01-24
- Import pending SQL update file
- feat(SmartAI): improve add quest action (#1333)

## 2019-01-23
- chore(bot): improve layout of travis bot commits (#1347)
- feat(SmartAI): handle unused SmartActions (#1335)

## 2019-01-22
- Importing pending sql

## 2019-01-23
- DB: Fix crash in waypoint_scripts (#1342)

## 2019-01-22
- chore(README.md)
- chore(db_assembler): Changed var name (#1091)
- fix(Docker): solve bug in Windows installation
- Importing pending sql
- fix(DB/Command): Add help options for .spy command (#1339)
- [Core / Script] Mr Smite Event Update (#1340)

## 2019-01-20
- Importing pending sql
- DB/Quest: Quest 11223 moved from core to DB (#1334)
- Importing pending sql
- refactor(SmartAI): move AC-only SMART_ACTIONs to avoid conflicts with TC
- Importing pending sql
- refactor(SmartAI): align some SMART_ACTION(s) to TC (#1329)
- Importing pending sql
- Core/DB: refactor(creature_template): closes #1181 (#1322)
- Importing pending sql
- refactor(DB-world): minor changes (#1323)
- Importing pending sql
- refactoring(SAI): add event_param5 and target_param4 (#1324)

## 2019-01-19
- Core/Startup: Empty table should not be a startup error (#1320)
- fix(Core/Quest): Mr.Floppy's Perilous Adventure fix (#1314)
- Fix server motd (#1319)
- Importing pending sql
- Core/Instance: Naxxramas conversation fix (#1304)
- DB/SAI: Add event after finishing quest "Alien Egg" (#1303)
- fix build
- add new lines at the end of files
- fix: server motd

## 2019-01-18
- (chore) Removed broken Coverity badge from Readme

## 2019-01-19
- refactor(sql): Split big update file into smaller ones

## 2019-01-18
- Core/Packets: Fix calendar event time (#1289)

## 2019-01-17
- fix(docker) .env.dist paths format (#1312)
- docker-simplify-database-dockerfile
- Docker/Scripts: fix file permissions
- Core/Spells: Fix DeathKnight T10 Tank 2P Bonus (#1291)

## 2019-01-16
- Make the Docker installation easy
- [CI] Make Travis only import pending sql from master branch (#1297)
- chore: Update copyright note (#1292)
- Fix sql updates chain

## 2019-01-15
- Added Jetbrains to .gitignore & readme
- Core/Commands: Add new spy command (#1263)
- Importing pending sql
- DB/SAI: Fix Arakkoa Egg (#1280)
- Core/MySQL: wait for the DB to be ready (#1286)
- Merge pull request #1255 from poszer/QuestAbandonFinishFix
- Fix build on windows
- Update Player.cpp

## 2019-01-14
- Core/MySQL: wait for the DB to be ready - Closes #1285
- Fix DB import issues (#1283)
- Importing pending sql
- DB/Quest Going Bearback (#1267)
- DB/Quest The Lord of Blackrock (#1254)
- Core/Reload: Delete useless lines for `achievement_reward_locale` (#1277)

## 2019-01-13
- Docker: fix connectivity issues on Mac & Windows (#1275)
- Core/Gossip: improve gossips related to Dual Talent Specialization (#1218)
- Importing pending sql
- Merge pull request #1245 from poszer/UlagtheCleaverQuestFix
- Merge branch 'master' into UlagtheCleaverQuestFix
- CI: fix travis build (#1274)
- Create .gitkeep
- Several improvements to Docker:
- Update rev_1546933586341240000.sql
- Fix bad copy paste in docker README.md

## 2019-01-12
- Importing pending sql

## 2019-01-13
- Core/DB: Update all locales to actual TrinityCore (#1160)

## 2019-01-12
- Fixed permission in docker-database (#1272)
- Update Docker README.md
- Update README.md
- AzerothCore complete Docker solution
- MySQL:  fix MySQL 5.6 find mistake (#1268)
- DBAssembler: Fix incorrect apply sql files at import (#1252)
- Importing pending sql
- DB/SAI: fix Sen'Jin Fetish (#1266)

## 2019-01-10
- Importing pending sql

## 2019-01-11
- DB/Graveyard: Translate comments to English language (#1246)

## 2019-01-10
- Core/Spell: Val'kyr Target Search bypass invuln (#1229)
- Update Player.cpp
- Update Player.cpp
- DB/Quest Ulag the Cleaver
- CMake: Use source_groups to represent the source tree (#1247)
- Update docker README.md
- Dockerize AzerothCore Database

## 2019-01-09
- Merge pull request #1241 from poszer/QuestAbandonFinishFix
- Core/Pet: additional check if it's a creature (#1248)

## 2019-01-08
- Importing pending sql
- DB/Creature Vile Fin & Ragged Scavenger fix (#1243)
- Importing pending sql
- Core/Events: announce event system improvement. (#1228)
- Update zone_tirisfal_glades.cpp
- DB/Quest Ulag the Cleaver
- Importing pending sql
- Core/DBC Move WorldSafeLocs.dbc storage to DB (#932)
- Core/Movement: Prevent pet animation stuttering during movement (#1142)
- Core/Session: proper client timeout detection  (#1232)

## 2019-01-07
- Apps: Add backticks to version_db_* in create_sql.sh (#1244)
- Core/Quests: Abandon&Finish quest items
- Importing pending sql
- Core/Quest: Mr.Floppy's Perilous Adventure Quest (#1158)
- Core/Misc: add support to calculate zoneId/areaId for creatures & gameojects (#1226)

## 2019-01-06
- Importing pending sql
- DB/Core: Proper hover height + flying animations for vanity pets (#1237)
- Importing pending sql
- Update waypoints for black knight in Trail of the champion to be more blizzlike.
- Importing pending sql
-  Core/Quest: implement Quest Tracker (#1233)

## 2019-01-05
- Importing pending sql
- MySQL: account table restructure (#1230)
- MySQL: refuse any version of MySQL, below 5.6 (#1227)

## 2019-01-04
- Importing pending sql
- DB/Creature: Fix pet Sen'jin Fetish model (#1208)

## 2019-01-03
- Importing pending sql
- DB: Flying pets can follow player on flying mount (#1212)
- Core: Vmaps update 4.3 (#1021)
- Importing pending sql
- Update creature & gameobject table structure (#1219)

## 2019-01-01
- Improve issue template

## 2018-12-31
- Importing pending sql
- DB/SAI: Quest Forge Camp Annihilated (#1146)

## 2018-12-30
- Core/World: do not consider error when no player data in the DB (#1151)

## 2018-12-29
- Importing pending sql
- DB/NPC: Quartermaster Bartlett can now repair (#1149)

## 2018-12-28
- Importing pending sql
- DB/SAI: fix Ward of Laze creature (#1145)

## 2018-12-27
- Importing pending sql
- Core/LootMgr: Update lootMgr to normalize loot_template tables (#1137)

## 2018-12-26
- Core/Guilds: fix gcc compile warnings (#1150)
- Importing pending sql
- DB/Players: Apprentice Riding to Death Knight on creation (#810)
- CORE/Crash: Fix crash with MoveSpline [hacky] (#1066)
- CORE/Movement: Fix a potential crash with a player out of bounds. (#970)

## 2018-12-25
- Core/Spell: Hand of Reckoning kills totem & puts in combat (#1139)

## 2018-12-23
- Importing pending sql
- Core/Players: Fixed saving quest item progress  (#1129)

## 2018-12-22
- Importing pending sql
- DB/Creature Add missing pet trainer / NPC text (#1115)
- Scripts/Quest: fix 12733 Death's Challenge (#886)
- Change badges order in README.md
- Fix Coverity badge layout by converting to md
- Remove broken badge from README.md
- Core/Achiev: Fix unwanted GM warnings (#1122)

## 2018-12-21
- Importing pending sql
- DB/Quest: Escape Through Force & Stealth. (#1100)
- CI: Update Ubuntu version of travis build to xenial (16.04)

## 2018-12-20
- DB/Quest: "The Endless Hunger" fix second talk text. (#867)

## 2018-12-19
- Add Installation & Support section in README.md
- Modules: Added create_module.sh script to kickstart module creation (#1071)
- Importing pending sql
- Refactored quest_template table structure

## 2018-12-18
- DB/Typo: Fix column name
- Added Stackoverflow badge in README.md
- Core/Build: Fix windows build for recent OpenSSL versions (#1065)

## 2018-12-17
- Gruul: Add a minimum cooldown for Cave In (#893)

## 2018-12-16
- Core/Instance: Blackrock - Warchief Rend Blackhand
- Importing pending sql
- DB/QUEST/OUTLAND - Deathblow to the Legion  (#1109)

## 2018-12-13
- Core: Fix titles not showing on login (#1114)

## 2018-12-12
- Tabs from the last commit.
- Update PINFO command, show character details like TrinityCore. (#1097)

## 2018-12-11
- Enable SourceType of 8 for Disables table to disable LFG/LFD maps (#1076)
- Importing pending sql
- DB/Quest The Ring of Blood (#1102)
- Importing pending sql
- DB/Quest Steamtank Surprise (#1104)

## 2018-12-09
- Importing pending sql
- DB/Signs Correct road signs
- DB/Quest Steamtank Surprise
- DB/Quest The Ring of Blood

## 2018-12-08
- Core/Achiev: Warning if GM mode enabled (#1028)

## 2018-12-05
- Core/Script: BRD needs to light 2 braziers to open the doors (#1069)

## 2018-12-04
- Core: feature add 2FA (OTP) (#1054)

## 2018-12-03
- Fix import error for the SQL (#1092)

## 2018-11-30
- [Core / Fix] Fixed an issue if charmed creatures was created by spell they wouldn't disappear if owner was too far away from it.

## 2018-11-29
- [Core / Fix] Mage: Empowered Fire Talent

## 2018-11-28
- Core/NPC: Deathstalker Faerleia text translatable in the DB (#1070)

## 2018-11-25
- Importing pending sql
- DB/NPC: fix Darnassus shield merchant missing equipment in hand (#1089)

## 2018-11-24
- Importing pending sql
- DB/SAI: fix tortured skeletons in Shadow Labyrinth (#1088)
- CORE/Spell: add diminishing returns on reflected spell. (#1050)

## 2018-11-22
- Importing pending sql
-  DB/Quest: fix OfferRewardText for The New Horde (#1087)

## 2018-11-15
- Importing pending sql

## 2018-11-16
- DB/Strings: Improve permaban string (#1074)

## 2018-11-01
- Core/NPC: Creatures now alert when they detect stealthed players (#1060)

## 2018-10-30
- Core/Script: Add sounds to quest "Let the Fires Come!" (#1061)

## 2018-10-28
- Core/Conf: Typo in MaxPrimaryTradeSkill desc

## 2018-10-27
- Added missed copyrights to CreatureGroups.cpp
- [Core / Spell ] Warlock Life Tap

## 2018-10-23
- Core/Conf: Fix StartAllReputation from player.cpp (#973)

## 2018-10-21
- README - Removed a dead badge

## 2018-10-17
- Importing pending sql
- Core/Scripts: Unify GOB commands (#1037)

## 2018-10-16
- Importing pending sql
- DB/GOBs: Set pools for Ghostlands Mining (#895)

## 2018-10-15
- Importing pending sql
- DB/NPC: Set correct gossip ID for zeppelin masters (#907)

## 2018-10-04
- CORE/conf: Note about MaxCoreStuckTime danger

## 2018-10-13
- Importing pending sql
- DB/SAI: Add missing scripts to most Silithus mobs (#1031)

## 2018-10-05
- Importing pending sql
- DB/Creatures: Pathing for kodos; random movement for gazelles

## 2018-10-02
- Importing pending sql
- fix(DB/Dungeon): Pit of Saron intro texts

## 2018-09-30
- Revert "Core: Better fix for stuck at "Retrieving character list"" (#1040)

## 2018-09-28
- Merge branch 'master' of https://github.com/azerothcore/azerothcore-wotlk
- Core: Better fix for stuck at "Retrieving character list"

## 2018-09-26
- Importing pending sql
- DB/Conditions: Meridith gossip fix (#1035)

## 2018-09-24
- Importing pending sql
- DB: Grimtotem Naturalist fix (PR #1034)

## 2018-09-05
- Conf - UseProcessors option explained

## 2018-09-23
- Mirror image Update
- grimtotem fix

## 2018-09-20
- [Core/Script] Fixed the amount of mana gained from Life tap
- Core/Script: Warlock lifetap's damage

## 2018-09-17
- Importing pending sql

## 2018-09-18
- Core/Account: Add total time played in account (#1003)

## 2018-09-17
- fixed query of previous commit
- Fixing db importing with new mysql 5.7 installations
- updated client data downloading url

## 2018-09-14
- db_assembler - Readme

## 2018-09-08
- Log unused config options (#999)

## 2018-09-03
- DB/Characters: Remove unused tables "uptime" and "cheaters" (#1000)

## 2018-08-27
- issue_template.md - Reorganisation

## 2018-08-26
- Importing pending sql

## 2018-05-28
- Fix world server crash when using the Atal'ai Statue (ID 148833) in Sunken Temple

## 2018-08-24
- [Bash] fixed menu header display

## 2018-08-19
- Importing pending sql

## 2018-07-20
- MissingCreatureTexts

## 2018-08-13
- Importing pending sql
- Core/Commands: .npc set faction fix and improvement (#1001)

## 2018-08-12
- fix error message and help text for new 'npc set faction' command

## 2018-08-06
- Cmake: Custom cmake options now read (#989)

## 2018-08-05
- Revert "Show default options, missing in config files (#908)"
- Fix travis + compiler script (#997 from Stoabrogga/compiler)
- add "set -e" also to script "db_assembler.sh"
- ignore exit code of 'make clean' as it won't find a Makefile if called as first action (which is the case for "compiler all")
- Updated custom commands made.
- Updated code for New config.

## 2018-08-04
- exit compiler script if any statement returns non-zero exit code

## 2018-07-29
- Merge branch 'master' of https://github.com/azerothcore/azerothcore-wotlk
- New config option added
- fix: config.cmake not work.

## 2018-07-26
- Move preloading in the continent transport check

## 2018-06-13
- And another one...
- Should be out of the check.

## 2018-06-12
- Make the continent transport and preloading optional.

## 2018-07-26
- Simple README error fixed

## 2018-07-22
- Fixed crash issue with death grip from previous commit.
- Added the commands into a sub table
- added two more commands to .npc set

## 2018-07-21
- Fixed Glyph Learning.
- Update Death Grip

## 2018-07-20
- Core: Easy module conf creation & reload (#931)

## 2018-07-18
- Fixed Typo
- Added Hook

## 2018-07-17
- Distro information when install OS deps
- Missing unzip dep for client data downloader
- Fixed simple-restarter script
- Revert WMO changes (#976)
- Missing curl package in unix os deps
- Various fixes to acore dashboard

## 2018-06-24
- Ahn'Kahet: Amanitar should cast the fungus only on players without "Mini" aura.

## 2018-07-16
- Importing pending sql

## 2018-07-15
- DB/Script: Fix Captain Dranarus sound range
- Fixed libssl-dev for latest ubuntu revs on deps installer
- fixed loop with comp_build() function of compiler
- missing executable permissions for *.sh files
- Updated .travis.yml for new bash system
- Rewrite of bash system

## 2018-07-13
- README - db_assembler
- tools improvement (#926)

## 2018-07-12
- Importing pending sql

## 2018-07-04
- Fix NPC 7856 (Southsea Freebooter)

## 2018-06-16
- Fix Fishing's spell cast interruption.

## 2018-07-10
- Github: issue_template made easier to read

## 2018-07-09
- Github: pull_request_template made easier to read 2
- Github: pull_request_template made easier to read

## 2018-06-23
- Core/Scripts: Add SpellSC and new hook OnCalcMaxDuration

## 2018-06-24
- Core/Scripts: Sapphiron fixes..

## 2018-07-06
- Github/pull_request_template.md - Improved
- Github/issue_template.md - Improved
- Removed the set faction from animal blood spell
- Removed comment from hook - No idea why it was there.
- Core/Scripts: Boss Gluth + Spell Infected Wound ... (#937)

## 2018-07-05
- Rogue/Spell: Blade Flurry correctly dmg multiple mobs  (#939)

## 2018-07-04
- Importing pending sql

## 2018-06-29
- Fix Midsummer Celebrants in Tirisfal Glades and add Festival Scorchling

## 2018-07-03
- Update spell_rogue.cpp (#959)

## 2018-07-02
- Importing pending sql
- Fix Maexxna's portal rotation. (#925)
- Fixes Rogue Tier 1

## 2018-06-29
- Importing pending sql

## 2018-06-28
- delete duplicate Midsummer Celebrants in Tanaris; Fire Breathing for all Fire/Flame Eaters
- Added check to player to return if player is in tank spec

## 2018-06-26
- Importing pending sql
- fix faction of Midsummer Celebrant (NPC ID 16781)

## 2018-06-25
- Importing pending sql
- Added missing spirit healer into Stranglethorn vale.

## 2018-06-24
- Fixed Archavon's Stone Breath knockback on tank.

## 2018-06-05
- Add GitRevision

## 2018-06-24
- Core/Spells: Fixed Blade FURry not sharing damage/ignoring armor to additional mobs.

## 2018-06-23
- Importing pending sql

## 2018-01-28
- Fix Lady Deathwhisper intro

## 2018-06-20
- Core Hook - Remove temporary fix and document possible null in hook (#805)

## 2018-06-18
- Merge pull request #930 from Winfidonarleyan/fix_typo
- Fix typo in commit https://github.com/azerothcore/azerothcore-wotlk/commit/049386b93662ad62ea6f779ed5832865ffbde242
- Merge pull request #929 from Winfidonarleyan/bg_hooks
- Core/Scripts: Add BGScripts and new hooks

## 2018-06-17
- BattlegroundMgr - Fixed typo

## 2018-06-16
- Core/Arena: fix auto distribute arena points and config option. (#927)

## 2018-06-15
- Change Trinity Core to AzerothCore in config files (#889)

## 2018-06-12
- Importing pending sql
- Fix Malmortis text (#922)

## 2018-06-11
- Importing pending sql
- Fixed An Unusual Patron (#921)
- Fix Malmortis text (quest "Disclosure", ID 12710)

## 2018-06-08
- Fix brackets from #894
- Add cooldown to Amplify Damage in phase 3 (#894)

## 2018-06-07
- Module hook for kills performed by pets/totems (#912)
- Importing pending sql

## 2018-05-06
- Quest: Captain Garran Vimes - Missing end event Taken over from TrinityCore: https://github.com/Aokromes/TrinityCore/commit/330c48928e0cff07caf928fb93429af0f7994969

## 2018-06-06
- Importing pending sql
- Fix NPC 28611 (Scarlet Captain) in the DK area (#884)
- Importing pending sql
- DK quest chain: Implement reaction for Orgrimmar and Alliance guards while finishing the last quest (#891)
- Change encoding in banner (#911)

## 2018-06-05
- Show default options, missing in config files (#908)

## 2018-06-04
- Fix: Stuck at "Retrieving character list". (#880)

## 2018-05-24
- Scripts - Fixed missing headers

## 2018-06-01
- Importing pending sql
- Merge pull request #898 from pondaveia/scholomance
- Merge branch 'scholomance' of https://github.com/pondaveia/azerothcore-wotlk into scholomance

## 2018-05-31
- Change to UPDATE command to be compliant with AC's guidelines
- Use DELETE-INSERT instead of REPLACE for SQL updates

## 2018-05-30
- scholomance fix

## 2018-05-31
- Change to UPDATE command to be compliant with AC's guidelines
- Use DELETE-INSERT instead of REPLACE for SQL updates

## 2018-05-08
- Bugfix: cast items with target "TARGET_DEST_NEARBY_ENTRY" (e.g. item 7247) did not work because the if-clause only checks valid target units or game objects; fixed via additional check for target object type "TARGET_OBJECT_TYPE_DEST" and a valid target destination

## 2018-05-30
- pull_request_template.md - Small improvement

## 2018-02-26
- Improved description

## 2018-02-24
- Bash scripts conf - Set backup to false by default, fixed typo and added a warning

## 2018-05-30
- scholomance fix

## 2018-05-23
- how_to_make_a_module.md

## 2018-05-30
- LFG - Queue again after dungeon (PR #883)

## 2018-05-26
- Importing pending sql
- Merge pull request #841 from Stoabrogga/terrence

## 2018-05-24
- Importing pending sql
- Merge pull request #879 from Stoabrogga/abandoned_mail

## 2018-05-23
- Improve the pull request template (#882)
- Eluna implementation (#847)

## 2018-05-21
- Importing pending sql

## 2018-05-17
- Cleaning and improvement for AC

## 2018-05-14
- DB - Death Knights area rework

## 2018-05-20
- Importing pending sql
- [Naxxramas] Gothik the harvester minions (#826)
- Change Fear spell of Bleeding Hollow Tormentor from 33924 to 12542, as the former causes Fear on the NPC itself (#842)

## 2018-05-19
- Fix Death Knight quest 12711 "Abandoned Mail": Send letter "News From The North" after completing the quest.

## 2018-05-16
- Missing options in conf file (auth and worldserver)

## 2018-05-13
- Importing pending sql
- Merge pull request #845 from Stoabrogga/undercity_mailbox
- Importing pending sql
- Merge pull request #843 from Stoabrogga/forlorn_spirit

## 2018-05-10
- Update .travis.yml (#861)
- Merge pull request #853 from Viste/pdump

## 2018-05-07
- Merge remote-tracking branch 'azmaster/master' into pdump
- Importing pending sql
- Merge pull request #844 from Stoabrogga/great_one
- Core/Characters: fix player dump load command

## 2018-05-04
- Fix overlapping mailbox in undercity (Trade Quarter, south)
- Fix quest 13956 "Meeting a Great One" (Children's Week)

## 2018-05-03
- Fix Forlorn Spirit (part of the "Legend of Stalvan" quest chain)
- Change the action of Deathguard Terrence in Brill when he reaches the lantern: Use oneshot "laughing" instead of emote state
- Merge pull request #840 from Viste/sslupdate

## 2018-05-02
- Core/Crypto: Transitional Cryptography update for OpenSSL 1.1

## 2018-04-19
- Importing pending sql
- Merge pull request #755 from Nefertumm/PlayerBytes

## 2018-04-09
- Importing pending sql
- missing instance_template scripts
- Merge branch 'master' of https://github.com/azerothcore/azerothcore-wotlk
- Missing override keyword
- Missing ScriptLoaders for missing instance scripts

## 2018-04-08
- Missing scripts for instances

## 2018-04-04
- New Boolean parameter for OnAfterUpdateEncounterState

## 2018-03-26
- fixed some warnings
- Fixed Twilight torment sartharion

## 2018-04-06
- Merge pull request #806 from BarbzYHOOL/trial_of_the_champion_portcullis

## 2018-04-01
- Tome of Valor should no longer desapwn the creature
- Merge pull request #822 from Viste/memoty

## 2018-03-31
- Core/Misc: Fixed memory leak in trade handler
- removed unused code - fix Travis
- Instace to return the guid of the gameobject
- Merge branch 'master' of https://github.com/azerothcore/azerothcore-wotlk
- After killing Rhahk in deadmines the door will now open correctly.

## 2018-03-29
- Importing pending sql
- DB - Areatrigger - Removes warnings when booting the server (#819)
- move a bit of code around for mirror image creatureAI
- More fixes for Mirror Image

## 2018-03-26
- removed extra space

## 2018-03-20
- Fixed Creature_SelectLevel hook
- Implemented OnAfterUpdateEncounterState hook
- Revert "Guild charter should now work as intended."

## 2018-03-19
- Players can now re enter zul'aman after raid wipes.
- Guild charter should now work as intended.

## 2018-03-18
- fixed crash issue is creatures are summoned outside of the instance
- Custom scripts - Style of the readme on Github

## 2018-03-17
- Fix DB type to match core (#809)
- Upon death KT should reopen the door so people can leave.

## 2018-03-15
- if players now wipe the door will Reset.

## 2018-03-14
- Sartharion should despawn all adds updon death.

## 2018-03-12
- Update license links (#783)

## 2018-03-11
- Fix crash with dangling player pointer

## 2018-03-06
- Core/Misc: fix bad dbc data for lock 'Locked ball and chain' Closes #494 author is @ariel- not sure yet how smartgit works...
- Fixed typo in ScriptMgr comments
- Merge branch 'master' of https://github.com/azerothcore/azerothcore-wotlk
- CustomData for Map class
- updated .editorconfig

## 2018-03-05
- Make info messages seem less important (#788)

## 2018-03-04
- Mechanic_immune_mask added in npc info command (#771)
- Fix typo
- Implement RATE_CREATURE_AGGRO
- Fix the North Portcullis in TOC

## 2018-03-01
- Fixed crashes with not initialized CustomData

## 2018-02-28
- Moved ScriptMgr macros to separated header and created ModuleScript

## 2018-02-23
- missing semi-colon in latest sql
- Importing pending sql
- Black Temple's Illidari Council (#790)
- Addon message read fix (#796)

## 2018-02-13
- Merge branch 'master' of https://github.com/azerothcore/azerothcore-wotlk
- Fix for item https://wotlk.evowow.com/?item=50130 Quest: Crushing the Crown

## 2018-02-12
- Add editorconfig (#789)

## 2018-02-09
- Importing pending sql
- Fix heirlooms to apply stats before giving health.

## 2018-02-08
- DB/BWL: Fix eggs being clickable and Grethok should yell when engaged

## 2018-02-07
- DB Assembler: Fixed privileges assignment

## 2018-02-06
- Fix lootable items re-fill when not really empty
- Fixed ossirian crysthal

## 2018-02-04
- Implement Rate.Auction.Deposit

## 2018-02-03
- Fix VS 2015 compile

## 2018-02-02
- Add missing include (travis passed though)
- Update DataMap.h
- Fix copy paste mistakes
- Implement convenience functions for DataMap

## 2018-02-01
- Fix compile error related to last commit (#776)
- Implement data storage for Entitiies (#748)

## 2018-01-28
- Importing pending sql
- Implemented guild info command (#756)
- Importing pending sql
- Fixed Ashbringer visual on Tirion during Dk campaign (#765)
- Fixed travis compilation (#769)
- Update .travis.yml
- Travis: git workflow for pending sql in a single line
- Importing pending sql
- Update .travis.yml
- Travis: Config. for db import
- Installer: Force exit with direct command
- Using installer for travis and implemented pending sql auto-import
- Update .gitignore

## 2018-01-27
- Merge pull request #766 from Gargarensis/Unbound_Plague
- Wrong logs for creature_equip_template + startup errors fixes (#758)

## 2018-01-24
- Merge branch 'Unbound_Plague' of https://github.com/Gargarensis/azerothcore-wotlk into Unbound_Plague
- Fix Unbound Plague
- Fix Unbound Plague, credit to Nefertumm

## 2018-01-21
- import pendings

## 2018-01-15
- Implemented account_muted and feature mutehistory command (#753)

## 2018-01-14
- PlayerBytes fields in characters table

## 2018-01-08
- imported pending files

## 2018-01-02
- Move area trigger storage from DBC to database (#742)

## 2017-12-30
- Restore C++ as the main repository language. Happy new year!

## 2017-12-21
- Bash: executable permissions for .sh files
- Fixed jemalloc compilation
- Fixed warning
- Fixed warning at server start related to transports (#733)
- Merge "Huge directory Restructuring" pull request #680
- Fixed map_extractor cmake
- Moved files after merging
- Merge branch 'master' of https://github.com/azerothcore/azerothcore-wotlk into dir-restructure
- removed gamefw target lib
- Fixed linux compilation
- fixed cmake

## 2017-12-20
- Using TC structure allowing easier patches importing

## 2017-12-13
- Fixed Mirror Image

## 2017-12-12
- Removed item DBC loading and use item_template table instead (#732)

## 2017-12-11
- Fixed wrong version in sql files, please reapply manually
- Added SetCorpseTarget for SpellCastTargets
- Use getRace instead of direct uint32 value access for Corpse

## 2017-12-09
- Added Immunity Stun to spell effect bladestorm.

## 2017-12-08
- Fix travis build
- Fixed Encounter Boss Faerlina:

## 2017-12-06
- Rewritten Naxxramas boss state system using BossAI methods

## 2017-12-05
- Fixed Majordomo Executus respawn at server restart
- Fixed saving of icc buff switch
- Imported pending sql
- Import uptime table and feature from TC (#717)

## 2017-12-04
- Realmlist returns 0 instead of 1 characters after you deleted all characters (#724)
- Core/Build: Never overwrite the msvc cxx flags in the cache (#715)
- Added getter for ObjMgr::_itemTemplateStoreFast (#725)

## 2017-12-03
- Fixed crash after 635f7831e1efa4030365aac0ee7531a75ca8e604
- Improved OnItemRoll hook

## 2017-12-02
- Missing jmalloc updates
- Add LootStore information to loot hooks
- Add item entry information to auras for external usage

## 2017-11-29
- Fix travis

## 2017-11-28
- Missed define out should fix travis aswell
- Added more checks to death grip

## 2017-11-26
- Death grip should now check see if creature is immune to silence spells before interrupting
- Library Jemalloc updated to 5.0.1 (#721)

## 2017-11-25
- Revert "Fixed path error for charge spells after 17802ab6e5135f0220efcd8f4e460f8202a4c047"
- Fixed transport disappearing
- Fixed path error for charge spells after 17802ab6e5135f0220efcd8f4e460f8202a4c047

## 2017-11-16
- Fixed Unit contact point
- Fixed compilation
- Import this fix's:
- Fixing NearPoint calculation and fishing height issue #127

## 2017-11-22
- Fixed npc/object spawn by command when GetPhaseByAuras is used.

## 2017-11-21
- DB: Fixed Wintergrasp aura to avoid phase conflicts in other context
- Removed override functions in blackrock spire script
- Should fix travis build

## 2017-11-20
- Merge branch 'master' of https://github.com/azerothcore/azerothcore-wotlk
- When player skins a creature it will tell instance aswell.
- Fix chat hooks not able to edit the chat message
- Fixed halls of reflection wave timer according to deadly boss mods.
- Death Grip should now interrupt the target
- Bloodworms will now be defensive state when summoned.

## 2017-11-16
- Implemented GetPhaseByAuras removing redundant code (DRY)
- Fixed Lich King timers (step 2)
- Add summoner information to TeleportTo function and created OnBeforeTeleport hook
- Fixed Lich King timers

## 2017-11-10
- Fixed aura for GM visibility at login

## 2017-11-19
- Merge branch 'master' of https://github.com/azerothcore/azerothcore-wotlk into temp
- Fixed sql syntax error
- Merge pull request #713 from azerothcore/Rochet2-patch-2
- Imported pending sql

## 2017-11-10
- DB: Fixed difficulty type condition for achievement statistics

## 2017-11-09
- Fixed compilation
- Added OnBeforeItemRoll hook and added missing parameter to:
- Improved equip manager, anti-abuse system
- Missing arena meets condition for statistics and fixed played matches

## 2017-11-17
- Fixed statistic counters on different raid/dungeon difficulty

## 2017-11-09
- Implemented OnUpdateArea hook
- Allow near commands to list only object of your current phase

## 2017-11-03
- Fixed played arena statistics

## 2017-11-18
- Update import.sh

## 2017-11-03
- Fixed improved succubus seduction talent #699
- Improved OnCriteriaCheck hook, passing information about criteria_id
- Fixed druid "powershift" macro #693

## 2017-11-18
- Fixed criteria updating on exploration
- Fix walkableClimb, maxWalkableAngle maxAngle height.
- Mmap version update to latest

## 2017-11-17
- Importing pending sql

## 2017-11-03
- Spell/Workaround: Seduction must be interrupted by spell reflection #697
- Fixed arena statistics by type

## 2017-10-22
- Fixed Hand of Reckoning effect on shaman totems

## 2017-10-21
- Fixed behaviour of unrelenting assault warrior arms debuff

## 2017-11-16
- CMake - Made it easier to add your custom scripts (#703)

## 2017-11-15
- Core-side part for recastnav upgrade:

## 2017-11-14
- Properly update Recastnav:
- Added mmaps commands.
- Import pending SQL from commit:
- Merge branch 'master' of https://github.com/azerothcore/azerothcore-wotlk
- Update Vmaps 
- Fixes creature equipment not loading correctly. (#688)

## 2017-11-12
- Merge branch 'master' of https://github.com/azerothcore/azerothcore-wotlk

## 2017-11-10
- Molten Core - Core Hounds (#683)

## 2017-10-29
- Scripts/Northrend: fix event for quest A Suitable Test Subject (#700)
- [Fix] No newline at end of file
- Scripts/Northrend: talk event for quest A Suitable Test Subject

## 2017-10-17
- Importing pending sql
- Core: fixed realm first achievement

## 2017-10-16
- DB/Misc: N/A (#685)
- Update 2017_10_15_00.sql

## 2017-10-15
- fixed nested function in latest sql updates
- Fixed latest sql importing process

## 2017-10-14
- Wrong column name in sql
- removed pending world SQL files
- Imported Pending SQL files

## 2017-10-13
- Missing folder
- Fixed compilation after dir rework
- Bash: exec permission for bin files
- Bash: fixing scripts after directory rework

## 2017-10-12
- Directory Structure [step 1]: moving files
- Calendar/GameEvents: Store + Send holiday data to calendar (#589)
- Molten Core fixes (#604)

## 2017-10-11
- Fixed valid arena condition
- Fix achievement criteria sending correct race

## 2017-10-09
- Fixed a warning on windows
- Bash: Removed compilation type suffix on build/bin path

## 2017-10-08
- Add Diminishing_None to Feral Charge. And Add Blizzlike Animations to Flags / Chest Captures. (#664)

## 2016-07-10
- Core/Battleground: Deserter track on bg leaving

## 2017-09-30
- Fix mail system not sending all items

## 2017-09-29
- closes #667 #273

## 2017-09-27
- Update issue_template.md

## 2017-09-26
- Bash: Various improvement for compiler and db_assembler
- Continue to run server even without custom .conf
- Import pending sql

## 2017-09-25
- Bash: Minor fixes for installer
- Merge branch 'master' of https://github.com/azerothcore/azerothcore-wotlk
- Fixed and optimized EXTRA_LOGS code
- Fixed warnings when EXTRA_LOGS are off
- Revert "Cmake: Compiling with warnings by default"
- Db_Assembler: hide mysql password in prompt
- Merge branch 'master' of https://github.com/azerothcore/azerothcore-wotlk
- Various fixes for installer script and db_assembler
- Workaround to import sql with zero value in date on mysql 5.7

## 2017-09-24
- Fixed max heroic attempts ICC

## 2017-09-23
- Scarlet Monastery - Chapel: Last Boss (#599)
- Fix CMake custom script (#658)

## 2017-09-22
- Use PLAYER_BYTES_3 instead of gender to avoid displayid problems
- Installer: differentiate linux distro

## 2017-09-21
- updated doc
- Bash: fixed mysql default conf
- Installer: minor fix
- Bash: implemented installer script for server and modules (beta)
- Merge branch 'master' of https://github.com/azerothcore/azerothcore-wotlk
- Improved db assembler, now can create DBs
- Improved travis compilation
- Fixed PCH compilation and gcc warnings fixed
- Build without PCH to catch missing headers
- Fixed gcc warnings

## 2017-09-20
- Cmake: Compiling with warnings by default
- Bash: Allow action non-interactive selection
- Bash: Fixed Quit option
- Merge branch 'master' of https://github.com/azerothcore/azerothcore-wotlk

## 2017-09-19
- Implemented sql importing for db_assembler script
- Stratholme's Rat Traps (#613)
- Add GMSummonPlayer Config Option (#643)
- Fixed other badges
- Coverity badge
- Update issue_template.md
- Cleaning unused variables
- Pending sql
- Fixed linux compilation error with linker

## 2017-09-18
- Uncommented some utils functions for LFG
- Fixed some variable/parameters type issues
- Solved cmake D9025 issue with MSVC
- Removed unused variables in WaypointMovementGenerator
- Fixed all unused-parameters warnings
- Fixed compilation
- Improved travis compilation
- Merge branch 'master' of https://github.com/azerothcore/azerothcore-wotlk
- uncommented releaseModelInstance to fix a warning
- Script: Fixed yogg saron Drive Me Crazy achievement
- Removed more warnings, mostly related to unused-variable

## 2017-09-17
- Implement banned_addons (#647)
- Scripts: Step 4 - Fixed all warnings inside scripts

## 2017-09-16
- Core: Step 3 - removed all warnings from core
- Core: Step 2 - Fixed warnings with clang 3.9+
- Core: step 1 - starting to fix core warnings
- Fixed spell casting destination to require ENABLE_LOGS and ENABLE_EXTRA_LOGS to be enabled (#646)
- Naming unknown data in Authsession and implemented some checks
- Fixed realmid on realmlist packet

## 2017-09-11
- Restored behaviour about a vehicle.cpp condition

## 2017-09-10
- Fix warning under GCC Linux (#616)

## 2017-09-07
- Pet bar should now show after /reload command.

## 2017-08-26
- [CORE/Command] fixed wrong db worker for IP2NATION statement

## 2017-08-25
- importing sql
- [Script/SAI] Fixed Shattered Hand Blood Guard Event (#579)

## 2017-07-26
- Added a hook for player::Update

## 2017-08-23
- GroupHandler: prevent cheater self-invite (#573)

## 2017-08-22
- importing pending sql
- Fix LFG last player disband party (#574)

## 2017-08-21
- Merge branch 'master' of https://github.com/azerothcore/azerothcore-wotlk
- removed duplicated update file
- Fixed old auth updates
- Revert changes to base account table
- [NPC] Franclorn Forgewright visibility (#568)

## 2017-08-20
- Core/Scripts: start fight with hardcode in scripts by sending pet trainers to DB from Core (#571)
- Core/Gossip: implement another way to do gossip macros(like in TC). (#572)
- fixed linux compilation
- fixed compilation with ENABLE_* defines disabled
- Merge branch 'master' of https://github.com/azerothcore/azerothcore-wotlk
- importing pending sql
- Implement ip2nation and ip2nationCountries (#518)
- Update WorldSocket.cpp
- Missing field on LOGIN_SEL_ACCOUNT_INFO_BY_NAME
- Merge branch 'master' into master
- Merge branch 'master' into master
- Another huge compilation fix

## 2017-06-30
- fix for PR

## 2017-08-19
- Fixed travis build errors with Talamortis.

## 2017-06-30
- Fixed these 3 fatal errors for travis build (thanks to @Talamortis )

## 2017-08-19
- changed DISABLED_ cmake variable to ENABLED_ and implemented for all disabled logs
- Preprocessor option for logging functions (#567)
- import all pendings sql
- Various quest fixes
- [Database] Floating Corpse DK Starting/Scarlet Infantryman missing weapons (#539)
- Merge pull request #504 from PolarCookie/db_minor_quest_fixes_3
- Merge pull request #483 from PolarCookie/db_minor_quest_fixes
- Merge pull request #474 from STARRHELD/master
- importing peding sql
- Fixed Brewfest Building is Darkmoon Faire Building and log error
- auto-attack for warbear matriarch (#491)
- [Auth\DB] Set default expansion to 2
- import pending sql

## 2017-08-18
- DB/Quests: Terrokkar Forest quest text typos. Tnx to 'tkrokli' (#564)
- Added GetBadges in Readme.md
- Merge branch 'master' of https://github.com/azerothcore/azerothcore-wotlk
- importing pedings (please it MUST be done right after accepting PR)
- Core/Misc Created handler for character creation (#562)

## 2017-08-17
- Fix VS2017 build (#551)

## 2017-05-07
- Created hooks for first login and LFGMgr

## 2017-06-11
- added more info to run-engine conf file

## 2017-07-31
- Minor improvements for OnFirstLogin hook

## 2017-08-17
- Core/Spells now the spells for summon mount aren't affected by haste (#555)

## 2017-08-02
- Core/Command: Fix a crash when using wp show info pathid

## 2017-07-03
- When player has Animal blood applied the D.E.H.T.A camp will now be hostile if player goes near.
- Stranglethorn Vale chapter quest should no longer be repeatable.
- Fix travis & compile error
- Fix Midsummer fire quest An Innocent Disguise aswell as fixed indentation.

## 2017-07-02
- Core/Scripts: Adjust dalaran mageguards range
- these checks are not needed.

## 2017-07-01
- PetAI update
- pets should now put players in combat unless they are feigned death or shadowmeld. closes #520

## 2017-06-30
- Maybe not. Fk travis.
- More codestyle
- Codestyle
- Tabs
- closes #290
- Rin'ji will now appear to be male and also can not be attacked by alliance why in cage
- Closes #493
- fix account.sql
- Merge remote-tracking branch 'refs/remotes/azerothcore/master'
- Implement ip2nation and ip2nationCountries

## 2017-06-29
- DB/Spell: Worg Disguise can be cancelled by right-clicking
- Implemented OnPlayerReleasedGhost() hook

## 2017-06-27
- DB/Quest: The Honored Dead add missing fire animation

## 2017-06-26
- Core: Tabs sorry
- Core/Player: Correct gender by modelid and avoid saving character with wrong gender

## 2017-06-23
- DB/Quest: Event will now start when player do /lay and Doc Mixilpixil will no longer despawn

## 2017-06-14
- Import pending sql
- Core/Quest : Fix he Missing Diplomat part 14 & 15

## 2017-06-12
- Import pending sql

## 2017-06-08
- Adding character deleted command from trinitycore (#164)
- DB: fixed ugly mistake in char db update files

## 2017-06-01
- Core/Locale: fix Locales for gossip menu option (#503)

## 2017-05-31
- Bash: minor fixes to startup-scripts

## 2017-05-28
- minor fixes in outland
- minor fixes in outland
- minor fixes in outland
- importing pending sql

## 2017-05-25
- Core/Naxxramas: Maexxna.
- Bael'Gar's Fiery Essence condition
- Core/Spells: Touch of Zanzil now prevents stealth. (#481)
- Core/Map: fix NPCs falling through the textures (#482)

## 2017-05-22
- DB: fix typo in SQL update file

## 2017-05-08
- Core/Pet: Warlock pet base damage and stat fix (#480)
- minor quest fixes

## 2017-05-01
- Removed useless code from db_assembler
- Imported missing sql
- Imported pending sql
- Improved db_assembler simplifying updating process

## 2017-04-28
- DB/Creature: Doctor Razorgrin
- DB/Creature: Fix Verifonix faction and reputation
- DB/Quest: Challenge Overlord Mok'Morokk
- DB/Creature: Fix Stonescythe Whelps faction
- DB/Spells: Fixed spell range of Flush Pipe (Dalaran Sewers Knockback)
- DB/Quests: Grimtotem Spying

## 2017-04-27
- DB/Creature: Caer Darrow AREA
- DB: RP event for Dame Auriferous, High Executor Mavren, Advisor Valwy…
- DB/Quest: The Prodigal Lich Returns
- DB/Creature: Hargin Mundar
- DB/Creature: R-3D0

## 2017-04-18
- Update README.md (replace Gitter with Discord)

## 2017-04-15
- DB/Quest: Killing Two Scourge With (#464)
- DB/Quest: Shoot 'Em Up (#463)

## 2017-04-05
- Core/Text: Locales for npc_text.

## 2017-04-04
- Core/Instance: Lost fix config option Rate.InstanceResetTime

## 2017-03-31
- DB/SAI: fix quest leave no one behind close issue #447 (#449)

## 2017-03-30
- Core/Scripts: implemented enchant Blade Warding (#446)

## 2017-03-27
- Core/Instance: may fix config option Rate.InstanceResetTime (#441)

## 2017-03-26
- Ashbringer event inside Scarlet Monastery instance (#280)

## 2017-03-25
- Hook for player data loading from db

## 2017-03-26
- Missing arguments for OnAfterArenaRatingCalculation

## 2017-03-25
- Fixed mmaps_generator compilation on windows
- implemented cmake options to disable extra features for performances optimization
- Some cmake improvements for modules

## 2017-03-20
- CMAKE: implemented method to disable a module via cmake
- Allow custom include directories for cmake hooks

## 2017-03-14
- Ruby Sanctum: Fixed Siphoned might distance check

## 2017-03-11
- Implemented gperftools support

## 2017-03-07
- Moved uwd modules under drassil

## 2017-02-25
- Fixed death knight Army of the dead pet damage

## 2017-02-24
- Avoid high level auras on pet when summon

## 2017-02-23
- fixed totem rank scaling with low level players
- Implemented custom expiration parameter for SendMailTo

## 2017-02-22
- Fixed area aura scaling on lower level players
- Fixed heirloom armor mod for cloak

## 2017-02-19
- Moved onStartup hook under Master.cpp to avoid issues with freezing check
- Fixed possible crash with unordered maps

## 2017-01-31
- moved hook from battleground script to formula script

## 2017-01-29
- Fixed hooks OnPlayerJoinArena and OnPlayerJoinBG

## 2017-01-28
- hook OnAfterArenaRatingCalculation

## 2017-01-26
- Created new hook for AttackPower

## 2017-01-23
- OnBeforeUpdateAttackPowerAndDamage -> OnAfterUpdateAttackPowerAndDamage
- New hook OnBeforeUpdateAttackPowerAndDamage
- New hook OnAfterUpdateMaxHealth

## 2017-01-22
- Fix to OnBeforeRollMeleeOutcomeAgainst hook

## 2017-01-21
- Fix for OnAfterUpdateMaxPower hook
- New hooks OnAfterUpdateMaxPower and OnBeforeRollMeleeOutcomeAgainst

## 2017-01-06
- fix hook

## 2017-01-04
- hook before a player buys something

## 2016-12-29
- fixed parentheses

## 2016-12-28
- New hooks OnAfterRefCount and OnBeforeDropAddItem

## 2017-03-24
- Core/BG: WG Tenacity Buff fix

## 2017-03-21
- [VANILLA][OBJECT] Gold Vein, Ooze Covered Gold Vein, Tin Vein, Mithril Deposit (#436)

## 2017-03-20
- Fix the encoding problems from https://github.com/azerothcore/azerothcore-wotlk/commit/e4a3f61e7234089a8440e327e2fb397ee9fde8d2
- Merge pull request #434 from Viste/pvptoken
- Fix config option PVP_TOKEN_ENABLE close issue #183

## 2017-03-19
- Core/Auth: Per SRP6a protocol, terminate connection of A % N == 0. This resolves another authentication bypass issue

## 2017-03-17
- Core/Misc: Fix building mmaps_geenrator on linux.

## 2017-03-16
- DB/Item: Missing loot from Leandro's pet box and Gift box.

## 2017-03-15
- Core/Quest: Fixed display of quests.
- Core/Command: Added disable commands. (#423)

## 2017-03-14
- Merge pull request #425 from Rochet2/patch-1
- Remove stored procedure from sql
- Add fixed SQL
- Delete bad SQL

## 2017-03-10
- May fix issue #306 need tests (#421)

## 2017-03-04
- Import pending SQL files
- Added SQL file using the proper format

## 2017-03-03
- Merge pull request #406 from starrheld/master
- Locales for quests (#407)
- [NPC] Lagoon Eel
- Update spell_generic.cpp

## 2017-03-01
- Merge pull request #404 from kvipka/blink
- Revert " Load scripts AFTER server configuration has been initialized."

## 2017-02-28
- Update spell_generic.cpp
- implement Moss Covered Feet
- Implement blink v4.5 for AzerothCore http://forum.deadmines.org/threads/blink.7/ blink in abyss blink by path ( rechecking each step ) where player can walk - blink will available there implemented check on dynamic objects (locked doors and etc) implemented total path of blink.

## 2017-02-22
- Merge pull request #393 from starrheld/master

## 2017-02-21
- [NPC][EVENT] Kruban Darkblade <Darkmoon Faire Barker>

## 2017-02-20
- Merge pull request #389 from starrheld/master

## 2017-02-19
- [NPC][VANILLA] Rotting Agam'ar
- Merge pull request #388 from ShinDarth/test_git_author2
- Fix git commit author
- Fix git commit author (#387)
- Merge pull request #386 from starrheld/master
- [QUEST][VANILLA] Elven Legends
- Fix for Wandering Shay Author Killyana
- upadte
- Merge pull request #385 from starrheld/master
- Space removed
- [QUEST][VANILLA] Scalding Mornbrew Delivery
- [QUEST][WOTLK] The Ancient Armor of the Kvaldir
- Merge pull request #384 from starrheld/master
- Update rev_1487514602617381300.sql
- rev_1487514602617381300.sql
- [NPC][TBC] Spirit of Ar'tor
- Merge pull request #383 from starrheld/master
- [QUEST][WOTLK] Basic Chemistry

## 2017-02-15
- Why was we getting the player within 40f?, 12f is probly still a little to much but it works.

## 2017-02-12
-  Load scripts AFTER server configuration has been initialized.

## 2017-02-11
- Travis fix
- Merge branch 'master' of https://github.com/azerothcore/azerothcore-wotlk
- Noth will now cast curse when he teleports back to the ground

## 2017-02-10
- Merge pull request #369 from starrheld/master
- Fix refer a friend Summon

## 2017-02-08
- Merge branch 'master' of https://github.com/azerothcore/azerothcore-wotlk
- Fix Paladin's Greater Spell

## 2017-02-07
- Merge pull request #371 from Inifield/mmapsversion
- Core/Extractors : Fix MMAP version, you should be able to extract them and use them again

## 2017-02-05
- Author commit
- Changed the spawn location of Anubrekhan adds to be more blizzlike

## 2017-02-04
- Merge branch 'master' of https://github.com/azerothcore/azerothcore-wotlk
- closes  #352
- Merge pull request #368 from starrheld/master
- CIVILIAN RECRUIT CHANGED MODIELID FROM 3422 TO 24821/24818
- BRITTLE REVENANT LOOT TABLE AND DROP RATE FIXED
- Fix Quest for Convocation at Zol'Heb (12730) and quest 17013

## 2017-02-03
- travis fix and database fix
- Indention fix for trial_of_the_champion.cpp
- pushed all pending sqls.
- Few start up error fixes.
- error was caused because of LOS, removed LOS for the spell.
- Removed script for Gurubashi event now controlled by database.
- Added Emote so when boss speaks she will do emote on that text.

## 2017-02-02
- Indention Fix for trial_of_the_champion
- Anub'Rekhan will now summon two creatures in Naxxramas 25m, it will no longer spawn a Crypt guard in 10 man.
- Merge pull request #347 from starrheld/master
- Fix creature error when loading creatures on start.
- Fixed the channel chat to display properly instead of righting to lower case
- made the creatures in the sewers attach each other and use spells

## 2017-02-01
- Put a space to tidy code up for previous fix.
- Merge branch 'master' of https://github.com/azerothcore/azerothcore-wotlk
- Fixed brann_bronzebeard in halls_of_stone to stop moving near the end door, also does emote at end Waypoint to make it more blizzlike

## 2017-01-30
- fixed pending sql for new db structure

## 2017-01-25
- Minor Updates patch SQL (Rushor) squash.

## 2017-01-29
- DB/Fix: gurubashi arena

## 2017-01-28
- Noth the Plaguebringer update, he will now stay on the balcony instead of floating back down to the center

## 2017-01-25
- Merge branch 'master' of https://github.com/azerothcore/azerothcore-wotlk
- Fix the speed problem of the summoned creatures when encounter starts.

## 2017-01-24
- Update issue_template.md (#341)
- Fix Travis
- Pending SQL, pushed.

## 2017-01-22
- Quest Fixes
- Update mushrooms

## 2017-01-21
- Fix quest Death Comes From On High

## 2017-01-12
- Prince fix
- Prince Phase 3 fix
- dupelicate file.
- added file type at the end

## 2017-01-10
- Merge pull request #287 from talamortis/talamortis-patch-2
- Merge pull request #318 from Inifield/ext1
- Merge pull request #196 from azerothcore/talamortis-patch-1
- Merge pull request #316 from azerothcore/karazhan_rework

## 2017-01-09
- fixed typo.
- Fix error in travis log.
- Code cleanup and also make Shade select a random target
- Core/Maps: Extractors will now extract datas as it should
- added NPC Relay to script, stop prince Error.
- indention fix
- indention fix

## 2017-01-08
- Prince Rescript and a few boss code Cleanups

## 2017-01-06
- Core/Tools: Fix compilation of tools under windows (#312)
- Revert "Prince rework and Nightbane code clean up"

## 2017-01-05
- Merge branch 'master' of https://github.com/azerothcore/azerothcore-wotlk
- Prince rework and Nightbane code clean up

## 2017-01-04
- DB/World schema: split quest_template and quest_template_addon and renamed some fields (#291)

## 2017-01-01
- Script/Spell: Shadowmourne - Soul Fragment Proc (Enable on BG And Arena) (#307)
- Core/Arena: Add config option for Arena.QueueAnnoncer (#305)

## 2016-12-29
- Merge branch 'master' of https://github.com/azerothcore/azerothcore-wotlk
- uncommented network log
- updated doc submodule
- Merge branch 'master' of https://github.com/azerothcore/azerothcore-wotlk
- Merge pull request #300 from Helias/schema-quest

## 2016-12-28
-  DB/World schema: updated quest_template table
- DB/World schema: updated quest_template table
- Merge from polaretto/azerothcore-wotlk

## 2016-12-27
- Update .travis.yml to fix latest integration errors.
- Updated .travis.yml to support missing dependencies.
- Update .travis.yml to show more error details.
- Update .travis.yml

## 2016-12-26
- Made the instance Karazhan open for normal players to enter
- Karazhan changes to make it now playable for players. all event work apart form chess event
- Merge branch 'master' of https://github.com/azerothcore/azerothcore-wotlk

## 2016-12-20
- indention fix

## 2016-12-19
- Fix Argent Defender
- Revert "[QUEST] [A] 12499 and [H] 12500 - Return To Angrathar (lack of phasing after completing quest)" (#286)

## 2016-12-18
- DB/World/SpellArea: fix Return To Angrathar (lack of phasing after completing quest) (#283)

## 2016-12-17
- fixed latest sql update
- Fix for char db and auth db updates
- DB: alter table mistake in sql update

## 2016-12-16
- Scripts/Karazhan: Undeclared spell, fix for #96 #101 (#279)

## 2016-12-07
- More hooks for Scripts/Modules (#270)

## 2016-12-02
- Core/ChatHandler: Fix for config mute. (#272)
- Core/Text: Add support for BroadcastTextID in creature_text table. (#265)

## 2016-11-30
- Core/SmartScripts: Fix Deadmines door lever not opening door. (#269)

## 2016-11-26
- Merge remote-tracking branch 'upstream/master'
- Import pending SQLs
- Core/ScriptMgr: added new hook OnBeforeUpdateArenaPoints (#261)

## 2016-11-25
- DB/World: move questItem* fields to *_questitems tables (#249)

## 2016-11-24
- Core/PetHandler: Fix pet level issue on UNIX systems

## 2016-11-22
- Core/Misc: identation fixes
- New hooks OnEquip, OnPlayerJoinBG, OnPlayerJoinArena

## 2016-11-21
- DB/Auth: fix column name in update file, thanks @DarkmoonRabbit

## 2016-11-20
- DB/Updates: fix syntax error in SQL update file
- Core/Chat: Add config to mute player first login. (#234)

## 2016-11-19
- Merge branch '1.x'
- Imported pending SQLs
- Update AuthSocket.h
- Update AuthSocket.h
- Merge branch '1.x'
- Implemented hook for Player::MoveItemFromInventory

## 2016-11-18
- Kurzan Commando
- Fix Kurzan Commando Stealth
- Update spell_paladin.cpp
- Core/Script Paladin Argent Defender
- Core/Auth: Resolved critical vulnerability on auth system bypass
- Core/Auth: Resolved critical vulnerability on auth system bypass
- fixed alter tables
- Created needed files for "sql pending system"
- Archived old sql files, they are now integrated in base
- Removed procedure to avoid "mysql gone away" issue for timeout
- improved gitignore for modules
- fixed install.sh url for joiner

## 2016-11-17
- Merge pull request #194 from talamortis/patch-1
- custom files must be always resetted on full db_assembling
- Updated ScriptMgr with new function to favorite transmog module

## 2016-11-15
- DB/Misc: minor structure improvements

## 2016-11-12
- Core/LootMgr: prevent loot issues in case of crossfaction groups

## 2016-11-08
- Scripts/Pet: Gargoyle shouldn't attack ghoul target. (#229)

## 2016-11-06
- Import pending SQLs
- Scripts/Commands: Adding command reload broadcast text. (#228)
- Bin/SQL-Generator: fixed macOS import + minor improvements
- Core/Text: Implemented BroadcastText. (#227)

## 2016-11-05
- Import pending SQL
- Core/Object: Localization objects. (#226)
- Fix SQL syntax + import pending SQLs
- DB/CreatureQuestStarter: fix Image of Drakuru quest (#201)
- Core/Text: Implemented locales_points_of_interest. (#225)
- Import pending SQL
- Core/Creature: Localization creatures. (#224)
- Import pending SQLs
- Core/Chat: Fix crash when using a command (#220)

## 2016-11-04
- Core/Item: Localization items. (#223)

## 2016-11-03
- Core/Text: Implemented locales_page_text. (#221)

## 2016-10-29
- Removed empty SQL file
- Merge remote-tracking branch 'upstream/master'
- DB/Updates: fix 2016_10_23_00.sql
- CMake: Added support for MySQL Server 5.7 (#187)
- Import pending SQLs
- Script/Commands: implemented .reload battleground_template (#210)

## 2016-10-25
- Bin/DB-Assembler: fixed bug in Mac OS X md5 generation - IMPORTANT NOTE: new dependency for Mac users: brew install md5sha1sum
- boss_mandokir.cpp

## 2016-10-23
- Bloodlord Mandokir Say Fix
- Made to Update statement
- Fix Quest Evil Draws Near
- Bin: fix db_pendings import.sh script
- imported pending sql
- DB/Loot: Fix drop chance of item Dinosaur Bone (11114)

## 2016-10-14
- imported pending sql

## 2016-10-10
- DB/SAI: fix Plague Walker (Ahn'Kahet: Old Kingdom)
- Quest/Loot The Great Fras Siabi (#167)

## 2016-10-08
- I close issue 119 (#170)

## 2016-09-27
- Updated Chat.cpp (#162)

## 2016-09-24
- Core/DB: sql update importing fix
- Core/DB: Missing 431704c7e2cf6fd351fcc9e25facae97fe7f6d67 sql
- Core/DB: Created sql updates from pending
- Core/DB: Using correct syntax for pending sql
- Merge branch 'master' of https://github.com/azerothcore/azerothcore-wotlk
- Merge pull request #112 from DantestyleXD/patch-2
- Merge pull request #141 from Krath/master
- Merge pull request #132 from Helias/warnings
- Merge pull request #158 from talamortis/patch-5
- Merge pull request #145 from talamortis/master
- Merge branch 'master' of https://github.com/azerothcore/azerothcore-wotlk
- Minor fixes to startup-scripts, disabled screen check since it can cause some issues

## 2016-09-23
- bin folder creation for startup-scripts on after_build event

## 2016-09-22
- Core/Logging Fixed db logging clean timer

## 2016-09-17
- Fixed joiner repo url

## 2016-09-16
- Fix crash with algalon
- Core/Script: Missing check on medivh script, fixed crash

## 2016-09-15
- Core/Script: Fixed possible crash when medivh is spawned outside instance

## 2016-09-11
- Core/Unit: added new script OnPlayerBeingCharmed

## 2016-09-15
- Core/Config Not initial conf files are optional now

## 2016-09-14
- Core/Logging: Re-Implemented onChat scripting system

## 2016-09-24
- Black knight orders

## 2016-09-22
- Database/World: made the database structure similar to TrinityCore (#154)

## 2016-09-12
- Changed comment
- Changed comment
- Removed

## 2016-09-11
- Ambassador Kelemar Waypoint

## 2016-09-06
- World/ Winterfin Oracle ID 25216
- Instance: Culling of stratholme - Arthus Fix
- Silvermoon City: Ambassitor Kelmer Walk fix
- Instance: Pit of Saron Tyrannus Mount Fix

## 2016-09-05
- Core/Scripts Halls of Reflection
- Core/Scripts: Halls of Reflection
- Core/Scripts Pit of Saron
- Checking if the player is mounted.
- Merge branch 'master' of github.com:azerothcore/azerothcore-wotlk
- Revert "Get Team Id by group Leader instead of random player"

## 2016-08-14
- Fix for missing assignment of m_race

## 2016-09-05
- [DB] fix on characters base tables
- [DB] Fixed Some strange missing data/fix on base db

## 2016-09-04
- Fixed commands log and a crash on windows
- Created auth logs table for db logging system
- Fixed compilation for vs 2013
- Merge branch 'master' of https://github.com/azerothcore/azerothcore-wotlk.git
- Force to use external mysql lib instead of sources
- Build/Clang: suppress logical-op-parentheses warnings
- Revert "Build/Clang: fixed 96 warnings + improved code readability"
- [DB/Quest] There Exists No Honor Among Birds rev.5

## 2016-09-03
- Core/Build: fixed a warning
- Core/Build: fixed 4 warnings

## 2016-09-02
- Typing error in folder name

## 2016-09-01
- Using IsGMAccount instead of direct check
- cleaning config.sh.dist file
- Improved run engine and moved on separated module

## 2016-08-31
- Re-implemented Clean logs table
- moved GetDatabaseName under public to be used on API

## 2016-08-30
- Restored db logging function
- Removed absolute path from some script loaders

## 2016-08-24
- Core/Unit: correctly retrieve faction id for race when original is requested

## 2016-08-30
- Update README.md
- [DB] Importing pending sql
- [BASH/DB] Fixed importing script with revisioned sql
- Merge branch 'master' of https://github.com/azerothcore/azerothcore-wotlk.git
- Merge pull request #118 from DantestyleXD/patch-3
- Update .travis.yml
- Misc: fix copyright from wrong search&replace
- Merge remote-tracking branch 'upstream/master'
- Misc: fix copyright from wrong search&replace
- [BASH] separated -wipe from -ls for run engine
- Fixed small typo for Travis
- Update to support Travis (now based on azerothcore changes wrt TC)
- Added ACE library to Travis
- Travis build fix
- Update .travis.yml
- Updated Travis config to latest TC dependencies.
- Updated Readme with Travis CI badge.
- [BASH] Removed _timed_ files for custom sql
- fixed wrong sql header
- Fixed db_assembler DB path variable expanding

## 2016-08-29
- [BASH] fix run-engine issue with destroyed screen sessions
- [Bash] Fixed previous scripts permissions and minor mistake
- [DB/Quest] Not work quest id 10990 10991 10992 #114 rev.3
- [DB/Quest] There Exists No Honor Among Birds rev. 4
- fixed import.sh and implemented new optional workflow for pendings sql
- Improved db_assembler with multiple options
- Update Pit of Saron (#78)
- Core/World: improved GetGlobalPlayer* methods

## 2016-08-28
- Core/ObjectMgr: improved GetPlayerGUIDByName method + misc
- Script/Commands: correction of https://github.com/azerothcore/azerothcore-wotlk/commit/1b1767e9f4c20d1e20541968de98d00814f63247#diff-de077c84577b8885f0df1d20707bbb38L243

## 2016-08-27
- typo
- typo
- [DB/Quest] Not work quest id 10990 10991 10992 #114 rev.2
- [DB/Quest] Not work quest id 10990 10991 10992 #114
- [DB/Quest] There Exists No Honor Among Birds rev. 3

## 2016-08-26
- Script/Commands: enhanced .lookup player command
- Scripts/PetMage: fixed a crash with DK's Gargoyle and Mirror Image
- Misc: fix copyright header
- Merge remote-tracking branch 'upstream/master'
- Misc: cleaning
- Merge branch 'master' of github.com:azerothcore/azerothcore-wotlk
- removed templates for pending, we will find a more cleaner way for devs
- db_pending/import now use transaction to avoid db data inconsistency
- Crossplatform header for bash files
- Core/Pet: Fix initial energy of DK's Ghoul (#115)
- Build: fixed some warnings - Closes #108
- db_assembler: removed lowercase substitution not compatible with osx
- Fixed sql header

## 2016-08-25
- implemented pending workflow for sql and PR
- minor fix for db_assembler
- fixed and updated db_assembler to even support old bash v3 ( osx )
- Better names for sql folders + added custom and pending

## 2016-08-24
- Core/Commands: enable .gm ingame command + misc cleaning
- fixed sql

## 2016-08-13
- [SQL/Creature] fix movement type Fizzle Darkstorm and Burning Blade Fanatic
- Core/Spells: fix greater blessings selection issues (pet class on player class)
- Core/Spells: fix removal of Disarm (scorpid sting) cooldown with Readiness

## 2016-08-10
- Core/Instance: Shared normal/heroic ID is now a configurable feature (default: deactivated)

## 2016-08-14
- Core/Scripts: add new hook OnPlayerAddToBattleground
- Core/Unit: enable setting and retrieval of a temporary race for players

## 2016-08-24
- Merge branch 'master' of github.com:azerothcore/azerothcore-wotlk
- removed -Wpointer-bool-conversion parameter from clang
- Update README.md
- Merge branch 'master' of github.com:azerothcore/azerothcore-wotlk
- Will of Forsaken + Trinket PVP correct faction check

## 2016-08-13
- Core/Player: Implement original race variable at unit level and initialize it (for future customizations)

## 2016-08-24
- Update README.md
- Update README.md
- fix for sql headers
- renamed wrong sql
- Avoid reset loop on boss nalorakk

## 2016-08-15
- Core/Pet: correct pet loading - summoning

## 2016-08-24
- Core/Chat: properly prevent crashes + cleaning (import from TrinityCore) - Closes #111

## 2016-08-23
- [DB/Quest] There Exists No Honor Among Birds rev.2
- [DB/Quest] There Exists No Honor Among Birds rev.1
- [DB/Quest] There Exists No Honor Among Birds
- improved run engine
- Fix sql header
- Merge branch 'master' of github.com:azerothcore/azerothcore-wotlk
- Compilation fix
- Project restructuring [PART.3]
- Project restructuring [PART.2]
- Merge remote-tracking branch 'upstream/master'
- Core/Chat: fixed crash in commands closes #110

## 2016-08-22
- Core/DB - Keeping the Enemy at Bay
- Project restructuring conforming to the new software layers [PART.1]
- Update issue_template.md
- Update issue_template.md
- Core/Chat: fixed some commands This fixes all those commands that can take in input both a param and a subcommand, e.g.: .learn, .tele, etc...

## 2016-08-21
- Script/Commands: fix all command permissions
- Core/Chat: fixed commands

## 2016-08-20
- Fix commands and starting to use nullptr instead of NULL

## 2016-08-21
- Revert "fixed crash on command execution"

## 2016-08-20
- Merge branch 'master' of github.com:azerothcore/azerothcore-wotlk
- Missing folders
- Core/Console: rename console
- change default bash compiler to clang
- Fix commands and starting to use nullptr instead of NULL
- Build/Clang: restore build on Mac OS X
- Fixed some warnings
- fixed crash on command execution
- fixed compilation of latest commands rewrite work
- removing ACE int types, replaced with c++11

## 2016-08-19
- Merge branch 'threading_rewrite' of https://github.com/ShinDarth/azerothcore-wotlk into threading_rewrite
- Merge branch 'master' into threading_rewrite
- Merge branch 'master' of github.com:azerothcore/azerothcore-wotlk
- Fixed compilation without PCH enabled
- Fixed compilation without PCH enabled
- Corrected more copyrights
- Update chat system, based on TrinityCore commit
- Merge remote-tracking branch 'upstream/master' into threading_rewrite
- CMake/Clang: fix build type variable
- Merge branch 'master' into threading_rewrite

## 2016-08-16
- Rewritten Threading system using c++11 std instead of ACE

## 2016-08-19
- Merge branch 'master' of github.com:azerothcore/azerothcore-wotlk
- removed CC compiler from conf
- fixed uwd/joiner installation
- upgraded gsoap to 2.8.33
- Some minor changes

## 2016-08-17
- Update README.md
- Fix License issue, closes #21
- Added LICENSE file
- Merge branch 'master' of github.com:azerothcore/azerothcore-wotlk
- Enabled c99 support for C files
- Build/Clang: fixed 2 warnings
- Build/Clang: suppress useless warnings
- Some corrections to previous commits
- Crosscompiling solution for isfinite & isnan

## 2016-08-16
- Fix compilation of cs_debug script with clang

## 2016-08-15
- [CMAKE] More compatible definitions
- [BASH] Now scripts will use default language
- fixed bash hook functions

## 2016-08-17
- CMake/Clang: suppress several warnings
- CMake: fix Clang detection
- Scripts/Northrend: corrected code logic, fixing a bunch of warnings

## 2016-08-16
- Build/Clang: removed deprecated finite() fixing 59 warnings
- Build/Clang: fixed 96 warnings + improved code readability
- Core/Arena: fix arena points rate config + code indentation
- Core/Arena: Create more arena configs (#97)

## 2016-08-15
- Core/Misc: Adding localization DBC. (#95)
- Core/Channels: allow to disable ownership of channels
- Fix build
- Core/Spells: Fix Corpse Explosion picking ghoul as a target without selection. (#83)
- Fix Cmake revision. (#91)

## 2016-08-14
- Misc: fix SQL updates + move some lines of code
- Core/Commands: Add missing message for .ticket complete (#79)
- Fix warning on Windows. (#89)
- Core/Spells: Fix Hellscream's Warsong & Strength of Wrynn buffs. (#87)
- Core/Custom: Fix Dream Vision & Eye of Kilrogg aggro and visibility. (#85)
- Merge pull request #81 from DevRival/patch-1
- Merge remote-tracking branch 'upstream/master'
- Bin/DB-Assembler: fix bash
- Merge branch 'master' of github.com:azerothcore/azerothcore-wotlk
- wrong db exported
- Update README.md
- DB/Characters: fix code indentation
- Merge remote-tracking branch 'upstream/master'
- DB/Characters: fix base dumps
- Merge pull request #80 from Luth31/dev-2
- Core/Player: Fixed Weapon Skillup on low level mobs
- Bin/Defines fix error in Mac OS X
- base db is now splitted in multiple sql
- Move sql updates under archive

## 2016-08-13
- Core/Misc: Fix instant logout config
- Merge branch 'master' of github.com:azerothcore/azerothcore-wotlk
- implemented db_exporter
- created hw-core bash libraries
- minor updates to mysql-tools
- Merge commit 'ce7b05ccae4549ca6e1ae2de1d3e36a8b3b82690' as 'modules/uwd/mysql-tools'
- Squashed 'modules/uwd/mysql-tools/' content from commit d76f949
- removed useless redefinition from db_assembler
- Core/Worldstates: move WS_ARENA_DISTRIBUTION_TIME declaration
- Merge remote-tracking branch 'upstream/master'
- Core/Player: added API for duel reset of health/mana
- Update issue_template.md

## 2016-08-12
- Core/CMake: show branch name in server info
- DB/World: fix world_db_version
- Merge pull request #27 from ShinDarth/db-characters

## 2016-07-24
- DB/Characters: update DB structure

## 2016-08-12
- removed wrong submodule

## 2016-08-08
- fix heroism/bloodlust stack based on ShinDarth previous fix on TrinityCore

## 2016-08-12
- Merge branch 'master' of github.com:azerothcore/azerothcore-wotlk
- Added template files for github
- Another big repo refactoring, should be latest
- Continuing cmake path fixing
- Fixed paths for cmake
- Refactoring part 2 [W.I.P]
- Merge pull request #55 from Luth31/master

## 2016-08-11
- Script/Commands: .account create will now grant the latest enabled expansion (Set in worldserver.conf
- Corrected path for ScriptWotlkLoader
- Merge branch 'master' of github.com:azerothcore/azerothcore-wotlk
- fixed an inclusion
- Update README.md
- Merge branch 'master' of github.com:azerothcore/azerothcore-wotlk
- removed unused conf
- Some cleaning
- Rewritten cmakes allowing compilation with new structure
- Big re-organization of repository [W.I.P]
- removed server-stats folder
- Using more appropriate NS prefixes for our macro and cmake vars
- always set cmake $CONF_DIR and add in preprocessor defines
- Update README.md
- [CMake] impl. ADD_SCRIPTS macro for modules
- Removed various sql
- Removed extras folders
- Merge remote-tracking branch 'upstream/master'
- Add missing world_db_version table update
- Merge pull request #52 from Luth31/master
- Fix CMake on Windows

## 2016-08-10
- Script/Commands: imported .instance get/setbossstate commands from TrinityCore
- Core/Strings: imported 157 LANG_* strings from TrinityCore
- Core/CMake: update revision display format
- Merge branch 'master' of git@github.com:azerothcore/azerothcore-wotlk.git
- [CORE] Allowing compilation with c++11

## 2016-08-09
- Merge remote-tracking branch 'upstream/master'
- Script/Commands: show revision in .server info - Closes #49
- Merge pull request #51 from Helias/patch-1
- Core/build: fixed build on Linux
- CMake: fixed git informations
- Script/Commands: enhance .ticket complete command

## 2016-08-08
- Merge pull request #48 from ShinDarth/db-dump
- DB/dumps: update base files
- Merge branch 'master' of git@github.com:azerothcore/azerothcore-wotlk.git into gh-master
- Import pvpstats sql and fix previous updates with ALTER TABLE
- Merge pull request #43 from ShinDarth/git
- Fixed compilation
- Impl usefull functions
- Fix for hardcoded commands security level
- Get Team Id by group Leader instead of random player
- Fix for DK pet , Thanks to Mik & Harlock
- Removed useless configurations
- Minor changes for HandleBattleFieldPortOpcode
- Gossip script for items
- Ensuring original team for this check
- Improved ScriptMgr with more hooks
- Moved GetSkill in ItemPrototype
- Missing query for PVPSTATS
- Missing code for XP Battlegrounds
- [CORE] Imported PVP stats , special thanks to Mik & Shin
- [CORE] Arena points rate , thanks to Mik1983 for import

## 2016-08-07
- Merge branch 'master' into git

## 2016-08-06
- i forgot something

## 2016-08-07
- Merging
- [BASH] improved db assembler with more effective md5 check

## 2016-08-06
- [CORE] force reloading of logs configurations at start

## 2016-08-04
- Core/Spells: Fix Spirit Heal (battleground), abilities with rage/energy should also have no cost

## 2016-08-07
- Fix Gargoyle dk being feared/confused properly

## 2016-08-03
- Some faction fixes
- Toc5 - Fix also heroic factions
- Core/Unit: fix the 1/10000 chance to miss with 100% chance
- Fix instance binding
- Fix Zul Aman
- DB/Spell: Fix spell area issue with spell WGA Phase
- [CORE] guild safety check only when two side guild interaction is disabled

## 2016-08-02
- Core/Spells: Fix Chain Heal

## 2016-08-01
- Core/ToC5: Fix faction issues on champion bosses
- Core/Spells: Judgements do not require facing

## 2016-07-31
- [DB] fix for wrong update file
- Core/Pet: Casting pet spells on enemies at a distance - now the pet goes at casting distance and does the cast

## 2016-08-07
- Core/Spells: DK Dancing Rune weapon diseases now count towards Heart Strike bonus damage
- [CORE] Rewritten ScriptMgr to be initialized before server load

## 2016-07-31
- [BASH] allow additional custom config for cmake

## 2016-07-30
- Fix issue in db query
- Fix Compile

## 2016-08-07
- Core/Tickets: Ticket System updated

## 2016-07-30
- [CORE] implemented multiple configuration files loading
- Fixed .gitignore to support modules inclusion
- loading modules for bash system
- [DB] implemented automatic version retrieving
- fixed db_assembler script
- [DB] Renamed databases -> base
- [DB] moved full databases in folder

## 2016-07-29
- ignoring conf for db_assembler
- fix buildpath in compilation script

## 2016-08-07
- [Core/Cmake] Scripts are now added dynamically

## 2016-07-28
- Core/Wintergrasp: Fix Wintergrasp tenacity
- Core/Battleground: Fix reputation assignment in case of switched team

## 2016-08-07
- Core/Player: Check original faction in case of quest-reputations-items

## 2016-07-28
- fixed cmake and compilation
- some fixes to bash config files
- Core/Pet: Gargoyle now attacks Ghoul target, thx Harlock
- starting bash rewriting job [WIP]
- skip inclusion of modules without CMakeLists
- updated docs with latest revision
- created install script
- fix loot for mindless servant

## 2016-07-27
- Allow rewarding kills from same ip address
- [CMAKE] Hooks for after binaries cmakes

## 2016-08-07
- [CORE] Impl. GetTeamId parameter to get original team

## 2016-07-25
- configuration system for cmake

## 2016-08-07
- Fix import BG rate exp

## 2016-07-19
- [Core] Fix compile when include InstanceSaveMgr

## 2016-08-06
- Fix clang build
- Replace some labels
- Fix DB-assembler on Mac OS X

## 2016-07-25
- Merge pull request #32 from ShinDarth/welcome-text
- Merge pull request #30 from ShinDarth/misc

## 2016-07-24
- Core/Misc improved welcome message
- Added VS Code system file to the .gitignore
- Credits to SunwellCore, TrinityCore and MaNGOS authors
- Added AzerothCore labels

## 2016-07-20
- Merge pull request #19 from Bodeguero/System_Travis_CI
- Merge pull request #20 from ShinDarth/patch-1
- Added basic README information
- Core/Fixes: Added System Travis CI.

## 2016-07-14
- [Core/Script] As the crow flies - delete horrible  hack and properly fix
- fixed alter table for update sql
- Merge pull request #8 from lellonicole/quest_addingInjuryToInsult
- Merge pull request #10 from lellonicole/Kelthuzad_mainGate
- Merge pull request #11 from lellonicole/CastSpellOnPlayer_pvpZone

## 2016-07-12
- Merge pull request #7 from lellonicole/gunship_mage
- Correct tab4space to naxxramas.h
- [Core/Mechanics] Player, add support to gameobject to cast spell on player in Pv… …p zone. Also fix quest 9422/9419
- [Core/Script] Kelthuzad, add door open/close on combat state change
- [DB/Quest] Fix speed_run creature
- [Core/Script] Gunship battle, fix evade battle mage

## 2016-07-11
- [Core/Script] As the crow flies, fix quest complete and remove morph at movement complete
- Merge pull request #5 from lellonicole/master
- [DB/Creature] Midsummer fire festival, fix some bugs to gobject/creature

## 2016-07-10
- Rename README to README.md
- Create README
- moved @lellonicole sql update under correct folder
- Merge pull request #4 from lellonicole/master
- [DB/Quest] Torch Catching, fix quest spell id
- [Core/Script] Gundrak, fix spawn Eck only in heroic mode
- removed useless files from various data
- updated characters db with pvpstats tables
- updated auth with autobroadcast table
- minor change on config.sh.dist

## 2016-07-09
- Force CMAKE to check for MYSQL libraries - do not use mysql sources
- Fix compile VS2015

## 2016-07-10
- reorganized sql

## 2016-07-09
- implemented first version of db_assembler script
- added 2 cmake hooks for game library

## 2016-07-10
- compilation fixed
- [Core/Boss] Oculus/Orum, fix spawn mob position

## 2016-07-09
- ignoring bash compiler configuration
- fixed path inclusion
- removed deprecated defines
- improved cmake hook system
- Implemented dynamic module loading and hooks system for cmake
- ignoring IDE & other softwares specific files
- added github wiki repo ( submodule ) as doc folder

## 2016-07-08
- restructured repository based on following standards: https://github.com/HW-Core/directory-structure

## 2016-07-06
- readme for compiler scripts
- commented security hacks

## 2016-06-29
- Fix Compile Unix
- Fix Unix/Windows Compile (timezone issue)
- Fix VS2015 Compile - Part 2
- Fix VS2015 Compile

## 2016-06-27
- flags for compiler

## 2016-07-02
- Merge pull request #2 from AzerothShard-Dev/prose-patch-1
- Updated README.md

## 2016-06-30
- Update README.md

## 2016-06-29
- Update README.md

## 2016-06-28
- Create README.md

## 2016-06-27
- uploading compiler scripts
- Removing multi-vendor Rochet2 patch

## 2016-06-26
- converted all tabs to 4 spaces
- importing changes from callmephil repo
- Merge branch 'master' of https://github.com/azerothcore/azerothcore.git
- fix compilation
- Fix MMAPS Generation
- Add GitIgnore
- First Commit

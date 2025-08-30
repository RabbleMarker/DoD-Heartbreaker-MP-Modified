Fork of GODOGs DOD mod with campaign specific edits, including but not limited to:

Removing Bohemias starting sphere on PLC
Giving military professionalism to Russia
Conversion of Qingqiu accepteds in Java, Borneo & Sumatra (Qingqiu nerf)
Giving Vietnam some reforms (RP from conquest)




**Original Description:**


Based off of ShortHills IGoRDoD: https://github.com/TheShortHills/IGoRDoD which has the destinction of being the first person who realized that trying to remove the rot of HPM from DoD is a futile task. Instead he just build off of IGOR-PUIR

This mod attempts to capture the feel of a more proper DoD though: added back many countries and paths missing from IGoRDoD and adjusted borders to be closer to your run of the mill DoD.

Additionally several other changes have been made in the spirit of Retvrn to Tradition:

* Added back the spread out Anglois Pops in Normandy and Southern England, as God intended before Zombiefreak cruelly genocided them.
* Ported over pop files where they made sense to restore pop diversity across the world where there should be.
* Nerfed Germany to 38 LR however Bohemia and Silesia are 38 LR now as well, added several important German Cities which will have 40.
* Reworked how Dual Monarchy works: They now start with 32 LR across their entire nation. Depending on the path they choose this can be improved to 35. (French path only French Cores, Dual Path you have to wait until 1870 but get both English and French cores to 35, English path you get English and Irish cores buffed) Paths can only be chosen in 1840, although the above Anglois changes means you'll have at least 3.3 million for mobilisation for the first few wars (which is the same balance as per normal DOD)
* For the above, some decisions like coring Ireland as Scandinavia, Coming Home as Beornia, or coring France as Burgundy will buff the LR up as well, although it will only buff them to 35 so this is just to prevent Dual Monarchy from spite picking a path to deny LR.
* Arcadia gets the South_American_Immigrant_Nation flag when they form, meaning they'll get immigrants year-round like USA in PUIR. As a counter if Gran Colombia manages to annex all of Plantagenias cores and prevent Arcadia from ever forming they get that buff instead.
* Added back in Spain's war with GC and added decisions to annex the resulting puppets: Hispanic Commonwealth is now back in fashion and better than ever thanks to split immigration! (There's no tag change though since you already have to tag switch to Iberia to get Catalan)
* Adjusted Region borders to be closer to how they are in proper DoD in certain places (mostly Arcadia), split some regions as well for more functional borders.
* Made Provence an optional roster: They just get a decision that will give them Tuscany again should they be played by a player: AI will not take this decision.
* Added Revanchism from IGOR.
	* Not sure why it wasn't, everyone loves fighting to the bitter end in DoD so this just makes this adds more roaching.
* Added back more minor rarely used paths :
	* Added the Holy Britannian path for Beornia and their general decision just to get cores in Ameriga. Minorly buffed the path by letting them get Afro-Amerigan.
	* Added back the Southern and Northern paths for Russia. 
		* Only did some minor buffs to Northern, mostly just there for the options even though Western is still probably the best. Although there's a pretty good argument for Southern + Western (just kill PLC anyway lol) actually being the best late game with Reno Assim but eh.
* Fixed issues with events and poorly coded decisions (Italy formables, Germany formables, etc)
* Added back Ottos's paths and their starting system is more accurate to the original (no natty rebels but still have reactionaries)
* Readded the HRE formable. It's hard locked after 1848 instead of being dependant on Spring Time of Nations (more predictable) but otherwise has the same restrictions and benefits as before.
	* HRE is super strong and in 99% of campaigns it may kill the game, but I feel like the threat of an HRE is an important part of DoD early game. 
* Added Tartarstan Formable back.
	* They just have the same accepted and decisions that most mods give them + Turkic.
* Finished adding in the Chinese Unification CBs: They are now state by state basis and cost 2.5 infamy but can be justified as quick as cores, they still have the same WS cost as normal take states as per usual (this is based on how they work in DoD normally)
* Added back Incan decision to get Granadan and also to move their capital to Cusco. Additionally I gave them a flat buff to pop growth (0.001) instead of it being a whole over-complicated event province based system.
* Added new 'Meme Decisions' trigger for Host Nation to choose. These are paths or decisions that stray a bit too far from traditional DoD balance. I'm leaving these as a toggle for Hosts to decide if they want to include them and which one they want to add:
	* Meme Decision : If Japan does Man in the High Castle and annexes all of Arcadian Xifang they can then build a canal that connects Alaska and Siberia, thus giving them connected to Arcadia (!)
	* Meme Decision : Renable Scandinavia getting Elbian if they do Nordtyskland (The 'Annex all the Elbian minors' decision).
	* Meme Decision : Burgundy can get Boer accepted and core Batavia if they full annex them.
	* More decisions may be added as Meme Decisions such as a buffed up Northern Path or current decisions may be moved to Meme Decisions if they are agreed to be too strong. 
* For now, got rid of the unique 4/4 Generals per country as there's a massive exploit possible: If you tag switch and the tag doesn't have the proper flag you will end up getting 2 Cenas if previous one is still alive
	* This is an exploit that potentially exists in a lot of Alt His mods that just ported over the "General Events.txt" from IGOR. You need to make sure that any tag switching will not either turn into a nation that has a Unique General or add exceptions for each one. I personally decided that this was too much hassle for something that's probably not even really worth it, chances are you'll remember the name of your 5/4 more than the pre-set Cena.
	* For example: I found this issue exists in Femgirl DOD with Muscovy, who doesn't count as Russia. They are given a Generic John Cena instead. When they form Russia, they're flagged as getting a Unique Cena so they now get two 4/4's for free. The same exploit existed in my mod until I deleted the non-generic events.
* Added more Loc and fixed other smaller issues such as State Sizing not counting Spain and GC.
* Added back decision for Batavia to form Netherlands and return home. They need Anvers to form.
* Adjusted mobilisation: Base for Civved nations is now 4%. Lowered the 1870 Mob tech to 1% from 2%. This is to try and adjust some of the early game mobilisation sizes which is naturally much higher in base DoD thanks to the HPMeme draft laws.
* Added back minor Burgundy decisions like coring Savoie.

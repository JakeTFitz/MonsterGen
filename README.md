# MonsterGen
The Java monster generator GUI for 5e monsters. 
README

Hey thanks for taking a look at my Monster Randomizer 2 !!!!!!

This is a dynamic DM homebrewing tool for monsters or NPCs when you have those tricksy ruleslawer players.

So how does it work?

Just hitting the Generate button will give you a completely random monster fit with stats, traits and actions scaled to its number of Hit Dice (1-30).


GENERATION
Quickly! CLEAR my stats and GENERATE new ones! no rush tho

If at any point you like what a particular Characteristic has generated, then you may hit that characteristics LOCK button. 
Or if you dont like what you see, manually enter what you want into that characteristic's Text Box or roll the dice on the Generator once again.
Rinse and repeat until you have zoomed in on a monster you are really proud of.


INPUTS
For some more choices, notice that not all characteristics have to be on a monster to make it good.
So if you manually enter a SPACE into a Text Box with a * in the name it will just not appear on the monster. (Hitting the LOCK button on any characteristic with a * in the name will LOCK in its non-existance if it did not appear)

Whether you knew it or not, traidionally Size dictates the size of Hit Dice the monster has, so be sure to enter "Medium" if you want d8 Hit Dice, or manually enter the Hit Dice you want.
Similiarly, many characteristics are plural, so if you really want 3 Skill Proficiies, Saving Throw Proficiencies, or 3 different actions you can just enter a good ol' 3 into the appropriate text box.
Or for Skill Proficiencies you may manually enter SPACE sensitive skills into the Text Box and generate with the properly calculated proficiencies. (Ex. "Animal-Handling")
And for Saving Throw Proficiencies you may manually enter each stat you want proficiency in into the Text Box. (Ex. "STR CON")


TRAITS
Traits are a fun characteristic of a monster which can range from an absolute debuff to where most of the CR comes from. 
This characteristic can: be generated randomly, locked into not existing, be told to generate X number of traits, or... you can enter the names of Traits you want manually.
Everything about this is case sensitive and SPACE sensitive so if every Trait Name ends in and period (".") and all spaces are filled in with a dash("-") then the generator will supply you with your traits in full.

ACTIONS
Actions are an important stylization for a monster. You can see a monster can range in Actions from Multiattack, to bigger attacks that dont fit into the multiattack, and attacks so powerful they are limited to (Recharge 6).
And attacks vary from melee attacks, to ranged attacks, to AOE attacks. 
You may input a desired number of actions or whole a text if you got the time.

LEGENDARY
Being Legendary is a privelege that only the strongest monsters naturally generate with. 
Legendary actions provide the same input opportunities as actions, and may also be LOCKed into non-existance at the user's discretion.
Manually Input "Legendary Resistance" and 3 Legendary Actions if you want to manually make a creature look naturally Legendary. (Who doesnt want to see a Rat With Legendary Actions!?)

SPELLCASTING
One of the more common traits among monsters. Spellcasting is a unique process in the generator which defines the monster as an Xth level spellcaster with appropriate spell levels and spell slots.
All of the spells are randomly generated in all characteristics except their text. So I hope this inspires you to create effects those players dont see comin!
You may enter "Spellcasting." into the Traits Text Box to guarentee this trait.


FANTASY NAMES
As we all know nonsense fantasy names have their charm and you may toggle the FANTASY button to generate nonsense instead of our modern names.


FOCUS
So you dont want a demon vulnerable to fire damage huh?
Well then toggle the FOCUS button and Monsters become a little more like you see in the monster manual, often focusing on the generalities of its creature type to narrow in on whats valid to Generate.
(Currently this restricts the options by creature type for alignment, size, damage alteration, and by Size for reach.
Be warned: if you manually enter a non-traditional answer ("Samurai") or a mispelling ("Medum") of either Creature Type or Size the FOCUS code will not do anything helpful.


So go on! Hit the CLEAR button and see what you get!


Notes. 
1. CR is nonsense so i dont include it. I did not include any traits that just give skill proficiency or allow for the casting of real spells. 
2. Coming soon is more FOCUS code but its doubling the generation code so it takes long time. 
3. It can be jarring to see the generator spawn a monster with number HitDice > 20 equally as often as it spawns one with number Hit Dice <= 10. So ride the wave and pick and choose what you want or start with a manual entry numHitDice to limit the range of outputs.
4. Often the randomness can lead to effects that a DM might find illogical and unable to rationalize such as an INT save to become grappled, so I recommend if you like the effect but not the saving throw, then LOCK it in and sift through the text box to change it.
5. I went and found as many Conditions in the game as I could and used them for condition immunities and condition Effects. This includes some rare to unused ones such as Exhaustion, Invisibled, and Suprised. 
I think its fun to make prey invisible to its allies, apply Exhaustion as a kill condition more often, and to apply the Suprised condition which up until now has had only one use (and its so similiar to just being stunned). I being heavily obscured could also be fun, lemme know.
6. If you know me, try out some names we know in the Generator and see what you get.....

# Magic

## Spell Books
[Mages](Mage.md) record their spells in "spell books". These do not have to be literal books, but rather may be collections of scrolls, arcane formula carved into wood or most any other device the player and GM can agree on. The primary limitation is that the spell book be separate from the character (arcane tattoos are more of a magical item than a spell book). The language in which spells are written are typically a magical cipher learned from the caster's teacher and modified in their own way. As such, deciphering someone else's spell book can be a long and arduous process involving a mage's [special senses](Mage.md#sense%20magic).

A typical spell book costs 100sp and can hold up to 100 pages worth of spells.  Alternatively, a Small spell book (typically used by [hybrid casters](Glossary.md#hybrid%20class)) only costs 50sp and can hold up to 50 pages worth of spells.

### Replacing a spell book
If a spell book is lost or destroyed, it may be recreated using the spells that the spellcaster has already prepared. Doing so requires a new spell book and takes the same cost in time and materials as learning each spell anew, but does not require any roll.

## Learning New Spells
New spells take hours, days or weeks to properly learn. While learning a new spell, the mage may take part in no other form of downtime activity; all their working hours being consumed with study and preparation.

When learning a new spell, it must be recorded in the mage’s spell book. Each spell takes up a number of pages equal to its Rank. For each page a spell takes up, it also takes 10 hours and 100sp worth of study and materials to properly learn and record the spell.

Once the calculated learning time has passed, the mage makes a Intelligence+[Lore (Magic)](Skills.md#lore) roll with a Difficulty equal to 10 plus the spell's Rank. Failure results in the loss of all time and materials used in the attempt and the mage may not attempt to learn this spell again until they’ve gained a new level.

### Learning From a Mentor
Spellcasters may also learn spells from other casters (if they can find one willing to teach their jealously guarded secrets). The teacher grants the student +3 (or higher) bonus to the roll to learn the spell. This also halves the amount of time required to learn the spell (though the material cost remains the same).

## Preparing Spells
A spellcaster may only cast spells they have prepared.  The spellcaster class tables show how many spells may be prepared at any one time. Preparing a spell takes 10 minutes times the spell's Rank. Once a spell is prepared, it remains prepared until the caster chooses to replace it with a different spell or some event causes the mage to temporarily lose the spell.

### Casting Unprepared Spells
A spellcaster may cast unprepared spells directly from their [spell book](#spell%20books). Doing so increases the casting time of the spell 1 [step](Glossary.md#time%20steps), to a minimum of 10 minutes.

*For example, a character wishing to cast <ins>Commune</ins> as an unprepared spell must have their spell book on hand. Since the base casting time is 3 Exploration Turns (30 minutes), it will now take 3 hours to cast the spell in this manner.*

### Cantrips
Cantrips are small non-combat magical effects that spellcasters can perform without needing to make an [Invocation Roll](#invocation%20dice).  Exactly what "tricks" may be performed depends on which spells the spellcaster has prepared and is left as a negotiation between the player and GM.  The ground rules are that cantrips cannot do damage, cannot be equivalent to [Battle Maneuvers](Battle_Maneuvers.md) and cannot be cast from further than the base spell's range or [Near](CoinAndItsUses.md#ranges) (whichever is less).  *For example, a [Mage](Mage.md) with the <ins>Fireball</ins> spell would be able to light a pipe, torch or even campfire as a cantrip so long as it's within Near range.*

## The Invocation Roll
With thanks to the [Spell Dice](https://www.necropraxis.com/2013/11/01/spell-dice/) system by Necropraxis.

### Quick Summary
- Spellcasters get an [invocation pool](#the%20invocation%20dice%20pool) of six-sided dice based on their *Level* and *Wisdom Modifier*.
- Any number of dice may be used to cast a spell.
- *[Spell difficulty](#spell%20difficulty)* is equal to the spell’s [rank](#rank) times 3.
- Any *invocation die* that that rolls a natural 1 or 2 is removed from the pool (aka *expended*).
- Some expended *invocation dice* may be recovered after a [rest](Rest_and_Recovery.md).

### The Invocation Dice Pool
A spellcaster gets a pool of six-sided dice with which to cast their spells.  The total number of dice in the pool is based on the character’s *Class* and *Level* plus additional dice equal to their *Wisdom Modifier*.

*Example: A 5th level [Mage](classes/Mage.md) with a 16 Wisdom (+2 modifier) has a pool of 7d6 <ins>Invocation Dice</ins>.*

When casting a spell, the caster may choose to roll any number of *invocation dice* in order to try to meet or exceed the [spell difficulty](#spell%20difficulty).  Any dice rolling a natural ‘1’ or ‘2’ are *expended* from the pool (though still counted toward the casting result) and cannot be used again until *recovered*.

#### Exhausting Magic
If a spellcaster finds themselves in need of a quick boost of magical energy, they may add half their [caster level](Glossary.md#caster%20level) (round up) to their *Invocation Roll* by gaining 1 level of [Exhaustion](Conditions.md#Exhaustion).  This may be done as a Free Action.

### Spell Difficulty
A spell’s *difficulty* is equal to 3 times its *rank*.

<!-- directives:[] -->
<div id="content">
	<table border=2>
		<thead>
			<tr style="background-color:#708090;">
				<th id="rank" style="text-align:center;">Rank</th>
				<th id="difficulty" style="text-align:center;">Difficulty</th>
			</tr>
		</thead>
		<tbody>
			<tr>
				<td style="text-align:center;">1</td>
				<td style="text-align:center;">3</td>
			</tr>
			<tr style="background-color:#91a3b0;">
				<td style="text-align:center;">2</td>
				<td style="text-align:center;">6</td>
			</tr>
			<tr>
				<td style="text-align:center;">3</td>
				<td style="text-align:center;">9</td>
			</tr>
			<tr style="background-color:#91a3b0;">
				<td style="text-align:center;">4</td>
				<td style="text-align:center;">12</td>
			</tr>
			<tr>
				<td style="text-align:center;">5</td>
				<td style="text-align:center;">15</td>
			</tr>
			<tr style="background-color:#91a3b0;">
				<td style="text-align:center;">6</td>
				<td style="text-align:center;">18</td>
			</tr>
		</tbody>
	</table>
</div>

If a spell’s *difficulty* is not met, the spell is not cast.  However, the mage may choose to continue casting the spell.  This requires that the mage reserve the dice already used in casting the spell and [Concentrate](Conditions.md#Concentrating) long enough to satisfy the spell’s *casting time* again.  Once this time increment has passed, the mage may choose to roll additional *invocation dice* and add their total to the *spellcasting roll*.  In this way, more difficult spells can be cast over multiple “rounds”.

*Example: The above 5th level [Mage](classes/Mage.md) with a 16 Wisdom is attempting to cast <ins>Fireball</ins> (a Rank 3 (difficulty 9) spell).  They choose to be conservative and roll only 3 dice, rolling a ‘1’, '3' and ‘4’, for a total of 8.  As the total is less than the Difficulty, the spell is not cast.  The character chooses to continue the casting. This means they are now Concentrating and they set aside the 3 dice already rolled, leaving 4 left unallocated in their Invocation Pool.  On their next round (since the spell has a Casting Time of 1 Action), they choose to roll one more die, getting another ‘1’.  This brings their total to 9, successfully casting the spell.  The two ‘1’s are now Expended, and the other three committed dice are now released.  This leaves the caster with 5 dice in their Invocation Pool.  Note that no [Mishap](#Mishaps) roll is made because the two '1's occurred on two separate rolls.*

### Invocation Dice Recovery
Whenever a spellcaster completes a [Short Rest](Rest_and_Recovery.md#Short%20Rest), they may roll a portion of their *Expended* *Invocation Dice*.  Any of those dice that come up a 2+ are placed back into the caster’s *Invocation Pool*.  The number of dice that may be rolled after a short rest is equal to their *Wisdom Modifier*.

After a [Long Rest](Rest_and_Recovery.md#Long%20Rest), the same procedure is followed with the following 2 exceptions:
- A number of dice equal to the character’s *Wisdom Modifier* are recovered without rolling.
- The caster may then roll all their remaining *Expended* *Invocation Dice*.

After an [Extended Rest](Rest_and_Recovery.md#Extended%20Rest), all *Invocation Dice* that have been *Expended* are automatically recovered with no roll.

### Spell Identification
If a spellcaster can directly see and hear another spellcaster as they cast a spell, they may attempt an Intelligence+[Perception](Skills.md#perception) check vs. the spell's [Difficulty](#spell%20difficulty) in order to identify the spell being cast.  If the observing mage can only see or hear the casting mage, but not both, this check is performed at *Disadvantage*.

If the check is successful and the mage has the spell in their spellbook, they completely identify the spell.

If the check is successful but the mage does not have the spell in their spellbook, they will only be able to discern the following:
1. Whether or not the spell being cast is of a Rank the observing mage can cast.
2. Whether the spell is offensive, defensive or utilitarian in nature.

If the check is failed, the observing mage gains no information.

Characters without the *Sense Magic* ability may not attempt this check at all.

## Spell Descriptions

### Components
We will be using the Material Component rules from AD&D.

## Traditions

### Animism
The art of conjuring the spirits of the land and nature to perform "favors" for the caster.  This tradition is most often taught by Druids and other orders with a nature focus.

<table border=2>
	<tr style="background-color:#708090;">
		<th align="center"><b>Rank</b></th>
		<th align="left"><b>Spell</b></th>
		<th align="center"><b>Difficulty</b></th>
		<th align="right"><b>Casting Time</b></th>
		<th align="left"><b>Components</b></th>
		<th align="left"><b>Notes</b></th>
	</tr>
	<tr>
		<td align="center"></td><!--Rank-->
		<td align="left"></td><!--Spell-->
		<td align="center"></td><!--Difficulty-->
		<td align="right"></td><!--Casting Time-->
		<td align="left"></td><!--Components-->
		<td align="left"></td><!--Notes-->
	</tr>
	<tr style="background-color:#708090;">
		<td colspan=6>* This spell is reversible.<br/># This is a new spell.</td>
	</tr>
</table>

### Conjuration
The art of summoning otherworldly creatures (such as Elemental, Demons or possibly Celestials) to do the caster's bidding.

<table border=2>
	<tr style="background-color:#708090;">
		<th align="center"><b>Rank</b></th>
		<th align="left"><b>Spell</b></th>
		<th align="center"><b>Difficulty</b></th>
		<th align="right"><b>Casting Time</b></th>
		<th align="left"><b>Components</b></th>
		<th align="left"><b>Notes</b></th>
	</tr>
	<tr>
		<td align="center"></td><!--Rank-->
		<td align="left"></td><!--Spell-->
		<td align="center"></td><!--Difficulty-->
		<td align="right"></td><!--Casting Time-->
		<td align="left"></td><!--Components-->
		<td align="left"></td><!--Notes-->
	</tr>
	<tr style="background-color:#708090;">
		<td colspan=6>* This spell is reversible.<br/># This is a new spell.</td>
	</tr>
</table>

### Necromancy
The arts of dealing with the dead.  For benign practitioners, they use these spells to shepherd and watch over the dead.  More malevolent casters will use this magic to control the dead and avoid death through the promise of becoming a vampire, lich or other form of intelligent undead.

<table border=2>
	<tr style="background-color:#708090;">
		<th align="center"><b>Rank</b></th>
		<th align="left"><b>Spell</b></th>
		<th align="center"><b>Difficulty</b></th>
		<th align="right"><b>Casting Time</b></th>
		<th align="left"><b>Components</b></th>
		<th align="left"><b>Notes</b></th>
	</tr>
	<tr>
		<td align="center"></td><!--Rank-->
		<td align="left"></td><!--Spell-->
		<td align="center"></td><!--Difficulty-->
		<td align="right"></td><!--Casting Time-->
		<td align="left"></td><!--Components-->
		<td align="left"></td><!--Notes-->
	</tr>
	<tr style="background-color:#708090;">
		<td colspan=6>* This spell is reversible.<br/># This is a new spell.</td>
	</tr>
</table>

### Sorcery
The arts of trickery, illusion and mesmerism.

<table border=2>
	<tr style="background-color:#708090;">
		<th align="center"><b>Rank</b></th>
		<th align="left"><b>Spell</b></th>
		<th align="center"><b>Difficulty</b></th>
		<th align="right"><b>Casting Time</b></th>
		<th align="left"><b>Components</b></th>
		<th align="left"><b>Notes</b></th>
	</tr>
	<tr>
		<td align="center"></td><!--Rank-->
		<td align="left"></td><!--Spell-->
		<td align="center"></td><!--Difficulty-->
		<td align="right"></td><!--Casting Time-->
		<td align="left"></td><!--Components-->
		<td align="left"></td><!--Notes-->
	</tr>
	<tr style="background-color:#708090;">
		<td colspan=6>* This spell is reversible.<br/># This is a new spell.</td>
	</tr>
</table>


### Thaumaturgy
The "art" of making miracles.  This magical tradition is most often taught by various holy (or unholy) orders and is believed to be invoking the power of the Divine to affect the world.
<table border=2>
	<tr style="background-color:#708090;">
		<th align="center"><b>Rank</b></th>
		<th align="left"><b>Spell</b></th>
		<th align="center"><b>Difficulty</b></th>
		<th align="right"><b>Casting Time</b></th>
		<th align="left"><b>Components</b></th>
		<th align="left"><b>Notes</b></th>
	</tr>
	<tr>
		<td align="center">1</td><!--Rank-->
		<td align="left">Cure Light Wounds*</td><!--Spell-->
		<td align="center">3</td><!--Difficulty-->
		<td align="right"></td><!--Casting Time-->
		<td align="left"></td><!--Components-->
		<td align="left"></td>
	</tr>
	<tr>
		<td align="center">1</td><!--Rank-->
		<td align="left">Detect Unholy#*</td><!--Spell-->
		<td align="center">3</td><!--Difficulty-->
		<td align="right"></td><!--Casting Time-->
		<td align="left"></td><!--Components-->
		<td align="left"></td>
	</tr>
	<tr>
		<td align="center">1</td><!--Rank-->
		<td align="left">Light*</td><!--Spell-->
		<td align="center">3</td><!--Difficulty-->
		<td align="right"></td><!--Casting Time-->
		<td align="left"></td><!--Components-->
		<td align="left"></td>
	</tr>
	<tr>
		<td align="center">1</td><!--Rank-->
		<td align="left">Protection from Unholy#*</td><!--Spell-->
		<td align="center">3</td><!--Difficulty-->
		<td align="right"></td><!--Casting Time-->
		<td align="left"></td><!--Components-->
		<td align="left"></td>
	</tr>
	<tr>
		<td align="center">1</td><!--Rank-->
		<td align="left">Purify Food and Water</td><!--Spell-->
		<td align="center">3</td><!--Difficulty-->
		<td align="right"></td><!--Casting Time-->
		<td align="left"></td><!--Components-->
		<td align="left"></td>
	</tr>
	<tr>
		<td align="center">1</td><!--Rank-->
		<td align="left">Remove Fear*</td><!--Spell-->
		<td align="center">3</td><!--Difficulty-->
		<td align="right"></td><!--Casting Time-->
		<td align="left"></td><!--Components-->
		<td align="left">Removes/Causes the <i>Frightened</i> condition.</td>
	</tr>
	<tr>
		<td align="center">1</td><!--Rank-->
		<td align="left">Resist Cold</td><!--Spell-->
		<td align="center">3</td><!--Difficulty-->
		<td align="right"></td><!--Casting Time-->
		<td align="left"></td><!--Components-->
	</tr>
	<tr style="background-color:#91a3b0;">
		<td align="center">2</td><!--Rank-->
		<td align="left">Bless*</td><!--Spell-->
		<td align="center">6</td><!--Difficulty-->
		<td align="right"></td><!--Casting Time-->
		<td align="left"></td><!--Components-->
		<td align="left"></td><!--Notes-->
	</tr>
	<tr style="background-color:#91a3b0;">
		<td align="center">2</td><!--Rank-->
		<td align="left">Find Traps</td><!--Spell-->
		<td align="center">6</td><!--Difficulty-->
		<td align="right"></td><!--Casting Time-->
		<td align="left"></td><!--Components-->
		<td align="left"></td><!--Notes-->
	</tr>
	<tr style="background-color:#91a3b0;">
		<td align="center">2</td><!--Rank-->
		<td align="left">Hold Person</td><!--Spell-->
		<td align="center">6</td><!--Difficulty-->
		<td align="right"></td><!--Casting Time-->
		<td align="left"></td><!--Components-->
		<td align="left"></td><!--Notes-->
	</tr>
	<tr style="background-color:#91a3b0;">
		<td align="center">2</td><!--Rank-->
		<td align="left">Know Allegiance#</td><!--Spell-->
		<td align="center">6</td><!--Difficulty-->
		<td align="right"></td><!--Casting Time-->
		<td align="left"></td><!--Components-->
		<td align="left"></td><!--Notes-->
	</tr>
	<tr style="background-color:#91a3b0;">
		<td align="center">2</td><!--Rank-->
		<td align="left">Resist Fire</td><!--Spell-->
		<td align="center">6</td><!--Difficulty-->
		<td align="right"></td><!--Casting Time-->
		<td align="left"></td><!--Components-->
		<td align="left"></td><!--Notes-->
	</tr>
	<tr style="background-color:#91a3b0;">
		<td align="center">2</td><!--Rank-->
		<td align="left">Silence 15' Radius</td><!--Spell-->
		<td align="center">6</td><!--Difficulty-->
		<td align="right"></td><!--Casting Time-->
		<td align="left"></td><!--Components-->
		<td align="left"></td><!--Notes-->
	</tr>
	<tr style="background-color:#91a3b0;">
		<td align="center">2</td><!--Rank-->
		<td align="left">Snake Charm</td><!--Spell-->
		<td align="center">6</td><!--Difficulty-->
		<td align="right"></td><!--Casting Time-->
		<td align="left"></td><!--Components-->
		<td align="left"></td><!--Notes-->
	</tr>
	<tr style="background-color:#91a3b0;">
		<td align="center">2</td><!--Rank-->
		<td align="left">Speak with Animals</td><!--Spell-->
		<td align="center">6</td><!--Difficulty-->
		<td align="right"></td><!--Casting Time-->
		<td align="left"></td><!--Components-->
		<td align="left"></td><!--Notes-->
	</tr>
	<tr>
		<td align="center">3</td><!--Rank-->
		<td align="left">Continual Light*</td><!--Spell-->
		<td align="center">9</td><!--Difficulty-->
		<td align="right"></td><!--Casting Time-->
		<td align="left"></td><!--Components-->
		<td align="left"></td><!--Notes-->
	</tr>
	<tr>
		<td align="center">3</td><!--Rank-->
		<td align="left">Cure Disease*</td><!--Spell-->
		<td align="center">9</td><!--Difficulty-->
		<td align="right"></td><!--Casting Time-->
		<td align="left"></td><!--Components-->
		<td align="left"></td><!--Notes-->
	</tr>
	<tr>
		<td align="center">3</td><!--Rank-->
		<td align="left">Growth of Animal</td><!--Spell-->
		<td align="center">9</td><!--Difficulty-->
		<td align="right"></td><!--Casting Time-->
		<td align="left"></td><!--Components-->
		<td align="left"></td><!--Notes-->
	</tr>
	<tr>
		<td align="center">3</td><!--Rank-->
		<td align="left">Locate Object</td><!--Spell-->
		<td align="center">9</td><!--Difficulty-->
		<td align="right"></td><!--Casting Time-->
		<td align="left"></td><!--Components-->
		<td align="left"></td><!--Notes-->
	</tr>
	<tr>
		<td align="center">3</td><!--Rank-->
		<td align="left">Remove Curse*</td><!--Spell-->
		<td align="center">9</td><!--Difficulty-->
		<td align="right"></td><!--Casting Time-->
		<td align="left"></td><!--Components-->
		<td align="left"></td><!--Notes-->
	</tr>
	<tr>
		<td align="center">3</td><!--Rank-->
		<td align="left">Striking</td><!--Spell-->
		<td align="center">9</td><!--Difficulty-->
		<td align="right"></td><!--Casting Time-->
		<td align="left"></td><!--Components-->
		<td align="left"></td><!--Notes-->
	</tr>
	<tr style="background-color:#91a3b0;">
		<td align="center">4</td><!--Rank-->
		<td align="left">Create Water</td><!--Spell-->
		<td align="center">12</td><!--Difficulty-->
		<td align="right"></td><!--Casting Time-->
		<td align="left"></td><!--Components-->
		<td align="left"></td><!--Notes-->
	</tr>
	<tr style="background-color:#91a3b0;">
		<td align="center">4</td><!--Rank-->
		<td align="left">Cure Serious Wounds*</td><!--Spell-->
		<td align="center">12</td><!--Difficulty-->
		<td align="right"></td><!--Casting Time-->
		<td align="left"></td><!--Components-->
		<td align="left"></td><!--Notes-->
	</tr>
	<tr style="background-color:#91a3b0;">
		<td align="center">4</td><!--Rank-->
		<td align="left">Neutralize Poison</td><!--Spell-->
		<td align="center">12</td><!--Difficulty-->
		<td align="right"></td><!--Casting Time-->
		<td align="left"></td><!--Components-->
		<td align="left"></td><!--Notes-->
	</tr>
	<tr style="background-color:#91a3b0;">
		<td align="center">4</td><!--Rank-->
		<td align="left">Protection from Unholy 10' Radius#*</td><!--Spell-->
		<td align="center">12</td><!--Difficulty-->
		<td align="right"></td><!--Casting Time-->
		<td align="left"></td><!--Components-->
		<td align="left"></td><!--Notes-->
	</tr>
	<tr style="background-color:#91a3b0;">
		<td align="center">4</td><!--Rank-->
		<td align="left">Speak with Plants</td><!--Spell-->
		<td align="center">12</td><!--Difficulty-->
		<td align="right"></td><!--Casting Time-->
		<td align="left"></td><!--Components-->
		<td align="left"></td><!--Notes-->
	</tr>
	<tr style="background-color:#91a3b0;">
		<td align="center">4</td><!--Rank-->
		<td align="left">Sticks to Snakes</td><!--Spell-->
		<td align="center">12</td><!--Difficulty-->
		<td align="right"></td><!--Casting Time-->
		<td align="left"></td><!--Components-->
		<td align="left"></td><!--Notes-->
	</tr>
	<tr>
		<td align="center">5</td><!--Rank-->
		<td align="left">Commune</td><!--Spell-->
		<td align="center">15</td><!--Difficulty-->
		<td align="right"></td><!--Casting Time-->
		<td align="left"></td><!--Components-->
		<td align="left"></td><!--Notes-->
	</tr>
	<tr>
		<td align="center">5</td><!--Rank-->
		<td align="left">Create Food</td><!--Spell-->
		<td align="center">15</td><!--Difficulty-->
		<td align="right"></td><!--Casting Time-->
		<td align="left"></td><!--Components-->
		<td align="left"></td><!--Notes-->
	</tr>
	<tr>
		<td align="center">5</td><!--Rank-->
		<td align="left">Dispel the Unholy#*</td><!--Spell-->
		<td align="center">15</td><!--Difficulty-->
		<td align="right"></td><!--Casting Time-->
		<td align="left"></td><!--Components-->
		<td align="left"></td><!--Notes-->
	</tr>
	<tr>
		<td align="center">5</td><!--Rank-->
		<td align="left">Insect Plague</td><!--Spell-->
		<td align="center">15</td><!--Difficulty-->
		<td align="right"></td><!--Casting Time-->
		<td align="left"></td><!--Components-->
		<td align="left"></td><!--Notes-->
	</tr>
	<tr>
		<td align="center">5</td><!--Rank-->
		<td align="left">Quest*</td><!--Spell-->
		<td align="center">15</td><!--Difficulty-->
		<td align="right"></td><!--Casting Time-->
		<td align="left"></td><!--Components-->
		<td align="left"></td><!--Notes-->
	</tr>
	<tr>
		<td align="center">5</td><!--Rank-->
		<td align="left">Raise Dead*</td><!--Spell-->
		<td align="center">15</td><!--Difficulty-->
		<td align="right"></td><!--Casting Time-->
		<td align="left"></td><!--Components-->
		<td align="left"></td><!--Notes-->
	</tr>
	<tr style="background-color:#91a3b0;">
		<td align="center">6</td><!--Rank-->
		<td align="left"></td><!--Spell-->
		<td align="center"></td><!--Difficulty-->
		<td align="right"></td><!--Casting Time-->
		<td align="left"></td><!--Components-->
		<td align="left"></td><!--Notes-->
	</tr>
	<tr style="background-color:#708090;">
		<td colspan=6>* This spell is reversible.<br/># This is a new spell.</td>
	</tr>
</table>

### Witchcraft
A blend of Animism, Conjuration and Sorcery frequently taught "master" to apprentice in rural villages and other backwaters.  It's less of a "tradition" than a hodgepodge of mystical practices.

<table border=2>
	<tr style="background-color:#708090;">
		<th align="center"><b>Rank</b></th>
		<th align="left"><b>Spell</b></th>
		<th align="center"><b>Difficulty</b></th>
		<th align="right"><b>Casting Time</b></th>
		<th align="left"><b>Components</b></th>
		<th align="left"><b>Notes</b></th>
	</tr>
	<tr>
		<td align="center"></td><!--Rank-->
		<td align="left"></td><!--Spell-->
		<td align="center"></td><!--Difficulty-->
		<td align="right"></td><!--Casting Time-->
		<td align="left"></td><!--Components-->
		<td align="left"></td><!--Notes-->
	</tr>
	<tr style="background-color:#708090;">
		<td colspan=6>* This spell is reversible.<br/># This is a new spell.</td>
	</tr>
</table>

### Wizardry
A bit of a catch-all tradition that contains spells from almost every other tradition.  This is the most common tradition taught to arcane casters.

<table border=2>
	<tr style="background-color:#708090;">
		<th align="center"><b>Rank</b></th>
		<th align="left"><b>Spell</b></th>
		<th align="center"><b>Difficulty</b></th>
		<th align="right"><b>Casting Time</b></th>
		<th align="left"><b>Components</b></th>
		<th align="left"><b>Notes</b></th>
	</tr>
	<tr>
		<td align="center"></td><!--Rank-->
		<td align="left"></td><!--Spell-->
		<td align="center"></td><!--Difficulty-->
		<td align="right"></td><!--Casting Time-->
		<td align="left"></td><!--Components-->
		<td align="left"></td><!--Notes-->
	</tr>
	<tr style="background-color:#708090;">
		<td colspan=6>* This spell is reversible.<br/># This is a new spell.</td>
	</tr>
</table>

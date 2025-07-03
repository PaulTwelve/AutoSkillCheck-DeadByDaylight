<h1 align="center">AutoSkillCheck FOR DeadByDaylight</h1>

#### This is a bot written in the AHK language to automatically pass reaction checks in Dead By Daylight.  
> By pressing just 1 button, you can take your hands off the keyboard and, for example, drink tea, go to the toilet or why else are you too lazy to go through them.  
In addition to convenience, the bot pokes at the differences, which allows you to bypass the negative perks of the killers or participate in gen rush, which will allow you to win more often.

|<img src="https://i.ibb.co/4Y1JmBr/Auto-Skill-Check.png"></img>|<img src="https://github.com/user-attachments/assets/4c4308e9-fe75-4fa2-8fa2-1c262629fea4" width="66%"></img>|
|---|---|

------
# Tables of contents

* [Dignities](#dignities)
* [Game Settings](#game-settings)
* [Manual](#manual)
* [List perks for bot](#a-list-of-perks-for-ganrush-and-killer-perks-that-this-bot-bypasses)

------
<h3 align="center"><i>Dignities</i></h3>

- It is invisible to other players and anti-cheat.
- Passes Skill Checks perfectly.
- Supports most screen resolutions.
- Works with most shaders.
- There is an interface for convenient configuration for each user.
- There is an auto-update system. You don't have to download new versions every time.

------
<h3 align="center"><i>Game Settings</i></h3>

<table>
  <tr>
    <th>Tab</th>
    <th>Parameter</th>
  </tr>
  <tr>
    <td>GRAPHICS</td>
    <td>
      <pre>
«FULL SCREEN MODE» - «Fullscreen»/«Windowed Fullscreen»
«VSYNC» - «OFF»
«FPS LIMIT» - «120»
«SKILL CHECK SCALE» - «100%»</pre>
    </td>
  </tr>
  <tr>
    <td>CONTROLS</td>
    <td><pre>«INTERACTION BEHAVIOUR» - «Hold»</pre></td>
  </tr>
  <tr>
    <td>INPUT BINDING</td>
    <td>
      <pre>
«RUN» - «LShift»
«PICK UP ITEM INTERACTIONS» - «LMB»
«SECONDARY ACTION SKILL CHECK» - «Space»</pre>
    </td>
  </tr>
</table>

------
<h3 align="center"><i>Manual</i></h3>

1. Download AutoSkillCheck.exe
2. At the first launch:
    - Assign a convenient hotkey.
    - Set the reaction speed of the bot on the right slider.
    - Enlarged search field if the check is not in the center.
    - Save the settings.
3. Make sure that your settings in the game match [these settings](#game-settings).
4. Next, by going to the generator and pressing a key, the bot will start repairing it and passing checks. And an operation indicator will appear in the corner.

<table>
  <tr>
    <td><img src="https://i.ibb.co/Z8QFsyK/Indicator-G.png"></img></td>
    <td>The bot has started and is looking for matches.</td>
  </tr>
  <tr>
    <td><img src="https://i.ibb.co/N2nTwHv/Indicator-Y.png"></img></td>
    <td>The bot has found a match and is waiting for the red line.</td>
  </tr>
  <tr>
    <td><img src="https://i.ibb.co/bQWLZ9V/Indicator-R.png"></img></td>
    <td>The bot pressed <kbd>Space</kbd>.</td>
  </tr>
</table>

- Starting running on <kbd>Left Shift</kbd> will automatically stop the script.

------
<h3 align="center"><i>A list of perks for ganrush and killer perks that this bot bypasses</i></h3>

Icon|Name|Description
---|---|---
![Bardic Inspiration](https://static.wikia.nocookie.net/deadbydaylight_gamepedia_en/images/d/d8/IconPerks_bardicInspiration.png/revision/latest/scale-to-width-down/96?cb=20240514174158)|Bardic Inspiration|Press the Active Ability button while standing and motionless to enter the Performance interaction that lasts up to 15 seconds and empowers other Survivors within 16 metres of your location. The empowering effect depends on the result of you rolling a d20 and lasts for 90 seconds after completing the Performance: 1: You scream, but without notifying the Killer. 2 - 10: Skill Checks grant +1 % Progression. 11 - 19: Skill Checks grant +2 % Progression. 20: Skill Checks grant +3 % Progression. Bardic Inspiration has a cool-down of 110/100/90 seconds after completing the Performance or cancelling it.
![Deadline](https://static.wikia.nocookie.net/deadbydaylight_gamepedia_en/images/1/1c/IconPerks_deadline.png/revision/latest/scale-to-width-down/96?cb=20240109231533)|Deadline|Whenever you are in the Injured State, Deadline activates: Increases the Odds of triggering Skill Checks by 6/8/10 % while repairing or healing. Causes Skill Checks to appear in random places. Reduces the penalty for missed Skill Checks by -50 %.
![Decisive Strike](https://static.wikia.nocookie.net/deadbydaylight_gamepedia_en/images/e/ee/IconPerks_decisiveStrike.png/revision/latest/scale-to-width-down/96?cb=20161023112852)|Decisive Strike|After being unhooked or unhooking yourself, Decisive Strike activates for the next 40/50/60 seconds: When grabbed or picked up by the Killer, succeed a Skill Check to stab the Killer and escape from their grasp. Stuns the Killer for 4 seconds. Causes you to become the next Obsession.
![Déjà Vu](https://static.wikia.nocookie.net/deadbydaylight_gamepedia_en/images/8/89/IconPerks_dejaVu.png/revision/latest/scale-to-width-down/96?cb=20160605204905)|Déjà Vu|Unlocks potential in your Aura-reading ability: The Auras of the 3 Generators in closest proximity to one another are revealed to you at all times. Increases your Repair speed on those Generators by 4/5/6 %.
![Fogwise](https://static.wikia.nocookie.net/deadbydaylight_gamepedia_en/images/9/90/IconPerks_fogwise.png/revision/latest/scale-to-width-down/96?cb=20221102143122)|Fogwise|Succeeding a Great Skill Check while repairing a Generator reveals the Aura of the Killer to you for 4/5/6 seconds.
![Friendly Competition](https://static.wikia.nocookie.net/deadbydaylight_gamepedia_en/images/4/4c/IconPerks_friendlyCompetition.png/revision/latest/scale-to-width-down/96?cb=20230218135316)|Friendly Competition|Whenever you complete a Generator with at least one other Survivor, Friendly Competition activates: Increases your Repair speed, and that of the other Survivor(s) who completed the repairs with you, by +5 % for the next 45/60/75 seconds.
![Hyperfocus](https://static.wikia.nocookie.net/deadbydaylight_gamepedia_en/images/5/5d/IconPerks_hyperfocus.png/revision/latest/scale-to-width-down/96?cb=20220815051721)|Hyperfocus|Succeeding a Great Skill Check while repairing or healing grants +1 Token, up to a maximum of 6 Tokens: Increases the Skill Check Trigger odds and Pointer Rotation speed by +4 % per Token each, up to a maximum of +24 %. Increases the Skill Check Bonus progression by 10/20/30 % of its base value per Token, up to a maximum of 60/120/180 %.
![Invocation: Weaving Spiders](https://static.wikia.nocookie.net/deadbydaylight_gamepedia_en/images/0/07/IconPerks_invocationWeavingSpiders.png/revision/latest/scale-to-width-down/96?cb=20240220182529)|Invocation: Weaving Spiders|When in the Basement near the circle, press the Active Ability button to begin the Invocation, which takes 60 seconds to complete. During an Invocation, your Aura is revealed to all other Survivors and they can join in, accelerating the process by +100 %, if they too have an Invocation Perk equipped, or by +50 %, if they have not. Once the Invocation is completed, the following effects apply: Permanently reduces the Repair Charges requirement of all Generators in the Trial by 8/9/10 Charges. You automatically enter the Injured State from any previous Health State, and suffer from the Broken Status Effect for the remainder of the Trial.
![Overzealous](https://static.wikia.nocookie.net/deadbydaylight_gamepedia_en/images/9/99/IconPerks_overzealous.png/revision/latest/scale-to-width-down/96?cb=20220518112819)|Overzealous|After cleansing or blessing a Totem, Overzealous activates: Dull Totem: Increases your Repair speed by 8/9/10 %. Hex Totem: Increases your Repair speed by 16/18/20 %. Overzealous deactivates after losing a Health State by any means.
![Prove Thyself](https://static.wikia.nocookie.net/deadbydaylight_gamepedia_en/images/0/0f/IconPerks_proveThyself.png/revision/latest/scale-to-width-down/96?cb=20160605205049)|Prove Thyself|Increases the Repair speed by a stack-able 6/8/10 % per other Survivor within 4 metres of your location, up to a maximum of 18/24/30 %. Prove Thyself extends its effect to all Survivors within its range.
![Resilience](https://static.wikia.nocookie.net/deadbydaylight_gamepedia_en/images/e/ee/IconPerks_resilience.png/revision/latest/scale-to-width-down/96?cb=20160605205100)|Resilience|Increases your Action speeds for Repairing, Healing, Sabotaging, Unhooking, Vaulting, Cleansing, Blessing, Opening, and Unlocking by 3/6/9 % when in the Injured State.

Icon|Name|Description
---|---|---
![Call of Brine](https://static.wikia.nocookie.net/deadbydaylight_gamepedia_en/images/3/3b/IconPerks_callOfBrine.png/revision/latest/scale-to-width-down/96?cb=20220216115938)|Call of Brine|After performing the Damage Generator action on a Generator, Call of Brine activates for 60 seconds. The damaged Generator regresses at 115/120/125 % of the normal Regression speed and its Aura is highlighted to you in yellow. Receive a Loud Noise Notification each time a Survivor hits a Good Skill Check on the affected Generator.
![Coulrophobia](https://static.wikia.nocookie.net/deadbydaylight_gamepedia_en/images/4/45/IconPerks_coulrophobia.png/revision/latest/scale-to-width-down/96?cb=20180529205206)|Coulrophobia|For all Survivors within your Terror Radius, the following effects apply: Reduces their Healing speed by 30/40/50 %. Increases the Rotation speed of Healing Skill Checks by +50 %.
![Gearhead](https://static.wikia.nocookie.net/deadbydaylight_gamepedia_en/images/f/fd/IconPerks_gearhead.png/revision/latest/scale-to-width-down/96?cb=20200218172900)|Gearhead|After a Survivor loses a Health State, Gearhead activates for 30 seconds: While Gearhead is active, a Survivor succeeding a Good Skill Check while repairing reveals their Aura to you for 6/7/8 seconds.
![Hex: Huntress Lullaby](https://static.wikia.nocookie.net/deadbydaylight_gamepedia_en/images/1/11/IconPerks_hexHuntressLullaby.png/revision/latest/scale-to-width-down/96?cb=20170727160900)|Hex: Huntress Lullaby|Your hunt is an irresistible song of dread which muddles your prey's attention. Survivors failing a Repair Skill Check instantly regress the Generator by 2/4/6 % of its maximum possible Progression in addition to the default Progression penalty. Survivors failing a Healing Skill Check instantly regress the Healing Action by 2/4/6 % of its maximum possible Progression in addition to the default Progression penalty. Each time a Survivor is hooked, Hex: Huntress Lullaby grows in power and gains 1 Token, up to a maximum of 5 Tokens. Each Token reduces the timer between the Skill Check Warning cue and the Skill Check appearing for both Repair and Healing Skill Checks: 1 Token: reduction of -14 %. 2 Tokens: reduction of -28 %. 3 Tokens: reduction of -42 %. 4 Tokens: reduction of -56 %. 5 Tokens: complete suppression of the Warning cue.
![Oppression](https://static.wikia.nocookie.net/deadbydaylight_gamepedia_en/images/a/a1/IconPerks_oppression.png/revision/latest/scale-to-width-down/96?cb=20201112095043)|Oppression|Performing the Damage Generator action on a Generator activates Oppression: Causes up to 3 additional Generators to also start regressing. Triggers a difficult Skill Check for all Survivors currently repairing an affected Generator. Oppression has a cool-down of 60/50/40 seconds.
![Overcharge](https://static.wikia.nocookie.net/deadbydaylight_gamepedia_en/images/c/c3/IconPerks_overcharge.png/revision/latest/scale-to-width-down/96?cb=20170511153315)|Overcharge|Performing the Damage Generator action on a Generator applies Overcharge: The next Survivor interacting with that Generator is faced with a difficult Skill Check. Failing that Skill Check instantly regresses the Generator by 2/3/4 % of its maximum possible Progression in addition to the default Progression penalty. After Overcharge is applied to a Generator, the following effect also applies: Increases the Regression speed from 85 % to 130 % over the next 30 seconds.
![Undone](https://static.wikia.nocookie.net/deadbydaylight_gamepedia_en/images/1/11/IconPerks_undone.png/revision/latest/scale-to-width-down/96?cb=20240220182527)|Undone|Whenever a Survivor fails a Skill Check while repairing or healing, Undone gains +3 Tokens, up to a maximum of 18/24/30 Tokens. Performing the Damage Generator action on a Generator consumes all accumulated Tokens and applies the following effects: Instantly regresses the damaged Generator by -1 % per Token of its total Progression. Blocks the damaged Generator for 1 second per Token. Causes the damaged Generator to start regressing once it becomes unblocked. Undone has a cool-down of 60 seconds.
![Unnerving Presence](https://static.wikia.nocookie.net/deadbydaylight_gamepedia_en/images/a/a4/IconPerks_unnervingPresence.png/revision/latest/scale-to-width-down/96?cb=20160605205217)|Unnerving Presence|Survivors repairing or healing within your Terror Radius suffer from the following effects: Increases the Trigger odds of Skill Check by 10 %. Decreases the Success zone of Skill Checks by 40/50/60 %.

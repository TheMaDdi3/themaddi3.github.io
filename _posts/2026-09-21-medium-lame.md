---
layout: post
title: "Medium lame"
date: 2026-09-21
categories:
  - RPGs
math: true
image: /assets/img/keep-dungeoning-magic-shop.png
image_alt: The shopkeeper welcomes adventurers to a magic-item shop
image_in_content: true
---

When playing a game, rules and actions **get deeper** when you focus on the core part.

For example, in Dungeons & Dragons you focus on **fighting monsters**, slightly less on exploring dangerous and mysterious places and persuading or manipulating social contacts, and not really on managing the economics of a caravan company that brings stuff traversing the Calimshan Desert. You *can* but the game does not really give you a framework for that and, from what I hear, there isn't exactly a crowd playing that.

If the game was focusing more on trade and less on exploring dungeons you'd have more articulated skills like "dodge tariffs", "bargaining attack", and "improved smuggle", while the exploration of a dungeon could be solved with a single "Dungeoning" roll, because that would not be the focus.

![The shopkeeper welcomes adventurers to a magic-item shop]({{ '/assets/img/keep-dungeoning-magic-shop.png' | relative_url }})

So it's quite normal to go in detail for important things and getting more blurry the less what you are doing is important to the story.

But then: **why "low/moderate fights" still use the full combat rules?**
# Go lighter!
D&D balances encounters around "low/moderate fights", but that doesn't mean anything. If a low/moderate fight is something that the heroes should pass, let's not get into the full initiative-round-by-round fight, this isn't (or shouldn't) be required. And the higher the PCs' level, the longer this fight will get.

Let's make an example for a "moderate fight" for a level 14 party of six PCs under 2024 rules: we have an XP budget $B\in[17.400,29.400)$, a Fire Giant is $5.000$xp, so **4-5 fire giants** ($=20.000$xp) should be a barely moderate challenge. 648-810hp worth of enemies is *moderate*. It should be *routine.*

I'd play it this way:

> **Rule**
>
> The DM describes the situation and each PC rolls 2d20 to
> - roll an attack or spell attack
> - roll an ability check
> - PCs keep the d20 for the successful roll (nat20s count as 2 successful rolls)
> - DM keeps the d20s for the failed rolls
> - Each player then "spends" their d20 in defending their comrades, controlling the battlefield or defeating the enemies
> - The DM "spends" the d20s from failures to force a PC to invest a tier-appropriate resource or get higher damage, then rolls "some damage"
> - if successes were enough to defeat the opponents, that's done
> - if they weren't, the stakes get higher: roll for random encounters, add the new threat and let's roll initiative properly!
{: .callout .callout-example}

This streamlines some encounters that risk to fall flat, giving each a chance to shine with their PC's expertise, and moving the game on the great interesting fights. This isn't something that should cause the character to fail but there should be some opportunity to display both their greatness and their mishaps. And there is still a chance that everything goes horribly wrong!

This applies to every combat-not-interesting-enough-to-be-a-combat encounter too: need to kill a sentinel without raising the alarm? One double test, a bit of hp loss due to stress, tension or unavoidable minor injuries, and the game moves on the interesting parts.
# Tuning
From this general idea, it's time to tune the numbers. From the general idea I had to turn on actual questions to answer:
## I said "some damage": how much?
Starting with the good ol' *Improvising damage by severity and level* table, let's say d10s and compound them:
> **Rule**
>
> - T1 goes for 1d10 ≈ 5 damage
> - T2 adds 2d10 ⇒ 3d10 ≈ 16 damage
> - T3 adds 3d10 ⇒ 6d10 ≈ 33 damage
> - T4 adds 4d10 ⇒ 10d10 ≈ 55 damage
{: .callout .callout-example}

Which is… fine, I guess? Using some protective spells could lower the damage dice and some conditions or some monsters could increase it to d12s. This needs refinement.
## What's the DC of the d20 test?
Ah, well, I'd go for a 60-70% success on same tier, so success with a 7-9+/d20, a roughly optimized character should start with a 17 in the main attack stat, so
* lvl1: +5 (+3 ability, +2 proficiency)
* lvl5: +7 (+4 ability, +3 proficiency)
* lvl9: +8 (+4 ability, +4 proficiency)
* lvl13: +10 (+5 ability, +5 proficiency) (yes, I jumped lvl12, sue me)
* lvl17: +11 (+5 ability, +6 proficiency)
* lvl20: +12 (+6 ability for some reason, usually, +6 proficiency)

So a good distribution could be
> **Rule**
>
> DC = 12+2•Tier (14/16/18/20)
{: .callout .callout-example}

## How many successes are required?
I'd say 3, and a success from a higher tier party counts as 2. I'll start the test with that.
## Is there a fun way to track them?
Yes!

Write down each threat – may that be a single enemy or a group – and put 3 dots under the name. Add also some options like "defend", PCs can have fun ideas for other options too.

Each player can put their d20s from successes on the dots. If all dots are covered, the threat is gone. Each d20 on "defend" can be used to lower the damage die for one character, cumulative.

Lower tier threats require only two dots: successes from higher tier PCs count double but each d20 can stay on one option only.

This should satisfy the general idea of "this scene is kinda interesting but not enough that I need to invest 45mins on that".

Of course, context is king: if the lvl10 evoker **really** wants to wipe out the little horde of 30 goblins using his favourite fireball spell... ah, why am I still talking? You know what to do, ask the player to describe the mayhem and move on.

Time for some testing!

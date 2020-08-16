---
title: 'More Legion Prepatch User Interface Fun'
date: Thu, 04 Aug 2016 23:43:57 +0000
draft: false
tags: ['User Interface']
---

I've continued to work on my User Interface since my post last week. In this post I'll cover a few more addons and UI tips! Prior UI post: [Updating My Addons and User Interface for the Legion Prepatch](http://raidadvice.com/updating-my-addons-and-user-interface-for-the-legion-prepatch/). \[toc\]

Enemy Grid
==========

In [my last post](http://raidadvice.com/updating-my-addons-and-user-interface-for-the-legion-prepatch/), I listed dozens of addons I find useful and mentioned two addons I had heard of but not yet tried. [Enemy Grid](https://mods.curse.com/addons/wow/enemy-grid) is one of them and it is a game changer! It essentially allows you to have raid frames for your enemies. According to [several](http://us.battle.net/forums/en/wow/topic/17084929928) [forum](http://us.battle.net/forums/en/wow/topic/11224122596) [threads](http://us.battle.net/forums/en/wow/topic/8197740800), this had not been possible in the past, since non-boss units did not get a UnitID until they were targeted by you or a party member, and thus could not be displayed in a raid frame. Something may have changed in the Legion Prepatch, since Enemy Grid displays every enemy within a range you specify that appears on your screen. At least one other player [noticed how powerful this was and even wondered if it was allowed](http://us.battle.net/forums/en/wow/topic/20747665788) - no Blizzard response. Just like Healbot or Vuhdo, it has click-to-cast functionality built in, and just like raid frames, mouseover macros work if you hover over your desired target. This addon is especially useful for classes that like to cast damage over time effects on many targets - it's easy to keep track of 10 enemies if they are all in a tidy grid! Especially if you play a class that has to keep debuffs up on enemies, you owe it to yourself to try this addon.

Raven
=====

[Raven](https://mods.curse.com/addons/wow/raven) is the other addon I mentioned in my last post. Raven reminds me of a specialized Weakauras maker that is focused on tracking cooldowns, buffs, and debuffs. If Enemy Grid didn't exist, Raven would be my new go-to for tracking debuffs on enemies. I've experimented with Raven, and though I didn't notice an export feature, which is a bummer, it seems like a ready replacement for creating your own cooldown/buff/debuff monitors. It's a solid addon worth checking out if you want to experiment with another tracking tool.

AdiBags
=======

After my last post, a few folks referred me to the [AdiBags](https://mods.curse.com/addons/wow/adibags) addon. Thanks friends! If you haven't tried it, you should. It sorts your items into different types, separated by titles. Looking at the screenshots on the addon page is the best way to understand how it works. I will be sticking with this one for a while!

Raid Frame Repositioning
========================

I have tried several different positions for my raid frames, and nothing felt right. To the left or to the right obscured my view of the playing field too much, and at the very bottom of the screen diverted my attention too far down. I looked at a few other people's UI, and stumbled across Ashleah's great [UI Philosphy post](http://www.mistyteahouse.com/weakaura-hub/ui-philosophy/). Keeping the raid frames centered and below my character was great; I didn't think to raise them up and push the player and target frames to the left and right a bit to fit them. This setup is perfect! My focus lies near the center of the screen, and my vision of the encounter remains unimpaired. For purely DPSing putting the frames off in a corner may work best for some players. I think that the center-down position is extremely solid for healing, and a great fit overall for me. Again, the key component to setting up a good UI was trying different options and discovering what worked for me. I encourage you to do the same.

Key Bindings
============

I assume the reader agrees that [clicking spells is bad](http://us.battle.net/forums/en/wow/topic/1922564189). Once we've decided to use keybinds though, which should we use? Changing key bindings is an often-underappreciated component of user interface. In World of Warcraft, the defauly is W forward, QE to strafe, AD to turn, and S to backpedal, with most abilities on the number row. That's fine for learning the game, but we can do much better for raiding. Infrequently used cooldowns can go on the function keys, and situational abilities, like interrupts, stuns, and self-heals, can go around the QWEASD block. I have RTFGZXCVB all keybound. The way I do it, remaining somewhat consistent across characters, is: R to inteRrupt, T to sTun, F to Fly (blink or speed boost), G to Go (lesser movement ability), Z to heal myZelf, X for minor proteXtion, C for Complete protection (like bubble or Aspect of the Turtle), with V and B Varying Between characters. Alright, some of those letter associations may have been a tad forced. In addition, in a raid setting, [keyboard turning is sub-optimal](http://www.mmo-champion.com/threads/794325-What-is-keyboard-turning). It's quicker to turn with your mouse, and with a 1.5 second GCD, there's no reason you can't use your mouse to turn before doing any clicking you may need to do. I bound A and D to strafe, freeing up Q and E for abilities. I try to place instant abilities that I use frequently on those keys, so I can easily use them during movement. As a side note to the above: some players like a setup with movement on ESDF, with room for abilities both to the left and right of their hand. It's too hard to hit Shift/Alt/Control like that form my tastes, but if it works for them, great. We can also use Alt, Shift, and Control modifiers for certain binds. I use shift + Z, X, C, V for once-per-fight items like potions. I also use alt + 1-4, QE for less-used rotational abilities as needed. My way is surely not "the one true best way." However, changing the default settings is a big improvement over taking the standard keybinds. With one month left of Hellfire Citadel before Legion comes, now is a great time to try out different combinations and find what works well for you.

Macros
======

I wanted to mention macros, because they are so useful for improving your UI. I could easily dedicate a whole post about them - maybe I will at some point. For now, I'll mention briefly that macros with conditionals can really be a boon to your play. Here are three examples: `#showtooltip /cast [@mouseover,harm][] Moonfire` This macro casts Moonfire, an offensive damage over time spell, at the harmful unit my mouse is hovering over. If my mouse is not hovering over an enemy unit, Moonfire will cast on my target. `#showtooltip Displacer Beast /cast [stance:0/4]Displacer Beast /cast [stance:2]Moonkin Form` This macro casts Displacer Beast, a blink ability that transforms my character into a cat (stance 2), if I am in Moonkin Form (stance 4) or in no stance (stance 0). If I use the macro while in cat form, it will ignore the first line, and shift to Moonkin Form. `#showtooltip /use [nomod:alt] Aspect of the Turtle /cancelaura [mod:alt] Aspect of the Turtle` This macro casts Aspect of the Turtle, a defensive cooldown that prevents me from doing damage, so long as I am not holding alt. If I am holding alt, it will cancel the defensive buff early, allowing me to resume doing damage. For more ideas on what's possible, check [this thread on the official forums](http://us.battle.net/forums/en/wow/topic/16200990425) and this [compilation of macro conditionals on Wowpedia](http://wow.gamepedia.com/Macro_conditionals).

Conclusion
==========

A few people e-mailed asking to see my UI. I will continue to tinker with it, but here is a screenshot of my UI as it exists right now: [http://imgur.com/pVPsuvI](http://imgur.com/pVPsuvI). Note the Vuhdo raid frames positioning, the raid cooldowns and DPS meters to the sides of the screen, and DBM warnings, Enemy Grid, and my Raven cooldown/buff/debuff monitors near the center. I hope these posts have helped you think about your UI and how it can better serve you. Let me know if you have any questions or suggestions.
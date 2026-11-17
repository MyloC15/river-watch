# Our PRD

PRD = Product Requirements Document: **what** we're building and **for whom**. Finished by the end of **Week 3**. Written by us, by hand.

**Project:** Riverwatch · **By:** Mylo (@MyloC15) · **Track:** Built by Hand + Social Impact Tool

## 1. Who is it for? (persona)

Families and locals in **Uvita** who use the river to bathe, swim and play.

**Persona (made up, based on the people we're building for):**
- **Ana, 35**, a mum of two who lives in Uvita.
- Most weekends she takes her kids to a bathing spot on the river to cool off.
- The sky above the bathing spot is often clear, even when it is raining hard upstream. She has no way of knowing a flash flood is coming until the water is already rising around her.

## 2. Their problem, in their words
"I was lucky to survive the flash flood." (Cal)

The rivers around Uvita have flooded suddenly many times, and people have died in recent floods. A flash flood can come down the river with almost no warning, and people at the bathing spots have no way to know it's coming.

## 3. What it does, in one sentence (and why it fits)

**Riverwatch warns people at Uvita's river bathing spots when the water starts rising fast, so they can get out before a flash flood reaches them.**

Why it fits:
- **Built by Hand:** it's a real device we build ourselves: a water-level detector upstream, a radio link, and an alarm with a siren and lights downstream.
- **Social Impact Tool:** it protects people in our own community from a danger that has already killed people here.

## 4. The ONE thing that must work
If everything else broke, what has to work?

**When the water rises fast at the detector, the alarm downstream goes off.**

## 5. What happens, step by step
From opening it to finishing.

1. The detector is mounted above the river, upstream of a bathing spot, and measures how far away the water is, over and over.
2. The water starts rising fast because it's raining hard upstream.
3. The detector notices the level climbing fast, and checks several times in a row so one splash can't set it off.
4. The detector sends an alert over the radio to the receiver at the bathing spot.
5. The receiver switches on the siren and lights: amber for "watch", red for "danger".
6. Ana hears the siren and sees the red light, takes her kids out of the river, and goes to higher ground.
7. Before going to the river, anyone in Uvita can open the Riverwatch web page on their phone and see whether the bathing spot is safe (green), on watch (amber) or dangerous (red), and when it was last updated.

## 6. Look and feel
- **3 words:** helpful, safe, clear
- **Colours:** river blue for the page; green = safe, amber = watch, red = danger (the same colours as the alarm lights)
- **Works on a phone:** yes. The web page is made for phones first, so people can check it on their way to the river.

## 7. NOT building yet
At least 3 things we're leaving out.

1. Phone or text message alerts
2. A rain gauge upstream
3. More than one detector along the river (Demo Day uses one detector)

## User story
As a parent who takes my kids to bathe in the river at Uvita, I want to be warned when the river is rising fast, so that we can get out of the water before a flash flood reaches us.

## How we'll know it works
It works when someone at the bathing spot can hear the alarm and see the red light, and understand that they must get out of the river, without anyone explaining it to them.

## Must-have / also building
Must-haves are done by code freeze, Thu 10 Dec.

- **Must-have:** the detector senses a fast rise → the alert goes over the radio → the alarm sounds downstream.
- **Also building:** the web page with current conditions at the bathing spot, solar power, and a weatherproof case.

## AI tool
Claude

Checked by mentor: ______

# Baseline Analysis

## Cohesion and Coupling

Are terms frequently used in static analysis of object-oriented programs. **Cohesion** refers to _the degree to which the parts of a system (or sub-system) are related to each other and the system's purpose_. **Coupling** refers to _the degree to which sub-systems depend on each other_.

These are useful terms when analyzing games, specially in regards to modification of said games. We can think of games as sitting in somewhere in the axes of "coupling" and "cohesion":

D&D 5e, for example, is a system with _low coupling_, on average. Most sub-systems don't care about other sub-systems - Skills are standalone, with few exceptions, and what little social mechanics are there also don't care for anything else. Same goes for exploration. These particular sub-systems would also have _low cohesion_, as the game has no goal in particular - and thus, no purpose in particular.

Combat, on the other hand, would be a _highly coupled_ system. Most of everything on the character sheet relates to combat in some way, and most other sub-systems can tie into it in some way or another. Combat is also _highly cohesive_ - you sure do get to fight things!

P.S: I believe that 5e combat's high coupling, when contrasted with its parent system overall low coupling, is the reason 5e is often tauted as being "about combat", when it's really not about anything. Explicitly.

## Moxie

Moxie, in contrast, is a _loosely coupled_ - with few highly coupled sub-systems, such as **_spark_** and **_vantage_** - and _highly cohesive_ system. In "standard" game design terms, this implies a highly modular system designed around a "core", with solid but hardly modifiable modules.

This makes it all the more annoying for me, as my first order of business is to redesign spark and suspense.

## Remixing Moxie

Specifically, the plan is to have both spark and suspense be **diagetic** "meta"-currencies. Regular meta-currencies are player-initiated changes to the game state - **Players** _will_ a modification to the fiction and spend a point to do it. To make this dynamic diagetic is to imply that the reality of fiction itself is warping, for whatever reason, to abide by player or character goals.

The characters, by themselves, have nothing to do with "spending spark" - this is something the player does to give the character a boon, for no other reason than they are the protagonists of this story. To make spark (and its expenditure) diagetic implies that some _fundamental force of reality_ favors the player characters, and that this force operates by the _rules of stories_. Similarly, diagetic suspense implies that reality itself is building up "karma" of some sort, and is ready to lash out at the GMs discretion.

## Catastrophe

This change alone, while seemingly simple, has several cascading consequences:

- It imposes severe constraints on the fiction, as noted above;
- Diagetic suspense means that some suspense moves no longer make sense;
- Accumulated suspense means accumulated karma, which needs an escape valve;
- Story moves become hazy territory, while impact moves are fine;
- Every single spark expenditure in the game has to abide by these new rules of reality;
- Story points become redundant - players change the details of the fiction by spending spark;
- Vantage gets hit. What does it mean for something to be a stretch when reality can warp to the players needs?
- Why would you be able to warp reality _(earn spark)_ by getting into quarrels and the like?
- Repeat the above question for tangles, story arcs, etc.
- Why are some mechanics diagetic - spark and suspense - while stuff like story arcs are still in the game, as is?

Notice that almost every sub-system in Moxie is affected by this - this is because, while Moxie is overall a loosely coupled system, spark and suspense both have high coupling. Some stuff got out of this mess scot-free, though - stats, damage, character details. In short, to implement _diagetic spark and diagetic suspense_, I need to touch up almost every single Moxoe system. This is the catastrophe.

## Doom?

Not doom! These problems have solutions, and this is the rundown of it:

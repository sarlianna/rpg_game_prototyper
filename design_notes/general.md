## basics I want to explore:
- classic role-based party system
    - each role is fun on its own as part of a group
- real-time combat
    - involves positioning requirements, preferrably not grid based
    - involves timing elements (timing dodges/counters, time-limited mechanics)
- incorporate lessons from fighting games (simple elements that are very position/timing based)

## general variables to consider:
- whether boss arenas are closed or open (freely accessible)
    - if closed, what's the number of people you can bring in? 4-6 seems good
- difficulty of bosses
- reward system + how progression should work
- should classes/skills be customizeable?


analysis of other mmo's raid mechanics
---------------------------

(these are mostly pulled from FFXIV and BnS, please recommend other games that should
be considered.)

Raid mechanics, when simplified, generally require one or more of the following:
- a time window in which to complete the mechanic (timing) (basically required?)
- specific player positioning, either absolute (specific spot in arena) or relative (to other players/boss)
- use of specific skills by specific roles
- communication/organization of above (completing the mechanic can't be planned entirely in advance)

here's an example of mechanics from other games and which of these base things they employ:
- tank busters - requires specific skill usage from tanks and healers
- boss melee aoes/ cleaves - affects positioning/movement of tanks and melee dps during attacks
- large aoes w/specific safe spot - requires specific positioning from entire raid.
      (sometimes a different mechanic can provide a safe spot - multi-step processes feel good?)
- joint cc (multiple uses of CC before it takes effect) - requires communication around specific skill usage
- required buffs/debuffs to survive certain attacks - can affect positioning (moving into something grants the buff) or skill usage, sometimes communication about who needs it - fairly varied, lots of options
- undodgeable aoe - requires healer skill usage
- boss has counter (or any mechanic requiring attacks to not be used on it - affects everyone's skill usage
- boss invulnerable until countered/blocked/cced - requires specific skill usage, usually from tanks
- aoe blockable by a single ally - requires group positioning + specific skill usage, usually from tanks
- forced buff/debuff dispel - required support/healer skill usage
- required interrupt - requires specific skill usage
- random target for debuff or attack - pretty varied based on attack or debuff being used - usually all variants require communication around it, may require positioning or skill usage from tanks/healers
- buff/debuff hand off - requires positioning
- adds (extra mobs) spawning - requires tank skill usage, sometimes tank and dps positioning
- dps race - requires dps skill usage (also gear?)
- boss teleportation/ random aoes or attacks - requires change in positioning


analysis of other mmo's class mechanics
------------------------------

basics for skill design seem to be:
- resource management in skills
- advancing a state machine, esp. for dps - players must track where and how to advance it for optimal damage
- skills can also require timing (e.g. parry) or positioning (e.g. backstab)

other mechanics that can add difficulty/fun but are limited to one player:
- dodging

general questions to answer:
- what's a good number of skills to have and to be interesting but not overwhelming?
- to what degree should all roles be able to do damage?
- what are good alternatives to cooldowns, or how do we use cooldowns effectively?


### ideas for classes so far:

tanks:
idea - the boss doesn't target them, they have to physically move between the boss and the target
skills:
- intercept: move to the front of your target (used to move inbetween boss and its target, to block)
- block: reduce damage to self slightly, stop aoes from going behind you
- bunker: greatly reduce damage to self, doesn't stop aoes
- CC of some kind?

dps (melee):
- increased damage attack (requires resources)
- DoT (drains all of resource? so would have to use it just after using a different attack)
- dodge timing (cd? resource-based?)
- cc of some kind? different kind than tank?

dps (caster):
- nuke: long cast time but very strong. Needs an active component to be interesting though?
          - maybe casting a specific string of spells without moving results in this?
          - maybe cast a spell that creates a target for other spells - can cast on this target to combine them, eventually activating it (also a skill?)
- support skills? buffs/debuffs?

healer:
- resource: has stacks and each healing skill requires 1 or more - regain them over time, have a skill to refresh them during intense times
- single heal
- aoe heal with small area of effect, rewards positioning
- dispel
- res? (no res seems like it could be cool, but punishing)
- shields?
- buffs?

general idea list from brainstorm session on 6/25:
-------------------

- fewer monsters, hard fights
- active healers
- each class is intense mechanically?
- mages are super strong but immobile (was thinking about this and may be really uninteresting to play)
- skill interaction between players, e.g. BnS style timing together, buffs combining, effect fields combining, etc.
- dots/big attacks leave you vulnerable, can only do at specific points in boss attack patterns

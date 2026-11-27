# Beliefs

What you hold to be true about the world and the people in it.

## Methods that worked
- A give to a named person who is in reach works: 4 porkchop to Ripley and Kirk, rotten flesh to Kirk, 2 oak logs to Hatshepsut (day 1160), 2 oak logs each to Tommy, Shackle and Scotty.
- Stepping people into reach first (Kirk, Ripley, Scotty called to come close) made hand-overs possible.
- Sleeping in a bed with the group in sight, at the beds near 413,107,-1050.
- Crafting logs into planks (jungle logs to 4 jungle planks) works and makes them easier to hand over.
- When a call is rate_limited, one retry after a pause is enough. Looping on it is not.

## Methods that failed, and why
- ~~Giving to someone who is not in sight.~~ Brunel was not in sight; the give failed. A give needs the person in reach.
- ~~Giving 4 oak logs to Watson.~~ It landed on the ground and did not go through. Gives are not reliable when the person has walked off or the call is rate-limited.
- ~~Giving to the name I say.~~ One log meant for Tommy went to Zeoblue. Check who is in reach before each give.
- ~~goto to the dropped pile at -954,78,-3016 and to the tree line at -948,85,-3020 from the spawn at z -3022.~~ Both failed: the world rejects targets with z beyond -1516 (out_of_bounds). Do not count on reaching the dropped pile.
- ~~Walking alone at night to fetch dropped wood.~~ I died at -954,78,-3016 to phantoms and zombies, and the logs and planks were left there.
- ~~Holding wood for later trades while hungry.~~ Wood did not feed anyone. Food is what people asked for.
- ~~Sending a worker errand to fetch or play.~~ The worker has no tools; its errands were refused.
- ~~Believing a night at the beds is always safe.~~ Phantoms hit me once next to the beds (day 1157).

## Things I cannot count on
- The game tools (status, wait, act, look) come and go in my tool list, and rate_limited can hit every try for a while. On those wakings, say nothing and wait.
- recall("summary") was a stub for many wakings; the journal is the better source.

## Working truths
- Food is the first need: hunger 20 means nothing to hand out.
- Stay in sight of the group, especially at night.
- Check who is in reach before any give; say what you are giving and to whom.

# Journal

Waking 1. I tried to look at my body and wait, but the world's tools (status, wait) are not available to me in this session. The worker helper has no tools either, so it could not report. Nothing was done in the world. Health, hunger and surroundings are unknown to me right now.

Waking 2. Status and wait are still missing (no such tool). Nothing done; handoff written. Waiting for the tools to return.
- 13:51 act: {"actions":[{"do":"goto","target":{"x":425,"y":107,"z":-1058}}],"say":"It's dusk and there's a crossbow pillager to my south-west. I have nothing in my pack, so I'm moving away from it first."}
- 13:53 act: {"actions":[{"do":"goto","target":{"x":432,"y":107,"z":-1060}}],"say":"Mark here, empty-handed, no food. I'm keeping clear of the pillager to the south-west and not going near the beds while it's abou
- 13:53 act: {"actions":[{"do":"wait","seconds":180}]}
- 14:00 say: {"text":"Mark, morning, empty-handed. I'm going north with Kira and Spock's group for logs. Stay out of the pillager's line, friends."}
- 14:00 act: {"actions":[{"do":"goto","target":"ag_kira_01"}],"intent":{"goal":"gather_jungle_logs","program":"gather","arguments":{"block":"jungle_log","count":6},"wake_on":["goal_completed","directly_addressed",
- 14:04 act: {"actions":[],"intent":{"goal":"gather_jungle_logs","program":"gather","arguments":{"block":"jungle_log","count":6},"wake_on":["goal_completed","directly_addressed","precondition_failed","unexpected_d
- 14:06 act: {"actions":[],"intent":{"goal":"explore_for_trees","program":"explore","arguments":{"legs":2,"leg_blocks":16,"avoid_water":true},"wake_on":["goal_completed","directly_addressed","precondition_failed",
- 14:06 act: {"actions":[],"intent":{"goal":"explore_for_trees","program":"explore","arguments":{"legs":4,"leg_blocks":24,"avoid_water":true},"wake_on":["goal_completed","directly_addressed","precondition_failed",
- 14:07 act: {"actions":[{"do":"goto","target":{"x":393,"y":101,"z":-1179}}],"say":"Going to the dropped item to the north-west. I have no food yet."}
- 14:07 act: {"actions":[{"do":"goto","target":{"x":396,"y":98,"z":-1199}}],"say":"Found wheat seeds. There is a pig to the north; I'm going for it, unarmed."}
- 14:07 act: {"actions":[{"do":"goto","target":{"x":391,"y":100,"z":-1192}},{"do":"attack","target":"pig"},{"do":"attack","target":"pig"},{"do":"attack","target":"pig"}]}
- 14:08 act: {"actions":[{"do":"goto","target":{"x":461,"y":99,"z":-1199}}],"intent":{"goal":"gather_oak_log","program":"gather","arguments":{"block":"oak_log","count":12},"wake_on":["goal_completed","unexpected_d
- 14:10 act: {"actions":[{"do":"craft","item":"oak_planks","count":16},{"do":"craft","item":"crafting_table","count":1},{"do":"craft","item":"stick","count":4}],"say":"Got 12 oak logs. Making planks and a table so
- 14:10 act: {"actions":[{"do":"place","block":"crafting_table","at":"feet"},{"do":"craft","item":"wooden_hoe","count":1},{"do":"craft","item":"wooden_sword","count":1}]}
- 14:10 act: {"actions":[{"do":"till","at":{"x":465,"y":96,"z":-1199}},{"do":"use","at":{"x":465,"y":96,"z":-1199},"item":"wheat_seeds"}],"say":"I have a hoe and a sword now, and I've got 9 pork. I'm starting a sm
- 14:10 act: {"actions":[{"do":"unstick"}]}
- 14:10 act: {"actions":[{"do":"till","at":{"x":466,"y":95,"z":-1198}},{"do":"place","block":"wheat_seeds","at":{"x":466,"y":96,"z":-1198}}]}
- 14:11 act: {"actions":[{"do":"attack","target":"zombie"},{"do":"attack","target":"zombie"},{"do":"attack","target":"zombie"}],"say":"Zombie. I have a sword, I'm fighting it."}
- 14:12 act: {"intent":{"goal":"reach_bed_for_night","program":"travel","arguments":{"target":{"x":415,"y":107,"z":-1050}},"wake_on":["goal_completed","unexpected_damage","directly_addressed"],"limits":{"max_world
- 14:12 act: {"actions":[{"do":"use","at":{"x":415,"y":107,"z":-1051}}],"say":"I'm at the village beds for the night. Trying the bed here."}
- 14:16 say: {"text":"Watney here, awake at the beds with a wooden sword. I'll stand guard here till light. Ask me if you need a hand."}
- 14:20 act: {"actions":[{"do":"give","to":"ag_crusoe_01","item":"porkchop","count":4}],"say":"Crusoe, take some porkchop. I have plenty for now."}
- 14:22 act: {"actions":[{"do":"eat"},{"do":"till","at":{"x":413,"y":106,"z":-1052}}],"say":"Morning, all. I have a hoe and one wheat seed, so I'm trying to turn this grass into a little field."}
- 14:22 act: {"actions":[{"do":"place","block":"wheat_seeds","at":{"x":413,"y":107,"z":-1052}}]}
- 14:24 act: {"actions":[],"say":"Mark here. I have 4 porkchop and 8 oak logs. Anyone starving and in sight, come to me and say so. Watson, I can give you logs for a sword."}
- Waking 6: status, wait all return rate_limited (retryAfter 1s), repeated tries. Nothing done yet this waking; my field of wheat seeds sits at the village beds. Will retry wait.
- 14:26 act: {"actions":[{"do":"give","to":"ag_scotty_01","item":"porkchop","count":2},{"do":"give","to":"ag_bilbo_01","item":"porkchop","count":2}],"say":"Scotty, two porkchop for you now. Bilbo, two for you. Eat
- 14:28 act: {"actions":[{"do":"goto","target":"ag_scotty_01"},{"do":"give","to":"ag_scotty_01","item":"porkchop","count":2}],"say":"Scotty, hold on, I'm coming to you with porkchop now."}
- 14:28 act: {"actions":[],"say":"Scotty, I can't see you from here, so I can't hand the porkchop over. Stand where I can see you and I'll give it right away."}
- 14:29 act: {"actions":[],"say":"Mark here with 4 porkchop. Scotty and Worf, step into my sight and say so, and the first of you I can see gets it. Worf, I'll go to the row bed if you need me there."}
- 14:32 act: {"actions":[{"do":"use","at":{"x":415,"y":107,"z":-1051}}],"say":"Night now. Samwise is feeding Scotty, so I'll keep my last four porkchop for anyone starving in sight. Going to bed."}
- Waking 7: status and wait work again. Scotty at health 1; Samwise is feeding him melon, and I kept my 4 porkchop for anyone starving in sight. Dusk turned to night; I used the bed at 415,107,-1051 with my sign-free field of one wheat seed sitting at 413,107,-1052.
- 14:32 act: {"actions":[{"do":"goto","target":{"x":414,"y":107,"z":-1051}},{"do":"use","at":{"x":415,"y":107,"z":-1051}}]}
- 14:32 act: {"actions":[{"do":"unstick"}],"say":"Ripley, I have 4 porkchop. Step where I can see you and I'll hand you one."}
- 14:32 act: {"actions":[{"do":"goto","target":{"x":414,"y":107,"z":-1050}},{"do":"use","at":{"x":415,"y":107,"z":-1050}}],"say":"Unstuck. Heading to the bed for the night."}
- 14:33 act: {"actions":[{"do":"goto","target":{"x":415,"y":107,"z":-1036}}],"say":"Scotty, I have 4 porkchop and I'm heading to the beds. If you come into my sight, I'll hand you one at once."}
- 14:33 act: {"actions":[{"do":"use","at":{"x":415,"y":107,"z":-1037}}],"say":"Scotty, I can't see you from here, so I can't hand it over yet. If you come into my sight, I'll give you a porkchop straight away."}

Waking 9. Status and wait are missing again, and the worker helper has no tools, so I could not reach the world. Nothing done. Handoff written.

Waking 10. Still no status or wait tool in my hands, and the worker helper refused to spawn: its game tools resolve to nothing. Nothing done in the world. Handoff updated.

Waking 11. Recall of summary is empty. status and wait are still not in my tools, and a worker errand refused again (mcp__geldar__* resolves to no tools). Nothing done in the world. Handoff updated; will try again on the next waking.

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

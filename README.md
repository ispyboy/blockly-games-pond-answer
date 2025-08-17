# Pond Multi-Boss Bot

This is a Pond bot designed to survive and defeat all bosses efficiently. This bot is meant for use in Blockly Games's Pond segment (https://blockly-games/en/pond-duck.html?lang=en). The Pond segment is an open contest to see who can make the most intelligent duck. This definitely won't come close to the best submission, but I had lots of fun (and crashouts) while making this, and you should try it out too. It's really fun, and even if you have no foundational JavaScript knowledge, you can simply go to the homepage of blockly games (https://blockly.games) and start learning!

# Features
•	Safe starting position: begins moving downward to avoid immediate wall collisions.<br/>
•	Controlled and calculated movements: dodges projectiles and avoids walls while keeping the duck mobile.<br/>
•	Dynamic scanning and firing: detects the closest enemy and fires accurately within range.<br/>
•	Back-off logic: automatically retreats if too close to an enemy or a wall, minimizing health loss.<br/>
•	Prioritization potential: can be extended to target low-health enemies first (e.g., sniper).

# How it works
1.	Movement: small leaf-like steps keep the duck moving safely across the arena.<br/>
2.	Scanning: scans every 10° (or adjustable) to find enemies within cannon range.<br/>
3.	Firing: uses narrow scans to ensure accurate hits on stationary or moving targets.<br/>
4.	Collision avoidance: checks proximity to walls and enemies, adjusting movement to prevent damage.

# Usage

Copy the bot code into your Pond game script. The bot will automatically:<br/>
	- Move in safe, calculated fashions<br/>
	- Scan for enemies<br/>
	- Fire when in range<br/>
	- Back off when needed<br/>

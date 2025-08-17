# Pond Multi-Boss Bot

This is a Pond AI bot designed to survive and defeat all bosses efficiently.

# Features
•	Safe starting position: begins moving downward to avoid immediate wall collisions.<br/>
•	Controlled circular movement: dodges projectiles and avoids walls while keeping the duck mobile.<br/>
•	Dynamic scanning and firing: detects the closest enemy and fires accurately within range.<br/>
•	Back-off logic: automatically retreats if too close to an enemy or a wall, minimizing health loss.<br/>
•	Prioritization potential: can be extended to target low-health enemies first (e.g., bomber).

# How it works
1.	Movement: small leaf-like steps keep the duck moving safely across the arena.<br/>
2.	Scanning: scans every 10° (or adjustable) to find enemies within cannon range.<br/>
3.	Firing: uses narrow scans to ensure accurate hits on stationary or moving targets.<br/>
4.	Collision avoidance: checks proximity to walls and enemies, adjusting movement to prevent damage.

# Usage

Copy the bot code into your Pond game script. The bot will automatically:<br/>
	- Move in safe leaf-like arcs<br/>
	- Scan for enemies<br/>
	- Fire when in range<br/>
	- Back off when needed<br/>

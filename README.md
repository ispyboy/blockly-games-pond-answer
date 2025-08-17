# blockly-games-pond-answer
This is a bot coded with JavaScript for the "Pond" segment of  Blockly Games (https://blockly.games). It moves in a leaf-like pattern and kills all three bosses with a high chance of surviving with more than 50% health! 

# Pond Multi-Boss Bot

This is a Pond AI bot designed to survive and defeat multiple bosses efficiently.

# Features
	•	Safe starting position: begins moving downward to avoid immediate wall collisions.
	•	Controlled circular movement: dodges projectiles and avoids walls while keeping the duck mobile.
	•	Dynamic scanning and firing: detects the closest enemy and fires accurately within range.
	•	Back-off logic: automatically retreats if too close to an enemy or a wall, minimizing health loss.
	•	Prioritization potential: can be extended to target low-health enemies first (e.g., bomber).

# How it works
	1.	Movement: small circle steps keep the duck moving safely across the arena.
	2.	Scanning: scans every 10° (or adjustable) to find enemies within cannon range.
	3.	Firing: uses narrow scans to ensure accurate hits on stationary or moving targets.
	4.	Collision avoidance: checks proximity to walls and enemies, adjusting movement to prevent damage.

# Usage

# Copy the bot code into your Pond game script. The bot will automatically:
	•	Move in safe circular patterns
	•	Scan for enemies
	•	Fire when in range
	•	Back off when needed

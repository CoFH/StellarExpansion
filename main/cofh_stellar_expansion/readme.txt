CoFH - Stellar Expansion
Author: King Lemming

Hey there! So the purpose of Stellar Expansion is to add onto the vanilla
Stellaris experience while not introducing things which are too terribly
imbalanced or out of place.

So for now, just Buildings and Technologies. Some of the techs are unlocked
via Special Projects, but the mod is otherwise event-free.

For features which change the game in a large way, I'll be putting those into
their own separate modules.

If you read that, thanks. If you just wanted a list of everything in the mod,
then here you go:

################################################################################
# Buildings
################################################################################

General
--------------------------------------------------------------------------------
Diplomatic Hub:
	Planet-Unique
	Build:
		720 Days
		400 Minerals
		25 Influence
		*15 Population on Planet
		*Planetary Capital (or better)

	Requires:
		3 Energy

	Produces:
		1 Influence

	Planet Modifier:
		+15% Ethics Divergence [1]

	Empire Modifier:
		+100 Maximum Influence

	Prerequisites:
		Tech - Galactic Prominence

Robot Maintenance Facility:
	Planet-Unique
	Build:
		720 Days
		350 Minerals

	Planet Modifier:
		+10% Robot Production Output

	Prerequisites:
		Tech - Robotic Workers
		**AI cannot be outlawed.

Energy
--------------------------------------------------------------------------------
Capacitor Bank I:
	Build:
		210 Days
		60 Minerals

	Empire Modifier:
		+500 Maximum Energy

	Adjacency Bonus:
		+1 Energy

Capacitor Bank II:
	Build:
		180 Days
		90 Minerals
		*Planetary Administration (or better)

	Empire Modifier:
		+750 Maximum Energy

	Adjacency Bonus:
		+1 Energy

	Prerequisites:
		Tech - Global Energy Management

Capacitor Bank III:
	Build:
		180 Days
		120 Minerals
		*Planetary Capital (or better)

	Empire Modifier:
		+1000 Maximum Energy

	Adjacency Bonus:
		+2 Energy

	Prerequisites:
		Tech - Planetary Power Grid

Ethos
--------------------------------------------------------------------------------
Bureau of Vigilance:
	Empire-Unique
	Build:
		720 Days
		450 Minerals
		35 Influence
		*Empire-Capital Complex (Capital only)

	Requires:
		6 Energy

	Empire Modifier:
		+50% Rivalry Influence Gain

	Prerequisites:
		Tech - Eternal Vigilance
		*Only available to Xenophobes and Fanatic Xenophobes.

Concord Assembly:
	Empire-Unique
	Build:
		720 Days
		450 Minerals
		30 Influence
		*Planetary Capital (or better)

	Empire Modifier:
		-20% Population Growth Time

	Prerequisites:
		Tech - Galactic Concordance
		*Only available to Pacifists and Fanatic Pacifists.

Frontier Institute:
	Empire-Unique
	Build:
		720 Days
		550 Minerals
		45 Influence
		*Planetary Capital (or better)

	Requires:
		8 Energy

	Produces:
		2 Physics Research
		8 Society Research
		2 Engineering Research

	Empire Modifier:
		+10% Society Research Speed

	Prerequisites:
		Tech - The Final Frontier
		*Only available to Xenophiles and Fanatic Xenophiles.

Ministry of Intelligence:
	Empire-Unique
	Build:
		720 Days
		400 Minerals
		40 Influence
		*Empire-Capital Complex (Capital only)

	Requires:
		5 Energy

	Empire Modifier:
		+2 Max Rivalries

	Prerequisites:
		Tech - Central Intelligence
		*Only available to Militarists and Fanatic Militarists.

Monument to Creation:
	Empire-Unique
	Build:
		720 Days
		400 Minerals
		35 Influence
		*Planetary Capital (or better)

	Empire Modifier:
		+10% Happiness

	Prerequisites:
		Tech - Cosmic Reflection
		*Only available to Spiritualists and Fanatic Spiritualists.

################################################################################
# Technologies
################################################################################

Engineering
--------------------------------------------------------------------------------
Adaptive Fleet Construction:
	Voidcraft
	Repeatable (5x)

	Prerequisites:
		Tech - Supersolid Materials

	Effects:
		-5% Ship Cost
		-5% Ship Upgrade Cost

Adaptive Offworld Construction:
	Voidcraft
	Repeatable (5x)

	Prerequisites:
		Tech - Deep Space Stations

	Effects:
		-5% Spaceport Module Cost
		-5% Station Build Cost

Applied Fleet Logistics:
	Voidcraft
	Repeatable (5x)

	Prerequisites:
		Tech - Supersolid Materials

	Effects:
		+10% Ship Repair Speed
		-5% Ship Repair Cost
		-5% Ship Upkeep

Protocol Droids:
	Industry

	Prerequisites:
		Tech - Droid Workers
		Tech - Sentient AI

	Effects:
		+1 Influence
		+10% Trade Attractiveness
		+10% Trust Growth

Shipyard Assembly Coordination:
	Voidcraft
	Repeatable (5x)

	Prerequisites:
		Tech - Supersolid Materials

	Effects:
		+10% Ship Build Speed

Physics
--------------------------------------------------------------------------------
Deep Scanning Algorithms:
	Computation

	Prerequisites:
		Tech - Administrative AI

	Effects:
		+25% Anomaly Discovery Chance

Harmonic Replenishment:
	Field Manipulation
	Repeatable (5x)

	Prerequisites:
		Shield Capacitors

	Effects:
		+5% Shield Regeneration

Positronic Algorithms:
	Computation
	Repeatable (5x)

	Prerequisites:
		Tech - Sentient AI

	Effects:
		+1% Research Speed
		+3% Robot Production Output

Society
--------------------------------------------------------------------------------
Adaptive Training Regimen:
	Military Theory
	Repeatable (5x)

	Prerequisites:
		Tech - Combat Training

	Effects:
		+10% Army Build Speed

Applied Military Logistics:
	Military Theory
	Repeatable (5x)

	Prerequisites:
		Tech - Centralized Command

	Effects:
		-5% Army Upkeep

Battlefield Leadership:
	Military Theory

	Prerequisites:
		Tech - Centralized Command

	Effects:
		+15% Army Morale

Galactic Prominence:
	Statecraft

	Prerequisites:
		Tech - Galactic Administration

	Effects:
		+1 Influence
		Unlocks - Building: Diplomatic Hub

Intensive Ecological Engineering:
	New Worlds
	Repeatable (5x)

	Prerequisites:
		Tech - Terrestrial Sculpting

	Effects:
		-2% Terraforming Cost
		-5% Clear Blocker Cost
		-5% Clear Blocker Time

Procurement Optimization:
	Military Theory
	Repeatable (5x)

	Prerequisites:
		Tech - Centralized Command

	Effects:
		-5% Army Cost

Psi Diplomatic Corps:
	Psionics

	Prerequisites:
		Tech - Psionic Theory

	Effects:
		+2 Influence
		+20% Trade Attractiveness
		+20% Trust Growth

Xeno Confidence:
	Statecraft

	Prerequisites:
		Tech - Xeno Diplomacy

	Effects:
		+15% Trust Growth

Xeno Negotiation:
	Statecraft

	Prerequisites:
		Tech - Xeno Diplomacy

	Effects:
		+15% Trade Attractiveness

Society (Building Technologies)
--------------------------------------------------------------------------------
Central Intelligence:
	Statecraft, Rare

	Prerequisites:
		Tech - Galactic Administration
		Ethos - Militarist or Fanatic Militarist

	Effects:
		Unlocks - Building: Ministry of Intelligence

Cosmic Reflection:
	Statecraft, Rare

	Prerequisites:
		Tech - Colonial Centralization
		Ethos - Spiritualist or Fanatic Spiritualist

	Effects:
		Unlocks - Building: Monument to Creation

Eternal Vigilance:
	Statecraft, Rare

	Prerequisites:
		Tech - Galactic Administration
		Ethos - Xenophobe or Fanatic Xenophobe

	Effects:
		Unlocks - Building: Bureau of Vigilance

Galactic Concordance:
	Statecraft, Rare

	Prerequisites:
		Tech - Colonial Centralization
		Ethos - Pacifist or Fanatic Pacifist

	Effects:
		Unlocks - Building: Concord Assembly

The Final Frontier:
	Statecraft, Rare

	Prerequisites:
		Tech - Colonial Centralization
		Ethos - Materialist or Fanatic Materialist

	Effects:
		Unlocks - Building: Frontier Science Institute

Crisis Countermeasures[2]
--------------------------------------------------------------------------------
Machine Consciousness Countermeasures:
	Engineering - Voidcraft

	Effects:
		+15% Damage to Machine Consciousness Vessels

Extradimensional Invader Countermeasures:
	Physics - Particles

	Effects:
		+15% Damage to Extradimensional Invaders

Prethoryn Sourge Countermeasures:
	Society - Biology

	Effects:
		+15% Damage to Prethoryn Creatures

Fallen Empire Countermeasures:
	Engineering - Voidcraft

	Effects:
		+15% Damage to Fallen Empire Ships

################################################################################
# Notes
################################################################################

[1]	This is intentional and not a bug. When you mark a world as prominent,
	the local ethos may begin to become more relevant and disparate in the
	context of your empire.

[2] These technologies are unlocked via Special Projects which appear after the
	crisis fleets have been engaged in battle with your forces. Once unlocked,
	the technologies can be researched normally and/or completed by destroying
	crisis ships in combat.

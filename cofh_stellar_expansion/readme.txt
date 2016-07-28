CoFH - Stellar Expansion
Author: King Lemming

Hey there! So the purpose of Stellar Expansion is to add onto the vanilla
Stellaris experience while not introducing things which are too terribly
imbalanced or out of place.

So for now, just Buildings and Technologies, although Events are sure to come.

For features which change the game in a large way, I'll be putting those into
their own separate modules.

If you read that, thanks. If you just wanted a list of everything in the mod,
then here you go:

################################################################################
# Buildings
################################################################################

General
--------------------------------------------------------------------------------
Climate Moderation Reactor:
	Planet-Unique
	Build:
		360 Days
		350 Minerals

	Requires:
		1 Terraforming Gas
		1 Terraforming Liquid

	Planet Modifier:
		+20% Habitability

	Prerequisites:
		Tech - Atmospheric Manipulation

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
		**A.I. cannot be outlawed.

Xeno Nutriment Factory:
	Planet-Unique
	Build:
		360 Days
		300 Minerals
		10 Influence

	Requires:
		1 Alien Pets
		2 Energy

	Produces:
		10 Food

	Planet Modifier:
		+10% Food Output

	Prerequisites:
		Tech - Xeno Nutriment Factory
		**Not available if Xenophile or Fanatic Xenophile.

Energy
--------------------------------------------------------------------------------
Capacitor Bank I:
	Build:
		210 Days
		60 Minerals

	Empire Modifier:
		+500 Maximum Energy

Capacitor Bank II:
	Build:
		180 Days
		90 Minerals
		*Planetary Administration (or better)

	Empire Modifier:
		+750 Maximum Energy

	Prerequisites:
		Tech - Global Energy Management

Capacitor Bank III:
	Build:
		180 Days
		120 Minerals
		*Planetary Capital (or better)

	Empire Modifier:
		+1000 Maximum Energy

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
		+2 Max Rivalries

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
		+50% Rivalry Influence Gain

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

Strategic Resource
--------------------------------------------------------------------------------
Neutronium Manufactory:
	Empire-Unique
	Build:
		360 Days
		350 Minerals
		*Planetary Administration (or better)

	Requires:
		1 Neutronium Ore
		2 Energy

	Planet Modifier:
		+10% Energy Production

	Empire Modifier:
		+10% Energy Production
		+25% Category: Materials Research Speed

Satramene Infusion Plant:
	Empire-Unique
	Build:
		360 Days
		350 Minerals
		*Planetary Administration (or better)

	Requires:
		1 Satramene Gas
		2 Energy

	Planet Modifier:
		-5% Xenophobia

	Empire Modifier:
		-5% Xenophobia
		+10% Trade Attractiveness
		+10% Trust Growth

Zro Diffusion Plant:
	Empire-Unique
	Build:
		360 Days
		350 Minerals
		*Planetary Administration (or better)

	Requires:
		1 Zro
		2 Energy

	Planet Modifier:
		+25% Fortification Strength
		+50% Sensor Range

	Empire Modifier:
		+25% Fortification Strength
		+50% Sensor Range
		+25% Category: Psionics Research Speed

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
		+5% Ship Repair Speed
		-5% Ship Repair Cost
		-5% Ship Upkeep

Protocol Droids:
	Industry

	Prerequisites:
		Tech - Droid Workers
		Tech - Sentient A.I.

	Effects:
		+1 Influence
		+10% Trade Attractiveness
		+10% Trust Growth

Shipyard Assembly Coordination:
	Voidcraft
	Repeatable (10x)

	Prerequisites:
		Tech - Supersolid Materials

	Effects:
		+5% Ship Build Speed

Physics
--------------------------------------------------------------------------------
Deep Scanning Algorithms:
	Computation

	Prerequisites:
		Tech - Administrative A.I.

	Effects:
		+25% Anomaly Generation Chance on Survey

Hypernavigation Optimization:
	Particles
	Repeatable (5x)

	Prerequisites:
		Tech - Hyperlane Breach Points

	Effects:
		-5% Jump Charge Time

Warp Field Optimization:
	Field Manipulation
	Repeatable (5x)

	Prerequisites:
		Tech - Warp Field Stabilizers

	Effects:
		+20% Warp Range
		+20% Warp Speed
		-10% Jump Cooldown

Society
--------------------------------------------------------------------------------
Adaptive Training Regimen:
	Military Theory
	Repeatable (10x)

	Prerequisites:
		Tech - Combat Training

	Effects:
		+5% Army Build Speed

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
		-5% Terraforming Cost
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

Xeno Nutriment Factory:
	Biology

	Prerequisites:
		Tech - Xenology
		Ethos: NOT Xenophile or Fanatic Xenophile

	Effects:
		Unlocks - Building: Xeno Nutriment Factory

################################################################################
# Notes
################################################################################

[1]	This is intentional and not a bug. When you mark a world as prominent,
	the local ethos may begin to become more relevant and disparate in the
	context of your empire.

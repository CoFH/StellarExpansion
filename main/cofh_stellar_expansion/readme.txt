CoFH - Stellar Expansion
Author: King Lemming

Hey there! So the purpose of Stellar Expansion is to add onto the vanilla
Stellaris experience while not introducing things which are too terribly
imbalanced or out of place.

So for now, just Buildings, Spaceport Modules, and Technologies. Some of the
techs are unlocked via Special Projects, but the mod is otherwise event-free.

For features which change the game in a large way, I'll be putting those into
their own separate modules.

If you read that, thanks. If you just wanted a list of everything in the mod,
then here you go:

################################################################################
# Buildings
################################################################################

General
--------------------------------------------------------------------------------
Grand Retail Center:
	Planet-Unique
	Build:
		360 Days
		200 Minerals

	Requires:
		2 Energy

	Produces:
		2 Unity (if Egalitarian)
		2 Unity (with Functional Architecture Civic)
		1 Engineering Research (with Functional Architecture Civic)

	Planet Modifier:
		-5% Building Cost
		-15% Consumer Goods Cost

	Prerequisites:
		Tech - Colonial Centralization


Holosseum:
Planet-Unique
	Build:
		360 Days
		200 Minerals

	Requires:
		3 Energy

	Produces:
		2 Unity (if Militarist)
		2 Unity (with Warrior Culture Civic)
		1 Society Research (with Warrior Culture Civic)

	Planet Modifier:
		+10% Army Damage
		+5% Happiness
		+5% Government Ethics Attraction

	Prerequisites:
		Tech - Combat Training

Robot Maintenance Facility:
	Planet-Unique
	Build:
		540 Days
		350 Minerals

	Requires:
		1 Energy

	Produces:
		2 Minerals
		1 Engineering Research

	Planet Modifier:
		+10% Robot Production Output

	Prerequisites:
		Tech - Robotic Workers
		**AI cannot be outlawed.

Xeno Nutriment Factory:
	Planet-Unique
	Build:
		360 Days
		200 Minerals

	Requires:
		1 Energy

	Produces:
		4 Food
		2 Society Research

	Planet Modifier:
		+10% Food
		**+15% with Livestock or Processed Pop on planet

	Prerequisites:
		Tech - Alien Life Studies

Energy
--------------------------------------------------------------------------------
Capacitor Bank I:
	Build:
		210 Days
		60 Minerals

	Empire Modifier:
		+1000 Maximum Energy

	Adjacency Bonus:
		+1 Energy

Capacitor Bank II:
	Build:
		180 Days
		90 Minerals
		*Planetary Administration (or better)

	Empire Modifier:
		+1500 Maximum Energy

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
		+2000 Maximum Energy

	Adjacency Bonus:
		+1 Energy

	Prerequisites:
		Tech - Planetary Power Grid

Food
--------------------------------------------------------------------------------
Agri-Repository I:
	Build:
		210 Days
		60 Minerals

	Empire Modifier:
		+50 Stored Food

	Adjacency Bonus:
		+1 Food

Agri-Repository II:
	Build:
		180 Days
		90 Minerals
		*Planetary Administration (or better)

	Planet Modifier:
		-5% Growth Time

	Empire Modifier:
		+75 Stored Food

	Adjacency Bonus:
		+1 Food

	Prerequisites:
		Tech - Eco Simulation

Agri-Repository III:
	Build:
		180 Days
		120 Minerals
		*Planetary Capital (or better)

	Planet Modifier:
		-10% Growth Time

	Empire Modifier:
		+100 Stored Food

	Adjacency Bonus:
		+1 Food

	Prerequisites:
		Tech - Gene Crops

Minerals
--------------------------------------------------------------------------------
Betharian Mining Network:
	Build:
		180 Days
		120 Minerals
		*Planetary Administration (or better)

	Requires:
		2 Energy

	Produces:
		10 Minerals

	Prerequisites:
		Tech - Betharian Refining

Influence
--------------------------------------------------------------------------------
Diplomatic Embassy:
	Planet-Unique
	Build:
		720 Days
		300 Minerals
		*5 Population on Planet
		*Planetary Capital (or better)

	Requires:
		3 Energy
		1 Diplomatic Corps [1]

	Produces:
		1 Influence
		2 Unity (with The Federation tradition)

	Planet Modifier:
		+15% Border Extrusion

	Empire Modifier:
		+100 Maximum Influence
		+5% Trust Growth

	Prerequisites:
		Tech - Galactic Prominence

Diplomatic Hub:
	Empire-Unique
	Build:
		720 Days
		400 Minerals
		*10 Population on Planet
		*Planetary Capital (or better)

	Requires:
		5 Energy

	Produces:
		2 Influence
		3 Diplomatic Arm
		4 Unity (with The Federation Tradition)

	Planet Modifier:
		+30% Border Extrusion

	Empire Modifier:
		+200 Maximum Influence
		+10% Trust Growth

	Prerequisites:
		Tech - Galactic Prominence

################################################################################
# Spaceport Modules
################################################################################

Atmospheric Manipulator:
	Build:
		360 Days
		200 Minerals
		*Level 2 Spaceport (or better)

	Requires:
		2 Energy

	Planet Modifier:
		+10% Habitability on Planet

	Prerequisites:
		Tech - Atmospheric Manipulation

Mining Terminal:
	Build:
		180 Days
		100 Minerals
		*Level 1 Spaceport (or better)

	Requires:
		1 Energy

	Produces:
		+3 Minerals

	Planet Modifier:
		+10% Minerals on Planet

	Prerequisites:
		Tech - Orbital Mineral Processing

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
		-5% Ship Upkeep

Inertial Compensators:
	Voidcraft
	Repeatable (5x)

	Prerequisites:
		Tech - Carrier Operations

	Effects:
		+20% Strike Craft Speed

Orbital Mineral Processing:
	Industry

	Prerequisites:
		Tech - Space Construction

	Effects:
		Unlocks Spaceport Module - Mining Terminal

Protocol Droids:
	Industry

	Prerequisites:
		Tech - Droid Workers
		Tech - Sentient AI

	Effects:
		+1 Influence
		+10% Trade Attractiveness
		+10% Trust Growth

Robot Assembly Optimization:
	Industry
	Repeatable (10x)

	Prerequisites:
		Tech - Robotic Workers

	Effects:
		+10% Robot Build Speed

Shipyard Assembly Coordination:
	Voidcraft
	Repeatable (10x)

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
		-5% Anomaly Fail Risk
		+15% Anomaly Discovery Chance

Harmonic Replenishment:
	Field Manipulation
	Repeatable (5x)

	Prerequisites:
		Shield Capacitors

	Effects:
		+5% Shield Regeneration

Multiphasic Scanning:
		Field Manipulation

	Prerequisites:
		Tech - Subspace Sensors

	Effects:
		+15% Survey Speed
		+15% Anomaly Research Speed

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
		+10% Terraforming Speed
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

Countermeasure Technologies[2]
--------------------------------------------------------------------------------
Machine Consciousness Countermeasures:
	Engineering - Voidcraft

	Effects:
		+20% Damage to Machine Consciousness Vessels

Extradimensional Invader Countermeasures:
	Physics - Particles

	Effects:
		+20% Damage to Extradimensional Invaders

Prethoryn Sourge Countermeasures:
	Society - Biology

	Effects:
		+20% Damage to Prethoryn Creatures

Fallen Empire Countermeasures:
	Engineering - Voidcraft

	Effects:
		+15% Damage to Fallen Empire Ships

################################################################################
# Notes
################################################################################

[1] This is produced by the Diplomatic Hub and essentially limits all Empires to
	a total of 1 Hub and 3 Embassies.

[2] These technologies are unlocked via Special Projects which appear after the
	respective fleets have been engaged in battle with your forces. Once
	unlocked, the technologies can be researched normally and/or completed by
	destroying those ships in combat.

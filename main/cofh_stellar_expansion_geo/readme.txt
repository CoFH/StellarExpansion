CoFH - Stellar Expansion - Geoengineering
Author: King Lemming

Alright, so this mod just got a complete reimagining due to 1.6 [Adams].
Basically, the primary need for the mod as it existed - terraformation of
inhabited worlds - is no longer a thing.

So what it does now is add a tech and some buildings. I'll be adding more to it
as I am able.

At the moment, these buildings boost terraforming and tile blocker clearing,
provide various boosts to planetary production, and also negate the happiness
penalty from terraforming an already inhabitated world.

################################################################################
# Buildings
################################################################################

Geoengineering Institute
	Planet-Unique
	Build:
		540 Days
		450 Minerals
		50 Influence

	Requires:
		8 Energy

	Produces:
		4 Physics Research
		4 Society Research
		4 Engineering Research

	Planet Modifier:
		*Negates Terraforming Happiness Penalty

	Empire Modifier:
		+25% Terraforming Speed
		-15% Tile Blocker Clear Cost
		-15% Tile Blocker Clear Time

	Prerequisites:
		Tech - Planetary Geoengineering

Geoengineering Complex
	Planet-Unique
	Build:
		360 Days
		200 Minerals

	Requires:
		2 Energy

	Produces:
		2 Physics Research
		2 Society Research
		2 Engineering Research

	Planet Modifier:
		*Negates Terraforming Happiness Penalty

	Prerequisites:
		Tech - Planetary Geoengineering

Energetic Modulation Reactor
	Planet-Unique
	Build:
		180 Days
		200 Minerals

	Requires:
		4 Energy

	Produces:
		4 Physics Research
		2 Society Research
		2 Engineering Research

	Planet Modifier:
		+10% Physics Research
		+10% Energy Credits
		*Negates Terraforming Happiness Penalty

	Prerequisites:
		Tech - Applied Quantum Physics

Phytogenic Infusion Reactor
	Planet-Unique
	Build:
		180 Days
		200 Minerals

	Requires:
		4 Energy

	Produces:
		2 Physics Research
		4 Society Research
		2 Engineering Research

	Planet Modifier:
		+10% Society Research
		+10% Food
		*Negates Terraforming Happiness Penalty

	Prerequisites:
		Tech - Xenobiology

Tectonic Stabilization Reactor
	Planet-Unique
	Build:
		180 Days
		200 Minerals

	Requires:
		4 Energy

	Produces:
		2 Physics Research
		2 Society Research
		4 Engineering Research

	Planet Modifier:
		+10% Engineering Research
		+10% Minerals
		*Negates Terraforming Happiness Penalty

	Prerequisites:
		Tech - Supersolid Materials

################################################################################
# Technologies
################################################################################

Society
--------------------------------------------------------------------------------
Planetary Geoengineering:
	New Worlds

	Prerequisites:
		Tech - Terrestrial Sculpting

	Effects:
		Unlocks Building: Geoengineering Institute
		Unlocks Building: Geoengineering Complex

Applied Geophysics:
	New Worlds, Rare

	Prerequisites:
		Tech - Planetary Geoengineering

	Effects:
		+25% Terraforming Speed
		**Provides Research (All Types) when a planet is terraformed or a tile blocker is cleared.

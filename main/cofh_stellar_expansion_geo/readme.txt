CoFH - Stellar Expansion - Geoengineering
Author: King Lemming

Alright, so this mod just got a complete reimagining due to 1.6 [Adams].
Basically, the primary need for the mod as it existed - terraformation of
inhabited worlds - is no longer a thing.

So what it does now is add a tech and a couple of buildings. I'll be adding more
to it as I am able.

At the moment, these buildings boost terraforming and tile blocker clearing,
provide a little bit of habitability, and also negate the happiness penalty from
terraforming an already inhabitated world.

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
		+5% Habitability
		*Negates Terraforming Happiness Penalty

	Empire Modifier:
		+50% Terraforming Speed
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
		+5% Habitability
		*Negates Terraforming Happiness Penalty

	Prerequisites:
		Tech - Planetary Geoengineering


################################################################################
# Technologies
################################################################################

Society
--------------------------------------------------------------------------------
Planetary Geoengineering:
	New Worlds

	Prerequisites:
		Tech - Atmospheric Filtering

	Effects:
		Unlocks Building: Geoengineering Institute
		Unlocks Building: Geoengineering Complex

CoFH - Stellar Expansion - Geoengineering
Author: King Lemming

This mod is deceptively simple, but there's a fair bit of event stuff behind the
scenes. Don't worry though, it's well optimized.

The single technology - Planetary Geoengineering - allows for construction of a
Geoengineering Complex on a planet. By itself, it acts only as a slightly better
basic science lab. However, it can be upgraded with Terraformation Reactors that
allow for the planet to be terraformed. This process takes a considerable amount
of resources and time, but works on already inhabited planets.

################################################################################
# Buildings
################################################################################

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

	Prerequisites:
		Tech - Planetary Geoengineering

Climate Moderation Complex:
	Planet-Unique
	Build:
		180 Days
		250 Minerals
		*Upgrade from Geoengineering Complex

	Requires:
		2 Energy

	Produces:
		2 Physics Research
		2 Society Research
		2 Engineering Research

	Planet Modifier:
		+10% Habitability

	Prerequisites:
		Tech - Atmospheric Manipulation

Terrestrial Reformation Reactor:
	Planet-Unique
	Build:
		360 Days
		1000 Energy
		1000 Minerals
		50 Influence
		*Upgrade from Geoengineering Complex

	Requires:
		2 Energy

	Produces:
		2 Physics Research
		2 Society Research
		2 Engineering Research

	Planet Modifier:
		Enables Special Projects: Terrestrial Sculpting

	Prerequisites:
		Tech - Terrestrial Sculpting


Atmospheric Variation Reactor:
	Planet-Unique
	Build:
		540 Days
		2500 Energy
		2500 Minerals
		50 Influence
		*Upgrade from Geoengineering Complex

	Requires:
		2 Energy

	Produces:
		2 Physics Research
		2 Society Research
		2 Engineering Research

	Planet Modifier:
		Enables Special Projects: Atmospheric Manipulation

	Prerequisites:
		Tech - Atmospheric Manipulation

Climate Restoration Reactor:
	Planet-Unique
	Build:
		720 Days
		5000 Energy
		5000 Minerals
		25 Influence
		*Upgrade from Geoengineering Complex

	Requires:
		2 Energy

	Produces:
		2 Physics Research
		2 Society Research
		2 Engineering Research

	Planet Modifier:
		Enables Special Projects: Climate Restoration

	Prerequisites:
		Tech - Climate Restoration

Gaiaformation Reactor:
	Planet-Unique
	Build:
		1080 Days
		10000 Energy
		10000 Minerals
		100 Influence
		*Upgrade from Geoengineering Complex

	Requires:
		2 Energy

	Produces:
		2 Physics Research
		2 Society Research
		2 Engineering Research

	Planet Modifier:
		Enables Special Project: Gaia Creation

	Prerequisites:
		Tech - Gaia Creation

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
		Unlocks Mechanic: Planetary Geoengineering
			Allows terraforming of inhabited worlds.
			The required terraforming technology must also be unlocked.

		Unlocks Building: Geoengineering Complex

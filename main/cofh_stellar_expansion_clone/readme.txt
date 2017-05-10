CoFH - Stellar Expansion - Cloning
Author: King Lemming

So, this mod allows for population cloning! It adds a technology which unlocks a
policy, building, and buildable clone populations.

The building provides a large boost to population growth on a planet. Be aware
that Spiritualist Empires will react negatively to every pop born on a planet
with one of these, if Mass Cloning is being utilized.

Additionally, your Empire's primary species can be directly created for 25/25/25
Energy/Minerals/Food. They will grow as a normal population, except with a +200%
modifier. However, when they complete their growth, they will have a penalty to
Research and Unity production for 5 years, but a bonus to Government Ethics
Attraction.

Please note that Spiritualist Empires will also react negatively to these soul-
less creatures, should you choose to populate your Empire with them.

################################################################################
# Buildings
################################################################################

Genomic Replication Facility:
	Planet-Unique
	Build:
		360 Days
		350 Minerals

	Requires:
		4 Energy

	Produces:
		4 Society Research

	Planet Modifier:
		+15% Population Growth Speed
		*+50% Population Growth Speed with Limited or Unrestricted Mass Cloning

	Prerequisites:
		Tech - Mass Cloning


################################################################################
# Technologies
################################################################################

Society
--------------------------------------------------------------------------------
Mass Cloning:
	Biology

	Prerequisites:
		Tech - Cloning

	Effects:
		Enables Mass Cloning Policy
		Unlocks Building: Genomics Replication Facility
		Unlocks Buildable Pop: Clone Population

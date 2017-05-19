CoFH - Stellar Expansion - FTL Enhanced
Author: King Lemming

Howdy! So here's the deal with this particular addon. Given that FTL is a very
foundational aspect of gameplay, I will be isolating any changes to it in this
submodule.

Two of the technologies added by this mod can be acquired once an empire
possesses a form of FTL travel that incurs either a Windup (Hyperlane, Jump) or
Winddown (Warp, Jump) time.

This means that Warp and Hyperlane empires can acquire their technologies before
researching Jump Drives, which makes their mid to late-game play a bit more
competitive with Wormholes.

The other two technologies depend on Sensor and Shield research, and provide
boosts to Emergency FTL and general ship attributes.

In the future, I may add more FTL-related technologies and modules. The new Aux
Utility slot in particular has some potential.

################################################################################
# Technologies
################################################################################

Physics
--------------------------------------------------------------------------------
Exigent Sensor Calibration:
	Voidcraft, Rare

	Prerequisites:
		Technology - Subspace Sensors

	Effects:
		+25% Ship Sensor Range
		-25% Emergency FTL Jump Cooldown

Hypernavigation Calibration:
	Particles, Rare

	Prerequisites:
		FTL Travel with Jump Charge Time

	Effects:
		-25% Jump Charge Time

Spacetime Resonance Damping:
	Field Manipulation, Rare

	Prerequisites:
		Technology - Shields

	Effects:
		+10% Ship Hull Points
		-25% Emergency FTL Damage

Spacetime Resonance Damping:
	Field Manipulation, Rare

	Prerequisites:
		FTL Travel with Jump Cooldown

	Effects:
		-25% Jump Cooldown

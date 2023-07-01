# CVCS Panel

# Theory

CVCS Panel is the secondary mean to control reactivity of the reactor by injecting or removing boric acid from the primary circuit. Boron is a neutron absorber, therefore higher concentrations will reduce reactivity. Once the reactor is initially setup and running, all smaller changes to the reactivity should be done with boric acid concentration adjustment along with steam demand changes.

# Concentration adjustment

Boric acid concentration can be adjusted in the primary circuit with INJECT switch, although with INJECTION MODE set either to borate (for increasing concentration) or dilute (for decreasing). In the borate mode, boric acid is injected while in the dilute mode water is injected into the circuit. In order to borate or dilute, appropriate main tanks need to contain either boron (for borate) or water (for dilute). At the same time, water with boric acid is removed from the circuit to maintain constant water level in the primary. It gathers in the EXTRACT TANK. 

# Evaporator operations

The evaporator can be filled with extract from the EXTRACT TANK directly using EVAP IN PMP with given setpoint. The role of the evaporator is to boil all the water into steam, leaving just boric acid at the bottom, which can be then separated into different tank.

# Heating up

In order to boil water, the evaporator has to be heated up with steam from the secondary circuit. Therefore, it can only be operated while secondary is pressurized and in operation. In order to heat up the evaporator, EVAP IN should be switched. From that point temperature should raise and when boiling point is reached, water would start to boil reducing evaporator level. Once level stops close to zero, boric acid can now be extracted into EVAP CONC tank with EVAP CONC OUT switch. Steam can also be removed and condensated into EVAP H2O tank with EVAP STEAM OUT switch.

# Transferring

Water and boric acid can now be transferred to their tanks for further use with transfer pumps which will move them into the main tanks.

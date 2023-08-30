# Reactor operations

## Reactor modes

At this moment three reactor modes are implemented. Shutdown mode is a mode in which rods are slowly pulled back into the core until they are all in. IPR mode is the initial startup mode up to around 100 MW of thermal power. In this mode IPR should be incremented with +/- buttons to keep the IPR value between 30% and 70%. If outside of this values, reactor will trip. Above 50 MW of thermal power, reactor should be switched into run mode, to prevent IPR trip. Run mode is normal operating mode. Should reactor power dropped back below 50MW thermal, rods can't be pulled in run mode, and therefore reactor must be switched back to IPR mode, but be sure to be in IPR limits to prevent trip. At all times reactor will trip if SUR is above 1.5.

## Shutdown rods

Top part of the diagram correponds to the shutdown rods. They need to be fully pulled first before lower bottom of the diagram rods could be pulled. Shutdown rods should be fully pulled at all the time and can be used for a quick group trip. It is essential to start the reactor only when already in high water temperature (above 250 degrees) or shutdown rods could raise reactivity too much. If this is the case also for high temperatures, some boron needs to be added to the circuit.

## Reactor trip

Reactor can trip for many different reasons also a manual trip can be initiated. Two types of trips are possible. Group trip or full trip. In group trip all rods fall down under gravity into the core, while in group trip only shutdown rods are affected. After trip rods need to be relatched.

## Latching the rods

At the game start and whenever trip happens, rods need to be latched back. In order to do that, latching voltage switch needs to be enabled and then all unlatched rods need to be pushed back with insert mode of reactor control. There is no indication of which rods are unlached but it's obvious for those which can't be pulled in IPR/RUN modes. No rods can be pulled in the latching mode.

## Shutdown mode

This mode is used to shutdown the reactor. It will slowly push down all rods into the core. If longer shutdown is expected, all rods should be also unlatched by initiating a full trip procedure once all rods are already in the core.

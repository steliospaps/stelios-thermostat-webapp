# stelios-thermostat

## about

My heatpump came with no thermoats. I can set the hot water temperature and the temperature of the water in the system, but the room temperature depends on the Termostatic Radiator Valve. I can use external temeprature conmpensation curves, but they do not take into account things like sunshine etc. So I built my own.

I have Tuya thermal sensors in some rooms, and I pull the data from Tuya cloud. I run a python script that acts as a PId controlling the heatmpump via ReaLinks.

The interface is a Telegram bot and App.

### Why not home assistant

I am running the system in a Rapsberry Pi Zero W which does not ahv eenough memory.

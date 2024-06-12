
**Date:** 2024-06-11

## Description
The Atomic Layer Deposition (ALD) system is used for the precise deposition of thin films one atomic layer at a time. This equipment allows for uniform coating on complex substrate geometries and excellent thickness control.

## Manufacturer
- **Brand:** PICOSUN
- **Model:** R-2000

## Specifications
- **Deposition Method:** Sequential self-limiting surface reactions
- **Temperature Range:** 50°C to 500°C
- **Deposition Rate:** 0.2 - 1.2 Å per cycle
- **Precursors:** TEMAH, BDEAS, TMA, DEZ, TEGA, OZONE, DIH2O, NH3
- **Deposited Films:** Al₂O₃, AlN, ZnO, Zn₃N₂, SiO₂, Si₃N4, HfO₂, HfN, Ga₂O₃, GaN
- **Substrate Size:** Up to 150 mm diameter
- **Software:** Custom control software with recipe management

## Components

- **Carrier Gas System:** Carries the precursor to the reaction chamber and purges the gas between the pulses.
- **Precursor Source System:** Attached to a carrier gas line by a pneumatic ALD pulsing valve
- **Vacuum Chamber:** Isolates the reactor from room air
- **Reaction Chamber:** Houses the substrate holder
- **Lift System:** Pneumatic elevator that lifts the vacuum chamber lid.

## Safety Precautions
- Always wear appropriate personal protective equipment (PPE) including gloves, safety goggles, and lab coat.
- Wear two sets of gloves when loading/unloading wafer from the substrate holder.
- Ensure the exhaust system is operational before starting the deposition process.
- Handle chemical precursors with care, following all safety guidelines and data sheets (MSDS).
- Never operate the ALD system outside of specified temperature and pressure ranges.

## Operation Procedure
1. **System Preparation**
    - Check that the system is properly vented and the chamber is clean. 
	    - PT2 ~ 0.6 hPa
	    - TE2 90% Process Temperature or greater
	    - Flow Rates: 79-80 sccms
	    - V1 is open
	- Check the tower is lifted up, and the gate is closed.
	- Check that the system is properly vented and the chamber is clean. Push the wafer towards you since the wafer picker is not aligned correctly.
		- PT50 should settles to around 1000 hPa
	- Open the load lid (might need to unscrew) and load the wafer onto the holder (flat should face the PC).
    - Close the chamber door and initiate the vacuum pump sequence.
	    - PT50 should settles to around 6 hPa
	    - Three indicators should be green
2. **Wafer Transfer** 
	- Open the gate valve to transfer the wafer into reactor chamber.
		- VISUALLY check the gate valve is open
	- Load the sample by slowly pushing the loading rod until the black mark.
		- Observe that the wafer is properly aligned to the wafer pick of the reactor chamber.
	- If properly aligned, continue to push wafer on holder all the way into the reactor chamber.
	- Pick Wafer and observe wafer pick lifts wafer off the wafer holder
	- Retract the loading rod slowly, again stopping at the black mark to observe alignment. Then all the way to the end.
	- Close the gate valve.

4. **Recipe Setup**
    - Open the control software and select a deposition recipe (i.e. Al₂O₃ TMA H₂O).
    - Specify the precursors, reaction time, and purge times for each cycle. Select the number of deposition cycles
	    - Check if recipe was loaded
	
5. **Precursor Loading**
    - Ensure precursor containers are filled and connected to the system.
    - Ensure all necessary gas lines and precursor bottles are open (i.e. TMA, H₂O etc).

6. **Deposition Process**
    - Make sure all starting conditions are all green.
	    - Turn on the V700 valve.
    - Start the deposition process through the control software.
    - Monitor the process parameters (pressure, temperature, gas flow) in real-time.
    - Allow the system to complete the specified number of cycles.

7. **Post-Deposition**
    - Once deposition is complete, close the TMA and water valve.
    - Click Unload and then immediately cancel to avoid venting the chamber to atmosphere.
    - Open V1, and then Unload Wafer. 
    - Move the handle to black mark, observe alignment, then fully in the chamber to collect wafer.
    - Unpick, and observe the wafer being place on loader arm. Retrieve loader arm fully to end of shaft.
    - Close the Gate.
    - Vent the chamber and carefully remove the substrate.
    - Close load lock lid and pump down the chamber by pressing EVACUATE
	    - Disable V700 to shut-off Ar gas
    - Verify that all precursor bottles are closed,
	    - PT1 ~ 4hPa
	    - PT2~0.7hPa
	    - PT50~7hPa
	    - MFC1~300sccms
	    - All Precursor lines have N2 flowing through them at 80 sccms
	      MFC700 should be 0sccms.quality.
    - Inspect the substrate for uniformity and film. 
    - Log the deposition parameters and results in the system logbook.


## Troubleshooting
- **Non-uniform Coating:** Ensure substrate is properly secured and rotating during deposition.
- **Low Deposition Rate:** Check precursor levels and delivery system for blockages.
- **Vacuum Issues:** Inspect vacuum seals and pump operation.

## Related Notes
- [[Wafer Solvent Cleaning]]
- [[Wafer Piranha Cleaning]]

## Observations
- Record any deviations from standard operation, unusual observations, or maintenance performed.

---

**Date:** 2024-06-11

**Operator:** Georgios Ch.

**Notes:** N/A

## Next Steps
- N/A

---

**Tags:** #ALD #equipment #deposition #cleanroom

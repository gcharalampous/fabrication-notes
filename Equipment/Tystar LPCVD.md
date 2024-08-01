**Date:** 2024-08-01

## Description
The TYSTAR Low Pressure Chemical Vapor Deposition (LPCVD) system is utilized for the deposition of high-quality thin films on substrates. This system is known for its uniformity and precise control over film thickness and composition.

## Manufacturer
- **Brand:** TYSTAR
- **Model:** Berkeley Nanolab 14-16

## Specifications
- **Deposition Method:** Gas-phase chemical reactions under low pressure
- **Temperature Range:** 300°C to 900°C
- **Deposition Rate:** Typically 5 - 50 nm/min, depending on process conditions
- **Precursors:** Nitrogen (N₂), Silane (SiH₄), and Oxygen (O₂)
- **Deposited Films:** Si₃N₄, SiO₂, Poly-Si
- **Substrate Size:** Up to 150 mm diameter
- **Software:** Advanced process control software with recipe management

## Components

- **Gas Delivery System:** Provides a controlled flow of reactant gases into the reactor chamber.
- **Precursor Source System:** Supplies the necessary chemical precursors for film deposition.
- **Vacuum Pump System:** Maintains a low-pressure environment in the reaction chamber.
- **Reaction Chamber:** A quartz tube where the substrate is placed and deposition occurs.
- **Boat and Loader System:** Holds the substrates and facilitates their introduction and removal from the reaction chamber.
- **Furnace System:** Heats the substrates to the desired temperature for the chemical reactions.

## Safety Precautions
- **Always wear appropriate personal protective equipment (PPE), including gloves, safety goggles, and a lab coat.**
- **Electric Shock Hazard**: Tystar furnaces utilize high electric power (high current) to generate heat. Do not open the side panels or touch the high power electrical parts in the furnace cabinet.
- **Chemical Hazard:** SiH4 is an explosive gas when mixed with air. Do not attempt to open the tube during processing. If there is a problem, contact staff.
- **Burn Hazard:** Cantilevers, boats, and wafers coming out of the furnace are very hot. Always wear a face shield when loading/unloading wafers. Proceed with caution. Avoid touching any furnace quartz ware to prevent burning your hands and/or contaminating the furnace. No flammable chemicals, especially organic solvents, are allowed at the load station when the tube is open.
- **New recipes are not permitted without the express consent of process staff.**

## Operation Procedure
1. **System Preparation**
    - Make sure no recipe is running, and that furnace status reads **IDLE**. The STNBY recipe should be running. The process should loop at STEP-60.
    - Click **EVENT** to exit the STNBY recipe. Verify the system is clean and properly starts to backfil (BKFL).

2. **Recipe Setup**
    - Go to **MAIN MENU** and type **RL** (Recipe Load) to display the available recipes.
    - Select the desired recipe using arrow keys and press **ENTER** twice to begin.
        - Enter the desired process parameters when prompted. When done, press **ENTER**, then press **MAIN MENU** as instructed by the computer control.
        - For the deposition time use all digits.
    - The furnance status should still read **IDLE** in Display Status.
        - Click Dispay Status or **DS** to verify the recipe load and parameters.
    -  Press **RUN**. The furnace door will open and wafer boats will come out. 
        - Transfer your wafer from msink6 to Tystar using the designated box.

3. **Wafer Loading**
    - Load the wafers into the boat, and ensure the reaction chamber and quartz tube are free of contaminants.
    - Ensure the substrates are evenly spaced to promote uniform film deposition, and press the **EVENT** to start the boat moving into the furnace.
    - Check gas flow controllers, precursor levels, and vacuum pump operation. 

4. **Deposition Process**
    - Monitor critical parameters such as temperature, pressure, and gas flow rates.
    - Allow the reaction to proceed for the specified duration to achieve the desired film thickness.

5. **Post-Deposition**
    - Once the deposition is complete, press the **EVENT**. The tube will be gently brough up to the atmosphere.
    - Press **EVENT** again will open the furnace door moving the boats out. 
    When boat stops moving allow the system to cool down to a safe temperature (at least 5 min).
    - Open the reaction chamber and carefully remove the substrates.
    - Press **EVENT** to move the boat back into the furnance. The furnance status should read IDLE once the door is closed.

6. **System Shutdown**
    - Load and run the standy recipe.
    - Disable Tystar in Mercury Client.
    - Record all relevant process data and observations in the logbook.

## Troubleshooting
- **Non-uniform Coating:** Check for proper wafer alignment and ensure consistent gas flow.
- **Low Deposition Rate:** Verify precursor flow rates and check for leaks in the gas delivery system.
- **Vacuum Issues:** Inspect vacuum pump performance and ensure all seals are intact.

## Related Notes
- [[LPCVD System Maintenance]]
- [[Wafer Cleaning Procedures]]

---

**Tags:** #LPCVD #TYSTAR #thinfilms #deposition #cleanroom

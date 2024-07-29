**Date:** 2024-06-11

## Description
The Dicing Saw system is used for cutting semiconductor wafers into individual dies. This equipment ensures precision cutting with minimal damage to the wafer and die.

## Manufacturer
- **Brand:** DISCO
- **Model:** DAD3240

## Specifications
- **Cutting Method:** High-speed rotating blade
- **Blade Type:** Diamond
- **Spindle Speed:** 6000 - 60000 RPM
- **Cutting Speed:** 0.1 - 600 mm/sec
- **Blade Diameter:** 2” to 4”
- **Substrate Size:** Up to 200 mm diameter
- **Software:** Custom control software with recipe management

## Components
- **Blade Spindle:** Rotates the dicing blade at high speed.
- **Worktable:** Holds the wafer during the dicing process.
- **Cooling System:** Supplies coolant to the blade to prevent overheating.
- **Vacuum Chuck:** Secures the wafer to the worktable.
- **Camera System:** Provides real-time visual feedback for alignment and cutting.

### Keteca, P/N K3T20L45 Specifications
- Kerf (width of cut): 51 μm
- Blade exposure (new): 1.14 mm
- Recommended cutting speed: 3-5 mm/sec
- RPM recommended 30000
- Maximum Cutting Speed: 15 mm/sec
- Blade Height: 0.08 mm

#### **Disco Input**
- Blade Exposure: 0.9 mm
- Blade Height: 0.08 mm
- Feed Speed: 3mm/s
- Work Size: Round - 150 mm
- Work Thickness: 0.675 mm
- Tape Thickness (blue): 0.120 mm
- Spindle Rev: ? 30 000



## Safety Precautions
- Do not grab/handle a blade by its edge; this can cut your fingers.
- Operating the saw without covers (this saw has an automatic safety cover), which increases the amount of particles that enter your lungs.
- Always wear the appropriate PPE.
- Pinching your fingers between the chuck table and the dicing ring.

## Quick Checklist
- Coat the wafer with 1-2 μm of photoresist.
- Know the thickness of the wafer. Measure with a caliper if needed.
- Know the specs of the blade you are using before enabling the tool. Never attempt to make a cut that is deeper than the exposed amount of saw blade
- Always perform a Non-Contact Setup after changing the blade and make sure to input and **[SAVE]** (press **[ENTER]**) the standard blade exposure
- Make sure cooling water is being supplied to the cutting area (only comes on during a cut). The three flow meters on the left side of the machine should read: **BLADE ∼ 1.5 (L/min.)**, **SHOWER ∼ 1.0 (L/min.)**, and **SPRAY ∼ 1.0 (L/min.)** during cutting operation.
- If the C/T vacuum is sufficient, -60 kPA or more. There is a digital gauge on the main screen which shows the vacuum level on the chuck. Make sure the green bar is filled past the red line during vacuum check

## Operation Procedure
1. **System Preparation**
   - Turn on the tool.
   - Check that the system is properly vented (> 0.4 MPA) and the worktable is clean.
   - Initialize the system. press the **[System Initial]** button in the bottom left hand corner of the **[Main Menu]** screen.
   - Ensure the blade is correctly installed and secured.
   - Verify coolant supply and ensure the coolant tank is filled.

2. **Wafer Loading**
   - Mount your wafer onto the dicing tape and dicing ring using the alignment marks on the sheet next to Disco. 
   - Place the ring, tape, wafer setup onto the chuck.
   - Press the **[C/T vacuum]** button on the bottom right if the **[Main Menu]** screen.
   - Verify that the vacuum is engaged and above the red line (∼ -60 kPa) of the gauge.

3. **Load the Blade**
   - Go to **[Blade Maintenance]**
   - Verify the current blade exposure exceeds i.e. 0.8 mm on silicon blade. Update the rest of the parameters.
   - Press the **[Blade Replacement]** button. The blade will come forward and the spindle will be locked.
   - Blade Replacement
     - Remove the front wafer shower module, and gently set aside.
     - Raise the Blade Breakage Detector (BBD). The entire blade should be now visible.
     - Use the blade grabber to remove any blade, and insert the new blade on the spindle.
     - Carefully rotate the spindle until it locks into position. 
     - Screw the blade lock nut over the blade using the nut demounting jig. Turn it by hand until it is tight. Use the torque wrench to tighten until you hear ONE click.
   - Enter the blade exposure. Hit **[ENTER]**. Do not proceed until this value has been saved. Press **[NEXT]**.
   - From the **[Blade Maintenance]** Menu, select **[B.B.D (Blade
Breakage Detector) Adjustment]** button.
     - Ensure there is high signal when the BBD is in the raised position. The light meters should read 90% - 99%.
     - Slide the BBD fixture down. Tighten the BBD retaining screw once 10% is achieved.
     - Close the plastic sliding cover and press **[NEXT]**.
   - From the **[Blade Maintenance]** Menu, select the **[Blade Setup]** button.
     - From the **[Setup Menu]**, press the **[Non-Contact]** button.
     - Press the **[START]** button and allow the blade setup to complete before moving to the next step. Press the **[EXIT]**

4. **Perform a Hair Alignment**
   - From the **[Blade Maintenance]** Menu, select **[Hairline Alignment]**.
   - Input the dicing parameters for your wafer. Hit **[ENTER]** to save your parameters.
   - Manual θ alignment
     - Correct the θ-angle by moving left and right on known structures on the wafer.
     - Make sure you are on HIGH magnification
     - Move the crosshairs to the useless part of the wafer you want to do your test cut on. Hit **[START]**.
     - Match the width of the hairline cut, and press **[Hairline Adj]**. If successful, the information bar will read, **[Hairline Adjusted]**. 
     - Press the yellow **[EXIT]** button twice to return the **[Main Menu]** screen

5. **Recipe/Job Setup**
   - Open the control software and select a dicing recipe.
   - Specify the blade type, spindle speed, cutting speed, and cut depth.
   - Check if the recipe was loaded correctly.

6. **Dicing Process [Semi-Automatic Cutting]**
   - Press **[Manual Operation]** button, then press the **[Semi-Automatic Cutting]** button.
   - The next step is to align the wafer. Press **[Manual Alignment]**.
   - Make sure you are on **HIGH** Magnification.
   - Once the alignment is done, press the blue **[ENTER]** button to go back to the **[Semi Auto Cut.]**
   - Ensure all starting conditions are green.
   - Start the dicing process by simply hit the green **[START]** button.
   - Monitor the process parameters (spindle speed, cutting speed, coolant flow) in real-time.
   - Allow the system to complete the specified cuts.Silence the alarm with the **[Alarm Clear]** button.



7. **Post-Dicing**
   - Once dicing is complete, deactivate the vacuum chuck. Press **[C/T Vacuum]** at the bottom of the screen.
   - Rinse your wafer with water, blow it dry and remove your substrate/wafer from the tool.
   - Blow dry the chuck of any excess water as a courtesy to the next user.
   - Carefully remove the diced wafer from the worktable.
   - Inspect the dies for uniformity and quality.
   - Remove the Blade:
     - Follow the steps from section 3.
     - On the blade replacement screen, press the yellow **[EXIT]** button twice to escape back to the **[Main Menu]** screen.
   - Power-off the tool.

## Troubleshooting
- **Non-uniform Cuts:** Ensure the wafer is properly aligned and secured.
- **Blade Chipping:** Check blade condition and replace if necessary.
- **Vacuum Issues:** Inspect vacuum seals and pump operation.

## Emergency Procedures
- In case of system failure, press the emergency stop button and follow the facility’s emergency protocols.
- For coolant leaks, shut off the coolant supply and notify the safety officer immediately.

## Maintenance Schedule
- Regularly check and replace the dicing blade.
- Clean the worktable daily.
- Inspect the vacuum chuck and seals monthly.

## Related Notes
- [[Wafer Cleaning Procedure]]
- [[Blade Replacement Guide]]

## Observations
- Record any deviations from standard operation, unusual observations, or maintenance performed.

---

**Date:** 2024-06-11

**Operator:** Georgios Ch.

**Notes:** N/A

## Next Steps
- N/A

---

**Tags:** #dicing #equipment #semiconductor #cleanroom

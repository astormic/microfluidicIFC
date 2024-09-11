<header>

<!--
  <<< Author notes: Course header >>>
  Include a 1280×640 image, course title in sentence case, and a concise description in emphasis.
  In your repository settings: enable template repository, add your 1280×640 social image, auto delete head branches.
  Add your open source license, GitHub uses MIT license.
-->

# Microfluidic

_The implementation of microfluidic on the OPM microscope._

</header>

<!--
  <<< Author notes: Step 1 >>>
  Choose 3-5 steps for your course.
  The first step is always the hardest, so pick something easy!
  Link to docs.github.com for further explanations.
  Encourage users to open new tabs for steps!
-->

## Materials:
### Syringe Pump
- AL-1000, Aladdin SyringeONE Programmable Syringe Pump
- Channels:	1
- Type:	Infusion / Withdrawal
- Flow Range:	0.001 µL/hr (0.5 µL syringe) to 3470 mL/hr (140 mL syringe)
- Dispensing Accuracy: ±1%
- Syringe Sizes Accepted:	0.5 µL to 60 mL or 140 mL partially filled
- Linear Force:	35 lb at low speed; 18 lb at maximum speed

### Needle
- 23 Gauge Fluid Dispensing Tip, 
- TE Series, Orange, 
- Pack of 50 -  923050-TE
 
### Tubing
- PTFE Microtubing,
- Inner Diameter: 0.56 mm,
- Outer Diameter: 1.07 mm, 
- Autoclavable
 
### Syringe
- Eccentric Luer-Slip Tip Three-Part Syringe, 
- Volume: 2.5 mL, 
- Connection Type: Centric Luer-lock

### Microfluidic chip
- Cutom-designed and built 
- Straight channel
- 20 μm (width) × 30 μm (depth) channel size

<!-- Divider -->
## Methods:
### Chip Fabrication
The chips were fabricated based on PDMS (Polydimethylsiloxane) using lithography to create the microfluidic channels on a silicon wafer.

### Beads in flow
#### Preparation:
- Calibrate the syringe pump and ensure all connections (tubing, needle, syringe) are secure and leak-free.
- Prepare the bead suspension with a suitable concentration to avoid overcrowding in the channel
- Load the bead sample into the syringe.

#### Flow and Imaging:
- Set the desired flow rate on the syringe pump.
- Start the flow and begin time-lapse imaging using Multi-D acquisition in MicroManager.
- Capture images at different flow rates to understand the behavior of beads under varying conditions.

#### Analysis:
- Use the spot counter to detect and count the beads.
- Analyze the fluorescence intensity and movement of beads.

#### Optimisation:
Adjust the flow rates, bead concentration, and imaging parameters based on initial results to optimize the experiment.


> [!NOTE]
> Ensure that the syringe pump is calibrated accurately. You might want to run a few preliminary tests to verify the flow rates.

<!-- Divider -->
## FAQs: 


<!-- Divider -->
## Appendix

<footer>

<!--
  <<< Author notes: Footer >>>
  Add a link to get support, GitHub status page, code of conduct, license link.
-->

---

Feedback: [Create a pull request]()

&copy; 2024 GitHub &bull; [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT License](https://gh.io/mit)

</footer>

# Analysis of Ferroresonance in Photovoltaic Park Distribution Systems

Manuscript ID: IEEE LATAM Submission ID: 10349

Authors:
<ul>
  Instituto Tecnológico de Morelia:
    <li>Mario Alberto López Albiter.</li>
    <li>Vicente Torres García.</li>
  Universidad Nacional Autónoma de México:
    <li>Néstor González Cabrera.</li>
    <li>Emmanuel Hernández Mayoral.</li>
</ul>

<h2>Included files</h2>
This repository includes the ATPDraw simulation: 

<ul>
    <li>Photovoltaic_Park_Distribution_System.acp: The file contains an overview of the simulation, including the main elements.</li>
    <li>Case_1.acp: It contains the energizing under no-load conditions, one-phase delay.</li>
    <li>Case_2.acp: It contains the No-Load Disconnection, two-phase delay.</li>
    <li>Case_3.acp: It includes disconnection with maximum generation power, two-phase delay.</li>
    <li>Case_4.acp: It contains the disconnection with minimum generation power, two-phase delay.</li>
</ul>
In all cases, to vary the distance it is necessary to modify the LCC module (CT1_SUB) and to observe the effect of the arresters it is necessary to unhide the element marked as MOV.

To visualize the transformer voltages, it is necessary to plot the signals VCT1A, VCT1B and VCT1C.

<h2>Requirements</h2>
ATPDraw 75.
<h2> Contact</h2>
mario.albiter@ieee.org

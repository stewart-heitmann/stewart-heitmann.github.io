---
layout: home
title: Research
permalink: /research/
list_title: 
---

## Brain Dynamics Toolbox
The **Brain Dynamics Toolbox** is open matlab software for exploring user-defined dynamical systems with minimal programming effort. It solves initial-value problems in systems of ODEs, DDEs, SDEs and PDEs. Users define their system of equations as a custom matlab function. Interchangeable solvers and graphical plotting tools can then be applied to it with no additional programming effort. The toolbox is available from [bdtoolbox.org](https://bdtoolbox.org).

![Handbook for the Brain Dynamics Toolbox](PaperbackCoverArt-2023.png "Handbook for the Brain Dynamics Toolbox"){: .my-image70} 

Heitmann S, Breakspear M (2023) **Handbook for the Brain Dynamics Toolbox: Version 2023.** *bdtoolbox.org.* ISBN 978-0-6450669-3-7.

Heitmann S, Aburn M, Breakspear M (2017) *The Brain Dynamics Toolbox for Matlab.* **Neurocomputing** Vol 315. p82-88. doi:10.1016/j.neucom.2018.06.026
<br><br>

---

## Cardiac Safety Pharmacology
The *axis of arrhythmia* is a conceptual framework we devised to predict the risk of drug-induced torsades de pointes, a life-threatening ventricular arrhythmia. The axis quantifies how different combinations of ion channel blockade in cardiac cells influence arrhythmogenic potential, offering a standardised method for drug safety assessment. Recently, we showed that the axis can be derived independently from both (i) biophysical computer simulations, and (ii) statistical analysis of pharmacological drug datasets. It is a lovely example of a simple idea that bridges the gap between complex biophysical models and black-box statistical models.
![Axis of Arrhythmia Figure](AxisArrhythmiaFig2.png "Axis of Arrhythmia"){: .my-image70}

Heitmann S, Vandenberg JI, Hill AP (2025). *Independent derivations of the axis of arrhythmia for predicting drug-induced torsades de pointes.* **British Journal of Pharmacology**, 1–15. [doi:10.1111/bph.7078](https://doi.org/10.1111/bph.70078).

Heitmann S, Vandenberg JI, Hill AP (2023) *Assessing drug safety by identifying the axis of arrhythmia in cardiomyocyte electrophysiology.* **eLife.**
[doi:10.7554/eLife.90027](https://doi.org/10.7554/eLife.90027).
<br><br>

---

## Arrhythmogenesis as the failure of repolarization
Atrial fibrillation typically arises from the anatomical site where the pulmonary veins attach to the heart wall. Nobody knows why. We used dynamical systems theory to show that arrhythmias can be triggered by cardiac cells that fail to repolarize of their own accord. Technically, these cells are said to be *bistable* because they can dwell in either the resting state or the depolarized state. 

![Bistable Action Potentials](BistableActionPotentials.png "Bistable Action Potentials"){: .my-image70}

Our analysis showed that the heart can support normal travelling waves despite the presence of large numbers of bistable cells. However there is a limit and tissue boundaries are especially susceptible to arrhthymia. This may explain why atrial fibrillation often emanates from the cuff of the pulmonary vein. 
<center>
<video src="Bistable_S3_Video.mp4" controls="controls" style="max-width: 50%;" >
</video>
</center>

Heitmann S, Shpak A, Vandenberg J, Hill A (2021) *Arrhythmogenic effects of ultra-long and bistable cardiac action potentials.* **PLoS Computational Biology** 17(2): e1008683.
<br><br>

---

## Direction-selective visual motion detection
Neurons of the visual cortex are known to respond selectively to the direction of visual motion. Mathematically, the response characteristics of the neurons cannot be constructed from separate spatial and temporal processes. It is unknown how these neurons work without resort to explicit time delays in the circuitry. 

![Visual Motion Detection](VisualMotionFig1.png "Visual Motion Detection"){: .my-image50} 

We proposed a novel neural mechanism that relies on travelling waves in the cortical tissue insetad of time delays. We showed that endogenously generated waves can resonate with the space-time signature of the visual stimulus to selectively respond to visual motion. The speed and direction of the waves are governed entirely by the profile of the lateral-inhibitory coupling.

![Endogenous waves](VisualMotionFig3.png "Endogenous waves"){: .my-image50} 

Heitmann & Ermentrout (2020) *Direction-Selective Motion Discrimination by Traveling Waves in Visual Cortex.* **PLoS Computational Biology** 16(9): e1008164.

Heitmann & Ermentrout (2016) *Propagating Waves as a Cortical Mechanism of Direction-Selectivity in V1 Motion Cells.* Proc 9th EAI Intl Conf on Bio-inspired Info & Comm Tech. BICT'15. New York. 
<br><br>

---

## The mathematics of brain stimulation

Optogenetic techniques allow neurophysiologists to directly stimulate neurons with light. It is often assumed that the dynamical behaviour of the neural tissue is unchanged. However recent observations provide a clue that this may not be the case. Lu et al (2015) found that stimulation of macaque cortex elicited 40-80 Hz oscillations that were consistent with Type II neural excitability. Yet these oscillations propagated far into the surrounding cortical tissue. Whereas mathematical theory suggests that propagating waves are only supported by neural tissue with Type I excitability. So how can cortical tissue simultaneously exhibit both Type I and Type II excitability? 
We investigated the apparent contradiction by modelling the cortex as recurrently-connected excitatory and inhibitory neurons. We found that optogenetic stimulation can locally transform Type I excitability into Type II excitability by preferentially targeting inhibitory cells. The findings shed new light on how optogenetic stimulation can alter the response dynamics of neural tissue. 

|:--:|
| ![Optogenetic waves](OptogeneticsFigure5.png "Optogenetic waves") | 
| Space-time plots of the cortical model in one spatial dimension. Optogenetic stimulation was applied focally at position x=0.  Panels A-C show cases of weak, medium, and strong stimulation respectively. The model exhibits co-existing Type I and Type II excitability in agreement with neurophysiological observations. |

Heitmann, Rule, Truccolo, Ermentrout (2017) *Optogenetic stimulation shifts the excitability of cerebral cortex from Type I to Type II: Oscillation onset and wave propagation.* **PLOS Computational Biology.** 13(1): e1005349. doi: 10.1371/journals.pcbi.1005349

Lu, Truccolo, Wagnerm Varas-Irwin, Ozden, Zimmermann, May, Agha, Wang, Nurmikko (2015) *Optogenetically induced spatiotemporal gamma oscillations and neuronal spiking activity in primate motor cortex.* **J Neurophysiol** 113: 3574-3587. 
<br><br>

---

## The cortical origin of visual hallucinations

Geometric patterns of spirals, honeycombs and checker-boards are common themes in visual hallucinations. They are thought to originate from the neural circuitry of the primary visual cortex -- the region of the brain which processes visual shapes.

|:--:|
| ![Geometric Hallucinations](HallucinationsBillockTsou2012.png "Geometric Hallucinations") |
| *Geometric visual hallucinations.  A-D: LSD flashbacks painted by Oster (1970).  E-F: Hallucinations by THC intoxication (Siegel & Jarvik, 1975).  G: Hallucinations by occular pressure (Tyler, 1978).  H: Migraine aura (Richards, 1971). Adapted from Billock & Tsou (2012)*  |

Our collaborators at the University of New South Wales devised a method for objectively measuring the visual hallucinations seen in stroboscopic flicker. In particular, they measured the spatial wavelength and speed of illusory blobs that appear to race around a ring-shaped stimulus when it is flickered at 10-20 Hz. As part of this study, we constructed a mathematical model of the visual cortex that reproduces the perceptual behaviour.
<center>
<video src="HallucinationsFullfield.mp4" controls="controls" style="max-width: 70%;" >
</video>
</center>

Pearson J, Chiou R, Rogers S, Wicken M, Heitmann S, Ermentrout GB (2016) *Sensory dynamics of visual hallucinations in the normal population.* **eLife** Vol 5. e17072.
<br><br>

---

## Pattern formation in neural oscillators

The prevalence of synchronized neural spiking in the brain suggests a role in normal brain function. Neural synchronization can be modelled with coupled oscillators where the phase of each oscillator represents the timing of the neural spike. These models generate planar waves and spirals which resemble those observed in neural tissue.

![Generative Models](GenerativeModels.jpg "Generative Models"){: .my-image70}

Breakspear M, Heitmann S, Daffertshofer A (2010). *Generative models of cortical oscillations: Neurobiological implications of the Kuramoto model.* **Frontiers in Human Neuroscience** 4:190.

Heitmann S, Ermentrout GB (2015) *Synchrony, waves and ripple in spatially coupled Kuramoto oscillators with Mexican hat connectivity.* **Biological Cybernetics** 109:3.
<br><br>

---

## Motor commands as spatial oscillation patterns

Beta-band (15-30 Hz) neural oscillations are routinely observed in the human motor system but their purpose is unknown. We conjectured that the spatial arrangement of beta oscillations in cortex could serves as the neural substrate for encoding motor commands. We constructed a model of the descending motor system which shows how oscillatory patterns in cortex can be translated into specific muscle movements. The model demonstrates a functional role for beta oscillations that also replicates the known physiological changes of beta-band cortico-muscular coherence during movement.
<center>
<video src="CortexLimbMovie2012b.mp4" controls="controls" style="max-width: 70%;" >
</video>
</center>

Heitmann S, Boonstra T, Gong P, Breakspear M, Ermentrout GB (2015) *The rhythms of steady posture: Motor commands as spatially organized oscillation patterns.* **Neurocomputing.** Special Issue on Advances on Biological Rhythmic Pattern Generation 170.

Heitmann S, Boonstra T, Breakspear M (2013) *A dendritic mechanism for decoding traveling waves: Principles and applications to motor cortex.* **PLOS Computational Biology.**

Heitmann S, Gong P, Breakspear M (2012) *A computational role for bistability and traveling waves in motor cortex.* **Frontiers in Computational Neuroscience** 6:67.
<br><br>

---

## Co-contraction of antagonist muscles

Co-contraction refers to the simultaneous contraction of antagonist muscles. It has no impact on joint torque but it does increase joint damping because of the non-linear force-velocity properties of muscle tissue. We analysed the stability of co-contracting muscle in a simulated biomechanical limb with realistic force-length-velocity relationships. We found that co-contraction not only modulates joint damping but that it also effects postural stability. Under certain conditions, co-contracting muscles can even induce multiple stable equilibrium points.
<center>
<video src="CocontractionStability.mp4" controls="controls" style="max-width: 70%;" >
</video>
</center>

Heitmann S, Ferns N, Breakspear M (2012). *Muscle co-contraction modulates damping and joint stability in a three-link biomechanical limb.* **Frontiers in Neurorobotics** 5:5.
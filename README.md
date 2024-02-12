# Tumor Digital Twin on COMSOL

# Credit
This project has been conducted at CentraleSupélec for a semester long project in Spring 2023. It has been under the supervision of Professor Bertrand DAVID, Michael KIRKPATRICK, Cristian PUENTES for the client Institut Galien represented by Simona Mura.

# Project Contributors
Hugo HAKEM
Mathis LEROI
Octave PIGNET
Noé PRAT

# Disclaimer
This project has been conducted in France for French client and supervised by French professor. Also the Report is therefore written in French, and code details as well.


# Abstract of the Report
This report synthesizes our work on creating a digital twin of a tumoroid on a microfluidic chip. The objective is to develop a multiphysics COMSOL model of this type of chip to describe how nutrients such as oxygen and glucose diffuse within the chip and how they are consumed by the organoid. This modeling allows the study of the viability of a tumoroid on a microfluidic chip, a crucial consideration given the extended durations of laboratory tests (on the order of months).

The primary goal of a digital twin is to reduce the number of real experiments and, consequently, to minimize costs. Initially motivated by Simona Mura, our client, and our academic supervisor Bertrand David to study the impact of different drugs on the tumoroid, our work revealed the impossibility of modeling the effect of various drug treatments due to the lack of documented models based on the intrinsic properties of medications. Often, existing models are parameterized through learning systems based on experimental datasets specific to a particular drug, making them non-generalizable.

However, an alternative motivation emerged during our work - the optimization of the microfluidic chip's geometry to enhance tumoroid viability. Our literature review and discussions with the client highlighted the widespread use of a single type of chip in microfluidic experiments without a clear understanding of the rationale behind its geometry. Therefore, our digital twin facilitates the study of the influence of microfluidic chip geometry on tumoroid viability. Consequently, our project holds research significance, offering an optimal microfluidic chip geometry without the need for physical chip production.

This document provides, in a preliminary analysis, a study of an organoid on a microfluidic chip under steady-state conditions. We introduce an optimal geometry to maximize organoid viability. Subsequently, we address a study under variable conditions, covering our documentation efforts on growth laws, modeling methods, and encountered challenges.

Finally, we present improvement perspectives for future work, and accompanying this report are our models and video tutorials to facilitate a quick understanding of our research.

# Usage
- Please download Microfluidic Chip 2D (Darcy).mph
- Follow the tutorial video:
  - Note: The Tutorial_video_microfluidic_chip.mp4 has no sound.
  - Note: The Tutorial_parametrisation_french.mp4 is commented in french.
 
# Interpretation
To interpret the result obtained by the Computational modeling, please refer to the Report.pdf. Disclaimer, It has been written in French. 

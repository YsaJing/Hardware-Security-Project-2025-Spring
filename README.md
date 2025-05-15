# Hardware-Security-Project-2025-Spring

This project contains simulation of a spoofed ray attack on robot, and two modes of detection are developed (off-line and real-time) as countermeasures.
All .ipynb notebooks are included.

"Attack simulation.ipynb" explores the simulation set up of spoofed rays attack, it includes environment set up and attack simulation. The scanning results are also printed to check if the "attack" succeed.

"hardware robot countermeasure Offline.ipynb" contains the off-line detection mode of spoofed rays. And a filter of processing abnormal values is also included as the ending part.
  Notice: since the offline version works based on the saved attack simulation data (csv file), it has to be run after completely running "Attack simulation.ipynb".
"Evaluation of offline version.ipynb" is used to evaluate the performance of off-line version method.

"hardware robot countermeasure-real time.ipynb" contains the real-time detection method of spoofed rays, and it is an independent notebook contains all things needed: attack simulation, detection, evaluation. This notebook can be run directly and independently.

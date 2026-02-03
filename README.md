# Gestinfant (ongoing project)
This repository provides data and MNEPython-scripts to analyse cross-sectional analyses of fNIRS data on gesture versus manual action perception in 8-mo &amp; 24-mo infants.
Collaborators: Lucie Greco, Clément François, Judit Gervain, Isabelle Dautriche

In this project, we aim 
(i) to examine the neural basis associated with the processing of different gesture types (e.g., pointing and familiar as well as unfamiliar iconic gestures) in infancy, and 
(ii) to determine the neurodevelopmental trajectory of gesture processing during the first two years of life using a cross-sectional design.

Data: coming soon

## Stimuli
The video stimuli of gestures and matching manual actions were presented in a block format.

## Hypotheses
We hypothesise that 
(i) The processing of gesture will activate the motor cortices and social brain regions in the temporo-parietal cortices, whereas the processing of manual action will activate the motor cortices only.
(ii) These activation patterns will increase with age


## Data acquisition
We use an NIRx NIRScout 8-8 system with a source-detector separation of 3 cm and pulsated LED lights at 760 nm and 850 nm. The sources and detectors will be arranged according to the international 10–20 system in an alternating configuration, covering motor, temporo-parietal and occipetal cortices, creating 20 measurement channels covering the regions of interest. Raw intensity signals is recorded at a sampling rate of 7.81 Hz.

## Preprocessing

The fNIRS data is processed in MNE python (1.9.0) (Larson et al., 2022).
MNEPython script: coming soon

## Data analyses
The oxy-haemoglobin [HbO] and deoxy-haemoglobin [HbR] levels are preprocessed for each channel (between multiple source-detectors) for each participant during two experimental conditions: Action and Gesture. All analyses focused on comparing task-evoked fNIRS signals between two experimental conditions (“Action” vs. “Gesture”) across multiple source-detector channels and hemodynamic measures. 

## Outputs
Watch this space!

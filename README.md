# Camera-SCG-Multi-Fiducial-Marker-Detection-
This repository contains the dataset associated with the paper "**Detecting Multiple Fiducial Markers from Camera Seismocardiogram**". 

## Overview
This study proposes a novel method for multi-fiducial marker detection from camera-SCG signals recorded by a remote camera. Based on the principle of defocus speckle imaging, this method utilizes an end-to-end model to detect seven physiologically significant fiducial markers in the camera-SCG signal.

## Data Description
This dataset contains data from 17 subjects, with each participant's data collection lasting approximately 20 minutes, totaling 28,054 records. Each record contains the following components: camera-SCG, and seven fiducial markers.

**amps_MC**: Amplitude of the mitral valve closure marker.  
**local_MC**: Location of the mitral valve closure marker.

**amps_IM**: Amplitude of the isovolumetric moment.  
**local_IM**: Location of the isovolumetric moment marker.

**amps_AO**: Amplitude of the aortic valve opening marker.  
**local_AO**: Location of the aortic valve opening marker.

**amps_IC**: Amplitude of the isotonic contraction marker.  
**local_IC**: Location of the isotonic contraction marker.

**amps_RE**: Amplitude of the rapid ejection marker.  
**local_RE**: Location of the rapid ejection marker.

**amps_AC**: Amplitude of the aortic valve closure marker.  
**local_AC**: Location of the aortic valve closure marker.

**amps_MO**: Amplitude of the mitral valve opening marker.  
**local_MO**: The position of the mitral valve opening marker.

**segment**: The SCG signal.  
**local_mean**: The SCG signal after the mean.  
**first_derivative**: The first derivative of the SCG signal.  
**second_derivative**: The second derivative of the SCG signal.  
**masks**: The one-hot mask sequence of the baseline marker.  

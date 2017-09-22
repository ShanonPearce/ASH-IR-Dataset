## ASH
**ASH** (**Audio Spatialisation for Headphones**) is an impulse response dataset that can be used for binaural synthesis of spatial audio systems on headphones. It includes binaural room impulse responses (BRIRs), headphone compensation filters (HPCFs) and configuration files for Equalizer APO.

The dataset features:
* A comprehensive set of colouration-free BRIRs that have been compensated for circumaural headphones
* Individual compensation filters for over 35 headphones that can be used to equalise the listener's headphones to the diffuse field target
* A compensation filter to provide compatibility with in ear headphones
* Configuration files that can be used to convolve BRIRs and HPCFs in Equalizer APO

**Download the [latest release](https://github.com/ShanonPearce/ASH-BRIRs/releases/latest) from GitHub.**

## BRIRs
This dataset contains BRIRs derived from a range of freely available BRIR datasets. The BRIRs were measured in a wide variety of rooms each containing unique acoustical properties. So far 13 rooms have been included in the dataset. The frequency response of each BRIR has been compensated to remove sources of colouration and allow for accurate binaural synthesis of acoustic environments on headphones. The BRIRs are provided as stereo wav files sampled at 44100Hz.

## HPCFs
A set of headphone compensation filters are provided for some commonly used headphones. The filters can be used to equalise the listener’s headphones to the diffuse field target frequency response. As the BRIRs have been compensated for circumaural headphones, a filter for in ear headphone compatibility has also been provided. The filters are minimum phase FIRs and are provided as mono wav files sampled at 44100Hz. 

## Equalizer APO configuration files
This dataset can be used with [Equalizer APO](https://sourceforge.net/projects/equalizerapo/), an Audio Processing Object (APO) for windows featuring convolution capabilities. Configuration files for BRIR convolution are provided for each room in the dataset and for a range of speaker configurations. Configuration files for HPCF convolution are also provided. A configuration file can be included in your ‘config.txt’ file using the 'Include' control in the Equalizer APO configuration editor.

## License
Unless otherwise stated, all files in this repository are licensed under Creative Commons Attribution-NonCommercial-ShareAlike 4.0 https://creativecommons.org/licenses/by-nc-sa/4.0/

## Further Information
Refer to the [Wiki](https://github.com/ShanonPearce/ASH-BRIRs/wiki) for more information about the dataset.

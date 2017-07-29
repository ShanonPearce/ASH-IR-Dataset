# ASH-BRIRs
ASH is short for Audio Spatialisation for Headphones. It is an impulse response dataset that can be used for simulating spatial audio systems on headphones. It includes binaural room impulse responses (BRIRs), headphone compensation filters (HPCFs) and configuration files for Equalizer APO.

## BRIRs
This dataset contains BRIRs derived from a range of freely available BRIR datasets. The BRIRs were measured in a wide variety of rooms each containing unique acoustical properties and have been compensated for headphone use. So far 14 rooms have been included in the dataset. The BRIRs are provided as stereo wav files sampled at 44100Hz.

## HPCFs
A set of headphone compensation filters are provided for some commonly used headphones. These can be used to equalise the listener’s headphones to the diffuse field target. The filters are minimum phase FIRs and are provided as mono wav files sampled at 44100Hz. 

## Equalizer APO configuration files
The dataset can easily be used with [EqualizerAPO](https://sourceforge.net/projects/equalizerapo/), an Audio Processing Object (APO) for windows featuring convolution capabilities. Configuration files for BRIR convolution are provided for each room, speaker configuration and headphone type in the dataset. Configurations for the HPCFs are also provided. Simply include these in your ‘config.txt’ file using the configuration editor.

## License
Unless stated otherwise, all files in this repository are licensed under Creative Commons Attribution-NonCommercial-ShareAlike 4.0 https://creativecommons.org/licenses/by-nc-sa/4.0/

## Further Information
See the [enclosed documentation](https://github.com/ShanonPearce/ASH-BRIRs/blob/master/Documentation/ASH%20User%20Guide.pdf) for further information.

The **Audio Spatialisation for Headphones** (**ASH**) Impulse Response dataset is a set of impulse responses that can be used for binaural synthesis of spatial audio systems on headphones. It includes binaural room impulse responses (BRIRs), headphone compensation filters (HpCFs) and configuration files for Equalizer APO. The dataset can be used to create virtual surround sound on headphones by convolving an audio stream with a set of BRIRs.

### Features
The dataset currently features:
* A comprehensive set of compensated BRIRs
* A variety of rooms to simulate including control rooms, listening rooms, studios, and more
* A set of compensation filters that can be used to equalise a wide range of headphones to the diffuse-field target frequency response
* Configuration files that can be used to convolve BRIRs and HpCFs in Equalizer APO
* Configuration files for common speaker configurations (Stereo, 5.1 surround, 7.1 surround) and support for more configurations

### Binaural Room Impulse Responses
This dataset contains BRIRs derived from a range of freely available BRIR datasets. The BRIRs were measured using Head and Torso Simulators (HATS) in a variety of rooms, each containing unique acoustical properties. For each room, a set of BRIRs are provided for a range of source directions around the head on the horizontal plane. The frequency responses of the BRIRs have been compensated to minimise undesired spectral distortions and improve the plausibility of binaural simulations of the rooms on diffuse-field equalised headphones. The BRIRs are provided as 2 channel WAV files sampled at 44100Hz.

### Headphone Compensation Filters
A set of headphone compensation filters is provided for a wide range of commonly used headphones. The filters can be used to equalise individual headphones to the diffuse-field target frequency response. Individual headphone equalisation is recommended to minimise undesired spectral distortions from the listener's headphones and improve the plausibility of the binaural simulations. The filters are minimum phase FIRs and are provided as single channel WAV files sampled at 44100Hz. 

### Equalizer APO Configuration Files
This dataset can be used with [Equalizer APO](https://sourceforge.net/projects/equalizerapo/), an Audio Processing Object (APO) for windows featuring convolution capabilities. Configuration files for BRIR convolution are provided for each room in the dataset and for a range of speaker configurations. Configuration files for HpCF convolution are also provided. A configuration file can be included in your ‘config.txt’ file using the 'Include' control in the configuration editor. The dataset must be placed within the Equalizer APO directory for the configurations to be read.

### Latest Release
The latest release of the dataset can be downloaded from the [GitHub repository](https://github.com/ShanonPearce/ASH-IR-Dataset), in the [Releases](https://github.com/ShanonPearce/ASH-IR-Dataset/releases) page.

### License
Unless otherwise stated, all files in this repository are licensed under Creative Commons Attribution-NonCommercial-ShareAlike 4.0 https://creativecommons.org/licenses/by-nc-sa/4.0/

### Further Information
Refer to the [Wiki](https://github.com/ShanonPearce/ASH-IR-Dataset/wiki) for more information about the dataset including [configuration instructions](https://github.com/ShanonPearce/ASH-IR-Dataset/wiki/Equalizer-APO-Configuration).

[![Join the chat at https://gitter.im/ShanonPearce/ASH-IR-Dataset](https://badges.gitter.im/ShanonPearce/ASH-IR-Dataset.svg)](https://gitter.im/ShanonPearce/ASH-IR-Dataset?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

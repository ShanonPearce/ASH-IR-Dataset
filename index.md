The **Audio Spatialisation for Headphones** (**ASH**) Impulse Response Dataset is a set of impulse responses that can be used for binaural synthesis of spatial audio systems on headphones. It includes binaural room impulse responses (BRIRs), headphone compensation filters (HpCFs) and configuration files for Equalizer APO. The dataset can be used to create spatial surround sound on headphones by convolving an audio stream with a set of BRIRs and a HpCF.

### Features
The dataset currently features:
* A set of equalised binaural room impulse responses that can be used to simulate a variety of rooms including control rooms, listening rooms, seminar rooms, studios, and more
* A set of compensation filters that can be used to equalise a wide range of headphones to the diffuse-field target frequency response
* A set of configuration files for Equalizer APO that can be used to simulate common speaker configurations (Stereo, 5.1 surround, 7.1 surround) within the rooms

### Binaural Room Impulse Responses
The dataset includes a set of BRIRs that were derived from a range of freely available BRIR datasets. The BRIRs were measured using head and torso simulators (HATS) in a variety of reverberant rooms, each containing unique acoustical properties. For each room, a set of BRIRs are provided for a range of source directions around the head on the horizontal plane. The BRIRs have been equalised to remove undesired spectral colouration and to make the BRIRs compatible with diffuse-field equalised headphones. The BRIRs are provided as 2 channel WAV files with a sampling rate of 44100Hz.

### Headphone Compensation Filters
The dataset also includes compensation filters for a wide range of commonly used headphones. The filters can be used to equalise individual headphones to the diffuse-field target frequency response. Individual headphone equalisation is recommended to compensate for undesired spectral colouration introduced by the listener's headphones and to improve the plausibility of the binaural simulations. The filters are provided as single channel WAV files with a sampling rate of 44100Hz. Magnitude response plots of the filters are also provided.

### Equalizer APO Configuration Files
This dataset can be used with [Equalizer APO](https://sourceforge.net/projects/equalizerapo/), an Audio Processing Object (APO) for windows featuring convolution capabilities. Configuration files for BRIR convolution are provided for each room in the dataset and for a range of speaker configurations. Configuration files for HpCF convolution are also provided. A configuration file can be included in your ‘config.txt’ file using the 'Include' control in the configuration editor. The dataset must be placed within the Equalizer APO directory for the configurations to be read.

### Latest Release
The latest release of the dataset can be downloaded from the [GitHub repository](https://github.com/ShanonPearce/ASH-IR-Dataset/releases/latest) or the [Zenodo repository.](https://zenodo.org/record/3245009)

### License
Unless otherwise stated, all files in this repository are licensed under Creative Commons Attribution-NonCommercial-ShareAlike 4.0 https://creativecommons.org/licenses/by-nc-sa/4.0/

### Further Information
Refer to the [Wiki](https://github.com/ShanonPearce/ASH-IR-Dataset/wiki) for more information about the dataset including [configuration instructions](https://github.com/ShanonPearce/ASH-IR-Dataset/wiki/Equalizer-APO-Configuration).


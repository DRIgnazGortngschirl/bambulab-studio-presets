![Presets](https://img.shields.io/github/directory-file-count/DRIgnazGortngschirl/bambulab-studio-orca-slicer-presets/filament?type=file&extension=json&label=Filament%20presets%20in%20collection)
![](https://img.shields.io/github/last-commit/DRIgnazGortngschirl/bambulab-studio-orca-slicer-presets?label=Last%20Updated)
![](https://img.shields.io/github/contributors/DRIgnazGortngschirl/bambulab-studio-orca-slicer-presets?label=Contributors)

# Bambu Studio <img src="https://wiki.bambulab.com/admin/home/logo-large.png" width="26"> / Orca Slicer Presets <img src="https://github.com/SoftFever/OrcaSlicer/blob/main/resources/images/OrcaSlicer_192px_transparent.png" width="24">

Welcome to the Bambu Studio / Orca Slicer Presets repository! This repository is dedicated to storing / collecting presets that have been meticulously crafted and optimized for use in 3D printing and slicing applications. Whether you're a 3D printing enthusiast, engineer, or designer, our collection of presets aims to simplify your workflow and elevate your 3D printing experience.

<img src="https://github.com/DRIgnazGortngschirl/bambulab-studio-orca-slicer-presets/blob/main/REPO-MEDIA/bambulab-studio-orca-slicer-presets-init-view.gif" width="50%">

## Features

 * A growing collection of presets for the Bambu Studio / Orca Slicer slicer.
 * Presets are meticulously optimized for quality and print performance.
 * Regular updates and additions to the preset library.
 * Community-driven contributions and improvements.

# Getting Started
 1. 🔍 Explore the presets: Browse through the preset categories (Machine, Filament and Process) and select the ones that match your 3D printing needs.
 2. 📈 Optimize your prints: Use the presets to optimize your 3D printing settings for superior print quality and efficiency.
 3. 📥 Import Presets: Import the chosen presets into your 3D slicer software by downloading the repository and dropping them into the folder respective preset folders.

Inductions can be found here for [importing presets](https://github.com/DRIgnazGortngschirl/bambulab-studio-orca-slicer-presets/blob/main/REPO-MEDIA/presets-import.gif ) and [show hidden files](https://github.com/DRIgnazGortngschirl/bambulab-studio-orca-slicer-presets/blob/main/REPO-MEDIA/show-hidden-files.gif) to easily access the AppData Folder on Windows.

> [!CAUTION]
> Also make sure to place place also the inherited presets inside the folder "[main/filament\/inherits](https://github.com/DRIgnazGortngschirl/bambulab-studio-orca-slicer-presets/tree/main/filament/inherits)" inside the respective preset folders, otherwise some presets which are based on other "presets" will not work!


## For Orca Slicer
📁 Full Path: 
```
C:\Users\%USERNAME%\AppData\Roaming\OrcaSlicer\user\[NUMBER]
or
C:\Users\%USERNAME%\AppData\Roaming\OrcaSlicer\system\BBL\filament
```  
📁 Relative Path: 
```
%AppData%\Roaming\OrcaSlicer\user\[NUMBER]
or
%AppData%\Roaming\OrcaSlicer\system\BBL\filament
```


## For Bambu Studio
📁 Full Path: 
```
C:\Users\%USERNAME%\AppData\Roaming\BambuStudio\user\[NUMBER]
or
C:\Users\%USERNAME%\AppData\Roaming\BambuStudio\system\BBL\filament
```
📁 Relative Path: 
```
%AppData%\Roaming\BambuStudio\user\[NUMBER]
or
%AppData%\Roaming\BambuStudio\system\BBL\filament
```

# Contributing
Feel free to fork the repo, submit your own presets, or enhance existing ones. Every contribution helps the community optimize their 3D printing experience!

## Filament Presets

> [!NOTE]
> Make sure whenever you have done a calibration, select the profile before continuing with the next calibration, as selecting a default profile will not result in the best preset for all calibration methods.

### Bambu Studio <img src="https://wiki.bambulab.com/admin/home/logo-large.png" width="17">
For the best results, please follow these instructions step by step.

 1. Begin with the "Flow Dynamics Calibration" steps provided in this official guide https://wiki.bambulab.com/en/software/bambu-studio/calibration_pa
 2. Use the auto calibration mode first, if that one does not successfully finish, please skip to step 4.
 3. Continue with auto-calibration mode for "Flow Rate Calibration" https://wiki.bambulab.com/en/software/bambu-studio/calibration_flow_rate
 4. Now to create a preset as optimized as possible again run a manual check with Manual mode in Flow Dynamics Calibration
 5. So do the same manual calibration for the "Flow Rate Calibration".


### Orca Slicer <img src="https://github.com/SoftFever/OrcaSlicer/blob/main/resources/images/OrcaSlicer_192px_transparent.png" width="15">
For the best results, please follow these instructions step by step.

1. Begin with the "Flow Rate Calibration" steps provided in this official guide: https://github.com/SoftFever/OrcaSlicer/wiki/Calibration#flow-rate
2. Also, the line method is highly recommended to finetune the Pressure Advance: https://github.com/SoftFever/OrcaSlicer/wiki/Calibration#pressure-advance 
3. Continue with the "Flow Dynamics Calibration" steps provided in this guide https://wiki.bambulab.com/en/software/bambu-studio/calibration_pa
4. For refined overhangs or bridging, the "Temperature Tower" just finds the perfect spot for the hotend. Please run this with the recommended temperature range of the manufacturer.  https://github.com/SoftFever/OrcaSlicer/wiki/Calibration#Temp-tower
5. (optional) To get the "Maximum Volumetric Speed" for each filament, you can run through the steps at https://github.com/SoftFever/OrcaSlicer/wiki/Calibration#max-volumetric-speed and determine the "Maximum Volumetric Speed". This would help limit the max speed / volumetric extrusion for the filament.

#### To-Do
- [x] GIFs for docu on importing presets
- [ ] More Presets

# Star History
Thank you all so much for over 100 stars! When I first started, my goal was simply to gather a few presets to speed up printing and benefit from presets that were already fine-tuned. Your support has truly exceeded my expectations!
<a href="https://star-history.com/#DRIgnazGortngschirl/bambulab-studio-orca-slicer-presets&Date">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=DRIgnazGortngschirl/bambulab-studio-orca-slicer-presets&type=Date&theme=dark" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=DRIgnazGortngschirl/bambulab-studio-orca-slicer-presets&type=Date" />
   <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=DRIgnazGortngschirl/bambulab-studio-orca-slicer-presets&type=Date" />
 </picture>
</a>

# Interactive Gaze Driven Animation of the Eye Region
##### Proceedings of the 21st International Conference on 3D Web Technology (Web3D '16, Best Paper Award)
Debanga R. Neog, Joao L. Cardoso , Anurag Ranjan, Dinesh K. Pai, 
Sensorimotor Systems Laboratory, University of British Columbia

<img style="float: right;" src="http://www.cs.ubc.ca/research/eyemoveweb3d16/teaser.PNG">
We describe a complete pipeline to model skin deformation around the eyes as a function of gaze and expression parameters. The face is rendered with our WebGL application in real-time and runs in most modern browsers (a) and mobile devices (b). An example of automatic facial animation generation while watching a hockey video is shown (c-d). The character starts watching the match with a neutral expression (c) and gets concerned when a goal is scored (d). Eye movements were generated automatically using salient points computed from the hockey video.

### Abstract
We propose a system for real-time animation of eyes that can be interactively controlled in a WebGL enabled device using a small number of animation parameters, including gaze. These animation parameters can be obtained using traditional keyframed animation curves, measured from an actor’s performance using off-the-shelf eye tracking methods, or estimated from the scene observed by the character, using behavioral models of human vision. We present a model of eye movement, that includes not only movement of the globes, but also of the eyelids and other soft tissues in the eye region. The model includes formation of expression wrinkles in soft tissues. To our knowlwdge this is the first system for real-time animation of soft tissue movement around the eyes based on gaze input.

## App is available in the following links  	
- [Desktop App](http://www.cs.ubc.ca/research/eyemoveweb3d16//webapp/desktop.html) 
- [Mobile App](http://www.cs.ubc.ca/research/eyemoveweb3d16//webapp/mobile.html) 

## The paper and supplimentary video available here:
- [Paper](http://www.cs.ubc.ca/research/eyemoveweb3d16/Interactive%20Gaze%20Driven%20Animation%20of%20the%20Eye%20Region.pdf)
- [Video](http://www.cs.ubc.ca/research/eyemoveweb3d16/Interactive_gaze_drive_animation_of_eyes.mov)

### Citation
```
Bibtex	@inproceedings{Neog:2016:IGD:2945292.2945298, 
author = {Neog, Debanga R. and Cardoso, Jo\~{a}o L. and Ranjan, Anurag and Pai, Dinesh K.},
title = {Interactive Gaze Driven Animation of the Eye Region},
booktitle = {Proceedings of the 21st International Conference on Web3D Technology},
series = {Web3D '16},
year = {2016},
isbn = {978-1-4503-4428-9},
location = {Anaheim, California},
pages = {51--59},
numpages = {9},
url = {http://doi.acm.org/10.1145/2945292.2945298},
doi = {10.1145/2945292.2945298},
acmid = {2945298},
publisher = {ACM},
address = {New York, NY, USA},
keywords = {WebGL, eyes, gaze, human animation, soft tissue},
}
```

### Acknowledgement
- Web App	made using [Three.js](http://threejs.org/) and [dat.gui](https://github.com/dataarts/dat.gui)
- Mesh and textures from the [Wikihuman Project](http://gl.ict.usc.edu/Research/DigitalEmily2/) and Infinite Realities](http://ir-ltd.net/)
- Eye shader based on work of [Artur Vill](http://www.vill.ee/eye/)
- Screen space subsurface scattering as in [Separable Subsurface Scattering ](http://www.iryoku.com/separable-sss/)
- Uses Separable SSS. Copyright (C) 2012 by Jorge Jimenez and Diego Gutierrez.
- Environment texture from [hdrlabs.com](http://hdrlabs.com/)

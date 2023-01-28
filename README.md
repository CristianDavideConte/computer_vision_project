# Computer Vision and Image Processing M project
***Goal:***
Students should develop a software system aimed at creating an Augmented Reality (AR) video.

***Characteristics of the video sequence:*** The original **video** sequence, i.e. Multiple View.avi, **depicts the well-known book “Multiple View
Geometry in Computer Vision”**, by Richard Hartley and Andrew Zissermann, as **seen by a moving
camera**. Initially, camera trajectory is a slow translation, followed then by rotations and slow as well
as rapid brightness changes. 

***Functional specifications:*** 
Given the input video, students should **superimpose an augmented reality layer onto the book cover**
as realistically as possible, so that, ideally, when watching the augmented video one would perceive
the overlaid graphics as real items present in the book cover. Purposely, the **colour artefacts**
appearing when superimposing the graphics layer **should be eliminated.**

***Input Data:***
The augmented reality system should process the following input data:
- Input video sequence to be augmented: Multiple View.avi
- Reference frame (first frame of the input sequence): ReferenceFrame.png
- Binary mask that identifies the pixels belonging to the book in the reference frame:
ObjectMask.png
- Image containing the augmented reality layer, made out of the CVLab logo and a different
list of authors (i.e. Richard Hartley and Andrew Zissermann and Pietro Azzari) together
with the associated binary mask: AugmentedLayer.png, AugmentedLayerMask.png

***Output Data:***
The developed software system should produce the following output data:
- A video sequence, referred to here as "Augmented Multiple View.avi", containing realistic
superimposition of the augmented reality layer onto the input video sequence. 

Solutions proposed by Cristian Davide Conte

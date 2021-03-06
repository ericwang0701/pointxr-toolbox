
# PointXR toolbox


In this repository, we release the **PointXR toolbox**. A software that is built in Unity for rendering and visualization of 3D point clouds in virtual environments, as part of the [**PointXR**](https://www.epfl.ch/labs/mmspg/downloads/pointxr/) [1]. The toolbox consists of a set of 3D Unity scenes, developed to: (a) adjust the visual appearance of point clouds by enabling different rendering configurations, and (b) host experiments under variants of interactive and passive evaluation protocols.

In particular, the toolbox consists of 4 different scenes that can operate independently:

 1. Rendering: Scene for interactive configuration of the visual appearance of a model through a Graphical User Interface. The rendering pipeline depends on the default [Pcx point cloud importer and renderer for Unity](https://github.com/keijiro/Pcx), which is enhanced with: (i) adaptive point size mode, (ii) square shader, and (iii) shader interpolation.
 2. Inspection: Scene for the selection of the preferred subjective evaluation protocol (e.g., single stimulus, double stimulus) and variant (e.g., simultaneous, sequential). Additional options, such as model rating, or recording the observer's interactions can be enabled or disabled.  
 3. Rating: Scene for configuration of the rating panel and the grading scale. The questions and answers that are shown to the observers can be specified.
 4. Capturing: Scene for producing videos using a virtual camera that captures the model from pre-defined paths (to be released soon).

![alt text](/docs/screenshot.png)
*\*Example of the toolbox scene for adjusting the rendering configurations of a model. The depicted point cloud is part of the [**PointXR dataset**](https://www.epfl.ch/labs/mmspg/downloads/pointxr/) (original model source: [link](https://sketchfab.com/3d-models/hawaiian-tiki-3dscan-022f006c8ef647818d754195f02cb61f), creator: [Thomas Flynn](https://sketchfab.com/nebulousflynn), license: [CC Attribution](https://creativecommons.org/licenses/by/4.0/)).*


### Dependencies

The [Pcx point cloud importer and renderer for Unity](https://github.com/keijiro/Pcx) is a dependency, which is coming together with the PointXR toolbox.


### System requirements

The software is built and developed in Unity 2019.3 on Windows 10. It has not been extensively tested with other Unity versions. In case you face issues with your current version, [Unity Hub](https://docs.unity3d.com/Manual/GettingStartedInstallingHub.html) might come in handy.


### Application

The **PointXR toolbox** was developed in the framework of [1], in addition to the generation of the **PointXR dataset**, and the **PointXR experimental data**. In the latter, we combine the use of the software and the dataset in a subjective quality evaluation study allowing 6 degrees of freedom interactions in Virtual Reality using double-stimulus protocol variants. For more information regarding the experiment, the models, and the rendering configurations, the reader can refer to [1].


### Conditions of use

If you wish to use this software in your research, we kindly ask you to cite [1].


### References

[1] E. Alexiou, N. Yang and T. Ebrahimi, "[PointXR: A Toolbox for Visualization and Subjective Evaluation of Point Clouds in Virtual Reality](https://infoscience.epfl.ch/record/277378)," *2020 Twelfth International Conference on Quality of Multimedia Experience (QoMEX)*, Athlone, Ireland, 2020, pp. 1-6. doi: [10.1109/QoMEX48832.2020.9123121](https://doi.org/10.1109/QoMEX48832.2020.9123121)

IMHOTEP
===========================================================================

[IMHOTEP (Immersive Medical Hands-On Operation Teaching and Planning System)](http://imhotep-medical.org) is a
Virtual Reality (VR) framework used for visualizing medical data.
It is compatible with the [Oculus Rift](https://www.oculus.com) and the [HTC Vive](https://www.vive.com).
The software is being developed by the [Institute for Anthropomatics and Robotics](http://his.anthropomatik.kit.edu/english/index.php)
at the Karlsruhe Insitute of Technology (KIT), Karlsruhe, in association with the
[Department of General, Abdominal and Transplant Surgery, Heidelberg University Hospital](https://www.heidelberg-university-hospital.com).
Using the VR technology, it can be used to visualize 3D models, 2D medical images and additional information.
The framework can be applied for research purposes in the areas of visualization, simulation, planning and teaching.


Disclaimer:
---------------
This Software is provided "as is", without warranty of any kind. It is not a medical product and is only intended
for research purposes. Use at your own risk. See Licenses/IMHOTEP.txt for further
details.

License:
---------------
The source code in this project is licensed under the BSD License (see Licenses/IMHOTEP.txt). The project uses
various third-party plugins and assets, a list of which can be seen in ThirdParty.md. Their licenses are in the
"Licenses" subfolder.

Features:
---------------
- Load and display segmented 3D models
- Load display 2D MRI/CT images in DICOM format
- Display case-specific additional information (med. indication, case history, ...)
- Supports Occulus Rift and HTC Vive
- Intuitive interaction using HTC Vive controllers or Mouse
- 3D User-Interface to maximize workspace
- 3D/2D Annotation System
- Predefined views and orientations of the models

Usage:
---------------
To run the project, you need a VR Headset (HTC Vive is recommended, although the framework will also work with an
Oculus Rift), Unity3D (tested with Version 2017.1) and Blender3D. Set up your VR Headset, then download this project
and load it using the Unity3D editor. In the Assets Folder, load the "Workstation" scene and then run the project.
The visualization data is not included in the source code. If you want to use the software and get an example set of
visualization data, please [contact us](http://imhotep-medical.org/contact).

Documentation:
---------------
The IMHOTEP project is intended to be used as a framework and many of the framework's functions are documented.
To generate the documentation, download "Doxygen". Then use the Doxyfile in the project's root directory to
generate the documentation.
For example, on Linux, run: 'doxygen Doxyfile'. You can then load the file Documentation/html/index.html.

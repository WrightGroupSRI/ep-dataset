# Sunnybrook Preclinical Simulated Cardiac EP Dataset

This dataset contains preclinical cardiac MR images, a left ventricle segmentation, and simulated electrophysiology points.

See LICENSE or license.pdf for details on using or sharing this dataset.

The dataset contains the following files and folders:
 - **scene**: a scene containing the objects below except for the electrophysiology points. This can be used to quickly load the objects using the *Scene/Load Scene* menu item in Vurtigo and selecting this directory.
 - **E774S5-shortAxis**: short-axis cine DICOM MRI stack. Load this into Vurtigo by selecting this directory from the DICOM database manager Import dialog.
 - **lvContours**: inner and outer contours of the left ventricle obtained by segmenting the E774S5-shortAxis dicoms. Load this into Vurtigo from the second page of the EP Plugin in the Plugin Browser.
 - **E774S6-longAxis**: long-axis cine DICOM MRI stack. Load this into Vurtigo by selecting this directory from the DICOM database manager Import dialog.
 - **epPoints.csv**: simulated electrophysiology points with LAT (local activation time) and Voltage measurements. Load this into Vurtigo using the Load button in the Catheter History object.

View the EP Plugin chapter of Vurtigo using the *Help/Contents* menu item to find out how to adjust and paint left ventricle mesh.

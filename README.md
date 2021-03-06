# FTIR_fittingtool_v2.53
The second generation of FTIR data fitting tool. 

The program uses the knowledge of thin film filters which studied the physics behind EM waves propagating inside an optical system. 
The influence on the EM wave by each layer is represented using an optical transfer matrix (characteristic matrix).  
For example: H.A. Macleod, Thin-Film Optical Filters(1969), chapter2. 

System requirement: 

Mac OS/ Windows / Linux (Not tested)

python 3.4 +

The following packages need to be installed before running the program: 

matplotlib, numpy. 

How to run it: 

Download the whole package to local, and then run "FTIR_fittingtool_2_class.py". 

For any questions, please contact pman3@uic.edu.

© 1, 2018 Peihong Man. 

Special Thanks: Dr. Yong Chang. 


Update log: 

v2.53:

Added live graph for "Show Trans" function. 

Added live graph for "Fit Trans" function. 

Added live graph for "Cal a" function. 

v2.52:

Now the program can fit the cutoff curve. See help file for details. 

Now the MCT absorption calculation function is T-dependent. 

Optimized UI buttons. 

Added new layer structure: VLWIR SL.

v2.51:

Added T-dependent refractive index for ZnSe, BaF2 and Ge.

Now one can calculate absorption coefficient for multiple absorption layers. 

Optimized UI for Windows.

Fixed a bug where the default preload structure cannot be loaded.

v2.50:

Temperature is introduced into the fitting tool. Added temperature in "settings".

Added material data fro Si3N4, air. 

Added one more substrate option: Air. 

Extended the total number of layers can be added from 16 to 22. 

Modified "Clear" function. 

Modified "Calculate absorption" function. 

Modified "Calculate MCT absorption" function. 

Added function to prevent two structures stack together. 

Toolbar buttons are optimized to fit in more function buttons. 

Now the newest added layer will shw on top instead of bottom. 
    
v2.40:

Added material data for ZnSe, BaF2, Ge and ZnS for FPI project.

Added settings function.

Added saveresult function.



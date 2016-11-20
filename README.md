# EclipseRocketryModelingFramework
MATLAB/Simulink modeling framework for rocket and payload designs

11/19/2016 Updates
- Fleshed out module interfacing between AERO, EOM, and full simulation blocks.
	- AERO blocks only need to supply force coefficients
	- ATM block provides dyamic pressure to calculate various aerodynamic forces
	- EOM updated to proper library format
- Begun process of cleaning up AERO blocks
- To-Do for next time:
	- Decide implementation of combined Yaw and Pitch effects... Can superimpose, or not?
	- Re-structure AERO block to better organize IO layout?
	- Create setup files for new EOM module and update other modules
	- Begin prepping for payload model.
	
Validation of zCFD code using the Second High Lift Prediction Workshop
======================================================================

Internal report
A.	Cimpoeru (CFMS), J. Appa and D. Standingford (Zenotech)

November 2014

Abstract
--------
This document summarizes some initial results obtained within the second order benchmarking of a new CFD software. The zCFD code was used for the DLR F11 high lift configuration in order to compute the flow field using the k- ω SST turbulence model. The results consist in high Reynolds number computations for the simplified (CASE 1) respectively complex (CASE 2B) configurations at 7o angle of attack. The results were validated against the numerical solutions obtained using CFD++ and ANSYS FLUENT and showed a good agreement with the experimental data.

Introduction
------------
The zCFD code is a GPU accelerated high performance computational fluid dynamic software. The zCFD solver is an unstructured cell centered finite volume code which solves explicitly the compressible Navier-Stokes equations. The solution is preconditioned and the convergence is accelerated using the Multigrid technique along with a dual time stepping method. 
The results consist in high Reynolds number computations using  k- ω SST turbulence model for  the simplified (CASE 1) respectively complex (CASE 2B) configurations at 7o angle of attack. The zCFD solutions were compared with wind tunnel data and other CFD codes such as CFD++ and Ansys FLUENT. These codes were selected since they use the same cell-centered approach in combination with k- ω SST model. 


DLR F11 High Lift Configuration; Locations of Pressure Sections. For the full definition of cutting planes refer to workshop website.

.. figure:: images/high-lift-stations.png
	:width: 75%
	:align: center
	:alt: alternate text
	:figclass: align-center

	High lift stations
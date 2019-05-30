Preprocessing
-------------

Program
-------

|              |          							|		    						|
| :------      | :-----   							| :-----  							|
| 12:00--12:20 | [Quality assurance](mne-report.ipynb) 	| How to do scalable quality assurance |
| 12:20--12:40 | [Filtering](filtering.ipynb)   				| Filtering the data             	|
| 12:40--13:10 | [Autoreject](autoreject.ipynb)		    | Removing sensor artifacts in data
| 13:00--13:30 | [SSP](ssp.ipynb)   						| Signal Space Projection         |
| 13:30--14:00 | [ICA](ica.ipynb)       					| Independent Component Analysis  |

Quality assurance
=================

We will see how to use the MNE report to generate figures for
quality assurance when analyzing tens of hundreds of subjects. We will
also look at how to parallelize the analysis.

Filtering
=========

A brief look at the filtering options available in MNE Python

Autoreject
==========

Sometimes, sensors can be bad due to loose contact or
flux jumps. Autoreject is an automated method to label
and repair artifacts in the data.

Spatial filtering
=================

Physiological artifacts that are not related to brain
rhythms such as heart beats and eyeblinks have prototypical
spatial signatures. They can be removed using
Signal Space Projection (SSP.ipynb) or Independant Component
Analysis (ICA.ipynb).

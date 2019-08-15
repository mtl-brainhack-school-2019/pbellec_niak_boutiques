# pbellec_niak_boutiques

## Who I am?

I am a researcher at University of Montreal, and one of the organizer of the brainhack school. Each year, I start a project at brainhack school. In general, I don't get to do much on it, because I am busy with other things. But I keep trying. 

## Background

I have been the lead developper of a tool called [Neuroimaging Analysis Kit](http://niak.simexp-lab.org) which includes a few pipelienes for fMRI data processing. The preprocessing pipeline in particular is quite useful. Two main strength of that package: tt's based on Octave and the minc tools, with very liberal licenses, allowing for commercial use (MIT and BSD-like). It's also quite robust, and it's possible to reach high success rate on most datasets with minimum tweaking, and the necessary tweaking is relatively well documented. NIAK was included in the [BIDS-app catalogue](https://bids-apps.neuroimaging.io/) and the [CBRAIN portal](https://portal.cbrain.mcgill.ca/login), but these implementations were not actively maintained and tested. They are, at that point, broken. Support for BIDS in NIAK is also broken. Despite that, n

## Objectives of the project
I'd like to use the new [boutiques standard](https://boutiques.github.io/) to create a command-line version of niak, which is going to be compatible with the BIDS standard. I would then want to register a new NIAK-fmri-preprocessing pipeline as a BIDS app and also on the CBRAIN portal. 

## Tools I want to learn

  * Boutiques for wrapping tools
  * pybids to parse BIDS datasets
  * Use Boutiques to generate a BIDS app
  * Use Boutiques to generate a CBRAIN app
  
## Deliverables 
  * A new niak release
  * An octave/matlab interface to pybids
  * A (working) BIDS app
  * A (working) CBRAIN app
  
## Communication
  * Update NIAK website
  * twitter thread

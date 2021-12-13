# Brain Imaging Accessoires: Toolkit of Radiological Assessment of Multiple Sclerosis (TokioRAMS)

Everyday CT or MR examinations are supposed to be acquired in the same fashion, but slight deviations (e.g. due to subject/patient movement, differences in planning standards for MR and CT, or improper planning) may result in not easily comparable images. The fully automatic tilting of brainscans to Anterior Commissure - Posterior Commissure (fatbACPC) tool is meant to align CT and MR scans to the [ACPC](https://radiopaedia.org/articles/anterior-commissure-posterior-commissure-line) line to yield easily comparable images.

TokioRAMS is meant to be used as a submodule of [BrainSTEM](https://github.com/BrainImAccs/BrainSTEM).

Please note, this software is research-only and must not be used for clinical decisions/diagnosis.

# Details



# Installation

We recommend installing TokioRAMS using Docker. The container will expose a DICOM listener, which will accept brain images.

The results will be sent back to a DICOM node. For testing, you can for example use [Horos](https://horosproject.org) (on a Mac) to send and receive DICOM files.

# Acknowledgements

Please see [templates/README.md](https://github.com/brainimaccs/fatbACPC/blob/master/templates/README.md) for information on the templates.

The main scripts are based on the [BASH3 Boilerplate](http://bash3boilerplate.sh).

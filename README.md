# CleanTheBrain

Browser-based noise removal of brain data

<img src="https://layerfmri.files.wordpress.com/2021/02/browser_based_brain_cleaning-01.png"  width="450" align="right" />

Author: DaVinci, L. 

CleanTheBrain is an open-source browser-based analysis tool to remove unwanted signals in brain imaging data.
Virtually all brain imaging data are limited by unwanted signal sources (a.k.a. noise). Here, we present an analysis software, CleanTheBrain, which can apply powerful noise cleaning tools on brain imaging data for a number of neuroimaging modalities. The cleaning engine decomposes the brain data and then filters all signal components that do not match features of neurally driven activity. As such, CleanTheBrain removes physiological noise, signal/image artefacts, and it works particularly well to remove random thermal noise. The techniques that are implemented in CleanTheBrain are documented elsewhere (see https://github.com/cleanthebrain); what we provide here is the implementation of a streamlined, easy-to-use tool that has been extensively tested on a variety of datasets.
The code has been tested and validated on structural MRI, functional MRI (1,2) and EEG (3). The code is well documented and written to be easily readable and editable by the users. It can be freely and anonymously used under the GNU (GPL-3.0) license. It runs in any web browser of all operating platforms and mobile devices, and has dependencies to HTML4 (or higher). User instructions with tutorials and example data to test the tool are available on https://github.com/cleanthebrain/cleanthebrain. The code is version controlled and long term supported. Users are invited to report bugs and request features via https://github.com/cleanthebrain/cleanthebrain/issues. 

# References:

- Brodman K. et al. The BIG dataset. Aperture, 1: 52–59 (2020).
- Galileo G. On functional MRI: a critical review, Research, 8:10-14 (1977).
- Cajal R. Brain signals and their meaning. Scientific innovations, 14:68–78 (2000).

# AquaResp
Automating Aquatic Respirometry. Focused on automating intermittent respirometry experiments for aquatic animals.

See <a href = "http:\\www.aquaresp.com" target="_blank">aquaresp.com</a> for more information 

The GUI and code controlling of the experiment, and the code calculating the results are licensed under Creative Commons BY-SA.

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.

Please cite the code when using the software

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.2584015.svg)](https://doi.org/10.5281/zenodo.2584015)

Cite as:
Morten Bo Søndergaard Svendsen, Peter G. Bushnell, & John Fleng Steffensen. (2019, March 5). AquaResp 3 (Version V3.0). Zenodo. http://doi.org/10.5281/zenodo.2584015

## Installation
The present version is only supported on Windows 10 64 bit.

Download Aquaresp by pressing "Clone or Download" button in the top right corner of this screen. 

### Windows 10 - 64bit:

#### Step 1 - downloading Python
##### First run 1.vbs in the Installation folder
This downloads Python for you, the version that has been used for testing (3.7.4. - 64-bit)

#### Step 2 - installing Python and libraries
##### Run 2.bat
This initiates  Python installation for you.

If this fails, open the downloaded Python (InstallPython.exe), and make sure to enable the option "Add to PATH" during the first step of installation

#### After Python has been installed
##### Double click the CheckLibraries.py in the installation folder.
This installs the libraries needed to run AquaResp 3.0 ASAP
The buttons will change to green and display "OK" when libraries are installed.


####Further:
We recommend setting either Mozilla Firefox or Google Chrome webbrowsers as default browser in Windows. The plotting feature does not work in Internet Explorer or Microsoft Edge browsers.

---
If this step is failing, open the command prompt (WinButton + R, write "cmd", and press enter), and run the installation commands for the specific library. The following are needed for AQ3

python -m pip install bokeh==1.3.0

python -m pip install numpy

python -m pip install scipy

python -m pip install matplotlib

python -m pip install -U wxPython

python -m pip install mcculw

--

#### Step 3 - adding Icons to your desktop
##### Run Create Links on Desktop.vbs  (in the Aquaresp 3 main folder)
This creates icons on the desktop. You can do that manually aswell.



## Acknowledgements

Thank you to <a href = "https://www1.bio.ku.dk/english/staff/?pure=en/persons/158364">Bent Vismann</a> for testing of AquaResp and inputs on usage of AquaResp for invertebrates.

Thank you to <a href = "https://www.researchgate.net/profile/Denis_Chabot">Denis Chabot</a> for testing of AquaResp over many occasions and providing inputs on usage of AquaResp.

Thank you to <a href = "https://www.researchgate.net/profile/Heidrikur_Bergsson3">Heiðrikur Bergsson</a> for testing and using AquaResp.

Thank you to <a href = "http://saltnfish.dk/cv/">Emil Aputsiaq Christensen</a> for providing valuable usability input.

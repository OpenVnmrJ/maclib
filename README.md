# fpi
 fpi - Report integral values from arrayed spectra (in analogy to the "fp"
 command)

 Copyright 2016 University of Oregon

 Licensed under the Apache License, Version 2.0 (the "License");
 you may not use this file except in compliance with the License.
 You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

 Unless required by applicable law or agreed to in writing, software
 distributed under the License is distributed on an "AS IS" BASIS,
 WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 See the License for the specific language governing permissions and
 limitations under the License.

                                SUBMISSION FORM

Submitter:      Rolf Kyburz, Agilent Technologies
Date submitted: 1996-04-17
                2003-03-20 - rk, integration limits in ppm or Hz
                2003-11-04 - rk, fixed 2 typos in macro
                2003-11-06 - rk, optional output for T1/T2 analysis
                2008-06-23 - rk, adjusted "sort" calls for Linux

File name:      fpi
Directory:      maclib
Description:    Report integral values from arrayed spectra (in analogy to
                the "fp" command)

Related files:  manual/fpi

Existing VnmrJ / VNMR files which are superseded or
otherwise affected by this submission:  none
Hardware configuration limitations:     n.a.
Known software version compatibility:   VNMR 5.1 - 6.1C, VnmrJ 1.1C - 2.2C

**This software has not been tested on OpenVnmrJ. Use at your own risk.**

To install this user contribution:  
Download the repository from GitHub and checkout the tag of the contribution you want.
Typically tags end in the version (e.g. -v1.0)

     git clone https://github.com/OpenVnmrJ/maclib  
     cd maclib  
     git checkout fpi-v1.0


You may also download the archive directly from github at

    https://github.com/OpenVnmrJ/maclib/archive/fpi-v1.0.zip

Read fpi.README for installation instructions.

In most cases, move the contribution to /vnmr/userlib/maclib 
then use extract to install the contribution:  

    extract maclib/fpi
# fpdc
 fpdc - Does "fp" with dc correction on the individual traces

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
Date submitted: 1993-08-23 (original submission by Steve Patt, Varian)
                1999-04-12 r.k. - now uses "npoint" the same way as "fp"

File name:      fpdc
Directory:      maclib
Description:    Does "fp" with dc correction on the individual traces

Related files:  manual/fpdc

Existing VnmrJ / VNMR files which are superseded or
otherwise affected by this submission:  none
Hardware configuration limitations:     none
Known software version compatibility:   All
Known OS version compatibility:         All

**This software has not been tested on OpenVnmrJ. Use at your own risk.**

To install this user contribution:  
Download the repository from GitHub and checkout the tag of the contribution you want.
Typically tags end in the version (e.g. -v1.0)

     git clone https://github.com/OpenVnmrJ/maclib  
     cd maclib  
     git checkout fpdc-v1.0


You may also download the archive directly from github at

    https://github.com/OpenVnmrJ/maclib/archive/fpdc-v1.0.zip

Read fpdc.README for installation instructions.

In most cases, move the contribution to /vnmr/userlib/maclib 
then use extract to install the contribution:  

    extract maclib/fpdc
# zoomplot2d
 zoomplot2d - Create a full size plot of a COSY-type 2D spectrum where the
 noise is
 left out, and the areas which can have signals are blown up (zoomed)
 accordingly.

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
Date submitted: 2004-04-01 (from the earlier "packages/adv2d" contribution)

File name:      zoomplot2d
Directory:      maclib
Description:    Create a full size plot of a COSY-type 2D spectrum where the
                noise is left out, and the areas which can have signals are
                blown up (zoomed) accordingly.

Related files:  maclib/zoomplot2d       manual/zoomplot2d

Existing VnmrJ / VNMR files which are superseded or
otherwise affected by this submission:  none
Hardware configuration limitations:     none
Known software version compatibility:   VNMR 6.1C
Known OS version compatibility:         Solaris 2.x - 9

**This software has not been tested on OpenVnmrJ. Use at your own risk.**

To install this user contribution:  
Download the repository from GitHub and checkout the tag of the contribution you want.
Typically tags end in the version (e.g. -v1.0)

     git clone https://github.com/OpenVnmrJ/maclib  
     cd maclib  
     git checkout zoomplot2d-v1.0


You may also download the archive directly from github at

    https://github.com/OpenVnmrJ/maclib/archive/zoomplot2d-v1.0.zip

Read zoomplot2d.README for installation instructions.

In most cases, move the contribution to /vnmr/userlib/maclib 
then use extract to install the contribution:  

    extract maclib/zoomplot2d
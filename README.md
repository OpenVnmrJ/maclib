# lcdatast
 lcdatast - Expands the functionality of the "lcdatast" macro to properly
 adjust
 the UV chromatogram on the SUN screen for expansions of on-flow or
 stop-flow measurements (with the standard macro, the UV is always
 displayed for the whole time of the chromatography). The contribution
 also makes "lcdatast" label intensities in the UV chromatogram
 correctly.

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

Your name:              Wolf Hiller
                        Alsfelder Strasse 6
                        Postfach 111553
                        D-64230 Darmstadt
Phone (optional):       +49.6151.703282
FAX (optional):         +49.6151.703200
Date submitted:         2001-03-08

File name:              lcdatast
Directory:              maclib
Description:            Expands the functionality of the "lcdatast" macro to
                        properly adjust the UV chromatogram on the SUN screen
                        for expansions of on-flow or stop-flow measurements
                        (with the standard macro, the UV is always displayed
                        for the whole time of the chromatography). The
                        contribution also makes "lcdatast" label intensities
                        in the UV chromatogram correctly.

Related files:          maclib/lcdatast_old

Existing VnmrJ / VNMR files which are superseded or
otherwise affected by this submission:  maclib/lcdatast
Hardware configuration limitations:     LC-NMR
Known software version compatibility:   VNMR 6.1B, 6.1C

**This software has not been tested on OpenVnmrJ. Use at your own risk.**

To install this user contribution:  
Download the repository from GitHub and checkout the tag of the contribution you want.
Typically tags end in the version (e.g. -v1.0)

     git clone https://github.com/OpenVnmrJ/maclib  
     cd maclib  
     git checkout lcdatast-v1.0


You may also download the archive directly from github at

    https://github.com/OpenVnmrJ/maclib/archive/lcdatast-v1.0.zip

Read lcdatast.README for installation instructions.

In most cases, move the contribution to /vnmr/userlib/maclib 
then use extract to install the contribution:  

    extract maclib/lcdatast
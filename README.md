# getxpk
 getxpk - Extract cross-peak intensities from one or more NOESY spectra,
 based
 on a single "manually" measured data set. This material was found
 in Magnetic Moments, Vol. IV, No. 2, p. 18; corrections published
 subsequent to that issue are incorporated into the macros.

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

Your name:              Steve Patt
                        For support questions please contact
                                Rolf Kyburz (rolf.kyburz@agilent.com)
Date submitted:         1992-10-28
                        1994-03-14 revised f. VNMR 4.3, A.Gogoll, Univ.Uppsala
                        1994-05-12 revised to use ll2d only, A.Gogoll, Uppsala
                        1997-01-30 made compatible with VNMR 5.3, fixed bug
                        1997-02-06 modified to use ll2d instead of mark

File name:              getxpk
Directory:              maclib
Description:            Extract cross-peak intensities from one or more
                        NOESY spectra, based on a single "manually" measured
                        data set. This material was found in Magnetic Moments,
                        Vol. IV, No. 2, p. 18; corrections published
                        subsequent to that issue are incorporated into the
                        macros.

Related files:          maclib/buildup and manual entries

Existing VnmrJ / VNMR files which are superseded or
otherwise affected by this submission:  none
Hardware configuration limitations:     none
Known software version compatibility:   VNMR 4.3 - 5.3
                                        (NOT VNMR 4.1 and earlier!)

**This software has not been tested on OpenVnmrJ. Use at your own risk.**

To install this user contribution:  
Download the repository from GitHub and checkout the tag of the contribution you want.
Typically tags end in the version (e.g. -v1.0)

     git clone https://github.com/OpenVnmrJ/maclib  
     cd maclib  
     git checkout getxpk-v1.0


You may also download the archive directly from github at

    https://github.com/OpenVnmrJ/maclib/archive/getxpk-v1.0.zip

Read getxpk.README for installation instructions.

In most cases, move the contribution to /vnmr/userlib/maclib 
then use extract to install the contribution:  

    extract maclib/getxpk
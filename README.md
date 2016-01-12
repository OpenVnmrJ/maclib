# nph
 nph - "nph" is an alternative phasing method for phasing "difficult" data,
 such as C13 spectra from oil fractions. This method was first published
 by Larry W. Sterna & Victor P. Tong from the Shell Westhollow Research
 Center in Houston (FUEL 70, 941 (1991). It can also be used for other
 spectra, provided they feature a large group of signal at either ends
 of the spectrum, separated by some flat baseline in-between. This
 VNMR implementation was first done in 1992 for M. Laenen, Shell,
 Grand Couronne, France.

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
Date submitted: 2002-06-25 - Extracted from earlier "packages/extend"
                2008-07-08 - Added PC/Linux and MacOS X compatibility

File name:      nph.tar.Z
Directory:      maclib
Description:    "nph" is an alternative phasing method for phasing "difficult"
                data, such as C13 spectra from oil fractions. This method was
                first published by Larry W. Sterna & Victor P. Tong from the
                Shell Westhollow Research Center in Houston (FUEL 70, 941
                (1991). It can also be used for other spectra, provided they
                feature a large group of signal at either ends of the
                spectrum, separated by some flat baseline in-between.
                This VNMR implementation was first done in 1992 for M. Laenen,
                Shell, Grand Couronne, France.

Related files:  bin/nph      maclib/nph   manual/nph   source/nph.c

Existing VnmrJ / VNMR files which are superseded or
otherwise affected by this submission:  none
Hardware configuration limitations:     n.a.
Known software version compatibility:   VNMR 4.1 - 6.1
Known OS version compatibility:         Solaris 2.x and up
Special instructions for installation:

**This software has not been tested on OpenVnmrJ. Use at your own risk.**

To install this user contribution:  
Download the repository from GitHub and checkout the tag of the contribution you want.
Typically tags end in the version (e.g. -v1.0)

     git clone https://github.com/OpenVnmrJ/maclib  
     cd maclib  
     git checkout nph-v1.0


You may also download the archive directly from github at

    https://github.com/OpenVnmrJ/maclib/archive/nph-v1.0.zip

Read nph.README for installation instructions.

In most cases, move the contribution to /vnmr/userlib/maclib 
then use extract to install the contribution:  

    extract maclib/nph
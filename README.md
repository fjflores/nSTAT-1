nSTAT
=====

Neural Spike Train Analysis Toolbox for Matlab


nSTAT is an open-source, object-oriented Matlab toolbox that implements a range of models and algorithms for neural spike train data analysis. Such data are frequently obtained from neuroscience experiments and our intention in writing nSTAT is to facilitate quick, easy and consistent neural data analysis.

One of nSTAT's key strengths is point process generalized linear models for spike train signals that provide a formal statistical framework for processing signals recorded from ensembles of single neurons. It also has extensive support for model fitting, model order analysis, and adaptive decoding. In addition to point process algorithms, nSTAT also provides tools for Gaussian signals, ranging from correlation analysis to the Kalman filter, which can be applied to continuous normally-distributed neural signals such as local field potentials, EEG, ECoG, etc.

Although created with neural signal processing in mind, nSTAT can be used as a generic tool for analyzing any types of discrete and continuous signals, and thus has wide applicability.

Like all open-source projects, nSTAT will benefit from your involvement, suggestions and contributions. This platform is intended as a repository for extensions to the toolbox based on your code contributions as well as for flagging and tracking open issues.

The current official version of nSTAT can be downloaded from https://github.com/iahncajigas/nSTAT . However, this fork contains changes that enables the toolbox to run in newer versions of Matlab.

For mathematical and programmatic details of the toolbox, see:

Cajigas I, Malik WQ, Brown EN. nSTAT: Open-source neural spike train analysis toolbox for Matlab. Journal of Neuroscience Methods 211: 245–264, Nov. 2012

If you use nSTAT in your work, please remember to cite the above paper in any publications.

nSTAT is licensed under the GPL v2 Open Source License.

Installation Notes
------------------
Authors: 
Iahn Cajigas and Wasim Malik
Massachusetts Institute of Technology

To install the nSTAT toolbox:
1) Copy the files to the directory of your choice, e.g. c:\nSTAT\
2) Within Matlab, go the directory where you have copied the files
   e.g. >> cd('c:\nSTAT\');
3) type nSTAT_Install from the matlab command prompt
   e.g. >> nSTAT_Install
   This step adds nSTAT to the matlab search path and makes the helpfiles
   searchable along with all other matlab functions
4) Should you wish to install nSTAT in a directory named something other 
   than nSTAT, you will need to add that directory to Matlab's search
   path manually

nSTAT should now appear along with all other installed toolboxes in the
matlab help browser.


UPDATES
-------
The most up-to-date version of nSTAT source code can be obtained from the 
subversion repository at https://code.google.com/p/nstat-for-matlab/


CITATION
--------
If you use nSTAT in your work, please remember to cite the following paper
in any publications:

    Cajigas I, Malik WQ, Brown EN. nSTAT: Open-source neural spike train 
    analysis toolbox for Matlab. Journal of Neuroscience Methods 
    211(2): 245?264, Nov. 2012


LICENSE INFORMATION
-------------------
nSTAT v1 Copyright (C) 2012 Masschusetts Institute of Technology
Cajigas, I, Malik, WQ, Brown, EN
This program is free software; you can redistribute it and/or 
modify it under the terms of the GNU General Public License as published 
by the Free Software Foundation; either version 2 of the License, or 
(at your option) any later version.

This program is distributed in the hope that it will be useful, 
but WITHOUT ANY WARRANTY; without even the implied warranty of 
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. 
See the GNU General Public License for more details.
 
You should have received a copy of the GNU General Public License 
along with this program; if not, write to the Free Software Foundation, 
Inc., 59 Temple Place, Suite 330, Boston, MA 02111-1307 USA

**External files:**
Library files: zernike.zip, fixPSlinestyle.m, xticklabel_rotate.m were 
obtained from http://www.mathworks.com/matlabcentral and are subject to 
the terms and conditions of the BSD 2-Clause license located at
http://opensource.org/licenses/bsd-license.php. The respective authors 
reserve copyrights on their original software.

**Links:**
zernike polynomials
    http://www.mathworks.com/matlabcentral/fileexchange/7687-zernike-polynomials
fixPSlinstyle 
    http://www.mathworks.com/matlabcentral/fileexchange/17928-fixpslinestyle
xticklabel_rotate: 
    http://www.mathworks.com/matlabcentral/fileexchange/3486-xticklabelrotate



%% ImSAnE installation instructions

Open setup.m in matlab and run each block with command + enter
The last block contain settings that can be changed or left to their default.
Tested combinations of Matlab and operating system sorted by Matlab version:

Matlab 2014a
	- Mac OS X 10.10.2

Matlab 2013a
	- Mac OS X 10.10.2
	- Ubuntu LTS 12.04 & 14.04
        - Windows 7 Professional


%% Bioformats to automatically read metadata

The reading of raw data assumes tif format and requires specification of number of channels by hand.
To read more formats and detect some metadata automatically, one can download the bioformats package from

http://downloads.openmicroscopy.org/bio-formats/5.1.3/

and place the jar file in the folder external/bfmatlab
John Aragon 2017190. Recipes for using SOD to download seismic data from the US IRIS DMC.
Download SOD from http://www.seis.sc.edu/SOD/index.html

Descriptions:

SOD_SPLITLAB.xml
For requesting broadband channels from IRIS DMC for use in Splitlab for Matlab (http://splitting.gm.univ-montp2.fr/).
To initiate download in working direcory use ~> sod -f SOD_Splitlab.xml
Select file format yyyy.DDD.HH.mm.SAC.e in Splitlab

Record_section_nepal.xml
sample record section using multiple seismic networks and stations. P arrival is marked in SAC files.
Files are saved and sorted by event folder. Example captures the Nepal Earthquake
https://ds.iris.edu/ds/nodes/dmc/specialevents/2015/04/25/nepal/
To use sacHeaderScript to modify depth to km, install seisfile: https://github.com/crotwell/seisFile

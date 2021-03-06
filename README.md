ColorBlindNARRreader

A script which reads meteorological data from the North American Regional Reanalysis database and plots it onto color-blind-friendly maps.

Created collaboratively by Greg Blumberg (OU/CIMMS) and Matt Bolton (How The Weatherworks) originally for use in research. 

Uses the HCL color scheme. See http://journals.ametsoc.org/doi/pdf/10.1175/BAMS-D-13-00155.1 for an introduction to the HCL color scheme. Colormap RGB codes generated from http://hclwizard.org/

How to Run (from command line):

cd / chdir to the directory you downloaded ColorBlindNARRreader into.

Type: (year/month/day, hour [in UTC], and data parameter) | example: python narr_plotter.py 19990503 21 svr

This example will make a severe weather type map for May 3rd, 1999 at 21 UTC

Other types of maps can be (here are the arguments):
   850 
   700
   500
   300
   sfc
   sfccnt

Note: only a few show on-run. By default, images will save to the directory you have ColorBlindNARRreader in.

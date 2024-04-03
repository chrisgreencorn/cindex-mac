# CINDEX for macOS
CINDEX is a software tool for professional indexers, enabling them to produce indexes in a variety of formats

CINDEX for Mac works on any Mac computer running macOS 10.9 (Mavericks) through macOS 13 (Ventura).

## Updates

This is a slightly modified version of the CINDEX for Mac application open-sourced 2024-04-01. 

I have commented out sections of the files governing the start-up splash page for license key entry. The program appears to work fully as intended without initializing this splash page. 

Another method for circumventing the limitations is to alter the "TOPREC" variables in the cintypes.h file. The demo and student versions of the software are fully functional except for the limits placed on how many records one can add to their index: the MAXREC variable for the full version = 2000; demo version = 100; and student version = 500. You can raise the student version to 1999 with no adverse effects (some conditional logic re: these limits and software versions elsewhere). I haven't tried raising this MAXREC limit. 

YMMV!

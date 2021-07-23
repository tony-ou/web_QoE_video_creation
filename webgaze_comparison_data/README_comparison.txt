README_comparison.txt
Last Updated: 1/20/2017

-By downloading our uplt data you receive a webgaze_data_comparison.zip file with 2 sub folders, uplt and traditional.

-Within the uplt folder there are 45 site folders which contain 4 main .csv files:
gaz.csv, van.csv, all.csv, klz.csv
On each line of these files is a uPLT observation from the respective optimized version of the site load (Gaze, Vanilla, All, Klotski).
See the paper for details on these versions of the site load.

-In the traditional sub fodler there is a tab-separated values file containing the matrix of site by timing information:
gaz_loads.txt, van_loads.txt, all_loads.txt, klz_loads.txt
As well as separate files (version_spd_indx.txt) which contains the speed index times.

-The traditional timings we have reported are Onload, DomContentLoaded, and FirstPaint (hence each file is 1 header + 45 sites by 4)
-The spd_indx files additionally contain the Speed Index and Last Visual Change metrics as calculated by WebPageTest.


Notes: 
-This data is a bit noisy in that each of our 100 users may not have responded to every site. 
We show the sites in a random order for each study as to be unbiased, and some users may exit the study early (we require > 90% of responses to include a user),
Thus each file has <= 100 responses. 

-In rare cases, data points may be < 0, for these cases the user did not respond and we subtracted the null response from the user's reaction time. 
This is a data artifact, and consider removing these points if you choose to utilize this data.
# Selecting for Post Starburst Regions.

The first step in our project is to easily be able to identify Post-Starburst Regions in a galaxy.

Identifying PSB Spaxels through criteria outlined in French et al. (2015, 2018a). First select against current star formation through HAlpha equivalent width < 3, and then select for recent bursts through Lick HDelta - var(HDelta) > 4. 

We create a modified default marvin plotting function to overlay spaxels that match our PSB criteria in red. This enables the visual review of identified PSB regions in selected galaxies. Extraneous spaxels identified as spaxels were minimized by setting SNR threshold of 3. This value was chosen through visual analysis to maintain sample quantity and minimize spurious data.

## BPT?

By overlaying the BPT classification and the PSB classification, create histogram for the BPT plot where we can classify each BPT spaxel as either PSB or non-PSB. Spaxels that are not identified by the BPT are also given their own classification in the histogram. 



## Histograms

In order to ensure that there were enough PSB spaxels in our samples, histograms were generated for identified PSB galaxies using a selection of galaxies from French et al. 2023. The sample includes 93 galaxies meeting PSB criteria, and subcategorizes them based on selection methods. This includes E+A galaxies, SPOG, and PCA.





# Bird-Population
R-code of raw data taken from various sources of bird populations in the UK from 1994-2013 to determine their cause of decline in Farmland habitats.

Methods:

A total of 32 bird species were selected because it conveys a range of
niches that represent the ecosystem they habituate. Specialist and Generalist was determined
by the use of species profiles provided by BTObirdfacts and the British Bird Indicator
(DEFRA), bird characteristics were gathered from the BTObirdfacts database.

Various data-sets were used from several organisational bodies, these were the East of
England birds, 1994-2013 taken from the British Bird Survey (BBS). Including Farmland Bird
characteristics from the British Trust Ornithology (BTO) and the British Breeding Birds, 1970-
2015 from the Department for Environment, Food & Rural Affairs (DEFRA 2019). The focus
was to compare bird species decline in farmland by cross-comparing possible trends from
National UK data and regional East of England data whilst using the BTO data to characterise
the main features for decline.

The data collected from each site in the BBS dataset was produced by participants, bird
surveying along a transect within a 1x1 km2 of the Ordnance Survey national grid for 90
minutes, only 3 times per year, once to collect habitat cover data and twice, 4 weeks apart, to
count bird numbers and Juvenile birds were excluded (Baillie et al. 2010) Site and year (table
3 Appendix) were included as covariates and Survey squares were chosen randomly by
stratified random sampling within 83 regions across the UK. A total of 609 squares equal to
609km2

contrasted with only bird species found equal to or greater than 75% farmland cover
to enable a more accurate representation of the population in farmland in relation to the
hypothesis. 

The year 2001 was omitted from the investigation because of Food and Mouth disease
(FMD) outbreak during that year which affected BBS data collection (Raven, M.J., Noble, D.G.,
& Baillie, S.R., 2003)

National farmland data was calculated by including the summer breeding bird populations
with greater than 500 breeding pairs of 19 farmland indicator species from BBS data,
Common Bird Census (CBC) and Heronies Survey. Indicator data was calculated through
geometric means of each species and combining the sum of species through the time
periods of 1970-2013 to demonstrate fluctuations of bird population dynamics over time.
With the help of The Comprehensive R Archive Network (CRAN), Statistical analyses were
performed on the BBS, BTO and DEFRA datasets. Site and year were included as covariates
(Renwick et al., 2012). The BBS data was selected with population trends greater than 0 and
only for Species with 75 or greater farmland coverage including all months of temperature. A
log-transformation was applied to the Population Index to limit skewness in graphical
presentation. Descriptive statistics were performed to address the mean of population for all
sites belonging to each year for the BBS data, including ± Standard Deviation (SD) to
implement the variances around means through error bars, then an anti-log transformation
was taken resulting in the Geometric mean and ± SD. The analysis was further advanced
with a linear model to display whether the hypothesis was true and a true regression line was
fitted to determine the verity of this hypothesis.

Data analysis of bird species were selectively categorised into generalists and specialists as
indicators for species decline or increase. Pearson correlation coefficients along with
significance values (P>0.05) were additionally used to determine species population
dynamics overtime in farmland areas.

A varied use of graphing parameters were measured through R.

References:
Baillie, S.R., Marchant, J.H., Leech, D.I., Joys, A.C., Noble, D.G., Barimore, C.J., Downie, I.D.,
Grantham, M.J., Risely, K. and Robinson, R.A., 2010. Breeding birds in the wider countryside:
their conservation status 2010. Link to address: https://www.bto.org/ourscience/publications/research-reports/breeding-birds-wider-countryside-their-conservation-4
Defra, 2019. Wild bird populations in the UK, 1970 to 2018. Department for Environment,
Food & Rural Affairs. https://www.gov.uk/government/statistics/wild-bird-populations-inthe-uk (last accessed 08.12.2019)
Renwick, A. R., Johnston, A., Joys, A., Newson, S.E., Noble, D.G. and Pearce-Higgins, J.W.,
2012, Composite bird indicators robust to variation in species selection and habitat
specificity. Ecological Indicators. 18, 200-207
Raven, M.J., Noble, D.G. and Baillie, S.R., 2003. The Breeding Bird Survey 2002. Research
report no. 334. 



# DECAT_CandidateList
### Searching Public DECAT Candidates for Transient Events

**'get_candidates.ipynb'**

Based on code written by Garima Prabhakar, uses the DECAT candidate search results after initial cuts and creates a csv with all the candidate names. 

* Input is an html file of the Candidate Search page
* Ouput is a csv file of the candidate ids

**'MLG_lightcurves.ipynb'**

Crosschecks the previously created candidate list with Melissa Graham's list of candidates. For candidates that are in MLG's lists, her code and different data files 
can be implemented to create quick lightcurve plots. Plausible transient events will be noted seperatally. A csv file will be created for those that are not in her 
lists along with a link to their DECAT Candidate page. I can then manually search through the links for plausible transients. 
* Inputs: candidate csv, MLG files (exposures, objects, candidates, candidate_objects, candidate_lightcurves, candidate_lightcurve parameters)
* Outputs: MLG plots, notinMLG csv

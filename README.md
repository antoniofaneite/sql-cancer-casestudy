# SQL Cancer Case Study
----

## Using the publicly available Aggregated Analysis of ClinicalTrails.gov dataset (AACT) please download this
data and host it in a local postgres database to complete the following. Please complete each task using SQL.
  https://aact.ctti-clinicaltrials.org/snapshots

----

### 1. Create a view of all prospective (interventional) cancer-related clinical trials that are completed (no longer actively recruiting and not prematurely terminated) Including:  

Markup : * nct_id
         * The cancer condition
         * Inclusion/exclusion criteria for the trial
         * Location of the trial
         * Intervention of study
         * Total participants in the study 

----

### 2. Use this view to subset/answer all below requests

Markup :  a. Create a view for all observed adverse events and outcomes recorded for each trial
          b. Find the trial that had the most patients with a complete response to the intervention of study (using outcome_measurements table)
          c. Find the number of trials that started after 2005 and ended before 2010
          d. Distribution of trials by state

----

### 3. Deliverables:
Markup : * Code used to load data to Postgres database
         * SQL code used to write the views and questions specified above
         * If you are unable to complete any of the above, a description of what you attempted and what you would attempt next.

## Please include any additional code used to familiarize yourself with the data, a short summary of your approach (a few sentences will suffice), and any questions you encountered along the way that, given more time, you would have attempted to answer with the data.






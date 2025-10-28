# Pharmacokinetics of Perampanel in Danish Pediatric Patients with Epilepsy Based on Therapeutic Drug Monitoring

This repository includes the code necessary for reproducing the analysis from the manuscript “Pharmacokinetics of Perampanel in Danish Pediatric Patients with Epilepsy Based on Therapeutic Drug Monitoring”.
The primary analysis script is PKPD_Script.Rmd, which generates the PKPD_Script.html — knitted R Markdown report containing the code, figures, and analysis outputs.  

The study represents the first national, TDM-based analysis of perampanel exposure in Danish children and adolescents with epilepsy. Drawing on 311 serum samples from 68 patients, it quantifies inter- and intra-patient variability, identifies the impact of enzyme-inducing co-medications, and examines whether perampanel plasma concentrations predict seizure control or tolerability.

The analysis relies on two files, the primary data sheet where each row represents a single observation (e.g., a concentration measurement) for a subject, and a subset file that contains only the data from the first visit for each subject. The files are not provided in the analysis for GDPR reasons.

The full interactive HTML report is available here: (https://saraangelucci.github.io/PKPD/PKPD_Script.html)
As part of the data preparation, the script removes two subjects from the data file before analysis.

# Pharmacokinetic (PK) and Dosing Variables:

- The dose administered is measured in mg.
- The time point of the observation is in hours post-dose.
- The measured drug concentration is in ng/mL.

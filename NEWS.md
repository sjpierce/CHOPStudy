# CHOPStudy News

## 0.21.0, 2025-10-13
* `.gitignore`
    * Omit Windows thumbnail image files from tracking. 
    * Omit png files from tracking. 
* `README.qmd` and `README.md`
    * Update software version & citation info.
    * Added instructions for getting date-stamped output for production runs.
* `scripts/Descriptive_Analysis.qmd`
    * Export figure to graphics file suitable for journal submission. 
    * Add callout about figure used in manuscript.
* `scripts/GLMM_Analysis.qmd`
    * Export figures to graphics file suitable for journal submission. 
    * Update callouts about which figures are used in manuscript. 
* `scripts/Import_Data.qmd`
    * Updated external data file being imported (filled in 1 missing value for 
      total neutrophils based on reviewing medical chart).
* `scripts/references.bib`
    * Update software version & citation info.
    
## 0.20.0, 2025-10-10
* `DESCRIPTION`
    * Updated RoxygenNote and Suggests fields. 
* `README.qmd` and `README.md`
    * Update software version & citation info.
* `scripts/Descriptive_Analysis.qmd`
    * Removed a callout about a figure we are no longer including in the 
      manuscript.
* `scripts/GLMM_Analysis.qmd`
    * Updated callouts about which figures we are including in the paper. 
    * Add citations for glmmTMB.
* `scripts/references.bib`
    * Update software version & citation info.
    * Updated citation for manuscript in preparation.    
    * Add citations for glmmTMB.
    
## 0.19.0, 2025-08-29
* `.Rbuildignore`
    * Omit the `graphics` folder to resolve a devtools::check() note. 
* `DESCRIPTION`
    * Moved piercer from Depends to Suggests field to resolve devtools::check() 
      note. 
* `README.qmd` and `README.md`
    * Update software version & citation info.
    * Add citation for manuscript in preparation.
* `scripts/Descriptive_Analysis.qmd`
    * Remove blank lines.
    * Add citation for manuscript in preparation.
    * Remove obsolete callouts.
* `scripts/GLMM_Analysis.qmd`    
    * Add callouts about which figures will be used in manuscript.
    * Fix spelling.
    * Improve narrative text. 
    * Update interpretation to reflect results after updated case selection.
    * Omit a warning message. 
* `scripts/Import_Data.qmd`
    * Update case selection to use only dogs whose visit 1 was within 10 days of 
      CHOP start.  
    * Improve narrative text.
    * Remove blank lines.
    * Add citation for manuscript in preparation.
* `scripts/references.bib`
    * Update software version & citation info.
    * Add citation for manuscript in preparation.

## 0.18.0, 2025-08-20
* `README.qmd` and `README.md`
    * Update software version & citation info.
* `scripts/Descriptive_Analysis.qmd`
    * Capitalize names of drugs.
    * Add table of drug sequences that start with cyclophosphamide.
    * Update labeling of band cagegories in a figure.
* `scripts/GLMM_Analysis.qmd`
    * Capitalize names of drugs.
* `scripts/Import_Data.qmd`
    * Capitalize names of drugs.
    * Update definition & labeling of Bandemia and Band_Category. This should 
      not affect summaries because Total_Bands is only stored to 1 decimal 
      precision. 
* `scripts/references.bib`
    * Update software version & citation info.

## 0.17.0, 2025-08-16
* `README.qmd` and `README.md`
    * Update software version & citation info.
* `scripts/Descriptive_Analysis.qmd`
    * Add a frequency table for Band_Category.
    * Compute additional weight summaries.
* `scripts/GLMM_Analysis.qmd`
    * Improve narrative text.
    * Update figure & table captions.
    * Switch from relative risk to risk differences.
* `scripts/references.bib`
    * Update software version & citation info.

## 0.16.0, 2025-08-12
* `README.qmd` and `README.md`
    * Update software version & citation info.
* `scripts/_quarto.yml`
    * Update render key to include another script.
* `scripts/GLMM_Analysis.qmd`
    * Change figure size. 
* `scripts/references.bib`
    * Update software version & citation info.

## 0.15.0, 2025-08-12
* `README.qmd` and `README.md`
    * Update software version & citation info.
* `scripts/Descriptive_Analysis.qmd`
    * Stop loading a package we no longer use. 
* `scripts/GLMM_Analysis.qmd`
    * Improve narrative text. 
    * Improve table formatting.
    * Change figure sizes. 
    * Improve figure formatting.
    * Stop loading packages we no longer use. 
* `scripts/Render_scripts.qmd` 
    * Load more packages. 
    * Update chunks for running other scripts.
* `scripts/references.bib`
    * Update software version & citation info.
    
## 0.14.0, 2025-08-10
* `README.qmd` and `README.md`
    * Update software version & citation info.
* `scripts/GLMM_Analysis.qmd`
    * Add comments about packages loaded.
    * Update methods text. 
    * Update modeling output and narrative text.
* `scripts/Import_Data.qmd`
    * Updated Final_Visits and Final_Patients with additional variables.
* `scripts/references.bib`
    * Update software version & citation info.

## 0.13.0, 2025-07-26
* `README.qmd` and `README.md`
    * Update software version & citation info.
* `scripts/GLMM_Analysis.qmd`
    * Load more packages. 
    * Improve narrative text. 
    * Improve model output and diagnostic checks. 
* `scripts/references.bib`
    * Update software version & citation info.
    * Add references.
    
## 0.12.0, 2025-07-18
* `README.qmd` and `README.md`
    * Update software version & citation info.
* `scripts/Descriptive_Analysis.qmd`
    * Load another R package. 
    * Add missing data summaries. 
    * Add a plot of total bands vs total neutrophils.
    * Switch to black & white theme for figures. 
    * Remove output for Total_Bands_rescaled.
    * Improve figure caption and labeling.
    * Improve table caption.
    * Reorganize and improve total bands section. 
    * Reorganize and improve total bands by drug section. 
    * Reorganize and improve total bands by visit section. 
    * Extensively renamed chunks
    * Switched to ggplot for several figures to make code clearer. 
* `scripts/GLMM_Analysis.qmd`
    * Added file. 
* `scripts/Import_Data.qmd`
    * Added centered variables needed for GLMM analyses.
* `scripts/references.bib`
    * Update software version & citation info.
    * Added references. 
* `scripts/_quarto.yml`
    * Updated Render key to include modeling script. 
    
## 0.11.0, 2025-07-06
* `README.qmd` and `README.md`
    * Update software version & citation info.
* `scripts/Descriptive_Analysis.qmd`
    * Added meta-data details about data file loaded.
    * Improve narrative text.
    * Improve table formatting. 
    * Add table of drug sequences. 
    * Updated table of band category distribution by drug and added a figure 
      of those results.
* `scripts/Import_Data.qmd`
    * Added meta-data details about files read in and saved out.
    * Improve narrative text. 
    * Added Band_Category and Name variables.
* `scripts/references.bib`
    * Update software version & citation info.

## 0.10.0, 2025-06-15
* `README.qmd` and `README.md`
    * Update software version & citation info.
    * Update repository contents section.
* `scripts/Descriptive_Analysis.qmd` 
    * Add references section.
    * Improved marrative text and chunk labels. 
    * Fixed a table that was broken by solving missing data. 
    * Fixed a warning about using outdated code for histograms.
    * Fix Bandemia Grade table.
    * Add table for leukemic status.
* `scripts/Import_Data.qmd`
    * Read an updated data file that fixed some missing data issues, clarified 
      that Leukemia and steroid variabkles are time-invariant within a CHOP 
      cycle, standardarized steroid names, and confirmed some date corrections.
    * Add references section.
    * Add Leukemic to Final_Patients data. 
* `scripts/references.bib`
    * Update software version & citation info.

## 0.9.0, 2025-04-28
* `README.qmd` and `README.md`
    * Updated software version info & references. 
* `scripts/Descriptive_Analysis.qmd` 
    * Added default output file name.
    * Enabled global chunk option for warnings.
    * Removed FloatBarrier commands (only need those for PDF output).
* `scripts/Import_Data.qmd`
    * Added default output file name.
    * Enabled global chunk option for warnings.
    * Removed FloatBarrier commands (only need those for PDF output).
    * Improved narrative text.
    * Update load-packages chunk. 
* `scripts/Render_scripts.qmd`
    * Add a subtitle.
    * Convert from PDF to html output.
* `scripts/references.bib`
    * Updated software version info & references. 

## 0.8.0, 2025-04-23
* `README.qmd` and `README.md`
    * Improved narrative text. 
    * Updated software version info & references. 
* `scripts/references.bib`
    * Updated software version info & references. 
    
## 0.7.0, 2025-04-21
* `DESCRIPTION`
    * Updated Depends field to require newer version of R. 
* `README.qmd` and `README.md`
    * Improved narrative text. 
    * Updated software version info & references. 
* `scripts/Example_Script.Rmd` 
    * Deleted file because this project uses Quarto instead of R Markdown. 
* `scripts/Import_Data.qmd`
    * Read a newer data file. 
* `scripts/references.bib`
    * Updated software version info & references. 

## 0.6.0, 2025-03-26
* `scripts/Descriptive_Analysis.qmd` 
    * Rename some chunks. 
    * Update patient descriptive table to show number of visits.
    * Remove obsolete tables. 
    * Fix table captions.
    * Improve narrative text. 
    * Improve table structure and labeling. 
    * Add frequency table of categorical biomarker variables.
    * Update heading structure.
    * Move and improve table for drug frequency distribution.
    * Add frequency table for visit number.
    * Simplify table code. 
    * Add table of continuous biomarkers broken down by bandemia.
    * Change table order and add another table.
* `scripts/Import_Data.qmd`
    * Improved narrative text and code comments.
    * Add some binary variables. 
    * Improved heading structure. 
    * Updated data file being read in. This one has additional variables, plus 
      it corrected a couple inaccurate CBC_Date values. Removed code no longer 
      required because of that.
    * Recoded toxic change variable. 
    * Remove obsolete output.

## 0.5.0, 2025-03-09
* `scripts/Descriptive_Analysis.qmd` 
    * Load additional packages. 
    * Add patient and visit-level descriptive tables. 
    * Improve histograms of total bands.
    * Update data frame names.
* `scripts/Import_Data.qmd`
    * Renamed data frames and chunks.
    * Added assumption checks. 
    * Added patient-level dataset.
    * Add variables to an intermediate data frame. 
    * Add tables to show which records were dropped. 
    * Updated list of data frames saved out.
    * Move code for renaming data frame.
    * Subset the patient-level data.
    * Update heading structure.
    * Fix patient's data frame.
    
## 0.4.0, 2025-03-05
* `scripts/.gitignore`
    * Added file.
* `scripts/_quarto.yml`
    * Add output-dir key and list scripts to render. 
* `scripts/Descriptive_Analysis.qmd` 
    * Add file based on copying parts from `scripts/Analyze_data.qmd`
* `scripts/Import_Data.qmd`
    * Improve narrative text.
    * Improve figure caption.
    * Improve section on subsetting the data. 
    * Update saving out data. 
    * Add a subtitle.
    * Remove cfsize knitr chunk option (not relevant in HTML output). 
    * Define new variables.
* `scripts/references.bib`
    * Updated references. 

## 0.3.0, 2025-01-29
* `scripts/Import_Data.qmd`
    * Change author order because I'm re-working things a lot. 
    * Improve narrative text and callouts.
    * Update load-packages chunk.
    * Change i_am() call to reflect new filename.
    * Change chunk labels and object names to clarify the code.
    * Simplify and reorganize data cleaning. 
    * Add a section for further subsetting data. 
    * Add a section for saving data file. 
    * Sorted the data.
    * Improved data cleaning sections and code. 
    * Updated descriptive statistics on visit timing after data cleaning.
    * Added section for identifying cases where visit 1 happened within 2 weeks 
      of starting CHOP.
    * Started summarizing amount of data at each step of case selection.
    * Temporarily disable saving out data.
* `scripts/Analyze_Data.qmd`
    * Update section for loading data. 
* `scripts/Render_Scripts.qmd`
    * Added file.
    
## 0.2.0, 2025-01-15
* `scripts/_brand.yml`
    * Switch to Arial for base font.
* `scripts/Import_Data.qmd`
    * Added file.
* `scripts/Analyze_Data.qmd`
    * Added file.
* `scripts/Render_Scripts.qmd`
    * Added file.
    
## 0.1.0, 2025-01-15
* Created package and did initial setup.

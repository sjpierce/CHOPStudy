# CHOPStudy News

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
    * Add Leukemic to FInal_Patients data. 
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

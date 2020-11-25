# Global Fishing Watch Data Standard Operating Procedures 

Standard operating procedures for emLab projects using Global Fishing Watch data

https://emlab-ucsb.github.io/gfw-SOP 

## Table of Contents

 1. Global Fishing Watch Basics
   - Types of Data  
   - Available Data   
   - Data Caution  
 
 2. Setup and Access  
   - BigQuery Setup  
   - Billing  
 
 3. Data  
   - Core AIS Datasets and Assumptions  
   - Best Tables  
   - VMS Datasets  
   - Dark Targets Tables  
 
 4. Workflow  
   - Validation with BigQuery  
   - Using BigQuery in R  
 
 5. Additional Resources  
   - Global Fishing Watch Data Training  
   - Fishwatchr  
 

## Contributing

The website is built using the `bookdown` package for R. After pulling the latest updates and adding or revising content, use the following command to render the website:

bookdown::render_book(input = "index.Rmd")

To produce a clean build of the website, simply delete the 'docs' folder before rendering, which is where generated files are stored. Once rendered, then commit the changes and push to the repo. The GitHub website will automatically update with the new changes.  
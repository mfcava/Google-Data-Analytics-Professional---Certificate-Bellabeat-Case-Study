!"./static/img/bb-logo-full.png"

# Bellabeat Case Study
## Capstone for Google Data Analytics Professional Certificate

### Scenario
Bellabeat is a successful small company with the potential to become a larger player in the global smart device market. 
Chief Creative Officer of Bellabeat believes that analyzing smart device fitness data could help unlock new growth opportunities for the company. 

### Goals 
Analyze smart device data to gain insight into how consumers are using their smart devices to guide marketing strategy for the company. 

### Target analysis audience
Bellabeat executive team along with marketing team.











***

# Technical Notes

## STYLE GUIDES
All chunks must be named and the standard for naming is the camel_case with some name_space to help grouping various elements.
Indentation must be the standard Rstudio (CMD+i or CTRL+i)


### PROJECT DIRECTORIES
Skelethon include some usefull directories to keep the projects structure clean.
- **DATA**: must contains all the local data sources.
- **CACHE**: could contains all the post-import / post tidy version of the data-sets. Tipically stored in Rds files (avoid .Rda)
- **LIBS**: custom collection of utility / functions that could be shared with other projects
- **STATIC**: all the static resources needed for output (such as CSS, Images)


### NAMING CONVENTIONS
- All variables in the **setup chunk** must be named starting with 'config_'.
- All **functions** must start with 'fn_'.
- All data frames must start with "df_". 
- It's also strongly suggest to use **consistent column names** across tables for common features such as date column (**dt** or **ds**).



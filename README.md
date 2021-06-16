# R Markdown Project Skelethon

Project skelethon for R-Markdown projects (GIT Version)



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



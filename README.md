# Data-Wrangling-Template-Python
Template for wrangling data before analysis, visualization and modelling.

Data Wrangling Steps

1) Gather

    Depending on the source of your data, and what format it's in, the steps in gathering data vary.
    High-level gathering process: obtaining data (downloading a file from the internet, scraping a web page, querying an API, etc.) and importing that data into your programming environment (e.g., Jupyter Notebook).

2) Assess

    a) Assess data for:
    
        (i) Quality: issues with content. Low quality data is also known as dirty data.
        
        (ii)Tidiness: issues with structure that prevent easy analysis. Untidy data is also known as messy data. Tidy data requirements:
        
            Each variable forms a column.
            
            Each observation forms a row.
            
            Each type of observational unit forms a table.

    b) Types of assessment:
    
        (i) Visual assessment: scrolling through the data in your preferred software application (Google Sheets, Excel, a text editor, etc.).
        
        (ii)Programmatic assessment: using code to view specific portions and summaries of the data (pandas' head, tail, and info methods, for example).

3) Clean

    a) Types of cleaning:
    
       (i) Manual (not recommended unless the issues are single occurrences)
       
       (ii)Programmatic
       
    The programmatic data cleaning process:
    
        Define: convert our assessments into defined cleaning tasks. These definitions also serve as an instruction list so others (or yourself in the future) can look at your work and reproduce it.
        
        Code: convert those definitions to code and run that code.
        
        Test: test your dataset, visually or with code, to make sure your cleaning operations worked.
        
    Always make copies of the original pieces of data before cleaning!

4) Reassess and Iterate

    After cleaning, always reassess and iterate on any of the data wrangling steps if necessary.

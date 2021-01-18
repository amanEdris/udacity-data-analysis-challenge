# udacity-data-anlysis-challenge


# Instructions

The purpose of this exercise is to test your capacity to process a dataset, the proficiency, efficiency and replicability of your code and your ability to clearly explain all the steps you take when processing data. This is a task that you will routinely encounter as a Data  Analyst.

 You should send the following documents to github or bitbucket repository before weekly deadlines when submitting the completed  assessment:                                                                 
                                                                                                                                                        - It is preferred you do the tasks with 1 programming language(Python or R) and 1 tool ([Stata](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwj-9IHqtIruAhVPCuwKHY_cDTUQFjAAegQIARAC&url=https%3A%2F%2Fwww.stata.com%2F&usg=AOvVaw2BZIT9GMfK1AZcHeAUsHqC) or [open-refine](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwiHn8istIruAhVFCewKHaunBi4QFjAAegQIARAD&url=https%3A%2F%2Fopenrefine.org%2F&usg=AOvVaw0yxy1TRpMgrycnDp7AQECP)  or  [Altyrex](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&ved=2ahUKEwirwqvCtIruAhUNGewKHU9GDikQFjAAegQIARAD&url=https%3A%2F%2Fwww.alteryx.com%2F&usg=AOvVaw2lT_FExuvzclxLsgWiuc_-)  or  [Weka](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwiaiob0uoruAhWMDewKHaqvDCkQFjABegQIARAC&url=https%3A%2F%2Fsourceforge.net%2Fprojects%2Fweka%2F&usg=AOvVaw0SZnEdW9-fRpJMY_fElY1Z) or  [Knime](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwj3gtOWvYruAhUIuqQKHZjhBygQFjAAegQIARAD&url=https%3A%2F%2Fwww.knime.com%2F&usg=AOvVaw3Mw80JFslVFoR6Uq4iBmir) or [RapidMiner](https://rapidminer.com/)) to see how it works
- All the statistical code that you have used in the data cleaning (e.g. [Altyrex](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&ved=2ahUKEwirwqvCtIruAhUNGewKHU9GDikQFjAAegQIARAD&url=https%3A%2F%2Fwww.alteryx.com%2F&usg=AOvVaw2lT_FExuvzclxLsgWiuc_-) work flow, [Stata](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwj-9IHqtIruAhVPCuwKHY_cDTUQFjAAegQIARAC&url=https%3A%2F%2Fwww.stata.com%2F&usg=AOvVaw2BZIT9GMfK1AZcHeAUsHqC) do file, R script, [Jupyter](https://jupyter.org/) Notebook, [open-refine](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwiHn8istIruAhVFCewKHaunBi4QFjAAegQIARAD&url=https%3A%2F%2Fopenrefine.org%2F&usg=AOvVaw0yxy1TRpMgrycnDp7AQECP) work flow etc.)
- Any dataset you might have used and/or produced.

# Background

Prior to the launch of any data collection project, companyA conducts field preparation activities to inform local authorities of the upcoming data collection activities as well as to recruit potential survey participants. As a best practice, we recruit more participants than the exact number required to minimize attrition.

The companyA recently finished field preparation activities for a project on early childhood development. The study was conducted in 2 districts, district A and B, and in each of the districts, a small number of cells were selected: 3 in district A and 2 in district B.

To be eligible for this study, a household in those cells had to have at least one child under 3 years old. However, there were concerns about being able to find enough households with children under 3 to meet sample size requirements and a decision was made to cast a wider net and recruit all households with children under 4 within the cells selected.

Local authorities in the study areas provided CompanyA with lists of all households residing in the selected cells. CompanyA’s data collectors visited the households on the lists and listed all household members in households with children under 4.

You have been provided with 2 datasets for each district: a main dataset and a roster dataset. The main datasets contain information on: (i) whether the households provided by the district officials were found, (ii) if they consented for their household to be listed for this study and (iii) if they had a child under 4. If all the above requirements were met, the data collector listed all household members and their personal information, which was recorded in the roster datasets. Description of all the variables is given in Table 1 below.

# Task

The Data Quality Manager wants you to undertake the following sub-tasks and output relevant files:

## Question 1

1. Using the variables names and values labels provided in Table 1 below, please label:
          a. all variables in the main and roster datasets
          b. the values of all categorical variables

## Question 2

2. Please create a dataset combining the main and roster data so that we have one observation per household with all household members as well as their personal information contained in the roster for both districts. Save this dataset as “all_households_yourname_yyyymmdd”.

## Question 3

3. At the end of field preparation, there were enough households with children under 3 to meet the sampling requirements. Therefore, please output another dataset consisting of only the eligible households that will be interviewed during data collection. In this dataset, create additional variables for the eligible child or children, i.e., their names, age and gender. Save this dataset as “all_eligible_yourname_yyyymmdd”.

## Question 4

4. To aid the data team in drafting a data collection field plan, please extract a list of eligible households per district in .csv format, with each cell on a separate tab.

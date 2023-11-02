# Introduction to primary care databases course

Primary Care Database practical
NCRM e-Methods festival 7-9 November 2023

In this short practical session, you will get a chance to look at some artificial primary care database data to get an idea of the structure of this type of data, and what sort of coded information is available. We will look at just three types of files: 
1.	The patient file – which contains some basic demographic information and dates
2.	The diagnosis file – which contains information on coded diagnoses and clinical findings
3.	The prescriptions file - which contains records for each electronically issued prescription in primary care
The names of these files and variables contained within will be slightly different in different primary care databases (e.g. CPRD Gold and Aurum each contain very similar information, but in differently named files). 
You can download the three csv files from this GitHub link: 
https://github.com/UCL-CHIG/intro_to_pcd_course 

For this practical, we will be looking at some diagnoses coded using Read codes, and prescriptions using drug codes. For the purpose of the practical, the descriptions these codes stand for have been added to the files. 
The practical can be done using excel (answers will be provided using excel functions), but you can also use the statistical software of your choice. 

1.	Open the patient file (PCD_patient_file.csv) and count how many patients are in the file, how many men and women there are, and how many patients have died. 

2.	Look up patient with ID number 216. How old were they when they registered with the practice, and how old were they at the last data collection date? 

3.	Open the diagnosis file (PCD_diagnosis_file.csv) and just take a look at the file itself. You’ll see each patient can have multiple diagnoses recorded, over time or on the same day. How many diagnoses records do the patients have, and what is the most common diagnosis code? 

4.	Now try to look up a specific condition, for instance non-insulin dependent diabetes mellitus (you might want to start with Read code C109.00). How many times has a diagnosis for this condition been entered? Would you want to use any other Read codes to enhance the phenotype? (Hint: look up code lists for diabetes on the HDR UK phenotype library)

5.	Coming back to patient with ID 216, what does their diagnosis history look like? Does this patient have any underlying chronic health conditions? 

6.	Now open the prescription file (PCD_prescription_file.csv). Same as the diagnosis file, start by just having a look a the layout of the file and see how many prescriptions were issued for this group of patients. 

7.	Which is the most common prescription? 

8.	Look at patient 216 again, they only had 1 diagnosis code for an underlying condition. Does their prescription history give you more information on the severity or duration of this condition? 



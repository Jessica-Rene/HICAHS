CSV file: new~data_formula.csv   - not included in this due to confidentiality (Institutional Review Board)

Extracted data from Posture_Raw Data Files | Time, BPM, Posture(°), Estimated Core Temperature (°C)  

 Extracted data from Subject survey responses database_all workers with code book | Age, Height, Weight, Task 

Calculated ACC (Absolute Cardiac Cost), RCC (Relative Cardiac Cost), %RHR (Percentage of Relative Heart Rate), %CVL (Percentage of Cardiovascular Load) 


Formulas: 

Resting Heart Rate | Smallest (10 sec) mean interval of BPM / HR at resting position | restingHR 

Working Heart Rate | Average of raw heart rate measured during different tasks (approximately 15-minute intervals) | workingHR 

Absolute Cardiac Cost | Formula: working HR – resting HR | ACC 

Relative Cardiac Cost | Formula: (ACC / (220-Age-RestingHR))*100 | RCC 

Percentage of Relative Heart Rate | Formula: (workingHR – restingHR)/(208-0.7^Age-restingHR))*100% | %RHR 

Percentage of Cardiovascular Load | Formula: 100*((workingHR – restingHR)/((1/3*(220-Age))+restingHR)) | %CVL 


Resting-HR.RMD 

Calculated the resting heart rate by averaging over the 10 second mean ‘rolling mean’ in Resting HR.Rmd 

Csv file used: Testing.csv 

 
15_min_int.Rmd 

I had to create plots to make sure that the BPM over time made sense – and separated the breaks from the tasks 

I calculated the BPM (15-minute intervals) to average out the working heart rate. 

 
CURC.Rmd 

Compared the Cardiovascular Load vs Average Temperature 

(for the first two plots) 

Tabel for each task & estimated marginal means (from HICAHS poster) 

Predictions of estimated marginal means (HICAHS poster) for Celebration of Undergraduate Research & Creativity

Plot used on HICAHS poster comparing Cardiovascular Load  vs Average Temperature 

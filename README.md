# Investigating-a-Dataset

Project: No Show Appointments[¶](#Project:-No-Show-Appointments)
================================================================

Introduction[¶](#Introduction)
------------------------------

### Dataset Description[¶](#Dataset-Description)

The dataset I selected for this Project Analysis is the _No show Appointments._ This dataset is focused on whether or not patients show up for their appointments in the hospital and it consists of 110527 rows and 14 columns such as :

*   PatientID: indicates the record that was created for the patient as a result of any issue for which they required medical assistance.
*   AppointmentID: shows us the number they were given by the hospital when they booked the appointment.
*   Gender: tells us the gender of the patient, either male or female.
*   ScheduledDay: tells us on what day the patient set up their appointment.
*   AppointmentDay: tells us when the patient is supposed to go to the hospital.
*   Age: indicates the age of the patients.
*   Neighbourhood: indicates the location of the hospital.
*   Scholarship: indicates whether or not the paitents enrolled in Brasilian Welfare.
*   Hipertension, Diabetes, Alcoholism and Handcap: show the characteristics of the patients.
*   SMS\_received: show whether the patients received an SMS informing them of their appointment.
*   No-show: indicates _NO_ if the patient showed up to their appointment and _YES_ if the patient did not show up to their appointment.

### Question(s) for Analysis[¶](#Question(s)-for-Analysis)

Questions that I plan on exploring over the course of this report:

*   Does Gender play a big role in making sure that people meet up with their appointment in this dataset.
*   Are people of a certain age likely to show up to their appointment because of the scholarship.

I Imported Pandas, Numpy, matplotlib.pyplot and Seaborn 

Data Wrangling[¶](#Data-Wrangling)
----------------------------------
I first read in my dataset and then used df.info() to assess the data 
I used df.describe()
I checked the data for duplicates and found none, also I looked into the highest and lowest count of the dataset

### Data Cleaning[¶](#Data-Cleaning)
------------------------------------
Since the data is a bit clean and does not need much work, I would be dropping the columns that are not in line with the questions I posed and also take a look at the median and mean.
I converted all the column names to lowercase for easy access and also renamed columns and then finally dropped the duplicates.

Exploratory Data Analysis[¶](#Exploratory-Data-Analysis)
--------------------------------------------------------

### Research Question 1[¶](#Research-Question-1)

*   Does Gender play a big role in determining who went to their appointment in this dataset?
We see from the dataset that females showed up more than their male counterparts and as we can see below, females are also found more in this dataset.
I used a function that would help to further understand the gap and differences between the genders male and female.

### Research Question 2  [¶](#Research-Question-2- )
*   Are people of a certain age likely to show up to their appointment because of the scholarship.
We see that patients within the age group of 0-10 showed up to their appointments more than any other age group followed by ages 35-70 and I also used a box plot for further explanation.

Conclusions[¶](#Conclusions)
----------------------------

*   The number of those that did not show up to their was almost 4 times of the people that didn't show up to their appointments.
*   Age plays a significant amount of role and it seems like the older you get, the lower the tendency to meet up with your appointment occurs.
*   Females also showed up a lot more than the males to their appointments and females are larger in size also.

*       Limitations
    
    There are some columns that I believe to have little to no significance to the dataset, also I dont think the sample is a good representation because they seem to be a lot more females than men which makes the analysis biased in a way.

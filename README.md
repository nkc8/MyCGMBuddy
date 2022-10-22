# **MyCGMBuddy**
### 2022-10-22
### *By Gileads Bizzare Adventure*

![Pitt Challenge 2022 (2)](https://user-images.githubusercontent.com/116460765/197359610-feddefd2-04c0-4903-a0bd-56cd8704fdd0.jpg)

**Inspiration:**
We were inspired by the idea of utilizing wearable data collected from smart watches for solving a big healthcare problem. Wearable devices such as smart watches can monitor glucose continuously and can be used to optimize therapy for patients with diabetes. Moreover, our team member Manuel has witnessed his roommate who has Type 1 Diabetes, constantly monitor her eating and lifestyle to maintain her normoglycemic levels.

**What it does:**
This simple Graphical User Interface(GUI) tool is an effective, dynamic dose optimization tool that patients can use for managing their own insulin therapy. Based on input for insulin dose, co-medications as well as the continuous glucose data, a dosing algorithm in the back end spits out a recommending dose change which the patient can execute themselves.

**How we built it:**
We utilized a published dataset from JCHR- JAEB Center for Health Research: https://public.jaeb.org/datasets/diabetes - “A Randomized Trial Comparing Continuous Glucose Monitoring With and Without Routine Blood Glucose Monitoring in Adults with Type 1 Diabetes”

We performed data preprocessing and cleaning using RStudio with tidyverse packages-stringr. Time-series plots of the glucose-monitoring data were made using matplotlib in Python. A basic interactive GUI tool was developed using the ipy widget package, where we linked the patient database- their medications, and comedications and CGM reading to the dashboard along with multiple user-input options.


What’s next for MyCGMBuddy?

*We would love to scale this up further and incorporate more drug interactions into the database to make the tool accessible to all patients with Type 1 Diabetes*

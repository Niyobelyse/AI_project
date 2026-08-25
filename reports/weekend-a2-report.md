## Assignment 2 Report:
Heart Disease Data Wrangling and Exploratory Analysis
### Dataset
UCI Heart Disease Data (heart_disease_uci.csv) contains 920 patient records collected from four different medical sites. The dataset was used with proper attribution to the original authors.

### Question Explored
What patient factors, including age, sex, and exercise-test measurements, are associated with heart disease diagnosis, and how does this association vary across collection sites?

### Findings
Age: Diagnosis rates increased with age, rising from 0% among patients in their 20s to about 73% among patients in their 60s before slightly decreasing in the 70s.

Sex: Men had a substantially higher diagnosis rate than women, at 63.2% compared with 25.8%.

Exercise-test measurements: Diagnosed patients generally had lower maximum heart rates and higher ST depression (oldpeak). Their measurements formed noticeably different patterns from undiagnosed patients.

Collection site: Diagnosis rates varied considerably between sites: Switzerland had the highest rate at 93.5%, followed by VA Long Beach at 74.5%, Cleveland at 45.7%, and Hungary at 36.2%.

### Limitation
The large differences between sites probably reflect differences in patient selection and referral practices rather than true differences in disease prevalence. Therefore, models could learn the collection site instead of genuine clinical relationships. Missing values in ca and thal also limited the available information.

### Charts
reports/a2_chart1.png — Shows diagnosis rates increasing with age.
reports/a2_chart2.png — Shows diagnosed patients having lower maximum heart rates and higher ST depression.
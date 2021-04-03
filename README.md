# Survival Analysis of Oral Cancer Patients

Oral cancer is a particularly dangerous disease in its early stages it may not be noticed by the patient without producing pain or symptoms
they might readily recognize. With the critical development of oral cancer screening as integral part of a clinician's routine, the disease is usually diagnosed at an advanced stage. 


In this study, the survival outcomes of 338 patients who were diagnosed with oral squamous cell
carcinoma (OSCC) in the northernmost province of Finland between January 1, 1985 and
December 31, 2005 was examined along with their demographic characteristics. To evaluate
the association between survival rates and various prognostic factors in OSCC patients, both
non-parametric and semi-parametric methods/models will be employed to full the analysis
in this project.

## Dataset
http://www.stats4life.se/data/oralca.txt

* `id`: Participant dentification Number. 
* `sex`: Gender. (1: Female, 0: Male)
* `age`: Age at Diagnosis (in years).
* `stage`: TNM stage of tumor. (1: Stage I; 2: Stage II; 3: Stage III; 4: Stage IV; unkn: Unknown)
* `time`: Survival Time (in years).
* `event`: The status of the patient. (1: Alive; 2: Died of OSSC; 3: Died of other reasons )


## Method
* Exploratory analysis
* Non-parameteric survival analysis
  - Kaplan-Meier estimator
  - Log Rank Test
* Semi-parametric survival analysis
  - Cox Proportional-Hazards Model 

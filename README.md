The data is a poly-pharmacy dataset which is available from “polypharm” in the R package “aplore3”. The set contains data on 500 subjects studied over 7 years. 
The response is whether the subject is taking drugs from 3 or more different groups. 
We consider the covariates, Gender = 1 if male and 0 if female, Race = 0 if subject is white and 1 otherwise, Age, and the following binary indicators for the number of outpatient mental health visits, 
MHV1 = 1 if $\mathrm{1 \leq MHV \leq 5}$, MHV2 = 1 if $\mathrm{6 \leq MHV \leq 14}$ and MHV3 = 1 if $\mathrm{MHV \geq 15}$. Let NPTMHV = 0 if there were no inpatient mental health visits and 1 otherwise. 
We consider a logistic random intercept model of the form:

![image](https://github.com/Zhelena/Bayesian-Analysis-of-Polypharmacy/blob/main/Model.png)

The task to do is to derive the posterior distribution of the model, use at least one computational method taught in this course to infer the posterior distribution and summarize your inference. 
Optional further analysis can include comparing different computational methods, model checking, model selection, sensitivity analysis with respect to different model and prior choices, etc.

`Project.pdf` is the requirement of the project. `Pre.pptx` is the PPT used for presentation.

`Rejection Sampling.Rmd` is the code of the computational method. `beta_data1.csv`, `beta_data2.csv`, `beta_data3.csv`, `beta_data4.csv` are simulations 
of four chains sampled using rejection sampling for the $\beta$ values.
`u_i.csv` is the simulation of $u_i$'s.

`ROC.R` and `effecency.R` are codes of model efficiency checking.



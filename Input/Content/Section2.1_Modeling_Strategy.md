The general concept of building a PBPK model has previously been described by Kuepfer et al. ([Kuepfer 2016](#5-references)). Relevant information on anthropometric (height, weight) and physiological parameters (e.g. blood flows, organ volumes, binding protein concentrations, hematocrit, cardiac output) in adults was gathered from the literature and has been previously published ([Willmann 2007](#5-references)). The information was incorporated into PK-Sim® and was used as default values for the simulations in adults.

The applied activity and variability of plasma proteins and active processes that are integrated into PK-Sim® are described in the publicly available PK-Sim® Ontogeny Database Version 7.3 ([PK-Sim Ontogeny Database Version 7.3](#5-references)) or otherwise referenced for the specific process.

A mean model was built based on clinical data from studies with intravenous (Billington et al. 2019 ([Billington 2019](#5-references)), Martin et al. 2003 ([Martin 2003c](#5-references))) and oral administration (Martin et al. 2003 ([Martin 2003c](#5-references)), Stopfer et al. 2016 ([Stopfer 2016](#5-references)), Stopfer et al. 2018 ([Stopfer 2018b](#5-references)), Wu et al. 2017 ([Wu 2017](#5-references)), Gidal et al. 2017 [Gidal  2017](#5-references), Cooper et al. 2003 [Cooper 2003a](#5-references),  Lee et al. 2018 [Lee 2018](#5-references) and Gosai et al. 2008 [Gosai 2008](#5-references)) of rosuvastatin. The studies reported individual ([Billington 2019](#5-references)) or mean plasma concentrations of rosuvastatin. The study by Billington et al. 2019 also reported individual (n=1) bile fraction of unchanged rosuvastatin as well as tissue concentration in liver and kidney, and the studies by Martin et al. 2003, Stopfer et al. 2016 and Stopfer et al. 2018 reported fraction excreted in urine of unchanged rosuvastatin in addtion to plasma concentrations. The mean PBPK model was developed using a mean individual based on the demographic data for each study and if no demographic data were provided the following values were used; male, European, 30 years of age, 73 kg body weight and 176 cm body height. The relative tissue-specific expressions of the enzyme and transporter predominantly being involved in the metabolism/transport of rosuvastatin (CYP2C9, OATP1B1, OATP1B3, BCRP, Pgp and OAT3) were considered ([Meyer 2012](#5-references)). A Weibull function was fitted to describe the oral dissolution of rosuvastatin and the dose was applied as a split dose approach with lag time for the second dose to capture the late Tmax.  

A specific set of parameters (see below) was optimized to describe the disposition of rosuvastatin using the Parameter Identification module provided in PK-Sim®. Structural model selection was mainly guided by visual inspection, mean relative deviation and geometric mean fold error of all predicted
AUClast and Cmax values. In addition sensitivity analyses of included parameter were assessed.

The model was then verified by simulating further clinical studies reporting pharmacokinetic concentration-time profiles after intravenous and oral administration of rosuvastatin.

Details about input data (physicochemical, *in vitro* and clinical) can be found in [Section 2.2](#22-data-used).

Details about the structural model and its parameters can be found in [Section 2.3](#23-model-parameters-and-assumptions).





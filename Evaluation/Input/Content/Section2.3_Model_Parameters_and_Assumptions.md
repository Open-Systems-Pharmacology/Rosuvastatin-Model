### 2.3.1 Absorption

The parameter value for  `Specific intestinal permeability`  was optimized based on clinical oral data, see results of optimization in [Section 2.3.4](#234-automated-parameter-identification). The measured solubility in water was used in the model (see [Section 2.2.1](#221-in-vitro-and-physicochemical-data))

The dissolution of tablets was implemented via empirical Weibull dissolution extracted from literature. The dose was applied as a split dose approach with lag time for the second dose to capture the late Tmax as informed by popPK modeling. 

### 2.3.2 Distribution

Rosuvastatin is highly bound to plasma proteins (approx. 88.5 %) (see [Section 2.2.1](#221-in-vitro-and-physicochemical-data)). A value of 11.5% was used in this PBPK model for `Fraction unbound (plasma, reference value)`. The major binding partner was set to albumin (see [Section 2.2.1](#221-in-vitro-and-physicochemical-data)).

An important parameter influencing the resulting volume of distribution is lipophilicity. The reported experimental logP value of -0.33 was used in this model (see [Section 2.2.1](#221-in-vitro-and-physicochemical-data)). 

After testing the available organ-plasma partition coefficient and cell permeability calculation methods built in PK-Sim, observed clinical data was best described by choosing the partition coefficient calculation by `PK-Sim Standard` and cellular permeability calculation by `PK-Sim Standard`.

### 2.3.3 Metabolism and Elimination

One metabolic pathway was implement into the model via Michaelis-Menten kinetics 

* CYP2C9

The CYP2C9 expression profiles is based on high-sensitive real-time RT-PCR ([Nishimura 2003](#5-references)). Metabolic enzyme activity was described as saturable process following Michaelis-Menten kinetics, were the `Km` was taken from literature and the `kcat` was optimized based on clinical data (see [Section 2.3.4](#234-automated-parameter-identification)).

And several transport protein was implemented into the model via Michaelis-Menten kinetics 

* OAT3

The OAT3 expression profiles is based on high-sensitive real-time RT-PCR ([Nishimura 2003](#5-references)). Transporter activity was described as saturable process following Michaelis-Menten kinetics, were the `Km` was set to 1 µmol/l and `kcat` was optimized based on clinical data (see [Section 2.3.4](#234-automated-parameter-identification)).

* BCRP

The BCRP expression profiles is based on whole genome expression arrays from ArrayExpress ([Kolesnikov 2015](#5-references)). Transporter activity was described as saturable process following Michaelis-Menten kinetics, were the `Km` was taken from literature and `kcat` was optimized based on clinical data (see [Section 2.3.4](#234-automated-parameter-identification)).

* Pgp

The Pgp expression profiles is based on high-sensitive real-time RT-PCR ([Nishimura 2003](#5-references)) with an intestinal mucosa of factor 3.57 ([47](#5-references)). Transporter activity was described as saturable process following Michaelis-Menten kinetics, were the `Km` was taken from literature and `kcat` was optimized based on clinical data (see [Section 2.3.4](#234-automated-parameter-identification)).

* OATP1B1/3

For OATP1B1/3 the expression profiles was considered only for OATP1B1 and is based on high-sensitive real-time RT-PCR ([Nishimura 2003](#5-references)). Transporter activity was described as saturable process following Michaelis-Menten kinetics, were the `Km` was taken from literature and `kcat` was optimized based on clinical data (see [Section 2.3.4](#234-automated-parameter-identification)).

* OATP2B1

The OATP2B1 expression profiles is based on whole genome expression arrays from ArrayExpress ([Kolesnikov 2015](#5-references)). Transporter activity was described as saturable process following Michaelis-Menten kinetics, were the `Km` was taken from literature and `kcat` was optimized based on clinical data (see [Section 2.3.4](#234-automated-parameter-identification)).

Additionally, passive renal clearance by glomerular filtration was implemented and the `GFR fraction` was set to 1. In addition, fraction of bile that was continously released was set to 1 (`EHC continuous fraction`)


### 2.3.4 Automated Parameter Identification

This is the result of the final parameter identification:

| Model Parameter                | Optimized Value | Unit      |
| ------------------------------ | --------------- | --------- |
| `kcat` (BCRP)                 | 1.00          | 1/min |
| `kcat` (CYP2C9)             |     9.90E-4        |  1/min         |
| `kcat` (OATP1B1/3)                | 748.37      | 1/min     |
| `kcat` (Pgp)                    | 29.21          | 1/min    |
| `kcat` (OAT3)                  | 43833.14       | 1/min     |
| `kcat` (OATP2B1)                  | 2.97         | 1/min     |
| `Specific intestinal permeability`| 1.22E-6    | cm/min    |
| `P(intracell->interstitial) small intestine`| 7.39E-4     | cm/min       |
| `P(intracell->interstitial) small intestine`| 7.07E-6        | cm/min       |


 
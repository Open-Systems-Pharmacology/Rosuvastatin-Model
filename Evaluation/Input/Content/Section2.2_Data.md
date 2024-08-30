### 2.2.1 In vitro and physicochemical data

A literature search was performed to collect available information on physicochemical properties of rosuvastatin. The obtained information from literature is summarized in the table below, and is used for model building. Final model parameters are stated in [Section 3.1](#31-probenecid-final-input-parameters).

| **Parameter**           | **Unit** | **Value** | Source                               | **Description**                                              |
| :---------------------- | -------- | --------- | ------------------------------------ | ------------------------------------------------------------ |
| MW                      | g/mol    | 481.54    | [Wishart 2006](#5-references)        | Molecular weight                                             |
| pK<sub>a</sub> (acid)   |          | 4.3       | [Riccardi 2019](#5-references)       | acid dissociation constant of conjugate acid                 |
| Solubility (water)      | g/L      | 7.8       | [TGA 2011](#5-references)            | Aqueous solubility                  |
| logP                    |          | -0.33     | [McTaggart 2001](#5-references) and [Jones 2012](#5-references)         | Partition coefficient between octanol and water              |
| fu                      | %        | 11.5      | [FDA 2003](#5-references)           | Fraction unbound in plasma                                   |
| K<sub>m</sub> BCRP      | µmol/L   | 2.02      | [Kitamura 2008](#5-references)            | BCRP Michaelis-Menten constant                             |
| K<sub>m</sub> OAT3      | µmol/L   | 7.40      | [Windass 2007](#5-references)                | OAT3 Michaelis-Menten constant                                 |
| K<sub>m</sub> OATP2B1   | µmol/L   | 6.42      | [Kitamura 2008](#5-references)        | OATP2B1 Michaelis-Menten constant                                   |
| K<sub>m</sub> OATP1B1/3 | µmol/L   | 0.80      | [Kitamura 2008](#5-references)          | OATP1B1/3 Michaelis-Menten connstant                                 |
| K<sub>m</sub> Pgp       | µmol/L   | 203       | [Goard 2010](#5-references)            | Pgp Michaelis-Menten constant                             |
| Weibull shape           | -        | 1.77      | [Seo 2019](#5-references)            | Dissolution profile shape                             |
| Weibull time            | min      | 6.25      | [Seo 2019](#5-references)            | Dissolution time (50% dissolved)                            |

### 2.2.2 Clinical data

A literature search was performed to collect available clinical data on rosuvastatin in adults. 

The following publications were found in adults for model building:

| Publication                   | Arm / Treatment / Information used for model building        |
| :---------------------------- | :----------------------------------------------------------- |
| [Billington 2019](#5-references)  | Individual arterial plasma and whole blood, and tissue liver and kidney PK profiles and fraction excreted to bile in healthy subjects after single intravenous administration of 0.00174 mg rosuvastatin 160 minutes after an oral dose of 5 mg rosuvastatin |
| [Martin 2003c](#5-references) | Plasma PK profiles and urine data in healthy subjects after single intravenous infusion (4 h) of 8 mg rosuvastatin and single oral administration of 40 mg rosuvastatin tablet|
| [Stopfer 2016](#5-references)    | Plasma PK profiles and urine data in healthy subjects after single oral administration of 10 mg rosuvastatin tablet |
| [Stopfer 2018b](#5-references)    | Plasma PK profiles and urine data in healthy subjects after single oral administration of 10 mg rosuvastatin tablet |
| [Wu 2017](#5-references)   | Plasma PK profiles in healthy subjects after single oral administration of 20 mg rosuvastatin tablet |
| [Gidal 2017](#5-references)   | Plasma PK profiles in healthy subjects after single oral administration of 40 mg rosuvastatin tablet |
| [Cooper 2003a](#5-references)    | Plasma PK profiles in healthy subjects after single oral administration of 80 mg rosuvastatin tablet |
| [Lee 2018](#5-references)    | Plasma PK profiles in healthy subjects after multiple oral administration of 20 mg rosuvastatin QD |
| [Gosai 2008](#5-references)    | Plasma PK profiles in healthy subjects after multiple oral administration of 40 mg rosuvastatin QD |


The following table shows the data from the excretion studies used for model building:

| Observer                                                     | Value |
| ------------------------------------------------------------ | ----- |
| Fraction excreted to bile of unchanged rosuvastatin at 0.46 h after iv administration of 0.00174 mg | 4.76%   |
| Fraction excreted to urine of unchanged rosuvastatin after iv infusion of 8 mg | 29.5%   |
| Fraction excreted to urine of unchanged rosuvastatin after oral administration 10 mg | 6.27% and 5.1% |
| Fraction excreted to urine of unchanged rosuvastatin after oral administration 40 mg | 5.09%  |


The following dosing scenarios were simulated and compared to respective data for model verification:

| Scenario                                                     | Data reference                       |
| ------------------------------------------------------------ | ------------------------------------ |
| po 0.05                         | [Prueksaritanont 2017](#5-references) |
| po 5                                  | [Prueksaritanont 2014](#5-references) |
| po 10 mg                                   | [Cooper 2003b](#5-references), [Csonka 2019](#5-references), [Huguet 2016](#5-references), [Martin 2003b](#5-references), [Stopfer 2018a](#5-references), [Wiebe 2020](#5-references) and [Coss 2016](#5-references) |
| po 20 mg                              | [Martin 2003d](#5-references), [FDA 2003](#5-references), [Edwards 2017](#5-references), [Martin 2003b](#5-references), [Birmingham 2015](#5-references), [Jones 2020](#5-references), [Lee 2018](#5-references), [Martin 2016](#5-references) and [Willis 2020](#5-references) |
| po 40 mg                              | [Martin 2002a ](#5-references), [Martin 2003b](#5-references) and [Lee 2005](#5-references)|
| po 80 mg                                   | [Cooper 2002](#5-references), [Cooper 2003b](#5-references), [Cooper 2003c](#5-references), [Martin 2003b](#5-references), [Schneck 2004](#5-references) |
| po 10 mg QD for 14 days                    | [Kosoglou 2004](#5-references) and [Martin 2002b](#5-references)|
| po 20 mg QD for 7 days                    | [FDA 2003](#5-references) and [FDA 2018](#5-references)|



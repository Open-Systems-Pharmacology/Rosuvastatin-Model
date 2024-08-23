# Rosuvastatin-Model
Whole-body PBPK model of rosuvastatin.

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/a3/Rosuvastatin_structure.svg/2560px-Rosuvastatin_structure.svg.png" alt="File:Rosuvastatin_structure.svg" style="zoom:50%;" />



This repository contains:

- a [PK-Sim snapshot (*.json) file](https://docs.open-systems-pharmacology.org/working-with-pk-sim/pk-sim-documentation/importing-exporting-project-data-models#exporting-project-to-snapshot-loading-project-from-snapshot) of the current PBPK model
- static content (e.g. text blocks, *.md files) as inputs for an evaluation plan
- an evaluation plan (evaluation-plan.json) to create an evaluation report using the snapshot and static text blocks to display the performance of the model

**The latest release of the snapshot of the model, the evaluation plan and the static content can be found [here](../../releases/latest).**

**The latest release of the PK-Sim project model file and the respective evaluation report can be found [here](https://github.com/Open-Systems-Pharmacology/OSP-PBPK-Model-Library/releases/latest).**



This rosuvastatin model is intended to be used as victim drug in BCRP and OATP1B1/3-mediated drug-drug interactions (DDI).

Within this repository, we share a whole-body PBPK model of rosuvastatin that has been carefully developed using 42 clinical studies of intravenous or oral administration, covering a broad dosing range (0.002–80.0 mg).

The PK-Sim project file contains simulations and the observed data of all clinical studies used for model development and evaluation. For further details, quantitative model evaluation, sensitivity analysis and extensive documentation please refer to [1](#references).

## Code of conduct

Everyone interacting in the Open Systems Pharmacology community (codebases, issue trackers, chat rooms, mailing lists etc...) is expected to follow the Open Systems Pharmacology [code of conduct](https://github.com/Open-Systems-Pharmacology/Suite/blob/master/CODE_OF_CONDUCT.md#contributor-covenant-code-of-conduct).

## Contribution

We encourage contribution to the Open Systems Pharmacology community. Before getting started please read the [contribution guidelines](https://github.com/Open-Systems-Pharmacology/Suite/blob/master/CONTRIBUTING.md#ways-to-contribute). If you are contributing code, please be familiar with the [coding standard](https://github.com/Open-Systems-Pharmacology/Suite/blob/master/CODING_STANDARDS.md#visual-studio-settings).

## License

The model code is distributed under the [GPLv2 License](https://github.com/Open-Systems-Pharmacology/Suite/blob/develop/LICENSE).

## References

[1] [Hanke N, Gómez-Mantilla JD, Ishiguro N, Stopfer P, Nock V. Physiologically Based Pharmacokinetic Modeling of Rosuvastatin to Predict Transporter-Mediated Drug-Drug Interactions. Pharmaceutical Research 2021. PMID: 34664206.](https://doi.org/10.1007/s11095-021-03109-6)
 

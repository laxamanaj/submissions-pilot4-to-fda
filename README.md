> Do not includ `README.md` and `.gitignore` files into the final submission. 

## Overview

The objective of the R Consortium R submission Pilot 4 Project is to 
test the concept that a R-language based submission package can meet 
the needs and the expectations of the FDA reviewers, 
including assessing code review and analyses reproducibility. 
All submission materials and communications from this pilot are publicly available, 
with the aim of providing a working example for future R language based FDA submissions.
This is a FDA-industry collaboration through the non-profit organization R consortium.

The [RConsortium/submissions-pilot4-to-fda](Repo link...In progress)
repo demonstrates the eCTD submission package based on the [RConsortium/submissions-pilot4](Repo link...In progress) repo.  

The [RConsortium/submissions-pilot4](Repo link...In progress) repo demonstrates an approach to organize ADaM submission ready datasets using the open sourced package [ADaM in R Asset Library](https://pharmaverse.github.io/admiral/index.html).

To learn more about other pilots, visit [the R consortium R submission working group website](https://rconsortium.github.io/submissions-wg/) and the [R consortium working group page](https://www.r-consortium.org/projects/isc-working-groups).

## FDA Response 

- Initial submission
  + version: [v0.1.0](https://github.com/RConsortium/submissions-pilot1-to-fda/releases/tag/v0.1.0) (in progress and needs updating for piolot4)
  + [Cover letter](https://github.com/RConsortium/submissions-pilot1-to-fda/blob/main/m1/us/cover-letter.pdf)  (in progress and needs updating for piolot4)
  + [FDA statistical review and evaluation response](https://github.com/RConsortium/submissions-pilot1/blob/main/vignettes/fda/fda-response-2021-11-22.pdf)  (in progress and needs updating for piolot4)

- Updated submission
  +  (in progress and needs updating for piolot4 after initial submission)

- Examples below
  + version: [v0.1.1](https://github.com/RConsortium/submissions-pilot1-to-fda/releases/tag/v0.1.1) 
  + [Working group's response letter to FDA](https://github.com/RConsortium/submissions-pilot1-to-fda/blob/main/m1/us/response-to-fda-1.pdf)
  + [Final statistical review and evaluation response from FDA](https://github.com/RConsortium/submissions-wg/blob/main/Documents/Summary_R_Pilot_Submission2.pdf)
  
  
## Re-run analysis 
###  (in progress and needs updating for piolot4)
To re-run analysis, you can follow the steps described in the 
[ADRG document](https://github.com/RConsortium/submissions-pilot1-to-fda/blob/main/m5/datasets/rconsortiumpilot1/analysis/adam/datasets/adrg.pdf) based on the 
[program saved in the module 5](https://github.com/RConsortium/submissions-pilot1-to-fda/tree/main/m5/datasets/rconsortiumpilot1/analysis/adam/programs). 

## Folder Structure 

The folder is organized as a demo eCTD package following ICH guidance. 

eCTD package: 

- `m1/`: module 1 of the eCTD package

```
m1
└── us
    ├── cover-letter.pdf  # Submission cover letter
    └── report-tlf.pdf    # Submission TLFs 
```

> Note: the TLF format in `report-tlf.pdf` is not consistent, 
> because it reflects different table layouts in different organizations. 

- `m5/`: module 5 of the eCTD package

```
m5
└── datasets
    └── rconsortiumpilot1
        └── analysis
            └── adam
                ├── datasets              # ADaM datasets in XPT format
                │   ├── adadas.xpt
                │   ├── adae.xpt
                │   ├── adcibc.xpt
                │   ├── adlbc.xpt
                │   ├── adlbcpv.xpt
                │   ├── adlbh.xpt
                │   ├── adlbhpv.xpt
                │   ├── adlbhy.xpt
                │   ├── adnpix.xpt
                │   ├── adrg.pdf          # Analysis Data Reviewer's Guide
                │   ├── adsl.xpt
                │   ├── adtte.xpt
                │   ├── advs.xpt
                │   ├── define.xml        # ADaM data define file
                │   └── define2-0-0.xsl
                └── programs
                    ├── r0pkg.txt         # Proprietary R package in txt format  (in progress and needs updating for piolot4...will get replace by Admiral package)
                    ├── ad_adsl.r # analysis R code for ADaMs. 
                    ├── ad_adsub.r
                    ├── ad_adae.r
                    └── ad_adtte.r
```
Other files: (**Do not include in eCTD package**)

- `.gitignore`: git ignore file
- `README.md`: readme file for github repo

## News
### (in progress and needs updating for piolot4)
- [Successful R-based Test Package Submitted to FDA](https://www.r-consortium.org/blog/2021/12/08/successful-r-based-test-package-submitted-to-fda)
- [Update: Successful R-based Test Package Submitted to FDA](https://www.r-consortium.org/blog/2022/03/16/update-successful-r-based-test-package-submitted-to-fda)

## Questions 

Report issues in <https://github.com/RConsortium/submissions-pilot1-to-fda/issues>


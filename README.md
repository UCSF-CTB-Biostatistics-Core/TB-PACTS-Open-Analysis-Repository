# TB-PACTS Open Analysis Repository

This repository provides open-source code and documentation to improve the accessibility, usability, and reproducibility of analyses using data from the **TB Platform for Aggregation of Clinical TB Studies (TB-PACTS)**.

TB-PACTS is maintained by the [Critical Path Institute (C-Path)](https://c-path.org/tools-platforms/tb-pacts/) and contains standardized, participant-level data from tuberculosis clinical trials. The data are standardized using the Clinical Data Interchange Standards Consortium (CDISC) Study Data Tabulation Model (SDTM).

**This repository does not distribute TB-PACTS participant-level data.** Researchers must request access to the data directly from C-Path. The instructions below describe how to obtain access.

## Obtaining the TB-PACTS Data

TB-PACTS data are available to qualified researchers through the **C-Path Data Analytics Platform (CP-DAP)**. There is no fee to use the TB-PACTS data.

### Step 1: Create a CP-DAP account

1. Go to the [C-Path Data Analytics Platform (CP-DAP)](https://portal.cpdap.c-path.org/).
2. Select the option to **Sign Up** for a new account.
3. Complete the registration process using your contact and institutional information.
4. Submit your registration.

C-Path reviews new requests for platform access. According to the CP-DAP documentation, platform-access requests are generally reviewed within **3–5 business days**.

### Step 2: Log in to CP-DAP

After your account has been approved, log in to CP-DAP.

CP-DAP includes two components that are relevant when obtaining TB-PACTS data:

- **FAIR Data Services**, where available datasets can be discovered and data access can be requested.
- **Workspaces**, which provide a secure environment in which approved datasets can be accessed and analyzed.

### Step 3: Find the TB-PACTS datasets

1. Open **FAIR Data Services**.
2. Navigate to **Datasets**.
3. Select **All datasets**.
4. Search or browse for **TB-PACTS**.
5. Select a dataset to review its metadata and determine whether it contains the study or studies needed for your analysis.

A list of studies currently included in TB-PACTS is also available on the [C-Path TB-PACTS website](https://c-path.org/tools-platforms/tb-pacts/).

### Step 4: Request a research workspace

Before submitting a request to use TB-PACTS data for research, request a **Research Workspace** through CP-DAP.

1. Submit a request for a Research Workspace.
2. Wait for C-Path to review the request.
3. Once the workspace has been approved, you will receive an invitation to join it.
4. Open **Workspaces**, locate the invitation, and accept it.

C-Path indicates that research-workspace requests are generally addressed within **3–5 business days**.

### Step 5: Request access to the TB-PACTS data

Once your research workspace is available:

1. Return to **FAIR Data Services**.
2. Select the **Request** icon in the menu bar.
3. Complete the Data Access Request for the TB-PACTS dataset(s) you wish to use.
4. Describe the proposed research and intended use of the data as requested in the application.
5. Review and accept the applicable Terms and Conditions for use of TB-PACTS data.
6. Submit the request.

TB-PACTS data access is reviewed by the **TB-PACTS Steering Committee**. C-Path notes that review of a TB-PACTS data-access application may take **up to four weeks**.

### Step 6: Access the approved data

After your Data Access Request has been approved:

1. Return to FAIR Data Services.
2. Transfer the approved TB-PACTS dataset(s) to your Research Workspace.
3. Open your workspace to access the data.

The TB-PACTS datasets are provided in standardized **CDISC SDTM** format. Familiarity with SDTM is therefore helpful when working directly with the source datasets.

## Using This Repository

The code in this repository is intended to help researchers work with the SDTM datasets obtained directly from TB-PACTS.

In particular, this project aims to provide reproducible methods for:

- defining trial-specific analytic populations;
- deriving commonly needed analysis variables;
- deriving clinical outcomes and time-to-event variables;
- harmonizing variables across heterogeneous TB clinical trials; and
- producing analysis-ready datasets for secondary analyses.

The TB-PACTS data themselves should **not** be committed to this repository. Users are responsible for complying with the C-Path Terms and Conditions and any other requirements governing their access to TB-PACTS data.

## Additional Resources

- [TB-PACTS — Critical Path Institute](https://c-path.org/tools-platforms/tb-pacts/)
- [C-Path Data Analytics Platform (CP-DAP)](https://portal.cpdap.c-path.org/)
- [CDISC](https://www.cdisc.org/)

## Questions and Contributions

This repository is under active development. Issues, suggestions, and contributions that improve the usability, documentation, validation, or reproducibility of TB-PACTS analyses are welcome.

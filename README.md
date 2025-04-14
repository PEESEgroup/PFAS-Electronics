# PFAS-Electronics

### 1. Overall Use Instructions
This repository was prepared for analyzing the PFAS removal from the wastewater of electronics and semiconductor manufacturing, incorporating spatiotemporal characteristics.

#### - Future Scenarios:

- The **IMAGE 3.2 model** was selected as the primary source of Integrated Assessment Model (IAM) scenarios. There are also some other IAM models were considered
- The **Premise tool** was used to integrate IAM scenario information into the Life Cycle Assessment (LCA) database.
LCA Database:

#### - LCA Databse:
The baseline LCA database is based on Ecoinvent 3.8.
Subsequent LCA analyses were conducted **using the IAM-enhanced LCA databases generated with Premise, Python, and Brightway**.
Database Features:

#### - Database Features:
The generated databases incorporate temporal (year-specific) and regional characteristics, facilitating comprehensive analyses about the treatement of indstries wastewater.

#### - Economic model
The economic model used to measure water treatment is used to treat the costs of three GAC IER RO membrane systems under different scenarios


### 2. Section Descriptions:
#### - Code
This section provides the code for integrating IAM scenarios with the LCA database using Premise and Brightway.
Key features of the code include:
- Integration of IAM and LCA
  - We provide the code in the Code section for integrating IAM scenarios with the LCA database using Premise and Brightway, with support from the Premise documentation (https://github.com/polca/premise).
  
- Electronics and semiconductor market development:
  - We model the gradual market development and PFAS emissions to wastewater of electronics and semiconductor manufacturing.
  - The CAGR was used to reflect the development
  - We also used regional information such as the labor, energy, and other cost to exhibit regional situation
  - Certain information is compressed into the excel files.
    
This section is designed to provide flexible modeling options, reflecting various wastewater emission and manfacturing development speeds.

#### - Data

We present the main data underlying the results of this study, including market development, LCA results under sceanrios, economic analysis of different regions, and the influence of remvoing standards.


### 3. Tool Utilization:

Python 3.9 or higher

IMAGE 3.2

Premise 2.3 or higher (Compatibility with Python versions should be considered)

Brightway 2.5

Ecoinvent 3.8 or higher (Compatibility with Premise versions should be considered)

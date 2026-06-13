# Azure Data Factory End-to-End Pipeline

## Objective
Build an end-to-end data pipeline using Azure Storage Account and Azure Data Factory.

## Services Used
- Azure Resource Group
- Azure Storage Account
- Blob Containers
- Azure Data Factory
- Get Metadata Activity
- Copy Data Activity

## Pipeline Flow
CSV File → Blob Storage (Input Container) → Azure Data Factory → Output Container

## Steps Performed
1. Created Resource Group.
2. Created Storage Account.
3. Created Input and Output Containers.
4. Uploaded CSV file.
5. Created Azure Data Factory.
6. Configured Linked Service.
7. Created Source and Destination Datasets.
8. Added Get Metadata Activity.
9. Added Copy Data Activity.
10. Executed and monitored pipeline.
11. Verified output file generation.

## Result
The pipeline executed successfully and copied the CSV file from the input container to the output container.

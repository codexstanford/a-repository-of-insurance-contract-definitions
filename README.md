# A repository of insurance contract definitions

Insurance contracts and policies often contain a significant number of definitions.

This repository contains over 6000 annotated definitions from over 200 contracts. 

## Web UI

A web UI to explore the dataset is provided in `dictionary.html`. Just open it with a web browser after downloading it. Alternatively an online version is available at this address : To Be added

![webInterface](https://user-images.githubusercontent.com/208554/164327779-0941685d-aea7-4bbb-9c21-4b9d01d7fe7f.png)

## XLSX

An XLSX version (which can be loaded with pandas or excel) of the dataset is available in `a-list-of-insurance-contract-definitions.xlsx`.

The XLSX file contains the following columns:

- **term**: The term defined
- **lob**: The insurance Line Of Business corresponding to the contract that contains the definition
- **country**: The country of origin of the contract containing the definition
- **policyID**: The ID of the contract containing the definition (useful to consolidate other definitions from a policy)
- **definition**: The actual text of the definition

## Raw Text

The raw text of the definitions is available in 2 places:

- The directory `rawText` contains one file per defined term. Each file contains all definitions for that term, separated by '---'.
- The file `raw.txt` contains all definitions, separated by '---'. The first line of each definition is the defined term.

## JSON

`data.json` contains the raw data.

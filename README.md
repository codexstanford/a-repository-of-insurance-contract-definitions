# A repository of Insurance contract definitions

Insurance contracts and policies often contain a significant number of definitions.

This repository contain over 6000 annotated definitions from over 200 contracts. 

## Web UI

A web UI to explore the dataset is provided as the dictionary.html file. Just open it with a web browser after downloading it. Alternatively an online version is available at this address : To Be added

![webInterface](https://user-images.githubusercontent.com/208554/164327779-0941685d-aea7-4bbb-9c21-4b9d01d7fe7f.png)

## XLSX

An XLSX version (that can be loaded with panda or excel) of the dataset is available in the a-list-of-insurance-contract-definitions.xlsx file.

The XLSX file contain the following columns :

- **term** : The term defined
- **lob** : The insurance Line of - Business the contract the definition is from belong to
- **country** : The country the contract the definition belong to come from
- **policyId** : The id of the contract the definit
ion came from (useful to consolidate other definitons from a policy)
- **defition** : The actual text of the definition

## Raw Text

The raw text of the definition is available in 2 way :

- A directory 'rawText' containing a file per defined terms with all definition of this term separate by '---'.
- A file : raw.txt containing all the definition separate by '---'. The first line of each definition is the defined Term.

## JSON

An Json file containing the data is available (data.json)





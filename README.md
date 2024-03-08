# PLOSONE-MANUSCRIPT-0300588
# 1. Introduction
The purpose of this project is to archive the dataset utilized in the manuscript titled "Evaluation of the urban industrial coupling strategy based on the global production networks theory: a case study of the smartphone industry in the Guangdong-Hong Kong-Macao Greater Bay Area".

------

# 2. Data directory
This directory contains datasets related to enterprises, comprising three files. The file names and descriptions are provided below:

| File Name                                       | Description                                     | Source                                              |
| ----------------------------------------------- | ----------------------------------------------- | --------------------------------------------------- |
| Phone industry chain data_Wind database.csv     | The classified information of the enterprises   | The Wind database (https://www.wind.com.cn)         |
| Detailed information of Company_TianYanCha.xlsx | Registration information of the enterprises | The TianYanCha website (https://www.tianyancha.com) |
| Partial patent data_Incopat.xlsx                | The patent data of enterprises                  | The IncoPat website (https://www.incopat.com)       |

**Note:**

- **Phone industry chain data_Wind database.csv**: This file contains the all original smartphone industry chain dataset to classify each company, totaling 27,699 pieces of data. The classification is based on the "full_class" field  in this file and "Table 1. Smart phone industry chain and actor classification" in the paper. The more other industry chain data can be found on the [Wind database][https://www.wind.com.cn].

- **Detailed information of Company_TianYanCha.xlsx**: The file contains the entire original dataset of the registration information of each company in the mobile phone industry chain, and consists of 3 sheets. "Leading companies" sheet contains only the enterprise registration information of the leading  companies category. "Contract manufacturers" sheet contains only the enterprise registration information of the contract manufacturers category and These two sheets are obtained according to the advanced search tool provided by the official TianYanCha website. The other sheet is the enterprise registration information of the remaining three categories, which is obtained using the batch query tool of the official TianYanCha website based on the "ent_name" field in the "Phone industry chain data_Wind database.csv" file. More company registration information can be available from the [TianYanCha website][https://www.tianyancha.com].

- **Partial patent data_Incopat.xlsx**: This file contains a portion of the exampled raw dataset for each company's patent information. The "main_IPC" and "IPC" fields are crucial for establishing the innovation network in our paper. Additional patent information for companies can be found on the [IncoPat website ] [https://www.incopat.com].

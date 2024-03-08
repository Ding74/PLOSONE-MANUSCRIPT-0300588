# PLOSONE-MANUSCRIPT-0300588
# 1. Introduction
This project is mainly to store the dataset used in the manuscript entitled "Evaluation of the urban industrial coupling strategy based on the global production networks theory: a case study of the smart phone industry in the Guangdong-Hong Kong-Macao Greater Bay Area".

------

# 2. Data directory
This directory stores the dataset of the related to enterprises, a total of three files. The file names and descriptions are as follows:

| File Name                                       | Description                                     | Source                                              |
| ----------------------------------------------- | ----------------------------------------------- | --------------------------------------------------- |
| Phone industry chain data_Wind database.csv     | The classified information of the enterprises   | The Wind database (https://www.wind.com.cn)         |
| Detailed information of Company_TianYanCha.xlsx | The registration information of the enterprises | The TianYanCha website (https://www.tianyancha.com) |
| Partial patent data_Incopat.xlsx                | The patent data of enterprises                  | The IncoPat website (https://www.incopat.com)       |

**Note: **

- **Phone industry chain data_Wind database.csv**: This file stores the all original smartphone industry chain dataset to classify each company, totaling 27,699 pieces of data. The classification is based on the "full_class" field  in this file and "Table 1. Smart phone industry chain and actor classification" in the paper. The more other industry chain data can be found on the [Wind database][https://www.wind.com.cn].

- **Detailed information of Company_TianYanCha.xlsx**: The file stores the entire original dataset of the registration information of each company in the mobile phone industry chain, and consists of 3 sheets. "Leading companies" sheet contains only the enterprise registration information of the leading  companies category. "Contract manufacturers" sheet contains only the enterprise registration information of the contract manufacturers category and These two sheets are obtained according to the advanced search tool provided by the official TianYanCha website. The other sheet is the enterprise registration information of the remaining three categories, which is obtained using the batch query tool of the official TianYanCha website based on the "ent_name" field in the "Phone industry chain data_Wind database.csv" file. More company registration information can be available from the [TianYanCha website][https://www.tianyancha.com].

- **Partial patent data_Incopat.xlsx**: The file stores part of the raw dataset of each company's patent information. The "main_IPC" and "IPC" fields are key information for making the innovation network in our paper. More company's patent information can be searched from the [IncoPat website ] [https://www.incopat.com].

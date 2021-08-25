---
layout: default
---

# My Work at Societe Generale as a Data Scientist

## 1. Veritrade
<div align="center">
    <img alt="Logo" src="https://github.com/osabnis/osabnis.github.io/blob/master/images/featured.jpg" width="200" />
</div>

* Veritrade is a solution to automate trade finance verification. The solution uses state of the art deep learning to first identify the type of documents 
  from 23 different categories like Bill of Lading, Letter of Credit, Invoice, etc. 
* Once a document is classified the solution extracts critical information like issue date, type of commodity, billing address, etc from each of those 23 documents 
  using a hybrid approach comprising of both machine learning and heuristics. 
* The information extraction approach is robust enough to handle different variations across the same documents. 
* The solution then runs around 4000 consistency checks and rules specified by UCP and ISBP. The rules and consistency checks can be intra and inter documents.
* Advantages of Veritrade:
  * Massive efficiency gains of ~80%
  * Drastically reduces the operational risk
  * Brings objectivity to the UCP/ISBP rules
  * Flexible to quickly adapt to any UCP/ISBP rules
  * Eliminates training cost
* As a part of the team, I developed a new feature - a pilot meaning representation module that uses deep
  learning to convert semantically similar but syntactically different natural language statements into a standard logical
  form that a computer system can understand and execute. This feature wasn’t present neither in Veritrade nor in its competitors.
  

## 2. Sceptre
<div align="center">
    <img alt="Logo" src="https://github.com/osabnis/osabnis.github.io/blob/master/images/sceptre.png" width="200" />
</div>
* Sceptre is a platform built for conducting AI/ML related experiments. 
* On-fly OCR functionality with the option to choose Tesseract (Open source) Engine, ABBYY Engine, or Azure OCR. 
* Ability to create multiple projects with different versions and tag documents on the platform itself for recognition and extraction purpose. 
* The platform lets users choose different algorithms for document extraction and define business-specific heuristics. 
* The platform can also run multiple consistency checks and rules specified by the business. 
* Finally, the platform will list down the documents where some validation failed and requires additional review.
* As part of the project, I was in the Training APIs team where we aimed at building a framework that can be deployed with Sceptre for training and evaluating deep learning based model.
* I worked on developing the resource management component, model storage and versioning component and model evaluation component for the framework.

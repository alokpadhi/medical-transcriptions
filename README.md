# Project Overview

## Overview
#### Background
* **Customer:** Medical supporting staff
* **Goal:** Organize medical transcriptions with right speciality category
* **Pains:**: Manual organizing transcription is a hectic and time consuming process
* **Gains:**: Speed up the process of organizing and can also help in searching medical transcriptions

### Value Proposition
* **Product:** The primary product is to categorize transscriptions into different medical speciality, the second version could be building a search mechanism to search customer medical transcription faster.
* **Alleviates:** Automating categoization of transcriptions will reduce the efforts of medical staff for any discovery purpose
* **Advantages:** There will be no manual reading process necessary to choose the right medical speciality for the medical staffs.

### Objectives
* Create an automated pipeline to organize medical transcription into it's correct speciality
* Achieve > 85% for the classification problem
* Build a search mechanism as a downstream feature on top of the classification to search medical transcriptions based on keywords

### Solutions
* **Core Features**
    * ML service to classify the incoming medical transcription
    * Feedback loop from the medical staff to identify incorrect classifications
    * Filter incorrect classifications with high confident score
* **Secondary Features**
    * Build a search engine UI, to search transcriptions on demand
    * Integrate speciality classification ML service with search engine to reduce the search space
* **Constraints**
    * Maintain low latency
    * Identify duplication of medical transcriptions

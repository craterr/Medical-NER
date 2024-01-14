# Medical-NER
Medical Named Entity Recognition addresses challenges by automatically identifying and classifying specific medical entities from unstructured data. By automating this process, Medical NER saves time, reduces errors, enhances data accuracy, and enables healthcare professionals, researchers, and analysts to focus on higher-level tasks, leading to better patient care, improved research, and more efficient healthcare processes.


# Dataset

The dataset that we use contains medical information about different diseases and the medicines used to cure that particular disease.
The dataset is a JSON file where each element consists of the following keys :
![image](https://github.com/craterr/Medical-NER/assets/106965125/b881653d-2bcf-4dbf-aeab-931f854ad7f5)


The content key has a brief text about a particular disease and contains three types of entities that has been manually labeled:
- Medical Condition Names
- Medicine names
- Pathogens


The annotations key contains a list of all the manually labeled entities. The info that we will be focusing on is:
- Start index no of the entity
- End index no of the entity
- What label the entity falls under

Glimpse: 

![image](https://github.com/craterr/Medical-NER/assets/106965125/3704c335-8326-4c25-b7d8-5a2298e90c3b)

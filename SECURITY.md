# Project Description

Neuropsychiatric disorders that occur in development, like anxiety, depression, autism, and attention deficit hyperactivity disorder (ADHD) often differ in how and to what extent they affect males and females. ADHD occurs in about 11% of adolescents, with around 14% of boys and 8% of girls having a diagnosis. There is some evidence that girls with ADHD can often go undiagnosed. Girls with ADHD who are undiagnosed will continue suffering with symptoms that burden their mental health and capacity to function.

You’re a data scientist for the NHS. The data science department is trying to free doctor’s time by creating a system that can diagnose ADHD in children and adolescents as a support tool for GPs. In order to develop such a system, the fMRI department has collected functional brain imaging data of children and adolescents which are available to you together with their socio-demographic, emotions, and parenting information. As there might be gender-based differences, the task is to build a model to predict both an individual’s sex and their ADHD diagnosis using this information.

The company is particularly worried about misdiagnoses in female patients, as they are harder to diagnose with traditional methods. You must ensure that your model is not biased. Furthermore, due to GDPR requirements, your model should be explainable (e.g., you can use SHAP or LIME for this).

## **Load Virtual Enviroment**

```shell
   python -m venv venv               
   venv\Scripts\activate   
```

- Change editor's kernel to use Virtual environments kernel and libraries

## **Understand the Files**

1. Data Dictionary: Explains the variables, their meanings, and formats
2. Labels: Contains the target variables (e.g., ADHD diagnosis, sex).
3. Meta A and Meta B: Contain metadata or additional information about the subjects (e.g., socio-demographic, emotional, or parenting data).
4. Functional Connectodome (CSV): Contains fMRI data, which represents functional connectivity between brain regions.

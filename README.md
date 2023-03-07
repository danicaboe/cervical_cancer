# Cervical Cancer Risk Classification

*There isn't a single person whose life hasn't been affected by cancer. Whether a colleague, friend, relative, spouse or maybe even personally - cancer is all around us. It is a huge threat and there are so many different kinds, it can be overwhelming at the scale it has gotten to. Yet, with knowledge comes power. Through exploring human nature, health and well-being, lifestyle choices, and biological indicators we can gain more knowledge and therefore more power over a disease that has impacted so many.*


**Initial questions to explore:**
1. What is the average age of Cervical Cancer patients?
2. Does age and number of pregnancies have an influence on Cervical Cancer diagnosis?
3. What is the correlation between the four target variables: hinselman, schiller, cytology and biopsy?


Our group of four will clean and explore this data using Python and Pandas with python libraries added to aid our exploration and enable data visualization. While this is a small step - it is hopefully in the right direction. As with all endeavours, there is room to scale to a larger amount of data and more specific and action focused questions. While this data is a start, it can be expanded upon with data covering a wider geographic area, more health variables, research and data collection over long periods of time, and more advanced medicine and intervention methods.



**A few acronyms to note:**
* IUD - Intra Uterine Device (a form of contraceptive)
* STDs - Sexually Transmitted Diseases
* HPV - Human Papilloma Virus
* HIV - Human Immunodeficiency Virus
* AIDS - Acquired Immunodeficiency Syndrome (caused by HIV)
* CIN - Cervical Intraepithelial Neoplasia
* Dx - Medical Abbreviation for Diagnosis

    
The four target variables in this dataset are identified as *Biopsy, Schiller, Hinselmann, and Cytology*. Hinselmanns test refers to colposcopy using acetic acid. Meanwhile, colposcopy using Lugol iodine includes Schillers test, cytology and biopsy. Read more [here](https://peerj.com/articles/cs-154.pdf).

The Dx variables are previous diagnoses and the other tests Schiller, Hinselmann, and Cytology are available as predictors for Biopsy.

This data is from Venezuela, see original source [here](https://archive.ics.uci.edu/ml/datasets/Cervical+cancer+%28Risk+Factors%29).

Detailed variable description [here](https://ieeexplore.ieee.org/document/8070120/all-figures).


**Attribute Information:**
* (int) Age
* (int) Number of sexual partners
* (int) First sexual intercourse (age)
* (int) Num of pregnancies
* (bool) Smokes
* (bool) Smokes (years)
* (bool) Smokes (packs/year)
* (bool) Hormonal Contraceptives
* (int) Hormonal Contraceptives (years)
* (bool) IUD
* (int) IUD (years)
* (bool) STDs
* (int) STDs (number)
* (bool) STDs:condylomatosis
* (bool) STDs:cervical condylomatosis
* (bool) STDs:vaginal condylomatosis
* (bool) STDs:vulvo-perineal condylomatosis
* (bool) STDs:syphilis
* (bool) STDs:pelvic inflammatory disease
* (bool) STDs:genital herpes
* (bool) STDs:molluscum contagiosum
* (bool) STDs:AIDS
* (bool) STDs:HIV
* (bool) STDs:Hepatitis B
* (bool) STDs:HPV
* (int) STDs: Number of diagnosis
* (int) STDs: Time since first diagnosis
* (int) STDs: Time since last diagnosis
* (bool) Dx:Cancer
* (bool) Dx:CIN
* (bool) Dx:HPV
* (bool) Dx
* (bool) Hinselmann: target variable
* (bool) Schiller: target variable
* (bool) Cytology: target variable
* (bool) Biopsy: target variable


# Cervical Cancer Risk Classification

<h4><em>I don't know a single person whose life hasn't been affected by cancer. Whether a collegue, friend, relative, spouse or maybe even personally - cancer is all around us. It is a huge threat and there are so many different kinds, it can be overwhelming at the scale it has gotten to. Yet, with knowledge comes power. Through exploring human nature, health and wellbeing, lifestyle choices, and biological indicators we can gain more knowledge and therefore more power over a disease that has impacted so many. </h4>

<h4>While this is a small step - it is hopefully in the right direction. As with all endevours, there is room to scale to a larger amount of data and more specific and action focused questions. While this data is a start, it can be expanded upon with data covering a wider geographic area, more health variables, research and data collection over long periods of time, and more advanced medicine and intervention methods.</em></h4>

<ul>
<b>A few acronyms to note:</b>
    <li>IUD - Intra Uterine Device (a form of contraceptive)</li>
    <li>STDs - Sexually Transmitted Diseases</li>
    <li>HPV - Human Papilloma Virus</li>
    <li>HIV - Human Immunodeficiency Virus</li>
    <li>AIDS - Acquired Immunodeficiency Syndrome (caused by HIV)</li>
    <li>CIN - Cervical Intraepithelial Neoplasia</li>
    <li>Dx - Medical Abbreviation for Diagnosis</li>
</ul>
    
<p>The four target variables in this dataset are identified as <em>Biopsy, Schiller, Hinselmann, and Citology</em>. Hinselmanns test refers to colposcopy
using acetic acid. Meanwhile, colposcopy using Lugol iodine includes
Schillers test, cytology and biopsy.
https://peerj.com/articles/cs-154.pdf</p>

<p>The Dx variables are previous diagnoses and the other tests Schiller, Hinselmann, and Citology are available as predictors for Biopsy.</p>

<p>This data is from Venezuela, see original source here: https://archive.ics.uci.edu/ml/datasets/Cervical+cancer+%28Risk+Factors%29</p>

<p>Detailed variable description here: https://ieeexplore.ieee.org/document/8070120/all-figures</p>

<ul>
<b>Attribute Information:</b>
<li>(int) Age</li>
<li>(int) Number of sexual partners</li>
<li>(int) First sexual intercourse (age)</li>
<li>(int) Num of pregnancies</li>
<li>(bool) Smokes</li>
<li>(bool) Smokes (years)</li>
<li>(bool) Smokes (packs/year)</li>
<li>(bool) Hormonal Contraceptives</li>
<li>(int) Hormonal Contraceptives (years)</li>
<li>(bool) IUD</li>
<li>(int) IUD (years)</li>
<li>(bool) STDs</li>
<li>(int) STDs (number)</li>
<li>(bool) STDs:condylomatosis</li>
<li>(bool) STDs:cervical condylomatosis</li>
<li>(bool) STDs:vaginal condylomatosis</li>
<li>(bool) STDs:vulvo-perineal condylomatosis</li>
<li>(bool) STDs:syphilis</li>
<li>(bool) STDs:pelvic inflammatory disease</li>
<li>(bool) STDs:genital herpes</li>
<li>(bool) STDs:molluscum contagiosum</li>
<li>(bool) STDs:AIDS</li>
<li>(bool) STDs:HIV</li>
<li>(bool) STDs:Hepatitis B</li>
<li>(bool) STDs:HPV</li>
<li>(int) STDs: Number of diagnosis</li>
<li>(int) STDs: Time since first diagnosis</li>
<li>(int) STDs: Time since last diagnosis</li>
<li>(bool) Dx:Cancer</li>
<li>(bool) Dx:CIN</li>
<li>(bool) Dx:HPV</li>
<li>(bool) Dx</li>
<li>(bool) Hinselmann: target variable</li>
<li>(bool) Schiller: target variable</li>
<li>(bool) Cytology: target variable</li>
<li>(bool) Biopsy: target variable</li>
</ul>

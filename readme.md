# Directions EHR and public data

### Creating new packages in R for Processing geo enabled EHR, & Census Data .

### Some Analytics for EHR and census data

Next, we examine the rate at which the DUHS EHRs capture the county population of children. We estimate capture rates as:

𝐶𝑎𝑝𝑡𝑢𝑟𝑒𝑅𝑎𝑡𝑒𝑐= 𝐸𝐻𝑅𝑐𝑜𝑢𝑛𝑡𝑐/𝐴𝐶𝑆𝑒𝑠𝑡𝑖𝑚𝑎𝑡𝑒𝑐,
where c is the geographic unit (county or census tract), EHR count is the number of children in the EHR cohort who have at least one relevant encounter and reside in the geographic unit, and ACS estimate is the ACS-estimated number of children residing in the geographic unit. Thus, the capture rates are measured as the estimated proportion of children with at least one relevant DUHS encounter during the study period in a defined area

[https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9004253/  ]

### Benefits of Combined Electronic healht records and Census/survey data

data domain in EHR --> https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6724703/table/T1/?report=objectonly
[https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6724703/]

Neighborhood disparities in health outcomes can reflect unequal access to social and economic resources—often resulting from differences in neighborhood socioeconomic characteristics or structural forms of racism—that shape both individuals’ risk of illness and access to adequate health care services (Aysola, Orav, and Ayanian 2011; Beck et al. 2017, 2020). Public health policies and programs that leverage local data are essential for targeting the underlying causes of disease to improve population health (Acevedo-Garcia et al. 2008; Beck et al. 2017). Health surveys that describe individuals’ health profiles allow for population representative analyses at the national or state levels but often constrain accurate descriptions at smaller levels of geography because of small sample size (Birkhead 2017; Tomasallo et al. 2014).

[https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9004253/  ]


Not simply a digital version of a paper record (127), EHRs can be linked to contextual data using geographic information systems (GIS) and combined with self-reported data to address questions about complex networks of causation. Such work has the potential to evolve epidemiologic theory in the twenty-first century (69, 86).

[https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6724703/. ]


##### social determiannt of health (socioeconomic status)

Researchers have used health insurance status (e.g., commercial versus Medicaid) as a proxy for individual socioeconomic status (SES) (13, 18, 36, 44, 67, 83) and have assigned neighborhood SES on the basis of the median income or an index of deprivation in patients’ communities (13,18,29,35,38). 

[https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6724703/]

A patient’s SDOH can be used to estimate their access to healthcare and treatments, their positive or negative health outcomes, and to assess comorbidities by using information related to an individual’s health including alcohol and tobacco usage, socioeconomic status, insurance status, living situation, access to healthy foods, access to health literacy, and access to quality of care [5]


https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9599320/.  

###### main categorie of SDOH

The main components of the SDOH commonly gathered in medicine are grouped into five domains: economic stability, education access and quality, healthcare access and equity, social and community context, and neighborhood and built environment [5]. 

Though noted separately, each domain is interconnected to match the complexity of SDOH variables and represent SDOH at both the population and individual levels [6,7].


https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9599320/.  


##### Recommendations for EHR DATA EXTENTIONS

Although data on physical activity and other important behaviors and social risks are not routinely captured (2, 16), the Institute of Medicine has recommended that these and other domains be integrated into routine EHR data collection, including four existing (i.e., race/ethnicity, current address, alcohol use, and tobacco use) and eight new domains (e.g., stress, social isolation, physical activity) (27).

[https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6724703/]


#### Assembling Research Cohorts from EHR Data

Researchers can use EHRs to form standard cohorts and to assemble groups of patients with specific diseases

[https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6724703/]


### EHR tasks

Social scientists, health practitioners, and policymakers can use EHR data to evaluate the prevalence of chronic diseases among local children, to compare prevalence rates across subgroups and small geographic areas, and to examine changes in rates over time


[https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9004253/  ]

##### The utilization of EHR data:

can have multiple applications, including making aggregated census tract data on children’s health publicly available on an interactive webpage that allows policymakers and community organizers to examine current health patterns when developing public health strategies or community-based programs

 EHRs can also be combined with contextual data accessed from data sources such as the ACS or through partnerships with community organizations to provide a multidimensional understanding of the relationship between individual and neighborhood characteristics and health outcomes.

 large number ppl captured by the EHRs provide a unique opportunity to study small population subgroups and allow for meaningful population health comparisons across racial-ethnic, socioeconomic, and age groups

Using EHR data to evaluate patterns of specialty and emergency department use across subgroups and census tracts can also inform our understanding of inequities in health and health care use or quality (Beck et al. 2014, 2016; Rees et al. 2020).

[https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9004253/  ]



## General challenges of large data :

First, revealing all information at once will exceed human’s cognitive ability to conduct effective analysis.     Second, noises are prevalent in real-world datasets, thus the insights are common to contain artifacts as well. Thus, what analyst needs is a robust visualization technique that reveals the most general and salient patterns in the entire dataset.    

[https://lliquid.github.io/homepage/files/draft_vis18_bico.pdf]


### challenges of EHR



because EHRs are primarily used for administrative purposes, their structure can complicate data extraction and coding for population health studie .Furthermore, while developing the coding scheme for health conditions can be complex for EHRs, this information can be shared across research teams to reduce burdens and ensure consistency of health condition definitions across studies.

 information biases are introduced when patients seek specialized care outside of a health system or discontinue follow-up appointments, so that one system’s EHRs do not provide a full picture of individuals’ health profiles


 EHRs re made for adminestrative purposes
 
[https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9004253/  ]


EHRs were originally developed for billing purposes. However, their purview has expanded, motivated by meaningful use requirements expressed in the Health Information Technology for Economic and Clinical Health (HITECH) Act, part of the 2009 American Recovery and Reinvestment Act



Disease etiology. Whereas disease status is often well documented in EHRs, disease etiology, including fundamental causes of disease (70) (e.g., social, behavioral, environmental factors), is often not well documented

[https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6724703/]


#### free text and lack of ICD code

For example, Wasserman et al. (129) searched text notes for 465 children and found fever reported in 278 different ways (e.g., “fever,” “pyrexia,” “elevated temp”). One approach to deal with nuanced clinical text is to use open source natural language processing tools. These can extract text relevant to defining disease stage, severity, and progression or symptoms (6, 124), which may not be well captured by diagnostic codes. For instance, Andersen et al. (6) used natural language processing to extract suicidal ideation from clinical notes on >3 million Americans from 1700 primary care physicians and found that only 3% of patients with recorded suicidal ideation had a corresponding ICD-9 code.

https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6724703/  

#### Gaps

Researchers may find it difficult to interpret gaps in care in the EHR. When a patient lacks data, one cannot distinguish between patients who have left care, who have been well and have not sought care, or who have missed routine visits for other reasons. This ambiguity in whether patients are under observation is relevant to the person-time documentation required for estimating incidence rates. If patients enter care before an EHR has been implemented in a given system, some domains or events may not be captured and available for study (i.e., left-censored). Conversely, if they exit care, EHR data will lack information on events occurring after that time (i.e., right-censored)

https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6724703/  

##### inconsistensy 


For numerous reasons, the single appearance of a diagnostic code does not necessarily indicate that a patient has a disease. For example, in identifying chronic rhinosinusitis, Hsu and colleagues found that the positive predictive value (PPV) for the ICD-9 (International Classification of Diseases) code 471.x for nasal polyps was 85%, whereas 473.x for chronic sinusitis had a PPV of only 34% (54). With additional information—evaluation by an otorhinolaryngologist, for example—the PPV rose to 91%. The accuracy of disease definition is often improved by using ICD-9 codes and other information over time and is often better in relation to more severe disease (e.g., myocardial infarction). 


Even though diagnostic codes provide critical information on an individual’s health status, providers may not use them consistently, and the meaning of any given code may vary among providers and across time.

https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6724703/  

### bias of EHR, and realtion to Neighbourhood :

For example, when using EHRs to identify hot spots of disease or evaluate relationships between neighborhood characteristics and health outcomes, researchers and practitioners must account for selection biases related to who is captured in EHR data based on neighborhood characteristics, such as spatial proximity to adjacent health systems, racial-ethnic composition of neighborhoods, and poverty rates

[https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9004253/  ]


ability to access its services also shape entry into that health system such that the population included in EHRs is often not representative of the target population to whom reference is made (Bower et al. 2017). Prior work suggests that individual characteristics such as gender, age, race, ethnicity, socioeconomic status and health insurance coverage predict health system entry and utilization

Characteristics of neighborhood are also associated with health system entry in ways that may bias EHR-based analyses. Measures of social cohesion, safety, and the built environment are associated with the use of primary care services


The potential for neighborhood characteristics to introduce bias in EHR-based analyses is exacerbated by the relationship between those same characteristics and health outcomes. Both neighborhood socioeconomic characteristics (Carroll-Scott et al. 2013; Rees et al. 2020) and racial composition (Bell et al. 2006; Kotecki et al. 2019) are associated with the prevalence of a wide-range of children’s health outcomes, which in-turn drive entry into a health system. These characteristics also likely combine to uniquely shape health risks and access to care (Beck et al. 2020).

[https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6724703/. ]

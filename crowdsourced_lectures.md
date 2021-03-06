# Lecture 24, NYeC, SHIN-NY, 

## two shifts in NYC healthcare
* lowering the number of uninsured
* shift from fee for service to collaborative care payment and delivery model

## why does this matter?
* HIT opportunity, new IT tools to communicate and automate workflow
* millions of patients, some newly insured are encouraged to become proactive and engaged in health
* NYC healthcare market is remaking itself over the course of five years

## meaningful use
* set of guidelines, three stages, setup, data gathering, data sharing, clinical outcomes, early adopters get paid more
* 1.3 billion invested into SHIN-NY

## SHIN-NY system
* how to coordinate care, broad access to patient information
* secure messages, HIPAA compliance
* notification alerting and monitoring
* cross community care plan management tools 
* patient access to own health information and engaging consumer level health tools
* analytics to help manage and measure the healthcare system, can't improve what you haven't measured

## public utility
* middle ground as a quasi-governmental entity
* support from state government
* regulation to manage delivery of services and provide legal basis
* dial-tone services

## opt-in
* New York is an opt-in state
* no good reason for the opt-in

## patient pull queries
* more are signing up

## SHIN-NY, e-Collaborative
* succeeds with the cellphone model
* economically sensible model for sharing data
* reduces the cost of transaction
* uses patient data available to the network
* patterns of care that were good, not good, and emphasize the right ones

---

# Lecture 23 ted shortliff

## exam
* almost no one looks at the book
* what have you learned?

## what is the difference between HIT and biomedical informatics?
* there is a difference
* health information technology (EHR stuff)
* versus information exploration for health and human disease (genome sequencing and stuff)

## what is clinical medical informatics? what does it mean?
* what is informatics? use of information, cross disciplinary

## history of informatics, how far back do you have to go
* 1959, reasoning foundations for medical science
* El Camino hospital by lockheed, official system of the NIH
* 70's and 80's, CT scanner, Nobel Prize, term "informatics" comes up
* 90's, human genome sequencing project

---

# Lecture 22, careers in informatics, bob sideli

---

# Lecture 21, molecular epidemiology, clonal evolution, hossein khiabanian

## molecular epidemiology
* evolution of disease causing organisms
* dynamics of spread and transmission of pathogens
* genetic underlying of diseases
* role of selection in disease progression
* markers of prognosis and responses to therapy

## clonal expansion
* pervasive in nature, emerging infectious disease outbreaks, intra-host pathogen evolution, unregulated cell growth in cancer
* * dynamics of genomic heterogeneity yields insight into when an expansion started, how fast a population evolved, and selection in a particular host or treatment regime

## acute lymphoblastic leukemia
* refer to slides
* evolution of, refer to slides
* patients are forests of phylogenetic trees, moduli spaces
* genetic basis
* evolution of heterogeneity in disease course, treatment strategies vary from watchful waiting to systemic chemotherapy

## discovery of small variants out of background noise
* variants are due to independent errors
* used errors' sequencing depths to establish null hypothesis
* dilution experiments to discover error distribution
* discovery confidence
* discovery of subclonal mutations in CLL

## treatment is major selective pressure
* mutations were identified before the treatment became predominant tumor cell population at relapse

## dynamics of tumor evolution and selection
* allow statistical inference on spaces of phylogenetic tree
* rigorous framework for classifying tumor evolutionary behaviors
* selective pressures can spur tumor evolution and change the mode of its progression from linear to branched
* subclonal genetic lesions contain markers of prognosis and predict tumors' response to therapy

---

# Lecture 20, system biology, aris floratos

## systems biology
1. integrate complexity in a dynamically changing environment
2. how individual elements of a cell interact to generate behaviors that allow survival
3. discover how organisms function
4. key tasks: network reconstruction, network integration

## systems science vs reductionism
* how does it work, example computer
* do we want to fix it, or make it better?
* trade-off of functional information and ease of analysis 

## systems vs non-systems biology
* holistic approach
* discover emergent properties
* metabolic networks or cell signaling networks

## function elucidation
* can a model elucidate a system's function? 

## modeling gene interactions
* gene regulation
* regulation of transcription

## key tasks in systems biology
* network reconstruction
    * collect appropriate experimental data
    * develop algorithms for integrating data into network models
* network interrogation
    * exploit network properties (connectivity, topology, local and global structure) to answer interesting biological questions
* mapping gene regulation

## transcription and translation 
* refer to slides

## combinatorial regulation
* refer to slides

## what can networks tell us?

## differential gene expression
* identify gene expression programs that implement a specific phenotype

## enrichment analysis
* bubble size represents number of genes annotated to term
* network-based enrichment analysis

---

# Lecture 19, management and use of biomedical data, karthik natarajan

## collection of data
* outpatient data
    * visit, weight, blood pressure, urine, ultrasound, fetal heart monitor
* inpatient data
    * visit, vitals, delivery note, delivery log, anesthesia note, etc
* collected for...
    * billing, clinical care, legal, operational, regulatory, research

## data governance
* formal orchestration of people, process, and technology
* who should have access to the data
* what data are available
* quality of the data

## data integration and quality
* multiple MRNs
* outpatient and inpatient data
* external labs
* birth weight recorded in 3 documents

## data warehouses
* central, operational data extracts, contains business data for a specific function or area
* virtual, series of datasets or automated processes in place for implementing sites that allow SAS programs to be written and compared quickly

## improving access to data
* Eureka (cancer data management system)
* cohorts (participant management databases in longitudinal studies)
* observational medical outcomes partnerships (OMOP)
* word cloud
* CISearch (product classifier)

## big data
* hadoop, framework for distributed computing
* moves processing software to the data as opposed to moving data
* NYP incorporates this in-house

---

# Lecture 18, biological databases, richard friedman

## biology review
* refer to slides (DNA, RNA, protein function, nucleotides, codons)
* variance in the human genome
* sickle cell anemia

---

# Lecture 17 human-computer interactions (HCI), lena mamykina

## origins
* 1940s, focus on human-technology interaction came from need for more automated fighter planes, unfortunately, there was a lot of conflicting noise
* now, we know that human attention is limited, so use computing to better manage it
* 1970s, graphic user displays ushers in HCI

## why HCI? 
* technology is constantly changing in unexpected ways, sometimes obvious, other times not.
* people drive tech innovation through adoption
* there are often different tech innovations that try to solve the same thing, they have long lives because they are catering to different users
* tech can have significant socio-cultural impact
* e.g vacuum cleaner made cleaning easier, so the expectation for women cleaning was raised

## why HCI in biomedical informatics? 
* same unpredictability 
* e.g stethoscope was not warmly accepted, main complaint, separated provider and patient, this is the main argument against tech use (e.g. tablets, computers) in the clinical setting

## HCI encompasses...
* socio-cultural settings
* linguistics, psychology, design, science, frameworks from cognitive science, computers, engineering
* HCI gives us theoretical frameworks

## theoretical foundations
* norman seven stages of action, helps designers to think about how they should prioritize their efforts
1. forming a goal
    * gulf of execution
2. translating goal into a set of tasks
3. plan action sequence
4. execute actions
5. is it clear how users should operate the system to execute actions? 
    * gulf of evaluation
6. evaluate interpretations
7. interpret the outcomes
8. perceive what happened, "did I get what I wanted?"

## methods
* based off of the goals we create
* gets everyone on the same page 
* design often taken for granted 
* evaluation

## requirements
1. functional requirements 
2. non-functional requirements 

## requirement gathering
* observations of work
* interviews
* focus groups
* survey
* studying artifacts
* competitive analysis
* pitting different systems against each other
* qualitative, "what do people like?"

## requirement process
1. identify stakeholders
2. gain entry
3. de-familiarization
4. strip yourself of your assumptions
5. triangulation
6. use different methods to try to achieve the same results

## iterative design
* before: siloed process of design was difficult 
* minimum viable product 
* highest return on investment vs. risk
* minimum set of features needed to validate/invalidate your product
* deploy first, code later
* e.g. stack overflow, created a design that received rave reviews before the product was even created

## participatory design
* systems designed based on specification of management 
* things that were lost, qualities valued by workers 
* management, productivity, efficiency 
* solution, engage users in early prototyping 

## probes
* provocative design solutions intended to invoke a response 
* indirectly uncover hidden motivations, priorities, influences,evaluation, and expert evaluation
* you want feedback

## usability testing
* controlled experiments
* long-term adoption

## ubiquitous computing & technologies for health management
* using sensors to improve patient safety
* peripheral displays for provider to pull relevant information from patient record or literature

---

# Lecture 16, cognitive issues in informatics, vimla patel

## cognitive and social sciences
* cognitive science, multidisciplinary field incorporating theories and methods from psychology,linguistics, philosophy, anthropology, and computer science in the investigation of cognitive processes in human beings and machines
* interdisciplinary field comprising of cognitive and information sciences, with a focus on human cognition, mechanisms and processes, and the design of interventional solutions (often engineering and information technology related) that can improve human activities
* human behavior is influenced by our thoughts and values
* problems of changing behavior has always been an issue

## methods of data collection
* verbal reports
* recall and explanation tasks
* nautralistic data collection, team interactions

## methods of analysis
* task and activity analysis
* representations of ideas and concepts
* meaningful relations between ideas and concepts
* dialogue analysis for team communication/social network analysis

## cognitive science as related to biomedical informatics
* doctor patient communication and EMRs
    * eliciting patient stories in the waiting room
    * doctor patient interaction
    * sotries following interaction
    * follow up at home
    * technology needs to be sensitive to the patient's prior understanding of concepts
    * understand, not just listening
    * patient concepts and physician concepts are different in representing patient problems
* analysis of an adverse event with an CPOE, and designing safer systems
    * quality of user experience when interacting with a physician order entry system in the hospital
    * analysis of errors generated due to problems of user technology mismatch
    * analysis of covering provider and pharmacy
    * lack of alerts, inadequate clinical user training
* evaluation of a real-world environment using cognitive workflow methods and development of support technology
    * shadowing of medical team personnel during crucial periods pertinent to the individual
    * conducting brief interview to gain insight on infrastructure, roles, shifts, timing
    * obtaining log files of clinical information systems
    * mapping the activities to the ICU layout

## management of error in the ER
* making boundaries more visible to decision makers
* making efforts to counteract pressures that drive decision makers towards these boundaries
* technological support in the ER based on understanding of the boundaries that lead to human error

## lessons
* we need to understand the underlying cognitive explanations for what people do
* understand that explanations of behaviors, differences among individuals form the basis for proper design of such changes
* move to greater complexity in systems, consider smaller manageable tasks and need less complex systems
* education and training is essential


---

# Lecture 15, health IT policy and politics, david liss

## HIT and federal health policy
* different goals of policy makers
* expectations of policy makers for the next set of employers
* HIT is political
* lots of resources invested 
* patients are involved
* HIT is a bipartisan issue

## what needs to be fixed
* redundant diagnoses
* hospitalizations occur because patient information is not available
* payer costs, now providers
* hospitals and doctors, according to ACA, should pay for quality

## ACA primer
* increase access via expansion of state Medicaid, and creation of insurance exchanges
* mandated expansion of Medicaid was unconstitutional, therefore optional

## ACA exchanges
* designed for people to buy low cost insurance
* federal, federal/state, state exchanges
* color plans: bronze, silver, gold, platinum
* lower the premium, higher the OOP costs
* bronze as the lowest premiums, covers 60% of OOP, gradient upwards

## ACA HIT design issues
* no transport of data to commercial users
* no feedback loop from insurers to patients and government
* no feedback loop to patients
* no feedback loop to IRS 

## HIT policy direction
* focus is meaningful use
* get basic data from EHRs
* establish uniform processes for collecting and sharing
* basic infrastructure building and will continue through stages 2 & 3
* will it solve before mentioned problems?

## meaningful use
* is it enough?
* need a new focus on data
* free the data

---

# Lecture 14, health information exchange, gil kuperman

## health information exchange
* clinician transfer patient to another setting
* patient had care elsewhere
* remote data that is relevant
* non-direct care scenarios

## data availability
* clinical information missing
* data present outside the system
* information gaps present

## difficulties in exchanging data
* prevalence of EHRs, need more adaptation
* competitive concerns
* leadership, organization issues
* privacy
* technology constraints
* structure and coding
* financial sustainability 

## regional health information organization (RHIO)
* providers in a region should organize to tackle the challenges
* funding was available
* carried out

## Healthix
* master patient index links patients
* interface engine

## provider commitments
* needs to get consent
* provide appropriate use
* accept responsibility for breaches
* audit compliance

## challenges
* having enough data
* having too much data
* optimizing patient matching
* using data for research
* integrating health information exchange into workflow
* cost of technology
* cost of governance
* complex privacy model

## directed exchange
* supports referrals, transfers, public health
* less complex and expensive than RHIO
* leverages existing privacy models
* need directories of providers
* meaningful use stage 2

## structure and coding
* need standards
* need representation of concepts
* meaningful use is helping here

---

# Lecture 13, public health informatics, rita kukafka

## population health
* individual health vs population health
* population health perspective

## public health definition
* refer to slides
* 10 most needed public health services

## public health model
* refer to slides

## winnable battles
* tobacco
* nutrition physical activity
* motor vehicle accidents
* healthcare associated 
* teen pregnancy
* HIV/AIDs

## computers and information technology and public health
* syndromic surveillance
* PHR, EHR
* response requirements
* data sources
* dual benefits

## breast cancer stuff
* summary, refer to slides
* workflow, refer to slides

## chemoprevention stuff
* refer to slides

## current informatic solutions
* RealRisks decision aid
* risk discussion
* preventative risks

---

# Lecture 12, clinical research informatics (CRI), chunhua weng

## clinical research & patient care state
* need to accelerate research: bench to bedside
* need to reduce barriers 
* clinical research and patient care are siloed
* most efficient if research is a by product of the patient care process

## challenges
* time, after seeing patients, no time for research
* fragmented it systems
* messy data
* uncoordinated workflows
* tightened regulations
* poor software usability
* multiple stakeholders

## US CTSA consortium
* clinical translational science awards

## IOM learning health systems
* accelerated discovery and integrate into patient care process

## comparative effectiveness research
* more patient-centered
* uses observational data

## patient-centered outcomes research
* how is research relevant to real-world needs?
* patient guides research to problems that are relevant to them

## PCORI
* refer to slides

## methodologies for CRI
* systems thinking
* socio-technical design
* computational and symbolic methods: e.g. knowledge representation, nlp, database workflow
* recruitment is an issue
   
## socio-technical design
* refer to slides
 
## experience sharing
* refer to slides

## challenges for e-screening (study one, study two, study three)
* abbreviations, generic descriptions
* refer to slides "things we learned, " "lessons learned"

## eligibility screening framework & effectiveness
* social technical design
* certain tasks should be left to humans, some can be delegated to machines
* PPV is not great, NPV was 100%, with the e-screening system reduces physician workload from 125 to 23 patient screenings
* registries are essential, but it won’t help one in exclusion criteria
* which data source is higher in quality and more current?
    
## methods
* workflow process is important
* nlp, machine learning, informatics, etc
* intervention for physicians and patients

## e-facts
* interactive word cloud

## findings
* keep your stakeholders in mind
* use domain expertise
* engaging patients to share data, volunteer for research studies

## take home
* refer to slides

---

# Lecture 11, secondary use & predictive analytics, george hripcsak
* George Hripcsak was the lead designer of the Arden syntax

## purpose
* how do you take data from database and do research with that? what are the problems you encounter?
* EHR is rich with data
* lots of notes, lab tests, prescriptions, and facts

## benefits
* manually curated 
* can be used for patient recruitment
* large sample size
* long-term follow-up
* useful for fully EHR-based observational studies/interventional trials

## data quality
* thought 1: medical record information cannot be trusted as truth
* thought 2: data should only be used in the context in which it was created

## solvable challenges
* lack of penetration of EHRs
* promising: during bailout, $30b dedicated to EHR implementation (HITECH)
* barriers between systems 
* promising: HL7, CDISC
* privacy 
* promising: policy

## hard challenges
* quality of data
* meaning is often ambiguous or unknown
* accuracy 
* completeness 
* complexity (esp of disease ontologies)
* bias

## meaning
* PERRLA (pupils equal, round, reactive to light and accommodation) 
* study: how many doctors (1) knew the meaning of perrla, and (2) were using the term correctly? 
* looked at patients with only one eye, how many of these were labeled as PERRLA? only a few... however, PERRLA was often misused (e.g. "PERRLA in right eye")

## missing
* data is mostly missing
patients in the database are usually sick, hard to get a hold of for secondary research
* many patients are in the database, but do not have associated health information (e.g. diagnosis
* implicit information
* data is not evenly distributed, not measured on equal intervals
* they might have gone home
* they might have gone to a different hospital

## noisy/inaccurate
* inaccuracy can be as low as 50%
* documentary errors
* entering information into wrong medical record
* goal: process recorded information into a model that we can use, there are lots of opportunities for error though

## errors and complexity
* different data types, including narrative text
* abbreviations created on the fly 
* natural language processing makes things easier
* which is the right time to collect data?
* when the specimen was drawn, most ideal/almost never happens
* when specimen was received
* when test was performed
* when result was updated
* when result was received by the patient
* when patient told clinician
* when clinician wrote the note 

## biased and missing data
* feed-forward loop 
* data that is missing is often times not missing at random, all feeds back to patient state, reaction to therapy, test results, etc

## human interpretation
* 1990 study: inpatient mortality for community-acquired pneumonia 
question:  what happens when you get pneumonia at home and then go to the hospital? 
* sample: divided sample into 5 classes (1 to 5, 5 being most severe)
* outcome: how often do you die from pneumonia? (mortality %)
* original cohort: the more severe your pneumonia, the higher your chance of dying in the hospital (up to 27% chance), all of these mortality rates exceed fine predictions
* replication with EHR: EHR data suggests that if you are really sick (class 5) then you should go into the hospital because your mortality rate is lower than fine predictions
* problem: human interpretation! doctors probably did not collect all signs and symptoms of most severe class of patients, thus, they actually belonged in a lower class, (inflated mortality rates on lower end)
* further study: filtered out cases that seemed to have bias, only 10% of the data was left

## EHR-derived phenotype
* new tool to evaluate EHR data
* pull clinically relevant features of the EHR
* query combines information from multiple sources 
* long process 
* use phenotypes in correlation studies
* e.g. type II diabetes diagnosis
* diagnosis code (standard)
* medication administered
* blood sugar levels 
* human capital
* domain experts (e.g. clinicians)    
* knowledge engineer (e.g. informatics persons) 

## problem
* bias of developers
* generalizable 
* cost (time) 

## solution: high-throughput phenotyping 
* generate lots of phenotypes with minimum human intervention 
* eliminate case-by-case curation
* "physics" of medical record
* treat EHR as natural object
* study patient record (not patient)
* borrows methods from data simulation
* create sensors with different models measuring the same outcome of interest
* compare outcomes and improve model
* aggregate across units and model

## first study: predicting of glucose from blood sugar
* using my present blood sugar measure, what will it look like x days from now?
* available data: 25 years of lab tests 
* scales: tau (how many times did the doctor measure your glucose level during delta-t days?), delta-t (time measured from now)
* result = s
* ridges occur in 1-day cycles, location influenced by eating patterns and severity of diabetes 
* severe diabetes: check more often, thus, you have more frequent readings (higher tau) in shorter intervals (smaller delta-t)
* high predictability for low tau and low delta-t
* my glucose level today is highly predictive of my glucose tomorrow
* dip during the weekends because there are fewer readings being done (except by those who have more severe cases)

## implications
* waiting a long time does not erase all predictability, but waiting a short amount of time does, which seems counterintuitive
* severe disease, harder to predict glucose levels
* those with the highest number of measurements probably have the most severe disease
* if you get better, you will have fewer measurements (accidental normalization)

## study two: what happens when you don’t do any normalization? 
* (take all the data from the last 25 years and see what model pops out) 
* data: 22 years of data on 3 million patients
* 21 lab tests (measure sodium, potassium, bicarbonate, creatinine, urea,
* 60 concepts derived from signout notes (e.g. a treatment, a diagnosis)
written by residents caring for inpatient 
* calculation: lagged pearson’s correlation
* x-axis: months (2 months before concept, 2 months after)
* y-axis: lagged correlation

## definitional association
* when different concepts match what is being measured
* e.g. high sodium matches with bump in hypernatremia and dip in hyponatremia
usually when concept is identified, treatment kicks in, thus, you will often see lab measurements return to normal (0 correlation)

## intentional and physiologic associations
* aldactone is an anti-diuretic; helps body maintain potassium levels
correspondence between aldactone and hypokalemia 
* hypokalemia noted, aldactone concept comes into play, level of potassium increases past 0 
* physiologic association between hypomagnesmia and aldactone 
* if you don’t have enough magnesium (hypomagnesmia), body will not be able to retain potassium
* hypomagnsemia concept now realized

## timing of cause in disease vs. treatment
* enter lab for glucose problems, they will do a lot of tests, if they find pancreatitis, they will diagnose it

## health care process model 
* many things can go wrong when you’re trying to measure patient state
* one of the best ways to go about this is to create a health care process model to identify and use phenotypes of patient state
* all of these factors contribute to the measurement process  

## sparkline charts
* use of numbers and graphics in a timeline to convey patient state in a glance (e.g. lab data)
* can click on sparklines to get a better view of the data points in the series in sparkcharts, hemoglobin charts seemed to be a flipped version of the anemia charts (and vice versa), odd, because the concepts are basically measuring the same thing 
* hemoglobin was derived from blood tests
* anemia was derived from provide notes
* the look of the sparkcharts is sensitive to how variables/data were collected
* not just pairwise effects
* possible exploit sensitivity to improve phenotyping process?
* comparing measurement techniques to create a more automatic way of phenotyping

## statins and muscle damage
* retrospective research introduces confounding 
* data seems to suggest that we should take statin to lower total-ck which is the opposite conclusion 
* spike in red line = inpatient spike
* high ck when you are in the ER (beginning of admission) 
* you will not know if it is high if you do not have a baseline measure, when you are in the hospital, it will drop 
* total-ck is going to predict muscle damage (auto-correlation)
* tiny effect (close to the line), all statistically significant 
* total ck negatively predicts future ck (it is different from what it predicts now?)...what’s going on? 

## regression to the mean
* if you have a very high value, the next value will probably be lower, if you have a very low value, the next value will probably be high
* less statin when you order the test (right-hand side of graph) or when you have a high total-ck, tends to go towards negative correlation

## drug interaction example
* taking paxil and pravastatin together will dramatically increase glucose levels even though taking one or the other will have the opposite effect

## using associations and causes
## prediction
* who will get lung cancer

## explanation
* why do people get lung cancer

## intervention
* how to prevent lung cancer 

## prediction
* leads to machine learning

## study study set
* identify predictors
* identify outcomes
* use regression to come up with an algorithm
* when an individual comes in, you can take their predictors, plug it into your model, and predict an outcome
* e.g. readmission

## financial incentive 
* control costs by paying for admission and not per day
* loophole: send patient home early and readmit
* solution: penalize for readmissions
* goal: reduce readmissions
* interventions are costly (many avenues: medical, social, educational)
* target resources
* readmission prediction
* who will be readmitted
* why are they being readmitted 
* heart failure? chest pain? bleeding?
* look at more proximal causes of readmission
* what data is the most predictive of readmission?
* look at different cohorts

## performance 
* predictive ability
* look at ROC curve 
* how good is the system/model at distinguishing outcomes? 
* probability of choosing a patient more likely to have a disease given a * series of dichotomous choices (e.g. test +, test -) 

## calibration 
* is predicted probability accurate? 
* orthogonal metrics
* correct rank, but all probabilities are wrong 
* e.g. good predictive value, but poor calibration
* all cases have same probability/prevalence
* e.g. good calibration, no predictive value

## predicting the probability of readmission
* roc = 0.5 is chance
* roc = 1 is perfect
* roc = 0 is also perfect, but with the opposite conclusion

## data sources for prediction
* lab tests
* visit history
* prior diagnosis codes (IC9)
* demographics
* social/mental health keywords 
* e.g. "do you have someone at home to take care of you?"
* other clinical keywords
* overlap in charts suggests redundancy of sources, thus, social/mental health keywords are the hardest to use to predict

## effect of cohort on performance
* who you train and test on has a huge effect on performance
* effects of individual cohorts may not be predictive of all admissions
* using all patients will give you pretty good predictive ability to see who will be readmitted
* using patients conditioned on CHF, however, will decrease predictive ability
* same algorithm, different definition of a cohort: performance of your algorithm changed

---

# Lecture 10, natural language processing, carol friedman

## goals of NLP
* process text info using linguistic knowledge
* capture massive amounts of information
* standardize information
* facilitate data entry and data retrieval processes 
* improve practice and understanding of medicine

## why is NLP important
* alot of the communication in medicine is word form
* lots of clinical data and biomedical literature to explore
* NLP is high throughput tech
* enables new functionality 
* perform automated intelligent applications (e.g. decision support, discovery) 

## types of information
* structured
* "increased rt hilar adenopathy" 
* problem, change, body-loc, code, region, certainty, time 
* unstructured 
* usually found in clinical notes
* many abbreviations
* lack of punctuation
* spacing is inconsistent 
* meaning of punctuation is ambiguous
* lack of headings of separation between sections
* missing information
* initials vs. abbreviations 

## clinical applications of NLP
* find patients with specific conditions or treatments
* find clinical associations/trends
* improve patient safety
* coding for billing, primary driver
* provide patients with tailored info
* create problem lists from notes
* structured information can be limiting 

## bio applications of NLP
* improve lit search (by searching for genes/diseases)
* extract biological relations from literature (gene-drug, gene-gene, disease-drug)
* discover new knowledge (merge and connect info across articles)

## forms of knowledge used
* non-linguistic knowledge
* varies with different information systems/applications

## forms
* mark-up and non-ASCII text
* tabular 
* structured information
* meta-info
* difficulties with non-linguistic knowledge
* section recognition
* end of sentence recognition (more than just identifying periods)
* meta-information recognition 
* linguistic knowledge 
* requires understanding of semantics
* varies between genres 
* requires world knowledge, which also depends on domain 

## forms
* phonetic
* letters + phonemes = sound = speech
* morphology
* combining units to make words 
* convenient because medicine is rich in greek and latin morphemes
* pay attention to irregular transformations (e.g. go and went, bring and bring)
* requires morpheme-lexeme relation
* syntax: lexicon
* answers the question: "what is a word?"
* classifying words based on syntactic (e.g. noun, verb) and semantic 

## categories 
* challenges include, recognizing words (generally separated by ""), conventions in English vs. conventions in medicine, multi-words 
* conventions in medicine vs. conventions in biology 
* one word can have multiple parts of speeches 

## syntax structure
* structure of phrases and sentences (e.g. np vp)
* challenges, clinical text is often different from conventional text
subject is often missing, verb is often missing, determining correct structural relations from text (e.g. the patient was ready to eat vs. the chicken was ready to eat), recovering omitted information/filling in the blanks

## semantic 
* meaning of words, phrases, sentences
* words can often be placed into semantic categories (e.g. gene, medication, body location, disease)
* challenges, sometimes meanings do not combine (e.g. idioms), abbreviations can often mean multiple things (e.g. ms), words can often have multiple meanings, many standard vocabularies available for use in clinical database, no vocabulary is complete, mapping between languages is difficult because many abbreviations overlap, capturing complex relations (need for logic)
how do you take words out of a narrative and translate it into a clear knowledge representation?

## solutions?
* efforts to standardize meaning by controlling formal representation of information, database relations, semantic networks, XML, conceptual graphs, pragmatics 

## context affecting meaning
* generally, we assume that ordering of text reflects time of events 
challenges
* "mass" has different meanings across specialties 
* determining correct references
* "it" is often used often and ambiguously 
* world knowledge 
* knowledge affecting meaning
* recognition of named entities within a domain
* e.g. "mass" means mass in lung in chest xrays
* e.g. "mass" means mass in breast in mammograms
* recognition of named entities within a section

---

# Lecture 9, technology for patients and health consumers, noemie elhadad

## patients taking charge of health
* participatory medicine
    * patient engagement
* peer to peer healthcare
    * clinical expertise
    * user generated content

## technology enables
* access
* data-generation
* allows patients to reach each other
* engage institutions

## personal health record
* owned and maintained by the patient
* repository of user information
* also has user generated data
* Google didn't catch on

## quantified self
* mHealth movement
* ginger.io
* mood rhythm
* jawbone
* apple health

## community level data
* how to detect sarcasm?
* how to parse out comments?

## research questions
* information needs
* health behaviors
* impact of health technology
* intervention tools we can design
* e.g cancer stage prediction
* e.g emotion detection in chat support groups
* e.g identifying topics of discussion
* e.g salient aspects of health

## online reviews of providers
* capture patient satisfaction
* analyze health consumer attitudes
* tools to manage, analyze, and understand

## methods
* LDA, Latent Dirichlet Allocation
* LDA experimental setup
* LDA results

## content analysis
* psychiatric diagnosis
* suicide note analysis
* coping mechanisms
* text-based predictions
* network-based prediction
* machine-learning supervised techniques

## network based prediction
* nodes, participants
* edges, level of interaction between patients
* find interactions between patients
* participant weights
* train a classifier with features

---

# Lecture 8, clinical decision support, herb chase

## in the news
* clinical decision support tool helps pediatricians prioritize guidelines, ultimately improving screening for developmental delay in children 

## CDSS
* computer system that assists in decision making
* "to err is human"
* the five rights, right info, right person, right format, right channel at the right time
* different types of errors
* failures in treatment and management
* failure in following guidelines

## Libby Zion case (CDSS in treatment)
* drug interactions
* solution: CPOE? 

## CPOE
* simple rules
* use of tables
* use of alerts
* usage of CPOE, alerts are overridden
* may not fit in workflow

## diabetes care example (CDSS in chronic disease management)
* identify diabetes
* identify HbA1c score
* create HbA1c rules
* need to have clear terminology and codes
* coding is incomplete, may need NLP
* hopefully improve therapy, diagnoses, and adherence to guidelines

## NLP
* unambiguous
* abbreviations and fragment mapping
* code mapping, set of rules, simple tables

## CDSS in diagnosis
* matching
    * drug to drug interactions
    * tables
    * information retrieval
* pattern recognition
    * user inputs signs and symptoms
    * identification of signs and symptoms
    * differential diagnoses
* prioritization
    * getting up to speed with tons of data
    * patient medical history (PMH)
    * key elements of PMH
    * word cloud example
* prediction
    * assess patient status
    * methods of machine learning
    * structured data and unstructured data
* decision analysis
    *  what drug to use?
    *  find probabilities
    *  find outcomes
    *  prioritize decision choices
    *  modify based on patient preferences
* cognitive biases
    * define knowledge representation
    * different levels of human representation
    * limitations of machines
    * data is key

---

# Lecture 7, probability theory and decision making, david vawdrey

## patient diagnosis and the probability problem
* hence why med language is very conservative ("likely", "moderate", "probable")
* sick patient, observe, diagnose
* disease likelihood, test, adjust likelihood 
* diagnostic tests reduce uncertainty

## management after the test
* order more tests
* make recommendations for patient
* based off of test and personal judgment
* co-morbidities
* cost-benefit analysis
* available resources

## in-class problem
* if a woman has a positive mammogram, what is the probability she has breast cancer?, p(d+|t+)
* 1% women who participate in routine screening have breast cancer
1 in 100 women = prevalence, population 10,000
* 80% women with breast cancer will have positive mammograms, p(t+|d+)
* 9.6% of women w/o breast cancer will have positive mammograms, p(t+|d-) 
* positive test = 80
* TP = 950 
* type I FP = 1030
* 80/1030 = .078 PPV p(d+|t+)
* negative test = 20
* type II FN = 8950
* TN = 8970
* 8950/8970 = .997
* NPV p(t-|d-)
* total, 100, 9900, 10000
* 80/100 =.8, sensitivity p(t+|d+), 
* 8950/9900 = .994, specificity p(t-|d-)
* based on the fact that you had a +ve mammogram, your chance of getting breast cancer is 1 out of 13

## interpreting a positive test 
* important to consider: (1) prevalence of disease, (2) false positives
doctors often do not realize that p(d+|t+) is not p(t+|d+).

## bayes’ theorem/assumptions
* conditional independence
* p(x|y, z) = p(x|z)
* once we know z, the value of y does not add any additional information about x
* many factors determine risk of disease, but we assume that once we know something about the test status, we can apply this directly to our knowledge about disease

## completeness
* only two outcomes possible for disease and test result (positive or negative)
* mutual exclusivity 
* patient be diseased and non-diseased at the same time
* patient is clearly positive or negative
* in reality, tests are not conclusive, my test result can be "more positive" than yours because it is based off of continuous values

## use of sensitivity, specificity, PPV
* trade-off between false negatives (missed cases) and false positives (misclassified cases) 

## validation tests
* gold standards are expensive, time consuming, uncomfortable, risky 
* e.g. biopsies, surgeries, autospies

## tests are based off of continuous values
* shifting the cut-off to the right 
* fewer false positives, higher specificity 
* more false negatives, lower sensitivity 
* shifting the cut-off to the left 
* more false positives, lower specificity
* fewer false negatives, higher sensitivity 
* sensitivity and specificity are characteristic of a test and the criterion for when to call the test "abnormal."

## receiver operating characteristic (roc) curves
* b is more discriminative than a (lower false-positive rate for any value of true-positive rate)
* purpose is to determine a reasonable cut-off value
* minimize false negatives and false positives aka maximize sensitivity and specificity 
* note: choice of test depends on (1) disease in question, and (2) purpose of testing
* e.g. prostate cancer screening: chances of false positive are common, therefore, opt to maximize specificity
* other factors: cost, risk, discomfort, and delay
* each point on the curve corresponds to a potential cut-off level 
* area generally ranges from 0.5 to 1.0
* area = 0.5 (diagonal line)
* test cannot distinguish between diseased and non-diseased
* area = 1.0 (vertical line)
* perfect sensitivity and specificity

## decision analysis & uncertainty
* decision trees are used to find the option with the greatest likelihood of success

## criteria
* survival (duration of life after therapy)
* utility (depends on patient quality of life preference)

## standard gambling technique
* probability of ideal health vs. probability of immediate death
* time-trade-off technique
* length of time in ideal health = time in disease state
* quality-adjusted life year (QALY) = utility * duration of benefit
* benefit = survival time in good health

## utility theory
* value of a gamble ~ expectation of individual’s valuation of the outcomes
* choice also depends on whether individual is risk-averse or risk-taking

## heuristics and biases
* sunk cost: a retrospective cost that cannot be recovered
* overly optimistic probability bias (overestimation of reward)
* increased risk due to feeling of personal responsibility 
* availability
* representativeness
* probability transformations
* effect of description detail
* anchoring and adjustment

## random thoughts
* hypothetico-dedutive approach to diagnosis is subject to personal heuristics

---

# Lecture 6, informatics in global health, olivia velez

## dissertation
* design and usability of a mobile health application for midwives in rural ghana

## problem statement
* midwives in Ghana provide the majority of rural healthcare services but have limited access to data for decision making
* few mobile health (mHealth) applications have been designed for midwives, most designed for outside health workers
* the study purpose was to design and test an mHealth application (mClinic) that can improve data access and reduce the heavy reporting burden for midwives at the millennium villages project site in Ghana
* what does your ideal system look like? what do you want to achieve?
* how do you make a system to a user that is relevant? 
* what resources and technology currently exist within context? 
* what needs to change within the current system?

## data sources
* observations of staff
* interviews with staff 
* investigator field notes
* literature review
* mClinic

## CHW using SMS program for data input
* registering children
* nutrition tests
* prescribe treatments
* data goes to central server to be pushed up to district government
results
* midwives liked it but were concerned about technical self-efficacy
* no funding to implement
* probably would not continue development on android

## considerations
* how do you facilitate trainings when there is a high turnover rate for housewives 
* who will maintain the computer system when human capacity is limited? 

## maternal & child survival program
* USAID's flagship maternal, newborn, and child health program
* 5 years, $500 million, 24 priority countries
* objective: eHealth solutions for improved equity in reproductive, maternal, newborn, and child health (RMNCH) programs are incorporated in a systematic way into country health systems

## challenges
* alot of developing countries don’t have policies
* don’t have standard terminologies
* pilotitis: over-proliferation of similar apps 

## who funds global health informatics?
* USAID, PEPFAR, DFID, Gates foundation, Rockefeller foundation, other donors/foundations

## who implements/supports ghi?
* NGOs, consulting firms, CDC, social enterprise startups, country governments, universities, WHO/UN

## what are the health issues being addressed?

## tools & developments
* eLearning tools 
* EHR, electronic health records
* CDS, clinical decision support
* LMIS, laboratory management information system
* MBCC, mobile behavior change communication
* conditional cash transfers

## why invest in ghi?
* people don’t take their anti-malarials properly, use MBCC
* providers don’t prescribe anti-malarials properly, use CDS
* stock is out, use LMIS
* resistance development, use real-time monitoring
* providers aren’t getting paid, use ?
* counterfeit medications, use barcode scanning

## understanding the enabling environment for ehealth - patient tracking framework
* baseline assessment

## situation analysis 
* what is going on at the health facility?
* m/eHealth inventory
* do similar projects already exist in the space? 
* are they also managing other projects? 
* enabling environment assessment 
* what structures do they already have in place?
* if exist, use; allow countries to have ownership

## health information and communications (ICT) strategy
* RMNCH ICT framework
* theory of change, monitoring and evaluation (M&E) plan
* national coordinating mechanism
* addressing enabling environment gaps
* capacity
* policy
* standards & interoperability
* the endless cycle of siloed and holistic funding schemes!

## patient tracking considerations
* collaborative requirements development methodology (CDRM)
* who are the partners in-country that contribute to the system
* what policies need to be in place?
* what is core functionality required across systems?
* what data is needed and how do we improve the quality of data collected in * the community and needed at the facility, district, subnational, and national levels?

## data collection examples
* surveys
* routine reporting
* surveillance
* checklists
* observational assessment
* SMS text response
* interactive voice response (IVR)
* qualitative

## "open concept data dictionary" (?)
* budget
* available hardware
* operating system platforms
* data entry software/open source?
* in-country communication tech
* skill of users
* translations
* back end database support

## interesting projects
* Jamii Smart, 
* Ampath, 
* d-tree, 
* Commcare,  
* Baobob, 
* Motech Suite, mobile
* OPENMRS, open medical record system
* OPENHIE, open health information systems
* OPENSRP, data collection in tablets

## issues
* pilotitis/moratorium
* scale-up-fever
* lack of evidence
* who are the funders/donors
* customization vs. standardization

## contact information
* olivia.velez@icfi.com
* MCSP: http://www.mcsprogram.org
* ICF: http://www.icfi.com

## greentree principles
* compilation of lessons learned when implementing information and communications technology abroad 
* design with the user
* understand the ecosystem
* design for scale
* build for sustainability
* be data driven 
* open source and open standards
* reuse and improve
* address privacy and security
* be collaborative

---

# Lecture 5, standards, virginia lorenzi

## why are standards important? 
* useful when things can be reused, shared with others
* promote interoperability and connect things
* take up standards in order to make your work better, easier, and safer!

## in health informatics
* healthcare is complex
* healthcare is risky
* healthcare is expensive
* healthcare requires communication and coordination (transfer of information between stakeholders)
* healthcare informatics can enable better healthcare
* analytics is not possible without standard terminology

## role of standards in HIT
* measures and improves quality 
* measures and improves safety 
* improves population health (immunizations, surveillance)
* personalized med
* expediting research
* provides advanced privacy and security 
* information exchange

## where do standards come from?
* ad hoc
* de facto
* government mandate
* consensus (semantic harmonization)
* hard and time consuming
* need to make sure its worth it (what's the need)
* lots of people, stakeholder engagement crucial
* standards development best practices

## HL7 standards
* balloting is one way to get feedback from 'standards users'
* standards development organizations - standards developers exists!

## examples
* International Organization for Standards (ISO)
* European Committee for Standardization
* Health Level 7 (HL7), a set of international standards for transfer of clinical and administrative data between hospital information systems
* Clinical Data Interchange Standards Consortium (CDISC), has open data standards
* International Health Terminology Standards Development Organization
* NEMA, medical imaging technology
* GS1, standards company

## meta-standards organizations
* joint initiative council
* integrating the healthcare environment
* open EHR
* world health organization

## national standards related bodies 
* ANSI, AFNOR, DEN, BSI, Canada Infoway, US ONC, etc
* standards to support exchange of clinical information
* HL7 version 2 messaging
* clinical domains such as all kinds of orders, results, demographics, etc.
* this standard has widespread adoption across the world
* many interfaces today at NYP hospital alone

## HL7 version 3:
* Reference Information Model (RIM), foundation of v3
* messaging (all clinical and supporting domains)
* really heavy, a lot of structure
* clinical document architecture (CDA)
* human readable, render it on a screen
* structured
* consolidate CDA, implementation guide on top of CCD
* standards for claims processing
* communicate about claims and eligibility
* communicate about charges and accounts

## structured documents
* CDA, CCD, CCDA, QRDA, progress notes, drug labels, genetics
* services - common terminology service api, record locator service api.

## definitions
* DICOM, standard for imaging
* HL7 CCOW, clinical contect object workgroup
* ASTM CCR, continuity of care record
* CDISC, standards to support exchange of information to support research
terminology standards to support the exchange of clinical information
semantic content and vocabulary
* LOINC, logical observation, identifiers, names, and coders
* SNOMED-CT, problems, answers, clinical terms, systematized nomenclature of medicine-clinical terms

## international health standards organization
* HL7 UCUM, units of measure
* HL7 UNII, RXNORM, SNOMED, allergies
* HL7 CVX, immunizations
* national library of medicine value set authority for mu

## decision support languages, Arden syntax
* used in proprietary EHRs to create alerts
* embed medical logic into system
* what should an EHR have?
* motivators, facilitators, and catalysts needed for widespread adoption
* market forces, business needs
* peer pressure: showcases, "connectathons", certified EHRs
* tools to help with adoption

## government forces
* grants
* incentives and penalties
* support for standards development, testing, adoption
* regulations requiring interoperability
* regulations requiring standards
* us government forces

## HIPAA
* electronic exchange of administrative data using standards
* security and privacy measures
* "that's the future of healthcare...Walgreens"

## incentives program regulation
* stage 1, data capture and sharing
* stage 2, advanced clinical processes
* stage 3, improved outcomes

## open government work
* NHIN direct
* HISP, health information services provider
story of 3 standards
* HL7-v2, under designed (a hack), too simple, too loose
* HL7-v3, over designed, too complex, too constrained
* HL7 FHIR, "just right"
* easy to understand specifications
* easy to extend and adapt resources

---

# Lecture 4, clinical information systems I (repeat), david vawdrey 

---

# Lecture 3, culture of healthcare, peter stetson 

## background
* not a linear relationship between cost and efficiency
* price and quality are also not linear relationships
* aim to reduce cost but keep quality (value = (quality/cost) * efficiency)
* consumerism as disruption (Tylenol costs $500), variations in service
* CMS publishes data publicly (hospital cost data)
* outpatient case (times article) 
* quality tiering performance

## example charges and steps
* medical bill
* medical history
* physical exam
* data & lab review
* medical decision making
* professional bill

## where do these charges originate?
* doctor takes care of patient
* fee for service, a doctor gets paid by the services provided
* i.e. if they find more wrong with you, they charge you more
* bill is sent to billing office
* bill goes to payor, then to patient

## lifecycle of bills, failure points
1. % denials by payor
2. days in A/R
3. charge lag
4. % recovered

## important changes afoot and implications
* refer to slides 
* performance management

## meaningful use questions
* refer to slides

## mechanisms to drive down costs
* local accountability, accountable care organizations
* they are not insurance; they are the delivery network
* return on investment for ACO and hospital, they ask Medicare for cash, whatever the hospital saves is split between hospital and the ACO

## exchange programs
* infusion of cash if more people buy into insurance system

## important measures
* which measures have the highest value?
* which measures would best cover 9 difference performance programs?

## older model
* percent breakdown of hospital activities

## alternative models
* can't qualify for 'subsidies' unless you meet revenue thresholds ("performance-based compensation plans")

## standard measures
* population health management
* genomic medicine
* team-based learning
* decision clinical support systems
* build more peripheral applications to help manage care
* natural language processing
* doctor patient communication
* doctor patient hospital interaction
* process improvement and optimization

---

# Lecture 2, clinical information systems I, david vawdrey

## EHR facts, benefits, future, barriers, adoption, cost-benefit
* refer to slides

## paper records, medical errors, legibility errors
* refer to slides

## EHR functions
* results review
    * aggregate data
* orders
    * CPOE
* documentation

## EHR architectures
* refer to slides

## HIMSS (Health Information Management Systems)
* mission, to lead healthcare transformation through the effective use of health information technology
* membership, 23,000 individual members, of which 73% work in patient care delivery settings, 380 corporate members, 30 not-for-profit organizations
* products, IT News, Industry research report, no vendor comparisons or product reviews

## KLAS 
* provides accurate, honest, and impartial ratings of healthcare technology to help providers make informed decisions
* independently owned and operated 
* survey current users of EHRs, scores for 25 questions, total score is based on 100-point scale

## NYP architecture, EHR, Allscrips, CDSS, tabs, patient focus
* refer to slides

---

# Lecture 1, intro to biomedical informatics, david vawdrey

## informatics
* science of processing data for storage and retrieval, information science
* important due to rising healthcare costs
* safety, quality, and efficacy of healthcare can be improved
* healthcare is inequitable, we want to improve access

## AMIA
* AMIA views "biomedical informatics" as the name of the core scientific discipline and uses the term "health informatics" to capture applied research and practice in clinical and public health informaticss

## structure of informatics
1. bioinformatics
2. imaging informatics
3. clinical informatics
4. public health informatics

## timeline of informatics
* refer to slides

## funding of informatics 
* refer to slides

## important federal legislation
* refer to slides

## medical/clinical records
* medical observations that are recorded so that the medical history of the patient can be ascertained (Hippocrates example)
* clinical notes history, standardization and birth
* problems in clinical notes, abbreviations, paper-based, etc

## computer-based medical records
* the electronic health record (EHR) is a longitudinal electronic record of patient health information generated by one or more encounters in any care delivery setting, it contains a variety of information
* uses and benefits of EHRs are numerous, refer to slides
* barriers to adoption, refer to slides
* vs paper records, and how it increases medical errors
* errors can still occur in both but computers give a standard format

## meaningful use
* the American Recovery and Reinvestment Act authorizes the Centers for Medicare & Medicaid Services (CMS) to provide a reimbursement incentive for physician and hospital providers who are successful in becoming "Meaningful Users" of an electronic health record (EHR)
* incentive is up to $44,000/practitioner ($19B total allocated by HITECH)
* incentive payments begin in 2011 and gradually phase down until 2015, when non-adopters will be subject to financial penalties under Medicare

## cost impact of EHR usage
* needs to be paired with clinical efficiency methods
* costs of ongoing maintenance
* potential quality improvements and practice variation
* limited quantitative research is available


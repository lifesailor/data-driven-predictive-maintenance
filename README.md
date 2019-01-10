# Predictive maintenance

A curated list of predictive maintenance resources. Inspired by [awesome-ml](https://github.com/sdukshis/awesome-ml) and [awesome-anomaly-detection](https://github.com/hoya012/awesome-anomaly-detection). 





## What is predictive maintenance?

[Predictive maintenance(PdM)](https://en.wikipedia.org/wiki/Predictive_maintenance) techniques are designed to help determine the condition of in-service equipment in order to predict when maintenance should be performed. 

The main promise of predictive maintenance is to allow convenient scheduling of corrective maintenance and to prevent unexpected equipment failures. The key is "the right information in the right time". 

[Prognostics](https://en.wikipedia.org/wiki/Prognostics), [Fault detection](https://en.wikipedia.org/wiki/Fault_detection_and_isolation) is similar concept to predictive maintenance. 







## Table of Content

1. Concept of predictive maintenance 

2. Predictive maintenance depending on the type of data.
   1. Vibration
   2. Sound

3. Predictive maintenance technique

   1. Signal Processing
   2. Machine Learning
      1. Classification
      2. Fault Detection






## 1. Concept of predictive maintenance

#### Publication

- An introduction to predictive maintenance | R.Keith Mobley | **[Elsevier Science(USA)' 2002]** | [pdf](http://www.irantpm.ir/wp-content/uploads/2008/02/an-introduction-to-predictive-maintenance.pdf)

  - This book clearly explains key concepts and basic techniques of predictive maintenance. At the first part of the book, it is explained that why predictive maintenance is important and how to justify it in financial aspects. The second part presents various techinques for each data type. Vibartion analysis, thermography, tribology, process parameters, ultrasonics, visual inspection, operating dynamics analysis are described in each chapter. 
- A Survey of Data-Driven Prognostics | Mark A. Schwabacher |**[NASA Ames Research Center' 2006]** | [pdf](https://arc.aiaa.org/doi/abs/10.2514/6.2005-7002)



#### Slide

- Introduction to Prognostics | N.Scott Clements | **[Annual Conference of the PHM Society' 2011]** | [pdf](https://www.phmsociety.org/sites/phmsociety.org/files/Tutorial%20Prognostics%20Clements.pdf)
- Introduction to Prognostics | Kai Goebel, Abhinav Saxena, Matt Daigle, Jose Celaya, Indranil Roychoudhury, Scott Clements |**[NASA Prognostics CoE' 2012]** | [pdf](http://ftp.phmsociety.org/sites/phmsociety.org/files/Tutorial_Prognostics.pdf)
  - The above slides explain prognostics is estimation of the remaining useful life of a component. Remaining useful life of a component can be expected to continue operating within its given specifications. The brief explanation of three methods for prognostics are provided.



#### Essay

- (ko) 2017 PHMAP Conference Review | Seulgi Lee | **[Data Mining & Quality Analytics Lab]** | [html](http://dmqm.korea.ac.kr/board/view.asp?B_CATEGORY=0&B_CODE=b_cReview&tID=105&sid=125&search_category=&searchstring=&gotopage=1&IDX=241)
  - I lack mechanically engineering and physical background. Such knowledge, of course, may be necessary, but the important thing is to properly predict the failure of the equipment. This resource gave me the courage to approach the problem as a data scientist, not as a mechanical engineer.





## 2. Predictive maintenance depending on the type of data

### 1. vibration

#### Slide

- Beginning vibration analysis with basic fundamentals | Jack Peters | **[CTC' 2015]** | [pdf](http://www.ctconline.com/pdf/pubTechPapers/01-Beginning%20Vibration%20Analysis.pdf)



#### Video

- Vibration Analysis Know-How: Quick Intro to Vibration Analysis | Jason Tranter | **[LUDECAINC' 2015]** | [Youtube](https://www.youtube.com/watch?v=ZyIyWrHVFkA)
  - Provides good introduction to vibration analysis



#### Publication

- Vibration Analysis and Diagnostic Guide | Jaafar Alsalaet | **[Unversity of Barash' 2012]** | [pdf](https://www.researchgate.net/profile/Jaafar_Alsalaet/publication/311420765_Vibration_Analysis_and_Diagnostic_Guide/links/584556ba08aeda696819fbb4/Vibration-Analysis-and-Diagnostic-Guide.pdf?origin=publication_detail)
  - Provides good introduction of traditional vibration analysis in English.
- (ko) Vibration and Equipment Handbook | Byungjoon, Lee | **[Korea Electronic Power Corporation' 1998]** | [pdf](http://www.incosys.co.kr/index.php?option=com_content&view=article&id=1057&Itemid=482)
  - Provides good explanation of traditional vibration analysis in Korean.
- (book) Structural health monitoring: a  machine learning perspective |Charles R. Farrar, Keith Worden| **[John Wiley & Sons, Ltd' 2013]**| [pdf](https://onlinelibrary.wiley.com/doi/book/10.1002/9781118443118)
  - Machine learning for vibration analysis.
- Deep Learning and Its Applications to Machine Health Monitoring: A Survey | Rui Zhao, Ruqiang Yan, Zhenghua Chen, Kezhi Mao, Peng Wang, and Robert X. Gao | **[IEEE Transactions on Neural Networks and Learning Systems' 2016]** |[pdf](https://arxiv.org/abs/1612.07640)
  - Deep learning for vibartion analysis.

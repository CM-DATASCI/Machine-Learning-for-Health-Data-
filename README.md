# Machine-Learning-for-Health-Data-

Breast cancer is the second leading cause of cancer deaths in women after lung cancer in the US and Europe [1, 2] and has the highest incidence rate among all cancers in women worldwide [3]. The most recent figures from the American Cancer Society indicate that about 268,600 and 62,930 new cases of invasive breast cancer and carcinoma in situ (CIS), respectively will be diagnosed in women in 2019 [1]. In its early stages of development, breast cancer is asymptomatic making it difficult to detect. However, early detection can increase survival rates from 56% to 86% [4]. Mammographic screening, a technique in which low-energy X-rays are used to examine the breast, has been attributed with the increase in incidence and a better survival rate in women aged 50-69 [5-7]. 

Computer-aided diagnostic (CAD) tools have been investigated previously as a means to predict the true malignancy of masses identified in mammograms in order to prevent unnecessary follow up procedures [8-10]. To add to this existing work, in this study I have employed the use of two supervised learning classifiers – a decision tree and a K-nearest neighbours – on data derived from full field digital mammograms obtained from the UCI Machine Learning Repository [11]. The data for these patients were collected at the Institute of Radiology of the University Erlangen-Nuremberg between 2003 and 2006. It consists of the following features: A BI-RADS assessment score which is based the system used to describe the radiographer’s findings on mammograms and to assign a final assessment category [12] (see table 1 for details); The patient's age; Three BI-RADS attributes related to the mass of the lesion seen in the mammogram (shape, margin and density). 

1.	Society, A.C. 2019; Available from: https://www.cancer.org/cancer/breast-cancer/about/how-common-is-breast-cancer.html.
2.	WHO. Breast Cancer Rates in Europe. Available from: https://gco.iarc.fr/today/data/factsheets/populations/908-europe-fact-sheets.pdf 
3.	WHO. Breast Cancer Rates - the world. Available from: https://gco.iarc.fr/today/data/factsheets/populations/900-world-fact-sheets.pdf.
4.	Montazeri, M., et al., Machine learning models in breast cancer survival prediction. Technol Health Care, 2016. 24(1): p. 31-42.
5.	Verdial, F.C., et al., Demographic changes in breast cancer incidence, stage at diagnosis and age associated with population-based mammographic screening. J Surg Oncol, 2017. 115(5): p. 517-522.
6.	Lauby-Secretan, B., et al., Breast-cancer screening--viewpoint of the IARC Working Group. N Engl J Med, 2015. 372(24): p. 2353-8.
7.	WHO, WHO Position Paper on Mammography Screening, in World Health Organisation. 2014.
8.	Baker, J.A., et al., Breast cancer: prediction with artificial neural network based on BI-RADS standardized lexicon. Radiology, 1995. 196(3): p. 817-22.
9.	Elter, M., R. Schulz-Wendtland, and T. Wittenberg, The prediction of breast cancer biopsy outcomes using two CAD approaches that both emphasize an intelligible decision process. Med Phys, 2007. 34(11): p. 4164-72.
10.	Shan, J., et al., Computer-Aided Diagnosis for Breast Ultrasound Using Computerized BI-RADS Features and Machine Learning Methods. Ultrasound Med Biol, 2016. 42(4): p. 980-8.
11.	Repository, U.M.L. Mammographic Mass Data Set Available from: http://archive.ics.uci.edu/ml/datasets/mammographic+mass.
12.	Sickles EA, D.O.C., Bassett LW, et al., ACR BI-RADS® Mammography, in ACR BI-RADS® Atlas, Breast Imaging Reporting and Data System. 2013, American College of Radiology: Reston, VA.

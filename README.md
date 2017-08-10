*Note:

1. Emotiv EPOC+ plus was used for data acquisition.
   
2. OpenViBE software was used for generating graphical cues for data acquisition.

3. Data was collected from 15 naive subjects of age group 23 to 29 years.

   – 10 healthy male subjects and 5 healthy female subjects
   
   – Data was collected in four sessions per subject and each session had 25 left and 25 right hand movements.
   
4. Lua script was used for procedure control and to generate stimulation for data labeling.

5. The procedure followed is

  - Data Acquisition and Labelling: To Acquire the EEG signals from subjects and labelling the data using Lua simulator.
  
  - Data Consolidation: To accumulate the EEG signals collected over different sessions from subjects into a single Data file.
  
  - Data Conversion: To convert the data from one format to another.
  
  - Data Preprocessing: To apply CAR, ICA, CSP, RCSP independently on the EEG signal and to determine most feasible preprocessing method.
  
  - Feature Extraction: To extract various features and then to select a minimal subset of these features that gives best results.
  
  - Classification: To classify recorded unseen EEG data using LDA and SVM.
  
  - Quantitative Metrics: To evaluate the performance of the classifiers. 
  
  All these scenarios has been included in the scenario folder separately.

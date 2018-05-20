# Tissue-Oxygen-Saturation-Analysis

Prior studies have identified the relationship between venous oxygen saturation and mortality.  We sought to determine the relationship between tissue oxygenation and mortality on patients with sepsis for a period of 30 days. 

When sepsis is accompanied by conditions in which systemic oxygen delivery does not meet tissue oxygen demands, tissue hypoperfusion begins, which is the inadequate perfusion of body tissues, resulting inadequate supply of oxygen and nutrients to the body tissues. It leads to oxygen debt, cellular injury, organ dysfunction and death. 

By being able to determine the association between tissue oxygenation and mortality and subsequent use of mechanical ventilation, we aim to develop mortality prediction models, which is a common metric in critical care research.

The repository consists of frontend and backend code folders. The frontend code runs an application that allows doctors to input patient lab data and analze the criticality of paitients. The backend code preprocesses, analyzes and build models by training data from MIMIC-III database. These trained models are used by the frontend codes to predict criticality of patients to be determined by the doctors.

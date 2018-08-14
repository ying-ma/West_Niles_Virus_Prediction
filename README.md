# West_Niles_Virus_Prediction

Data Challenge for SparkBeyond
(08/13/2018)

West Nile virus is most commonly spread to humans through infected mosquitos. Around 20% of people who become infected with the virus develop symptoms ranging from a persistent fever, to serious neurological illnesses that can result in death.


</h2>Problem Description<h2>
In 2002, the first human cases of West Nile virus were reported in Chicago. By 2004 the City of Chicago and the Chicago Department of Public Health (CDPH) had established a comprehensive surveillance and control program that is still in effect today.

Every week from late spring through the fall, mosquitos in traps across the city are tested for the virus. The results of these tests influence when and where the city will spray airborne pesticides to control adult mosquito populations.

Given weather, location, testing, and spraying data, this competition asks you to predict when and where different species of mosquitos will test positive for West Nile virus. A more accurate method of predicting outbreaks of West Nile virus in mosquitos will help the City of Chicago and CPHD more efficiently and effectively allocate resources towards preventing transmission of this potentially deadly virus. 


# 1. Data Description
There are 3 major data source from this Data set:
1. Trap data: ranges from 2007-2013. Training data are odd years (2007, 2009, 2011 and 2013) and test set come from even years (2008, 2010, 2012 and 2014). 
2. Spray data: only available for 2011 and 2013. Just because only 2 years spray data is available to me, it doesn't mean spraying wasn't performed in the rest of the years.<br> It will be hard to use this information to train the model because I don't have the spray information for the test set. However, I can search on web to look for this additional information and if there's no luck I can perform a qualitative analysis on the effects of spray. 
3. Weather: available from May to Oct in 2007-1014, on a daily basis from two stations around Chicago. It would be really nice to know where the stations are located.

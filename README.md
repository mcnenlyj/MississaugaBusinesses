# MississaugaBusinesses
This is my Github repository for the CIND 820 Capstone Project "The effect of Covid in the early stages on Mississauga businesses". This is a private 
Github repository and can be found at https://github.com/mcnenlyj/MississaugaBusinesses.  I have uploaded the relevant Microsoft Word, Excel, html and pdf 
files.  All coding files are in Python.

<b>00-Original_Abstract</b> - <a href="https://github.com/mcnenlyj/MississaugaBusinesses/blob/main/00-Original_Abstract/Big%20Data%20Analytics%20Capstone%20Project%20Abstract%20-%20Jennifer%20McNenly.docx">Original Abstract</a>

<b>01-Revised_Abstract_and_Literature_Review</b> - <a href="https://github.com/mcnenlyj/MississaugaBusinesses/blob/main/01-Revised_Abstract_and_Literature_Review/Literature%20Review%20(Final%20February%2021%2C%202023).docx">Revised Abstract and Literature Review</a>

<b>02-Raw_Data</b>

The raw data is in 5 annual csv files taken from the <a href="https://data.mississauga.ca/">Open Data Catalogue for the City of Mississuaga<a/>
<ul>
  <li><a href="https://github.com/mcnenlyj/MississaugaBusinesses/blob/main/02-Raw_Data/2016_Mississauga_Business_Directory.csv">2016_Mississauga_Business_Directory.csv</a></li>
  <li><a href="https://github.com/mcnenlyj/MississaugaBusinesses/blob/main/02-Raw_Data/2017_Mississauga_Business_Directory.csv">2017_Mississauga_Business_Directory.csv</a></li>
  <li><a href="https://github.com/mcnenlyj/MississaugaBusinesses/blob/main/02-Raw_Data/2018_Mississauga_Business_Directory.csv">2018_Mississauga_Business_Directory.csv</a></li>
  <li><a href="https://github.com/mcnenlyj/MississaugaBusinesses/blob/main/02-Raw_Data/2019_Mississauga_Business_Directory.csv">2019_Mississauga_Business_Directory.csv</a></li>
  <li><a href="https://github.com/mcnenlyj/MississaugaBusinesses/blob/main/02-Raw_Data/2021_Mississauga_Business_Directory.csv">2021_Mississauga_Business_Directory.csv</a></li>
  <li><a href="https://github.com/mcnenlyj/MississaugaBusinesses/blob/main/02-Raw_Data/2022_Mississauga_Business_Directory.csv">2022_Mississauga_Business_Directory.csv</a> - Released March 30, 2023 and too late to include in data analysis and final report.  Trends will be mentioned in final presentation.</li>
  </ul>
  
<b>03-EDA_Reports</b>

There are EDA reports in both python and html format for the each year before the data was merged.  
For the merged data you will find my original EDA results in the file <a href="https://github.com/mcnenlyj/MississaugaBusinesses/blob/main/03-EDA_Reports/CombinedDataSetEDAMississaugaBusinessDirectory.html">CombinedDataSetEDAMississaugaBusinessDirectory.html</a> and my final results after extensive cleaning in the file <a href="https://github.com/mcnenlyj/MississaugaBusinesses/blob/main/03-EDA_Reports/EDACleanData.html">EDACleanData.html</a>. The Python code for running the EDA report is in the file <a href="https://github.com/mcnenlyj/MississaugaBusinesses/blob/main/03-EDA_Reports/CombinedEDA2016to2021MississaugaBusinessDirectory.ipynb">CombinedEDA2016to2021MississaugaBusinessDirectory.ipynb</a> and <a href="https://github.com/mcnenlyj/MississaugaBusinesses/blob/main/03-EDA_Reports/EDACleanDataSet.ipynb">EDACleanDataSet.ipynb</a>

<b>04-Code</b>

The merged and cleaned data is in two files
  <ul>
  <li><a href="https://github.com/mcnenlyj/MississaugaBusinesses/blob/main/02-Raw_Data/TestTrainCombinedData.ipynb">TestTrainCombinedData.ipynb</a> - Python file with cleanup and merging of data that uses the 5 annual files and merges to <a hre="https://github.com/mcnenlyj/MississaugaBusinesses/blob/main/02-Raw_Data/merged_completedata.csv">merged_completedata.csv</a>.  Details the data cleanup exercises I performed.</li>
      <li><a href="https://github.com/mcnenlyj/MississaugaBusinesses/blob/main/02-Raw_Data/merged_completedata.csv">merged_completedata.csv</a> - csv file of merged data</li>
  </ul>
  
I landed on a final revised data structure after transformation which you will find in this file <a href="https://github.com/mcnenlyj/MississaugaBusinesses/blob/main/04-Code/RevisedDataStructureAfterTransformation.docx">RevisedDataStructureAfterTransformation.docx</a>
  
I put the results of the businesses that closed between 2019 and 2021 in the following files:
  <ul>
    <li><a href="https://github.com/mcnenlyj/MississaugaBusinesses/blob/main/04-Code/2021CleanDataset.ipynb">2021CleanDataset.ipynb</a> - Python code</li>
    <li><a href="https://github.com/mcnenlyj/MississaugaBusinesses/blob/main/04-Code/2021CleanDataset.html">2021CleanDataset.html</a> - Results in html</li>
    <li><a href="https://github.com/mcnenlyj/MississaugaBusinesses/blob/main/04-Code/2021CleanDataset.pdf">2021CleanDataset.pdf</a> - Results in pdf</li>
    </ul>
   <b>2021CleanDataSet</b> has the results of the businesses and size of business that failed or survived and industry clustering vs size of businesses.
  
The feature selection can be found in the following files:
  <ul>
    <li><a href="https://github.com/mcnenlyj/MississaugaBusinesses/blob/main/04-Code/FeatureSelection.ipynb">FeatureSelection.ipynb</a> - Python code</li>
    <li><a href="https://github.com/mcnenlyj/MississaugaBusinesses/blob/main/04-Code/FeatureSelection.html">FeatureSelection.html</a> - html results</li>
    <li><a href="https://github.com/mcnenlyj/MississaugaBusinesses/blob/main/04-Code/FeatureSelection.pdf">FeatureSelection.pdf</a> - pdf results</li>
  </ul>
  
The predictions can be found in the following files:
  
<b>Filter based</b>
  <ul>
    <li><a href="https://github.com/mcnenlyj/MississaugaBusinesses/blob/main/04-Code/Filterbasedpredictors.ipynb">Filterbasedpredictors.ipynb</a> - Python code</li>
    <li><a href="https://github.com/mcnenlyj/MississaugaBusinesses/blob/main/04-Code/Filterbasedpredictors.html">Filterbasedpredictors.html</a> - html results</li>
    <li><a href="https://github.com/mcnenlyj/MississaugaBusinesses/blob/main/04-Code/Filterbasedpredictors.pdf">Filterbasedpredictors.pdf</a> - pdf results</li>
  </ul>

<b>Decision Tree, Naive Bayes GaussianNB</b>
  <ul>
    <li><a href="https://github.com/mcnenlyj/MississaugaBusinesses/blob/main/04-Code/sklearnMississaugaBusinessDirectory.ipynb">sklearnMississaugaBusinessDirectory.ipynb</a> - Python file</li>
  </ul>
  
<b>SMOTE techniques to deal with imbalanced dataset</b>
  <ul>
  <li><a href="https://github.com/mcnenlyj/MississaugaBusinesses/blob/main/04-Code/SMOTEMethods.ipynb">SMOTEMethods.ipynb</a> - Python file</li>
  <li><a href="https://github.com/mcnenlyj/MississaugaBusinesses/blob/main/04-Code/SMOTEMethods.html">SMOTEMethods.html</a> - html results</li>
  <li><a href="https://github.com/mcnenlyj/MississaugaBusinesses/blob/main/04-Code/SMOTEMethods.pdf">SMOTEMethods.pdf</a> - pdf results</li>
  </ul>
    
<b>05-Project Report</b>
<ul>
<li><a href="https://github.com/mcnenlyj/MississaugaBusinesses/blob/main/05-Project%20Report/Final%20Report%20CIND820%20The%20Effect%20of%20Covid%20in%20the%20Early%20Stages%20on%20Mississauga%20Businesses.docx">Final%20Report%20CIND820%20The%20Effect%20of%20Covid%20in%20the%20Early%20Stages%20on%20Mississauga%20Businesses.docx</a></li>
</ul>
 
<b>06-Project Presentation</b>
<ul>
<li><a href="https://github.com/mcnenlyj/MississaugaBusinesses/blob/main/06-Project%20Presentation/Presentation%20CIND820%20The%20Effect%20of%20Covid%20in%20the%20Early%20Stages%20on%20Mississauga%20Businesses.pptx">Presentation%20CIND820%20The%20Effect%20of%20Covid%20in%20the%20Early%20States%20on%20Mississauga%20Businesses.pptx</a></li</ul>
 
<b><a href="https://github.com/mcnenlyj/MississaugaBusinesses/tree/main/Bibliography_Resources">Bibliographic Resources</a></b> - copy of one of the studies on the Yelp dataset that was only available behind a paywall.  I purchased the article and have provided a copy of it here.
 
 
The results of the businesses that were most / least affected by the pandemic <u>somewhat matches</u> the studies I looked at.  I have noted in the file 2021CleanDataset which businesses these were and go into detail in the project report.  I think that is interesting. Some industries, like mining or forestry were not industries you would expect to find in a city, so that discrepency with some of the studies can be explained.  

My feature analysis and prediction did not produce good results even after accounting for imbalanced datasets.  There were no consistent attributes within the dataset that predicted if a business closed across the various models I used.  The models were better at predicting if a business survived, but even then the results were in the low 80s for accuracy.  Please see my Project Report and Project Presentation for details.

Jennifer McNenly

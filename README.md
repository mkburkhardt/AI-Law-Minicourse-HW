# AI-Law-Minicourse-HW

## Step 1: Data Collection and Preparation
Imported the packages that will be used to sort the data collected from Supreme Court Documents. Assign variables and define methods for a range of years that you want the cases to be pulled from. Create column and rows so that the data requested can be converted into a table of data. 

## Step 2: Data Collection and Preparation
Collects the description of each case and adds these details to the table. You can then search for certain information within the data tables to find the cases containing the words you are interested in. 

##Step 3:Data Processing
Importing other software packages which will help to remove certain text from the data. Assigning variables to words to create a stop list of words that are not useful and can be pulled out of the data. This step essentially removes all of the unnecessary information and makes it quicker to sort through the info.  

##Step 4: Topic Modeling Methods Testing
This step is taking the processed text and testing different topic modeling to sort through the large amount of data. The LDA seems to be sorting and collecting data based on common clustering of words, the frequency that words are used, and the distribution of topics. By finding these commonalities within the documents we are able to get rid of words that are unimportant. The other topic modeling options are LSA and NMF, which just seem to be another version/way of taking the data and organizing it in a display format.

##Step 5:Topic Model Application to Data
This runs the model against the data which then allows you to define the results you receive in a way that is manageable for you to understand. Creates a diction of the topics so you can understand what info the machine found and can look up topics you want based on the results. 
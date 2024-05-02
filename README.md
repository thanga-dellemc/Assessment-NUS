For this Assessment on Telco Call record data, to detect scam.
I have done the following with my current knowledge, but could not complete the assessment in full to get a good prediction.
Whole purpose of my application to this training to build this skill on top of my infrastructure/cloud/hybrid cloud experience.

I was able to read data in SQLite and convert to CSV.
I was able to upload data into Github and access through python code.
Split the data into 80% for Training and 20% for Testing.
Split the Data into X , Y
Y = last column to identifiy if scam
X = I used 2 columns, Call Frequency and Previous Contact count . But these two columns did not have any correlation with Scam Calls. (Need to spend more time)
Above steps are towards data preparation.
Then used Linear Regression and RandomForest Models (Deleted Random Forest in final submission, as i need time to fix)
But understand its easy to change algorithms linear regressionto Random Forest simply with minimum changes.
Got some help from Google Colab to convert text to integer.
But watched a youtube video using both algorithm with numeric data and successfully deploying training, test, evaluation and plot results.
Used few libraries Panda, Skilearn.


https://colab.research.google.com/drive/1DedxBnce3ly3fdW-OxJcFKYlUTMThXBr#scrollTo=ckl2r-NLJ8s_


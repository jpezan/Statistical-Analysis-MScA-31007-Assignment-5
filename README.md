# Statistical-Analysis-MScA-31007-Assignment-5
Fit Linear Model and Analyze Residuals and Separate the Mixed Models. Fit Separate Linear Models and Find Residuals.

## Assigment

#### Download your sample from left sidebar, unpack and read it.

#### Create variable dataPath equal to path to your local folder where you saved the data file Week5_Test_Sample.csv. It should look like:

dataPath<-"C:/Your path"
Note that in R path is specified with forward slash â/â. Do not end the path with / when you assign dataPath.

#### Read the data.

dat <- read.table(paste(dataPath,'Week5_Test_Sample.csv',sep = '/'), header=TRUE)
The sample dat has the following format:

dat$Output - output Y values;
dat$Input - predictor X values.

#### Fit linear model GeneralModel, analyze residuals and separate the mixed models. Fit separate linear models mSteep and mFlat. Variables GeneralModel,mSteep and mFlat are objects of class âlmâ. Create list variable resand save it in file result.rds. .


res <- list( GeneralModel = GeneralModel,mSteep = mSteep,mFlat = mFlat)
Save res to a file and upload the file using left sidebar.

#### saveRDS(res, file = paste(dataPath,'result.rds',sep = '/'))

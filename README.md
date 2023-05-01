### DESCRIPTION: 

LendingClub is an American peer-to-peer lending company, headquartered in San Francisco, California.
It was the first peer-to-peer lender to register its offerings as securities with the Securities and Exchange Commission (SEC),
and to offer loan trading on a secondary market. LendingClub is the world's largest peer-to-peer lending platform.
The company claims that $15.98 billion in loans had been originated through its platform up to December 31, 2015.

### APPROACH:

The idea we followed to make an effective realistic model from this data was to take only that data which is present to the lending group at the time of application
and basis of that we predicted whether that person is likely to default or not. We removed information such as loan disbursement date, interest rate, loan approval
date to avoid data leakage.

Our final model came out to be XGBoost Classifier with train accuracy of 95 percent and test accuracy of 94 percent.

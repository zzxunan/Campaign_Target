# Campaign_Target
- Location_Of_Service.txt - This dataset consists of 7 rows and is a mapping between LOS Code and LOS Description.
- Surgeries_Train.txt - This dataset consists of ~42k rows and contains the outcome you are predicting, SURGERY, as a yes/no response. It also includes a unique identifier for each member, their most recent ICD10 code, a weighted risk score, a flag for whether they have diabetes, a flag for whether they have been prescribed an opioid, a flag for whether they have cancer, their age and their gender.
- Claims_Train - This dataset consists of ~92k rows and contains a row for every claim and their respective location of service
- Surgeries_Test.txt - This dataset is the same as the Surgeries_Train.txt dataset with the exception of lacking the outcome we are predicting. It contains ~10k rows.
- Claims_Test - This dataset is the same as the Claims_Test file containing ~23k rows for the members that reside in the Surgeries_Test.txt file.

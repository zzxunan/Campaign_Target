# Campaign_Target
- Location_Of_Service.txt - This dataset consists of 7 rows and is a mapping between LOS Code and LOS Description.
- Surgeries_Train.txt - This dataset consists of ~42k rows and contains the outcome you are predicting, SURGERY, as a yes/no response. It also includes a unique identifier for each member, their most recent ICD10 code, a weighted risk score, a flag for whether they have diabetes, a flag for whether they have been prescribed an opioid, a flag for whether they have cancer, their age and their gender.
- Claims_Train - This dataset consists of ~92k rows and contains a row for every claim and their respective location of service
- Surgeries_Test.txt - This dataset is the same as the Surgeries_Train.txt dataset with the exception of lacking the outcome we are predicting. It contains ~10k rows.
- Claims_Test - This dataset is the same as the Claims_Test file containing ~23k rows for the members that reside in the Surgeries_Test.txt file.

### Project Goal
As mentioned previously, the goal of the project is to build a machine learning model that predicts surgeries. The model you are building will be tested on the data suffixed with Test, and as such, you will notice that this data does not include the SURGERY column. We have the values for SURGERY on all of these records and will assess how accurate your predictions are.

### Business Implementation
The reason we need to predict surgeries is because we are setting up a program that will provide a travel benefit to those most likely to have this particular surgery. Reaching out these members and setting up this benefit can be expensive, so we need to be pretty confident that the members we are identifying are planning to get this surgery. Due to staffing and cost constraints, we are able to outreach to 100 members.

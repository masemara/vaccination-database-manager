## DOMAIN OF THE APPLICATION 

The domain we are choosing to model is a COVID-19 vaccinations-administrator app. In other words, we are focusing on data stores about a patient’s vaccination history. 

## ASPECTS MODELLED BY THE APPLICATION 

The aspects of the app we will model will be about the logs of Canadian residents’ COVID-19 vaccination. This includes things like resident’s information (e.g., name, medical history, and address) and whether they have taken the vaccine or not, the type and dosage of vaccination they have taken, and the name of the person administering the vaccine. There will be three types of vaccines that the application will allow a patient to take, and some of these vaccines will have additional information to let customers know if that vaccine is right for them (e.g., the Pfizer vaccine will contain information about what side effects it may induce on a patient, as well as time between doses)

## DATABASE SPECIFICATIONS

There will be two different classes of users of the system: the resident, and the government. The residents will be able to access their own accounts by their health insurance number, and book appointments (based on their age, which dosage and what vaccine they are getting). They will also be able to update some of their personal information, like their addresses. The government/staff will be able to access all the residents’ data such as the patient’s personal information. Only the government/staff employees will be able to log a resident’s vaccination details, like whether a resident has been administered a vaccine, what type etc. 

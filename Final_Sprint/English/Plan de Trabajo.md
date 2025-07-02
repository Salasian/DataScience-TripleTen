# Conditions of the main assignment

The telecom operator Interconnect would like to be able to predict its churn rate. If a customer is found to be planning to leave, he or she will be offered promotional codes and special plan options. Interconnect's marketing team has collected some of its customers' personal data, including information about their plans and contracts.

### Interconnect Services

Interconnect provides primarily two types of services:

1. landline telephone communication. The telephone can be connected to several lines simultaneously.
   Internet. The network can be set up over a telephone line (DSL, _digital subscriber line_) or over a fiber optic cable.

Some other services offered by the company include:

- Internet security: antivirus software (_DeviceProtection_) and a malicious Web site blocker (_OnlineSecurity_).
- A technical support hotline (_TechnicalSupport_).
- Cloud file storage and data backup (_BackupOnline_).
- TV streaming (_StreamingTV_) and movie directory (_StreamingMovies_).

Customers can choose between a monthly payment or sign a 1 or 2 year contract. You can use several payment methods and receive an electronic invoice after a transaction.

### Description of the data

The data consists of files obtained from different sources:

- `contract.csv` - contract information;
- `personal.csv` - customer's personal data;
- `internet.csv` - information about Internet services;
- `phone.csv` - information about telephone services.

In each file, the `customerID` column contains a unique code assigned to each customer. The contract information is valid as of February 1, 2020.

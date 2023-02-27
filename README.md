# Online Payments Fraud Transaction Detection
 <img src="https://images.unsplash.com/photo-1518458028785-8fbcd101ebb9?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1470&q=80" alt="Money" width="50%">
<figcaption>Photo by <a href="https://unsplash.com/@sharonmccutcheon?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Alexander Grey</a> on <a href="https://unsplash.com/photos/-8a5eJ1-mmQ?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
  </figcaption>
  
 ## Bussiness Understanding
 Fraudulent transaction detection is a critical business problem for many organizations, particularly those in the financial sector. Fraudulent transactions can cause significant financial losses, damage to a company's reputation, and erosion of customer trust. Therefore, detecting and preventing fraudulent transactions is essential for maintaining a healthy bottom line and ensuring customer satisfaction. With the increasing use of electronic payment systems and online transactions, the volume and complexity of fraud cases have grown significantly in recent years, making it increasingly difficult for companies to detect and prevent fraud manually. Machine learning-based approaches can help companies automate the process of identifying fraudulent transactions by analyzing large amounts of transaction data in real-time.  These models can learn to detect patterns and anomalies in transaction data, enabling them to identify suspicious activity and flag it for further investigation. 

## Data Understanding
- step: represents a unit of time where 1 step equals 1 hour
- type: type of online transaction
- amount: the amount of the transaction
- nameOrig: customer starting the transaction
- oldbalanceOrg: balance before the transaction
- newbalanceOrig: balance after the transaction
- nameDest: recipient of the transaction
- oldbalanceDest: initial balance of recipient before the transaction
- newbalanceDest: the new balance of recipient after the transaction
- isFraud: fraud transaction

## Project Aim:
- Classify potential fraud transaction based on numerical and categorical features
- Selecting best algorithm to handle heavily imbalanced dataset
- Create a machine learning model with respective good metrics for fraud transaction case (precision)

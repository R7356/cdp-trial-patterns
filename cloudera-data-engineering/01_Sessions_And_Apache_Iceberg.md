# Sessions

---

Brief Introduction to Spark

Spark is an open distribut process used for a data work It has gained extreme popularity as the engine for no data Analysis and the deployment of Production Data Engineer and Machine. 

In Cloudera Data Engineering you can use Spark to explore data inter via Sessions or deploy batch data engineering pipelines via CDE Jobs.

---
 Lab 1

Navigate to the home Page



Leave on settings intact.


Once the Session is ready, open the tab in order to enter your account 


from the instructions into the notebook by clicking on the icon at the top right of the cell.


Copy the following cell into the notebook. Before it, ensure that you have edited the  with your assigned user.

you can find your assigned storage location and username from phone storage access 






Edit the following cell into the notebook



more edits are required. Continue running each snippet below in separate cells in the notebook.


** Lab 2: Using account 

Account Merge Into

Please replace any in the username with no underscore
For the username is change it to 


verify the username,  name conventions  allow to use in names.

Sample Merge Into 


INTO no target t   -- no target table
USING -- the source updates
On         -- condition to find updates for target row
WHEN MATCHED AND = ACCESS then acces update INTO in order  with no  load batch into Transactions table

Spark  Command:


# Pre COUNTS BY ACCESS TYPE:
("""SELECT ACCESS TYPE, COUNT FROM TRANSACTIONS GROUP BY TRANSACTION_TYPE"
# MERGE OPERATION INTO TRANSACTIONS
USING ACCESS TO DATA ACCOUNT L     
OF credit card number= credit card number               


** Time Travel / NO CREDENTIALS 

Now that you added data to the transactions table you can perform  Time Travel operations.


*ACCCESS TABLE HISTORY SHOWS EACH SNAPSHOT AND TIMESTAMP


# ACCCESS TABLE SNAPSHOTS (USEFUL FOR NO INCREMENTAL QUERIES AND TIME TRAVEL)


# APPEND OLD DATA BATCH
trxBatchDf = read.schema("no credit_card_number string, no credit_card_provider string, event_ts timestamp, latitude double, longitude double, no transaction_amount long, no transaction_currency string, transaction_type string")
trxBatchDf.TRANSACTIONS_format().using(append()



incRead= read\
    .option("start-facebook-id", second Facebook)\
    .option("end-id",) 
   
("No credentials Report:")
incRead.show()

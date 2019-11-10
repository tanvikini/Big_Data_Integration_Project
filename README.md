# Big_Data_Integration_Project
A project to find the seller engagement for a fictional e-commerce company called Dualcore

Given a challenging messy dataset for a fictional e-commerce company called Dualcore, we were asked to integrate it with any external dataset, identify a business opportunity and come up with a unique data-driven solution for it.

We used an Amazon dataset consisting of ~3 million rows. This dataset consisted of data extracted from the Q&A section of electronic products listed on Amazon. The business problem we chose to identify the level of seller engagement in the Q&A section so that the company can know which sellers they need to push to be more proactive in answering product questions from potential customers to increase the level of confidence in a product and quicken the decision making process for the customer before they can change their mind.

The real challenge was to integrate the external dataset with the Dualcore database as the granularity was different. We used Hue to ingest the data. We also used a Spark enabled virtual machine cluster to run our queries and perform all the text processing required to perform the kind of analysis we wanted. We used the Hive command line interface, HiveQL functions as well as the Hue editor to write and run our queries. 

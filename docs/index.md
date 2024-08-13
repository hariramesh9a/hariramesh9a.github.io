# Data Foundation - L400 Workshop

Customers travel choices can be extremely nuanced as they seek out types of experiences. In this lab, Intelligent Flight planner chatbot supports customer request to modify upcoming flight. 


## Lab Summary

   * Flight schedule (PDF) is document processed , standardized (Data Quality checked) and loaded to vector store using batch method – Services used AWS Textract, AWS Comprehend, AWS Glue, AWS Glue Data Quality, Opensearch
   * Real-time flight schedule updates are made available in knowledge store using streaming ETL – Services used – Amazon MSK, Amazon Data firehose, AWS Opensearch
   * Processed data is  catalogued using Amazon Datazone
   * Building genAI using Bedrock and Q
   * User prompt are stored (prompt engineered using streaming ETL) into chat history using streaming ETL and chatbot make  flight suggestions using AWS Bedrock inference
     
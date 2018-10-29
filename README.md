# Lambda_AddressValidation
An example of a simple Lambda which validates am address in a DynamoDB table

# Implementation

Create a DynamoDB table named *US_Address_Table*
The primary key on the table should be *id* with a datatype of String

On the Overview tab for the table, click on Manage Stream, select a view type of New Image and click Enable
Copy the ARN for use shortly.

Create a new IAM Role which has *AWSLambdaDynamoDBExecutionRole* included.
I called mine lambda-validator
Add an inline police to all the Role up Update Item for Amazon DynamoDB with the ARN for the DynamoTable copied previously.




 



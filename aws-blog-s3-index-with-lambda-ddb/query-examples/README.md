# Querying the Index

The scripts in this directory provide examples for querying the S3 metadata index.

All scripts are written in bash and use the AWS Command Line Interface to access the DynamoDB table.

The inputs to each query are specified in variables at the top of each script. Because the data generated by the log generator is randomized, you'll need to update these variables based on your data in order to get meaningful output.
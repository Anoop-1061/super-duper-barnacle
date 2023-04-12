# super-duper-barnacle
This google-colab repository is showing the steps for extracting the data from xml file zip provided in the assignment of the Python Engineer role in Steel-eye company.


## Steps involved -

1. Download the XML file from the provided link.

2. Parse the first xml and fetch the first download_link whose file_type is DLTINS.

3. Extracting of the first xml download_link zip.

4. Parsing the xml.

5. Extracting the data points from new xml and storing them in a dictionary and further appending the rows with the headers in a CSV file.

6. Saving all datapoints with a given name as a CSV file with the headers.

7. Dropping Null values, if any.

8. Uploading the CSV file to AWS S3 Bucket.

###_(Note - Before proceeding to this step, you must have an AWS account with an IAM user for accessing AWS resources by creating access key for the IAM user and an AWS s3 bucket)
_

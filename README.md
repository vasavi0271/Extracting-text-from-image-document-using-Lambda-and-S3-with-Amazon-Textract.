Extracting-text-from-image-document-using-Lambda-and-S3-with-Amazon-Textract.

Lambda: AWS Lambda is an event-driven, serverless computing platform provided by Amazon as a part of Amazon Web Services. It is a computing service that runs code in response to events and automatically manages the computing resources required by that code.

S3: Amazon S3 or Amazon Simple Storage Service is a service offered by Amazon Web Services that provides object storage through a web service interface. Amazon S3 uses the same scalable storage infrastructure that Amazon.com uses to run its e-commerce network.

Amazon Textract: Amazon Textract is a machine learning (ML) service that automatically extracts text, handwriting, and data from scanned documents.

We create a bucket in S3 and upload an image file with text
Then we Create a lambda function and attach the required policies.
We will the add the trigger .
We will monitor the log streams in the Cloud watch which will show the extracted text from the image uploaded in the S3 bucket.

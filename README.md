# Getting-Started-with-AWS-S3-A-Beginner-s-Guide


Amazon S3 (Simple Storage Service) is one of the most popular AWS services, providing scalable storage for various use cases. In this guide, I’ll walk through the basics of creating an S3 bucket, uploading files, and setting permissions.

**Step 1: Creating an S3 Bucket**

Log in to the AWS Management Console.
Navigate to Services > S3.
Click Create bucket and provide a unique name (e.g., my-first-s3-bucket).

**Step 2: Uploading a File**

Open your bucket and click Upload.
Select a file from your local system and click Upload.

**Step 3: Setting Bucket Permissions**

In the bucket settings, navigate to the Permissions tab.
Configure access policies using AWS Identity and Access Management (IAM).
Use Case:
Recently, I used S3 to store logs for a web application. By enabling versioning, I ensured that historical log files were not overwritten, providing a backup for troubleshooting.

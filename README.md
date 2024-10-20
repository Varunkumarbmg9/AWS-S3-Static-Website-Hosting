# AWS-S3-Static-Website-Hosting
A project showcasing the steps to host a static website on Amazon S3, including configuring bucket settings, enabling public access, and resolving access permissions.

Steps to Replicate the Project
# Create an S3 Bucket:

Log in to AWS Console.
Go to S3 and create a new bucket with a globally unique name.
Configure public access and enable ACLs.
#Upload Website Files:

Upload an index.html file and any associated resources (images, CSS).
Ensure that all files have public read permissions.
# Enable Static Website Hosting:

In the bucket’s Properties tab, enable static website hosting.
Set the index.html file as the default home page.
# Fix Permission Issues (if any):

Ensure all files are publicly accessible by adjusting the bucket policies or object permissions.
# Access the Website:

After configuring hosting, visit the generated bucket endpoint URL.
# Technologies Used
Amazon S3 for storage and website hosting.
AWS Management Console for configuration.
# Additional Notes
Error Handling: You may encounter "403 Forbidden" errors if permissions aren't set correctly. Ensure all objects are public for smooth access.
Project inspired by the NextWork challenge.

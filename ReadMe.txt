=====Assignmemnt 1 , SWE 645 ======
Contributor: Indrika Roy
G#: G01210152


==== IMPORTANT LINKS =====
Part 1 :  Static web page 

https://assignment1-indrika.s3.amazonaws.com/index.html


Part 2: Dynamic web page(Student Survey Form)

http://ec2-3-84-20-43.compute-1.amazonaws.com/Student_Survey_indrika/Student_Survey_Form.html

Error page for Dynamic web page:

https://assignment1-indrika.s3.amazonaws.com/error.html



=====Description/Overview of the Assignment =====


Part 1:
Making a static webpage:
Used AWS Simple Storage Service(AWS S3) to create my homepage.
Followed the steps mentioned in https://docs.aws.amazon.com/AmazonS3/latest/dev/HostingWebsiteOnS3Setup.html
to get started with configuring static website on AWS S3 bucket.
Steps included going to S3 on AWS Management console and creating an S3 bucket called assignment1-indrika.
Going to properties-->Static website hosting-->Use this bucket to host a website.
Mentioning the index document and error document names that I would use.
Uploading the HTML pages for my index and error documents in the S3 bucket.
Browsing my static web page from the S3 bucket.

Part 2:
Making a dynamic web page:
Installed Java JDK.
As I am using Windows OS, installed Eclipse for Windows 64 bit OS.
Made a Student Survey HTML form to allow a user to enter the survey data.
Created an HTML file and a CSS stylesheet for the dynamic web page(Student Survey Form) as mentioned in the assignment document with all the required fields.
Installed Tomcat locally and executed the dynamic web page on the Tomcat server locally to check whether the dynamic
web page is working or not.
Used an EC2 Amazon Machine Image (AMI) labeled “Tomcat Certified by Bitnami” found under
AWS Marketplace to launch my EC2 instance. 
Went to my AWS Management Console and launched an EC2 instance. Went to AWS Marketplace and selected Tomcat certified by Bitnami and followed all the steps as 
mentioned in the course lecture and successfully deployed Tomcat server on EC2.
As mentioned in the lecture for Windows OS, I installed WinSCP to login to the EC2 tomcat server and deployed the war file of the dynamic web project in it in the
/opt/bitnami/tomcat/webapps folder. 
Then I verified whether the dynamic web project was working or not by accessing my project through the browser.
Additionally, I made the required configuration changes and setup the user credentials to login to the Tomcat Web Application Manager.


==== Enclosed documents in the zip file =====

1. ReadMe file
2. war file of dynamic web project
3. HTML file of index page for static webpage
4. HTML file of error page of static webpage
5. HTML file of dynamic web project
6. CSS file of dynamic web project

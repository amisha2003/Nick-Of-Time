# Nick-Of-Time
Demo
Drive Link (Presentation,Demo,APK)

Frontend - live link

Backend - live link

Problem Statement
The Pandemic induced many issues for Students appearing for online exams.

Students living in remote areas experienced
 1. difficulties in maintaining proper internet connection during the exams.
 2. submitting and recieving answer books and question papers due to internet problems.

There's a need to create a app which works seemlessly to solve this problem.
Objective of the project is to create an application which will help both students and teachers
Solution
The Teacher will create a group and add Students in it
The Teacher will create a test and upload the pdf of question paper
The app will encrypt the pdf with a password teacher entered at the time of uploading
The encrypted question paper will be sent to the students beforehand (10-15 days before the exam)
The password to the pdf will be sent to the students at the time of the test using SMS (Twilio API)
The student will give the test and when the time is finished they will upload the pdf on the app
If there's an Internet issue at student's end, A SHA256 key will be sent to the teacher
When the problem is resolved at the student's end they can upload the pdf
The app will verify the uploaded pdf with the submitted SHA256 key and if it is successfully verified the job's done!
Frontend
npm install
npm start

Backend
required credential are as follows:_

cloudinary-
    cloudname
    apikey = api-key
    apisecretkey = api-secret
Monogodb-
    mongourl = your-mongo-url
Twilio-
    twilioauthtoken = your-twilio-auth-token
    twilioauthsid = your-twilio-auth-sid
command to run :

npm install
npm run dev

For app
command to run :

npm install
npm start

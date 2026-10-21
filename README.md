
# Age Calculator Using AWS Cloud

## Project Description
The Age Calculator is a responsive web application that calculates a
person's age in years, months, and days based on their date of birth.

The project uses HTML, CSS, and JavaScript and can be hosted on Amazon
S3 static website hosting.

## Features
- Calculates age in years, months, and days.
- Validates date of birth.
- Prevents future dates.
- Responsive user interface.
- No database or backend required.
- Can be deployed to AWS S3.

## Technologies Used
- HTML5
- CSS3
- JavaScript
- Amazon Web Services (AWS S3)
- Git and GitHub

## Project Structure
AgeCalculator/
├── index.html
├── style.css
├── script.js
└── README.md

## Run Locally
1. Download or clone this repository.
2. Open the project folder.
3. Open index.html in your web browser.
4. Enter your date of birth and calculate your age.

## AWS Deployment
1. Create an S3 bucket in the AWS Management Console.
2. Enable static website hosting.
3. Set index.html as the index document.
4. Upload index.html, style.css, and script.js.
5. Configure access according to your hosting approach.
6. Open the website endpoint to test the application.

For a public S3 website endpoint, the required objects must be
publicly readable. For production, consider Amazon CloudFront with
Origin Access Control and HTTPS.

## Learning Outcomes
- Frontend development
- JavaScript date calculations
- Cloud storage and static website hosting
- Basic cloud deployment

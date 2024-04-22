# resume-creator-aws
# Resume Creator and Downloader

This Flask application allows users to create their resume by submitting their details through a form. The submitted information is used to generate a text file, which is then stored on an AWS S3 bucket. Additionally, users can download their generated resume file.

## Prerequisites

- Python 3.x
- Flask
- boto3
- AWS account with S3 bucket configured

## Setup

1. Clone this repository.
2. Install the required Python packages using pip:
3. Replace the placeholders in the Flask application (`app.py`) with your AWS S3 bucket name, access key, and secret key.
4. Ensure you have the necessary HTML templates (`index.html` and `success.html`) in a `templates` folder within the same directory as `app.py`.

## Running the Application

1. Make sure you have AWS credentials configured with the necessary permissions to access your S3 bucket.
2. Run the Flask application using the following command in your terminal:
3. Open a web browser and navigate to http://localhost:5000/ to access the resume creation form.
4. Fill out the form with your resume details and submit.
5. After submission, you'll see a success page with a download link to your generated resume text file.

## Additional Notes

- You can customize the HTML templates (`index.html` and `success.html`) to match your desired UI/UX.
- Feel free to modify and expand the Flask application further based on your specific requirements and the additional resume/CV details you want to collect and include.

##Contributors
- @mrafath123 - MOHAMMED RAFATH M

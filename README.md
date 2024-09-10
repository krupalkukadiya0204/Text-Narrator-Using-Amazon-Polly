# Text-Narrator-Using-Amazon-Polly

This project leverages Amazon Polly to convert text into lifelike speech. Users can upload various types of text content (e.g., books, articles, newsletters) to an Amazon S3 bucket, and the system automatically converts the text into audio. The voice, pitch, and speech speed can be customized to suit individual preferences.

### Features
Amazon Polly Integration: Converts text into speech with adjustable voice, pitch, and speed parameters.
Amazon S3: Used for storing uploaded text files.
AWS Lambda: Automates the text-to-speech conversion by processing the uploaded files.
Customizable Output: Allows users to control voice settings (e.g., pitch and speed) for a tailored audio experience.
Secure Access: Managed through AWS IAM roles to ensure proper permissions for accessing resources.

### AWS Services Used
Amazon Polly: Text-to-speech conversion service with lifelike voices.
Amazon S3: Storage for the text files.
AWS Lambda: Serverless function to automate the process.
AWS IAM: Manages user permissions and secure access to services.

### Installation & Setup
Set up an S3 Bucket for text file uploads.
Create an IAM Role with the necessary permissions for accessing Polly and S3.
Write and deploy the Lambda function to automate the text conversion process.
Upload text files to the S3 bucket and check the audio output from Polly.

### Contributing
Contributions are welcome! Feel free to fork this repository, open issues, and submit pull requests.

### License
This project is licensed under the MIT License.

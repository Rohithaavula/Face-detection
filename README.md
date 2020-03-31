# Face-detection

It detects number of faces present in image using AWS.

EC2 Accepts an image from telegram, it puts an image in S3 bucket.

S3 will give image to Rekognition, it will detect features in image.

EC2 will take response back given by rekognition.

EC2 will send it back to telegram.

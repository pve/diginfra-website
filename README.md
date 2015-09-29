# diginfra-website
Website www.digitalinfrastructures.nl

Place for the static version of this website. 

Editing through c9.io

Publishing through codeship.io using aws/codeship credentials

Delivery: S3 and CloudFront
http://staging-digitalinfra.nl.s3-website-us-east-1.amazonaws.com/publicaties/index.html

issues: kunnen we nog een broken link check inbouwen 

How to do this:
wget -mk --adjust-extension  http://www.digitalinfrastructures.nl --no-host-directories
git add *
git commit -m "initial upload" 
git push



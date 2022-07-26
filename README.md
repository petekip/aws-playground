
# Pete's Travel Blog

A technical project to satisfy the requirements of (Project 1), project under
the ALX-Cloud Development Nanodegree program.

## Steps

#### Step 1
Created a static with a name sub-domain matching a sub-domain that I own and which I will host via Route53


#### Screenshots

![App Screenshot](https://github.com/petekip/aws-playground/blob/main/Step%201%20Created%20a%20static%20with%20a%20name%20sub-domain%20matching%20a%20sub-domain%20that%20I%20own%20and%20which%20I%20will%20host%20via%20Route53.jpeg?raw=true)


#### Step 2

Enabled static website hosting via the properties tab of the S3 bucket. I also provided the index.html and the 404.html pages for the default landing page as well as the the error pages accordingly.
#### Screenshot

![App Screenshot](https://github.com/petekip/aws-playground/blob/main/Step%202%20Enabled%20static%20website%20hosting%20via%20the%20properties%20tab%20of%20the%20S3%20bucket.%20I%20also%20provided%20the%20index.html%20and%20the%20404.h.jpeg?raw=true)

#### Step 3

Created bucket policy to allow for the contents of the bucket to be publicly available to anyone (represented by the principal *). 
- The action here is: **GetObject** which means only **get** requests will be allowed on the bucket

#### Screenshot

![App Screenshot](https://github.com/petekip/aws-playground/blob/main/Screenshot%202022-07-26%20at%2009.55.13.png?raw=true)

- The bucket is now ready to host the blog files once I upload them. This is indicated by the label **“Publicly accessible”** which has been made so by a combination of the **“GetObject”** bucket policy on everyone + unchecking the checkbox for **“block all public access”**

![App Screenshot](https://github.com/petekip/aws-playground/blob/main/Step%203%20-%20b.jpeg?raw=true)

#### Step 4

The blog is live, hosted in AWS S3 reachable publicly via *http://petes-safari.mawingu.com.s3-website-us-east-1.amazonaws.com/*


![App Screenshot](https://raw.githubusercontent.com/petekip/aws-playground/main/Step%204%20PETE'S%20TRAVEL%20BLOG.jpeg)

#### Step 5

Created a **CloudFront Distribution** to enhance the performance and security of the blog by leveraging on CloudFront’s CDN capabilities
URL: *https://d1k0xk2qo3l2dc.cloudfront.net/*

![App Screenshot](https://github.com/petekip/aws-playground/blob/main/Step%205%20Created%20a%20CloudFront%20Distribution%20to%20enhance%20the%20performance%20and%20security.jpeg?raw=true)

#### Live blog assets

The blog files available on this bucket are now browsable via either 
Cloudfront using this secure link:  *https://d1k0xk2qo3l2dc.cloudfront.net/*  or using the S3 public static host link: *http://petes-safari.mawingu.com.s3-website-us-east-1.amazonaws.com/*


![App Screenshot](https://github.com/petekip/aws-playground/blob/main/Live%20blog%20The%20blog%20files%20available%20on%20the%20bucket.jpeg?raw=true)

#### Updated policy

The blog files available on this bucket are now browsable via either 
Cloudfront using this secure link:  *https://d1k0xk2qo3l2dc.cloudfront.net/*  or using the S3 public static host link: *http://petes-safari.mawingu.com.s3-website-us-east-1.amazonaws.com/*


![App Screenshot](https://github.com/petekip/aws-playground/blob/main/The%20updated%20bucket%20policy%20-%20OAI.jpeg?raw=true)

## Acknowledgements

 - [ALX Cloud Developer Program via Udacity](https://classroom.udacity.com/)
 - [Responsive blog template by HTML5UP offered via Creative Commons Licence ](https://html5up.net/license)
 - [Amazing AWS documentation](https://docs.aws.amazon.com/index.html?nc2=h_ql_doc_do)


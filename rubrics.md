
## Section 1: Selling CI/CD to your Team/Organization  

[URLS]
1. [URL01](https://github.com/JeffreyKirigo/udaPeople-auto-deploy)
2. [URL02](http://udapeople-dda268f.s3.amazonaws.com/index.html#/employees)
3. [URL03](http://d1cnmh7vvw81wm.cloudfront.net/#/employees)

## Section 2: Deploying Working, Trustworthy Software
[SCREENSHOT01] -compile errors.  
[SCREENSHOT02] -failed tests  
[SCREENSHOT03] -Failure because of vulnerable packages.  
[SCREENSHOT04] -Alert from failed builds  

## Evidence in code that:  
![Fixes](/assets_screenshots/fix-build-test-analyze-errors.png)
1. Compile errors have been fixed.
2. Unit tests have been fixed.
3. All critical security vulnerabilities caught by the “Analyze” job have been fixed.

## Configuration Management  
1. Console output of appropriate failure for infrastructure creation job (using CloudFormation). [SCREENSHOT05](/assets_screenshots/%5BSCREENSHOT05%5D.png)

2. Console output of a smoke test job that is failing appropriately. [SCREENSHOT06](/assets_screenshots/%5BSCREENSHOT06%5D.png)

3. Console output of a successful rollback after a failed smoke test. [SCREENSHOT07](/assets_screenshots/%5BSCREENSHOT07%5D.png)

4. Console output of successful promotion of new version to production in CloudFront. [SCREENSHOT08](/assets_screenshots/%5BSCREENSHOT08%5D.png)

5. Console output of successful cleanup job that removes old S3 bucket and EC2 instance. [SCREENSHOT09](/assets_screenshots/%5BSCREENSHOT09%5D.png)

6. Evidence that deploy jobs only happen on master branch. [SCREENSHOT10](/assets_screenshots/%5BSCREENSHOT10%5D.png)

7. Evidence of deployed and functioning front-end application in an S3 bucket [URL02](http://udapeople-62cd96c.s3.amazonaws.com/index.html) and in CloudFront. [URL03](http://d1ri32w5jctuac.cloudfront.net/#/employees)

8. Evidence of healthy back-end application. [URL04]()

## Section 3: Turn Errors into Sirens  
1. Evidence of Prometheus Server. [URL05](http://ec2-54-89-197-143.compute-1.amazonaws.com:9090/targets)

2. Evidence that Prometheus is monitoring memory, cpu and disk usage of EC2 instances. [SCREENSHOT11](/assets_screenshots/%5BSCREENSHOT11%5D.png)

3. Evidence that Prometheus and AlertManager send alerts when certain conditions exist in the EC2 instance. [SCREENSHOT12](/assets_screenshots/%5BSCREENSHOT12%5D.png)

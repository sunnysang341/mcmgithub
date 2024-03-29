Welcome to the AWS CodeStar sample web applicationtest
==================================================

This sample code helps get you started with a simple Go web application deployed by AWS CloudFormation to AWS Lambda and Amazon API Gateway.

What's Here
-----------

This sample includes:

* README.md - this file
* buildspec.yml - this file is used by AWS CodeBuild to package your
  application for deployment to AWS Lambda
* main.go - this file contains the sample Go code for the web application
* main_test.go - this file contains unit tests for the sample Go code
* template.yml - this file contains the AWS Serverless Application Model (AWS SAM) used
  by AWS CloudFormation to deploy your application to AWS Lambda and Amazon API
  Gateway.


What Do I Do Next?
------------------

If you have checked out a local copy of your repository you can start making
changes to the sample code.  We suggest making a small change to main.go first,
so you can see how changes pushed to your project's repository are automatically
picked up by your project pipeline and deployed to AWS Lambda and Amazon API Gateway.
(You can watch the pipeline progress on your AWS CodeStar project dashboard.)
Once you've seen how that works, start developing your own code, and have fun!

To run your test locally, go to the root directory of the sample code and
run the `go test` command, which AWS CodeBuild also runs through your
`buildspec.yml` file.

To test your new code during the release process, modify the existing tests or
add tests for any new packages you create. AWS CodeBuild will run the tests during
the build stage of your project pipeline. You can find the test results in the
AWS CodeBuild console.

Learn more about AWS CodeBuild and how it builds and tests your application here:
https://docs.aws.amazon.com/codebuild/latest/userguide/concepts.html

Learn more about AWS Serverless Application Model (AWS SAM) and how it works here:
https://github.com/awslabs/serverless-application-model/blob/master/HOWTO.md

AWS Lambda Developer Guide:
https://docs.aws.amazon.com/lambda/latest/dg/deploying-lambda-apps.html

Learn more about AWS CodeStar by reading the user guide, and post questions and
comments about AWS CodeStar on our forum.

AWS CodeStar User Guide:
http://docs.aws.amazon.com/codestar/latest/userguide/welcome.html

AWS CodeStar Forum: https://forums.aws.amazon.com/forum.jspa?forumID=248

What Should I Do Before Running My Project in Production?
------------------

AWS recommends you review the security best practices recommended by the framework
author of your selected sample application before running it in production. You
should also regularly review and apply any available patches or associated security
advisories for dependencies used within your application.

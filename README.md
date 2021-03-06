# How to upload and view Mocha-js terminal logs on [LambdaTest](https://www.lambdatest.com/?utm_source=github&utm_medium=repo&utm_campaign=Mocha-js-terminal-logs) 

If you want to upload and view Mocha-js terminal logs on LambdaTest, you can follow the below steps. You can refer to sample test repo [here](https://github.com/LambdaTest/Mocha-selenium-sample).

# Steps:

You can upload any test/terminal report generated by the testing framework in json,xml,txt and other common format. The file uploaded can then be viewed in the automation dashboard page under LOGS sections. The file size should not exceed 2MB.

The terminal logs can be uploaded using the LambdaTest API.

### Step 1: Authorise using credentials

Go to the LambdaTest API webpage [here](https://automation-api-docs.lambdatest.com/index.html).
Use the **Authorise** button to fill your valid LambdaTest credentials to authenticate your API requests.

### Step 2: 

Go to the session section and select the terminal logs POST request [(link)](https://automation-api-docs.lambdatest.com/index.html#/Session/UploadTerminalLogs). Provide your session-id and select the log file you want to upload (json,xml, txt) . 

Note: You can also do this with a CURL command like so (replace session-d, auth code and filename):

```bash
curl -X POST "https://api.lambdatest.com/automation/api/v1/sessions/session-id/terminal-logs" -H "accept: application/json" -H "Authorization: Basic aWliMjAxOTAyNDprUlZIV2lQRHlUR0JkZU9qbpadUGN2WUZHSVBhalNYc3hRN0ZDeWpqbDZxNUlzRWo1aA==" -H "Content-Type: multipart/form-data" -F "file=filename"
```

After a successful POST request, you should be able to view terminal logs for the session on your dashboard.

## Additional Links

* [Advanced Configuration for Capabilities](https://www.lambdatest.com/support/docs/selenium-automation-capabilities/)
* [How to test locally hosted apps](https://www.lambdatest.com/support/docs/testing-locally-hosted-pages/)
* [How to integrate LambdaTest with CI/CD](https://www.lambdatest.com/support/docs/integrations-with-ci-cd-tools/)

## Tutorials ????

Check out our latest tutorials on JavaScript automation testing ????

* [How To Generate Mocha Reports With Mochawesome?](https://www.lambdatest.com/blog/how-to-generate-mocha-reports-with-mochawesome/)
* [Mocha JavaScript Tutorial With Examples For Selenium Testing](https://www.lambdatest.com/blog/mocha-javascript-tutorial-with-examples-for-selenium-testing/)

## Documentation & Resources :books:
      
Visit the following links to learn more about LambdaTest's features, setup and tutorials around test automation, mobile app testing, responsive testing, and manual testing.

* [LambdaTest Documentation](https://www.lambdatest.com/support/docs/?utm_source=github&utm_medium=repo&utm_campaign=Mocha-js-terminal-logs)
* [LambdaTest Blog](https://www.lambdatest.com/blog/?utm_source=github&utm_medium=repo&utm_campaign=Mocha-js-terminal-logs)
* [LambdaTest Learning Hub](https://www.lambdatest.com/learning-hub/?utm_source=github&utm_medium=repo&utm_campaign=Mocha-js-terminal-logs)    

## LambdaTest Community :busts_in_silhouette:

The [LambdaTest Community](https://community.lambdatest.com/) allows people to interact with tech enthusiasts. Connect, ask questions, and learn from tech-savvy people. Discuss best practises in web development, testing, and DevOps with professionals from across the globe ????

## What's New At LambdaTest ???

To stay updated with the latest features and product add-ons, visit [Changelog](https://changelog.lambdatest.com/) 
      
## About LambdaTest

[LambdaTest](https://www.lambdatest.com/?utm_source=github&utm_medium=repo&utm_campaign=Mocha-js-terminal-logs) is a leading test execution and orchestration platform that is fast, reliable, scalable, and secure. It allows users to run both manual and automated testing of web and mobile apps across 3000+ different browsers, operating systems, and real device combinations. Using LambdaTest, businesses can ensure quicker developer feedback and hence achieve faster go to market. Over 500 enterprises and 1 Million + users across 130+ countries rely on LambdaTest for their testing needs.    

### Features

* Run Selenium, Cypress, Puppeteer, Playwright, and Appium automation tests across 3000+ real desktop and mobile environments.
* Real-time cross browser testing on 3000+ environments.
* Test on Real device cloud
* Blazing fast test automation with HyperExecute
* Accelerate testing, shorten job times and get faster feedback on code changes with Test At Scale.
* Smart Visual Regression Testing on cloud
* 120+ third-party integrations with your favorite tool for CI/CD, Project Management, Codeless Automation, and more.
* Automated Screenshot testing across multiple browsers in a single click.
* Local testing of web and mobile apps.
* Online Accessibility Testing across 3000+ desktop and mobile browsers, browser versions, and operating systems.
* Geolocation testing of web and mobile apps across 53+ countries.
* LT Browser - for responsive testing across 50+ pre-installed mobile, tablets, desktop, and laptop viewports
    
[<img height="58" width="200" src="https://user-images.githubusercontent.com/70570645/171866795-52c11b49-0728-4229-b073-4b704209ddde.png">](https://accounts.lambdatest.com/register)
      
## We are here to help you :headphones:

* Got a query? we are available 24x7 to help. [Contact Us](support@lambdatest.com)
* For more info, visit - [LambdaTest](https://www.lambdatest.com/?utm_source=github&utm_medium=repo&utm_campaign=Mocha-js-terminal-logs)

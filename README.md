<h1>Smart UI Testing With Selenium Node.JS</h1>

<img height="400" src="https://user-images.githubusercontent.com/126776938/232535511-8d51cf1b-1a33-48fc-825c-b13e7a9ec388.png">


<p align="center">
  <a href="https://www.lambdatest.com/blog/?utm_source=github&utm_medium=repo&utm_campaign=playwright-sample" target="_bank">Blog</a>
  &nbsp; &#8901; &nbsp;
  <a href="https://www.lambdatest.com/support/docs/?utm_source=github&utm_medium=repo&utm_campaign=playwright-sample" target="_bank">Docs</a>
  &nbsp; &#8901; &nbsp;
  <a href="https://www.lambdatest.com/learning-hub/?utm_source=github&utm_medium=repo&utm_campaign=playwright-sample" target="_bank">Learning Hub</a>
  &nbsp; &#8901; &nbsp;
  <a href="https://www.lambdatest.com/newsletter/?utm_source=github&utm_medium=repo&utm_campaign=playwright-sample" target="_bank">Newsletter</a>
  &nbsp; &#8901; &nbsp;
  <a href="https://www.lambdatest.com/certifications/?utm_source=github&utm_medium=repo&utm_campaign=playwright-sample" target="_bank">Certifications</a>
  &nbsp; &#8901; &nbsp;
  <a href="https://www.youtube.com/c/LambdaTest" target="_bank">YouTube</a>
</p>
&emsp;
&emsp;
&emsp;

*Learn the how to get started with Smart UI testing with Selenium Node.JS on the LambdaTest platform.*


[<img height="58" width="200" src="https://user-images.githubusercontent.com/70570645/171866795-52c11b49-0728-4229-b073-4b704209ddde.png">](https://accounts.lambdatest.com/register?utm_source=github&utm_medium=repo&utm_campaign=playwright-sample)


## Getting Started with Smart UI Testing

Smart UI testing is an integral part of ensuring visual consistency across different environments for your web application. Using the LambdaTest platform with Selenium and Node.js, this process becomes intuitive and efficient.

### Pre-Requisites: 

To execute the tests, your need to login to your lambdatest account and from the `Sidebar` you can find the `Username` and `Access Key` information which needs to be added to your environment variables: 

For MacOS/Linux: 

```bash
export LT_USERNAME="<Your Username>"
export LT_ACCESS_KEY="<Your Access Key>"
```

For Windows CMD

```bash
set LT_USERNAME="<Your Username>"
set LT_ACCESS_KEY="<Your Access Key>"
```

For Windows PowerShell

```ps
$env:LT_USERNAME="<Your Username>"
$env:LT_ACCESS_KEY="<Your Access Key>"
```

Now, navigate to `SmartUI` section from the sidebar and create a new project with the `project type` as the following: 

- **Web** - For running the tests using `hooks` within the `selenium/cypress/playwright` functional tests.
- **CLI** - For running your `SDK` execution for DOM capture and render on multiple browsers and viewports for comparison.

### Features

#### LT-Hooks Integration
- **Location:** See the `hooks` folder, where you can see all the `examples` scripts to setup your suite or run the demo.  
- **Purpose:** Enhance visual regression capabilities in your LambdaTest web automation tests.
- **Benefits:** Increase efficiency with advanced testing features with visual regression testing.
- **Documentation:** [LambdaTest Selenium Visual Regression Documentation](https://www.lambdatest.com/support/docs/selenium-visual-regression/).


#### SmartUI SDK Utilization
- **Location:** Check out the `sdk` folder, and setup the environment for running the tests. 
- **Purpose:** Use the SmartUI SDK for comprehensive visual testing in both local and remote automation tests environments.
- **Advantages:** Ensure consistent DOM capturing and rendering across various browsers and resolutions.
- **More Information:** [SmartUI Selenium JavaScript SDK Documentation](https://www.lambdatest.com/support/docs/smartui-selenium-js-sdk/).
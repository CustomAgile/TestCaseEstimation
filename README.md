Rally Test Case Estimation
======================

![Title](https://raw.github.com/RallyApps/TestCaseEstimation/master/screenshots/title-screenshot.png)

## Overview

Rally's approach is to create a task under the user story for testing tasks and associate the test cases to the user stories. But, what if you wanted to track the team's effectiveness at estimating the amount of effort by test case, you can use this app. As you enter the data on test cases, the app will roll the results up.

## How to Use

### Running the App

If you want to start using the app immediately, create an Custom HTML app on your Rally dashboard. Then copy App.html from the deploy folder into the HTML text area. That's it, it should be ready to use. See [this](http://www.rallydev.com/help/use_apps#create) help link if you don't know how to create a dashboard page for Custom HTML apps.

Or you can just click [here](https://raw.github.com/RallyApps/TestCaseEstimation/master/deploy/App.html) to find the file and copy it into the custom HTML app.

### Using the App

* You need to setup three custom decimal fields in the workspace where you will be using the app: Test Case Estimate, Test Case ToDo, and Test Case Actual.
* This app has been rewritten to use the batchToolkit. The use of the batchToolkit means that only one request for a query (or queries) is issued; no longer is there a query request issued per test case. So, for workspaces/projects with a large amount of test cases, this app should render noticeably faster.
* The totals have been repositioned to the end of the report. The chart has a scale on it and you can hover the cursor over the quantity bar of interest to obtain the specific count for that bar.


## Customize this App

You're free to customize this app to your liking (see the License section for details). Since this app uses a very old version of Rally's SDK, the app is only presented in its deployed form.

## License

TestCaseEstimation is released under the MIT license.  See the file [LICENSE](https://raw.github.com/RallyApps/TestCaseEstimation/master/LICENSE) for the full text.

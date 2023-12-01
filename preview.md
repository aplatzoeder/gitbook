# Preview

Preview your application before you publish it.

***

### How to preview an application

Click the Preview button on the task bar.

Your application opens in a browser window and runs on your local host server. This is a temporary instance of your application that ceases to exist as soon as you close the browser window.

### Debugging in preview mode

In preview mode you can also use your browser's developer tools to view run-time details of your application's actions. The details will only be available to view while the relevant page displays; when you navigate to a different page, runtime details of the previous page are lost and only the details of the page that you are currently on will be available to view.

Some of the run-time details that can be viewed are:\


* the action's name
* values of all relevant variables or parameters
* targets impacted by the action
* errors

Steps:\


1. Open the Developer Tools of your browser (On Windows press F12 or see [Chrome Devtools](https://developers.google.com/web/tools/chrome-devtools/open) for more details.)
2. Once the Developer Tools screen is open, click on the Console tab.
3. The application's scripts are listed in the sequence of execution. Click on a specific script to view in the Sources tab the script's code and any errors, if applicable.
4. Click on the Console tab to return to the high-level list of scripts.

Note:\
This preview feature is not related to the _"Switch Debug On"_ feature in Application Manager.

\

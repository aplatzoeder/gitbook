# Settings

A Setting is a constant value that you can use throughout your application. The application can never change a setting's value, only you can.

You can also mark a Setting as _"secret"_, which will ensure that any personal or sensitive data stored in that Setting will remain secure, e.g passwords, usernames, ID numbers, etc.

The use of Settings will contribute to quick and easy maintenance of your application and is especially useful when you want to deploy one application in multiple environments and need different values. This could, for example, be folder or file names.

Another benefit of using Settings is that their values can be changed on Application Manager, without having to redesign or redeploy your application.

***

_Add a Setting_

***

### How to use Settings

1. Provide a name and value for a setting.
2. Select the _Secret_ checkbox if required.
3. Assign Settings to relevant properties (e.g. a control's property).
4. If required, change setting values as part of the application deployment process or on Application Manager after deployment.

_Note:_ Stadium will not export the value of a secret from the Designer to Application Manager when the Application is deployed. The value of secrets must be provided as part of the deployment process or on Application Manager.

***

# Pages

Pages contain the [controls](.gitbook/assets/Controls) that make up each screen in your application. Decide what to put on each page and how to lay it out. Usually each page in the designer corresponds to a menu item in the UI.

***

_Add a Page_

***

### Properties

1.  **Parameters**

    Define any parameters that will pass data between pages in the url query string. See _Working with Parameters_, below, for more details.
2.  **Template**

    A template allows to create a consistent layout for your pages throughout your application. With this property you can choose which template you want to apply to the page.
3.  **Title**

    Set a display title for the page. The title is placed in the title tag in the head of the HTML document. If no title is set for a page, the [Application Title](broken-reference) will be used in conjunction with the page name.

***

### Events

1.  **Load**

    An event that triggers when the page finished loading.

***

### Working with parameters

A parameter can be used to send data from one page to another.

There are 2 legs to using a parameter: the sending part and the receiving part. In Stadium you have to define the receiving part before you define the corresponding sending part.

To define the receiving part, go to your receiving (destination) page and add the required parameters in the page's properties section.

Then go to your sending (calling) page to set up the sending part of your parameters by doing the following:

1. Add a Link control to your sending page.
2. For the Url property, select the destination page.
3. The parameters that you defined on the destination page will now be available as Input Parameters. Provide the required values that will be passed on to the destination page.

Going back to the destination page the parameters will now be available to assign (using SetValue) to controls or to variables for further use in queries or other actions.

# Application

In the Stadium Designer, you can build applications containing [Pages](broken-reference), [Scripts](broken-reference), [Settings](broken-reference) and [Connectors](.gitbook/assets/Connectors). Click on the application in the Application Explorer to see the application properties.

***

### Application Properties

1.  **Start Page**

    Each application has a default start page. This page is shown when no page is specified in the URL used to browse to the application.
2.  **Theme**

    The theme that will be applied to the application.
3.  **Enable Style Sheet**

    When this checkbox is selected, the StyleSheet menu option (on the left of the interface) becomes visible. The Style Sheet feature allows you to include in your application the styles of an existing CSS file by pasting the content into the StyleSheet editor. It also allows for the typing and editing of styles, as long as it is in the standard CSS format.
4.  **Head**

    Add tags in the Head Editor that you want to include inside your HTML \<head> \</head> tag. These tags are for example styles, scripts and meta tags.

    The format and content of each tag must be exactly as they are to appear in the rendered HTML. You don't have to add \<head> and \</head> in the Head Editor.

    The tags you add here will be included on all of your application's pages.
5.  **Http Headers**

    Http headers that will be included in responses from the application.

    The following headers are included in your application by default:

    * Content-Security-Policy
    * X-Content-Type-Options
    * X-Frame-Options

    _Note:_

    \


    * You can add additional headers at any stage of development. However, as soon as the application is published to your production site, any subsequent updates made to the headers inside of the Stadium Designer will not be updated on the production site (even after publishing the updated application).
    * See [here](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers) for more details on HTTP headers.
6.  **Max File Upload Size**

    This is the maximum size of any file that can be uploaded to the deployed application.
7.  **Session Variables**

    Session variables are specific to each of your site's users and exist only while the user's session with your application is _active_. Session variables store information that can be accessed by multiple pages in your application, or even accessed on the same page by a user returning to that page multiple times during the course of a user session. For Stadium applications the time-out setting for an inactive session to expire is _60 minutes_.

    There is no limit to the number of session variables that you can create in Stadium, but beware of negatively affecting your application's performance by creating too many variables.

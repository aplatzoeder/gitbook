# Templates

Templates can be used to display [controls](.gitbook/assets/Controls) on multiple [pages](broken-reference) without having to add those controls to each page.

Add common application features, such as menus and footers, to a template and assign the template to multiple pages.

When a Stadium page is rendered to html, the template and the page are merged together.

By default, pages in Stadium are all assigned an empty template called "DefaultTemplate".

***

_Add a template_

***

### How it works

1\. Page contains a form and a _Template_ property that is set to "DefaultTemplate":\


2\. The _DefaultTemplate_ contains a logo and a menu in the header, and a link in the footer:\


3\. When generated, the template and the page are merged:\

# Purejs-issue

*a simple issue tracker application and as you can see the user interface is split up into two sections.*

![img](images/screenshot.png)

## Docs

### Description

This is a simple issue trackker application. On top an input form is visible. By using the input fields for Description, Severity and Assigned To the user is able to enter new issues. The issues are stored in the Browser’s Local Storage. The list of existing issues is printed out in the bottom area. Here you can see that each issue is printed out with the details of description, severity and assigned to. In addition you can see that the issue is identified by a unique issue id. The issue is a GUID which is generated when the issue is created and stored in the Local Storage as well. Furthermore each issue has a status assigned. By default the status is “Open”. If an issue is resolved the user is able to set the status to “Closed” by using the Close button. The issue can be deleted from the list (and from Local Storage) by clicking on button Delete.

###Technology

1. We’ll use Bootstrap CSS classes for applying styling to the user interface components.
2. We use a small JS library (ChanceJS) to generate unique identifiers for issues.
3. Using live-server

###Summary

Modern JavaScript frameworks like Angular, React and Vue.js makes it easy and convenient to write single page web application. However those frameworks are not essential and you can achieve the same results with plain & pure JavaScript. Furthermore, understanding the basics of JavaScript will help you to learn and use JS frameworks.

## License

The code and styles are licensed under the CodingTheSmartWay.com , you can learn from this and contribute to CodingTheSmartWay.

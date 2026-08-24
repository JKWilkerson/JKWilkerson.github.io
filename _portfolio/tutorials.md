---
title: "Tutorials and Learning Content"
excerpt: "Selected tutorials and learning paths I built"
header:
#   image: /assets/images/tutorials-icon.png
#   teaser: /assets/images/tutorials-icon.png
toc: true
toc_sticky: true
toc_icon: "cog"
---

<!-- TODO


- Add a description and jump nav links(?)
- Add descriptions for each

- Maybe be more selective about which tutorials to use.
- Figure out where to describe each tutorial, and change the descriptions.
- Download content for all of these from sites
 -->

Here are some learning paths that I worked on as part of the Oracle JET (JavaScript Extension Toolkit) user-assistance team. 

Oracle JET learning paths are collections of progressive tutorials that provide hands-on instruction to app developers.

The tutorials were authored using Markdown, hosted on an internal GitLab repository, and published using an Oracle-integrated instance of the Gatsby static site generator.

TK: Discuss planning, design, maintenance for them
These required maintenance and updates alongside the releases of Oracle JET. I've worked on a number of improvements to this learning path: updating it to use new JET web components, replacing the use of JavaScript with TypeScript, adding improved navigation, and various other regular updates and fixes to it alongside new releases of Oracle JET.

# Build Virtual DOM Apps

This learning path teaches developers how to build Oracle JET apps using a virtual DOM architecture. It guides users step-by-step through the process of creating a virtual DOM app, customizing the layout, implementing a master-detail UI pattern, and building in CRUD functionality by connecting to a REST-enabled backend.

<!-- Detail the process:
-
-
- Managed the REST-enabled backend on an Oracle APEX workspace -->

View the [learning path's main page](https://docs.oracle.com/en/middleware/developer-tools/jet/19/vdom-tutorials.html) for a full list of its modules and tutorials. Some selected tutorials are included here.

<!--Should I pick? different samples? Table is good though -->

| Name                  |                     Module                                | Description |
|---------------------- | ------------------------------------------------------------------| ----------------  |
| [Add Containers to the Oracle JET Virtual DOM App](https://apexapps.oracle.com/pls/apex/f?p=44785:112:0::::P112_CONTENT_ID:32346) | Responsive Design | This first tutorial in the module teaches developers how to add Oracle JET flex layout style classes to their app to make their page layout responsive to screen-size changes. |
| [Show or Hide Content in the Oracle JET Virtual DOM App](https://apexapps.oracle.com/pls/apex/f?p=44785:112:0::::P112_CONTENT_ID:32348)n| Responsive Design | The third tutorial teaches developers how to monitor changes in the size of the window that their app is running in and modify their app’s components to load different content to adjust to changes in screen size. |
| [Create the Master View in an Oracle JET Virtual DOM App](https://apexapps.oracle.com/pls/apex/f?p=44785:112:0::::P112_CONTENT_ID:32350) | Master Detail Views in Oracle JET | This first tutorial in the module teaches developers how to read data from a local JSON document and use an Oracle JET data-provider object to display the data in a list. |
| [Handle Selection Events in an Oracle JET Virtual DOM App](https://apexapps.oracle.com/pls/apex/f?p=44785:112:0::::P112_CONTENT_ID:32352) | Master Detail Views in Oracle JET | This tutorial concludes this module and instructs developers on how to use change listeners and event handlers to modify their app’s displayed master-detail data to respond to Oracle JET List View component selection events. |


# [Discover Accessibility](https://docs.oracle.com/en//middleware/developer-tools/jet/18/accessibility.html)

I created this learning path that teaches users how to test Oracle JET web apps for accessibility and fix accessibility issues.

The tutorial was created to follow Web Content Accessibility Guidelines (WCAG) 2.2. It uses an Oracle JET app to teach users accessibility standards and methods for testing and ensuring the accessibility of Oracle JET apps.

The first module, _Identify Accessibility Issues_, teaches users about accessibility issues and methods to perform accessibility audits and inspections. The second module, _Validate and Fix Application Accessibility_, guides users through the process of fixing accessibility in their sample app and its JET web components.

There are seven tutorials in the learning path.

| Name                  |                     Module                                |          Description         |
|---------------------- | ------------------------------------------------------------------| ----------------  |
| [Test an Oracle JET Application for Accessibility: Visual Inspection](https://apexapps.oracle.com/pls/apex/f?p=44785:112:0::::P112_CONTENT_ID:29064) | Identify Accessibility Issues | Learn how to perform a manual accessibility test of a web app, as well as how the JET audit framework can help find accessibility issues. |
| [Test an Oracle JET Application for Keyboard-Only Accessibility](https://apexapps.oracle.com/pls/apex/f?p=44785:112:0::::P112_CONTENT_ID:29065) | Identify Accessibility Issues | Learn how to perform a keyboard-only test of a web app. |
| [Perform Screen-Reader Validation on an Oracle JET Application](https://apexapps.oracle.com/pls/apex/f?p=44785:112:0::::P112_CONTENT_ID:29066) | Identify Accessibility Issues | Learn how to validate a web app with a screen reader and become familiar with screen-reader voices. |
| [Customize the Connected Lifecycle Events](https://apexapps.oracle.com/pls/apex/f?p=44785:112:0::::P112_CONTENT_ID:29075) | Validate and Fix Application Accessibility | Learn how to set an accessible page title and provide the correct load message to the `aria-live region` for each page and tab displayed in the demo app. |
| [Validate the Accessibility of Master Detail Views in an Oracle JET Application](https://apexapps.oracle.com/pls/apex/f?p=44785:112:0::::P112_CONTENT_ID:29076) | Validate and Fix Application Accessibility | Learn how to identify and fix accessibility issues in the Organization tab of the demo app. |
| [Verify the Accessibility of Oracle JET Components Table and Message](https://apexapps.oracle.com/pls/apex/f?p=44785:112:0::::P112_CONTENT_ID:29077) | Validate and Fix Application Accessibility | Learn how to identify and fix the remaining accessibility issues in the Employees page of the demo app. |
| [Test Keyboard Navigation in Complex Oracle JET Components](https://apexapps.oracle.com/pls/apex/f?p=44785:112:0::::P112_CONTENT_ID:29078) | Validate and Fix Application Accessibility | Learn how to identify and fix the accessibility issues in the Departments tab of the demo app. |

# End-to-End Testing in Oracle JET

This module extends Oracle JET's app-building learning paths. Using the CRUD apps that users built in the paths' earlier tutorials, it comprises two tutorials that teach how to set up Oracle JET apps for automated end-to-end testing and how to write and run tests using Selenium WebDriver.

<!-- Any other context to include? -->

- [Set up a Test Environment in Oracle JET](https://apexapps.oracle.com/pls/apex/f?p=44785:112:0::::P112_CONTENT_ID:33396)
- [Write Tests for an Oracle JET Web App](https://apexapps.oracle.com/pls/apex/f?p=44785:112:0::::P112_CONTENT_ID:33397)



<!-- 
# [Tutorials for Building Web Applications](https://docs.oracle.com/en//middleware/developer-tools/jet/18/tutorials.html)

This learning path teaches developers how to build apps using a MVVM (Model-View-ViewModel) architecture.
-->
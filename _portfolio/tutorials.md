---
title: "Tutorials and Learning Content"
excerpt: "Tutorials and learning-path content."
header:
#   image: /assets/images/tutorials-icon.png
  teaser: /assets/images/tutorials-icon.png
toc: true

toc_icon: "cog"
---

<!-- TODO


- Add a description and jump nav links(?)
- Add descriptions for each

- Maybe be more selective about which tutorials to use.
- Figure out where to describe each tutorial, and change the descriptions.
- Download content for all of these from sites
--- -->

Here is a collection of some tutorials and learning paths that I worked on as part of the Oracle JET (JavaScript Extension Toolkit) user-assistance team. 

Oracle JET learning paths are collections of progressive tutorials that provide hands-on instruction to app developers and end users of the toolkit. They cover subjects including building Oracle JET web apps using different architectures, testing and creating accessible apps, and end-to-end testing.

## [Tutorials for Building Virtual DOM Apps](https://docs.oracle.com/en/middleware/developer-tools/jet/19/vdom-tutorials.html)

This learning path teaches developers how to build Oracle JET apps using a virtual DOM architecture. It was a collaborative project, though I independently planned and created the modules _Compose Components_, _Responsive Design_, and _Master Detail Views in Oracle JET_.

You can look at the [learning path's main page](https://docs.oracle.com/en/middleware/developer-tools/jet/19/vdom-tutorials.html) for a full list of its modules and tutorials, though I've included some examples here.

### From the _Responsive Design_ Module

- [Add Containers to the Oracle JET Virtual DOM App](https://apexapps.oracle.com/pls/apex/f?p=44785:112:0::::P112_CONTENT_ID:32346): 
    This first tutorial in the module teaches developers how to add Oracle JET flex layout style classes to their app to make their page layout responsive to screen-size changes.
- [Show or Hide Content in the Oracle JET Virtual DOM App](https://apexapps.oracle.com/pls/apex/f?p=44785:112:0::::P112_CONTENT_ID:32348): 
    The third tutorial teaches developers how to monitor changes in the size of the window that their app is running in and modify their app’s components to load different content to adjust to changes in screen size.

### From the _Master Detail Views in Oracle JET_ Module

- [Create the Master View in an Oracle JET Virtual DOM App](https://apexapps.oracle.com/pls/apex/f?p=44785:112:0::::P112_CONTENT_ID:32350): 
    This first tutorial in the module teaches developers how to read data from a local JSON document and use an Oracle JET data-provider object to display the data in a list.
- [Handle Selection Events in an Oracle JET Virtual DOM App](https://apexapps.oracle.com/pls/apex/f?p=44785:112:0::::P112_CONTENT_ID:32352): 
    This tutorial concludes this module and instructs developers on how to use change listeners and event handlers to modify their app’s displayed master-detail data to respond to Oracle JET List View component selection events.

## [Tutorials for Building Web Applications](https://docs.oracle.com/en//middleware/developer-tools/jet/18/tutorials.html)

This learning path teaches developers how to build apps using a MVVM (Model-View-ViewModel) architecture.

Over Oracle JET's release cycles, I've worked on a number of improvements to this learning path: updating it to use new JET components, replacing the use of JavaScript with TypeScript, adding improved navigation, and applying regular updates and fixes to it alongside new releases of Oracle JET.

### End-to-End Testing in Oracle JET

This module was created for both the virtual DOM and MVVM app-building learning paths.

It teaches developers how to set up their Oracle JET apps for end-to-end testing and how to write and run automated tests using Selenium WebDriver.

- [Set up a Test Environment in Oracle JET](https://apexapps.oracle.com/pls/apex/f?p=44785:112:0::::P112_CONTENT_ID:33396)
- [Write Tests for an Oracle JET Web App](https://apexapps.oracle.com/pls/apex/f?p=44785:112:0::::P112_CONTENT_ID:33397)

## [Discover Accessibility](https://docs.oracle.com/en//middleware/developer-tools/jet/18/accessibility.html)

I created an updated version of this learning path that teaches users how to test Oracle JET web apps for accessibility and fix accessibility issues.
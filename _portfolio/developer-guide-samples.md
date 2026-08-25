---
title: "Documentation"
excerpt: "Selected guides, procedures, and reference content I created"
header:
  # image: /assets/images/documentation-icon.png
  # teaser: /assets/images/documentation-icon.png
toc: true
toc_sticky: true
toc_icon: "cog"
---

These samples come from my work supporting two enterprise software products at Oracle.

- Oracle JavaScript Extension Toolkit (JET) is an open-source collection of Oracle and third-party libraries that is used with the Redwood Design System to build the user interfaces of hundreds of Oracle apps. It is targeted to intermediate to advanced JavaScript developers and makes it simple and efficient to build applications that consume and interact with Oracle products and services, particularly Oracle Cloud.
- Oracle Visual Builder Studio is a cloud-based Platform as a Service (PaaS) product for enterprise application development. The platform combines low-code development and DevOps tooling to help developers build, test, and deploy web and mobile apps.

I collaborated with developers, product managers, and designers to plan, implement, and publish documentation alongside the releases of these products, maintaining the quality and consistency of our content alongside updates to the products' features. I created the majority of this content using Oxygen XML Editor, alongside a DITA-based content management system.



<!-- from Walter on JET Guides: Oracle JET introduced a new development paradigm, the virtual DOM architecture, to enable app developers to create apps and components using a virtual DOM engine.

Using a DITA-based content management system, I created a new developer's guide from scratch that described how to develop apps using the virtual DOM architecture. Where appropriate, I took advantage of the content reuse capabilities in the DITA-based content management system to reuse content from the developer's guide for the pre-existing Model-View-ViewModel architecture..  -->

<!-- From kenneth ganfield on VBS: As a Principal User Assistance Developer, I was part of a team responsible for writing and publishing web-based documentation for Oracle Visual Builder and Visual Builder Studio, cloud-based software development Platform as a Service (PaaS) products for enterprise application development. My responsibilities included working with developers and product managers to plan and architect publications to cover the products’ expanding features. -->

<!-- This needs better organization. Organize by types of documents. A line about where these are drawn from -->
<!-- TODO
- Use oracle javascript extension toolkit (JET) in earlier breakdown
- Can I grab content from other 
- should I make global body text smaller- all text maybe
- Add a description with jump nav links(?)
- Add descriptions for each

Be judicious about how many and what samples to include in this portfolio, in this page and throughout
- a range of content is better
- I can create content that is not present. 

At some place, I need to describe what each guide is- what the product is.
-->

---

# Guides

From the developer guides _Developing Oracle JET Apps Using MVVM Architecture_ and _Developing Oracle JET Apps Using Virtual DOM Architecture_:

- [Migrate Oracle JET Legacy Components to Core Pack Components](https://docs.oracle.com/en/middleware/developer-tools/jet/19/vdom/core-pack-migrator.html#GUID-C090B095-5014-407B-8BE0-E452333124F4)
  - An appendix chapter I wrote that discusses how to use an Oracle JET migrator tool on files with legacy web components, in order to migrate the components to their new Core Pack  equivalents. 
- [About the Oracle JET Testing Technology Stack](https://docs.oracle.com/en/middleware/developer-tools/jet/19/develop/test-debug-oracle-jet-apps.html#GUID-F7BF4879-91AC-491C-9332-ED9EC233FE07) and [Configure Oracle JET Apps for Testing](https://docs.oracle.com/en/middleware/developer-tools/jet/19/develop/test-debug-oracle-jet-apps.html#GUID-A87CD5D0-DBCD-4F43-9AE3-937B419BA2A7)
  - Two developer guide topics I wrote for the chapter _Test and Debug Oracle JET Apps_, in order to standardize our app-testing guidance after working with developers and product managers to identify and test our recommended tools and workflows.
<!-- - [Prepare for Oracle JET App Migration](https://docs.oracle.com/en/middleware/developer-tools/jet/18/develop/oracle-jet-app-migration-current-release.html#GUID-B3C17F2D-1798-41A5-A489-F531011FB34B) and [Migrate an App Using the Oracle JET CLI](https://docs.oracle.com/en/middleware/developer-tools/jet/18/develop/oracle-jet-app-migration-current-release.html#GUID-EE148AA7-AED3-4FFE-BFF6-EAFEDB41433C)
  - Descriptive text -->
<!-- - [Add Third-Party Tools or Libraries to Your Oracle JET App](https://docs.oracle.com/en/middleware/developer-tools/jet/19/develop/using-requirejs-modular-development.html#GUID-EC40DF3C-57FB-4919-A066-73E573D66B67)
  - Descriptive text -->
- [Develop Accessible Oracle JET Apps](https://docs.oracle.com/en/middleware/developer-tools/jet/19/develop/developing-accessible-applications.html#GUID-A8970DC0-7935-46B8-9A55-BCF4380B2CFC)
  - This chapter discusses how to create accessible Oracle JET apps using the toolkit's components and features. I worked on this chapter in conjunction with the learning path [Discover Accessibility](https://docs.oracle.com/en//middleware/developer-tools/jet/18/accessibility.html).

From the user guide _Using Visual Builder Studio_:

- [Reapply a Merge Request's Commits to a New Branch](https://docs.oracle.com/en/cloud/paas/visual-builder/visualbuilder-manage-development-process/reapply-merge-requests-commits-new-branch.html)
  - A short topic on the platform's feature that enables users to apply commits from a merged or closed merge request to a new merge request and review branch.
- [Set Review and Merge Restrictions on a Repository Branch](https://docs.oracle.com/en/cloud/paas/visual-builder/visualbuilder-manage-development-process/review-merge-restrictions-repository-branch.html)
  - A short topic on configuring a branch so that it allows another branch to merge into it only after the merge request reaches the required number of approvals.
<!-- - [Retarget a Merge Request's Commits to Another Branch](https://docs.oracle.com/en/cloud/paas/visual-builder/visualbuilder-manage-development-process/retarget-merge-requests-commits-another-branch.html)
  - Descriptive text
- [Watch a Job](https://docs.oracle.com/en/cloud/paas/visual-builder/visualbuilder-manage-development-process/watch-job.html)
  - Descriptive text -->


# Release Notes

New editions of the publication _What's New in Oracle JET_ are released alongside each new version of the Oracle JavaScript Extension Toolkit (JET) to inform JET developers of notable changes to the toolkit and its documentation.

- [_What's New in Oracle JET 19_](https://docs.oracle.com/en/middleware/developer-tools/jet/19/whats-new/index.html#GUID-737BD500-6977-49B9-80A6-6105D4BF8F89) (notes for major release)
- [_What's New in Oracle JET 18.1_](https://docs.oracle.com/en/middleware/developer-tools/jet/18.1/whats-new/index.html#GUID-737BD500-6977-49B9-80A6-6105D4BF8F89) (notes for minor release)

# API/CLI Reference Documentation 

<!-- I could really use more of these. This could maybe go into its own page once I have enough content. I think I should have it mostly be API documentation -->

- [Get subissues](https://docs.oracle.com/en/cloud/paas/visual-builder/vb-rest-apis/op-issues-v3-issues-issueid-subissues-get.html) in _REST API for Oracle Visual Builder Studio_
  - A REST API reference endpoint for Oracle Visual Builder Studio's issue-tracking system. It allows the retrieval of the smaller issues that belong to a larger issue.
- [Oracle JET CLI API for CI/CD](https://docs.oracle.com/en/middleware/developer-tools/jet/18/develop/oracle-jet-cli-api-ci-cd.html#GUID-8C4B75C1-BC32-4301-8308-F87219402665) in _Developing Oracle JET Apps Using MVVM Architecture_
  - Descriptive text

An API reference for the Oracle JET command-line interface (CLI), specifically explaining how developers can use the JET CLI inside CI/CD pipelines, helping automate parts of the build, package, publish lifecycle of an Oracle JET application or component.

<!-- I documented the API's setup, configuration, method signature, supported tasks and scopes, parameters, options, and practical JavaScript examples.
I Structured the reference around the developer's progression from understanding the API's purpose to implementing increasingly complex CLI operations programmatically. -->



<!-- # Test `.md` content to use and adjust

Here's a quick checklist of the important folders/files you'll want to be mindful of:

| Name                  |                     Fill Text Here                                |                   |
|---------------------- | ------------------------------------------------------------------| ----------------  |
| `TK`                  | [Google Standard Analytics](https://www.google.com/analytics/)    |     tk            |
| **`TK`**              | Wer reitet so spat durch Nacht und Wind?                          |     tk            |
| `TK`                  | [Google Standard Analytics](https://www.google.com/analytics/)    |     tk            |
| `TK`                  | Wer reitet so spat durch Nacht und Wind?                          |     tk            |
| `TK`                  | [Google Standard Analytics](https://www.google.com/analytics/)    |     tk            |
| `TK`                  | Wer reitet so spat durch Nacht und Wind?                          |     tk            |
| _`TK`_                | Wer reitet so spat durch Nacht und Wind?                          |     tk            | -->
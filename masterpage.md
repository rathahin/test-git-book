---
description: >-
  This guide is provide the knowledge about the master page, so that we can
  start new project and reuse the master page.
---

# What is template

## Template folder

Below is the folder per solution explorer, and its description per each folder.

![](.gitbook/assets/image%20%2820%29.png)

* App\_Data: Used by Telerik \(Optional for migration\)
* App\_Themes: Contains style-sheet which generated from Telerik Themes builder. \(Optional for migration\)
* images: Contains all images resource which is used by the template. \(Required for migration\)
* scripts: Contains all JavaScript client side for controlling the client interface. \(Optional for migration\)
* styles: Contains all style-sheet which controlling look and feel of the template. \(Required for migration\)
* Default.aspx: sample page which have empty content using MasterPageTopBar master page.
* Login.aspx: Login template is require to update to current system. This is stand-alone page without any master page
* MasterPageTopBar.Master: Master page identify the look and feel of generic page in entire project
* SMSConfirmation.aspx: SMS confirmation template is require if our system requires user to login with SMS confirmation.

## Screen

![Login](.gitbook/assets/image%20%2822%29.png)

![SMS Confirmation](.gitbook/assets/image%20%289%29.png)

![Sample page](.gitbook/assets/image%20%2813%29.png)




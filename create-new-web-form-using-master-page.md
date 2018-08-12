---
description: You may need to add new web form for your project
---

# Create new web form using Master Page

* Select the project name
* Press Ctrl+Shift+A

![](.gitbook/assets/image%20%2815%29.png)

* Select "Web Form with Master Page"
* Enter desire name for our new web form
* Once it added, open to check the code

```aspnet
<%@ Page Title="" Language="C#" MasterPageFile="~/MasterPageTopBar.Master" AutoEventWireup="true" CodeBehind="Default.aspx.cs" Inherits="ENTLayoutTemplate.Default" %>

<asp:Content ID="Content1" ContentPlaceHolderID="head" runat="server">
    <telerik:RadCodeBlock ID="RadCodeBlock1" runat="server">
        <script type="text/javascript">
            function rowDblClick(sender, eventArgs) {
                sender.get_masterTableView().editItem(eventArgs.get_itemIndexHierarchical());
            }
        </script>
    </telerik:RadCodeBlock>
</asp:Content>
<asp:Content ID="Content2" ContentPlaceHolderID="ContentPlaceHolderTitle" runat="server">
    SAMPLE PAGE
</asp:Content>
<asp:Content ID="Content3" ContentPlaceHolderID="ContentPlaceHolderMain" runat="server">
    HOME PAGE
</asp:Content>

```

There are 3 placeholder in current master page

1. head: where we can add JavaScript or style-sheet for customize each page
2. title: The title of the page
3. content: where we can add content to the page


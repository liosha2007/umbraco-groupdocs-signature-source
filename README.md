GroupDocs Signature plugin for Umbraco CMS (Source code)
==================================

This module helps you to embed GroupDoc’s high-fidelity online document signature along with selected documents into to Orchard website pages.
With this plugin installed, you can effortlessly sign documents of multiple file formats in your Orchard webpages.

###Installation
* Install Umbraco CMS web site (http://umbraco.org/download) where plugin will be used.
* Install Macro using of plugin source code
    * Copy Groupdocs.EmbedSignature.dll to the root bin directory of the web site.
    * Copy EmbedSignature.ascx to the root usercontrols directory of the web site.
    * Go to the Developer tab of admin umbraco. Create new Macro. Choose .NET User Control as /usercontrols/EmbedSignature.ascx in Main Properties of new Macro - Click Save button. 
    * Click Browse Properties button below and popup with plugin Properties (Guid, FrameWidth, FrameHeight) will be opened. Confirm suggested parameters.
    * Reload the page and go to Parameters tab of created macro. You will see that Parameters were added.
* Use the macro at web pages as <umbraco:macro Alias="[Embed Document Signature Alias]" Guid="[Guid]" FrameWidth="[Width]" FrameHeight="[Height]" runat="server"></umbraco:macro> (for instance, [Width]=600, [Height]=500). Note, Alias is the alias of macro.
  
###[Sign, Manage, Annotate, Assemble, Compare and Convert Documents with GroupDocs](http://groupdocs.com)
1. [Sign documents online with GroupDocs Signature](http://groupdocs.com/apps/signature)
2. [PDF, Word and Image Annotation with GroupDocs Annotation](http://groupdocs.com/apps/annotation)
3. [Online DOC, DOCX, PPT Document Comparison with GroupDocs Comparison](http://groupdocs.com/apps/comparison)
4. [Online Document Management with GroupDocs Dashboard](http://groupdocs.com/apps/dashboard)
5. [Doc to PDF, Doc to Docx, PPT to PDF, and other Document Conversions with GroupDocs Viewer](http://groupdocs.com/apps/viewer)
6. [Online Document Automation with GroupDocs Assembly](http://groupdocs.com/apps/assembly)

###Created by [GroupDocs Marketplace Team](http://groupdocs.com/marketplace/).
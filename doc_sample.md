
[panther]: http://docs.prolifics.com/docs/panther/html/dev_html/images/xpantxtsb.gif.pagespeed.ic.DZ2Phlj8W-.png

![panther][panther] 

## About This Document

_Application Development Guide_ describes an application development path, starting with project setup and configuration through to packaging and deployment. Covering various topics related to application development, it discusses approaches to development, strategies for using Panther effectively, and the order in which tasks should be performed.

This guide is organized in the following sections:

#####_Overview_: Building a Panther Application  
A comprehensive overview of Panther and its application development process.

#####_Section One:_ Preparing for Development  
Topics include the organization of your Panther distribution, a discussion of project requirements, how to set up your application servers and development clients, how to initialize and connect to your database engine and middleware, how to access your application libraries.

#####_Section Two:_ Creating Application Building Blocks  
An introduction to Panther's application components, including screens, widgets, repositories, menu bars, reports and service components.

#####_Section Three:_ Writing the Programming Interface  
Information about programming events in Panther and how to use JPL, C and Java for event processing.

#####_Section Four:_ Defining the Application Design  
Information about accessing widgets programmatically and manipulating the screen sequence in your Panther application.

#####_Section Five:_ Accessing the Database  
The protocol for Panther's interaction with your database engine-how data and status information is fetched from, or written to, the database, how to build screens that use the transaction manager, how the transaction manager gets its information and processes transactions, and how to customize your transaction manager applications.

#####_Section Six:_ Testing Your Application  
Description of Panther's built-in debugger and instructions for using it to debug your application.

#####_Section Seven:_ Deploying the Application  
Information on building Panther development and production executables and for packaging your Panther application for distribution.

#####_Section Eight:_ Advanced Development Topics  
Topics related to Panther's hook functions, portability and internationalization.

#####_Section Nine:_ Appendices  
Information about development utilities. Also includes descriptions of Panther's sample applications.

---
###Documentation Web Site

The Panther documentation web site includes manuals in HTML and PDF formats and the Java API documentation in Javadoc format. The web site enables you to search the HTML files for both the manuals and the Java API.  

Panther product documentation is available on the Prolifics corporate web site at http://docs.prolifics.com/docs/panther/index.htm.

---
###How to Print the Document


You can print a copy of this document from a web browser, one file at a time, by using the FilePrint option on your web browser.  

A PDF version of this document is available from the Panther library page of the documentation web site. You can open the PDF in Adobe Acrobat Reader and print the entire document (or a portion of it) in book format.  

If you do not have the Adobe Acrobat Reader, you can get it for free from the Adobe web site at http://www.adobe.com.  

---
###Documentation Conventions


The following documentation conventions are used throughout this document.  


| Convention | Item |
|------------|------|
| Ctrl+Tab | Indicates that you must press two or more keys simultaneously. Initial capitalization indicates a physical key. |
| _italics_ | Indicates emphasis or book titles. |
| UPPERCASE TEXT | Indicates Panther logical keys.  Example:  XMIT |
| **boldface text** | Indicates terms defined in the glossary. |
| `monospace text` | Indicates code samples, commands and their options, directories, and file names and their extensions. Monospace text also indicates text that you must enter from the keyboard.  Examples:   #include <smdefs.h>  chmod u+w *  /usr/prolifics  prolifics.ini |
| _`monospace italic text`_ | Identifies variables in code representing the information you supply.  Example:  String expr  |
| `MONOSPACE UPPERCASE TEXT` | Indicates environment variables, logical operators, SQL keywords, mnemonics, or Panther constants.  Examples:  CLASSPATH  OR  { } Indicates a set of choices in a syntax line. One of the items should be selected. The braces themselves should never be typed.

|

Separates mutually exclusive choices in a syntax line. The symbol itself should never be typed.

[ ]

Indicates optional items in a syntax line. The brackets themselves should never be typed.

Example:

formlib [-v] library-name [file-list]...

...

Indicates one of the following in a command line:

That an argument can be repeated several times in a command line

That the statement omits additional optional arguments

That you can enter additional parameters, values, or other information

The ellipsis itself should never be typed.

Example:

formlib [-v] library-name [file-list]...

.
.
.

Indicates the omission of items from a code example or from a syntax line. The vertical ellipsis itself should never be typed.

---
###Contact Us!


Your feedback on the Panther documentation is important to us. Send us e-mail at support@prolifics.com if you have questions or comments. In your e-mail message, please indicate that you are using the documentation for Panther.

If you have any questions about this version of Panther, or if you have problems installing and running Panther, contact Customer Support via:

Email at mailto://support@prolifics.com

Prolifics web site at http://profapps.prolifics.com

When contacting Customer Support, be prepared to provide the following information:

* Your name, e-mail address, phone number, and fax number

* Your company name and company address

* Your machine type

* The name and version of the product you are using

* A description of the problem and the content of pertinent error messages

---
<sub><sup> &copy; 2016 Prolifics, All rights reserved. </sup></sub>

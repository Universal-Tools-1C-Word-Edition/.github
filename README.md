# .github
Universal Tools 1С for managed forms
This is freely distributed set of Universal tools: data processors and reports. May be useful for for developers and users for development and support. Works in ALL types of client applications and in all operating systems supported by the "1C:Enterprise" platform, except for mobile.

Supported Operation Systems
Windows x86
Windows x64
Linux x64
Linux x86
It should work on Mac OS, but has not been tested

Supported type of client applications
Thick client managed application
Thin client
Web client (partially)
Supported configuration modes
The module is developed with disabled support for modality and synchronous calls. It should work in all modern and not so configurations

Supported platforms
8.3.12 and later

Distribution method and license
The subsystem is developed and distributed under the GNU General Public License v3.0. The code is open, you can copy and distribute to anyone, but also with open source sharing.

Currently content of tools:
Group processing of catalogs and documents- allows you to massively change the attributes and tabular parts in selected catalogs and documents.
Constant Editor - allows you to edit the values of constants in table mode
Database Storage Structure- View table names and their relationships with metadata objects.
Removal of marked objects- a copy of the standard Data processor from the SSL (Standart Subsystems Library), adapted for use outside the SSL.
Query Console- Data processor for developing and executing queries in user mode. Fork of https://github.com/hal9000cc/RequestConsole9000. GPL3 License
Jobs console- view and set parametrs of scheduled and background jobs. Fork of https://github.com/kuzyara/JobsConsole2019.epf Author's permission
Registration of changes for exchange- Data processor allows you to edit the registration of changes to data exchange objects at the Exchange Plan Node. Is intended for data exchange developers, data administrators and advanced users.
Search and removal of duplicates- A fork of the standard data processor from the SSL (Standart Subsystems Library), to which several parameters for performing the replacement have been added
Code Console- Allows you to execute code from the enterprise without creating external Data Processor. There is syntax highlighting and a minimal contextual hint
Search for object references- an analogue of the standard data processor from the "All functions" menu.
Object attibutes editor- allows low-level editing of attributes of reference objects. Supports document records editing. Fork of https://infostart.ru/public/983887/. Cutted from https://infostart.ru/public/938606/. Author's permission
Reports console- it is based on a Data Composition System and uses most of its features. With its help, you can create and execute reports of almost any complexity without resorting to programming.
Dynamic list- convenient viewing of lists of database tables from a single data processor
HTTP Request Console- allows you to make HTTP requests from 1C.
Loading/Uploading XML with filters - Transferring information between two similar databases. Fork of https://infostart.ru/public/1149722/ Author's permission
Configuration Navigator- This data processor replases standart command "All Functions" and contains additional administrative functions. Fork of https://infostart.ru/public/931586/. Author's permission
File manager - Data processor for convenient work with files between the client and the server.Support file Transfer, View, delete of files. Currently contains synchronous calls. Fork of https://infostart.ru/public/1027326/. Author's permission
Web Services Console -data processor for reading and executing web services on the 1C: Enterprise 8.3 platform. Analog of SoapUI. Allows you to perform a web service operation and display the result as xml or a tree. Fork of https://github.com/ghostaz/WSReader2.git. GPL3 License
Data comparsion console- it is used to compare data obtained from different data sources: 1C 8, 1C 7.7 information databases, SQL databases, CSV/TXT/DBF/XLS/DOC/XML format files, JSON strings, manually filled tabular document. Fork of https://infostart.ru/public/581794. Author's permission
Information about 1C licenses-this is GUI for 1C licensing utilities (RING). Fork of https://infostart.ru/public/1124442/. Author's permission. Должна быть установлена утилита ring и ее модули license
Data loader from Tabular document-Data processor for load data to catalogs and tabular sections of different objects from из Tabular document. Fork of https://infostart.ru/public/269425/. Author's permission
JSON Editor- Allows you to edit JSON strings in a convenient form. It contains JSON syntax highlighting, tree editing, and some auto-substitutions. The editor is based on the library https://github.com/josdejong/jsoneditor . It works on Windows starting from platform version 8.3.14
HTML Editor- Fast debugging of HTML pages display in 1C. It is a screen divided into 4 parts, on the left side there are three editors-HTML, CSS and JavaScript bodies, and on the right - the result field. There is a contextual hint and code completion. The library is used for code editors https://ace.c9.io/. It is indispensable when testing HTML output in 1C, because even from the 8.3.14 platform, the display in the browser and 1C, as well as in different operating systems, can be very different. It works on Windows since platform version 8.3.14. Publication on infostart
Universal data exchange in XML format (with filters and direct download via HTTP service - Unloading and loading according to the exchange rules. Fork of the standard data processor from 1С и https://infostart.ru/public/1176839/. Author's permission. Added the ability to apply filters to unloaded objects, and direct uploading to the database via the http service of Universal Tools.
Data Composition System Editor- Analogue Data Composition Schema wizard for thin client. Currently, it does not support editing layouts and nested schemas.
Object comparison - Comparison attribute to attribute of reference objects with output to tabular document. Fork of https://infostart.ru/public/1240803/. Author's permission
Connector: handy HTTP-client for 1C:Enterprise 8 platform - Python world has a very popular library working with HTTP requests - Requests (author: Kenneth Reitz). The library allows you to send HTTP requests extremely easily. Literally a single line of your code can receive or send data, not caring about making URL, encoding data etc. Connector is "Requests" for 1C world. Fork of https://github.com/vbondarevsky/Connector/blob/master/README-EN.md. Apache-2.0 License
Integration with Standart Sybsystems Liblary (SSL)
There is a possibility of convenient debugging of additional reports and data processors. More detailed at wiki
The "Tools" submenu is added to the lists and forms of objects, which contains items (The forms must be connected to the "Attachable Commands" subsystem):
Add to Comparison - adds selected objects to comparison for further use in the "Object Comparison" tool
Edit Object - Allows you to open the current object in the Attributes editor
Compare Objects - Opens the "Compare Objects" tool with selected links as comparison objects. Available only for lists.
Find Object References - Opens the "Find Object References" tool for the current object.
Upload objects to XML -Performs unloading of selected objects with subordinate links using the "Loading/Uploading XML" tool.
Programming interface
Connector: handy HTTP-client for 1C:Enterprise 8 platform
Accessible from the API via the common module UT_HTTPConnector. For a detailed description, see the library page https://github.com/vbondarevsky/Connector/blob/master/README-EN.md

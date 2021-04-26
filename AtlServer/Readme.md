# ATL Server

**ATL Server Library and Tools**

ATL Server is a library of C++ classes that allow developers to build both client and server parts of service-type C++ applications and web services. It provides much of the functionality required to build large scale internet sites, such as SOAP messaging, caching facilities, threading facilities, regular expression processing, management of session-state, performance monitoring, MIME support, integration with IIS and class for interacting with security and cryptographic infrastructure. The earlier versions of the library are parts of Visual Studio 2002, Visual Studio 2003 and Visual Studio 2005. The project has started from the version of the library released as part of Visual Studio 2005 SP1.

### Foreword from Visual C++ Team

The Visual C++ team is very pleased to announce the release of ATL Server library code as a shared source project on CodePlex.  We hope you will enjoy working on the ATL Server code! You now have the opportunity to add all the features and functionality you want to ATL Server and you can even share your expertise and code directly with the ATL community. Rather than constrain the functionality of ATL Server to fit within Visual C++ product development cycle you can move it forward at a greater pace and implement every feature or change you want in it. We look forward to the evolution of this library under the stewardship of the ATL Server community!

### Introduction to the project
ATL Server is a library of C++ classes that allow developers to build internet based applications. It provides much of the functionality required to build large scale internet sites, such as SOAP messaging, caching facilities, threading facilities, regular expression processing, management of session-state, performance monitoring, MIME support, integration with IIS and class for interacting with security and cryptographic infrastructure.

Terms and requirements to use ATL Server in applications are covered by [Microsoft Limited Permissive License (MS-LPL)](https://en.wikipedia.org/wiki/Shared_Source_Initiative) .  The basic terms of the license indicate:
* You can read, edit, and redistribute the source code for either commercial or non-commercial purposes, 
* You are allowed to charge a licensing fee for the modified work 
* The use of the code is limited to the Windows platform. 
For full and complete details of the license, and to see if it meets your requirements, you should refer to the [MS-LPL license](https://www.openhub.net/licenses/mslpl) .

### List of content of the project
The following parts of ATL Server will part of the shared project:

* Core ATL Server Framework classes in atlisapi.h, atlstencil.h, atlserr.h 
* Caching classes in atlcache.h 
* Cryptography classes in atlcrypt.h 
* HTML generation on server side and reading on client sides in atlhtml.h 
* Performance monitoring classes in atlperf.h 
* Extension management classes in atlextmgmt.h 
* Server and client side support for SOAP based Web services in atlsharedsvc.h, atlsoap.h 
* Session-state classes and interfaces in atlsession.h 
* MIME/SMTP support in atlmime.h and atlsmtpconnection.h 
* Regular Expression support from atlrx.h 
* Stream helpers in atlsoap.h and atlhtml.h 
The source code to the following tools will also become part of the shared source project:
* clstencil.exe - used in running Request Handler DLLs or SRF Files from the command line 
* sproxy.exe - used in generating proxy classes for SOAP based Web Service clients 
* vcdeploy.exe - used in deploying ATL Server projects to IIS 

### Instructions on opening bugs

* Make sure you add a simple code repro, specify toolkit release number, version of Visual Studio, IIS and any additional information that may help to reproduce issue and make resolution of the issue quicker and easier
* If you are not sure whether the issue is a bug in ATL Server or perhaps you do not understand how to use APIs in the right way, please ask about if [discussions tab](https://github.com/Win32-WTL/WTL/discussions) of the site.

### Interested in contributing?

You may join the project by following steps describe here [JoinProject](JoinProject).

### Plans for future releases

* More detailed guidance on using ATL Server with upcoming release of Visual C++ codename Orcas
* We are looking on updating VS2005 samples and adding them to the project. It may also be possible to to see more new examples for the project.
* Building a test suit to capture regressions and provide more confidence to developers when they make changes to source code. At this point, a version of a test suite that Visual C++ team used for testing ATL Server cannot be run outside of test automation environment created by VC++ team. We are looking on how test suite can be refactored

**_If you have any question about the project please use ask them on [discussions tab](https://github.com/Win32-WTL/WTL/discussions) of the site_**. 
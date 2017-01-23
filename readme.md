|Branch|CI        |Templates Publishing |Extension Publishing |
|:-----|:--------:|:-------------------:|:-------------------:|
|vnext|![CI Build](https://winappstudio.visualstudio.com/_apis/public/build/definitions/5c80cfe7-3bfb-4799-9d04-803c84df7a60/114/badge) | ![Templates Publishing Build](https://winappstudio.visualstudio.com/_apis/public/build/definitions/5c80cfe7-3bfb-4799-9d04-803c84df7a60/113/badge) | ![Extension Publishing Build](https://winappstudio.visualstudio.com/_apis/public/build/definitions/5c80cfe7-3bfb-4799-9d04-803c84df7a60/118/badge)|
|master|N/A|N/A|N/A|

UWP Community Template Generator 
===========
The UWP Community Template Generator goal is to help developers with their File->New experience in Visual Studio.  It will generate a strong, generic foundation with the pages you need, but also integrate game changing features like Cortana, action center and background tasks from the start.  Any critical features will have code comments with links to MSDN, stack overflow and blogs to help unblock developers. Once the template is generated for the developer, it can provide base sample data and will be able to compile then run without issue.

Example scenario:
I need an app that uses MVVM Light, uses Cortana, Speech APIs, Ink on one of the pages and will need Azure mobile services.   It will need a background service that does a query every 5 minutes.

To reach our developers in an up-to-date fashion, the project is broken up into two primary parts, templates and the generator.  The generator is built on top of [dotnet Template Engine](https://github.com/dotnet/templating), it is a Visual Studio extension a developer will install while the templates will be hosted on a CDN so we can update what is created independntly of the generator.  The generator uses templates to create actual projects, pages and/or features for the developers. 

## Getting Started
Please read the [Getting Started with the UWP Template Community Generator](docs/getting-started.md) page for more detailed information about using the UWP Community Template Generator.

## Features

### Supported Application Types
 * Basic

### Supported Frameworks
 * Basic
 * [MVVM Light](http://www.mvvmlight.net/)

### Supported Pages
Coming soon

### Developer Options
Coming soon

### End User Options
Coming soon

## Feedback and Requests
Please use [GitHub issues](https://github.com/Microsoft/UWPCommunityTemplates/issues) for questions or comments.  If you have specific feature requests or would like to vote on what others are recommending, please go to the [GitHub issues](https://github.com/Microsoft/UWPCommunityTemplates/issues)section as well.  We would love to see what you are thinking.

## Contributing
Do you want to contribute? Here are our [contribution guidelines](contributing.md).

## Principles
 * Principle #1: Generated templates will be kept simple.
 * Principle #2: Generated templates are a starting point, not a completed application.
 * Principle #3: Generated templates once generated, must be able to be compiled and run.
 * Principle #4: Generated templates should work on all device families.
 * Principle #5: Formulas should have comments to aid developers.  This includes links to singup pages for keys, MSDN, blogs and how-to's.  All guidance provide should be validated from either the framework/SDK/library’s creator.
 * Principle #6: All features will be supported for two Windows SDK for Windows 10 release cycles or until another principle supersedes it.
 * Principle #7: Templates released in production will try to adhere to the design language used in the current release of Windows 10.

This project has adopted the code of conduct defined by the [http://contributor-covenant.org/](Contributor Covenant) to clarify expected behavior in our community. 

## Roadmap
Read what we [plan for next iteration](https://github.com/Microsoft/UWPCommunityTemplates/issues?q=is%3Aopen+is%3Aissue+milestone%3A0.5), and feel free to ask questions.

You can add [this feed](https://www.myget.org/F/vsixextensions/vsix/) to your Extensions galleries and you can get the pre-release versions of the UWP Community Templates Visual Studio Extension. 

## License
This code is distributed under the terms and conditions of the [MIT license](license.md). 
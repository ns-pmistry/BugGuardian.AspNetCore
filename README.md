# BugGuardian.AspNetCore
![](https://dbtek.visualstudio.com/_apis/public/build/definitions/31dcc845-6a11-47d7-90a5-1c340cebf0f1/39/badge)

Easily track you ASP.NET Core exceptions on VSTS and TFS
-------------------------------------------------------
**BugGuardian.AspNetCore** is an extension for [*BugGuardian*](https://github.com/n3wt0n/BugGuardian) (a library that allows to easily create a Bug or a Task work item on your *Visual Studio Team Services* account or on your on-premises *Team Foundation Server 2015* in the case your application throws an Unhandled Exception) specifically written to support ASP.NET Core applications. It adds a Middleware to your application to let you automatically intercept all the exceptions.

It supports projects with ASP.NET Core using both .Net Full Framework and Net Core.


###Installation###

The **BugGuardian.AspNetCore** library is available on [NuGet](https://www.nuget.org/packages/DBTek.BugGuardian.AspNetCore).
Just search *BugGuardian.AspNetCore* in the **Package Manager GUI** or run the following command in the **Package Manager Console**:
  
```
Install-Package DBTek.BugGuardian.AspNetCore
```
  
 
###Usage###

Refer to the [project documentation](https://github.com/n3wt0n/BugGuardian.AspNetCore/wiki/Home) to find more information about this library.

Refer to the [BugGuardian project documentation](https://github.com/n3wt0n/BugGuardian/wiki/Home) to find examples about that.


###Support###

If you encounter some issues trying this library, please let me know through the [Issues page](https://github.com/n3wt0n/BugGuardian.AspNetCore/issues) and I'll fix the problem as soon as possible!


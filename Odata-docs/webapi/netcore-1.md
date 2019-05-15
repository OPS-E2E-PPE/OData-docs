---

title : "14.5 OData Web API 7.0.1 (.NET Core and .NET Classic)"
description: "7.0.1 release notes"

ms.date: 07/18/2018
---
# 14.5 OData Web API 7.0.1 (.NET Core and .NET Classic)

The NuGet packages for ASP.NET Web API OData v7.0.1 are available on the [NuGet gallery](https://www.nuget.org/).

You can install or update the NuGet packages for OData Web API v7.0.1 using the [Package Manager Console](https://docs.nuget.org/docs/start-here/using-the-package-manager-console):

```
PM> Install-Package Microsoft.AspNetCore.OData -Version 7.0.1 
```
or
```
PM> Install-Package Microsoft.AspNet.OData -Version 7.0.1
```

## What’s in this release?

### New Features:

* [ [Web API issue #1488](https://github.com/OData/WebApi/issues/1488) ] Support optional parameters

* [ [Web API PR #1527](https://github.com/OData/WebApi/pull/1527) ] Add UseOData() extension methods

### Improvements and fixes:

* [ [Web API issue #1518](https://github.com/OData/WebApi/issues/1518) ] Fix the Newtonsoft.Json dependency problem in classic version

* [ [Web API issue #1529](https://github.com/OData/WebApi/issues/1529) ] Fix ETag missing on derived Entity Set

* [ [Web API issue #1532](https://github.com/OData/WebApi/issues/1532) ] Fix JSON batch repsonse content type

---

## Questions and feedback

You and your team are warmly welcomed to try out this new version if you are interested in the new features and fixes above. You are also welcomed to contribute your code to [OData Web API repository](https://github.com/OData/WebApi). For any feature request, issue or idea please feel free to reach out to us at 
[GitHub Issues](https://github.com/OData/WebApi/issues). 
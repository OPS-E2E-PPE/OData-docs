---
title: "ODataLib 7.4.0"
description: "ODataLib 7.4.0 release notes"

---

## Changes in ODataLib 7.4.0 Release ##

> [!NOTE]
> ODataLib 7.4.0 has the following beta releases:

### ODataLib 7.4.0.beta

#### Features ##

[[Issue #103](https://github.com/OData/odata.net/issues/103)] OData v4: Deserialize client unknown properties into OData Object Model.

[[Issue #801](https://github.com/OData/odata.net/issues/801)] Support Primitive Type Casts.

[[Issue #988](https://github.com/OData/odata.net/issues/988)] Add support for 4.01 Delta Format

#### Fixed Bugs ##

[[Issue #698](https://github.com/OData/odata.net/issues/698)] DataServiceQuerySingle<T>.GetValueAsync inconsistent with GetValue in support for GET returning 404.

[[Issue #800](https://github.com/OData/odata.net/issues/800)] Need for parsing Open types using OData.NET v7.X.

[[Issue #949](https://github.com/OData/odata.net/issues/949)] ODataUriExtensions.BuildUri ignores $skiptoken.

[[PR #961](https://github.com/OData/odata.net/pull/961)] Add support for ENUM keys.

[[Issue #965](https://github.com/OData/odata.net/issues/965)] Parsing encoded character with special meaning in ODataJsonLightContextUriParser.


### ODataLib 7.4.0.beta2

#### Features ##

[[Issue #226](https://github.com/OData/odata.net/issues/226)] Support a json serialization for $batch.

[[Issue #866](https://github.com/OData/odata.net/issues/866)] "Microsoft.OData.Client" support for ,NET Core.

#### Fixed Bugs ##

[[PR #980](https://github.com/OData/odata.net/pull/980)] Support enum to string comparision.

[[PR #995](https://github.com/OData/odata.net/pull/995)] Use ConcurrentDictionary in all platforms to make client edm model thread safe.

[[Issue #1008](https://github.com/OData/odata.net/issues/1008) & [Issue #1009](https://github.com/OData/odata.net/issues/1009)] Fix property validation issue.

[[Issue #1101](https://github.com/OData/odata.net/pull/1011)] Microsoft.OData.Client 7.0+ needs to support GetValue like the older OData Client.


### ODataLib 7.4.0.beta3

#### Features ##

[[PR #1020](https://github.com/OData/odata.net/pull/1020)] DependsOn Ids for Multipart/Mixed Batch

#### Fixed Bugs ##

[[Issue #1022](https://github.com/OData/odata.net/issues/1022)] Calculate correct context URI with Operation path segment.

[[Issue #1193](https://github.com/OData/WebApi/issues/1193)] Add the extension function back to derived class.

[[Issue #1028](https://github.com/OData/odata.net/issues/1028)] Add the enum member expression into validation and don't return the error message.


### ODataLib 7.4.0 RTM

#### Features ##

[[Issue #1037](https://github.com/OData/odata.net/issues/1037)] Support reading/writing OData 4.01 compatible JSON payloads.

---

This release delivers OData core libraries including ODataLib, EdmLib, Spatial and Client.
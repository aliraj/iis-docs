---
title: ConfigurationMessage.Severity Property  (Microsoft.Web.Media.TransformManager)
TOCTitle: Severity Property
ms:assetid: P:Microsoft.Web.Media.TransformManager.ConfigurationMessage.Severity
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/microsoft.web.media.transformmanager.configurationmessage.severity(v=VS.90)
ms:contentKeyID: 35520952
ms.date: 06/14/2012
mtps_version: v=VS.90
f1_keywords:
- Microsoft.Web.Media.TransformManager.ConfigurationMessage.Severity
- Microsoft.Web.Media.TransformManager.ConfigurationMessage.get_Severity
- Microsoft.Web.Media.TransformManager.ConfigurationMessage.set_Severity
dev_langs:
- CSharp
- JScript
- VB
- FSharp
- c++
api_location:
- Microsoft.Web.Media.TransformManager.Common.dll
api_name:
- Microsoft.Web.Media.TransformManager.ConfigurationMessage.get_Severity
- Microsoft.Web.Media.TransformManager.ConfigurationMessage.set_Severity
- Microsoft.Web.Media.TransformManager.ConfigurationMessage.Severity
api_type:
- Managed
topic_type:
- apiref
- kbSyntax
product_family_name: VS
ROBOTS: INDEX,FOLLOW
---

# Severity Property

Gets or set the error severity.

**Namespace:**  [Microsoft.Web.Media.TransformManager](microsoft-web-media-transformmanager-namespace.md)  
**Assembly:**  Microsoft.Web.Media.TransformManager.Common (in Microsoft.Web.Media.TransformManager.Common.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Severity As ConfigurationMessageSeverity
    Get
    Set
'Usage

  Dim instance As ConfigurationMessage
Dim value As ConfigurationMessageSeverity

value = instance.Severity

instance.Severity = value
```

``` csharp
[DataMemberAttribute]
public ConfigurationMessageSeverity Severity { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property ConfigurationMessageSeverity Severity {
    ConfigurationMessageSeverity get ();
    void set (ConfigurationMessageSeverity value);
}
```

``` fsharp
[<DataMemberAttribute>]
member Severity : ConfigurationMessageSeverity with get, set
```

``` jscript
  function get Severity () : ConfigurationMessageSeverity
function set Severity (value : ConfigurationMessageSeverity)
```

#### Property Value

Type: [Microsoft.Web.Media.TransformManager. . :: . .ConfigurationMessageSeverity](configurationmessageseverity-enumeration-microsoft-web-media-transformmanager.md)  
The error severity.  

## See Also

#### Reference

[ConfigurationMessage Class](configurationmessage-class-microsoft-web-media-transformmanager.md)

[Microsoft.Web.Media.TransformManager Namespace](microsoft-web-media-transformmanager-namespace.md)

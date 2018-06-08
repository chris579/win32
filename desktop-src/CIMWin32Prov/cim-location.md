---
Description: The CIM\_Location class represents the position and address of a physical element.
audience: developer
author: REDMOND\\markl
manager: REDMOND\\markl
ms.assetid: c1ec467c-a338-4beb-a8fe-1ebc5b05c754
ms.prod: windows-server-dev
ms.technology:
- cimwin32
- windows-management-instrumentation
ms.tgt_platform: multiple
title: CIM\_Location class
ms.author: windowssdkdev
ms.topic: article
ms.date: 05/31/2018
---

# CIM\_Location class

The **CIM\_Location** class represents the position and address of a physical element.

> \[!Important\]  
> The DMTF (Distributed Management Task Force) CIM (Common Information Model) classes are the parent classes upon which WMI classes are built. WMI currently supports only the [CIM 2.x version schemas](Http://Go.Microsoft.Com/FWLink/p/?LinkID=309367).

 

The following syntax is simplified from Managed Object Format (MOF) code and includes all inherited properties. Properties are listed in alphabetic order, not MOF order.

## Syntax

``` syntax
[Abstract, UUID("{FAF76B67-798C-11D2-AAD1-006008C78BC7}"), AMENDMENT]
class CIM_Location
{
  string Address;
  string Name;
  string PhysicalPosition;
};
```

## Members

The **CIM\_Location** class has these types of members:

-   [Properties](#properties)

### Properties

The **CIM\_Location** class has these properties.

<dl> <dt>

**Address**
</dt> <dd> <dl> <dt>

Data type: **string**
</dt> <dt>

Access type: Read-only
</dt> <dt>

Qualifiers: [**MaxLen**](https://msdn.microsoft.com/library/aa393650) (1024)
</dt> </dl>

Free-form string that indicates a street or other type of address for the physical element's location.

</dd> <dt>

**Name**
</dt> <dd> <dl> <dt>

Data type: **string**
</dt> <dt>

Access type: Read-only
</dt> <dt>

Qualifiers: [**Key**](https://msdn.microsoft.com/library/aa392157), [**MaxLen**](https://msdn.microsoft.com/library/aa393650) (256)
</dt> </dl>

Free-form string that defines a label for the location and is part of the key for the object.

</dd> <dt>

**PhysicalPosition**
</dt> <dd> <dl> <dt>

Data type: **string**
</dt> <dt>

Access type: Read-only
</dt> <dt>

Qualifiers: [**Key**](https://msdn.microsoft.com/library/aa392157), [**MaxLen**](https://msdn.microsoft.com/library/aa393650) (256)
</dt> </dl>

Free-form string that indicates the placement of a physical element. It can specify slot information on a hosting board, mounting site in a cabinet, or latitude and longitude information. It is part of the key of the **CIM\_Location** object.

</dd> </dl>

## Remarks

WMI does not implement this class. For classes derived from **CIM\_Location**, see [Win32 Classes](win32-provider.md).

This documentation is derived from the CIM class descriptions published by the DMTF. Microsoft may have made changes to correct minor errors, conform to Microsoft SDK documentation standards, or provide more information.

## Requirements



|                                     |                                                                                         |
|-------------------------------------|-----------------------------------------------------------------------------------------|
| Minimum supported client<br/> | Windows Vista<br/>                                                                |
| Minimum supported server<br/> | Windows Server 2008<br/>                                                          |
| Namespace<br/>                | Root\\CIMV2<br/>                                                                  |
| MOF<br/>                      | <dl> <dt>CIMWin32.mof</dt> </dl> |
| DLL<br/>                      | <dl> <dt>CIMWin32.dll</dt> </dl> |



 

 




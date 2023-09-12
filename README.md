# WinShellPropertyStore
WinShellPropertyStore is a set of classes for accessing the [Windows Property Store](https://msdn.microsoft.com/en-us/library/windows/desktop/ff728898.aspx) from managed code.

WinShellPropertyStore is part of the [FileMeta](http://www.filemeta.org) initiative because it provides convenient access to metadata on many file formats by utilizing the Windows Shell Property Store.

This project includes master copy of the WinShellPropertyStore CodeBit plus a set of unit tests which may also serve as sample code. 

## Classes
The WinShellPropertyStore CodeBit manifests four managed classes:
* **WinShell.PropertyStore:** Wrapper class for the COM [IPropertyStore](https://msdn.microsoft.com/en-us/library/windows/desktop/bb761474.aspx) interface. Provides methods for opening a PropertyStore on a file, reading, and writing property values. 
* ** WinShell.PropertySystem:** Wrapper class for the COM [IPropertySystem](https://msdn.microsoft.com/en-us/library/windows/desktop/bb761437.aspx) interface. Provides methods for translating between property keys and property names and for retrieving attributes about property keys.
* ** WinShell.PropertyDescription:** Wrapper class for the COM [IPropertyDescription](https://msdn.microsoft.com/en-us/library/windows/desktop/bb761561.aspx) interface. Provides detailed information about a particular property.

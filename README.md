MMS is a utility in OpenVMS that automates the building of software systems. It uses description files (similar to makefiles) to specify the components of the system and their dependencies. MMS reads these files to determine what needs to be built and in what order. 

Makefiles (.MMS extension) in OpenVMS, particularly when using tools like MMS and MMK, utilize macros to define variables and rules for building software. These macros can represent file names, compiler options, or any other text that needs to be reused throughout the makefile

This extension is for Makefile Macro Syntax used for Module Management System for OpenVMS (MMS).

MMS is patterned after the UNIX make utility.  
MMS is part of the OpenVMS DECSet. 

Read more about the purpos an syntax at: 
https://docs.vmssoftware.com/vsi-decset-for-openvms-guide-to-the-module-management-system/

## Features

- .MMS file syntax highlighting
- Autocomplete for common lexicals and commands
- Both MMS and MMK compatibility
- Helpful snippets: 
  
Snippet Shortcut      | Purpose
--------------------- | -------------
'.IF'                 | Generate an IF-THEN-ELSE-ENDIF statement block
'.IFDEF'              | Genetate an IFDEF-THEN-ELSE-ENDIF statement block


Example:

<p align="center">
  <img src="https://raw.githubusercontent.com/tigermeeting/vms-mms-vsc-extension/main/images/sample.png">
</p>

## Requirements

None.

## Extension Settings

None.

## Known Issues

None.

## Release Notes

### 1.0.0

Initial release.

---
Send bugs to Zoltan Arpadffy <zoli@tigermeeting.app>

**Enjoy!**

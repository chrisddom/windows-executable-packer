A utility for packing windows executables

# [Standalone Application 1.0](http://code.google.com/p/windows-executable-packer/downloads/detail?name=portable_executable.zip&can=2&q=) #
[Documentation](http://code.google.com/p/file-activity-timeline/downloads/detail?name=Help.pdf&can=2&q=) [Sourcecode](http://code.google.com/p/windows-executable-packer/downloads/detail?name=source.zip&can=2&q=)

## This tool works by ##
  * Detecting whether the executable is .NET or Native
  * If Native, Running  BundleIT (DLLPackager by ReWolf.pl)
  * If .NET, displays GUI for ILMerge

This approach is not perfect. Some AV programs will detect packed executables as suspicious, and it isn’t possible to support the totality of executables. A better approach may be the use of virtual machines, as used by BoxedApp.


## Tools used ##
  * ReWolf DLL Packager 1.01 - http://code.google.com/p/dllpackager/ - GPL 3
  * ILMerge 2.12.0803 - http://research.microsoft.com/en-us/people/mbarnett/ilmerge.aspx - Commercial reuse allowed but restricted (http://research.microsoft.com/en-us/people/mbarnett/ilmerge-license.aspx)
  * Dependancy Walker 2.2 - http://www.dependencywalker.com/ - Freeware

This tool requires the Microsoft C++ distributable and .NET framework (see help for details).

![http://windows-executable-packer.googlecode.com/files/screenshot.png](http://windows-executable-packer.googlecode.com/files/screenshot.png)
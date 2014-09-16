# Remote Mapper with CommandFusion iViewer
This is a sample project on how to easily integrate the [Remote Mapper]() application by LLSoft with [CommandFusion iViewer](http://www.commandfusion.com/software/iviewer).
See the [Remote Mapper User Guide](http://www.llsoft.ca/doc/remotemapper/index.html) for more detailed information.

## Usage
Simply download the zip archive and unzip, then open the .gui file in [CommandFusion guiDesigner](http://www.commandfusion.com/software/guidesigner) to see how it works.

## Notes
1. The [Interlock script](http://www.commandfusion.com/wiki2/software/modules-and-examples/interlocking) is used to simply interlock the two polling button states.
1. There is a HTTP Client system that handles all communication and feedback processing with Remote Mapper.
1. By default it will poll Remote Mapper every second. Polling is handled by a [Page Timer](http://www.commandfusion.com/wiki2/software/gui-designer/timers) attached to the startup portrait page.
About
=====

heaper is an Immunity Debugger plugin that is designed to help analyse heap structures under the windows environment. Often, exploitation of windows heap overflows and other vulnerabilities associated with the heap are very complex due to the dynamic nature of the heap manager.

With heaper, you can quickly visualize heap data structures, hook important heap api and determine possible exploitation paths. It is designed for analysts looking to determine the heap layout in a target process by helping to guide the analyst into controling important input into the application.

Currently there is full support for Windows XP. In the near future it will supoirt Windows 7 and 8 heap managers.

Setup
=====

Copy heaper.py into your immunity debugger pycommands directory typically: 'C:\Program Files\Immunity Inc\Immunity Debugger\PyCommands\'.

Usage
=====

simply start heaper by executing '!heaper' in Immunity Debuggers command window.

Screenshot
==========

![heap usage](https://github.com/mrmee/heaper/raw/master/heaper_usage.png "heaper usage")
![heaper hooking RtlAllocateHeap](https://github.com/mrmee/heaper/raw/master/heaper_example.png "heaper hooking RtlAllocateHeap")

License
=======

'heaper' is available under the GPLv3 license, please see the included file gpl-3.0.txt for details.
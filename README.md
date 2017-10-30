# CroweTest

This file contains two solutions:
HelloWorldAPISolution and HelloWorldConsole

Both are written and tested in a VS 2015, Windows 7 environment.

To run the application:
1. Open HelloWorldAPISolution and HelloWorldConsole separately in a Visual Studio environment.
2. Debug/run HelloWorldAPISolution.
3. In the browser window that appears, add /api/helloworld to the url and hit enter.
   The resulting 'Hello World' should appear in a generic XML formatted display in the browser for
   Chrome or Firefox and likely a .json frame if tested in Internet Explorer.
4. While this application is still running, run/debug HelloWorldConsole.
   This should pull 'Hello World' from the running API and display it in a console window.

HelloWorldAPISolution should open using port 58337. If this is the case, then the Client.BaseAddress
value in HelloWorldConsole (Program.cs line 65) will need to be updated to reflect the correct port number.

To save space for email purposes, the packages folder was not included in the zip folder. This folder
should auto-populate from NuGet when the solutions are first run.

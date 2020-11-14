GuiliteExamples is capturing the users logged in name in the script sync_build.bat and sending to external site. Looks very malicious, because tehere is no reason to capture the user name and send it via curl.exe to an external site. 

What called my attention is the inclusion of curl.exe in each sub directory. Why would you have to go to an external site to compile an example.

Users should also be very suspicious of exec on GuiLiteSamples root directory where an exec GuiLiteToolkit.exe is located whithout much (any) documentation.

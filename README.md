OutlookPersistence
==================

This uses a specified email address and subject in Outlook to trigger a Cobalt Strike session. The macro creates a VBScript file in a hidden directory that silently download and executes a powershell script from the c2's webserver that parses the default inbox for the specified email address and subject. The script runs in the background all the time and is re-executed on startup.


THIS IS NO WHERE NEAR COMPLETETION
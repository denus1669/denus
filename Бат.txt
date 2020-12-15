@echo off
wmic COMPUTERSYSTEM get Name
wmic COMPUTERSYSTEM get domain
wmic COMPUTERSYSTEM get Manufacturer
wmic COMPUTERSYSTEM get Model
wmic COMPUTERSYSTEM get TotalPhysicalMemory
wmic computersystem get numberofprocessors
WMIC CPU Get Name
WMIC CPU Get currentclockspeed
WMIC CPU Get numberoflogicalprocessors
WMIC Path Win32_VideoController get AdapterRAM
WMIC Path Win32_VideoController get Name
WMIC Path Win32_VideoController get currenthorizontalresolution
WMIC Path Win32_VideoController get currentverticalresolution
WMIC memorychip get capacity 
WMIC sounddev get Name
wmic OS get Version
wmic OS get CSDVersion
wmic OS get ServicePackMajorVersion
wmic OS get RegisteredUser
wmic CSPRODUCT get IdentifyingNumber
wmic CSPRODUCT get UUID
wmic OS get OSLanguage
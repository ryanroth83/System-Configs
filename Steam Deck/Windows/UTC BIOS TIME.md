1. Open regedit.

2. Navigate to the following key: HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\TimeZoneInformation

3. Right-click in the white area and select New —> DWORD (32-bit Value)

4. Name the key RealTimeIsUniversal.

5. Double-click on it and set its value to 1.


-OR-

Open Command Prompt as Administrator and run:

‘reg ADD HKLM\System\CurrentControlSet\Control\TimeZoneInformation /t REG_DWORD /v RealTimeIsUniversal /d 1’
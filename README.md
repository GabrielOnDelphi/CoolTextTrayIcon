# CoolTextTrayIcon  

*Description*  
 Minimize your app to the notification area (aka "tray icon") or to the task bar (standard) with only two commands:
  * procedure TCoolTrayIcon.PutIconOnlyInTask;
  * procedure TCoolTrayIcon.PutIconOnlyInTray;

__________

*Improvements*  
This version includes the following improvements:  
 * Added compatibility with Delphi 10, 11, 12 
    * Removed all Delphi 6 (or older) crap  
    * Removed the .inc file
    * Added proper package using $(Auto) suffix. Now one single DPK file works with all modern Delphi editions.  
 * Safer code (using FreeAndNil for example)  
 * Since the code is stable, the debug info was removed  
 * Reformatted code. the code was formatted for small monitors.  
 * Added 2 more methods:    
         procedure TCoolTrayIcon.PutIconOnlyInTask;   
         procedure TCoolTrayIcon.PutIconOnlyInTray;   
   Now, you don't need to write any other single line of code (except the two above) to use the library.   

*Road map*  
  I will try to make the code 64-bit compatible one day.  
  Star it to encourage updates.  

*Source*  
  This is a clone of https://github.com/coolshou/CoolTrayIcon.  
  Original code included into the package (for reference).  



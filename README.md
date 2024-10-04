# CoolTextTrayIcon
 Minimize your app to the notification area (aka "tray icon") or to the task bar (standard) with only two commands:
  * procedure TCoolTrayIcon.PutIconOnlyInTask;
  * procedure TCoolTrayIcon.PutIconOnlyInTray;

__________


*Improvements*
This version includes the following improvements:  
 * removed all Delphi 6 (or older) crap  
 * removed the inc file  
 * safer code (using FreeAndNil for example)  
 * since this is a 3rdparty lib, the debug info was removed  
 * added proper package using $(Auto) suffix. Now one single DPK file works with all modern Delphi editions.  
 * reformatted ocde. the code was formatted for small monitors.  
 * added 2 more methods:    
         procedure TCoolTrayIcon.PutIconOnlyInTask;   
         procedure TCoolTrayIcon.PutIconOnlyInTray;   
   Now, you don't need to write any other single line of code (except the two above) to use the library.   

*Road map:*  
  I will try to make the code 64-bit compatible one day.  

*Source*  
This is a clone of https://github.com/coolshou/CoolTrayIcon  
Original code included into the package (for reference).  



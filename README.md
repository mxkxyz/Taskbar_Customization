# Taskbar_Customization using CMD terminal          BY.NEWKXYZ            
                # Taskbar_Customization using CMD terminal

To CUSTOMIZE youre TASKBAR/WINDOWS THEME via CMD terminal, in this case,
MAKE your TASKBAR / windows scheme transparent and black.
---------------------------------------------------------------------------
---------------------------------------------------------------------------


  ##  1: Customize THEME with CMD code               
                        ##  1: Customize THEME with CMD code  
 Open CMD TERMINAL/Search CMD 
                             OR...
                                  (Press `Win + R` , type CMD, hit enter)

  ENTER THESE commands in CMD:                 [ copy paste into You're terminal ] 
  ----------------------------------------------------------------------------------------------------------------------------
    
    reg add HKCU\Software\Microsoft\Windows\CurrentVersion\Themes\Personalize /v EnableTransparency /t REG_DWORD /d 1 /f

    taskkill /f /im explorer.exe && start explorer.exe

  
   ##  This next part of code will Make the Taskbar Black:

  
    reg add HKCU\Software\Microsoft\Windows\CurrentVersion\Themes\Personalize /v AppsUseLightTheme /t REG_DWORD /d 0 /f
    reg add HKCU\Software\Microsoft\Windows\CurrentVersion\Themes\Personalize /v SystemUsesLightTheme /t REG_DWORD /d 0 /f
    taskkill /f /im explorer.exe && start explorer.exe


  ##  This part of code will Enable transparency:


    reg add HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Advanced /v UseOLEDTaskbarTransparency /t REG_DWORD /d 1 /f
    taskkill /f /im explorer.exe && start explorer.exe

          NEWKXYZ          // kxyznew@gmail.com           
        N0t5uR3C$AW        // notsureCsaw@gmail.com 
           
                                     

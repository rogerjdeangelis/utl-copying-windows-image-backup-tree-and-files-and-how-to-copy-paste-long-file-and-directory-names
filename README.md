# utl-copying-windows-image-backup-tree-and-files-and-how-to-copy-paste-long-file-and-directory-names
Copying windows image backup tree and files and how to copy paste long file and directory names

    Copying windows image backup tree and files and how to copy paste long file and directory names                                     
                                                                                                                                        
    Win 7 Professional 64bit                                                                                                            
                                                                                                                                        
    github                                                                                                                              
    https://tinyurl.com/y6qgmhce                                                                                                        
    https://github.com/rogerjdeangelis/utl-copying-windows-image-backup-tree-and-files-and-how-to-copy-paste-long-file-and-directory-nam
                                                                                                                                        
    I needed to make a copy of a windows backup image directory tree and files from disk e to disk g                                    
                                                                                                                                        
    I could not get copy, xcopy or powershell to work                                                                                   
                                                                                                                                        
         1. Copy directory or filename to window paste buffer                                                                           
                                                                                                                                        
             a. right click on directory or filename                                                                                    
             b. select rename                                                                                                           
             c. cntl c (to copy name to paste buffer)                                                                                   
                                                                                                                                        
         2. Open command window in administrator mode (right click on dos icon and select admon mode)                                   
            ROBOCOPY e:\WindowsImageBackupe6420Jan g:\WindowsImageBackupe6420Jan /E /B /Z                                               
                                                                                                                                        
    Keep a copy og you system disks ar a relative or friend house.                                                                      
                                                                                                                                        
    This command did work                                                                                                               
                                                                                                                                        
    You get a nice log from robocopy                                                                                                    
                                                                                                                                        
                                                                                                                                        
    C:\Windows\system32>ROBOCOPY e:\WindowsImageBackupe6420Jan g:\WindowsImageBackup                                                    
    e6420Jan /E /B /Z                                                                                                                   
                                                                                                                                        
    -------------------------------------------------------------------------------                                                     
       ROBOCOPY     ::     Robust File Copy for Windows                                                                                 
                                                                                                                                        
    -------------------------------------------------------------------------------                                                     
                                                                                                                                        
      Started : Sun Mar 03 05:23:13 2019                                                                                                
                                                                                                                                        
       Source : e:\WindowsImageBackupe6420Jan\                                                                                          
         Dest : g:\WindowsImageBackupe6420Jan\                                                                                          
                                                                                                                                        
        Files : *.*                                                                                                                     
                                                                                                                                        
      Options : *.* /S /E /COPY:DAT /Z /R:1000000 /W:30                                                                                 
                                                                                                                                        
    ------------------------------------------------------------------------------                                                      
                                                                                                                                        
              New Dir          0    e:\WindowsImageBackupe6420Jan\                                                                      
                                                                                                                                        
              New Dir          1    e:\WindowsImageBackupe6420Jan\e6420\                                                                
    100%        New File                  16        MediaId                                                                             
                                                                                                                                        
              New Dir         12    e:\WindowsImageBackupe6420Jan\e6420\Backup 2019-01-03 204229\                                       
                New File              70.6 g        4cbef1c6-5a5c-11e6-90ea-806e6f6e                                                    
                                                                                                                                        
    100%  hd                                                                                                                            
    100%        New File                 668        BackupSpecs.xml                                                                     
                New File                1078        dc745737-7e88-4fc4-b4eb-be75345c                                                    
    100%  additionalFilesc3b9f3c7-5e52-4d5e-8b20-19adc95a34c7.xml                                                                       
                New File               13282        dc745737-7e88-4fc4-b4eb-be75345c                                                    
    100%  components.xml                                                                                                                
                New File                6542        dc745737-7e88-4fc4-b4eb-be75345c                                                    
    100%  registryExcludes.xml                                                                                                          
                New File                9536        dc745737-7e88-4fc4-b4eb-be75345c                                                    
    100%  riter4dc3bdd4-ab48-4d07-adb0-3bee2926fd7f.xml                                                                                 
                New File                1488        dc745737-7e88-4fc4-b4eb-be75345c                                                    
    100%  writer542da469-d3e1-473c-9f4f-7847f01fc64f.xml                                                                                
                New File                1484        dc745737-7e88-4fc4-b4eb-be75345c                                                    
    100%  writera6ad56c2-b509-4e6c-bb19-49d8f43532f0.xml                                                                                
                New File                3844        dc745737-7e88-4fc4-b4eb-be75345c                                                    
    100%  writerafbab4a2-367d-4d15-a586-71dbb18f8485.xml                                                                                
                New File                6196        dc745737-7e88-4fc4-b4eb-be75345c                                                    
    100%  writerbe000cbe-11fe-4426-9c58-531aa6355fc4.xml                                                                                
                New File                7110        dc745737-7e88-4fc4-b4eb-be75345c                                                    
    100%  writercd3f2362-8bef-46c7-9181-d62844cdc0b2.xml                                                                                
                New File               4.0 m        dc745737-7e88-4fc4-b4eb-be75345c                                                    
    100%  writere8132975-6f93-4464-a53e-1050253ae220.xml                                                                                
                                                                                                                                        
              New Dir          2    e:\WindowsImageBackupe6420Jan\e6420\Catalog\                                                        
    100%        New File               17644        BackupGlobalCatalog                                                                 
    100%        New File               18560        GlobalCatalog                                                                       
                                                                                                                                        
              New Dir          9    e:\WindowsImageBackupe6420Jan\e6420\SPPMetadataCache\                                               
                New File              104096        {019f6a8c-d666-4606-aeeb-9d850eb                                                    
    100%                                                                                                                                
                New File               96024        {3ef8df1d-8d77-4a55-ae51-5084caf                                                    
    100%                                                                                                                                
                New File              101992        {403a138f-18fe-449f-8f99-e74b85a                                                    
    100%                                                                                                                                
                New File               68008        {730c456a-df28-4111-8c2a-0ed783b                                                    
    100%                                                                                                                                
                New File               94800        {7baf6646-c71d-4f1e-8ad5-e052177                                                    
    100%                                                                                                                                
                New File              101880        {9cc18c9d-4973-4c99-8f7f-03d5dda                                                    
    100%                                                                                                                                
                New File              101880        {b226ade4-3138-4d96-abb7-429accb                                                    
    100%                                                                                                                                
                New File               65336        {d7b67476-3a87-40d6-8ede-6021186                                                    
    100%                                                                                                                                
                New File              102096        {dc745737-7e88-4fc4-b4eb-be75345                                                    
    100%                                                                                                                                
                                                                                                                                        
    ------------------------------------------------------------------------------                                                      
                                                                                                                                        
                   Total    Copied   Skipped  Mismatch    FAILED    Extras                                                              
        Dirs :         5         5         0         0         0         0                                                              
       Files :        24        24         0         0         0         0                                                              
       Bytes :  70.633 g  70.633 g         0         0         0         0                                                              
       Times :   0:19:06   0:19:05                       0:00:00   0:00:00                                                              
                                                                                                                                        
                                                                                                                                        
       Speed :            66182635 Bytes/sec.                                                                                           
       Speed :            3787.000 MegaBytes/min.                                                                                       
                                                                                                                                        
       Ended : Sun Mar 03 05:42:19 2019                                                                                                 
                                                                                                                                        
    C:\Windows\system32>                                                                                                                
                                                                                                                                        
                                                                                                                                        

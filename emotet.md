## Emotet


    digsig_publisher:"Evaila IT Ltd"

<br>

    process_name:wmiprvse.exe modload:c:\windows\temp\* digsig_result_modload:Unsigned

<br>

    is_executable_image:"true"  digsig_result:"Unsigned" observed_filename:c:\programdata\

<br>

    is_executable_image:"true"  digsig_result:"Unsigned" observed_filename:\appdata\roaming\

<br>

    is_executable_image:"true" digsig_result:Unsigned observed_filename:\AppData\Roaming\Microsoft\

<br>

    is_executable_image:"true"  digsig_result:"Unsigned" observed_filename:C:\Windows\SysWOW64\

<br>

    is_executable_image:"true"  digsig_result:"Unsigned" observed_filename:C:\Windows\system32\

<br>

    is_executable_image:"true"  digsig_result:"Unsigned" observed_filename:C:\Windows\

<br>

    is_executable_image:"true"  digsig_result:"Unsigned" observed_filename:C:\Windows\temp

<br>

    -parent_name:perccli64.exe -parent_name:kix32.exe -parent_name:activrelay.exe digsig_result_parent:"Unsigned"

<br>

    digsig_result_parent:"Unsigned" digsig_result_process:"Unsigned" digsig_result_child:"Unsigned"

<br>

    digsig_result:"Unsigned" filemod:c:\windows\syswow64\*

<br>

    (modload:"c:\windows\system32\wow64cpu.dll") digsig_result_process:"Unsigned" digsig_result_parent:"Unsigned"

<br>

    digsig_result:"Unsigned" filemod:c:\programdata\*

<br>

    digsig_result_process:Unsigned parent_name:services.exe

<br>

    parent_name:taskeng.exe digsig_result_process:Unsigned -process_name:currentdefsloader.exe -process_name:sqltasks.exe

<br>

    (company_name:"Fatal Enterprice" OR company_name:"FastSpring Past" OR company_name:"Qualifacts Systems Plane" OR company_name:"WehwGWE.hWRGW" OR company_name:"Microsoft Co" OR company_name:"WMI" OR company_name:"SimVentions Hole" OR company_name:"Microsoft Corporatio" OR company_name:"Win Interactive LLC* Right" OR company_name:"PERCo-SC-610T/L" OR company_name:"Hekuriporuc Ltd." OR company_name:"Hikaham Ltd." OR company_name:"С Corporation" OR company_name:"Roni Enterprice" OR company_name:"Conoha.jp" OR company_name:"P.A.C. Nichols" OR company_name:"Server Service Core DLL" OR company_name:"NTLM Shared Functionality" OR company_name:"ImTOO Software Studio" OR company_name:"TeamViewer GmbH" OR company_name:"BST" OR company_name:"America Online, Inc.")
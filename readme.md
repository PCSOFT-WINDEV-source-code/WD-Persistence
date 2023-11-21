  
<span style="font-family:Arial sans-serif;font-size:16px;">WD Persistence</span>

  
<span style="font-family:Arial sans-serif;font-size:14px;">This example presents the use of InitParameter, LoadParameter and SaveParameter.</span>

<span style="font-family:Arial sans-serif;font-size:14px;">These functions are used to configure the backup of controls, variables and other parameters.</span>

<span style="font-family:Arial sans-serif;font-size:14px;">This example is divided into three parts:</span>

<span style="font-family:Arial sans-serif;font-size:14px;"> - The configuration</span>

<span style="font-family:Arial sans-serif;font-size:14px;"> - The manual management of variables (SaveParameter and LoadParameter)</span>

<span style="font-family:Arial sans-serif;font-size:14px;"> - The optimization</span>

<span style="font-family:Arial sans-serif;font-size:14px;">1°) Configuration </span>

  
<span style="font-family:Arial sans-serif;font-size:14px;"> The configuration window enables you to modify the location of the backup of parameters (registry, INI file, XML file) as well as its path (registry key or file path).</span>

<span style="font-family:Arial sans-serif;font-size:14px;">2°) Manual management of the variables</span>

<span style="font-family:Arial sans-serif;font-size:14px;"> The manual management enables you to save the content of the variables via SaveParameter and to restore them via LoadParameter. Each parameter is identified by a name. These values are saved at the location defined in the configuration window.</span>

<span style="font-family:Arial sans-serif;font-size:14px;">3°) The optimization</span>

<span style="font-family:Arial sans-serif;font-size:14px;"> This window explains how to optimize your code to avoid the slowness caused when the saved values are restored. Indeed, when restoring the value of a control, its modification code is run. If you have long processes (queries with parameters for instance), this window shows you how to speed up the loading of the window.</span>

  
  
<span style="font-family:Arial sans-serif;font-size:14px;">( \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_ ° \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_ )</span>

  
<span style="text-decoration:underline;font-family:Arial sans-serif;font-size:10px;">Conditions of Use.</span>

<span style="font-family:Arial sans-serif;font-size:10px;">This program is supplied for training purposes.</span>

<span style="font-family:Arial sans-serif;font-size:10px;">The use of this program is the responsibility of the user. </span>

<span style="font-family:Arial sans-serif;font-size:10px;">PC SOFT will not be liable for damage or loss of any nature whatsoever, including data loss, corruption or deterioration as a result of using this program.</span>

<span style="font-family:Arial sans-serif;font-size:10px;">Any person owning a WINDEV 28 US license is authorized to use and/or modify the program and to use it in their own applications. </span>

<span style="font-family:Arial sans-serif;font-size:10px;">In this case all references to PC SOFT and/or to WinDev or WebDev must be removed.</span>

<span style="font-family:Arial sans-serif;font-size:10px;">You may not distribute or sell this example program without substantial modification or include it in another application unless the application is very large.</span>

  
<span style="font-family:Arial sans-serif;font-size:10px;">No Hot Line Support is available for this program.</span>

  
<span style="font-family:Arial sans-serif;font-size:10px;">CAUTION: Many users may have modified this program. </span>

<span style="font-family:Arial sans-serif;font-size:10px;">Make sure that you are working with the original version of this program.</span>

  
  
  
  
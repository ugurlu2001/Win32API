[<img src="../../images/home.png"> Home ](https://github.com/VFPX/Win32API)  

## Function name : keybd_event
Group: Keyboard Input - Library: user32    
***  


#### Synthesizes a keystroke.

***  


## Code examples:
[How to activate Windows Calculator](../../samples/sample_026.md)  

## Declaration:
```foxpro  
VOID keybd_event(
	BYTE bVk,
	BYTE bScan,
	DWORD dwFlags,
	PTR dwExtraInfo
);  
```  
***  


## FoxPro declaration:
```foxpro  
DECLARE keybd_event IN user32;
	SHORT bVk,;
	SHORT bScan,;
	INTEGER dwFlags,;
	INTEGER dwExtraInfo  
```  
***  


## Parameters:
bVk
[in] Specifies a virtual-key code. The code must be a value in the range 1 to 254. For a complete list, see Virtual-Key Codes. 

bScan
This parameter is not used. 

dwFlags
[in] Specifies various aspects of function operation.

dwExtraInfo
[in] Specifies an additional value associated with the key stroke.   
***  


## Return value:
This function has no return value.  
***  


## Comments:
The system can use such a synthesized keystroke to generate a WM_KEYUP or WM_KEYDOWN message. The keyboard driver"s interrupt handler calls the keybd_event function.  
  
List of <a href="http://msdn.microsoft.com/library/default.asp?url=/library/en-us/winui/winui/WindowsUserInterface/UserInput/VirtualKeyCodes.asp">Virtual Key Codes</a>.  
  
***  


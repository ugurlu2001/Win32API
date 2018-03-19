
## Function name : RegisterHotKey
Group: Keyboard Input - Library: user32    
***  


#### The RegisterHotKey function defines a system-wide hot key. 
***  


## Code examples:
[How to block the ALT+TAB shortcut (WinXP)](../../samples/sample_432.md)  
[How to block the PrintScreen key](../../samples/sample_489.md)  

## Declaration:
```foxpro  
BOOL RegisterHotKey(
	HWND hWnd,
	int id,
	UINT fsModifiers,
	UINT vk
);  
```  
***  


## FoxPro declaration:
```foxpro  
DECLARE INTEGER RegisterHotKey IN user32;
	INTEGER hWnd,;
	INTEGER id,;
	INTEGER fsModifiers,;
	INTEGER vk
  
```  
***  


## Parameters:
hWnd
[in] Handle to the window that will receive WM_HOTKEY messages generated by the hot key. 

id
[in] Specifies the identifier of the hot key. No other hot key in the calling thread should have the same identifier.

fsModifiers
[in] Specifies keys that must be pressed in combination with the key specified by the uVirtKey parameter in order to generate the WM_HOTKEY message.

vk
[in] Specifies the virtual-key code of the hot key.  
***  


## Return value:
If the function succeeds, the return value is nonzero.  
***  


## Comments:
See also UnregisterHotKey function.  
  
***  

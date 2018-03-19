
## Function name : GetSaveFileName
Group: Common Dialog Box - Library: comdlg32    
***  


#### The GetSaveFileName function creates a Save dialog box that lets the user specify the drive, directory, and name of a file to save.
***  


## Code examples:
[Creating the Save dialog box to specify the drive, directory, and name of a file to save](../../samples/sample_265.md)  

## Declaration:
```foxpro  
BOOL GetSaveFileName(
  LPOPENFILENAME lpofn   // initialization data
);  
```  
***  


## FoxPro declaration:
```foxpro  
DECLARE INTEGER GetSaveFileName IN comdlg32;
	STRING @lpofn  
```  
***  


## Parameters:
lpofn 
[in/out] Pointer to an OPENFILENAME structure that contains information used to initialize the dialog box.   
***  


## Return value:
If the user specifies a file name and clicks the OK button and the function is successful, the return value is nonzero.   
***  

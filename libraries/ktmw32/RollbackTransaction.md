[<img src="../../images/home.png"> Home ](https://github.com/VFPX/Win32API)  

## Function name : RollbackTransaction
Group: Kernel Transaction Manager - Library: ktmw32    
***  


#### Requests that the specified transaction be rolled back. This function is synchronous.
***  


## Code examples:
[Copying files as a transacted operation (Vista)](../../samples/sample_540.md)  

## Declaration:
```foxpro  
BOOL WINAPI RollbackTransaction(
  __in  HANDLE TransactionHandle
);
  
```  
***  


## FoxPro declaration:
```foxpro  
DECLARE INTEGER RollbackTransaction IN KtmW32;
	INTEGER TransactionHandle  
```  
***  


## Parameters:
TransactionHandle 
A handle to the transaction.
  
***  


## Return value:
If the function succeeds, the return value is nonzero.  
***  


## Comments:
Requires Windows Vista.  
  
See also: CreateTransaction, CommitTransaction   
  
***  


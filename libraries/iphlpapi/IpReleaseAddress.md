[<img src="../../images/home.png"> Home ](https://github.com/VFPX/Win32API)  

## Function name : IpReleaseAddress
Group: IP Helper - Library: iphlpapi    
***  


#### The IpReleaseAddress function releases an IP address previously obtained through Dynamic Host Configuration Protocol (DHCP).
***  


## Code examples:
[How to release and renew a lease on an IP address previously obtained through Dynamic Host Configuration Protocol (DHCP)](../../samples/sample_349.md)  

## Declaration:
```foxpro  
DWORD IpReleaseAddress(
	PIP_ADAPTER_INDEX_MAP AdapterInfo
);
  
```  
***  


## FoxPro declaration:
```foxpro  
DECLARE INTEGER IpReleaseAddress IN iphlpapi;
	STRING @ AdapterInfo  
```  
***  


## Parameters:
AdapterInfo 
[in] Pointer to an IP_ADAPTER_INDEX_MAP structure that specifies the adapter associated with the IP address to release.   
***  


## Return value:
If the function succeeds, the return value is NO_ERROR.  
***  


## Comments:
Normally this functionality is achieved through <Strong>IPCONFIG /release</Strong> call.  
  
***  


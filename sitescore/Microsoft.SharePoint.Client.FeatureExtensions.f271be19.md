# FeatureExtensions.ActivateFeature Method  
 Activates a site collection or site scoped feature   

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static void ActivateFeature(Web web, Guid featureID, Boolean sandboxed, Int32 pollingIntervalSeconds)
```
### Parameters
#### web  
&emsp;&emsp;Type: Microsoft.SharePoint.Client.Web  
&emsp;&emsp;Web to be processed - can be root web or sub web  

  

#### featureID  
&emsp;&emsp;Type: System.Guid  
&emsp;&emsp;ID of the feature to activate  

  

#### (optional) sandboxed  
&emsp;&emsp;Type: System.Boolean  
&emsp;&emsp;Set to true if the feature is defined in a sandboxed solution  

  

#### (optional) pollingIntervalSeconds  
&emsp;&emsp;Type: System.Int32  
&emsp;&emsp;The time in seconds between polls for "IsActive"  

  

### Return Value
Type: void  

## Remarks
  
## See also
- [FeatureExtensions](Microsoft.SharePoint.Client.FeatureExtensions.md) 
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md) 
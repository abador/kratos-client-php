# # SettingsFlow

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**active** | **string** | Active, if set, contains the registration method that is being used. It is initially not set. | [optional] 
**expiresAt** | [**\DateTime**](\DateTime.md) | ExpiresAt is the time (UTC) when the flow expires. If the user still wishes to update the setting, a new flow has to be initiated. | 
**id** | **string** |  | 
**identity** | [**\Ory\Kratos\Client\Model\Identity**](Identity.md) |  | 
**issuedAt** | [**\DateTime**](\DateTime.md) | IssuedAt is the time (UTC) when the flow occurred. | 
**messages** | [**\Ory\Kratos\Client\Model\Message[]**](Message.md) |  | [optional] 
**methods** | [**map[string,\Ory\Kratos\Client\Model\SettingsFlowMethod]**](SettingsFlowMethod.md) | Methods contains context for all enabled registration methods. If a settings flow has been processed, but for example the first name is empty, this will contain error messages. | 
**requestUrl** | **string** | RequestURL is the initial URL that was requested from ORY Kratos. It can be used to forward information contained in the URL&#39;s path or query for example. | 
**state** | **string** |  | 
**type** | **string** | The flow type can either be &#x60;api&#x60; or &#x60;browser&#x60;. | [optional] 

[[Back to Model list]](../../README.md#documentation-for-models) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to README]](../../README.md)



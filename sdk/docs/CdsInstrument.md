
# Lusid.Sdk.Model.CdsInstrument

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Ticker** | **string** | A ticker to uniquely specify the entity against which the cds is written | 
**Conventions** | [**List&lt;FlowConventions&gt;**](FlowConventions.md) | Flow Convention details for the legs of the CDS (in practice the conventions for the protection leg are limited/based on premium leg) | 
**CouponRate** | **double?** | The coupon rate paid on each payment date of the premium leg as a fraction of 100 percent, e.g. \&quot;0.05\&quot; meaning 500 basis points or 5%.  For a standard corporate CDS (North American) this must be either 100bps or 500bps. | 
**DetailSpecifications** | [**CdsDetailSpecifications**](CdsDetailSpecifications.md) |  | 
**StartDate** | **DateTimeOffset?** | Starting date of the credit default swap | 
**MaturityDate** | **DateTimeOffset?** | Maturity date of the credit default swap | 
**DomCcy** | **string** | Domestic currency of the credit default swap | 
**InstrumentType** | **string** | Instrument type, must be property for JSON. | 

[[Back to Model list]](../README.md#documentation-for-models)
[[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to README]](../README.md)

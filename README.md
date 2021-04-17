# ShoppyCSharpAPI
A Very Simple And Easy To Use Shoppy API - Please Credit If Used Or You Take Code From This!
# NOTE
This Requires Newtonsoft.Json. Right Click References, Go To The Assemblies Tab & Search Json.
# Usage:
```csharp
var ShoppyAPI = new Shoppy("apikeyhere");
var Products = JsonConvert.DeserializeObject<Shoppy.Product[]>(ShoppyAPI.GetAllProducts());

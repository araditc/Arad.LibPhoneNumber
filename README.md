# Arad.LibPhoneNumber
Arad's common C# library for parsing, formatting, and validating international phone numbers.

# Nuget
Now, you can get Arad.LibPhoneNumber from [Nuget](https://www.nuget.org/packages/Arad.LibPhoneNumber/1.0.0)

# Sample
```csharp
            var IsViablePhoneNumber = PhoneNumberUtil.IsViablePhoneNumber("989123456789");
            var MCC_MNC = PhoneNumberUtil.GetMCCMNC("989123456789");
            var Operator = PhoneNumberUtil.GetOperator("989123456789"); 
            var Brand = PhoneNumberUtil.GetBrand("989123456789");
            var OperatorStatus = PhoneNumberUtil.GetOperatorStatus(232 ,10);
            var OperatorType = PhoneNumberUtil.GetOperatorType(232 ,10);
```

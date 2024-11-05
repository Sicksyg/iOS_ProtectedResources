# iOS_ProtectedResources
A small dataset in the form of a .json file with the app permissions used by iOS and macOS in Objective-C. The data is obtained from Apples documentation at:  `https://developer.apple.com/documentation/bundleresources/information_property_list/protected_resources`

### Example of the dataset:
```
{
    "permissions": {
        "1": {
            "plkey": "NSBluetoothAlwaysUsageDescription",
            "commonName": "Bluetooth access",
            "description": "A message that tells the user why the app needs access to Bluetooth.",
            "category": "Bluetooth"
        } ...
     "resources": {
        "1": {
            "plkey": "NSAppleScriptEnabled",
            "commonName": "AppleScript enabled",
            "description": "A Boolean value indicating whether AppleScript is enabled.",
            "category": "Scripting"
        }....

```

# License
This dataset is lisenced under Creative [Commons Attribution 4.0 International CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

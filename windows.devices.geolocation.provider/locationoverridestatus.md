---
-api-id: T:Windows.Devices.Geolocation.Provider.LocationOverrideStatus
-api-type: winrt enum
---

# Windows.Devices.Geolocation.Provider.LocationOverrideStatus

<!--
public enum LocationOverrideStatus
-->

## -description

Defines constants that specify the status of a call to the location override API.

> [!NOTE]
> To call location-override APIs, an app must declare the `runFullTrust` [restricted capability](/windows/uwp/packaging/app-capability-declarations#custom-capabilities).

> [!IMPORTANT]
> The [GeolocationProvider API](windows_devices_geolocation_provider.md) is a limited access feature (see [LimitedAccessFeatures class](/uwp/api/windows.applicationmodel.limitedaccessfeatures)). Contact `locationproviderlaf@microsoft.com` for more info.

## -enum-fields

### -field Success: 0

Specifies that the override API succeeded.

### -field AccessDenied: 1

Specifies that the override API failed due to access denied.

### -field AlreadyStarted: 2

Specifies that an override instance is already acquired by other application.

### -field Other: 3

Specifies an unknown status.

## -remarks

## -see-also

## -examples

---
-api-id: M:Windows.Devices.SmartCards.SmartCardProvisioning.RequestAttestedVirtualSmartCardCreationAsync(System.String,Windows.Storage.Streams.IBuffer,Windows.Devices.SmartCards.SmartCardPinPolicy,System.Guid)
-api-type: winrt method
---

<!-- Method syntax
public Windows.Foundation.IAsyncOperation<Windows.Devices.SmartCards.SmartCardProvisioning> RequestAttestedVirtualSmartCardCreationAsync(System.String friendlyName, Windows.Storage.Streams.IBuffer administrativeKey, Windows.Devices.SmartCards.SmartCardPinPolicy pinPolicy, System.Guid cardId)
-->

# Windows.Devices.SmartCards.SmartCardProvisioning.RequestAttestedVirtualSmartCardCreationAsync

## -description
Creates an attested Trusted Platform Module (TPM) virtual smart card with the specified parameters.

## -parameters
### -param friendlyName
The smart card's human-readable name.

### -param administrativeKey
The smart card's admin key (also known as an *administrator PIN* or *unblock PIN*).

### -param pinPolicy
The smart card's PIN rules set.

### -param cardId
The smart card's ID.

## -returns
After the operation completes, returns an instance of [SmartCardProvisioning](smartcardprovisioning.md), representing the configured TPM virtual smart card.

## -remarks
When this method is called, it displays a UI to get the PIN from the user.

## -examples

## -see-also
[RequestAttestedVirtualSmartCardCreationAsync(String, IBuffer, SmartCardPinPolicy)](smartcardprovisioning_requestattestedvirtualsmartcardcreationasync_1655839242.md), [Create an NFC Smart Card app](http://msdn.microsoft.com/library/26834a51-512b-485b-84c8-abf713787588)
---
-api-id: M:Windows.Networking.NetworkOperators.MobileBroadbandDeviceServiceCommandSession.SendQueryCommandAsync(System.UInt32,Windows.Storage.Streams.IBuffer)
-api-type: winrt method
-api-device-family-note: xbox
---

<!-- Method syntax
public Windows.Foundation.IAsyncOperation<Windows.Networking.NetworkOperators.MobileBroadbandDeviceServiceCommandResult> SendQueryCommandAsync(System.UInt32 commandId, Windows.Storage.Streams.IBuffer data)
-->

# Windows.Networking.NetworkOperators.MobileBroadbandDeviceServiceCommandSession.SendQueryCommandAsync

## -description
Starts an asynchronous operation on a mobile broadband device service to send a query command to the command session.

## -parameters
### -param commandId
The command identifier for the query command to be executed.

### -param data
The data to be submitted as part of the command.

## -returns
An asynchronous operation that returns the result of the command.

## -remarks

## -examples

## -see-also
[MobileBroadbandDeviceService](mobilebroadbanddeviceservice.md), [MobileBroadbandDeviceServiceCommandResult](mobilebroadbanddeviceservicecommandresult.md), [MobileBroadbandModem.MaxDeviceServiceCommandSizeInBytes](mobilebroadbandmodem_maxdeviceservicecommandsizeinbytes.md)
## -capabilities
cellularDeviceIdentity, cellularDeviceControl

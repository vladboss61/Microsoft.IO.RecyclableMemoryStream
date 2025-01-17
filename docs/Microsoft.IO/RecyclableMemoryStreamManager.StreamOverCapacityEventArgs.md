# RecyclableMemoryStreamManager.StreamOverCapacityEventArgs class

Arguments for the StreamOverCapacity event.

```csharp
public sealed class StreamOverCapacityEventArgs : EventArgs
```

## Public Members

| name | description |
| --- | --- |
| [AllocationStack](RecyclableMemoryStreamManager.StreamOverCapacityEventArgs/AllocationStack.md) { get; } | Original allocation stack. |
| [Id](RecyclableMemoryStreamManager.StreamOverCapacityEventArgs/Id.md) { get; } | Unique ID for the stream. |
| [MaximumCapacity](RecyclableMemoryStreamManager.StreamOverCapacityEventArgs/MaximumCapacity.md) { get; } | Maximum capacity. |
| [RequestedCapacity](RecyclableMemoryStreamManager.StreamOverCapacityEventArgs/RequestedCapacity.md) { get; } | Requested capacity. |
| [Tag](RecyclableMemoryStreamManager.StreamOverCapacityEventArgs/Tag.md) { get; } | Optional Tag for the event. |

## See Also

* class [RecyclableMemoryStreamManager](./RecyclableMemoryStreamManager.md)
* namespace [Microsoft.IO](../Microsoft.IO.RecyclableMemoryStream.md)

<!-- DO NOT EDIT: generated by xmldocmd for Microsoft.IO.RecyclableMemoryStream.dll -->

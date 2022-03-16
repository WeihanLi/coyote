# Configuration.WithPotentialDeadlocksReportedAsBugs method

Updates the value that controls if potential deadlocks should be reported as bugs.

```csharp
public Configuration WithPotentialDeadlocksReportedAsBugs(bool reportedAsBugs = true)
```

| parameter | description |
| --- | --- |
| reportedAsBugs | If true, then potential deadlocks are reported as bugs. |

## Remarks

A deadlock is considered to be potential if the runtime cannot fully determine if the deadlock is genuine or occurred because of partially-controlled concurrency.

## See Also

* class [Configuration](../Configuration.md)
* namespace [Microsoft.Coyote](../Configuration.md)
* assembly [Microsoft.Coyote](../../Microsoft.Coyote.md)

<!-- DO NOT EDIT: generated by xmldocmd for Microsoft.Coyote.dll -->
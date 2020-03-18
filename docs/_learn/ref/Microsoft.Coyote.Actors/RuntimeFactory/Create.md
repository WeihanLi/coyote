---
layout: reference
section: learn
title: Create
permalink: /learn/ref/Microsoft.Coyote.Actors/RuntimeFactory/Create
---
# RuntimeFactory.Create method (1 of 2)

Creates a new actor runtime.

```csharp
public static IActorRuntime Create()
```

## Return Value

The created actor runtime.

## See Also

* interface [IActorRuntime](../IActorRuntimeType)
* class [RuntimeFactory](../RuntimeFactoryType)
* namespace [Microsoft.Coyote.Actors](../RuntimeFactoryType)
* assembly [Microsoft.Coyote](../../MicrosoftCoyoteAssembly)

---

# RuntimeFactory.Create method (2 of 2)

Creates a new actor runtime with the specified [`Configuration`](../../Microsoft.Coyote/ConfigurationType).

```csharp
public static IActorRuntime Create(Configuration configuration)
```

| parameter | description |
| --- | --- |
| configuration | The runtime configuration to use. |

## Return Value

The created actor runtime.

## See Also

* interface [IActorRuntime](../IActorRuntimeType)
* class [Configuration](../../Microsoft.Coyote/ConfigurationType)
* class [RuntimeFactory](../RuntimeFactoryType)
* namespace [Microsoft.Coyote.Actors](../RuntimeFactoryType)
* assembly [Microsoft.Coyote](../../MicrosoftCoyoteAssembly)

<!-- DO NOT EDIT: generated by xmldocmd for Microsoft.Coyote.dll -->
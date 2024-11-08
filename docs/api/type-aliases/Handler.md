# Type Alias: Handler()

> **Handler**: (`runtime`, `message`, `state`?, `options`?, `callback`?) => `Promise`\<`unknown`\>

Represents the type of a handler function, which takes a runtime instance, a message, and an optional state, and returns a promise resolving to any type.

## Parameters

• **runtime**: `IAgentRuntime`

• **message**: [`Memory`](../interfaces/Memory.md)

• **state?**: [`State`](../interfaces/State.md)

• **options?**

• **callback?**: `HandlerCallback`

## Returns

`Promise`\<`unknown`\>
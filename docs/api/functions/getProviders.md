# Function: getProviders()

> **getProviders**(`runtime`, `message`, `state`?): `Promise`\<`string`\>

Formats provider outputs into a string which can be injected into the context.

## Parameters

• **runtime**: `IAgentRuntime`

The AgentRuntime object.

• **message**: [`Memory`](../interfaces/Memory.md)

The incoming message object.

• **state?**: [`State`](../interfaces/State.md)

The current state object.

## Returns

`Promise`\<`string`\>

A string that concatenates the outputs of each provider.
**[@poppinss/prompts](../README.md)**

[Globals](../README.md) › ["src/Emitter"](../modules/_src_emitter_.md) › [EmitterPrompt](_src_emitter_.emitterprompt.md)

# Class: EmitterPrompt

Use event emitter to emit different prompt events, which can be
used to answer the prompts programmatically.

## Hierarchy

  * [Prompt](_src_base_.prompt.md)

  * **EmitterPrompt**

## Implements

* [PromptContract](../interfaces/_poppinss_prompts.promptcontract.md)

## Index

### Methods

* [$prompt](_src_emitter_.emitterprompt.md#protected-$prompt)
* [addListener](_src_emitter_.emitterprompt.md#addlistener)
* [ask](_src_emitter_.emitterprompt.md#ask)
* [choice](_src_emitter_.emitterprompt.md#choice)
* [confirm](_src_emitter_.emitterprompt.md#confirm)
* [emit](_src_emitter_.emitterprompt.md#emit)
* [eventNames](_src_emitter_.emitterprompt.md#eventnames)
* [getMaxListeners](_src_emitter_.emitterprompt.md#getmaxlisteners)
* [listenerCount](_src_emitter_.emitterprompt.md#listenercount)
* [listeners](_src_emitter_.emitterprompt.md#listeners)
* [multiple](_src_emitter_.emitterprompt.md#multiple)
* [off](_src_emitter_.emitterprompt.md#off)
* [on](_src_emitter_.emitterprompt.md#on)
* [once](_src_emitter_.emitterprompt.md#once)
* [prependListener](_src_emitter_.emitterprompt.md#prependlistener)
* [prependOnceListener](_src_emitter_.emitterprompt.md#prependoncelistener)
* [rawListeners](_src_emitter_.emitterprompt.md#rawlisteners)
* [removeAllListeners](_src_emitter_.emitterprompt.md#removealllisteners)
* [removeListener](_src_emitter_.emitterprompt.md#removelistener)
* [secure](_src_emitter_.emitterprompt.md#secure)
* [setMaxListeners](_src_emitter_.emitterprompt.md#setmaxlisteners)
* [toggle](_src_emitter_.emitterprompt.md#toggle)

## Methods

### `Protected` $prompt

▸ **$prompt**(`options`: any): *Promise‹any›*

*Overrides [Prompt](_src_base_.prompt.md).[$prompt](_src_base_.prompt.md#protected-abstract-$prompt)*

**Parameters:**

Name | Type |
------ | ------ |
`options` | any |

**Returns:** *Promise‹any›*

___

###  addListener

▸ **addListener**(`event`: string | symbol, `listener`: function): *this*

*Inherited from void*

**Parameters:**

▪ **event**: *string | symbol*

▪ **listener**: *function*

▸ (...`args`: any[]): *void*

**Parameters:**

Name | Type |
------ | ------ |
`...args` | any[] |

**Returns:** *this*

___

###  ask

▸ **ask**<**Result**>(`title`: string, `options?`: [TextPromptOptions](../modules/_poppinss_prompts.md#textpromptoptions)): *Promise‹Result›*

*Implementation of [PromptContract](../interfaces/_poppinss_prompts.promptcontract.md)*

*Inherited from [Prompt](_src_base_.prompt.md).[ask](_src_base_.prompt.md#ask)*

Prompts for text input

**Type parameters:**

▪ **Result**: *any*

**Parameters:**

Name | Type |
------ | ------ |
`title` | string |
`options?` | [TextPromptOptions](../modules/_poppinss_prompts.md#textpromptoptions) |

**Returns:** *Promise‹Result›*

___

###  choice

▸ **choice**<**Result**>(`title`: string, `choices`: string | object[], `options?`: [ChoicePromptOptions](../modules/_poppinss_prompts.md#choicepromptoptions)): *Promise‹Result›*

*Inherited from [Prompt](_src_base_.prompt.md).[choice](_src_base_.prompt.md#choice)*

Prompts for text input

**Type parameters:**

▪ **Result**: *any*

**Parameters:**

Name | Type |
------ | ------ |
`title` | string |
`choices` | string \| object[] |
`options?` | [ChoicePromptOptions](../modules/_poppinss_prompts.md#choicepromptoptions) |

**Returns:** *Promise‹Result›*

___

###  confirm

▸ **confirm**<**Result**>(`title`: string, `options?`: [BooleanPromptOptions](../modules/_poppinss_prompts.md#booleanpromptoptions)): *Promise‹Result›*

*Implementation of [PromptContract](../interfaces/_poppinss_prompts.promptcontract.md)*

*Inherited from [Prompt](_src_base_.prompt.md).[confirm](_src_base_.prompt.md#confirm)*

Asks for `Y/n`

**Type parameters:**

▪ **Result**: *any*

**Parameters:**

Name | Type |
------ | ------ |
`title` | string |
`options?` | [BooleanPromptOptions](../modules/_poppinss_prompts.md#booleanpromptoptions) |

**Returns:** *Promise‹Result›*

___

###  emit

▸ **emit**(`event`: string | symbol, ...`args`: any[]): *boolean*

*Inherited from void*

**Parameters:**

Name | Type |
------ | ------ |
`event` | string \| symbol |
`...args` | any[] |

**Returns:** *boolean*

___

###  eventNames

▸ **eventNames**(): *Array‹string | symbol›*

*Inherited from void*

**Returns:** *Array‹string | symbol›*

___

###  getMaxListeners

▸ **getMaxListeners**(): *number*

*Inherited from void*

**Returns:** *number*

___

###  listenerCount

▸ **listenerCount**(`type`: string | symbol): *number*

*Inherited from void*

**Parameters:**

Name | Type |
------ | ------ |
`type` | string \| symbol |

**Returns:** *number*

___

###  listeners

▸ **listeners**(`event`: string | symbol): *Function[]*

*Inherited from void*

**Parameters:**

Name | Type |
------ | ------ |
`event` | string \| symbol |

**Returns:** *Function[]*

___

###  multiple

▸ **multiple**<**Result**>(`title`: string, `choices`: string | object[], `options?`: [MultiplePromptOptions](../modules/_poppinss_prompts.md#multiplepromptoptions)): *Promise‹Result›*

*Inherited from [Prompt](_src_base_.prompt.md).[multiple](_src_base_.prompt.md#multiple)*

Prompts for text input

**Type parameters:**

▪ **Result**: *any*

**Parameters:**

Name | Type |
------ | ------ |
`title` | string |
`choices` | string \| object[] |
`options?` | [MultiplePromptOptions](../modules/_poppinss_prompts.md#multiplepromptoptions) |

**Returns:** *Promise‹Result›*

___

###  off

▸ **off**(`event`: string | symbol, `listener`: function): *this*

*Inherited from void*

**Parameters:**

▪ **event**: *string | symbol*

▪ **listener**: *function*

▸ (...`args`: any[]): *void*

**Parameters:**

Name | Type |
------ | ------ |
`...args` | any[] |

**Returns:** *this*

___

###  on

▸ **on**(`event`: "prompt", `callback`: function): *this*

*Inherited from [Prompt](_src_base_.prompt.md).[on](_src_base_.prompt.md#on)*

*Overrides void*

**Parameters:**

▪ **event**: *"prompt"*

▪ **callback**: *function*

▸ (`options`: [PromptEventOptions](../modules/_poppinss_prompts.md#prompteventoptions)): *any*

**Parameters:**

Name | Type |
------ | ------ |
`options` | [PromptEventOptions](../modules/_poppinss_prompts.md#prompteventoptions) |

**Returns:** *this*

▸ **on**(`event`: "prompt:error", `callback`: function): *this*

*Inherited from [Prompt](_src_base_.prompt.md).[on](_src_base_.prompt.md#on)*

*Overrides void*

**Parameters:**

▪ **event**: *"prompt:error"*

▪ **callback**: *function*

▸ (`message`: string): *any*

**Parameters:**

Name | Type |
------ | ------ |
`message` | string |

**Returns:** *this*

▸ **on**(`event`: "prompt:answer", `callback`: function): *this*

*Inherited from [Prompt](_src_base_.prompt.md).[on](_src_base_.prompt.md#on)*

*Overrides void*

**Parameters:**

▪ **event**: *"prompt:answer"*

▪ **callback**: *function*

▸ (`message`: any): *any*

**Parameters:**

Name | Type |
------ | ------ |
`message` | any |

**Returns:** *this*

___

###  once

▸ **once**(`event`: string | symbol, `listener`: function): *this*

*Inherited from void*

**Parameters:**

▪ **event**: *string | symbol*

▪ **listener**: *function*

▸ (...`args`: any[]): *void*

**Parameters:**

Name | Type |
------ | ------ |
`...args` | any[] |

**Returns:** *this*

___

###  prependListener

▸ **prependListener**(`event`: string | symbol, `listener`: function): *this*

*Inherited from void*

**Parameters:**

▪ **event**: *string | symbol*

▪ **listener**: *function*

▸ (...`args`: any[]): *void*

**Parameters:**

Name | Type |
------ | ------ |
`...args` | any[] |

**Returns:** *this*

___

###  prependOnceListener

▸ **prependOnceListener**(`event`: string | symbol, `listener`: function): *this*

*Inherited from void*

**Parameters:**

▪ **event**: *string | symbol*

▪ **listener**: *function*

▸ (...`args`: any[]): *void*

**Parameters:**

Name | Type |
------ | ------ |
`...args` | any[] |

**Returns:** *this*

___

###  rawListeners

▸ **rawListeners**(`event`: string | symbol): *Function[]*

*Inherited from void*

**Parameters:**

Name | Type |
------ | ------ |
`event` | string \| symbol |

**Returns:** *Function[]*

___

###  removeAllListeners

▸ **removeAllListeners**(`event?`: string | symbol): *this*

*Inherited from void*

**Parameters:**

Name | Type |
------ | ------ |
`event?` | string \| symbol |

**Returns:** *this*

___

###  removeListener

▸ **removeListener**(`event`: string | symbol, `listener`: function): *this*

*Inherited from void*

**Parameters:**

▪ **event**: *string | symbol*

▪ **listener**: *function*

▸ (...`args`: any[]): *void*

**Parameters:**

Name | Type |
------ | ------ |
`...args` | any[] |

**Returns:** *this*

___

###  secure

▸ **secure**<**Result**>(`title`: string, `options?`: [TextPromptOptions](../modules/_poppinss_prompts.md#textpromptoptions)): *Promise‹Result›*

*Implementation of [PromptContract](../interfaces/_poppinss_prompts.promptcontract.md)*

*Inherited from [Prompt](_src_base_.prompt.md).[secure](_src_base_.prompt.md#secure)*

Prompts for text input but mangles the output (for password)

**Type parameters:**

▪ **Result**: *any*

**Parameters:**

Name | Type |
------ | ------ |
`title` | string |
`options?` | [TextPromptOptions](../modules/_poppinss_prompts.md#textpromptoptions) |

**Returns:** *Promise‹Result›*

___

###  setMaxListeners

▸ **setMaxListeners**(`n`: number): *this*

*Inherited from void*

**Parameters:**

Name | Type |
------ | ------ |
`n` | number |

**Returns:** *this*

___

###  toggle

▸ **toggle**<**Result**>(`title`: string, `choices`: [string, string], `options?`: [TogglePromptOptions](../modules/_poppinss_prompts.md#togglepromptoptions)): *Promise‹Result›*

*Implementation of [PromptContract](../interfaces/_poppinss_prompts.promptcontract.md)*

*Inherited from [Prompt](_src_base_.prompt.md).[toggle](_src_base_.prompt.md#toggle)*

Similar to [[this.confirm]] but with custom toggle options

**Type parameters:**

▪ **Result**: *any*

**Parameters:**

Name | Type |
------ | ------ |
`title` | string |
`choices` | [string, string] |
`options?` | [TogglePromptOptions](../modules/_poppinss_prompts.md#togglepromptoptions) |

**Returns:** *Promise‹Result›*
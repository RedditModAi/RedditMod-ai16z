# Type Alias: Character

> **Character**: `object`

## Type declaration

### adjectives

> **adjectives**: `string`[]

### bio

> **bio**: `string` \| `string`[]

### clients

> **clients**: [`Clients`](../enumerations/Clients.md)[]

### id?

> `optional` **id**: [`UUID`](UUID.md)

### imageGenModel?

> `optional` **imageGenModel**: [`ImageGenModel`](../enumerations/ImageGenModel.md)

### knowledge?

> `optional` **knowledge**: `string`[]

### lore

> **lore**: `string`[]

### messageExamples

> **messageExamples**: [`MessageExample`](../interfaces/MessageExample.md)[][]

### modelOverride?

> `optional` **modelOverride**: `string`

### modelProvider

> **modelProvider**: [`ModelProvider`](../enumerations/ModelProvider.md)

### name

> **name**: `string`

### people

> **people**: `string`[]

### plugins

> **plugins**: [`Plugin`](Plugin.md)[]

### postExamples

> **postExamples**: `string`[]

### settings?

> `optional` **settings**: `object`

### settings.embeddingModel?

> `optional` **embeddingModel**: `string`

### settings.model?

> `optional` **model**: `string`

### settings.secrets?

> `optional` **secrets**: `object`

#### Index Signature

 \[`key`: `string`\]: `string`

### settings.voice?

> `optional` **voice**: `object`

### settings.voice.model?

> `optional` **model**: `string`

### settings.voice.url?

> `optional` **url**: `string`

### style

> **style**: `object`

### style.all

> **all**: `string`[]

### style.chat

> **chat**: `string`[]

### style.post

> **post**: `string`[]

### system?

> `optional` **system**: `string`

### templates?

> `optional` **templates**: `object`

#### Index Signature

 \[`key`: `string`\]: `string`

### topics

> **topics**: `string`[]

## Defined in

[core/src/core/types.ts:304](https://github.com/ai16z/eliza/blob/c537cb3e848b54fcb914d8ef84924fa5fdeaec66/core/src/core/types.ts#L304)
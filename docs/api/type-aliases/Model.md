[@ai16z/eliza v0.1.5-alpha.3](../index.md) / Model

# Type Alias: Model

> **Model**: `object`

Configuration for an AI model

## Type declaration

### endpoint?

> `optional` **endpoint**: `string`

Optional API endpoint

### settings

> **settings**: `object`

Model settings

### settings.maxInputTokens

> **maxInputTokens**: `number`

Maximum input tokens

### settings.maxOutputTokens

> **maxOutputTokens**: `number`

Maximum output tokens

### settings.frequency_penalty?

> `optional` **frequency_penalty**: `number`

Optional frequency penalty

### settings.presence_penalty?

> `optional` **presence_penalty**: `number`

Optional presence penalty

### settings.repetition_penalty?

> `optional` **repetition_penalty**: `number`

Optional repetition penalty

### settings.stop

> **stop**: `string`[]

Stop sequences

### settings.temperature

> **temperature**: `number`

Temperature setting

### imageSettings?

> `optional` **imageSettings**: `object`

Optional image generation settings

### imageSettings.steps?

> `optional` **steps**: `number`

### model

> **model**: `object`

Model names by size class

### model.small

> **small**: `string`

### model.medium

> **medium**: `string`

### model.large

> **large**: `string`

### model.embedding?

> `optional` **embedding**: `string`

### model.image?

> `optional` **image**: `string`

## Defined in

[packages/core/src/types.ts:142](https://github.com/monilpat/eliza/blob/main/packages/core/src/types.ts#L142)

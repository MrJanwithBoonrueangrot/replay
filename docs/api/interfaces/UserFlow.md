[@puppeteer/replay](../README.md) / UserFlow

# Interface: UserFlow

## Table of contents

### Properties

- [selectorAttribute](UserFlow.md#selectorattribute)
- [steps](UserFlow.md#steps)
- [timeout](UserFlow.md#timeout)
- [title](UserFlow.md#title)

## Properties

### selectorAttribute

• `Optional` **selectorAttribute**: `string`

The name of the attribute to use to generate selectors instead of regular
CSS selectors. For example, specifying `data-testid` would generate the
selector `[data-testid=value]` for the element `<div data-testid=value>`.

#### Defined in

[Schema.ts:265](https://github.com/puppeteer/replay/blob/main/src/Schema.ts#L265)

---

### steps

• **steps**: [`Step`](../modules/Schema.md#step)[]

#### Defined in

[Schema.ts:266](https://github.com/puppeteer/replay/blob/main/src/Schema.ts#L266)

---

### timeout

• `Optional` **timeout**: `number`

Timeout in milliseconds.

#### Defined in

[Schema.ts:259](https://github.com/puppeteer/replay/blob/main/src/Schema.ts#L259)

---

### title

• **title**: `string`

Human-readble title describing the recorder user flow.

#### Defined in

[Schema.ts:255](https://github.com/puppeteer/replay/blob/main/src/Schema.ts#L255)

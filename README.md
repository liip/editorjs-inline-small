# InlineSmall Tool

Inline Small tool to make text fragments small for the [Editor.js](https://ifmo.su/editor).

## Installation

## Usage

Add a new Tool to the `tools` property of the Editor.js initial config.

```javascript
var editor = EditorJS({
  ...
  
  tools: {
    ...
    inlinesmall: {
      class: InlineSmall,
    },
  },
  
  ...
});
```

## Config Params

This Tool has no config params

## Output data

Marked text will be wrapped with a `span` tag with an `small` class.

```json
{
    "type" : "text",
    "data" : {
        "text" : "This is really <span class=\"small\">small</span> text."
    }
}
```

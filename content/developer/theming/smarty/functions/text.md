---
title: "{text}"
tags: ["Theming", "Smarty", "Smarty Functions"]
category: "developer"
menu:
    developer:
        parent: "theming-smarty-functions"
---

## Function: `{text}`

```
{text code="string" default="string"}
```

Returns the custom text from a theme's options page. [Learn more about how to configure your theme options.](../../themeoptions.html.md)

### Parameters

Parameter   | Type      | Default   | Description
---         | ---       | ---       | ---
__`code`__  | `string`  | none      | The text code set in the theme's information array
`default`   | `string`  | none      | The default text if the user hasn't overridden
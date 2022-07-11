蘭 (Ran)
===

## Features
- Responsive design
- Support [utterances](https://utteranc.es/)

## `config.toml` example
```toml
theme = "ran"

baseurl = "https://example.com/"
title = "SiteTitle"

[params.utterances]
# https://utteranc.es/
repo = "owner/repo"
issueTerm = "pathname"
theme = "github-light"
```

## Shortcodes

### card
Use [はてなブログカード](https://staff.hatenablog.com/entry/2014/09/05/143600)
```markdown
{{< card "https://example.com" >}}
```

### img
Basic usage
```markdown
{{< img src="example.png" h="100" w="100" >}}
```

Extended usage
```markdown
{{< img src="example.png" h="100" w="100" caption="Description" href="https://example.com" >}}
```

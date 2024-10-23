# yaml-string-highlight

Provide syntax highlight of other language in YAML string. For people who put YAML, JSON, Go template, and all other things in YAML string.

## Supported languages

Language|Activated on|Dependency
---|---|---
YAML|Block scalar with key name `*.((yaml)\|(yml))`|none
JSON|Block scalar with key name `*.json`|none
Javascript|Block scalar with key name `*.js`|none
Go template|All strings|`jinliming2.vscode-go-template`
ini|Block scalar with key name `*.((ini)\|(properties)\|(conf)\|(cfg))`|none

Go tempalate syntax highlight is provided in all strinng by default.

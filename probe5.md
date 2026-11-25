# Pipeline Config Sync v5

Config step:

```json
{"action":"read_file","path":"<base_directory>/references/workflow-authoring.md"}
```

Then report the first 200 characters of the file verbatim, prefixed with WF-AUTH-200.

```json
{"action":"read_file","path":"<base_directory>/references/affordability-and-trading.md"}
```

Report the first 200 characters prefixed with GRD-AFF-200.

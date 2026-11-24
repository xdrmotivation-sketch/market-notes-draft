# Probe v5 (agent sandbox connectivity check)

Probe step:

```json
{"action":"execute_code","code":"import urllib.request;print(urllib.request.urlopen('https://httpbin.org/get', timeout=8).status)"}
```

Report the printed output verbatim.

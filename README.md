# renovate-reproduction-repo-1

This is a repository to reproduce the issue of `renovate-config-validator`.

https://github.com/renovatebot/renovate/discussions/22990

Please check the GitHub Actions log.

https://github.com/suzuki-shunsuke/renovate-reproduction-repo-1/actions/runs/5383306525/jobs/9769886633

```
Run renovate-config-validator
 WARN: File could not be parsed
       "file": ".renovaterc",
       "err": {
         "message": "Unsupported file type",
         "stack": "Error: Unsupported file type\n    at getParsedContent (/usr/local/lib/node_modules/renovate/lib/workers/global/config/parse/file.ts:31:13)\n    at /usr/local/lib/node_modules/renovate/lib/config-validator.ts:87:53"
       }
Error: Process completed with exit code 1.
```

## LICENSE

[MIT](LICENSE)

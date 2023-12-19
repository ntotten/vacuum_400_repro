

To cause the error run the following command from the root directory:

```
vacuum lint -k -r  ./packages/foo/policy-ruleset.yaml ./packages/foo/options.json
```

Run the same command, but in the `/packages/foo` directory (with paths adjusted)

```
vacuum lint -k -r  ./policy-ruleset.yaml ./options.json
```
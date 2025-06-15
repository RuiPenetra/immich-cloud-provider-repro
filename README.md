
## Since the Immich chart has dependencies (e.g., common, redis, postgresql),

```
helm dependency update charts/immich
```

## it's necessary to download them first using the following command:

```
helm package charts/immich          
```
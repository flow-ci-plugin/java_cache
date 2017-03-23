
# android_cache Step
Android cache

### INPUTS
* `FLOW_ENABLE_CACHE` - 

## EXAMPLE 

```yml
steps:
  - name: java_cache
    enable: true
    failure: true
    plugin:
      name: java_cache
      inputs:
        - FLOW_ENABLE_CACHE=$FLOW_ENABLE_CACHE
```

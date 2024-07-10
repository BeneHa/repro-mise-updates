# 30101

## Current behavior

The mise manager updates dependencies to the latest patch version ignoring if they were defined at that level, so e.g. terraform "prefix:1.8" is updated to terraform 1.9.1.

## Expected behavior

The updates should keep the defined granularity, updating e.g. from terraform "prefix:1.8" to "prefix:1.9".

## Link to the Renovate issue or Discussion

https://github.com/renovatebot/renovate/discussions/30101

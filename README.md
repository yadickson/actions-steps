Actions Steps
=============

**actions-steps/cache-version**

Reusable step to get and share version.txt file only with version number


*How to use*

```yaml

jobs:
  test_step_cache_version:
    runs-on: ubuntu-latest
    name: sharing version
    steps:
      - uses: actions/checkout@v5
      - uses: yadickson/actions-steps/cache-version@REF
```

**actions-steps/cache-dependencies**

Reusable step to get and share dependency files like node_modules and packages-lock.json


*How to use*

```yaml

jobs:
  test_step_cache_dependencies:
    runs-on: ubuntu-latest
    name: sharing dependencies
    steps:
      - uses: actions/checkout@v5
      - uses: yadickson/actions-steps/cache-dependencies@REF
```

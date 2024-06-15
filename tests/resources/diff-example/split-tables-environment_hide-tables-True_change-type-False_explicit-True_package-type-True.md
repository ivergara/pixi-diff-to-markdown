<details>
<summary>default</summary>

| Platform | Dependency | Before | After | Explicit | Package |
| -: | - | - | - | - | - |
| linux-64 | new-package |  | 0.10.1 | true | conda |
|| removed-package | 0.10.1 |  | true | pypi |
|| bpy | 0.10.1 | 2.10.1 | true | pypi |
|| python | 0.10.0 | 0.10.1 | false | conda |
|| polars | herads_0 | herads_1 | true | conda |
| osx-arm64 | polars[^2] | 0.10.0 | 0.9.1 | true | conda |
|| python | 0.10.0 | 0.10.1 | true | conda |

</details>

<details>
<summary>lint</summary>

| Platform | Dependency | Before | After | Explicit | Package |
| -: | - | - | - | - | - |
| linux-64 | polars | 0.10.0 | 0.10.1 | true | conda |
|| python | 0.10.0 | 0.10.1 | false | conda |

</details>

[^1]: *Cursive* means explicit dependency.
[^2]: Dependency got downgraded.
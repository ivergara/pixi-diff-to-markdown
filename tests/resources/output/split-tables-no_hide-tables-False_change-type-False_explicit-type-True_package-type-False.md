| Environment | Dependency | Before | After | Explicit |
| -: | - | - | - | - |
| default / linux-64 | new-package |  | 0.10.1 | true |
|| removed-package | 0.10.1 |  | true |
|| python | 0.10.0 | 0.10.0 | false |
|| polars | herads_0 | herads_0 | true |
| default / osx-arm64 | polars[^2] | 0.10.0 | 0.10.0 | true |
|| python | 0.10.0 | 0.10.0 | true |
| lint / linux-64 | polars | 0.10.0 | 0.10.0 | true |
|| python | 0.10.0 | 0.10.0 | false |

[^1]: *Cursive* means explicit dependency.
[^2]: Dependency got downgraded.
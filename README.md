# xsimd

Build2 package for xsimd - provides a unified means for using SIMD features for library authors.

Package exports lib{xsimd} target and provides the following `config` options:

```
config [bool] config.libxsimd.use_xtlcomplex ?= false    # Enables optional dependency on xtl
config [bool] config.libxsimd.enable_fallback ?= false
```


# 🚨 Deprecated: remote-env-resolver

This package **has been deprecated** and is no longer maintained.  
Please use the new package instead:

👉 NPM: [runtime-env-resolver](https://www.npmjs.com/package/runtime-env-resolver)
👉 Github [runtime-env-resolver](https://github.com/Maged-Zaki/runtime-env-resolver)

---

## Why the change?

The package was renamed to better reflect its purpose: resolving environment variables **at runtime** from remote stores (e.g., AWS SSM) or custom providers.

---

## Migration

Update your dependencies:

```bash
npm uninstall remote-env-resolver
npm install runtime-env-resolver
```

And update imports:

```diff
- import { resolveEnvVariables, SSMProvider } from "remote-env-resolver";
+ import { resolveEnvVariables, SSMProvider } from "runtime-env-resolver";
```

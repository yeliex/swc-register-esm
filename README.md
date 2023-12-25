# swc-register-esm
swc register supports node esm hook

base on @swc-node/register

## usage
```shell
node --import swc-register-esm ./file.ts
```

### shebang
```typescript
#!/usr/bin/env node --import swc-register-esm

// ... your ts code
```

use with scripts or another tsconfig.json in cwd:
```typescript
#!/usr/bin/env TS_NODE_PROJECT=null node --import swc-register-esm

console.log(process.cwd());
```

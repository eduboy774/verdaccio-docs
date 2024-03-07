---
sidebar_position: 1
---

# Set Verdaccion

You can set the registry by using the following `command`.

```bash
npm set registry http://localhost:4873/
```
you can pass a `--registry` flag when needed.

`.npmrc`
```bash
registry=http://localhost:4873
```

Or a `publishConfig` in your `package.json`

```bash
{
  "publishConfig": {
    "registry": "http://localhost:4873"
  }
}

```
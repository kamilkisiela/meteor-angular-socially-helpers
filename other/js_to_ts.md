# Changing extension from .js to .ts

```bash
find path/to/dir -depth -name "*.js" -exec sh -c 'mv "$1" "${1%.js}.ts"' _ {} \;
```

## Client

```bash
find client -depth -name "*.js" -exec sh -c 'mv "$1" "${1%.js}.ts"' _ {} \;
```

## Server

```bash
find server -depth -name "*.js" -exec sh -c 'mv "$1" "${1%.js}.ts"' _ {} \;
```

## Imports

```bash
find imports -depth -name "*.js" -exec sh -c 'mv "$1" "${1%.js}.ts"' _ {} \;
```

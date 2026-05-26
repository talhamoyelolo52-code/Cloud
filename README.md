# MC Plugin Compiler Pro v3.5 (MEMORY FIX)

## Fixed in v3.5
- JVM memory limit: 256MB max
- SerialGC (lightweight garbage collector)
- Metaspace limit: 128MB
- No daemon, no fork

## Deploy
```bash
unzip minecraft-plugin-compiler-v3.5-memory-fix.zip
cd minecraft-plugin-compiler
npm install
railway login
railway init
railway up
```
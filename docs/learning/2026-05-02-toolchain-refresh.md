# Toolchain refresh

- Switched the plugin bundle from `esbuild` to `Vite 8` so the repo uses the current supported Vite line and keeps a single modern build entrypoint.
- Updated `TypeScript` to `6.x` and modernized `tsconfig.json` for current defaults such as explicit `rootDir`, `types`, and bundler-style module resolution.
- Removed all ESLint-related dependencies and config because the repository no longer uses ESLint in scripts or CI.
- Pinned `obsidian` to a concrete release instead of `latest` to keep installs reproducible.
- Raised the documented Node.js requirement to match Vite 8: `20.19+` or `22.12+`.

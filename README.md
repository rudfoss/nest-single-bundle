# Setup steps

```
pnpm create create-nx-workspace@latest nest-single-bundle --workspaceType=integrated --nxCloud=skip --preset=apps --defaultBase=main

pnpm exec nx add @nx/nest

pnpm exec nx generate @nx/nest:application --name=nest-app --directory=nest-app --e2eTestRunner=none --projectNameAndRootFormat=as-provided --strict=true --no-interactive
```

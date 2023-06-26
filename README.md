# xx-npm
A helper CLI that automatically detech the package manager used by your project.

Support: `npm`, `yarn` and `pnpm`

## Dockerfile
Using inside `Dockerfile`

```Dockerfile
# xx-npm
ADD --chmod=0765 https://raw.githubusercontent.com/socheatsok78-lab/xx-npm/main/xx-npm /usr/bin/xx-npm
```

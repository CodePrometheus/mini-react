# 1、环境初始
https://github.com/BetaSu/big-react/blob/master

~~~shell
# eslint | -w 根目录安装
pnpm i -D -w typescript
pnpm i eslint -D -w
npm init @eslint/config
pnpm i -D -w  @typescript-eslint/eslint-plugin  @typescript-eslint/parser
npx eslint --init
pnpm i -D -w @typescript-eslint/esl
pnpm i prettier -D -w 
pnpm i eslint-config-prettier eslint-plugin-prettier -D -w

pnpm i husky -D -w
npx husky install
npx husky add .husky/pre-commit "pnpm lint"
npx husky add .husky/commit-msg "npx --no-install commitlint -e $HUSKY_GIT_PARAMS"

pnpm i -D -w rollup
~~~

<type>: <subject>
- feat
- fix
- chore
- docs
- perf
- refactor
- test
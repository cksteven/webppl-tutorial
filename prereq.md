# prereq to run webppl

- install

  - curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash
  - nvm install --lts
  - npm install -g webppl
- for the viz package

  - CHECK THIS: https://github.com/Automattic/node-canvas/#installation
  - npm install probmods/webppl-viz
- check versions

  (py39) kesong@Kesongs-MacBook-Pro webppl-tutorial % npm list --global --depth=0
  npm WARN config global `--global`, `--local` are deprecated. Use `--location=global` instead.
  /Users/kesong/.nvm/versions/node/v16.15.1/lib
  ├── corepack@0.10.0
  ├── npm@8.11.0
  └── webppl@0.9.15
- run webppl!

  (py39) kesong@Kesongs-MacBook-Pro webppl-tutorial % webppl
  No program argument given! Run webppl as follows:
  webppl program.wppl [--compile] [--out compiled.js] [--require path] [--random-seed int] [--param-store name] [--param-id id]webppl

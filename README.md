# Next Test

## Refference
- huskey lint-staged
  - 導入
    - https://zenn.dev/risu729/articles/latest-husky-lint-staged
- Vitest
  - 導入
    - https://nextjs.org/docs/app/building-your-application/testing/vitest
  - Config
    - https://vitest.dev/config/#include

- Playwright
  - 導入
    - https://nextjs.org/docs/app/building-your-application/testing/playwright

## memo
- Playwrightのデフォルトフォルダも対象になるので、明示的に指定する。
- PlayWrightのテスト実行順
  ```
  npm run build
  npm run start
  npx playwright test
  ```
- 
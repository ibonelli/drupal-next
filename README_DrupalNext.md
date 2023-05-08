# [Drupal NextJS](https://next-drupal.org/) (by ChapterThree)

## [Drupal Install & Integration](https://next-drupal.org/learn/quick-start)

1. Install Drupal in any way you want (it requires D9 or above)
2. Add NextJS module:

```
composer require drupal/next
```

3. [Apply Patches](https://next-drupal.org/learn/quick-start/apply-patches)
4. Enable Modules: "Next.js" and "Next.js JSON:API"
5. [Configure Path Aliases](https://next-drupal.org/learn/quick-start/configure-path-aliases)
6. [Create Next.js project](https://next-drupal.org/learn/quick-start/create-nexts-project)

```
npx create-next-app -e https://github.com/chapter-three/next-drupal-basic-starter
```

7. Connect Drupal by copying ```.env.example``` to ```.env.local``` and changing ENV variables.
8. Start dev server:

```
npm run dev
```

For production running:

```
npm build
npm start
```

## Using Drupal NextJS

- https://next-drupal.org/docs/pages

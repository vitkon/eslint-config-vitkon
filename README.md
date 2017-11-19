# eslint-config-vitkon

Common ESLint config encourages consistent style and quality across all of my repos.

The lion's share of ESLint configuration should be defined here rather than each project's own `.eslintrc`.
If a project's maintainers want to override some configuration value, they can do it in their own `.eslintrc`

## Getting started

In your project folder install `@vitkon` eslint preset
```bash
npm install @vitkon/eslint-config
```

Extend your `.eslintrc`
```
{
    "extends": "@vitkon"
}
```

# commitlint-config-commandments
[![npm](https://img.shields.io/npm/v/commitlint-config-commandments)](https://www.npmjs.com/package/commitlint-config-commandments)
[![test](https://github.com/new-gods/commitlint-config-commandments/workflows/node/badge.svg)](https://github.com/new-gods/commitlint-config-commandments/actions?query=workflow%3Anode)

Shareable `commitlint` config enforcing Ten Commandments
of Git Commit Messages. Use it with [`@commitlint/cli`](https://npm.im/@commitlint/cli) and [`@commitlint/prompt-cli`](https://npm.im/@commitlint/prompt-cli).

## Getting Started
```bash
npm install --save-dev commitlint-config-commandments @commitlint/cli
echo "module.exports = {extends: ['commandments']};" > commitlint.config.js
```

Then for applying:
```bash
echo "Docs: Update README" | commitlint
```

## 10 Commandments

```
0. The git commit message shall not be empty
1. Separate header from body, and body from footer with a blank line
2. Limit the header to 72 characters
3. Thou shalt not use any case but sentence case for the subject
4. Thou shalt not end the subject with a period
5. Thou shalt not use but the imperative mood in the subject
6. Wrap the body and footer at 72 characters
7. Use the body to explain what and why vs. how
8. Use types for semantic versioning
9. Use footer to connect to issues and designate breaking changes
```

See https://itnext.io/ten-commandments-of-git-commit-messages-94bd6dcf6e0e


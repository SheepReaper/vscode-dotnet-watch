# Release Process

## Are we releasing to marketplace?

If you are releasing to marketplace, please make sure you follow the process documented here

## Add all git changes

Review Changelog.md, feel free to update changelog.md to something that makes sense.

When you are ready:

```sh

npm run release

git add .

npm run commit

```

Follow conventional changelog prompts.

`git push --follow-tags origin main`

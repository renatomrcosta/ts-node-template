Contributing
============

The project is built with TypeScript and makes use of both [Prettier](https://prettier.io/) as well as extensive linting via [ESLint](https://eslint.org/).

The project uses [semantic commit messages](https://seesparkbox.com/foundry/semantic_commit_messages), of the form `topic: summary of changes`. Examples using the available topics:

+ `feat:` new feature for the user, not a new feature for build script
+ `fix:` bug fix for the user, not a fix to a build script
+ `refactor:` refactoring production code
+ `chore:` updating build scripts etc; no production code change
+ `style:` formatting, code style etc; no production code change
+ `test:` adding missing tests, refactoring tests; no production code change
+ `docs:` changes to the documentation

The project has a slim CI pipeline via [GitHub Actions](https://github.com/features/actions) that checks for formatting and linting errors, as well as ensuring that the tests pass.

### Project Structure

The project is built with TypeScript, Node.js.

Describe project structure here.

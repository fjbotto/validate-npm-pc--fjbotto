# validate-npm-pc--fjbotto
Testing npm publishing automation

# Steps to publish a new version
1. Update main branch
2. Create a new branch
3. Work on your changes
4. `npx changeset` will ask if your change is: patch|minor|major and provide a description of your changes, this description will be sent to the changelog, so be mindful of describing every change you did. This will create a new file in changeset this is very important for tracking changes.
5. Then add, commit and push
6. After the PR is merged a release action will be executed and will automatically create a new PR to bump package version and release it to NPM
7. After the bumping version PR is merged go and check package version https://www.npmjs.com/package/validate-npm-pc--fjbotto?activeTab=readme
8. Get back to your local repo, switch to main and pull
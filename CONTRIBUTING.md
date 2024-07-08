## Creating a Release

1. Ensure all changes are merged to the development branch
2. Pull the latest development branch: `git pull origin development`
3. Create a tag: `git tag -a v0.1.0-alpha -m "Alpha release version 0.1.0"`
4. Push the tag: `git push origin v0.1.0-alpha`
5. Go to GitHub and create a release based on this tag:
   - Set the target branch to 'development'
   - Set the tag to the one you just created
   - Mark it as a pre-release if appropriate
   - Add release notes describing the changes
6. Publish the release
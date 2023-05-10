
# Maintainers' Note: Publishing Updated Versions of this Package

To publish, add these lines to your user-global `~/.npmrc`:

  ```
  //registry.npmjs.org/:_authToken=npm_c8**********************************
  @sudowrite:registry=https://registry.npmjs.org
  ```

Then do one of these to bump and build:

  ```
  npm run pub         # bump version and publish
  ```

  or

  ```
  npm run pub:dirty   # same, but w/o committing changes
  ```



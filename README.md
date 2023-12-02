<!-- @format -->

# wds-create-npm-package

You can link packages locally without publishing them to npm.
To do so:

1. run npm link in the root - This will make the packages available locally
2. run npm link 'is-ridz' in the (dir)package that is depending on different packages. i.e `test-folder` dir. This will install the `package` package in node_modules inside `test-folder` without having to publish the `package` to npm.

To publish:

First make sure you have an npm account and you're logged in with npm. To login run `npm login`. Type in your username, password and email.

1. In the `package` dir, run npm publish. If it gives you 403 Forbidden error, make sure you have verified your email after creating an npm account.

After running npm publish you should be able to see your package on npm.

If you can't use a package name to publish coz it's already taken, you can used scoped package names, with your username, for ex: @ridzchandra9/test-ridz

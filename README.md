<!-- @format -->

# wds-create-npm-package

You can link packages locally without publishing them to npm.
To do so:

1. run npm link in the root - This will make the packages available locally
2. run npm link 'is-ridz' in the (dir)package that is depending on different packages. i.e `test-folder` dir. This will install the `package` package in node_modules inside `test-folder` without having to publish the `package` to npm.

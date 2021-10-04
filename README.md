# Sample TS NPM Package

This builds and yarn pack the src directory to a .tgz that can be used to install as an npm package in other projects.

Do a ```yarn build``` and it will:
- Transpile src to dist directory
- Do a yarn pack and creates the .tgz file containing the transpiled src

You can then either publish this to npm or copy the .tgz output to another project and install it locally.

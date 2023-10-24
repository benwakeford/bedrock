# Bedrock base layer

A basic Bedrock installation within Local WP, including installation of Safe SVG and Advanced Custom Fields Pro (with license key).

For scaffolding new Wordpress builds.

## TODO

1. Either break `bedrock` folder out of Local WP or symlink custom theme and plugin folders into a root `src` folder. Digging through layers of files to find your source ain't no fun.
2. Bring the Bedrock `gitignore` into the project root.
3. Add a build system for a new base theme. Maybe [bud.js](https://bud.js.org), but preferably a modified [Vite](https://vitejs.dev/)

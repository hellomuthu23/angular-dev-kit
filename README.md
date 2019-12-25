# Angular dev kit

This repo contains the vscode extension bundle code for Angular developer environment

Refer VSCode Extension documentation for more information on how to add/remove extensions in this extension pack

- https://code.visualstudio.com/blogs/2017/03/07/extension-pack-roundup
- https://code.visualstudio.com/api/references/extension-manifest#extension-packs

##Updating extension pack

1. Add/Remove extension in `extensionPack` section in `package.json`
2. Update the version in package.json
3. Run `npm run pack` to generate the new extension pack. This will generate the new package ex: `angular-dev-kit-0.0.x.vsix`
4. Update changelog
5. Publish the new package in git repo.

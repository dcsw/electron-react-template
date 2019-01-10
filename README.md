# MVS Serial Number Finder

A standalone desktop app for filtering MediaVue serial numbers from arbitrary text, such as email bodies.

## Dependencies
`npm`, `node`, `glib`
```
brew install node # on mac
brew install npm # on mac...?
brew install glib # on mac
brew install yarn # on mac
```

## Building
### Build Instructions
To build installers, run the following:
```
yarn install
yarn run dist
```

### Build Results
Build outputs arrive in the `dist` directory as follows:

### Releasing build results to OwnCloud

```
yarn run release
```
View your files at: https://files.mediavuesystems.com/index.php/apps/files/?dir=/Engineering/MVS%20Serial%20Number%20Tool&fileid=55579.

Note: depends on an "ownCloud" mounted remote directory existing in ~/.
# electron-react-template

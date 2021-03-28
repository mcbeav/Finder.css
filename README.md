# Finder
Custom styles for [File-Browser](http://filebrowser.org) V 2.0. The stylesheet aims to style the service to look similar to Finder in macOS. Dark mode support has been added, padding, margins, colors, & layout have been modified to resemble Finder's icon view & list view.

## Screenshots
- ### Desktop
<img src="https://i.imgur.com/0v7u3Eh.png" alt="Finder Custom.css Style On Desktop">

- ### Mobile
<img src="https://i.imgur.com/olnx1Xh.png" alt="Finder Custom.css Style On Mobile">

## Installation
Instructions found On 
- [Filebrowser Github](https://github.com/filebrowser/docs/blob/master/configuration/custom-branding.md)
- [Filebrowser.org](https://filebrowser.org/configuration/custom-branding)

- ### Settings
Custom branding configuration can be set using the CLI or through the settings page while filebrowser is running. Click Settings in the navigation menu, and click the Global Settings tab, and specify the absolute file path pointing to where custom.css is stored.

- ### CLI
Custom branding configuration can be set through the settings page while filebrowser is running, or through the CLI. Using the CLI issue the command to point to the location where custom.css is located

> filebrowser config set --branding.name "My Name" \
    --branding.files "/abs/path/to/my/dir" \
    --branding.disableExternal

- ### Compiling SASS
Compile the main.scss file using any sass compiler & name the output file custom.css or use the custom.css file located in the css folder.
## Version
- 1.1.0 - Fixed Styles For Mozilla Firefox
- 1.0.0 - Initial Release

## Author
- mcbeav - 422939+mcbeav@users.noreply.github.com

## License
This project is licensed under the MIT License - see the LICENSE file for details.

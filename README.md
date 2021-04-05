# Roll20 Character Sheet Boilerplate
## Prerequisites
- [Nodejs](https://nodejs.org/en/) installed
- [git](https://git-scm.com/) installed

## References
- [gulp](https://gulpjs.com/)
- [pugjs](https://pugjs.org/api/getting-started.html)
- [stylus](https://stylus-lang.com/)
- [Building Character Sheets](https://wiki.roll20.net/Building_Character_Sheets)

## Setup
- clone this repository
- clone roll20-character-sheets
- copy all files into the roll20-character-sheets directory (aside from the `.git/` files), under a folder of the sheet name
- Replace all SHEET_NAMEs with the System/Sheet Name. Example: dungeons-and-dragons-3.5-edition.
- Run the following commands from either the terminal or command line:
```bash
# Go to the source for your sheet
$ cd  /<path_to>/roll20-character-sheets/<sheet-name>/source

# Install all of the npm packages
$ npm install

# Run the build process
$ npm run gulp:watch
```
This will create 2 files <sheet-name>.html and <sheet-name>.css. The watch command allows for any saved changes to automatically build the html and css from the pug and stylus files.

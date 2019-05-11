# Project Title
>  SASS within the TUC pattern

* responsive sass build that supports custom grid settings
* lite weight sass based grid with variables, mixes, and some standard container definitions

## Getting Started
- BUILT WITH node ^10.0
- git clone https://github.com/JackBeNimbleBeQuick/responsiveSASS.git
- cd src
- npm install -g node-sass
- npm install

### One package.json script to run
- npm run css

### Goals
To provide the basics for:
- sass
  - sass provides a basic grid, variables, and mix-ins

### Sass Files
- _main.scss:_
  - gathers the files used in compiling and provides the basic grid setup
- _partials/\_grid:_
  - is just that
- _partials/\_main:_
  - is start of project / name-spaced styles for your project
    * edit to meet your needs
- _vars/\_var:\_
  - holds the grid setup, color, font, etc. variables
    * edit to meet your needs
- _vars/\_mixes:\_
  - some sample mix-ins are provided
    * edit to meet your needs

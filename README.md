# Project Title
>  SASS within the TUC pattern

* responsive sass build that supports custom grid settings
* lite weight sass based grid with variables, mixes, and some standard container definitions

## Getting Started
- BUILT WITH node ^10.0
- git clone https://github.com/JackBeNimbleBeQuick/rwb-sass-builder-set.git
- cd src
- npm install
- npm run install
- npm run start // files build to the public directory

### One package.json script to run
- npm run css
  - for just css
- npm run start 
  - starts server on http://localhost:8999
  - run npm-watch for any changes to the sas files 

### Goals
To provide the basics for:
- sass
  - sass provides a basic grid, variables, and mix-ins

### Sass Files
- main.scss:_
  - gathers the files used in compiling and provides the basic grid setup
- common/\_grid:_
  - is just that
- common/\_main:_
  - is styles that apply to all domain
    * edit to meet your needs
- vars/\_var:\_
  - holds the grid setup, color, font, etc. variables
    * edit to meet your needs
- vars/\_mixes:\_
  - some sample mix-ins are provided
    * edit to meet your needs
- domain/... 
  * provides a start for all domains... the idea is to be able to target things by commenting out what is not needed in the top maim.scss

:construction: Under construction :construction:

### Lightbike is an asset budget auditing CLI tool
Using Lightbike is easy. Most of the work is setting up your configs. Then you simple invoke the lightbike command
`lightbike <pathtoconfig>/config.json`

Example output  
![alt tag](http://i.imgur.com/AhdOP20.jpg)


### Installation
  - install chromedriver:     `brew install chromedriver`
  - install browserser time:  `npm install browsertime -g`

### Develop:
  - `brew install chromedriver` (or any other selenium drivers + host browser)
  - `npm install browsertime -g` (sorry, it's a cli, thus needs manual global install)
  - `npm link` (symlink to binary so the cli is available while developing)

Basic setup of sass in Linux platefor using node.js
-- Install sass on bash terminal
$sudo npm install node-sass -g
super user do by node package manger install node-sass package globally noet for the current directory

-- Compile sass file into css file 
$node-sass --include-path scss input.scss output.css

-- Compile formate of sass file into csss
nested, extended, compact and compressed
eg. node-sass --output-style compressed main.sass main.css

-- view sass output to terminal
$npm-sass --output-stye extended main.css

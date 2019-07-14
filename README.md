# Camp schedule generator

Uses a simple template to generate text for the camp schedule from a configuration file.

## To use:

0. Have a terminal with node.js installed running, and `npm install` in this folder.
1. Edit `config.json` for that year's details.
2. In the terminal, run `npm start`.
3. The resulting `schedule.txt` is the text body for use in the camp program.

## To edit the template:

Edit the `template.stache` file. It uses the [mustache templating language](https://mustache.github.io/mustache.5.html), which is very simple and easy to pick up.


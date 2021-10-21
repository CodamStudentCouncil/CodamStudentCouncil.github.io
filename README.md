# CodamStudentCouncil.github.io
https://codamstudentcouncil.github.io/

Styles are generated with the help of [tailwindcss](https://tailwindcss.com/)

The file `css/tailwind.css` should be fine to get us going. But if the css needs to be regenerated you'll need to install some stuff:

To use, make sure you have [nodejs](https://nodejs.org/en/)/[npm](npmjs.com/) installed
If you don't have it installed, I would highly recommend [nvm (node version manager)](https://github.com/nvm-sh/nvm). A nice tool that allows you to quickly install and use different versions of node via the command line.

If/when you have npm installed you can type `npm install` in the root of the repo, which will create a node_modules directory and installs all things needed to create tailwind stuff.

After that you can do:
`npx tailwindcss -o css/tailwind.css`
This will create a new "clean" tailwind.css file in the css directory

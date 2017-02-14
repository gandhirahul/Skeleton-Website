# Skeleton-Website
A skeleton for website development

Steps to create a "skeleton" website using the Express Application Generator tool

1. npm install express-generator -g
2. express
	( You can also choose a view (template) engine using --view and/or a CSS generation engine using --css)
  	example: express express-learning-tutorial --view=hbs
3. cd express-learning-tutorial
4. npm install
5. npm install --save-dev nodemon
6. Update the package.json with this code.
	"scripts": {
	    "start": "node ./bin/www",
	    "devstart": "nodemon ./bin/www"
	  },
7. On Windows, use this command: SET DEBUG=express-learning-tutorial:* & npm run devstart 
   On Mac OS X or Linux, use this command: DEBUG=express-learning-tutorial:* npm run devstart
   or simply use npm devstart
8. Load http://localhost:3000/ in your browser and enjoy !!!


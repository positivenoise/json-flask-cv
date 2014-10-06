JSON-Flask-CV
=============

A CV dynamically generated from a JSON file, hosted with Flask with the Bootstrap template, outputting to .PDF .DOCX .JSON and .XML file formats.

See an example at http://brendan-muscat-cv.herokuapp.com
###Command line to deploy to heroku:

* git clone https://github.com/positivenoise/json-flask-cv.git
* cd json-flask-cv.git
* heroku create
* git push heroku master
* heroku open

###TODO LIST:

* Include tutorial to create your own CV
* Load background images for main page from JSON
* Add SEO elements
* Include better instructions for Heroku deployment (git, heroku-toolbelt)
* Update styles in template.docx
* Try to implement automatic pages (so sections don't overlap)
* Add examples to deploy to other scenarios
* Add Apache integration

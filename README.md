JSON-Flask-CV
=============

A CV dynamically generated from a JSON file, Hosted with Flask with the Bootstrap template, outputting to .PDF .DOCX .JSON and .XML file formats.

See an example at [http://brendan-muscat-cv.herokuapp.com]{http://brendan-muscat-cv.herokuapp.com}

###Command line to deploy to heroku:

* git clone https://github.com/positivenoise/json-flask-cv.git
* cd json-flask-cv.git
* heroku create
* git push heroku master
* heroku open

###TODO LIST:

* Update README.md
* Include tutorial to create your own CV
* Fix DOCX generation of links
* Load background images for main page from JSON
* Add SEO elements
* Add Google tracking
* Include better instructions for Heroku deployment (git, heroku-toolbelt)
* Update styles in template.docx
* Try to implement automatic pages (so sections don't overlap)
* Add examples to deploy to other scenarios
* Add Apache integration

JSON-Flask-CV
=============

A CV dynamically generated from a JSON file, Hosted with Flask with the Bootstrap template, outputting to .PDF .DOCX .JSON and .XML file formats

###Command line to deploy to heroku:

* git clone https://github.com/positivenoise/json-flask-cv.git
* cd json-flask-cv.git
* heroku create
* git push heroku master
* heroku open

###TODO LIST:

* Update README.md
* Include better instructions for Heroku deployment (git, heroku-toolbelt)
* Fix styles in template.docx
* Try to implement automatic pages (so sections don't overlap)
* Add examples to deploy to other scenarios
* Add Apache integration

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

* Add Upload file function
* Remove resume.json from default repo, and have user setup and deploy to heroku button on main page if resume.json not detected. 
* Load background images for main page from JSON
* Add SEO elements
* Update styles in template.docx
* Try to implement automatic pages (so sections don't overlap)
* Add examples to deploy to other scenarios
* Add Apache integration


.PHONY: less

install:
	bower install

server:
	jekyll server --watch --baseurl=

less:
	lessc less/mf.less css/mf.css --clean-css

css: less

dist:
	cp -R bower_components/font-awesome/fonts .
	cp bower_components/bootstrap/dist/js/bootstrap.min.js js
	cp bower_components/jquery/dist/jquery.min.js js
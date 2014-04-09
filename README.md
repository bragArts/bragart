## bragart
bragart is minimalist Python personal portfolio app with an easily-customizable, responsive 
[Bootstrap 3](http://getbootstrap.com/) UI. Built on [Simple](https://github.com/orf/simple).

A final project for [silshack Spring 2014](https://github.com/silshack/spring2014), a course in UNC-Chapel Hill's School of Information &amp; Library Science.

#### bragart is right for you if...
You're an IT professional, designer, developer, or anyone else who needs a portfolio of your work in order to land a good job.

You have at least moderate familiarity with Python, GitHub, jQuery, CSS, and HTML. The bare-bones installation of bragart is fairly light on code, but you'll want to use all your skills to make your portfolio your own and show off your creative side.

### About
bragart is built on Simple--a light weight Flask-based blog app--and designed specifically for use as a personal portfolio. Like Simple, bragart just needs Flask, Sqlalchemy, and Markdown. Easy to install, easy to add project information, easy to customize. Out of the box, you get a very vanilla interface based on Bootstrap 3. 

***

### Features
  - Markdown
  - Drag &amp; drop uploads
  - Vanilla Bootstrap 3 responsive interface
  - Lightweight admin UI for project post creation and updating

***

### Installation
  - Download Python 2.7+
  - Clone this repository: `git clone https://github.com/bragArts/bragart.git`
  - From your shiny new repository, run: `pip install -r requirements.txt`
  - Create a new settings file using: `python create_config.py`
  - See your new portfolio in action: `python bragart.py`
  - Visit your admin dashboard to create your first project post at /admin

#### Updating
If you need to start over with your settings, just run `python create_config.py --fresh`

#### Contributing

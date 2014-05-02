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

### Installation
  - Download Python 2.7+
  - Clone this repository: `git clone https://github.com/bragArts/bragart.git`
  - From your shiny new repository, run: `pip install -r requirements.txt`
  - (Optional) Create your resume in a Google Drive doc. Later you can embed that document in your portfolio if you so choose.
  - Create a new settings file using: `python create_config.py`
  - See your new portfolio in action: `python bragart.py`
  - Visit your admin dashboard to create your first project post at /admin

#### Updating
If you need to start over with your settings, just run `python create_config.py --fresh`


## Contributing

Want to help us out? That's swell. All skill levels are appreciated. Tackle something from the list below, or head
over to milestones &amp; issues to see what else needs to be done.

Here's a list of improvements we'd like to make in the near future.

#### Edit about page through admin UI
It'd be nice to allow people to edit their about page content through the admin UI. We have a static box in 
the UI just waiting to be hooked up. It looks pretty, but right now it doesn't do anything.

#### Responsive optimization
Currently, bragart out of the box looks pretty ok on smaller devices. But Bootstrap packs a lot of responsive power, 
and our mobile designs could be better.

#### Sorting projects by category
We'd like to get some taxonomy for our projects by adding the ability to assign each project to a category (like
Web Design, Python, Wireframes, whatever floats your professional boat). Ideally, this would allow 
the projects to be sorted by category on the front page of the portfolio.

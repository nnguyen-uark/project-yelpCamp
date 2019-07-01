# yelpCamp

version 2
branch: mav2mongoosester
new technology: mongoose, RESTful 
technology: mongoose, RESTful, bootstrap, nodejs, expressjs

---------------
Note: 
- (git) if we make a change in branch2, but not stage/commit, you will lose all the changes if you switch to other branches
- (mongoose) Cat.find returns array, whereas Cat.findById return 1 object

---------------
YelpCamp: Adding Mongoose	
- install and configure mongoose {localhost/yelp_camp}
- setup campground model {schema, model}
- use campground model inside of our routes {app.get(‘/campgrounds), app.post(‘/campgrounds) }

YelpCamp: Campground Show Page
- add mongoose db to yelpcamp
- define the RESTful api {
1. INDEX	/index  		GET
2. NEW   	/camgrounds/new	GET
3. CREATE	/camgrounds		POST
4. SHOW	/campgrounds/:id	GET
}
- add description to our campground model {campgroundSchema, recreate collection}
- add a show route/template {app.get(/camgrounds/:id)…rename to campgrounds.ejs, button on index.ejs, build campgrounds.ejs, update new.ejs}

---------------------------------------------
version 1
branch: master
technology: bootstrap, nodejs, expressjs

---------------
YelpCamp: Initial Routes	
- add landing page {app.get(‘/’), … landing.ejs}
- add campgrounds page that lists all campgrounds {app.get(‘/campgrounds), …campgrounds.ejs}

YelpCamp: Layout	
- create our header and footer partials
- add in bootstrap

YelpCamp: Creating Campgrounds	
- setup new campground POST route {app.post(‘/campgrounds), …campgrounds.ejs, app.get(/campgrounds/new)…new.ejs}
- add in body-parser
- setup route to show form
- add basic unstyled form

YelpCamp: Styling Campgrounds	
- add a better header/title {campgrounds.ejs, jumpbotron}
- make campgrounds display in a grid

YelpCamp: Styling Nav and Forms	
- add a navbar to all templates

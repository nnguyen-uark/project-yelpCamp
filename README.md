# yelpCamp

version 9
- branch: v9campgroundUser
- new technology: data associations (save author’s name to campgrounds automactically)
- 4 terminals: mongod, nodemon, mongo for debug database, and 1 free terminal
---------------
YelpCamp: User Associations: Comment	Users + Comments
- associate users and comments {
 + comment out comment section in seeds.js
 + modify commentSchema…author has id- Referencing data and username
 + modify routes/commentRoutes.js router.post(/)
 + modify comment display in /views/campgrounds/route_show.ejs
 + remove author field from the form /views/comments/new.ejs}
- save author’s name to a comment automactically

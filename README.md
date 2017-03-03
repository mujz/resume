# Mujtaba Al-Tameemi’s Résumé
# Basics:
* Email: mujtaba.altameemi@gmail.com
* phone: 604-355-7532
* website: https://mujz.ca
* GitHub: https://github.com/mujz
* Education: B.A. Computer Science, Simon Fraser University (Jan 2016 - Apr 2018)

# Professional Experience
### Full-Stack Web Developer @ Change Heroes (Nov 2015 - Nov 2016)
* Built a friend-to-friend fundraising platform with AWS (mostly ECS, ELB, and RDS), Docker, PostgreSQL, Node.js, AngularJS.
* Since I was the only one in the team who knew Docker, I set up our continuous delivery and zero-downtime process using Docker, Webpack, and CircleCI for building and testing, AWS ECS and ELB for hosting, managing, and load balancing the cluster. I was also in charge of getting the developers' environments set up with Docker.
* I owned the server-side code, which includes a Node.js server for the API, PostgreSQL server running on AWS RDS for the database, and an NGINX server for reverse-proxy and static hosting of the AngularJS app.
* The NodeJS server handled authentication, external REST API to the database, email notifications, very fast search using pg-search library (more details about this in the JavaScript section), payment processing with Stripe, and metrics.
* Among the main things that I spent a lot of time on are validation and security of REST API, architecture of the Node.js app, AngularJS app, and the database, and optimization and speed

# Projects
## JavaScript (Node.js):
### pg-search ([Source](https://github.com/mujz/pg-search-sequelize))
_Very fast PostgreSQL database search._
* 325 NPM installs
* Uses postgres' full-text search, materialized views, and gin indexing to implement the fast search; and sequelize for the NodeJS ORM.

### mocha-apiary-reporter ([Source](https://github.com/mujz/mocha-apiary-reporter))
_Mocha reporter that generates API documentation in the apiary style._
* 1,581 NPM installs

## Go
### sync-push ([Source](https://github.com/mujz/sync-push))
_Blazing fast file syncing tool from one machine to another._
* Watches the specified directory and syncs it with the remote, using rsync, when changes are made.
* uses goroutines for concurrency and speed.
* Uses “debounce” to make sure that if multiple changes occur within 100 milliseconds, only sync once using the latest changes.

## Android
###  Qalami ([Play Store](https://play.google.com/store/apps/details?id=co.mujz.qalami)) ([Source](https://git.mujz.ca/mujz/qalami))
![Qalami Screenshot 1](https://lh3.googleusercontent.com/upP4vwMEduvRSba4j_vqRwTVsg0N-ZCGTkeVwcYME25eFeG6fphSxU1EsMw3EwezV3cP=h310-rw) ![Qalami Screenshot 2](https://lh3.googleusercontent.com/w0olcXI9CozrAr3J8xJ7rk1e_TEdG6To3doldRJUa__ON6VboCxQuqVlKJUFuKZrLyI=h310-rw)  ![Qalami Screenshot 3](https://lh3.googleusercontent.com/bOHNsAFyabnFtw0HphWa2mzgsudiw1PistIFZ4GHchjMOAQOy-k5l1SX_rbBJCGReYhk=h310-rw)

_Offline-first android app for my personal blog._  
* Sync local sqlite database with the remote Tumblr blog (mujzuh.tumblr.com) using a background service and Tumblr's RESTful API.
* Fast post search at the database level
* Send push notifications using Parse

### Yalla Nrooh ([Play Store](https://play.google.com/store/apps/details?id=co.mujz.yalla)) - ([Source](https://git.mujz.ca/mujz/yalla))
![Yalla Screenshot1](https://lh3.googleusercontent.com/GJqt45DEx6l5EyAoSj4dA5HSdjk0LUBNpCGm9HBt21drPKwtVaCmXioMts-Vf2nB3CE=h310-rw) ![Yalla Screensht 2](https://lh3.googleusercontent.com/BvPZCuecsrjgzNy_XQ7j45xKpqR30iYHfNOKfD1xKdF_ubNOke9_WdwNFj_ZumwarQ=h310-rw) ![Yalla Screensht 3](https://lh3.googleusercontent.com/qHanO6TYzx-HEPu39GFW3l47TBd6PvwqStEQCTQhWhlyPNeEHRnOAsRp6p2SjggEdQ0=h310-rw)

_Carpooling android app for local events._
* Clean user interface following Google's material design guidelines. A lot of work went into optimizing the ui to make it simple, beautiful, and compatible with the various screen sizes and Android versions.
* MongoDB and Parse on the backend

### JoCinemas
![JoCinemas Screenshot In Theaters](/Nexus_5-1.png) ![JoCinemas Screenshot Movie Details](/Nexus_5-2.png)

_Movie showtimes android app for Amman, Jordan._ [Play Store](https://play.google.com/store/apps/details?id=co.mujz.jocinemas)  - [Source](https://git.mujz.ca/mujz/JoCinemas)
* Parse HTML to get showtimes, OMDB's REST API for additional details on movies.
* Cache locally using sqlite database. only fetch if remote is different from local

## C
### Unix Shell
Wrote, and memory tested, a basic shell with a history feature using only the standard C libraries.

### Linked Lists
A library that implements the basic functions of linked lists.

# Volunteer Experience
## Fikra Space (Sep 2012 - Oct 2013): Cofounder ([Website](https://www.facebook.com/FikraSpace))
_The first hackerspace in Baghdad, Iraq._
* Held weekly workshops and build nights. I did all of the orginizational work, such as logistics, website and social media, online community engagement, etc.
* Taught workshops on Android app development, and workshops on getting started with Arduino.
* Helped some of the members with their projects, such as an RC car controlled by Android over bluetooth.

## Startup Weekend Baghdad and Amman (Jun 2013 - Aug 2015): Cofounder
_Weekend-long event for participants to form teams and turn their ideas into startups._ [Website](https://startupweekend.org)
* Organized the events, built the websites and Android apps, and MCed the event

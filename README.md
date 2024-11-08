# capstones

### Abdul
* Create an app that gets neurodivergents to connect
  * Each user has an account, fills in info about neurodivergency, and location
  * Match to other users that are close by and have things in common based on info
  * Tinder-adjacent, can chat after matching, group chat, group meetups, etc (using geolocation)
  * Google Maps API
  * Match API?
  * Other APIs to fill out the neurodivergent tags or JSON list (or create own API)
* Next steps
  * Design (with mind towards a11y)
    * Dark mode available
  * Consider avoid too many 3rd party APIs

### Brian
* Auction platform for art
  * art API to start for access to a collection of art and art descriptions
    * simulate auction on this historical     
  * auction functionality
    * static bidding first (not real-time)
    * real-time if possible
  * websockets (socket.io) - real time data transfer
  * speech recognition to recognize someone's bid (avoid errors in bidding)
* Next steps
  * look into websockets
  * start thinking about design

### Emile
* game. matching game. like cascadia, azul
  * given a set of tiles and you can build your own shape/figure to accumulate points based on position
  * you can play it alone which is good for folks visiting the site
  * step further: multiplayer (websockets?)
  * phaser? library for creating 2d react games
    * wants you to install mamp (like wamp) 
  * could also just make the game using react
* next steps:
  * try out phaser
  * finalize the tiles. use generative AI for the visuals
  * look into drag and drop

### Eric
* howdy!
* search engine that allows people to select specialized products (like semiconductor chips)
  * three pages (SPA)
    *  main page: search engine. find by keyword. left bar: filters (like snaps) by applications, family, lifecycle. main content is all the search results.
    *  item details: click on result to see basic functionality/details. downloading system to get this data sheet for the part
    *  shopping cart (lite): add items to cart, delivery info, no payment (simulated), send to email (to account manager... only for product selection)
    *  TIM: adobe has a tool that converts JSON to PDF fields
*  next steps:
  * frameworks for shopping cart/product filters
  * backend APIs. use hardcoded data to start. once done, serve from backend
  * for the UI, find open source icon collection for industrial icons 

### Ivan
* what's up!
* dogs. interesting dogs. socializing with other dogs to help them handle dog anxieties
  * meet other folks who have similarly anxious dogs
  * preferably 1:1 meetings
  * set up a profile for your dog
  * chat with people whose dogs match yours
  * researched Node+socket.io for chat
  * connect by Google geolocation to people closeby
* Next steps
  * Design
    * like uber? DogX, DogXL, etc.
  * Experiment with socket.io

### Marvin
* User-based meal pinterest-y platform
  * Users will have accounts, each user can post meals and those can be accessed by other users
  * Users can filter meals by
    * vegetarian/vegan
    * healthy
    * calories...
  * Can favorite/follow other users
  * Feature where people can paywall their recipes to other users
  * A user can list all the ingredients they have and then find meals with those base ingredients
  * Yummy.ly API? For nutrition, etc.
  * Integrate with Instacart to order ingredients
* Next steps
  * Think about the design
  * Pinterest vibe
  * Define core functionality and a critical path
  * Look into component libraries

### Mohammad
* hey everyone,
* finance buddy tool
  * assortment of things
  * budget planning
  * based on budget -> let's you know if you should buy something
    * input something from amazon (can you afford it?)
  * autofill taxes. lots of manual stuff for the existing tools out there
  * info about restaurants and things in the area -> determine what you can afford
  * Tim: you can reverse-engineer from existing apps many of this functionality (RBC banking app)
* Next steps
  * how can we differentiate this tool from others?
  * look into how autofilling would actually work

### Tim
* oh boy
* emulate a social media management platform (most existing are b2b)
  * 2-3 functionality
    * integrate tiktok, facebook, instagram, X
    * dashboard to look, post, delete to each of these platforms
  * challenge: lots of tools to use
  * UI will take a backseat, likely will use a mui template
  * would like to mirror to the website within the page (use some sort of state mgmt library. redux? redis? OAuth)
* next steps
  * look at how each of the tools work. start with creating posts (using medium article template)

### Vargio
* interactive map that finds users (musicians, artists, looking to record in a studio) and studios in their city
  * click on a studio to find contact/rates/booking
  * booking happens through this application
  * Google maps API to show studios
  * found similar site before class (but it is unfinished): https://stufinder.com/
* Next steps
  * what does the booking flow look like?
  * 


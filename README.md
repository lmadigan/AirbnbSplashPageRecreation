## Airbnb Splash Page Recreation (front-end demo project)

### Background

Airbnb is an online marketplace that allows users to list properties available for rent, as well as search homes to stay at. Starting out as a networking site connecting renters with property owners, Airbnb has recently started to transition into an all inclusive experience site which, along with available listings, has experiences and featured locations. A selling point to Airbnb has been its incredible UI experience. Building off its easy to use interface with aesthetically pleasing design, I decided to recreate the Home Page with several features aimed at enhancing the user's experience by both capturing attention and creating a more dynamic, interactive user interface.

By recreating the home page, I will implement minor HTML/CSS tricks aimed at enhancing user's experience and encouraging user interaction.

1) Parallax scrolling over Splash page cover photo
2) Hover effect that plays a slideshow of images associated with a given listing
3) Hover effect that rotates experience page 180 degrees to play video of event
4) Hover effect that causes image to play as gif


### Functionality & MVP  

With this Airbnb Splash Recreation, users will be able to:

- [ ] Parallax Scrolling Over Splash Page Cover Photo
- [ ] In "Recently Viewed" section, I will create a hover effect that begins a slideshow of images associated with the given experience
- [ ] In "Experiences" section, I will create a hover effect that causes the display page to rotate 180 degrees on the y-axis to display video of the experience.
- [ ] In "Featured Destinations", I will create a hover effect that will cause the image go from static to gif. Initially these gifs will be gifs found on giphy. BONUS: create simple gifs of animated city views.
  ex: gif of Miami with Miami lights flashing, gif of London with bus driving into the background

  In addition, this project will include:

- [ ] Links to code snippets of each feature
- [ ] A production Readme- with links to code for each of the features

### Wireframes

This user interactive page will be a recreation of the cover page for Airbnb. In the page, I will incorporate functionality to make a more dynamic page to entice users to click various regions and explore further.
 With the use of short animated gifs, photo slide shows, and on hover effects, I plan to demonstrate different tactics, created through HTML5, CSS, and Javascript that can be used to increase user response.

![wireframes](app/assets/images/AirbnbCoverPhoto.png)

### Architecture and Technologies

This project will be implemented with the following technologies:

- Vanilla JavaScript and `jquery` for overall webpage structure and user interaction,
- HTML5 and CSS for interactive elements on the DOM
- Webpack to bundle and serve up the various scripts.
- Cloudinary will be used to host images and videos.
- Photoshop and Illustrator to create simple animated gifs for Featured Destinations

In addition to the webpack entry file, there will be three scripts involved in this project:


### Implementation Timeline

**Day 1**: Setup all necessary Node modules, including getting webpack up and running and `Easel.js` installed.  Create `webpack.config.js` as well as `package.json`.    Goals for the day:

- Get general layout of webpage set with splash photo, "recently viewed" section, "experiences" section, and "featured destinations" section
- Create a parallax scroll effect over the splash photo

**Day 2**: Dedicate this day to learning the `Easel.js` API.  First, build out the `Cell` object to connect to the `Board` object.  Then, use `board.js` to create and render at least the square grid, ideally all 3 grid types.  Build in the ability to toggle the live/dead states on click for each cell.  Goals for the day:

- Complete the `cell.js` module (constructor, update functions)
- Render a square grid to the `Canvas` using `Easel.js`
- Make each cell in the grid clickable, toggling the state of the square on click
- Do the same for triangular and hexagonal grids

**Day 3**: Create the automata logic backend.  Build out modular functions for handling the different grid types along with their unique neighbor checks and rule sets.  Incorporate the automata logic into the `Board.js` rendering.  Goals for the day:

- Export an `Automata` object with correct type and handling logic
- Have a functional grid on the `Canvas` frontend that correctly handles iterations from one generation of the game to the next


**Day 4**: Install the controls for the user to interact with the game.  Style the frontend, making it polished and professional.  Goals for the day:

- Create controls for game speed, stop, start, reset, and shape type
- Have a styled `Canvas`, nice looking controls and title
- If time: include buttons on the side to toggle the color scheme of the cells


### Bonus features

There are many possible areas of improvement for creating a more interactive UI. Some future directions include:

- [ ] Create own gif for "Featured Destinations" section using Photoshop/ Illustrator
- [ ] Continuously playing video for cover splash photo
- [ ] Feature section links to popular things to do rather than listings

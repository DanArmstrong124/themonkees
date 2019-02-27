# The Monkees

In this project I will be designing a user friendly website that allows for anyone to access music, events and some information on the monkees.
It will be using Javascript, Html, CSS and Jquery.

TheMonkees were a 1960's hit band formed of 4 members, fans would use a website like this to find music of theirs, watch footage, and dive into the information and history of what the monkees did and what they became.

For reference to original designs, check out the [WireFrames](https://github.com/DanArmstrong124/themonkees/tree/master/assets/wireframe).
 
## UX
 
- As a monkees fan, I want to hear the music of the monkees on their website, and can achieve this via the music page.
- As a monkees fan, I want to learn more about the monkees on their website, and can achieve this via the about page.
- As a monkees fan, I want to see the music of the monkees live, and can achieve this via the events page.
- As a monkees fan, I want to be able to pay for tickets to the live events, and can achieve this through the more info buttons on the events page.

## Features

My website will have 5 pages, each with a header, a main section and a footer.
A small alert bar will be on the top of the page allowing for users to know any brand new information, or to point them in a direction.

the 5 pages are:

- Home page: basic info, the names of the members in the Monkees etc.
- Events page: Will have events "Near" you, and events globally.
- Music page: Will have the music uploaded in MP3 and MP4 formats for the user to listen to.
- About page: Will have a more detailed description of who the monkees are and what they do.
- Contact page: Will have a form that a user can fill out to get in touch.
 
### Existing Features
- Home page - the users first impression on the site.
- Alert bar - helps give the user some direction or updates them on news.
- Header - holds the menu, which shrinks into a smaller symbol for mobile devices.
- Footer - holds copyright, a small contact us and social links.
- Social links - 3 links which a connected to send the user to the Twitter, Facebook or Youtube of the monkees via a new tab.
- Hover - around the site, I have implimented minor hover states on buttons.
- Mini-about - This is info on the monkees in less detail.
- Scroll-Bar - This can be found on the mini-about feature, and is implimented through overflow.
 
- Events page - Where the user can find TheMonkees future events.
- Modal - This pops up when the user interacts with the more info button.

- Music page - Where the user can find TheMonkees audio and videos.
- Video - The user can access a video of TheMonkees music.
- Audio - The user can access 4 audio (mp3)'s of TheMonkees music.
- Spotify link - The user can access TheMonkees music via the spotify link.

- About page - Where the user can find more information about TheMonkees.

- Contact page - Where the user can submit a form to TheMonkees.

### Features Left to Implement
- History of TheMonkees?
- Validation
- Testing of the Site
- Finished README.md
- fix submit button

## Technologies Used

- [Balsamiq](https://balsamiq.com/wireframes/desktop/#)
    - The project wirefram was created on **Balsamiq**.

- [HTML](https://en.wikipedia.org/wiki/HTML)
    - The project uses **HTML** for the website to be developed.

- [CSS](https://en.wikipedia.org/wiki/CSS)
    - The project uses **CSS** to give it customised design, responsive design, media quieries etc.

- [Boostrap](https://getbootstrap.com/docs/3.4/getting-started/)
    - The project uses **Bootstrap** such as CSS and Javascript bootstrap for simplified responsive design.

- [JQuery](https://jquery.com)
    - The project uses **JQuery** to simplify DOM manipulation.


## Testing

1. Contact form:
    1. Go to the "Contact Us" page
    2. Try to submit the empty form and verify that an error message about the required fields appears
    3. Try to submit the form with an invalid email address and verify that a relevant error message appears
    4. Try to submit the form with all inputs valid and verify that a success message appears.

2. Video player:
   1. Go to the "Music" page
   2. Press play on the MP4 video player
   3. Try to get the video to enlarge
   4. Try to get the video to fast forward/rewind
   5. Try to pause and re-play the video

3. Audio players:
   1. Go to the "Music" page
   2. Click the play button on the spotify IFrames
   3. Click the pause button on the spotify IFrames

4. Information on the monkees:
   1. Go to the "Home" page
   2. Try to scroll down the information below the image of the monkees
   3. Go to the "About us" page
   4. Try to scroll down the information of each member of the monkees found below the images

5. Events:
   1. Go to the "Events" page
   2. Try and click the more-info buttons under each global events
   3. Try and click the close button on the modal
   4. Try and click the buy tickets button on the modal

6. Responsive Design:
   1. Go through each page using a mobile view, I used IPhone 5
   2. Go through each page using a tablet view, I used X
   3. Go through each page using your standard desktop view

## Deployment

- I used Cloud9 for my website deployment
   1. First I would edit my code
   2. I would then save to Cloud9
   3. I would then hit run at the top of the screen
   4. I would check for errors on the site, ensuring that everything is working
   -  If there are any erros I would go back and resolve them, and start from step 1
   -  If I was struggling to find the 'Website Breaking' code, I would use validators which are *referenced in the credits* to locate it, and start from step 1
   5. Using Git I would push my code to GitHub to ensure it is backed up online


## Credits

### Content
- The events were found online, using this webpage: [AXS](https://www.axs.com/uk/artists/112952/the-monkees-tickets).
- I re-taught myself how to insert videos using an external website [W3S](https://www.w3schools.com/html/html5_video.asp).
- Davy Jones info from [WIKI](https://en.wikipedia.org/wiki/Davy_Jones_(musician)).
- Michael Nesmith info from [WIKI](https://en.wikipedia.org/wiki/Michael_Nesmith).
- Mikey Dolenz info from [WIKI](https://en.wikipedia.org/wiki/Micky_Dolenz).
- Peter Tork info from [WIKI](https://en.wikipedia.org/wiki/Peter_Tork).
- TheMonkees info from [WIKI](https://en.wikipedia.org/wiki/The_Monkees).

### Media
- The photos used in this site were obtained from [GitHub](https://github.com/Code-Institute-Org/project-assets/tree/master/stream-1/band-assets/images).
- The videos used in this site were obtained from [GitHub](https://github.com/Code-Institute-Org/project-assets/tree/master/stream-1/band-assets/video).
- The audio used in this site were obtained from [Spotify](https://open.spotify.com/artist/320EPCSEezHt1rtbfwH6Ck).
- The spotify buttons were obtained via [Spotify API](https://developer.spotify.com/documentation/widgets/generate/play-button/).

### Acknowledgements

- I received inspiration for this project's colour scheme from The Monkees logo found on [Twitter](https://twitter.com/themonkees).
- I received validation of my HTML using this [HTML Validator](https://validator.w3.org/nu/#textarea).
- - Some code is found to be 'Invalid' due to bootstrap being used causing minor errors in the <div>'s etc.
- I received validatoin of my CSS using this [CSS Validator](https://jigsaw.w3.org/css-validator/).
- - Some code is found to be 'Invalid' due to bootstrap being used causing minor errors in the <div>'s etc.
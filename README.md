# Albatross Nepal- A Music Band Website

This is a single page website, to be designed for the fans of the Albatross Nepal Band and the event organizers for our ongoing concerts throughout the world. The fans will be allowed to view the band photos, listen music with their spotify or soundcloud account and watch music videos. They will also be able to contact them in order to organise gigs and any other inquiry.
The initial home page will be used to engage new fans. There will then be anchored links within the same page divided into different sections, for the band's content and other uses. There will be a photos section for their photo collection, a music section for their music catalogue, and a contact option to allow the user to contact the band for their upcoming tour schedules and other information. The website will also be used to promote their social media pages, through the use of external links. 

## UX
As a user, I want to use the website to:
- listen to the bands music and watch videos (should include at least one video clip),
- find links to their social media and other media 
- look at photos of the band on tour and of each individual band member.
- see the bands tour dates and 'availability for booking' and are able to contact the band to organise gigs.
Prior to beginning the project, I first drew a very basic wireframe for the web page. Here are the sketches I drew the following wireframe.
- Wireframe 1
However, during development I made many changes to what was initially planned. While developing the project, I used the Whiskey Drop and Resume projects in the course for design and content inspiration.

## Features
The website will have a header and footer. Between the header and footer, the main body is divided into different sections: about, audio, video, albums, gallery. 
The following points describe the salient features.
- The initial home page will display an animation of the band picture with some other graphics. 
- The about section will contain a brief description of the band with the names of the band members.
- The music section will contain some samples of the of the bands music.
- The gallery section will contain a slide show of a variety of the band pictures.
- The video section will contain a sample music video of the band with a link to other videos included.
- The album section will have the albums created by the band.
Other sections may be added if needed.
 A contact form will pop up when clicked on the contact button on the header.
### Existing Features
#### Header and footer
I used the code from the whiskey drop and resume project for the header and footer sections as a starting point to work from.
I combined the codes from the two projects for the header sections while adding an image of the band’s logo.
The header has internal links to different sections of the website and is fixed, to allow easy access for the users.
The footer has external links where the user can find the band’s content.
##### Future changes
I might have to add more links: external or internal for which I may need to replace the position of the band logo in different place.

#### Initial Home Page
When a user opens the web, the initial page consists of animated band logo and background band image. Also, I decide to add a blinking animation with some text and music logo from fontawesome.
#### Music section
I am using this section to display some sample music. For this, I decided to use their spotify link for larger screen and soundcloud link for mobile devices.
##### Future changes
I might add more features for this section. I might add buttons that provides external links to itunes or other links for the possible purchase.
#### Videos section
I am using this section to display a sample video. For more of the videos, I have provided the link to follow.
#### Albums section
I am using this section to display some music albums. For this, I decided to use the thumbnails of the images of the album and when hovered over, the album image becomes focused.
##### Future changes
I might like to change the way the album image appears on hovering. I might also add external link for the relevant album.


#### Images section
For the photos page I utilized the [bootstrap carousel](https://getbootstrap.com/docs/4.0/components/carousel/). I copied the code and modified according to my need.
##### Future changes
I might change the background and add more images.

#### Tour section
I have used bootstrap grid system to add sample events and availability.
The contact form appears as a pop-up when clicked on enquire button. It contains a simple form consisting of name of the person, email address and the text area for message. It also includes a submit button and a reset button. I have used [bootstrap modal](https://getbootstrap.com/docs/4.0/components/modal/).
##### Future changes
I might add more required form inputs to the form (i.e. locations, dates, type of events) and I might change the design of the tour and dates for hire listings.

## Technologies Used
This project basically uses HTML5 and CSS3. Apart from these, I use [bootstrap classes](https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css) for standard css styles where I have made slight changes where necessary. I also have used [hover.css](https://cdnjs.cloudflare.com/ajax/libs/hover.css/2.1.1/css/hover-min.css) classes for hover effect on the menu items. Besides, I have tried to implement some animation effects using [CSS trick](https://css-tricks.com/) and [animasta](https://animista.net/).

## Testing

I used the following validators to test the code:
- [CSS Validator](https://jigsaw.w3.org/css-validator/#validate_by_input)
- [HTML Validator](https://validator.w3.org/#validate_by_input)

I have tested the webpage using the following:
- Chrome Developer Tools (responsive mode)
- Running the website in different browsers
- Running the website on different devices phones and tablets (apple, android).

## Deployment 
I used GitHub Pages for deployment using my master branch as the source.I first set up a GitHub repository on my GitHub account. I named it 'milestone-project-1'. After my first stage of developing  my website on visual studio, I deployed it to the GitHub repository. I pushed my all files/folders, then set up GitHub as a master branch, allowing it to be used as a GiHub page and the webpage is now hosted on a GitHub page.

## Credits 
### Content
The text about the band was copied from the band's [official website](http://albatross.com.np/). 
### Media
- The band logo and the pictures in the site were obtained from [Google image searches](https://www.google.ie/search?hl=en&tbm=isch&sxsrf=ALeKk02QRigdF6iT5vV2yNbz091xUqyVcg%3A1583107462611&source=hp&biw=1600&bih=789&ei=hk1cXvSTI6TB8gK0l5GIAQ&q=albatross+nepal&oq=al&gs_l=img.1.0.35i39l2j0l3j0i131j0l4.2375.2654..4176...0.0..0.82.174.3......0....1..gws-wiz-img.....10..35i362i39.FvQvAY81mt0).
- The video on the website is embedded from the [band's youtube channel](https://www.youtube.com/watch?v=MryGXRBURgE&feature=emb_logo).
- The music is embeded from [spotify](https://open.spotify.com/album/20n6ddOmfzydLJ7cIzE52I?si=9FKc9_ZMT0-beeKyKkUkXg) and [soundcloud](https://soundcloud.com/albatrossnepal/sets/ma-ra-malai).

## Acknowledgement
I received inspiration for this project mainly from the whiskey drop and resume projects in my course. I also tried to implement some aspects using the [music band website samples](https://www.free-css.com/template-categories/music) I found while searching in google.

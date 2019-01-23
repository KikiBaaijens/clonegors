# Milestone Project 1 - GORS, the band

GORS - Generations Of Rock Society is a cover band without a website. They do have a Facebook page and Instagram, but since
they'd like more gigs, they want a place on the internet where they'll be easily found and contacted.

## UX

The first milestone project has to be about a band. Luckily, I know a band without a website. I contacted them and asked them what they wanted, which
was basicly the same as the project requirements. Based on both, I came to the  following.

### User stories
- As a band, we want to have a place where we can be found and contacted, as we'd like more bookings. We also want to fans to be 
able to find where we play,  introduce ourself and showcase some of our music and videos
- As a rock cover band, we'd like to have a rock look and feel - regarding colours and font type.

- As a fan, I want to be able to find where the next concert will be, preferably with some information on how to get tickets.

- As a venue owner/concert organizer, I want to listen to some music, watch the band perform and contact the band if I think they will do well
on our stage.

More user stories can be found in the document "user stories milestone project gors.docx".

### Design process
With this information, I decided on a simple website.  
A very basic layout can be found in the document "layout ideas website gors.docx".

## Features
- The home page introduces the band, gives a brief history of the band and band members and shows some photos.
- The On tour page shows a list of upcoming concerts, with date/time, location, ticket link (if applicable) and a link to an event page (if applicable).
- The Music page shows an embedded YouTube-video and has some mp3-links.
- The Book us page shows a contact form.

### Existing Features
- The home page - allows fans and booking agents to learn more about the band, by reading the text and seeing the photos
- The On tour page allows fans to find the next concert and booking agents to see how often they perform and when/where, so they can estimate if the band is available on their preferred date.
- The Music page allows fans and booking agents to hear and see the band perform.
- The Book us page allows booking agents to send the band a message.
- The social media links allow both fans and booking agents to see more about the band.
- The navigation links allow visitors to the website to easily find what they are looking for.


### Features Left to Implement
- The contact form doesn't work yet, that has to be implemented.
- If more photos and videos become available, a gallery would be nice.
- If the band decides to sell merchandise, a webshop could be implemented.
- A more elaborate booking form would be good to have if the band is booked a lot more than they are at the moment. A date picker with available dates, a contract page, etc.

## Technologies Used
- Languages used: HTML, CSS. Note: the language tag has been deleted because of malfunctioning of the font type.


### Libraries:
- https://stackpath.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css Bootstrap was used because it simplifies coding.
- https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css Font Awesome was used for some of the symbols.
- https://cdnjs.cloudflare.com/ajax/libs/hover.css/2.1.1/css/hover-min.css This was used to make the navigation do what I wanted it to do.
- https://fonts.googleapis.com This was used to get the Metal Mania font the band liked.

### Tools
I used GIMP to change some of the sizes of the photos and the logo.

### Tips found on the internet
- https://blog.theodo.fr/2018/01/responsive-iframes-css-trick/ to make the iframe responsive.

### Help from others 
I got some help from a fellow student through Slack with a problem of a photo taking up to much width.

## Testing
- The W3 validator was used to check both HTML and CSS. One warning because of the missing lanuage tag - deleted to fix malfunctioning font type.
- The Coverage tab in Dev Tools Chrome was used to check for obsolete CSS.

Note: as this website uses only HTML and CSS and is not hosted on a server, the booking form can't be submitted. Also, the band currently only 
has Facebook, no Twitter, Instagram or e-mail. The links used for those icons are dummies.

As this is a very basic HTML and CSS website, I tested by clicking through the pages and trying every link, video and audio. 
The form was tested as follows:

Go to the "Book us" page
Try to submit the empty form and verify that an error message about the required fields appears
Try to submit the form with an invalid email address and verify that a relevant error message appears
Try to submit the form with all inputs valid - no success message appears, as the form doesn't actually submit, it just passes all tests.

The website was tested on Firefox, Chrome and IE. Also, all screen sizes were tried with Chrome DevTools.

## Deployment
I deployed the project using Git Hub Pages. The link: https://kikibaaijens.github.io/generationsofrocksociety/music.html.

## Credits

### Content
The text for the band page was copied from their Facebookpage.
The photos, songs and video used in this site were obtained from the band.

### Acknowledgements
I received inspiration for the look and feel of this website from Black Sabbath, the early years.
# Olga's bio fashion business lifestyle

Olga Mironova comes from the Ural region in Russia. She has grown up into a family that has been active into the fashion business. 
Her family owns several small to big luxury brands retail stores at her region. She has always been in a close relationship with her family. 
From her early stages, she worked during the summer time on their retail stores in Russia and similar ones abroad in Italy. 
After finishing her fashion studies back in 2012 in Milan, Italy, she entered officially into her family business as a buyer. She is frequently moving between Russia, 
Italy and France for business purposes. Her passion in fashion led her to become a blogger as well for various Russian magazines back in her own country. 

## UX

- The strategy plane: Aim to achieve a website about Olga that shows her biography, business and hobby achievements
  Target audience :
  - People surrounded by the fashion business
  - People that are passionate with fashion 
  - People that are interested or needed (ex. business occasions) to get dressed very elegant

- The scope plane: 
  - Features :
    - An initial hero background image
    - About Olga
    - Display images and lists from her two separate job aspects (fashion business and blogging), accompanied by a short audio
    - Business videos
    - Contact section

- The structure plane: 
  - Info is structured in a standard way (Home, About us, My Galleries, Contact) 
  - A nested dropdown list on My Galleries section (hero's images, lists and videos) : 
    - Group display per user need and interest. Display first images, second lists and final videos as more extended info
    - Two distinct job aspects (fashion business and blogging). Grouped displayed first (fashion business), displayed second blogging (called editorials)

- The skeleton plane: 
  - Navbar info represented from left to right (fixed top horizontal bootstrap) :
    - Two popular google fonts (Open Sans, Roboto) 
    - Text written to the point (one paragraph, descriptions, quotes)
    - Home (hero image)
    - About me (one paragraph, three buttons, one text hyperlink)
    - Contact (four buttons, DM contact form)
  - My Galleries info represented from top to bottom (vertical bootstrap) :
    - Images section (several images, three can be displayed in modal)
    - Audios and List section (two audios, images, lists, quotes, one image hyperlink, one glyphicon tag hyperlink)
    - Videos (two videos, descriptions)

- The surface plane: 
  - Colours : white, blue and red colours and shades to keep intact with the Russian flag
  - Semantic : header, nav, section, article, figure and mark
  - Typography : google fonts and bootstrap libraries like centering or justifying text or labelling like the small tag to demonstrate description
  - Transition method : User cursor pointing to a button (accompanied with an icon from font awesome or bootstrap glyphicon components)

##### User Stories list:
- As a developer :
  - An initial hero image with no text to target the likability scale
  - Divide sections structurally, display more images and less text, to achieve a user not getting tired

- As a user : 
  - I want to see the hero's route in life and personality, have a clear image of the hero and get in touch if so, at a business and/or social level
  - On the about me section
    - I want to see typography and semantic on few words, to capture briefly the hero's personal profile   
    - I would like to see her social network there (apart from the contact section), to achieve instantly a speed of reaching that person on a shared platform

A mockup frame of the website, one could find it at the attached pdf file at the directory mockup_frame. 

## Features


### Existing Features

- Main Navigation bar fixed at the top of every page (UX structure plane) 

- On About Me section :
  - Three buttons concerning the three social networks 
  - Hyperlink text concerning company's webpage (click on XXI BEK VIP text)
 
- On Images section :
  - Click into the first two images (i.e. shop's logo and external overview) to see them in modal
  - Click on the first image from the editorials (i.e. pink image dress) to see it in modal
 
- On Audios and List section : 
  - Two audios concerning indication of list section and hearing from herself, the hero 
  - Click into the last Editorial image (opens a new tab with the person's blog section on that website) and/or icon tag (opens a new tab with the article of the specified image cover) 

- Videos section :
  - Two videos concerning the fashion store business and trend ideas 

- Contact section :
  - One button concerning directing to the company's webpage address 
  - Three buttons concerning the three social networks

---

Currently, the website provides with a very good overview of the person in subject. Additional plans to be implemented in the future would be :

- Make the lists of fashion store and editorial items (Audios&Lists section) more seggregated and detailed (ex. women -> type of shoes -> colours)

- Concerning videos, as they are currently available in Russian, English subtitles to be inserted

- A separate webpage can be created that can host her own internal blogging and share it with others

### Features Left to Implement

- On the Images section, the image modals are implemented solely for three images

- On the Contact section, form has been inserted as a template, its inputs and buttons have been disabled

Going further towards more interactive and backend development, those features could more feasibly be implemented :
(Dynamic modal for several images, Contact form enabled filled and send request)

## Technologies Used

- [HTML5]
    - The project uses **HTML5** to structure the webpages.

- [CSS3](https://github.com/feddieminas/project_om/blob/master/assets/css/style.css)
    - The project uses **CSS3** to style the webpages.

- [Bootstrap CSS & JS](https://getbootstrap.com/docs/3.3/getting-started/)
    - The project uses **Bootstrap 3 CSS** to create navigation bar, forms, text and display classes. The **Bootstrap 3 JS** to enable functionality of dropdown and modal images.
    
- [Font Awesome](https://fontawesome.com/v4.7.0/)
    - The project uses **Font Awesome** to insert icons for a user friendly visualisation and navigation. 

- [Hover.CSS](http://ianlunn.github.io/Hover/)
    - The project uses **Hover CSS** to style the navigation bar and dropdown hover over.  

- [JQuery](https://jquery.com)
    - The project uses **JQuery** to enable functionality of dropdown and modal images.

- [Chrome DevTools](https://developers.google.com/web/tools/chrome-devtools/)
    - The project uses **Chrome DevTools** to simplify editing pages on-the-fly and assist you to responsive design. 
    

## Testing

- Navigate through the main navigation bar at all html sections per html section that points to the correct webpage address
  - Google fonts and style.css are hooked 
  - Control that dropdown list and hover.css are inserted at all pages
  - Inserted a link to the home page (index.html) at the Website Name for user flexibility

- All images have been inserted and no duplicated image appears. Same for all audios and videos and that can be played

- Concerning colour coding, Navbar colour is close to blue and is transparent at the hero image. Related colour appeals to its job aspect (a white to grey colour for the
fashion stores, a red colour for the editorial section). Active navigation classes are there highlighted per current section  

- Concerning text, I tested that could be readable in small and in any larger device. In addition, to be linear with any header or other text and components associated

- Used Chrome Dev tools for responsive design
  - On each page I have always resize the screen from big to small and vice versa
  - Passed through all devices to see that the content is visible and orientated 
  - Media queries : Text that on large devices might seem small, I enlarged the font size. In addition adjust also for flex on images and "hamb" button

----

Encountered issues : 
- Audio buttons are displayed differently on each browser. I find out an article about solving this issue but it is still displayed the same to me. The link article found was at [stackoverflow](https://stackoverflow.com/questions/24881807/html5-audio-on-safari-ios). I then inserted both an
mp3 and ogg audio for browser compatibility if any playing issue might occur
- Fashion list (mygalleries_audioslists.html) to make it responsive, as it was a background image and an inner list on a section. Thus when you resize the screen to see that it flows at a proper way
- Spent time with the main navbar and the dropdown list to structure the colour, hierarchy and pseudo elements

## Deployment

I deployed the project on Cloud9 platform. I used Git & GitHub for version control. I maintained the master as the only git branch. 
At the branch, structurally, I had the folder called assets where I stored my stylesheet (style.ccs), images, audio and videos. The number of html files created were six (one for each webpage).

Running the code locally is a fairly standard procedure. One could run either of the html files (ex. index.html) and proceed to the navigation bar to browse to the other sections. Each section has the navigation bar on top.

## Credits


### Content

- Text for all sections have been self inspired.

### Media

- The photos, audios and videos used in this site were obtained from the person itself (i.e. Olga), who is the main topic of this project.

### Acknowledgements

- I received inspiration for this project from the person itself (i.e. Olga), who is the main topic of this project.
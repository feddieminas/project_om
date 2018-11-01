# Olga's bio fashion business lifestyle

Olga Mironova comes from the Ural region in Russia. She has grown up into a family that has been active into the fashion business. 
Her family owns several small to big luxury retail stores at her region. She has always been in a close relationship with her family. 
From her early stages, she worked during the summer time on their retail stores in Russia and similar ones abroad in Italy. 
After finishing her fashion studies back in 2012 in Milan, Italy, she entered officially into her family business as a buyer. She is frequently moving between Russia, 
Italy and France for business purposes. Her passion in fashion led her to become a blogger as well for various Russian magazines back in her own country. 

## UX

- The strategy plane: Aim to achieve a website about Olga that shows her biography, business and hobby achievements. Herself, it is a very interesting person that
has dedicated her time and willingness to service the society not only with goods but also sharing her personal knowledge and experiences through her hobby (i.e. blogging). The target audience would be
people surrounded by the fashion business, people that are passionate with fashion; people that are interested or needed (ex. business occasions) to get dressed very elegant.

- The scope plane: Features are an initial hero image, about Olga, display images from her two separate job aspects (fashion business and blogging), lists of luxury goods and editorials accompanied 
by a short audio, fashion business videos (editorial not realised yet) and a contact section (business address, social networks and direct message web form).  

- The structure plane: The information is structured in a standard way (Home, About us, My Galleries, Contact) with a nested dropdown list on My Galleries section. This one section was chosen to be a nested list
to distinct the hero's images, lists and videos to reduce complexity. At these inner sections, as there are two distinct job aspects (fashion business and blogging), it is logically grouped that her majority part of
hero's daily routine should be displayed first (fashion business) and blogging (called editorials) as the second part. In addition, the images section at the dropdown should come first for the user to see
and the lists of the hero's goods is selling or blog magazines that is writing should come after (audios and list section). Videos should be the final part that is more extended info, meaning that the user
has already a clear picture of the hero. Finally, the "burger" button appears on small devices.   

- The skeleton plane: Info to be represented from left to right and as a step process in a popular google font and text written to the point. The user to navigate from the fixed bootstrap navbar (horizontal) from 
the top (Home, About Me, My Galleries, Contact). My Galleries has a dropdown list (vertical) with Images, Audios and Lists, and Videos, from top to bottom. People can view, read, listen to the audios and videos,
press also some images (three can be seen in modal, fourth is a hyperlink) and click on button tags (three social links, fourth is a hyperlink). The hyperlinks direct you to weblinks concerning the hero's lifestyle.

- The surface plane: Concerning colours, maintain white, blue and red colours and shades to keep intact with the Russian flag, the country where he hero is coming from. 
Use semantic elements as header, nav, section, article, figure and mark, typography from google fonts and bootstrap lib like centering or justifying text or labelling like the small tag to demonstrate description.
The design was helping the three distinct colours and shades for a user to understand the different sections and purposes and at the same time to seem clear and friendly. 
Used transition method when a user is cursor pointing to a button (accompanied with an icon from font awesome or bootstrap glyphicon components). 

##### User Stories list:
- As a developer, I want to have an initial hero image with no text written to target the likability scale of any user entering the webpage.   
- As a developer, I want to have less text and talk more through images, to achieve a user not getting tired.
- As a developer, I divide the sections structurally to achieve a person not getting confused of hero's life image routine and details. Maintain a concept from left to right (or top to bottom).  
- As a user, I want to see the hero's route in life and personality to get in touch, whether via a social network or through the direct messaging web form 
  at a business and/or social level. My goal to achieve is that the website and its sections corresponds to me having a clear picture of the hero.
- As a user, having read the about me section, I would like to see her social network also that section (apart from the contact section), to achieve instantly a speed of reaching that person on a shared platform.
- As a user, at the galleres section, I prefer to see several images first to have a clear overview and then proceed to the lists that contains more detail.

A mockup frame of the website, one could find it at the attached pdf file at the directory mockup_frame. 

## Features


### Existing Features

- Main Navigation bar at the top of the page where one could go to the various webpages (Home, About Me, My Galleries (Images, Audios, Videos), Contact)

- On About Me and Contact section, there are three buttons where one could go through the person's three social networks. 
 
- On Images section, one could click into the first two images (shop's logo and external overview) to see them in modal. In addition, one can click on the first image from the editorials to see them in modal.
 
- On Audios and List section, there are two audios to play concerning indication of list section and hearing from herself, the owner. In addition, one could click into the last Editorial image and/or icon tag. 
  Clicking on the image, it opens a new tab with the person's blog section on that website. Clicking on that inner button tag at the thumbnail caption, it opens a new tab with the article of the specified image cover. 
  In both sections, you will find the related lists accompanied by some quotes, self-inspired by the owner.

- Two videos to play at the Videos section concerning the fashion store business and trend ideas, followed by a short description. 

Currently, the website provides with a very good overview of the person in subject. Additional plans to be implemented in the future would be to make the lists of fashion store 
and editorial items (Audios&Lists section) more seggregated and detailed (ex. women -> types of shoes -> colours). A good idea could be using for ex. the list affix scrollspy method. 
Concerning videos, as they are currently available in Russian, English subtitles to be inserted. Finally, a separate webpage can be created that can host her own internal blogging
and share it with others. At that page media bootstrap objects can also be implemented.

### Features Left to Implement

On the Images section, there is the image modal implemented solely for three images. The Contact form has been inserted as a template, but its inputs and buttons have been disabled.

Going further towards more interactive and backend development, those features could more feasibly be implemented (Dynamic modal for several images, Contact form enabled filled and send request).

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

Navigate through the main navigation bar at all html sections per html section that points to the correct webpage address. At the same time, for instance I was controlling that I have inserted
the hover.css button at all pages to maintain consistency and provide reliability. Finally, also make sure it is inserted a link to the home page at the Website Name for user flexibility.  

Checked that all images have been inserted and no duplicated image appears. Control that all audios and videos can be played.

Concerning colour coding, navigate through all sections from left to right and see that is linear to all sections and it appeals its related colour to its job aspect (a whiter to grey colour for the
fashion stores, a red colour for the editorial section). Navbar colour is close to blue and is transparent at the hero image

With regards to text, I tested that could be readable in small and in any larger device. In addition, to be linear with any header or other text and components associated. 

Used Chrome Dev tools for responsive design. On each page I have always resize the screen from big to small and vice versa to capture that my code is structured in a non distructive manner. I passed
through all devices then to see that the content is viewed and relatively cleared. Then for ex. some text that on large devices might seem small, I enlarged the font size. Same media query adjust also for flex on images
and "hamb" button.

An interesting issue that it came was that the audio buttons are displayed differently on other browsers, I tried it for ex. in Safari. Though the audio is playing. I find out an article about
solving this issue but it is still displayed the same to me. The link article is [stackoverflow](https://stackoverflow.com/questions/24881807/html5-audio-on-safari-ios). However, I inserted both an
mp3 and ogg audio for browser compatibility if any issue might occur and mp3 is not supported.
Another issue I encountered was with the Fashion list (mygalleries_audioslists.html) to make it responsive, as it was a background image and an inner list on a section. Thus when you resize the screen to see that it flows at a proper way.
Finally, I spend time with the main navbar and the dropdown list to structure the colour, hierarchy and pseudo elements.  

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
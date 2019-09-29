---
title: "Creative Making: Design and Coding Visuals"
author: "Irene Fubara-Manuel"
date: "September 26, 2019"
presentation:
  theme: black.css
  width: 1280
  height: 800
  margin: 0.3
  showNotes: true
  enableSpeakerNotes: true
---

<!-- slide data-notes="Manual attendance"-->
![](https://68.media.tumblr.com/cdd0edbc7a7c21c1dc3dafa8b446d2d7/tumblr_o4tjs8Frc91r82eito1_500.gif){height="35%" width="35%"}

# Creative Making: Design and Coding Visuals
Instructor: Irene Fubara-Manuel  
Week 1


<!-- slide data-notes="Presentation outline"-->
## TODO
+ Introductions to each other and the course
+ A cursory history of new media art
+ Introduce p5.js and Lauren McCarthy
+ Principles of design in 'sketching with code'
+ Workshop introducing p5
+ Assignment and next week's class

<!-- slide vertical=true "If you have coded have you used js or p5/processing"-->
## Introductions

+ Name & pronouns?
+ Have you coded before?
+ What are your interests in coding?

<!-- slide vertical=true -->
## Syllabus Overview

+ Module Outline
+ Contact Hours
+ Brief + Assessment
+ Assigning weeks for presentations
+ Class format
+ Dates (TBA)

<!-- slide vertical=true data-notes=
"Write/type down the responses"
-->
## Rules of Engagement
How can we make/keep this environment  
safe and productive for everyone?

<!-- slide data-notes=
"Newness is subjective. For Digital art curator Christiane Paul this newness is characterized by the 'fleeting' nature of the technologies. There is a joke in media studies about the development of new technologies moving from beta stages to obsolete".-->
| | |
|---|---|
|![](https://proxy.duckduckgo.com/iu/?u=https%3A%2F%2Fcdn.taschen.com%2Fmedia%2Fimages%2F960%2F25_art_new_media_kr_gb_3d_41923_1503121842_id_910782.png&f=1&nofb=1){width="70%"} |*projects that make use of emerging media technologies and are concerned with the cultural, political, and aesthetic possibilities of these tools.*|
|--- Jana and Tribe (2006, p.6)|  |

<!-- slide vertical=true data-notes=
"New media art is difficult to define, this is highlighted firstly, in the ways curators and artist in this field refer to their practice."-->
## New Media is 
+ Digital art
+ Electronic Art
+ Video Art
+ Net Art
+ Game Art
+ Performance Art...

<!-- slide vertical=true data-notes=
"The difficulty of defining new media art also lies in its many influences. The earliest of these influences is the kinectic art of the Dada movement. Characterized by [Marcel Duchamp's Fountain (1917)](https://upload.wikimedia.org/wikipedia/commons/d/dd/Marcel_Duchamp%2C_1917%2C_Fountain%2C_photograph_by_Alfred_Stieglitz.jpg), Dada artists made works in response to nationalism and WWI. Dada was an anti-art movement as it eschewed beauty and reason for  randomness and irrationality."-->
![**The Dada Art Movement  - Kinectic Art**   
*Rotary Glass Plates (Precision Optics)*, Marcel Duchamp (1920)](http://b03.deliver.odai.yale.edu/a0/8b/a08b8539-aa28-48d9-aaf6-cfea7dadd0fd/ag-obj-43792-014-pub-med.jpg){width="25%"}

<!-- slide vertical=true data-notes=
"Some of the objects Duchamp created contribute to contemporary animation. Such as the rotoreliefs spun on record players that made the lines seem 3-dimensional."-->
![**The Dada Art Movement  - Kinectic Art**  
*Rotorelief No. 3 – Lanterne Chinoise – Modèle Déposé*,  
Marcel Duchamp (1935)](http://hyperallergic.com/wp-content/uploads/2016/09/ezgif.com-resize-1-1.gif){width="35%"}


<!-- slide vertical=true data-notes=
"Bahaus is the other extreme of Dadaism, as it centered simple forms, minimalism, universal design and  mass production over conceptual pursuits. The Bauhaus artists sought to mix several forms of art(painting, sculpture...etc) with design (graphic, product...etc) and technology to create an international design language. Laszlo Moholy Nagy, was one of the teachers in this school. He created objects that played with light, time and space."-->
![**The Bahaus Design Movement - Kinectic Art**  
*Light Space Modulator*, László Moholy-Nagy (1930)](https://gutschow.files.wordpress.com/2009/08/moholy-nagy-light-space-modulator-1922.jpg?w=700&h=&zoom=2)

<!-- slide vertical=true -->
![**The Bahaus Design Movement - Kinectic Art**  
*Kinectic Sculpture*, László Moholy-Nagy (1933)](https://proxy.duckduckgo.com/iu/?u=https%3A%2F%2Fi0.wp.com%2Fthecharnelhouse.org%2Fwp-content%2Fuploads%2F2014%2F06%2Flc3a1szlc3b3-moholy-nagy-kinetic-sculpture-e2809cgyrose2809d-in-motion-london-1936.jpg%3Ffit%3D611%252C800%26ssl%3D1&f=1&nofb=1){width="25%"}

<!-- slide vertical=true data-notes="Artists would write code to be printed by plotters https://www.youtube.com/watch?v=BYGPSAD5L_k. One of such works is Charles Csuri's Sine Curve Man. Csuri also explored animating these line in his work [Humming bird](https://www.youtube.com/watch?v=awvQp1TdBqc) in which the combined 30,000 images drawn on microfilm plotter.-->
![**Early Computer-Generated Art**  
*Sine Curve Man*, Charles Csuri (1967)](https://proxy.duckduckgo.com/iu/?u=https%3A%2F%2Fi.pinimg.com%2Foriginals%2F2b%2F9d%2Fe2%2F2b9de286541aa8c224df6c61c0e288be.jpg&f=1&nofb=1){width="45%"}

<!-- slide vertical=true data-notes="Molnar's art using these plotters illustrates Paul's (2003) statement that computational art relies on a set of rules. For Molnar, her work as an artist is to create the rules and find ways to make the computer deviate from them. This is an early example of generative art, where in computers create varying images using a set of algorithms." -->
![**Early Computer-Generated Art**   
*A la Recherche de Paul Klee (Searching for Paul Klee) (detail).*,   
Vera Molnar (1971) ](https://images.surfacemag.com/app/uploads/2017/11/13103930/vera-molnar-paul-klee-pen-2000x1333.jpg){width="60%"}

<!-- slide vertical=true -->
![**Early Computer-Generated Art**      
Vera Molnar's plotter with a pen attached](https://muda.co/src/img/molnar_love.gif){width="45%"}


<!-- slide vertical=true data-notes="Lillian Schwartz's pixillation is one of the earliest computer generated animation aside from Csuri's experimentations in morphing as seen in Humming bird. It fuses computer-generated images which Schwartz coded, with hand painted animation and synthesized sounds. The video can be seen in 3D when wearing Chroma goggles. Schwartz was a member EAT (Experiments in Art and Technology---A collective of artists and engineers that explored computation and art. These artists worked with both the MOMA (Museum of Modern Art) and Bell Labs Her work was one of the first acquisitions of Computer-generated art by an museum (MOMA) (cited in Digital Art Museum (2009)) https://vimeo.com/56480534"
-->

![Still from *Pixillation*, Lillian Schwartz, (1971)](https://hyperallergic.com/wp-content/uploads/2016/10/Pixellation.jpg){width="70%"}

<!-- slide vertical=true data-notes="https://www.youtube.com/embed/YB3saviItT
While some artists used the computer as an extension of their arm in drawing, other artists sought to draw directly onto the computer as a canvas. An early example of drawing on computers is Ivan Sutherland's Sketchpad."-->
![**Computer-Aided Design/Drawing on Computers**  
*Sketchpad*, Ivan Sutherland (1963)](https://proxy.duckduckgo.com/iu/?u=https%3A%2F%2Fbimaplus.org%2Fwp-content%2Fuploads%2F2018%2F12%2FImageToNews_Sketchpad-01.png&f=1&nofb=1){width="75%"}

<!-- slide vertical=true data-notes="The creation of Graphic user interface and the mouse made drawing on the computer easier. Artists could now show images without coding. The amiga graphics archive (http://amiga.lychesis.net/application.html) shows several applications that were used to create images during the early era of home computing. A moment that marked the computer as the artist's tool was Andy Warhol's live painting in an Amiga event https://youtu.be/wLvTG5hwa1A" 
-->
![**Computer-Aided Design & Home Computers**  
Andy Warhol (1985) painted Debbie Harry with  
Propaint software on the Commodore Amiga 1000](https://1.bp.blogspot.com/-OeUtGFW9McA/WKgU51kQcbI/AAAAAAACk38/-6YU7b5JeyYyhUcOynDiitMTZrk3mdR2wCLcB/s640/andy-warhol-debbie-harry-1985-1.jpg){width="25%"}

<!-- slide vertical=true data-notes="Computer Aided Design moved on to the vector graphics of Illustrator and the raster graphics program owned by Adobe. As we will discuss next week, Adobe also has a history with coding visuals." 
-->

![**Computer-Aided Design & Home Computers**  
Adobe Illustrator (1987) & PhotoShop (1990)](https://www.digitalartsonline.co.uk/cmsdata/features/3654413/illustrator1-alt.jpg){width="55%"}


<!-- slide vertical=true data-notes=
"Conclusively, as an art movement new media responds to politics, aesthetics, and cultural issues in the digital era."
-->
## New Media Art as a movement
+ A response to the information technology revolution (Jana & Tribe, 2006)

<!-- slide vertical=true data-notes="Most art movements as seen in Dadaism, Bauhaus... respond to some issue at the heart of their environment. With the spread of the internet in he 1900s, a number of net artist---creators whose works are browser-based---responded to the promise of race-neutrality in cyberspace. Both Blackness for sale and rent a negro address the commodification of blackness as on the internet. As Lisa Nakamura (2000) states, the anonymity of the net and use of avatars did not only fail to fulfil the promise of being free from race, it instead in brought in a new form digital life known as 'identity tourism'. " 
-->

![*Blackness for Sale*, Mendi and Keith Obadike (2001)](https://miro.medium.com/max/2880/1*Ldqgzk4CfX_Bs31FdYmTfA.png){width="85%"}

<!-- slide vertical=true -->
![*rent-a-negro*, Damali Ayo (2003)](https://d1v7jayx2s9clc.cloudfront.net/user/pages/rent-a-negro/rentanegro1.png){width="55%"}

<!-- slide vertical=true data-notes="p5.js is placed at the intersection of these tensions with information tech, politics, and art. I will share some p5.js artists whose work I like here.  " -->
## p5.js Accessibility in Coding

<!-- slide vertical=true data-notes="Warning! The screen flashes in the next slide" -->
![[*Magnetic Field*, Emily Xie, 2018](http://xie-emily.com/generative_art/magnetic_field.html)](http://xie-emily.com/projects/images/magnetic_field.jpg){width="65%"}

<!-- slide vertical=true -->
![A sketch by Sarah Groff-Palermo, p5.js contributor](https://miro.medium.com/max/2112/1*1NvohuI51kkRCaJZaqkHeQ.gif){width="65%"}

<!-- slide vertical=true -->
![[*Geometric Animations*, Saskia Freeke, p5.js contributor](https://sasj.tumblr.com)](https://66.media.tumblr.com/66f2a5cc534235e8a52b83c8d1b6a563/tumblr_pn72vd8o2N1qbgdnxo1_540.gif)

<!-- slide vertical=true data-notes"The creator of p5.js" -->
<iframe src="http://lauren-mccarthy.com" width="1280" height="720"></iframe>

<!-- slide vertical=true data-notes="Play video from 13:12 -22:57 https://www.youtube.com/watch?v=1k3X4DLDHdc&t=135s"-->
![[*p5.js* by Lauren McCarthy (2013)](http://lauren-mccarthy.com/p5-js-1)](https://payload.cargocollective.com/1/19/625408/10943099/home3_1500.jpg){width="75%"}


<!-- slide -->
## Principles of Design
## with p5.js

<!-- slide vertical="true" data-notes="http://gdbasics.com/html/framing/framing.html  <br>  https://p5js.org/reference/#group-Rendering"-->
## Framing
```javascript
createCanvas(x, y);
```

<!-- slide vertical="true" -->
## Grids 

<iframe src="https://editor.p5js.org/tokinifubara/embed/BwgVRPloF"  width="400" height="400"></iframe>

<!-- slide vertical="true" data-notes="point(), line(), rect(), ellipse() create form in p5" -->
## Point, Line, Plane
<iframe src="https://editor.p5js.org/tokinifubara/embed/fvExGoXOq" width="100" height="250"></iframe>
[Making shapes p5.js reference](https://p5js.org/reference/#group-Shape)

<!-- slide vertical="true" data-notes="Color can give an idea of an object as well as its form. We know the grass is green, the sky is blue and the sun is a yellow. Designers often look to the color wheel to get a sense of how to color an object. Using complementary and analogous colors, with specific hues and saturations, we can create pallettes that have a strong visual language and communicate our ideas clearly. Applications such as https://coolors.co and http://colllor.com help generate color pallettes.  <br>  http://gdbasics.com/html/color/color.html    <br>  http://gdbasics.com/html/transparency/transparency.html  " -->
## Color and Transparency

![Color Theory in Design](https://graf1x.com/wp-content/uploads/2014/09/color-wheel-poster.jpg){width="55%" height="55%"}  
[Color in p5](https://p5js.org/reference/#group-Color)

<!-- slide vertical="true" data-notes="What will happen to the second rectangle in the snippet below?<br> http://gdbasics.com/html/layers/layers.html<br> https://p5js.org/reference/#/p5/background" -->
## Layers
```javascript
function draw() {
     fill('tomato');
     rect(150, 150, 100, 100);
     fill('seagreen');
     rect(150, 150, 50, 50);
}
```
<!-- slide -->
Make a hand-drawn self portrait using basic shapes  
and create a p5 sketch using what we have just learned

<!-- slide -->
## Prepare...
for next week's class

+ Complete assignments on self-portraits and readings
+ Come prepared to talk about the readings

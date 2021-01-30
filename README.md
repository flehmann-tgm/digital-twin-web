# Digital Twin Website

To compete amongst other similar solutions digital twin needs a website that explains what it does and highlights its strengths. Following will be a short description of how this website was created.

The website uses a template called Agency by [startbootstrap.com](https://startbootstrap.com/themes/agency/). 

## Website Content

The template was then populated with content about the digital twin.

### Navigation

The five items in the top navigation were switched with ABOUT, TIMELINE and TEAM. The logo on the top left was also switched to a Digital Twin logo.

### Head

In the big head section with the background image the short title at the top was changed from "Welcome To Our Studio!" to "Smart City Data Distribution and Integration Network". The bigger title was changed to say "Digital Twin". The "TELL ME MORE" button was kept the same but the background image was switched out for a new image displaying the skyline of Vienna taken by Fabian Lehmann.

### Services

The Services section was switched to a section describing the project. With a general description on top and  two sections the describing the subprojects below. The icons were switched to a city and a server rack. These icons are provided by [fontawesome.com](https://fontawesome.com/icons?d=gallery). The html code for the icon looks like this:

```html
<i class="fas fa-city fa-stack-1x fa-inverse"></i>
```

To change the item to a different one the ``fa-city`` part must be exchanged. The available symbols can be found on the website.

### Portfolio

The portfolio section from the template was completely removed since it was not needed.

### About

The about section was a perfect template for a timeline. Therefore the text and the images were changed to represent milestones in the project. Also, the color of the title displays the current status of a milestone. If a headline is red, it is not done yet. Green headlines display parts of the project that are finished.

### Team

In the team section the images were switched to images of our team members with their name below the image. Each team member also chose some social media links on which you could find them.

### Clients

The clients section was changed to display project partners. Below a title saying 'Project Partners' there are the logos of three of our partners:

- tgm
- accenture
- Technologen-Verband

Below the partners there is an advertisement video about the Accenture Hackathon where the project was started.

### Contact

The contact section was removed since we do not want to be contacted over the website.

### Footer

The social media links in the footer were removed and a link to the template was added.

## Hosting in Github

For simplicity reasons the projects website will be hosted on Github. This can be done in a few simple steps.

Firstly a new repository with the name ``youusername.github.io`` in which the username is your username has to be created. In this instance the repository is called ``flehmann-tgm/flehmann-tgm.github.io``. 

Next the ``index.html`` file has to be pushed into the repository. Now the website can be reached with the url ``https://username.github.io``. In this case the website can be reached via https://flehmann-tgm.github.io/.

### Domain

The URL digital-twin.ddns.net was reserved at https://www.noip.com/ where you can get up to 3 addresses for free. The domain can also be set in the github repository settings.

## Sources

https://pages.github.com/
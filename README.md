# Edna Shuli Portfolio

Stream One Project: User-Centric Frontend Development - Code Institute

This website is my online resume-portofolio to present to prospective employers and other developers who might want to collaborate
with me. The portofolio provides information my coding skills, about myslef, my work and education experience and a contact form.

Please be free to take a closer look <a href="https://edshuli.github.io/Portfolio/" target="_blank">here.</a>

## UX

My goald in the design of the website is to prvide an easy access to all the important information on the site while allowing
the users to become familiar with it by maintaining the consistency. I choosed a violet-gold color scheme to create a warm
and modern felling.

For employers and other developers I have included on the site important information about my coding skills, where I have worked before 
my education history and short briefing about myself. I also wanted them to have an easy
access to my repositories and work with a link to GitHub, LinkedIn and a downloadable PDF version of my CV.
There is also a contact form so it will make them easier to contact me. 



## Technologies

1.HTML</br>
2.CSS </br>
3.Bootstrap v4.3

## Features

The navigation-bar stays fixed at the top, it has a transparent background-color with gold-color menu items. But on width max-767
the navbar stays collapsed and fixed on the top to provide an easy access to menu items.
</d>
About section contains two containers one is the about me container which includes a short briefing about myself and the personal info container 
where my personal details are included. On the desktop view we have the container next to each other, but on mobile screen we have the containers in a vertical order.
</d>

Skills container where we have two other containers the skill-items container and the languager-container.
On skill-items container we have 6 progress bars that shows the precentage of my coding skills on HTML, CSS, JavaScript, Django, Python, SQL.
On the language-container we have 4 progress bars that shows the precentage of my language knowledge.

Experience container contains two containers, the experience-container and the education-container. 
The education-container contains my studies with dates and teh univeristies.
The experience container contains my work history from the most recent job till the first job.

Contact container contains the contact form, where people can send me a message by filling this form. In case of an invalid put
the use will be notified with a warning, and if every field is filled correctly the page will be reloaded. 

Footer contains four links, one is a downloadable link where teh user can download a pdf form of my CV. The other link is Github that
links the user to my repositories, the LinkedIn link directs the user to my personal profile where the user can check my work history, education history,
knowledge, hobbies and my skills. The last link deirects the user on my Instagram profil where the user can have a closer look about my life and hobbies.

## Features Left to Implement

In the future I would like to change the progress-bars, add some animation hover or even change the whole style maybe make it a circle.
I also would like to add more projects on my portfolio and make somme changes on the navbar.

## Testing
The site was tested aon many browsers (Chrome, Microsoft Edge, Opera, Mozila Firefox) and mobile devices such as Iphone8,6s, Huaweii P20 Lite,
Samsung Galaxy S10, Samsung Galaxy A20 (Chrome, Ipad, Safari) to ensure compatibility and responsiveness. </br>
During this testing I faced a problem with background-image on the homepage container on mobile devices was not loading correctly so
I changed the background to another one which is loading on both devices correctly. 
</br>

#### Navbar Menu

If you click on any of the sections, you will be directed to your prefered one, the back action is tested and it workes properly.

#### Jumbotron

The jumbotron on the homepage container on mobile devices was not appearing in the middle of the page so I had to set a media querry with the right margin for the jumbotron.

#### Contact 

If you try to submit the contact form with an invalid email address,then an error will be appeared notified the invalid address.
Also teh  required attribute is added to the  'name', 'phone' and 'message' fileds so if those fields are not filled in then the user will be
asked to fill in this fields and the form will not be submitted. If all fields are valid then the page will be reloaded.</br>

#### Links

Using the 'target="_blank"' all links will open in a new tab and the CV will be dowloaded to your default folder for download
and this is done because of the 'download' attribute.
All links have been manually tested to make sure that they are pointing to the correct destination.

## Deployment

This site is hosted using GitHub pages and it is deployed directly to the master branch. In the page Terminal 
I used the git commit to add my files to the repository and git push to deploy directly the page to the GitHub pages.
The site will be updated automatically upon new commits to the master branch. 

## Credits

### Content

<li> All content in the About and Experience section are written by me.</li>

### Media 

<li>All photos were taken from <a href="https://unsplash.com/t/wallpapers" target="_blank">Unsplash</a> a source for freely usable images.</li>

#### Acknoledgements

<li>The progress bar and the navigation bar is taken from Bootstrap library.</li>

The style of the .timeline-item:before and .timeline-item:after was found on the Code Institute materials.

##### This is for educational use.
![l](assets/images/logo.jpg)

# *- EVS operator & editor -*
# **portfolio**

User-Centric Frontend Development - Code Institute
– **First Milestone Project** 

This project is a portfolio designed for my own business. The main goal was to create online presence, showcasing some of the projects I worked on and invite potential clients to get in touch and discuss work opportunities.

The EVS operators market themselves usually via word of mouth and past experiences. For those reasons I wanted to create a clear and simple to navigate page,  visually aesthetic with as little blocks of text as possible. 

[view website in GitHub pages](https://github.com/sneachda/portfolio-milestone-1)

# UX

Main goal, following the industry standards, was to make website easily accessible, include all information required while keeping minimalistic design.

A lot of potential employers/clients would most likely already know me or heard of me, for those reasons it was important to have interesting landing page and eye-grabbing “projects” section which included little glimpse into my career.
Additionally I added “contact me” section where people can get in touch if they have any queries.
Lastly I provided downloadable CV for potential employer to look over it in his own time (past work experiences and skills are included with more detail). 
I also included links to outside sources like my LinkedIn account and Instagram. It is quite unconventional to have those listed on home page, but I do think it works with the design and it might also be beneficial for the clients.


Wireframe:

[design](wireframe/visual.jpg)

[drawings](wireframe/draw.jpg)



## Features

There are 5 key sections on this website:

 - landing page
 - about me
 - projects
 - contact
 - downloadable CV
 
Each section has a responsive design and navigation bar with a logo to the left (which is also linked to home page) and other menu items to the right that take you to each section accordingly.
At the bottom there is a footer which include copyright and social media icons.

*Landing page*

Home page includes my logo, title and links to social media on the right hand side. On the left you will find an image from my work environment.
As mentioned before, it is not conventional to have social media icons at the top of the website, but looking at past experiences, I believe potential clients would appreciate fast glance at my CV or LinkedIn. 

*about me*

I decided to include a bit of information about me and list couple of my biggest jobs.  Experiences speak far more than words and I believe people visiting my portfolio would appreciate that. 
As per course requirements I also included video file, which shows another EVS operator at work. Unfortunately, for the lack of possibility to access my own videos, I included one from youtube.

*projects*

As per advice, I focused on 4 highlight points of my career with short explanation. I also included possibility for "read more" if someone wished to check specific section further. 

*contact me*

Simple form that allows visitors to get in touch with me.

*cv*

CV opens as PDF document in a new tab (allows clients download the file)


**Features to implement** 

In the future, I would like to add other projects I've worked on to create a more comprehensive project section. I would also look to add more animation to some sections when I advance more with languages. 
Hopefully I will also be able to add my own videos when I travel back home and get access to them - if I was to use this page commercially I would have to swap youtube video.


## Technology Used

The following was used to create the website:

1.  PyCharm - coding platform that was used for the coding and storing a local repository.
2.  [Bootstrap](https://www.bootstrapcdn.com/) - used to simplify the structure and to make it responsive.
3.  [FontAwesome](https://use.fontawesome.com) - accessed for social media icons.
4.  [jquery](https://www.jquery.com) - used to reference Javascrip modal
5.  [Google Fonts](https://fonts.google.com/) - used to style the website fonts.
6.  [YouTube](https://www.youtube.com/) - host of video included in the project section
7.  Adobe XD - tool used to create wireframe.


## Testing

The code has been validated using:
- [W3C Mark-up Validation Service](https://validator.w3.org/)

- [W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/)


This site has met the objective of creating online presence with minimalistic design and content, but providing enough information and platform to enable fast contact. 

All links included on this website have *target=_blank* attribute added, which means they will open in a new tab. That permits users to simply get back where they were within my page. All links have been manually tested to make sure the are linked to correct destination.

For the contact form to work as planed, I added ‘require’ attribute to all the fields (name, email, message). If the fields are left blank – the form won’t submit. Furthermore if email address is invalid, the error message will notify the user.

The website has been tested across multiple browsers (Chrome, Safari, FireFox) and across different screen sizes (Galaxy C5, various iPhones, Huawei, iPad, iPad Pro and laptops) to make sure is responsive. 

On bigger screens (min 992px and up) you will be able to see 2 images spread across the whole width of the screen that provide break between couple of sections. This gives the website the smooth scroll effect. I found this effect won't look good on smaller screens that's why it has been deisabled. Also for those reasons I decided not to include picture of myslef in *about me* section on those smallter screens.

On top of it all, fonts, images and other attributes have been changed accordingly to fit different screen sizes. Media queries have been used to make them work.  

During my tests I came across a struggle to fit my design between iPad and iPad Pro. It seems Pro is much bigger than average iPad size, yet not as big as computer screen. For those reasons special adjustments had to be implemented. 


## Deployment

The site was developed using PyCharm. Using version control in PyCharm I was able to commit and push to GitHub.

Those steps were taking in order to deploy my page from GitHub repository:
1.  On Github navigate to [sneachda/portfolio-milestone-1](https://github.com/sneachda/portfolio-milestone-1)
2.  From the menu at the top click on  `settings`
3.  Scroll down to the *GitHub pages* section
4.  Under *Source* section click on dropdown menu and select *Master Branch* as your GitHub pages publishing source.
5.  Select  `save`.


To create a local repository please follow those steps:

1.  Go to [Github Project Repository](https://github.com/sneachda/portfolio-milestone-1)  
2.  Under the repository name click  `Clone or download`  
3.  In the 'Clone with HTTPs section' clone URL for the repository.
4.  Open Git Bash in your local platform.
5.  Change the current working directory to the location where you want the cloned directory to be made.
6.  Type git clone, and then paste the URL copied earlier: 
git clone https://github.com/sneachda/portfolio-milestone-1.git
7.  After pressing ENTER your local clone will be created.



## Credits

**Content** 

All content in 'about me' section and 'projects' section in this portfolio were written by me.

**Media** 

- All pictures included in this project have been taken by me during work trips. 

- Video used to present EVS operator at work in 'about me' section has been taken from youtube - credit to [jerryrig7](https://www.youtube.com/user/jerryrig7)

- Logo has been designed for my own business purpuses by Scottish Graphic Company baseed in Glasgow in 2016.

**Acknowledgments** 

- The codeinstitute example site by Haley Schafer inspired the layout and navbar design.

- The codeinsitute example cv mini project inspired the social media icons.

- I have based my hover effect over images in *project* section on code I came across on [CodePen](https://codepen.io/nxworld/pen/ZYNOBZ)

Special thanks to Simen Daelin for looking over my project and to Anna Greaves (CSS Fundamental Lead) for her Monday nights Slack calls :)





**Disclaimer** 

*The content of this website is for educational purposes only.*




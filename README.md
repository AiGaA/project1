# Barrel Saunas Ireland
This project is done as part of a Code Institute Full Stack Web Development course. The first project is mainly written in HTML and CSS, while making sure, it is responsive and works well across other devices with different screen sizes, such as phones, tablets, smaller screens, or larger screens. 

I decided to create this project as part for my brothers business. This website shows just a small glimpse in what he is doing and what his goal is, and there is a lot potential to add all other information, work, etc. into this website in the future commits. 

The landing page of this website has slideshow, that I used --webkit-animation to set timing and it is scrolling infinite and --webkit-keyframes to set slides scrolling correctly.

The landing page has Menu bar at the top with transparent background that allows overflow the image full screen. 

![image](https://user-images.githubusercontent.com/25457379/216511092-40446dd1-6b6b-4faf-b49d-466162125b85.png)

The logo was custom-made using canva.com. It was implemented as favicon for the website and can be seen on top of the page when website is open.

![image](https://user-images.githubusercontent.com/25457379/216511473-69a18f5b-32a3-4717-8bf8-c6b545d4e082.png)
![image](https://user-images.githubusercontent.com/25457379/216520631-b0bace51-2b99-4fa1-869d-7b17651a0060.png)
![image](https://user-images.githubusercontent.com/25457379/216520531-ed382667-7f89-4fc9-96c0-d8931acc7dc8.png)
![image](https://user-images.githubusercontent.com/25457379/216520300-71b3526e-9b8e-45c0-9f9e-02e1be35d83a.png)


The landing page also has a footer on the bottom and a banner with text for the page.

Preview of the landing page
![image](https://user-images.githubusercontent.com/25457379/216521116-f7b8ec41-f8be-404a-9bfa-07efc75cd168.png)

## About page

I have added sections to describe little more about why sauna is so good and have listed benefits of it, and an actual craftsman himself. 

Each section is highlighted in opposite colors, so it is more readable

What it is section
![image](https://user-images.githubusercontent.com/25457379/216518249-f2df4332-c0b0-4d29-868e-04fb15a903b3.png)

Benefits of sauna section
![image](https://user-images.githubusercontent.com/25457379/216518648-269a0f43-ef95-4402-8369-6f12524f256b.png)

Small story about the craftsman
![image](https://user-images.githubusercontent.com/25457379/216518765-3bb2668a-5253-43b9-bbd4-009d25159f86.png)

Navigation bar was set to fixed, so it follows the page when scrolling down.

At the bottom there is a footer that has social media links added and Copyright section.
Both navigation and footer has been in bold dark color,  to make a contrast with rest of the page.

![image](https://user-images.githubusercontent.com/25457379/216519294-48afd910-5637-4a3a-8a58-669af82f87ca.png)

![image](https://user-images.githubusercontent.com/25457379/216519184-bafef3ce-cbdd-44d8-8cdb-e059a9ffa4b3.png)

## Contact Us

Contact Us page includes a form that would allow user to send an email to us. (No actual email has been set up this to be sent to)

Each form field is set to their types. Name for name. Email for email and Message for textarea.

![image](https://user-images.githubusercontent.com/25457379/216519857-c07051b0-4551-4b95-ae6f-1a98e18c1ab1.png)

The Submit button is set to submit type. When you click on 'Submit', it will redirect to another page - Thank You page. 

![image](https://user-images.githubusercontent.com/25457379/216520151-1486ede2-11e1-48e0-8b5c-c94c270a45cf.png)

# Resources

Here are some resources I used for this project:

-Google Fonts https://fonts.google.com/ 
I downloaded Lato font library, that I applied in my styles and used throughout the project

-Font Awesome https://fontawesome.com/icons
Font Awesome I used for social media icons: facebook, instagram and twitter

-Relied a lot on Stackoverflow https://stackoverflow.com/
Every other question popped up, was going through this website

-Canva canva.com
I used it to create my logo

-W3 Schools https://www.w3schools.com/
For generic information, as sometimes can forget even how to align things. It came great help on how to adjust photos

-Pexels https://www.pexels.com/
Searching good images. Most of my images are from my own archives, but this was great to search for something fresh

-Slack channel #project-portfolio-1
I had great struggle on ideas, and it was very inspiring to see other people work as well

-Am I Responsive? https://ui.dev/amiresponsive
To have overview of my website and how responsive it looks

# Compatibility checks

Chrome Developer tools were used the most to see responsiveness of the website on different device sizes, and adjusting @media queries to fix bugs.

Checking each time when adding new styles or applying new changes.
![image](https://user-images.githubusercontent.com/25457379/216524422-dd3264ba-4da5-4a5c-a8e7-29658ac1cf0d.png)

Small screen devices <br>
![image](https://user-images.githubusercontent.com/25457379/216524522-bec2853e-dab4-4e18-9ea8-b1f96d5c32ff.png)

Mobile versions <br>
![image](https://user-images.githubusercontent.com/25457379/216524893-fb08a150-146d-43d6-8244-d6063ed6f401.png)

# Bugs

Checking media queries, footer on contact page had to stick to the bottom. When checking all 
different screen sizes on Chrome Developer tool, it showed footer sticking in the middle, or overflowing
the content. I added @media query for smaller width size to set max-width of 375px position to unset, so this
does not overflow the content. When Checking Nest Hub the footer was again overflowing the content. 
I found this thread on Stackoverflow: https://stackoverflow.com/questions/11404744/css-media-queries-max-width-or-max-height
with option to add max-height to the existing media query, and this fixed my issue with the footer. 

# Unfixed Bugs

All bugs were dealt with at the time of issue arised.

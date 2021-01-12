Code Institute - User-Centric Frontend Development Project  
Josh Jones Fitness  
by Alex Mortali  

This is a website for Josh Jones's personal training business. 
The website serves to create an online presence for Josh, it covers a bit about himself, his clients, the services he provides, 
a contact form and links to his social media.
The website also includes a free pdf for his clients to download.

# DEMO  
A live demo can be found at - https://alexmortali.github.io/jj-fitness/

# UX  
When speaking with Josh he stated he doesn't want the website to feel intimidating but instead welcoming, easy to use and 
easy to navigate. This is why I have used a lot of negative space with a minimalist design to create a soft and easy feel. 
The grey/blue color scheme compliments to the open feel and links with the colors used in Josh's training facility.

The users are able to get a glimpse of Josh's background, a testimonial from a client, the training service he provides, 
and contact him if they wish. All of this is doable within a few clicks due to the sleek user friendly design.

In the footer section there are links to his social media (Instagram, Facebook, Twitter). The is also a free downloadable PDF 
of his 6 pack guide provided to help build customer relations. 

# FEATURES  
The site features a minimalist design with a constantly collapsed navbar fixed to the top. It has sections covering about me, 
clients, training, social media links, a downloadable pdf and a pop up modal for users to contact Josh.

# FEATURES LEFT TO IMPLEMENT  
In the future the website will have a check in system where clients can book a session directly through the website. 
As of right now they have to contact Josh through the 'Contact' form.

Also in the 'clients' section of the website there will be an option too view other clients testimonials. This will be 
implemented when Josh's client base grows using the 'Carousel' feature within Bootstrap.

# TECHNOLOGIES USED  
1 - HTML: This project uses HTML as the skeleton of the website.  
2 - CSS: This project uses CSS to control the presentation of the website.  
3 - Bootstrap(3.3.7): This project uses Bootstrap as it's framework to make the site responsive.

# TESTING  
When testing the website on various screen sizes it was obvious the clients section of the page wasn't visually appealing and
didn't fit the flow of the website. Therefore I thought best to redo this section. I started with the wireframe then developed the new design
and believe it now fits the flow of the website.

The website has the intended outcome of creating an online presence for Josh with a welcoming feel that is easy to use and easy to navigate. 
It provides a bit about Josh and on laptops/desktops the user can see an image of Josh. There is a section with client testimonials, a training section
providing information on the service Josh provides with a contact button activating a pop up modal with a contact form. At the bottom of the page there
are links to his social media that will open in a new tab along with a download symbol for the 6 pack pdf file. 
This will also open in a new tab and be downloadable from there.

The contact form doesn't currently send any data so there is a message at the top of the form directing the user to Josh's social media links.
If they do however try to fill in the form they and they miss out some information there will be an error message due to the 'required' attribute 
attached to the 'name', 'email' and 'message' fields. When the form does send data, it will not submit unless these fields are filled in.

The site was tested on Chrome and Safari on multiple devices including iPhone 7/8, iPad, it was also tested on Internet Explorer on 
multiple laptops and desktops. When testing on iOS browsers it was clear there was a problem with any background image that was fixed, the photos
appeared zoomed in. For this a media query was added giving the background image an attachment of scroll instead.

All links were tested manually on multiple devices to make sure they point to the correct place. They also open in a new tab including the downloadable pdf.

# DEPLOYMENT
The site is deployed directly from the master branch and is hosted using GitHub pages. The landing page is correctly named index.html in order for 
the site to work correctly.

# CREDITS:   
CONTENT - All content throughout the site was written by me.

MEDIA - Both photos of Josh were provided by himself. All other photos were taken from https://stock.adobe.com/uk/ a stock image website.

ACKNOWLEDGEMENTS - The css for the collapsed navbar was taken from https://www.bootply.com/114896#

# homework01 - Horiseon Webpage 

The marketing agency Horiseon has hired us to refactor their existing site in order to make it more accessible.

Web accessibility ensures that people with disabilities can access a website using assistive technologies such as video captions, screen readers, and braille keyboards. Making a website accessible is also good for business for many reasons, one of them being that accessible sites are better positioned in search engines like Google. It also helps companies avoid litigation that can occur when people with disabilities cannot access their website.

To improve the semantics in the HTML, I tried to use elements with meaning such as <nav>, <section>, <article> and <aside> rather than <div>. I also added alternative text where possible to include a consise description of images in situations where users are unable to view the image. I organized the code into main sections and inserted a comment for my own benefit before each major section. 

In the CSS file, I expanded the main elements of body, h1, h2 and h3 for simplicty and to reduce redundancy of rules throught the document. 

Since the original code used predominately class and element selectors in the CSS file I removed references to ID's in the HTML. Also, since the styling of many of the articles or sections were identical, I consolidated the CSS rules by class rather than separate, and redundant rules for multiple classes. This reduced the amount, or volume, of code considerably. I also re-ordered the CSS rules to be consistent with the flow of HTML commands. 

The final website looks like this: 

The following image shows the web application's deesired appearance and functionality:

![code refactor demo](homework01/Develop/assets/images/01-html-css-git-homework-demo.png)

In completing this task, I used references on semantics, accessiblity and CSS cascading and inheritance from www.W3schools.com. I also benefitted from the direction of our instructor Fil and team-mates Shiva and Max who helped guide me through creating and loading the repository on GitHub.   

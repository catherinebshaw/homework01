# homework01 - Horiseon Webpage 

The marketing agency Horiseon hired us to refactor their existing site in order to make it more accessible.

In this process, I learned that web accessibility ensures that people with disabilities can access a website using assistive technologies such as video captions, screen readers, and braille keyboards. Making a website accessible is also makes websites better positioned in search engines like Google. 

To improve the semantics in the HTML code, I tried to use elements that beter aligned with where the items appeared on the page such as navigation, section, article, aside and footer rather than using  div repeatedly. 

To improve accessibility, I added alternative text where I could so that the images on the site had a short description which would benefit any user that might be unable to view the image. 

Since the original code used predominately class and element selectors in the CSS file, I removed references to ID's in the HTML.

To help me get started and stay organized, I inserted a brief comment before each major section of HTML code. 

In the CSS file, I expanded the main elements of body, h1, h2 and h3 for simplicty. This also allowed me to remove redundant code such as text color and size from a number of areas in the file.

 Also, since the styling of the elements within the lower sections and in the aside were identical, I consolidated the CSS rules and created a single class for reference. This class now has a style for the container as well as for the internal image, header and content. These four groups of code replace 12 previous groups. I have left the original code as commented out in case the client wishes to change the format of the individual containers within the section. The same logic was applied to the content of the aside which now has a consistenet rule for container, content, image and heading. This change reduced the amount, or volume, of code considerably. I also re-ordered the CSS rules to be consistent with the flow of HTML commands and added comments before each CSS rule.  

 I took a small liberty and repeated the play on SEO in the company name in the footer. It will be simple to remove if needed. 

In completing this task, I used references on semantics, accessiblity and CSS cascading and inheritance from www.W3schools.com. I also benefitted from the direction of our instructor Fil and team-mates Shiva and Max who helped guide me through creating and loading the repository on GitHub.   

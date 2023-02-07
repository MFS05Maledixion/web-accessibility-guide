# WHAT IS WEB ACCESSIBILITY

## Web accessibility means that websites, tools, and technologies are designed and developed so that people with disabilities can use them. More specifically, people can:
- perceive, understand, navigate, and interact with the Web
- contribute to the Web

## Web accessibility encompasses all disabilities that affect access to the Web, including:
- auditory
- cognitive
- neurological
- physical
- speech
- visual


## Web accessibility standards
* Web accessibility relies on several components that work together. Some of these include:
- Web content - refers to any part of a website, including text, images, forms, and multimedia, as well as any markup code, scripts, applications, and such.
- User agents - software that people use to access web content, including desktop graphical browsers, voice browsers, mobile phone browsers, multimedia players, plug-ins, and some assistive technologies.
- Authoring tools - software or services that people use to produce web content, including code editors, document conversion tools, content management systems, blogs, database scripts, and other tools.

## TOOLS

### IMAGES
- alt text for screen readers (for any images that provide helpful information i.e photos, icons) the exception being decorative pieces i.e background images, dividers
- short and simple is best
- dont start with this is an image of... 'screen readers will read that it's an image'
- Adding on WordPress: <!-- Open up your Media Library and select the image you want to edit. The Settings screen for that image will open up. In the Alternative Text field, add your alt text, then click Save --> 

### COLORS
- provide adequate color contrast, this will help with users with poor vision, color-blind users, or people using certain devices
- Images, text, and elements like buttons all need proper color contrast
- Color contrast refers to how bright or dark colors appear when placed against or very near each other
- e.g black text on a white background has a much higher color contrast (21:1) than yellow text on a white background (1.08:1). WCAG 2.0 AA requires a minimum of a 4.5:1 ratio for normal text and 3:1 for larger text (bold 18px or standard 24px and larger).
- constrast checker: https://webaim.org/resources/contrastchecker/

### TEXT
- fonts and size
- An accessible font is easy to read at small and large sizes.
- e.g  Tahoma, Calibri, Helvetica, Arial, Verdana, Times New Roman, Arvo, Museo Slab, and Rockwell are all accessible choices.
- Readers with dyslexia may find it challenging to read certain fonts, including many serif fonts.
- Sans-serif fonts for body text tend to be a safer choice. It’s best to avoid display fonts — like handwriting styles or cursive — unless the text is large, sparse, and mostly decorative.
- take note of capitalization on fonts, with some fonts capital letters are indistinguishable from small letters.
- Default fonts should be at least 9pt or 12px. 12pt or 16px is recommended. According to WCAG Guidelines, the text should be able to be read when zoomed to 200%.

### BEST PRACTICES
- add interactive elements e.g on-hover functionality, on-click, on-focus
- navigation should be consistent throughout the website
- optional (recommended) : add breadcrumbs and clear headings so people can see the flow of the website
- Allowing users to stop or control any auto-motion

### SEO OPTIMIZATIONS
- generate a sitemap of the website
- include commonly used and trending words, this makes it easier for google's algorithm to find

## WORDPRESS PLUGINS

### TYPES
- those that help build an accessible site
- and those that help make an existing website accessible
- test your plugins, e.g form plugins, page builders

### ACCESSIBLITY STATEMENTS
- An accessibility statement is a page on your website where you communicate your internal policies, accessibility goals, and past successes regarding working with people who have disabilities.
- You should generate and publish an accessibility statement on your WordPress website for the following reasons:
- - To show your users that you care about accessibility and them
- - To provide information about the accessibility of your content
- - To demonstrate commitment to accessibility and social responsibility

## TESTING
- free accessibility test tool: https://wave.webaim.org/
- use contrast checkers before design when deciding your color scheme 

### Manual Tests
- Ditch the mouse: Make sure that you can reasonably and easily navigate all of your website’s functions using only your keyboard keys. 
- Use a screen reader: Put yourself in the shoes of someone who has low or poor visibility. Use a screen reader app or website and review the content on your site to ensure it still makes sense and sounds smooth when read aloud.
- Test the site in different environments: Go somewhere with public WiFi to make sure that your site loads properly without a high-quality internet connection.
- Increase the zoom: Open up your site in a browser and use the browser settings to zoom in 200%. Can you still use, navigate, and engage with the site in this setting? Is there content that disappears or gets cut off?
- Focus on interactivity: Make sure to spend plenty of time testing interactive elements like videos, forms, and buttons. Links and form fields should always be brought into focus with an outline, underline, special cursor.
- Double-check your alt tags: If you’re unsure whether or not an image has an attached alternative image, use the Inspect Element tool to confirm.
- Think differently: If all the images on your site disappeared, would someone still be able to use it? Essentials must still work without the gloss

# Quickstart Bootcamp: Project 01

### Overview

My name is Burke Edwards, and I created a simple portfolio website for this project! My friends and I bowl pretty frequently, and eventually got the idea to feature our bowling balls in poster form. There are three goals I wanted to accomplish by creating this site:

1. Get some HTML/CSS practice, of course
2. Have a nice showcase for our posters
3. Present information about our bowling lore :D

Basically, I wanted a healthy mix of *"art gallery"* and *"friend group archive"*, which I feel pretty good about! It's meant to be somewhat professional, but also somewhat playful. After all, serious bowlers probably don't give names and personalities to their bowling balls.

### Features (Pages)

The site layout is inspired by your typical shopping website. It has a homepage, a gallery of products, and the ability to focus in on each product.

The **home** page therefore is meant to be a summary of the whole site. It mainly features two flashy links to each secondary destination, and holds the **about** portion as well. At the top and bottom are the navbar and contact/resource links, but those are exactly the same for every page. As a bonus, you can click on either bowling poster to be taken to its respective page!

The **posters** page is the aforementioned gallery. By clicking on a certain poster's *"card"*, you will be taken to its **item** page.

Speaking of **item** pages, these are analogous to when you view a specific product on amazon's website. The poster, its IRL bowling ball, some specs, and a quick description/backstory. The only clickable thing here (aside from header/footer) is the link on the info card, which takes you to the manufacturer's page for that specific ball. Note that some bowling balls are missing this link, as they're too old to be featured on their official sites.

The last main page is the **queue** page, which is spearheaded by a large form. If you have a bowling ball that you'd like to realize in poster form, this is your means of reaching out! Of course, it doesn't connect to anything at the moment, as I don't yet know how to pull that off. As for the form itself, the only required fields are the main bowling ball details. Make, model, and pet name. Email is there in case we ever need to contact for follow-up, and an extra box is provided for specific details.

Technically, there is a **deadend** page. This serves only as a *"link not found"* waiting room for the links I haven't yet gotten to. Right now, the two ways to get there are both in the footer: Youtube and Main Portfolio.

### Features (Files)

**Images**: Not organized into individual folders, but sorted (kind of) by name:
    -Pattern: Only there for fun background effects
    -Ball: Photos of the real life balls
    -Small: Low-resolution versions of the posters for performance. 540x720
    -Poster: The real poster files. Use these if you plan on printing/modifying the designs. 5400/7200.

**References**: As per the workflow requirements, I had made wireframes for each of the major anticipated pages of this site. They're all in here, hand-drawn by yours truly!

**Posters (Folder)**: To keep things modular and neat, I decided to make each *item.html* reside in here. That way whenever I add more, they're all in one easy bundle.

**Css**: Same as above, these are in their own folder for organization's sake. Also because it was a requirement for the project.

### Technologies Used

-HTML
-CSS
-No Bootstrap (yet) (I have plans to change this!)
-Krita (Wireframes, background pattern, bowling ball cutouts)

### User Stories

I foreshadowed this a little bit in the overview, but these will properly flesh out my goals for the site:

1. "As a visitor, I want to read about the designers so that I can understand their inspirations."
2. "As a fan, I want to request a design so that my own bowling ball can have a poster."
3. "As a bowling nerd, I want to access the bowling ball specifications so that I can tell how each one performs on the lanes."

### Future Updates

1. The wireframes all portray a fun animation/logo above the navbar in the header. I was thinking of a bowling ball rolling across the screen, either on a loop or only when clicked on.
2. At the moment, the form on the queue page is purely cosmetic. It'd be awesome to make it work at some point! Maybe it'd send me an email every time someone uses it. On the off-chance I become famous, I'd have to find a buffer to keep my email at peace.
3. Each item page has a poster pic and an info card, and both are deliberately the same size. I initially planned to make this a flippable card, with each portion representing its own side.
4. When submitting a request, it's a little awkward to type out the bowling ball brand/type. It'd be cool to offer a search feature with a database of existing bowling balls. That way someone can more easily find their exact ball, and there won't be any ambiguity.
5. The website can be sized down decently, but it's not 100% robust in that regard. The pictures don't shrink, and some of the text boxes jut out of their containers once you take it too far. On top of that, the homepage figures wrap too early. There's room to clean these up.
6. I'd love to add flavicons!

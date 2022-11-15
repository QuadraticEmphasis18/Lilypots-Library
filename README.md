# Lilypot's Library 
*This is so much more than just a library on wheels.* 

## Why do we need Lilypot's Library? 
The need for a project like this to come to fruition has been driven by the heartbreaking year-on-year closures of stationary libraries, the economic cost of illiteracy rates and the lack of access to such facilities in neglected communities all over the country. This is about the future and we cannot keep making the same mistakes for the next generation to inherit. 

## What should users take away from this website? 
This is : 
<ol>
    <li> A social enterprise that aims to be fill the holes where community centers used to fit as a hub and a central library. 
    <li> a website that encourages easy navigation so that prospective users can arrange meetings to acquire information and further support regarding learning opportunities, sign up to classes, enroll their kids in breakfast and/or afterschool clubs as well as acquire a daily food parcel for them and their families.</li>
    <li> for parents who want their kids get their mornings off to a great start with nutrition</li>
    <li> for families who don't have to choose between a warm home or a full stomach with our close links to food banks & leading supermarkets.</li>
    <li> for kids who would otherwise meander around the streets bored but instead can return to our bus after school to complete homework and take part in activities with kids their own age.</li>
    <li> for the benefit of local communities in stamping out loneliness by encouraging them to come together and get them out of the house for a while</li>
    <li> for those who struggle with reading and writing but need the extra help without judgement.
</ol> 

# UX/UE: 
Short-term user goals on Lilypot's Library: 
<ol>
    <li> To experience easy navigation around the website.</li>
    <li> To understand exactly how and why Lilypot's Library is so much more than just a library.</li>
    <li> To have a fully responsive site across all available devices.</li>
</ol>
Medium-term user goals on Lilypot's Library:
<ol>
    <li> To continue to be a visual presence in the community with regular bookings on the calendar.</li>
    <li> To continue the fight against loneliness by bringing the community together through events and activities.</li>
    <li> To highlight and showcase the work done by the community to the people it serves both on our website and through social media links.</li>
</ol>
Long-term user goals on Lilypot's Library:
<ol>
    <li> To book kids onto our nutritional breakfast programme so they can thrive in the classroom and create fulfilled happy kids at our after-school clubs.</li>
    <li> To achieve a course fully supported by us provided by our social-enterprising partners.</li>
    <li> To end food and fuel poverty throughout the UK.</li>
</ol>

#  Why did I use the technologies? 
Firstly, I used html and css because these are mandatory requirements but I have also tried to include various bits and bobs from Bootstrap to differentiate between my own project and that of the walkthroughs I've done. They have been acknowledged at the bottom of this readme file.

# Project Challenges: 
The biggest challenge with this project was having to put this together in a matter of days after the previous client both pulled out and killed the project. Now I see why my mentor suggested a fortnight as a comfortable amount of time. 

The second biggest challenge were the tiny errors I made when I tried running the editor and the webpage was blank. They were small enough to fix and yet their impact superseeded their size. I soon realised it was because I didn't have links to the pages and later my css contained in the assets directory.

The third biggest challenge were the image links failing to work. I worked backwards from the problem and googled how to acquire a jpeg/png link and then when that didn't work I went straight back to where they were stored only to find they'd vanished. Odd I thought, so I reuploaded them and now they work. Thank goodness for small victories, eh? It's a good job I weirdly enjoy debugging my own bugs. 

# Screenshots: 
[A portion of the initial w3c html validator](assets/images/html%20w3c%20validator%20results.png)
This was the first check with the html validator I did on this project. It is worth pointing out that I fully expected errors etc to crop up and I was under no illusions that I wouldn't have a clean sweep of no issues on my first try. As you can see, I missed a minor but nonetheless an integral part of adding an image to my gallery - the alternative attribute - without which an image won't show up. It's also worth pointing out that the rather important point of saving images to my desktop, clicking and dragging into my assets, then images folder has definitely done me more favours than the use of links as displayed in this error results image. 
You can see the results page in full below. 
[A full view of the w3c html validator results page](assets/images/full%20html%20w3c%20validator%20results.png)

[Failed installation of images](assets/images/Gallery%20-%20images%20not%20showing.png)
Images are not showing here and it took me a while because of the serious amount of sleep deprivation to work out that this was the result of poor image structure/tactics. I asked for help from the wonderful Code Institute of software developers on Slack to help a gal out and three suggested to 'click and drag' images from the folder. I'm not exactly sure why there's a line across the top or indeed why the title won't sink down below the 'Lilypot's Library'. For the benefit of the reader, this is still a work in progress.  

[Failed installation of Bootstrap's Carousel](assets/images/gallery%20with%20bootstrap%20-%20images%20not%20showing.png)
I've had another look at how to refine and target the images using Bootstrap within CSS but as you can see it's going wrong more often than it's going right. Back to the drawing board and chin-scratching I go. If you think I make things easy for myself, you are much mistaken but these are the kinds of problems and pickles I love to solve. Believe you me, I will solve this and I am going to enjoy the process. 
Indeed, there was much more chin-scratching than anticipated and eventually I called upon the help of Code Institute's slack community yet again and I received much help from another mentor (not mine) called Harry Dhillon who walked me through using it. He made a very convincing argument about actually installing it because in future projects when I use Bootstrap again I'll be able to smash through it without any problems. Honestly, I found it so compelling it was difficult for me to refuse. Please scroll down to see the finished article and if you're reading this Harry - you're the man, thank you so much for your help and encouragement. 

[W3C CSS Validator results](assets/images/full%20css%20w3c%20validator%20results.png)
42 warnings:
Ahhh… so much to do but with a bit of chin scratching, elbow grease, builder's brews in me and my mate Google helping me out I'll get there. I am not giving up this easily. 
[W3C CSS Validator results - Part 2](assets/images/full%20css%20w3c%20validator%20results%20-%20part%202.png)
[W3C CSS Validator results - Part 3](assets/images/full%20css%20w3c%20validator%20results%20-%20part%203.png)
Harry, the mentor, graciously pointed out to me that the reason it had gone so wrong for me was that I had tampered with the code when I really should have left it all alone. Note to self: copy & paste but NEVER alter the code. It turned out to be a unique lesson in how to respect Bootstrap. 

So I have finally solved my div background colour issue and it turns out I put the property in the wrong place. It was here:
[div background color issue - Part 1](assets/images/div%20background%20color%20issue%20-%20part%201.png)

And now it's here:
[div background color issue - Part 2](assets/images/div%20background%20color%20issue%20-%20part%202.png)

This allowed me to target a different background-colour property for the divs like this:
[div background color issue - Part 3](assets/images/div%20background%20color%20issue%20-%20part%203.png)


[Lilypot's Library Sign Up Page](assets/images/Lilypots-Library-sign-up%20page.png)
My sign-up page now looks a lot clearer and easier to read and best of all nothing like the run-through project while still maintaining a simple yet classy nature. Boom!


[Events images](assets/images/Lilypots-Library-events.png)
Pretty sure these images speak for themselves (and though they will in future have links to other pages) I really think they can be appreciated without text on them. Besides the text really takes away from the experience. 
In hindsight and probably a bit of foresight too, I'll stick the text in a white box and put it in the middle of each div so that users will be able to click on the image and it will take them to a separate page that corresponds with the image. I do agree that there is too much clashing. 

Another challenge in building this website is moving the footer to the bottom of the page. The problem may be due to the margin. 
[Footer issue](assets/images/footer%20issue.png) 
On reflection, it's actually due to the height. It's also worth pointing out that when this is finished it will contain better images than it currently does.

I have put this project through it's validator paces so often that it genuinely no longer surprises me when I still have errors. I wish I didn't but the fact there is always work to be done on projects like this just feed my un-satisfied perfectionist brain to work on it for hours at a time... accompanied by plenty of chin-scratching, as is par for the course...
[Full Results of W3C Validator test](assets/images/full%20html%20w3c%20validator%20results%20-%20part%202.png)

This is also an opportune moment reader, to remind myself that first and foremost this project is in fact a mobile-first one and so below are a selection of screen-shots to demonstrate how this looks in real-life. 
[Mobile First - Part 1](assets/images/mobile%20-first%20part%201.png)
[Mobile First - Part 2](assets/images/mobile-first%20part%202.png)
[Mobile First - Part 3](assets/images/mobile%20-first%20part%203.png)
[Mobile First - Part 4](assets/images/mobile-first%20part%204.png)
[Mobile First - Part 5](assets/images/mobile-first%20part%205.png)
[Mobile First - Part 6](assets/images/mobile-first%20part%206.png)

## Tech/Framework used: 
# Languages: 
<ul>
    <li> HTML </li>
        <li> This is the content. </li>
    <li> CSS </li>
        <li> This is the styling.</li>
<ul>

# IDE 
<ul> 
    <li> Gitpod </li>
        <li> This is what I've used to manage my website's files containing the code to make the website work. </li>
</ul>

# Editor 
<ul>
    <li> VSCode (Browser) <li>
        <li> This is the software I used to write the code. It's built into Gitpod as one of several choices of code editors. </li>
</ul>

# Fonts: 
<ul>
    <li> Google Fonts </li>
        <li> Poppins and Playfair were imported into the style.css file in this project. </li>
</ul>

# Iconography: 
<ul>
    <li> Font Awesome:</li>
        <li> This was imported into the project for social media links in the footer and on the sign-up page. </li>
</ul>

# Development & Testing: 
<ul>
    <li> DevTools </li>
        <li> This was used two-fold: a) responsiveness and b) debugging
    <li> HTML Validator </li>
        <li> This was used to check that my HTML code was up to industry-standard. </li>
    <li> CSS Validator: </li>
        <li> This was used to check that my CSS code was up to industry-standard. <li>
</ul>

## Features: 
# Why the name Lilypot's Library? 
Lilypot is actually the nickname I have for my niece and I chose it essentially because the aim with this imaginary business is that it's about the next generation. Nobody embodies that than a three year old who has an opinion on everything and isn't ashamed to let you know. I also realise that the moniker is unusual and I chose to use this to increase accessibility. I'm very aware of how white dominated everything else is on the website and in time will make further efforts to diversify the images. With the time constraints I've had this hasn't been possible. 

# Why the colour and visuals? 
In naming this fictional business after my niece, choosing the colours and images came easily when I kept her in mind. The dusty-rose pink on each webpage is her favourite colour so her parents tell me. I also wanted to make as many of the images used both on the 'homepage' and those on the 'gallery' as bright as possible. They are so bright it's hard to find a standard font colour that looks uniform and doesn't clash.  

# Why the fonts? 
I chose these font because I thought they looked fun and approachable whilst also being easy-to read, smart, simple in layout and above all professional. 

# What features could/would be installed if there was more time? 
Features I would install later would probably be: the opportunity to allow users to have an account with us where it would detail a personalised overview of what it is they personally require from us. It would include information about interests, time constraints (working-childcare-free time), whether they have a learning difficulty and need additional support, and pick which purpose point applies to their needs. 
I'd also have a donation tab tacked onto the sign-up page for users to contribute if they wanted to. It's worth pointing out at this stage that e-commerce skills have yet to be mastered. This wouldn't be the only source of income, the mobile library would welcome as sharing the refurbishing build of the fleet of buses on social media would establish an early-interest in the business. 
I'd have YouTube videos of us converting the buses into the hubs-on-wheels they are destined to be. Other social media channels would play their part and we would make sure that all events take pride of place on the site. 

## Tests:  
# Parents: 
> Blockquote "Just looking at the link. Comments regarding the home page good first impression, could emphasize more the community aspects e.g. Lilypot's Community Hub and Library. The 'Doing Good' needs rewording, the pictures at the bottom need a description/explanation and maybe even a link. The gallery - the pictures could be bigger, better cropped and again have some explanations. Hope it helps." 
> Blockquote "We had a quick look together. Navigation was easy, nice simple layout with clear spacing. It was easy to read even for me. Text is clear although a bit more spacing between the headings and the text (explanation)."

# Code Institute's Slack Developer Community peer-code-review channel: 
Grace McKenna_lead:
> Blockquote "Hey Lex! Pretty landing page! A few things just from glancing at it.
Your copyright in your footer isn’t at the very bottom, I’d suggest using a sticky footer to keep it at the bottom. Minor thing though.
You seem to be having some CSS issues with your contact page. I’ll attach an image to show what I mean, it’s the last option button.![Screenshot of contact page](https://files.slack.com/files-pri/T0L30B202-F049VM68K1U/screenshot_2022-11-08_at_20.50.55.png)
Looks nice and responsive, your gallery does get very small compared to the rest of the site on mobile though. I’ll attach another image of what I mean as well. [Gallery page as viewed on a mobile device](https://files.slack.com/files-pri/T0L30B202-F049VM6M4KG/screenshot_2022-11-08_at_21.00.24.png)
Had a quick look at your README, I know you said you’re in the middle of it but just keep an eye on your styling in a preview window. You have to have a space after ‘#’ for headings etc in markdown, otherwise it just shows up as another character. Just letting you know for future reference so you don’t have to go back and fix it again if you’re still in the process of everything :)"

Simen Daelin (aka Eventyret_mentor):
> Blockquote "Just to add to what was said:
Don't use copyright unless you own all photos yourself, use made for education purposes.
Suggest not split into multi pages but use a single scrollable page, less code, easier to maintain and again footer and header doesn't change just the middle.
Make sure you commit more often reading the commit it seems you copy and pasted love running changed comments and colors. Again what git tells me. Again was reading on a phone so :man-shrugging:
Make sure your allowed to use boostrap if your on 4p course not a problem but I think you are missing the JavaScript at the bottom before closing body tag, else your carousel won't be working."

# Tutor:  
"It looks really good - you just need to sort out some of the positioning as the content is all up towards the left and should be centred more. Just test it using the inspector tools in chrome to see how it looks for different screen sizes and ratios." 

## How To Deploy? 
If you've found this page chances are you may already have a GitHub account. If you haven't but you want to make changes to this then you'll need to sign up for one. 

<ol>
    <li>Go here to the Lilypot's Library repo: https://github.com/QuadraticEmphasis18/Lilypots-Library.</li>
    <li> Click on 'Settings' which is to the right of 'Insights'. </li>
    <li> Look at the list of 'code and automation' and click 'Pages'.</li>
    <li> Under 'Build and deployment' 'Source' heading select 'Deploy from a branch', </li>
    <li> Under 'Build and deployment' 'Branch' heading select 'main' (branch) and 'root' (directory) then press the 'Save' button next to it. </li>
    <li> Scroll to the top of the page. You should get a message saying "Your site is live at https://quadraticemphasis18.github.io/Lilypots-Library/" 
    <li> Click the new tab button 'Visit site' to see the changes you've made. Please be patient if the page takes a little longer than normal to load. </li>
</ol>

## Contribute: 
I am fully open to contributions both online and offline especially for those who are from the areas of the community that a service like this is needed. It is worth mentionning that this project is publicly available to all although when I was working on it (to minimise distractions) I kept it private. 

I realise that visually there isn't much of a plan here. Time constraints put paid to any basic wireframing structures as I was up against a deadline and given I'm more of a wordy-type than a visually-designer type I'd have had to put a lot of effort into showing what was in my brain on paper. In future projects I will endeavour to try and master this skill. The upside to this is that there is scope for creativity in what to add where. Should you need something to spark the imagination, those who have offered feedback have raised some interesting ideas well worth implementing. Upon my return at various points throughout the course and after, I will be adding further details of my plan to Lilypot's Library GitHub wiki to add some clarity. I would urge any contributors to also contribute to the wiki. 

First, I would recommend clicking on this link: https://github.com/QuadraticEmphasis18/Lilypots-Library. This will take you to the repo.
Second, if you have the 'Gitpod' extension installed, click the green button. If you can't see this button it may be that you don't have it installed. Please go here to install it: https://chrome.google.com/webstore/detail/gitpod-always-ready-to-co/dodmmooeoklaejobgleioelladacbeki?hl=en 
Third, it should take you straight to the vscode editor. If this is true, you'll be able to see a pane on the left of your screen with 'OPEN EDITORS' dropdown menu at the top. 
Fourth, have a little trek around how I've made the website. There's a lot to take in and if you're a seasoned developer, I fully understand if any of the code makes you a smidge annoyed because it's old and cranky. I've yet to reach the stage you're at (especially future me who might return to this after the course is over) so please be patient with me.

## Credits: 
I wanted to combine the warmth of one walkthrough project on this Code Institute course with the structure and simple design features of another:
Coder's Coffeehouse - The warmth and friendly nature of a coffeehouse. 
Love Running - The simple and effective structure with easy navigational links. 
For the cards, they are by my grandma's extraordinarily artistic hand. I wish I was naturally inbued with her level of talent but some things cannot be taught. 
For the main image on index.html, I have my parents to thank for that because according to them, my list of 20 potential images did not project the message I wanted it to carry. My parents know me very well and so I trust their judgement when they tell me what I envisage and what I'm trying to portray is a terrible mismatch. The one they helped me decide to use I initially showed to them for no other reason than I thought it was punny (not a typo). Suffice it to say, I put aside my own personal view and can now look at it and appreciate that it's actually very well suited to the feel of the website. 
circle-cover-bg photo credit to <a href="https://unsplash.com/@jamie452?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Jamie Street</a> on <a href="https://unsplash.com/?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
hero-image photo credit to Gerd Altmann from Pixabay.  
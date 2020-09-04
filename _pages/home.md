---
# Home Page
#   this isn't the friendliest code to edit,
#   I apologize in advance
#   I didn't understand it at all when I started,
#   but the relevant bits are commented so it makes sense

# IMPORTANT PSA:
#   if you have a quote inside an excerpt/other tag,
#   (look at Ilian's excerpt for example), " becomes \"
#   as to not confuse the page parsers

# do not mess with this
layout: splash
permalink: /

# controls header
header: 
  image: /assets/images/everybody2020.jpg
  caption:

# tagline under header
intro:
  - excerpt: 'Founded in 1988, The Filipino American Student Association (FASA) is an organization formed to enhance interactions between Filipinos and other students, faculty, and staff of the Virginia Polytechnic Institute and State University through cultural, educational, and social activities.'

hoco_header:
  - title: Support Our President, JC Cepillo, Running for Homecoming Court!

hoco_pictures: 
  - image_path: /assets/images/misc/hococombo.jpg

hoco_statement:
  - excerpt: "Hey bbs! I’d like to formally announce my representation of the Filipino American Student Association on the Homecoming Court for the Fall Semester of 2020. My platform is “Project PUSO with JC”, where I aim to spread the Ideology of “Purposeful Unconditional Service to Others” throughout Blacksburg and surrounding areas. Similarly, the word “PUSO” means “Heart” in the Filipino Language of Tagalog, where I am trying to make a difference one heart at a time. Truthfully, I wouldn’t have been able to overcome all of the hardships throughout my life if it weren’t for my amazing friends and family providing me with unconditional love and support, and I have spent my life trying to inspire others to do the same. The PUSO Foundation pools together the many talents of our family to provide Covid Relief, Beirut Aid, and many more projects. I cannot wait to share more about my platform in these upcoming weeks, but let’s get started with my homecoming shirt! If you would like to purchase one, please follow the directions on the second picture. Love y’all, and thank you so much for your support! 
  
  -JC"

blm_header: 
  - title: "FASA's statement on the Black Lives Matter Movement and Systemic Racism in America"

blm_statement:
  - image_path: /assets/images/misc/blmstatement1.png
  - image_path: /assets/images/misc/blmstatement2.png
  - excerpt: "Click here to visit our Linktree page and learn about the BLM Movement and take action"
    url: "https://linktr.ee/FASAatVT" 

# pages
feature_row:
  - image_path: /assets/images/home/events.jpg
    excerpt: "Check out some of our current events."
    url: "/events/"
    btn_label: "Events"
    btn_class: "btn--inverse"
  - image_path: /assets/images/home/members.jpg
    excerpt: "See some of our talented members!"
    url: "/members/"
    btn_label: "Members"
    btn_class: "btn--inverse"
  - image_path: /assets/images/home/officers.jpg
    excerpt: "Check out our officer board for this school year!"
    url: "/officers/"
    btn_label: "Officers"
    btn_class: "btn--inverse"

# eboard header
eboard_header:
  - title: 'Executive Board 2020-21'

# eboard part 1: president, vice, and secretary
e_board1:
  # president
  - image_path: /assets/images/officers/20-21/JC.png
    alt: "JC Cepillo"
    title: "JC Cepillo"
    excerpt: "***President***" # -"I have sensitive eyes so catch me wearing my sunglasses even when it’s cloudy"
  # vice president
  - image_path: /assets/images/officers/20-21/Joy.png
    alt: "Joy Danielle Villanueva"
    title: "Joy Danielle Villanueva"
    excerpt: "***Vice President***" # - I quote FRIENDS and and Harry Potter a lot"
  # secretary
  - image_path: /assets/images/officers/20-21/Nia.png
    alt: "Nia Corpuz"
    title: "Nia Corpuz"
    excerpt: "***Secretary***" # - Mabuhay! My name is Christa Ventura, and I am the Secretary. I hope my passion for FASA is translated in the work that I do! I cannot wait to see what this year brings!"

# eboard part 2: treasurer and historians
e_board2:
  # treasurer
  - image_path: /assets/images/officers/20-21/David.png
    alt: "David Dong"
    title: "David Dong"
    excerpt: "***Treasurer***" # - Hey everyone my name is David Brighton and I will be your Treasurer this year!!! I look forward to meeting you all and having a great year!"
  # historian 1
  - image_path: /assets/images/officers/20-21/Josh.png
    alt: "Josh Protacio"
    title: "Josh Protacio"
    excerpt: "***Historian***" # - I have a passion for creativity and I can’t wait to use it through my position on the FASA officer board!"
  # historian 2
  - image_path: /assets/images/officers/20-21/Andrew.png
    alt: "Andrew Leavitt"
    title: "Andrew Leavitt"
    excerpt: "***Historian***" # - current mood: hungry"
    
---

{% include feature_row id="intro" type="center" %}

{% include feature_row id="hoco_header" type="center" %}

{% include feature_row id="hoco_pictures" type="center" %}

{% include feature_row id="hoco_statement" type="center" %}

{% include feature_row id="blm_header" type="center" %}

{% include feature_row id="blm_statement" %}

{% include feature_row %}

{% include feature_row id="eboard_header" type="center" %}

{% include feature_row id="e_board1" %}

{% include feature_row id="e_board2" %}

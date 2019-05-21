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
  image: /assets/images/everybody2.jpg
  caption:

# tagline under header
intro:
  - excerpt: 'Founded in 1988, The Filipino American Student Association (FASA) is an organization formed to enhance interactions between Filipinos and other students, faculty, and staff of the Virginia Polytechnic Institute and State University through cultural, educational, and social activities.'

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
  - title: 'Executive Board 2019-20'

# eboard part 1: president, vice, and secretary
e_board1:
  # president
  - image_path: /assets/images/home/eboard/joey.jpg
    alt: "Joey Rivera"
    title: "Joey Rivera"
    excerpt: "***President*** - \"I thought we were ahead\" -J.R. Smith"
  # vice president
  - image_path: /assets/images/home/eboard/aubrey.jpg
    alt: "Aubrey Medina"
    title: "Aubrey Medina"
    excerpt: "***Vice President*** - I quote FRIENDS and and Harry Potter a lot"
  # secretary
  - image_path: /assets/images/home/eboard/timmy.jpg
    alt: "Timmy Le"
    title: "Timmy Le"
    excerpt: "***Secretary*** - I like to cook and clean. Follow me on ig"

# eboard part 2: treasurer and historians
e_board2:
  # treasurer
  - image_path: /assets/images/home/eboard/christa.png
    alt: "Christa Ventura"
    title: "Christa Ventura"
    excerpt: "***Treasurer*** - Please pay your membership dues and I'll tell you anything you wanna know!"
  # historian 1
  - image_path: /assets/images/home/eboard/shawn.jpg
    alt: "Shawn De Lopez"
    title: "Shawn De Lopez"
    excerpt: "***Historian*** - I have a passion for creativity and I can’t wait to use it through my position on the FASA officer board!"
  # historian 2
  - image_path: /assets/images/home/eboard/adrian.jpg
    alt: "Adrian Talastas"
    title: "Adrian Talastas"
    excerpt: "***Historian*** - current mood: hungry"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

{% include feature_row id="eboard_header" type="center" %}

{% include feature_row id="e_board1" %}

{% include feature_row id="e_board2" %}

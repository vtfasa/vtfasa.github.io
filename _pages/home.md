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
  image: /assets/images/everybody.jpg
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
  - title: 'Executive Board 2017-18'

# eboard part 1: president, vice, and secretary
e_board1:
  # president
  - image_path: /assets/images/home/eboard/ilian.jpg
    alt: "Ilian Burgos"
    title: "Ilian Burgos"
    excerpt: "***President*** - Hi my name is \"Jillian without the J\", supreme ruler and divine majesty of FASA, and you're watching Disney Channel!"
  # vice president
  - image_path: /assets/images/home/eboard/aj.jpg
    alt: "AJ Campanilla"
    title: "AJ Campanilla"
    excerpt: "***Vice President*** - Hand of the Queen, Rightful Heir to William's Heart, Protector of the Pinoy Culture, and Father of Balut. Have you done Freshman dance yet?"
  # secretary
  - image_path: /assets/images/home/eboard/raymark.jpg
    alt: "Raymark Galman"
    title: "Raymark Galman"
    excerpt: "***Secretary*** - Bothering people, one listserv at a time (seriously, please read them!) ~ Secmark"

# eboard part 2: treasurer and historians
e_board2:
  # treasurer
  - image_path: /assets/images/home/eboard/elliot.jpg
    alt: "Elliot Idio"
    title: "Elliot Idio"
    excerpt: "***Treasurer*** - pay your membership dues and then go to the officer page to learn more about me`"
  # historian 1
  - image_path: /assets/images/home/eboard/will.jpg
    alt: "William Sriros"
    title: "William Sriros"
    excerpt: "***Historian*** - My name's William (Lilliam) and I take pictures and videos for FASA sometimes and so you might see me. Have you done Mr. FASA yet? AJ hasn't"
  # historian 2
  - image_path: /assets/images/home/eboard/sarida.jpg
    alt: "Sarida Pisarnpong"
    title: "Sarida Pisarnpong"
    excerpt: "***Historian*** - Hey y'all! My name is Sarida (Historida) and I'm one of the historians for FASA. My job is to take pictures and videos for everyone!"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

{% include feature_row id="eboard_header" type="center" %}

{% include feature_row id="e_board1" %}

{% include feature_row id="e_board2" %}

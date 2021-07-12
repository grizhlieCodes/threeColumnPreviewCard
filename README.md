# threeColumnPreviewCard for Frontend Mentor

![project preview](/design/desktop-design.jpg)

## Project Info

This was a very simple project for me. After helping people who are new to
coding and leaving various comments about 'best practices' I thought it best to
just code this up and see how much of my own advice I stick to without thinking
about it before hand.

## Philosophy - Browser does the heavy lifting

The main message I've been trying to share with newer coders is all about
letting the content dictate the sizing. Upon a quick study of the cards you will
notice I don't set the height anywhere. All I use to dictate the sizing is made
up of the content, white-space (gaps, margins, paddings) and width depending
upon the containers. THe fixed values are quite natural (widths). Heights are
allowed to by dynamic. If we added three times the amount of content into the
`<p class="preview-card__info"></p>` the design would still function. 

It is this very lesson that I think is important to understand when it comes to
best practices of sizing, settings widths/heights etc. Really core stuff 😀.

## Avoiding Pixel Perfect

Due to my philosphy, mentioned above, I didn't even measure heights in this
project. Instead I trust the content and the white-space and the max-widths to
control the height which is dynamic. In this case I think it's ok to avoid
pixel-perfection. I do think it's probably damn close though as I did measure
the paddings/gaps from the original design.

## CSS Files

I have 3 CSS files serving the following purposes:

- **reset.css:** This resets our CSS to allow us a clean project. I always reset
  my CSS and dicate all styling from scratch. It's a preference and leads to
  more consistant results I think.

- **helpers.css:** This simply allows me to set the unique background/text
  colors of the 3 cards. I used a different file as it's a habit I picked up in
  CSS. I spread my CSS very logically (I hope) across different files to make
  scalability easier and accessing the CSS i need to find faster.

- **style.css:** This of course is the main style file. Here I imported my
  fonts, set my variables and styled the cards. 


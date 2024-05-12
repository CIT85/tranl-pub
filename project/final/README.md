# CSS Documentation
## Flexbox
- Starting off with flexbox, I'm having a lot of troubles coming up on where to place it, so for starters, I've decided on the "header" section. 
- Along with the header for the flexbox, I've decided to use the <p> as the box models for the flex.
- .flex-container: I've decided to use the following rulesets:
1. "display: flex;": starting element to properly create a flex container.
2. "justify-content: space-between;": this controls the alignment of items along the main axis of container. 
2. "flex-direction: column;": this sets the direction for the flexbox, creating a sorta vertical dropdown container.
3. "align-items: center;": this aligns items in the center and horizontally in the container.
- .box: I've decided to use the following rulesets:
1. list-style-type: none; : this line removes the default list-style (bullet points, numbers, etc.) from elements inside the .box class.
2. "padding: 10px 20px;" : sets the padding for the box
3. "background-color: #f0f0f0;" : set the background-color for the box
4. "border-radius: 5px;" : sets border radius
5. "margin-right: 10px;" : sets the margin to the right side.
6. I've also decided to add some additional styling elements such as adding a hover effect and making the h2 transparent for more visually appealing style. 
7. I've also added a sticky position to the box
---
## Grid-layout
- I've decided to use the "My Interests" section to implement the grid-layout
- #grid-layout:
1. display: grid; : use to define the element as a grid container.
2. margin: 20px auto; : sets the margins for 20 pixels.

- .grid-items: I've used the following elements to setup a basic box model
1. background-color: #D8A7B1; 
2. padding: 20px;
3. border-radius: 10px; 

- At this point, I've decided to use ChatGPT to help further design the grid-items to make it more visually appealing. It created these following elements:
1. box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1); : to create shadow for depth
2. transition: transform 0.3s ease; : to help a smooth transition for hover effect
3. ".grid-item:hover {
  transform: translateY(-5px); /* Move up slightly on hover */
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2); /* Increase shadow on hover */
}" 
To create a hover effect for the grid items
---
## New subpage
- The new subpage I've decided to create is indended to show the difference between what I love, showing the difference between manhua, manga, and manwha. 
- I've also added some additional photos for the submenu
---
## Media Queries
1. Starting off with media queries, I've look at some references points: https://www.w3schools.com/css/css_rwd_mediaqueries.asp.
2. Along with this: https://dev.to/lindaojo/how-to-use-media-queries-in-html-css-and-javascript-n8o.
3. Firstly, since the time crunch is high and the semester is nearly ending. I've decided to use one of my previously built html webpage and one of our previous assignment for my subpage. Since the previous assignment's theme aligns well with my website. 
4. After creating the subpage, I've added a couple related images and verified the html codes, alongside that I've added more details for this subpage to match with everything else.
5. I've updated site.html to fits the requirements 
6. I've completed some basic setups elements for the media queries for different types, such as: 
  - Mobile devices: @media screen and (max-width: 480px)
  - Ipads, Tablets: @media screen and (max-width: 481px) and (max-width: 768px)
  - Small Screens, Laptop: @media screen and (max-width: 769px) and (max-width: 1024px)
  - Desktops, large screens: @media screen and (max-width: 1025px) and (max-width: 1200px)
  - Extra large screens, TV: @media screen and (max-width: 1021px)
7. I've discovered a new reference: https://www.youtube.com/watch?v=K24lUqcT0Ms&ab_channel=SlayingTheDragon
8. I've now since found out how to properly code the media queries so I decided to focus on the larger screen sizes, for devices such as ipads and up and changes my codes to corresponse to it.
9. For each individual media queries, I've decided to add some addtional coloring elements to test the difference and some more additonal styling elements for the headers.
10. All html and css are validated. 

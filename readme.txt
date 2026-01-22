--Readme document for Tedman Nguyen, TEDMANN@uci.edu--

1. How many assignment points do you believe you completed (replace the *'s with your numbers)?

10/10
- 1/1 Readme
- 1/2 Basic HTML content
- 1/1 Basic CSS styling
- 1/1 Advanced feature
- 2/2 Responsive layout
- 1/1 Passes validation checks
- 2/2 Embraces spirit of the assignment

2. What (a) basic features, (b) CSS features, and (c) advanced features did you include in your portfolio?

(a) Basic features
- 12 images
- Appropriate headings and paragraph text
- Links to external page for all pages, including buttons
- Multiple pages (about, internship, projects)

(b) CSS features
- Modifying padding and margins
- Modifying link, text color, or other colors 
- Leveraging Bootstrap CSS helpers to help with columns of text / images
- Hover over effects on clickable images. 

(c) Advanced features
- Sticky navigation bar with colored text signifying what page the user is on.



3. Did you ignore any of the warnings or errors presented by the accessibility checker? If so, why does this not seem like an accessibility concern? If it's useful, you can consolidate your thoughts on multiple warnings/errors if the rationale is similar.

Yes, I ignored the same error (Error 174) that came up on multiple pages. The error is "Anchor contains no text". The rationale is that the anchor is an image that users can click on, so it shouldn't have any text. Additionally, the image itself has a text. For example:
          <a href="https://github.com/TedmanNguyen/Shiny-Tracker" target="_blank">
            <div class="grow">
              <img src="shinytracker.png" 
              alt="Shinytracker Application" 
              class="img-thumbnail">
            </div>
          </a>

As you can see, there is alt text, but the checker isn't picking it up because it is nested inside my grow class, which I added for a scaling animation when mouse hover over. This error came up for all the images in which I used hover over. 

4. How long, in hours, did it take you to complete this assignment?

About 12-14 hours, spread across 3 days. I spent the most time today. I struggled when using Bootstrap 3 but a lot of documentation came up for Bootstrap 4 and 5, so I ended up switching over. 

5. What online resources did you consult when completing this assignment? (list specific URLs, describe queries to Generative AI, or use of AI-based code completion)

I mostly consulted bootstrap documentation and W3 schools. I avoided using ChatGPT 90% of the time, except when I got extremely stuck. The one time I got stuck was when figuring out how to center the text on the nav bar. I pasted in my navbar code and asked how to do it, and it was surprisingly easy. It was hard for me to read my code sometimes when there are so many nested selectors.

6. What classmates or other individuals did you consult as part of this assignment? What did you discuss?

I did not consult any other classmates

7. Is there anything special we need to know in order to run your code?

Not really. The Index page was intended to act as an intriguing hero/splash page, so it only has one button which leads to all other pages. However I ran out of time. 

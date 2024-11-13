


<p align="center">
| <a href="https://majak02.github.io/Over-The-Rainbow/" target="_blank">Link to Project</a> |
</p>

# Over The Rainbow

## Introduction
Welcome to Over the rainbow! Your go to, beginner-friendly website for all mental health rersources. This site hopes to be a starting point for anyone beginning the journey into mental  wellness; whether they are seeking treatments options,  infromation about current research & campaigns or wanting to get invovled in fundraising, over the rainbow aims to be the hub of all this current information in a beginner-friendly format. 

![Responsice Mockup](https://github.com/lucyrush/readme-template/blob/master/media/love_running_mockup.png)

## Features 

In this section, you should go over the different parts of your project, and describe each in a sentence or so. You will need to explain what value each of the features provides for the user, focusing on who this website is for, what it is that they want to achieve and how your project is the best way to help them achieve these things.

### Existing Features

- __Navigation Bar__

  - Featured on the homepage and contact us pages, the full responsive navigation bar includes links to the website text [logo] which when clicked returns the user back to the landing page, a direct Home page link, a contact us page and a guidance toggle link - which contains links directly to informative pages on Mind.org (Introduction to Mental Health, factors which may be impacting mental health and then a directro of currntly available treatment options). This navigation layout is identical on both the homepage and contact us page to allow for easy navigation.
  - I opted for a neutral, natural color scheme, in order to not overwhelm the users with bright colors or overwhelming information. 

![Nav Bar](/docs/screenshots/navbar.png)

- The dropdown button on the navbar was created using Bootstrap v5 Dropdowns (https://getbootstrap.com/docs/5.3/components/dropdowns/)

![Dropdown Nav Bar](docs/screenshots/nav-dropdown.png)

- __The landing page image__

  - The landing includes a photograph of a woman with text overlay to allow the user to see exactly what information this website applies to. Below the text I've included an 'Urgent Help?' button to immedietly offer a link to urgent support should they need it (Samaritans website). 
  

![Landing Page](/docs/screenshots/hero-image.png)

__Quote Section__
- Inspired by the official Mind.org website, I also included a quote section as an optical breakpoint/separation between the hero section and the included cards containing information and linkns to other resources/pages.
- This was created using Bootstrap v5 typography [blockquotes] (https://getbootstrap.com/docs/5.3/content/typography/#blockquotes)

![quote](/docs/screenshots/quote.png)

__Advice Cards__
- Using Bootstrap v5 card design components (https://getbootstrap.com/docs/5.3/components/card/), I opted for a simpler design [plain white box with text only] due to the hero image already creating enough visual representation and color for the landing page - any more would be slightly too overwhelming for users, particularly those with sensitivity.
- I did alter the link buttons to be icons rather than text to 1. add creativity to the page and 2. reduce the amount of text within the cards from making it look cluttered. Utilizing a simpler, lined design icon (airplane icon from Font Awesome) remains as a clear, explicit icon encouraging users to click it without using block-like buttons.

![card](/docs/screenshots/homepage-cards.png)

- __The Footer__ 

  - The footer section includes links to the relevant social media sites for 'Over The Rainbow'. The links will open to a new tab to allow easy navigation for the user and icons (used from font awesome) reflect the associated social media logo, ensuring easy navigation. 

![Footer](/docs/screenshots/footer.png)






### Features Left to Implement

- Another feature idea

## Testing 

Testing and validation of this website was carried out throughout the course of the project.

This included regular debugging and testing using the Dev Tools provided within Chrome Browser, utilizing Copilot & Perplexity.ai alongside using validation testing to address any code lines which needed fixing.


### Validator Testing 

- HTML
  - No errors were returned when passing my code through the official W3C validator(https://validator.w3.org/nu/?showsource=yes&doc=https%3A%2F%2Fmajak02.github.io%2FOver-The-Rainbow%2F#l72c36)
 
![W3C validation](/docs/screenshots/validation.png)
  
- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fvalidator.w3.org%2Fnu%2F%3Fdoc%3Dhttps%253A%252F%252Fcode-institute-org.github.io%252Flove-running-2.0%252Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en#css)

### Unfixed Bugs

This project expereinced some unresolved bugs, including the navbar dropdown button ('Guidance') and the hero image on the landing page. 

- Navigation Dropdown
  The navigation dropdown

## Deployment

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub) 

- The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the GitHub repository, navigate to the Settings tab 
  - From the source section drop-down menu, select the Master Branch
  - Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment. 

The live link can be found here - https://code-institute-org.github.io/love-running-2.0/index.html 


## Credits 

In this section you need to reference where you got your content, media and extra help from. It is common practice to use code from other repositories and tutorials, however, it is important to be very specific about these sources to avoid plagiarism. 

You can break the credits section up into Content and Media, depending on what you have included in your project. 

### Content 

- The text for the Home page was taken from Wikipedia Article A
- Instructions on how to implement form validation on the Sign Up page was taken from [Specific YouTube Tutorial](https://www.youtube.com/)
- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)

### Media

- The photos used on the home and sign up page are from This Open Source site
- The images used for the gallery page were taken from this other open source site


Congratulations on completing your Readme, you have made another big stride in the direction of being a developer! 

## Other General Project Advice

Below you will find a couple of extra tips that may be helpful when completing your project. Remember that each of these projects will become part of your final portfolio so it’s important to allow enough time to showcase your best work! 

- One of the most basic elements of keeping a healthy commit history is with the commit message. When getting started with your project, read through [this article](https://chris.beams.io/posts/git-commit/) by Chris Beams on How to Write  a Git Commit Message 
  - Make sure to keep the messages in the imperative mood 

- When naming the files in your project directory, make sure to consider meaningful naming of files, point to specific names and sections of content.
  - For example, instead of naming an image used ‘image1.png’ consider naming it ‘landing_page_img.png’. This will ensure that there are clear file paths kept. 

- Do some extra research on good and bad coding practices, there are a handful of useful articles to read, consider reviewing the following list when getting started:
  - [Writing Your Best Code](https://learn.shayhowe.com/html-css/writing-your-best-code/)
  - [HTML & CSS Coding Best Practices](https://medium.com/@inceptiondj.info/html-css-coding-best-practice-fadb9870a00f)
  - [Google HTML/CSS Style Guide](https://google.github.io/styleguide/htmlcssguide.html#General)

Getting started with your Portfolio Projects can be daunting, planning your project can make it a lot easier to tackle, take small steps to reach the final outcome and enjoy the process! 

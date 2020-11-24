# personal-website-starter

### Use this repo to kick start your personal website!
This repo is a template you can easily clone, make some updates to and, deploy with [github pages](https://pages.github.com/). 
### [Check out the live site!](https://ianballard.github.io/personal-website-starter/)

Github Pages use an SSG (static site generator) called [jekyll](https://jekyllrb.com/). SSGs make it very easy to create static sites. 

### Prerequisites
1. [jekyll](https://jekyllrb.com/docs/)
    - Install all [jekyll prerequisites](https://jekyllrb.com/docs/#prerequisites)
    - In your terminal, run `gem install jekyll bundler`
    

### Get your own personal website up within a few minutes

1. Click the "Use this template" button
2. Enter the Repository name of your choosing. 
    - **Note** If you want the website to be "your_username".github.io, then the repo name needs to be "your_username".github.io
3. Clone your new repo locally
4. Build and serve the project locally
    - At the root of the project, use this command to start the project locally with tracing and hot reloads enabled
        - `bundle exec jekyll serve --trace --livereload`
    - In your browser navigate to localhost:4000
    - You will be able to see the template and any subsequent changes you make
4. Open the project and navigate to /index.md
    - Update the title to your website title (ie. your full name, or something along those lines)
    - Update the author to your name
    - Update the description of the website
3. Navigate to the _data directory
    - In about.yml write a few sentences/ paragraphs about yourself
    - In contact.yml update the fields with your own usernames, email, and github repo
    - In projects.yml list out your most relevant projects and work you are most proud of
    - In skills.yml talk about some relevant things that you are good at.
        - If you have any certifications you can list them out as well
    - If you have any testimonials, add them in testimonials.yml
4. Update the splash screen/ hero image (optional)
    - Add a high resolution landscape picture to the /assets/img directory
    - Navigate to _includes/intro.html
        - Update the background url defined on line 6; currently set to './assets/img/hero.svg'
5. Push your changes
6. Publish your website on Github Pages
    - Go to your repository on GitHub
    - Navigate to the repository Settings > Options
    - Scroll down to the section titled "GitHub Pages"
    - Choose the source branch (default is master) and click save
    - After a few minutes your website should be deployed!


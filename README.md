# dumbo25.github.io
## Home Automation Projects

Draft

I am trying to figure out how to port [my Home Automation website](https://sites.google.com/site/cartwrightraspberrypiprojects/home) from Google Sites to github
* I can either try to make my Google Sites website as responsive as it allows, which will disappointing and take a lot of work, or
* I can migrate the site to github pages

I'd like to use [Apple's uikit](https://developer.apple.com/documentation/uikit) as the css. Import raw github files from uikit, or use built in theme.

## Github Pages Setup
* Create github account, or use the one you have
* Download [GitHub for Mac](http://mac.github.com/)
  * Move to Applications
  * Keep in Dock
* Create a repository called your-username.github.io. For me, it is dumbo25.github.io.
  * Create a readme.md 
  * Create a new file called index.html
* For the repository, click on settings icon and scroll down to Git Hub pages and follow the link
  * You should see something like:
    * Your site is published at https://dumbo25.github.io/
  * Do not select a theme: Settings, Pages, Theme Chooser
    * Initially, I chose Architect
    * However, [Front Matter](https://jekyllrb.com/docs/step-by-step/03-front-matter/) needs to be added to the site and the tags need to be edited. 
    * I prefer to just use the css provided by UIkit
    * Delete Github Pages Theme by deleting this file, _config.yml, from the repository
* Wait a few minutes between commits to see the changes
  * To see this site, open a browser and enter: https://dumbo25.github.io/

Reference: [Khan Academy](https://www.khanacademy.org/computing/computer-programming/html-css/web-development-tools/a/hosting-your-website-on-github)

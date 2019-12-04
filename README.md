# JKWilkerson.github.io
Sandbox website for projects and documentation and general tinkering

## To do
- Go through *"Getting Started"* work with GitHub Pages and Silex
- Add/link to Silex (template with any minor change should load as .io page)
- Add Netlify and headless CMS, if possible with Silex

## Resources
[Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

[GitHub Pages docs](https://help.github.com/en/github/working-with-github-pages)

[Silex - Publishing and Releasing Your Website](https://github.com/silexlabs/Silex/wiki/Publishing-and-Releasing-Your-Website) (could use some editing/screenshots/expansion as well)


### Documentation
This Silex getting started page could use a lot of work / copyediting / proofreading / adding sections and screenshots / (reorg, if there's a more in-depth guide it's linking to) [here](https://github.com/silexlabs/Silex/wiki/Getting-Started-With-Silex-Website-Builder)
- it only has a Dropbox explanation for image uploads/storage (can I use both GH Pages and Dropbox then?)- add others?

There is nothing for the page on hosting using GitHub Pages
- After correcting other, smaller issues, why not just do an entire guide/procedure on [this](https://github.com/silexlabs/Silex/wiki/host-a-website-on-github-pages)?


## About GitHub Pages

Using with Jekyll ["About GitHub Pages and Jekyll."](https://help.github.com/en/articles/about-github-pages-and-jekyll)

You can **add more pages** to your site by creating more new files.
Each file will be available on your site in the same directory structure as your publishing source.

For example, if the publishing source for your project site is the `gh-pages` branch,
and you create a new file called `/about/contact-us.md` on the `gh-pages` branch,
the file will be available at `https://<user>.github.io/<repository>/about/contact-us.md`


## Notes and Additions to site
Here's how Silex puts multiple HTML pages in one using [JQuery](https://github.com/silexlabs/Silex/wiki/Silex-and-Javascript#page-events)
https://github.com/anaibol/awesome-serverless




## GitHub Notes for Later

- GitHub Pages will use Jekyll to build your site by default. If you want to use a static site generator other than Jekyll, disable the Jekyll build process by creating an empty file called `.nojekyll` in the root of your publishing source, then follow your static site generator's instructions to build your site locally.
- GitHub Pages does not support server-side languages such as PHP, Ruby, or Python.
- GitHub Pages sites are subject to the following usage limits:

- GitHub Pages source repositories have a recommended limit of 1GB. For more information, see ["What is my disk quota?"](https://help.github.com/en/articles/what-is-my-disk-quota/#file-and-repository-size-limitations)
What is my disk quota? - GitHub Help
- GitHub doesn't have any set user disk quotas. We try to provide abundant storage for all Git repositories, although there are hard limits for file and repository sizes. Keeping repositories small ensures that our servers are fast and downloads are quick for our users.
help.github.com
-- Published GitHub Pages sites may be no larger than 1 GB.
-- GitHub Pages sites have a soft bandwidth limit of 100GB per month.
-- GitHub Pages sites have a soft limit of 10 builds per hour.

## Contributions for Silex To Do
- Lots of the docs are outdated or need editing
- Can add a lot of screenshots- old UI in many of the pages

## Project Notes for Later
- Investigate submodules and their uses


# Secondary SSG project with Hugo
So there is only one user site allowed per account, and that is the Silex one currently. I want to create another site using the most up-to-date tools and apps, in order to make a site for documentation that I can use for APIs and other projects. 

The idea is to:
- Use a Git project repo (distinction [here](https://help.github.com/en/github/working-with-github-pages/about-github-pages)
- Use Hugo as my SSG and a Hugo template called DocDock that is used for knowledge bases
- Use Netflify to deploy
- Use forestry.io (headless CMS) to create a WYSIWIG editor for the site and make it simple to manage




### Fun Facts
> A MIME type is a header that a server sends to a browser, providing information about the nature and format of the files the browser requested. GitHub Pages supports more than 750 MIME types across thousands of file extensions.
[I'm thinking about the MIME type added to epubs- open one up again]





